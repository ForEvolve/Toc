# Toc
Table of content of `ForEvolve.*` projects.

## NuGet
All `ForEvolve.*` packages are available in my MyGet [NuGet V3 feed URL](https://www.myget.org/F/forevolve/api/v3/index.json) source. 

* The `*-upsilon-*` packages are open source prerelease packages (you can also call them alpha but upsilon is way more fun).
* The `*-omnicron-*` packages are not yet open sourced prerelease packages, but temporarily there for use. These will disappear and be replaced with an `*-upsilon-*` version once I am done organizing my ".NET core helpers" projet.

## Projects
### DynamicInternalServerError
[![forevolve MyGet Build Status](https://www.myget.org/BuildSource/Badge/forevolve?identifier=a6353d8a-cc43-4e21-b226-c2ca715205ab)](https://www.myget.org/) 

[DynamicInternalServerError](https://github.com/ForEvolve/DynamicInternalServerError) is a middleware that convert `Exception` to json errors automatically; it also convert `BadRequest(ModelState)` action results to the same json format and is pluggable in Swagger [Swashbuckle.AspNetCore](https://github.com/domaindrivendev/Swashbuckle.AspNetCore).

### Other
More to come...

## Obsolete projects

* [.NET core helpers](https://github.com/ForEvolve/dotnetcore) - this project is getting revamped!
