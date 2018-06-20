# Toc

Table of content of `ForEvolve.*` projects.

## NuGet

All release packages are available on NuGet.org, so you can type `Install-Package ForEvolve.All` or `Install-Package ForEvolve.AspNetCore.Localization` to install those packages.

### Prerelease packages

All prerelease packages are available in my MyGet [NuGet V3 feed](https://www.myget.org/F/forevolve/api/v3/index.json).

You can see the `*-upsilon-*` packages as alpha or pre-alpha but upsilon is more original and fun imho.

#### How to use a custom NuGet feed?

I wrote [How to use a custom NuGet feed in Visual Studio 2017](http://www.forevolve.com/en/articles/2017/08/06/how-to-use-a-custom-nuget-feed-in-visual-studio-2017/) article to help get started with the framwork.

> MyGet feed URI: https://www.myget.org/F/forevolve/api/v3/index.json

## How to contribute

First, tank you for your interest and please read [Contributing to ForEvolve open source projects](CONTRIBUTING.md) for more information.

### Contributor Covenant Code of Conduct

Also, please read the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md) that applies to all ForEvolve repositories.

### Templates

If possible, please use one of the following templates when opening an issue:

- [Bug report](.github/ISSUE_TEMPLATE/bug_report.md)
- [Feature request](.github/ISSUE_TEMPLATE/feature_request.md)

## .NET Standard Projects

### ForEvolve MetaPackages (.Net Core Framework)

[![ForEvolve VSTS Build Status](https://forevolve.visualstudio.com/_apis/public/build/definitions/b800edd0-96da-46c1-a089-06a4466e62d9/17/badge)](https://www.myget.org/F/forevolve/api/v3/index.json)

[ForEvolve MetaPackages](https://github.com/ForEvolve/MetaPackages) simply reference the other ForEvolve .Net Core packages (all `ForEvolve .Net Core Framework` packages and both `DynamicInternalServerError` packages)
It should be easier to use the ForEvolve Framework without knowing the packages division.
If you prefer fine-grained packages referencing, you can still do it.

### ForEvolve .Net Core Framework

![VSTS build build status](https://forevolve.visualstudio.com/_apis/public/build/definitions/fdc5922a-3dc1-4827-97a6-0f622b2fd497/26/badge)

[ForEvolve .Net Core Framework](https://github.com/ForEvolve/ForEvolve-Framework) is the main Framework that contain multiple projects like AspNetCore, ApplicationInsights, Azure helpers and DynamicInternalServerError.

### AspNetCore Localization

[![forevolve MyGet Build Status](https://www.myget.org/BuildSource/Badge/forevolve?identifier=b9aba5cc-96df-42d0-bf33-ed89456a6fdf)](https://www.myget.org/F/forevolve/api/v3/index.json)

[AspNetCore Localization](https://github.com/ForEvolve/ForEvolve.AspNetCore.Localization) allows you to enable localization of Asp.Net Core 2.0 applications, especially the validation attributes, in a few line of code. Supported languages are `English` and `French`, but contributions are welcome (I only know those two languages so I can't translate into more).

### Other

More to come...

## Other repositories

- [Visual Studio snippets](https://github.com/ForEvolve/vs-snippets) - this project contains some C# and Javascript snippets like "guard clause" (updated for VS2017) and "aaa comments" (arrage, act, assert).
