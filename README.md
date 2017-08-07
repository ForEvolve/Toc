# Toc
Table of content of `ForEvolve.*` projects.

## NuGet
All `ForEvolve.*` packages are available in my MyGet [NuGet V3 feed URL](https://www.myget.org/F/forevolve/api/v3/index.json) source. 

The `*-upsilon-*` packages are open source prerelease packages (you can also call them alpha or pre-alpha but upsilon is way more fun).

### How to use a custom NuGet feed?
I wrote [How to use a custom NuGet feed in Visual Studio 2017](http://www.forevolve.com/en/articles/2017/08/06/how-to-use-a-custom-nuget-feed-in-visual-studio-2017/) article to help get started with the framwork.

> MyGet feed URI: https://www.myget.org/F/forevolve/api/v3/index.json

## ASP.NET Core Projects
### ForEvolve MetaPackages (.Net Core Framework)
VSTS: [![ForEvolve VSTS Build Status](https://forevolve.visualstudio.com/_apis/public/build/definitions/b800edd0-96da-46c1-a089-06a4466e62d9/17/badge)](https://www.myget.org/F/forevolve/api/v3/index.json)

[ForEvolve MetaPackages](https://github.com/ForEvolve/MetaPackages) simply reference the other ForEvolve .Net Core packages (all `ForEvolve .Net Core Framework` packages and both `DynamicInternalServerError` packages) 
It should be easier to use the ForEvolve Framework without knowing the packages division.
If you prefer fine-grained packages referencing, you can still do it.

### ForEvolve .Net Core Framework
[![forevolve MyGet Build Status](https://www.myget.org/BuildSource/Badge/forevolve?identifier=fbfabe8c-a7d7-4e60-9fbb-8d7627bc53d0)](https://www.myget.org/F/forevolve/api/v3/index.json)

[ForEvolve .Net Core Framework](https://github.com/ForEvolve/ForEvolve-Framework) is the main Framework that contain multiple projects like AspNetCore, ApplicationInsights and Azure helpers.

### DynamicInternalServerError
[![forevolve MyGet Build Status](https://www.myget.org/BuildSource/Badge/forevolve?identifier=a6353d8a-cc43-4e21-b226-c2ca715205ab)](https://www.myget.org/F/forevolve/api/v3/index.json) 

[DynamicInternalServerError](https://github.com/ForEvolve/DynamicInternalServerError) is a middleware that convert `Exception` to json errors automatically; it also convert `BadRequest(ModelState)` action results to the same json format and is pluggable in Swagger [Swashbuckle.AspNetCore](https://github.com/domaindrivendev/Swashbuckle.AspNetCore).

### Other
More to come...

### Obsolete projects

* [.NET core helpers](https://github.com/ForEvolve/dotnetcore) - this project is getting revamped and has been moved to [ForEvolve .Net Core Framework](https://github.com/ForEvolve/ForEvolve-Framework).

## Other repositories

* [Visual Studio snippets](https://github.com/ForEvolve/vs-snippets) - this project contains some C# and Javascript snippets like "guard clause" (updated for VS2017) and "aaa comments" (arrage, act, assert).
* [Postman test framework](https://github.com/ForEvolve/postman-tests-framework) - this project is a little Postman test framework to help avoid "messy-er" code. It allow to write test code like `myTarget.response.should.be.ok();` and `myTarget.response.should.be.fast();`.
