# DevOps.Code.DataAccess.Metapackages.ApiControllers

[![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst/devops-code-dataaccess-metapackages-apicontrollers.svg?label=AppVeyor&style=for-the-badge)](https://ci.appveyor.com/project/cdorst/devops-code-dataaccess-metapackages-apicontrollers)
[![NuGet package status](https://img.shields.io/nuget/v/CDorst.DevOps.Code.DataAccess.Metapackages.ApiControllers.svg?label=NuGet&style=for-the-badge)](https://www.nuget.org/packages/CDorst.DevOps.Code.DataAccess.Metapackages.ApiControllers)

## Description

Metapackage for entity API controllers

## Environment Variables

This project depends on this environment variable:

Name | Description
---- | -----------
`LOCAL_NUGET_SOURCE_PATH` | *Required* to build the project, but not required during code execution. This is set to `c:\projects\nuget\cache` on the build server. On your development machine, set this to an empty, existing path. `dotnet restore` will inspect this folder prior to checking NuGet.

## Dependencies

Name | Status
---- | ------
Microsoft.AspNetCore.Mvc.Core | [![NuGet package status](https://img.shields.io/nuget/v/Microsoft.AspNetCore.Mvc.Core.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/Microsoft.AspNetCore.Mvc.Core)
Microsoft.Extensions.Logging.Abstractions | [![NuGet package status](https://img.shields.io/nuget/v/Microsoft.Extensions.Logging.Abstractions.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/Microsoft.Extensions.Logging.Abstractions)
[CDorst.DevOps.Code.DataAccess.Interfaces.Repository](https://github.com/CDorst/DevOps.Code.DataAccess.Interfaces.Repository) | [![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst/devops-code-dataaccess-interfaces-repository.svg?label=AppVeyor&style=flat-square)](https://ci.appveyor.com/project/cdorst/devops-code-dataaccess-interfaces-repository) [![NuGet package status](https://img.shields.io/nuget/v/CDorst.DevOps.Code.DataAccess.Interfaces.Repository.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/CDorst.DevOps.Code.DataAccess.Interfaces.Repository)

## Dependents

The projects below use this repository as a direct dependency.

Name | Status
---- | ------
[Entities.FooBars.ApiController](https://github.com/CDorst/Entities.FooBars.ApiController) | [![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst/entities-foobars-apicontroller.svg?label=AppVeyor&style=flat-square)](https://ci.appveyor.com/project/cdorst/entities-foobars-apicontroller) [![NuGet package status](https://img.shields.io/nuget/v/CDorst.Entities.FooBars.ApiController.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/CDorst.Entities.FooBars.ApiController)
[Entities.StaticFooBars.ApiController](https://github.com/CDorst/Entities.StaticFooBars.ApiController) | [![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst/entities-staticfoobars-apicontroller.svg?label=AppVeyor&style=flat-square)](https://ci.appveyor.com/project/cdorst/entities-staticfoobars-apicontroller) [![NuGet package status](https://img.shields.io/nuget/v/CDorst.Entities.StaticFooBars.ApiController.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/CDorst.Entities.StaticFooBars.ApiController)

## NuGet


This project is published as a NuGet package at [https://www.nuget.org/packages/CDorst.DevOps.Code.DataAccess.Metapackages.ApiControllers](https://www.nuget.org/packages/CDorst.DevOps.Code.DataAccess.Metapackages.ApiControllers)

## Version

1.0.0

## Metaproject

DevOps.Code.DataAccess.Metapackages.ApiControllers is maintained by robots and exists because of a declarative template metaproject. View the metaproject's component directory at [https://github.com/CDorst/Project.Index](https://github.com/CDorst/Project.Index)

