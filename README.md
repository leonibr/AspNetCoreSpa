

<<<<<<< HEAD
* [ASP.NET Core](http://www.dot.net/)
* [Entity Framework Core](https://docs.efproject.net/en/latest/)
    * Both Sql Server and Sql lite databases are supported (Check installation instrcutions for more details)
* [Angular](https://angular.io/)
* [Angular CLI](https://cli.angular.io/) (Only code scaffolding for now)
* [Webpack 2](https://webpack.github.io/)
* [Bootstrap 4](http://v4-alpha.getbootstrap.com/)
* [ng-bootstrap](https://ng-bootstrap.github.io/)
* [@ngx-translate](http://www.ngx-translate.com/)
* [Typescript 2](http://www.typescriptlang.org/)
* [SASS](http://sass-lang.com/) support
* [Best practices](https://angular.io/docs/ts/latest/guide/style-guide.html) in file and application organization for Angular.
* Testing Angular code with [Jasmine](http://jasmine.github.io/) and [Karma](https://karma-runner.github.io/0.13/index.html).
* End-to-end Angular code using [Protractor](http://www.protractortest.org).
* [Istanbul](https://github.com/gotwarlost/istanbul) for test coverage
  * with [Remap Istanbul](https://github.com/SitePen/remap-istanbul) for remapping Javascript to TypeScript coverage
* [HMR](https://webpack.github.io/docs/hot-module-replacement.html) (Hot Module Replacement) with Webpack
* Webpack DLL support for fast rebuilds (~ < 0.5 second), depends upon machine performance.
* [Compodoc](https://compodoc.github.io/compodoc/) for Angular documentation
* [Server](https://github.com/aspnet/dotnet-watch) and [client](https://webpack.github.io/docs/hot-module-replacement.html) watches
* Login and Registration functionality using [Asp.Net Identity & JWT](https://docs.asp.net/en/latest/security/authentication/identity.html)
* Token based authentication using [Openiddict](https://github.com/openiddict/openiddict-core)
     * Get public key acess using: http://localhost:5000/.well-known/jwks
* Extensible User/Role identity implementation
* Various social login support, Follow [this](https://github.com/asadsahi/AspNetCoreSpa/wiki/Social-Login-Setup) wiki page to see how it will work.
* Lazy loading with pre loading all modules for fast navigation.
* [Angular dynamic forms](https://angular.io/docs/ts/latest/cookbook/dynamic-form.html) for reusability and to keep html code DRY.
* [Serilog](https://serilog.net/) with [Seq](https://getseq.net/) support to manage structured logging.
* [Swagger](http://swagger.io/) as Api explorer (Visit url **http://localhost:5000/swagger** after running the application). More [details](https://github.com/domaindrivendev/Swashbuckle.AspNetCore)
 
## Pre-requisites
=======
## Modified from Original Repo
>>>>>>> Changed Readme to reflect changes from original repo

* Updated all dependencies to the latest
* Added PostgreSQL support - Is the default now
    * Update your connection string at `appsettings.json`
    * To use SQL Server just uncomment `//options.UseSqlServer{...}`  at `[ProjectFolder]Server\Extensions\ServiceCollectionExtensions.cs (line 150)`
    * To use SQLLite set `useSqLite` to `true` at `appsettings.json`


