# resources

#### asp.net community stand up links
* [Feb 20, 2018 Razor UI in class libraries](https://www.one-tab.com/page/PiTdahJmTn65szGajXoqwA)


#### ASP.NET blog posts
* [Is the repository pattern useful with Entity Framework Core?](https://www.thereformedprogrammer.net/is-the-repository-pattern-useful-with-entity-framework-core/)
* [Adding ASP.NET Core Identity to an existing project](https://hanson.io/bootstrapping-asp-net-core-week-4/)
* [OpenID Connect Debugger](https://www.recaffeinate.co/post/introducing-openid-connect-debugger/)
* [ASP.NET Identity w/o Entity Framework](https://markjohnson.io/articles/asp-net-core-identity-without-entity-framework/)
* [Debugging ASP.NET Source Code](https://www.stevejgordon.co.uk/debugging-asp-net-core-2-source)
* [The line ending in the following file are not consistent](http://www.adamtuliper.com/2015/10/stop-visual-studio-from-complaining.html)
* https://joonasw.net/view/creating-auth-scheme-in-aspnet-core-2
* https://learn-blazor.com
* [ADDING HTTP HEADERS TO IMPROVE SECURITY IN AN ASP.NET MVC CORE APPLICATION](https://damienbod.com/2018/02/08/adding-http-headers-to-improve-security-in-an-asp-net-mvc-core-application/)
* [ASP.NET Identity Series Part I](https://chsakell.com/2018/04/28/asp-net-core-identity-series-getting-started/?utm_campaign=Revue%20newsletter&utm_medium=Newsletter&utm_source=ASP.NET%20Weekly) 
* [ASP.NET Weekly](https://www.getrevue.co/profile/aspnetweekly)
* [Customizing Swagger UI](https://cpratt.co/customizing-swagger-ui-in-asp-net-core/)
* [Custom CORS Policy](https://social.technet.microsoft.com/wiki/contents/articles/51042.asp-net-core-2-0-applying-cors-policies.aspx)
* [ASPNET Core Swagger UI Authorization using IdentityServer4](https://www.scottbrady91.com/Identity-Server/ASPNET-Core-Swagger-UI-Authorization-using-IdentityServer4)

#### ASP.NET workshops
* [ASP.NET Core Authentication](https://github.com/blowdart/AspNetAuthenticationWorkshop)
* [ASP.NET Core Authorization](https://github.com/blowdart/AspNetAuthorizationWorkshop)
* [ASP.NET Core Application](https://www.jerriepelser.com/books/airport-explorer/basic/intro/)

#### angular
* [Augulary](https://augury.angular.io/)
* [compodoc](https://compodoc.github.io/compodoc/)
* [Http Requests with RxJs switchMap](https://hackernoon.com/using-rxjs-to-handle-http-requests-what-ive-learned-4640aaf4646c)
* [ng-conf 2018 videos](https://nitayneeman.com/posts/all-talks-from-ng-conf-2018/?utm_campaign=NG-Newsletter&utm_medium=email&utm_source=NG-Newsletter_250#angular-cdk-and-material-in-2018)
* [Angular In Depth Blog](https://blog.angularindepth.com)
* [CRUD Operations Using Angular HttpClient](http://www.dotnetcurry.com/angularjs/1438/http-client-angular)
* [3 common mistakes in RxJs](https://medium.com/@paynoattn/3-common-mistakes-i-see-people-use-in-rx-and-the-observable-pattern-ba55fee3d031)
* [Top 10 Angular Articles Of The Month](https://github.com/Mybridge/angular-articles)

#### GraphQL & REST Apis
* [GraphQL Asp.Net Sample Series](http://fiyazhasan.me/graphql-with-asp-net-core-part-ii-middleware/)
* [GraphQL, Asp.Net Core + EF](https://fullstackmark.com/post/17/building-a-graphql-api-with-aspnet-core-2-and-entity-framework-core)
* [Designing a Beautiful REST+JSON API](https://www.youtube.com/watch?v=5WXYw4J4QOU)
* [Phil Sturgeon](https://philsturgeon.uk/)
* [Nate Barbettini – API Throwdown: RPC vs REST vs GraphQL, Iterate 2018](https://www.youtube.com/watch?v=IvsANO0qZEg)
* [GraphQL Sample Project Instructions](https://medium.com/@shemseddine/setup-a-graphql-api-using-asp-net-core-79f1b88f6ad8)

#### my blog posts
* TO DO: ASP.Net Core Cookie Authentication in a Web Farm with DataProtection Middleware and Dapper

#### books
* [The Little ASP.NET Core Book](https://www.recaffeinate.co/book/)
* [csharp-smorgasbord](https://cdn.filipekberg.se/fekberg-blog/csharp-smorgasbord-free/Filip_Ekberg-CSharp_Smorgasbord.pdf)
* [http://goalkicker.com](http://goalkicker.com)
* [LINQ from Jon Skeet](https://codeblog.jonskeet.uk/category/edulinq/)
* [Free E Books from Github Repo](https://github.com/EbookFoundation/free-programming-books/blob/master/free-programming-books.md)

#### Tasks
- [ ] Check The [Morning Brew Blog](http://blog.cwa.me.uk/) posts every Friday for the week and make list of things to try from the links.

#### Issues
* How to configure custom.cshtml as default page in Razor Pages?

#### Github Auth Samples
* https://github.com/aspnet/AuthSamples

#### Community
* http://jakedawkins.com


#### MarkDown Shortcuts
0. [Microsoft Guide](https://docs.microsoft.com/en-us/vsts/collaborate/markdown-guidance)
#### Window Shortcuts
**File Explorer** 
- Open File Explorer = windows logo + E
- Alt + F4 --> Closes the File Explorer
- Alt+D --> Highlight address bar
- F4 --> Opens a drop-dwon list of folders in the address bar.

#### git tips & trics
 - To find parent branch of current branch - `git show-branch | grep '*' | grep -v "$(git rev-parse --abbrev-ref HEAD)" | head -n1 | sed 's/.*\[\(.*\)\].*/\1/' | sed 's/[\^~].*//'`
 
 #### vs code short cuts
 - To change a variable name and all its reference in the code use F2
 - ctrl + P to open up command pallette. You can search any file in the project with this.
 
 #### vs code plugins
 - Move TS --- to move files. It auto updates all references.
 - Bracket Pair Colorization 
 - GraphQL for VS Code
 - Prettier Code Formatter
 - TSLint

#### miscellaneous 
- webgraphviz
- [keyframes google chrome extension for animations CSS](https://www.youtube.com/watch?v=H598jXvQhLw)
- [Versioning REST Api Best Practices](https://stackoverflow.com/questions/389169/best-practices-for-api-versioning)

#### angular tips
 - To upgrade from angular 5 to angular 6 run ng update @angular/cli after running npm install npm install @angular/cli. This will rename angular-cli.json file to angular.json. You may have to try second time if it does not replace angular-cli.json with angular.json [source](http://www.talkingdotnet.com/upgrade-angular-5-app-angular-6-visual-studio-2017/)
 
#### CSS tips
- [adding font-face with custom fonts](https://coderwall.com/p/5vrdkg/google-fonts-using-fontface-in-your-css)
