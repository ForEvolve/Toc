# Table of content

This repo is the table of content of the `ForEvolve` projects.

## NuGet

**[comming soon with v1.0.0]**

All released packages are available on NuGet.org.

To reference all application packages, you can `Install-Package ForEvolve.App`.
You can also reference packages individually, like `Install-Package ForEvolve.AspNetCore.Localization`.

### Prerelease packages

All prerelease packages are available in the following MyGet feed: [NuGet V3 feed](https://www.myget.org/F/forevolve/api/v3/index.json).

You can see the `*-upsilon-*` packages as alpha or pre-alpha but upsilon is more original and fun imho. Until it cause too much confusion (if it does).

#### How to use a custom NuGet feed?

I wrote [How to use a custom NuGet feed in Visual Studio 2017](http://www.forevolve.com/en/articles/2017/08/06/how-to-use-a-custom-nuget-feed-in-visual-studio-2017/) article to help get started with the framwork (or any custom feed for that matter).

> MyGet feed URI: https://www.myget.org/F/forevolve/api/v3/index.json

## .NET Standard Projects

### ForEvolve MetaPackages (.Net Core Framework)

[![ForEvolve VSTS Build Status](https://forevolve.visualstudio.com/_apis/public/build/definitions/b800edd0-96da-46c1-a089-06a4466e62d9/17/badge)](https://www.myget.org/F/forevolve/api/v3/index.json)

[ForEvolve MetaPackages](https://github.com/ForEvolve/MetaPackages) references the other ForEvolve packages. The test helpers (for unit, integration or ... testing) are not included in the MetaPackage since it is not needed for application code.

This package allows users to use the ForEvolve toolbox without knowing the packages division. If you prefer to reference packages individually, you can do it to; its up to you.

### ForEvolve Framework

![VSTS build build status](https://forevolve.visualstudio.com/_apis/public/build/definitions/fdc5922a-3dc1-4827-97a6-0f622b2fd497/26/badge)

[ForEvolve Framework](https://github.com/ForEvolve/ForEvolve-Framework) is the main repository that contain multiple projects like AspNetCore, ApplicationInsights and Azure helpers, and DynamicInternalServerError. That project is a toolbox to boost productivity, I've centralized boilerplate code and utilities there.

Please visit the project repository for more information.

### AspNetCore Localization

[![forevolve MyGet Build Status](https://www.myget.org/BuildSource/Badge/forevolve?identifier=b9aba5cc-96df-42d0-bf33-ed89456a6fdf)](https://www.myget.org/F/forevolve/api/v3/index.json)

[AspNetCore Localization](https://github.com/ForEvolve/ForEvolve.AspNetCore.Localization) allows you to localized Asp.Net Core 2 validation attributes in a few line of code.

Supported languages are `English` and `French`, I only know those two languages so I can't translate into more. If you can translate messages into another language, feel free to contribute.

Please visit the project repository for more information.

## Other repositories

- [Visual Studio snippets](https://github.com/ForEvolve/vs-snippets) - this project contains some C# and Javascript snippets like "guard clause" (updated for VS2017) and "aaa comments" (arrage, act, assert).
- [Bootstrap 4.1 dark theme](https://github.com/ForEvolve/bootstrap-dark) is a Bootstrap 4.1 dark theme.
- [Bootstrap 4.1 dark theme docs](https://github.com/ForEvolve/bootstrap-dark-docs) loads the `bootstrap-dark` theme in a tweaked Bootstrap documentation website to help validate use-cases.

## How to contribute

First, thank you for your interest and please read [Contributing to ForEvolve open source projects](https://github.com/ForEvolve/Toc/blob/master/CONTRIBUTING.md) for more information.

### Contributor Covenant Code of Conduct

Also, please read the [Contributor Covenant Code of Conduct](https://github.com/ForEvolve/Toc/blob/master/CODE_OF_CONDUCT.md) that applies to all ForEvolve repositories.

### Templates

If possible, please use one of the following templates when opening an issue:

- [Bug report](https://github.com/ForEvolve/Toc/blob/master/.github/ISSUE_TEMPLATE/bug_report.md)
- [Feature request](https://github.com/ForEvolve/Toc/blob/master/.github/ISSUE_TEMPLATE/feature_request.md)
