

## Modified from Original Repo

* Updated all dependencies to the latest
* Added PostgreSQL support - Is the default now
    * Update your connection string at `appsettings.json`
    * To use SQL Server just uncomment `//options.UseSqlServer{...}`  at `[ProjectFolder]Server\Extensions\ServiceCollectionExtensions.cs (line 150)`
    * To use SQLLite set `useSqLite` to `true` at `appsettings.json`


