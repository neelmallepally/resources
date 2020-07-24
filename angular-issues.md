@ViewChild undefined with ngIf

```html
<div *ngIf="loadingComplete$ | async; else loading>
  <child> </child>
</div>
<ng-template #loading> Loading....</ng-template>
```
Child Component has some method
```js
Component({})
export class ChildComponent {

  next:void{
    // statements
  }
}
```

ParentComponent.ts

####Not working:
ViewChild(ChildComponent, {static: true}) child: ChildComponent;
child.next(); in the parent component will result in next method not available on undefined
####Fix:
ViewChild(ChildComponent, {static: false}) child: ChildComponent;

