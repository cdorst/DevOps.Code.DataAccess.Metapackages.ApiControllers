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
Microsoft.AspNetCore.JsonPatch | [![NuGet package status](https://img.shields.io/nuget/v/Microsoft.AspNetCore.JsonPatch.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/Microsoft.AspNetCore.JsonPatch)
Microsoft.Extensions.Logging.Abstractions | [![NuGet package status](https://img.shields.io/nuget/v/Microsoft.Extensions.Logging.Abstractions.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/Microsoft.Extensions.Logging.Abstractions)
[CDorst.DevOps.Code.DataAccess.Interfaces.Repository](https://github.com/CDorst/DevOps.Code.DataAccess.Interfaces.Repository) | [![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst/devops-code-dataaccess-interfaces-repository.svg?label=AppVeyor&style=flat-square)](https://ci.appveyor.com/project/cdorst/devops-code-dataaccess-interfaces-repository) [![NuGet package status](https://img.shields.io/nuget/v/CDorst.DevOps.Code.DataAccess.Interfaces.Repository.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/CDorst.DevOps.Code.DataAccess.Interfaces.Repository)

## Dependents

The projects below use this repository as a direct dependency.

Name | Status
---- | ------
[Addresses.States.ApiController](https://github.com/CDorst/Addresses.States.ApiController) | [![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst/addresses-states-apicontroller.svg?label=AppVeyor&style=flat-square)](https://ci.appveyor.com/project/cdorst/addresses-states-apicontroller) [![NuGet package status](https://img.shields.io/nuget/v/CDorst.Addresses.States.ApiController.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/CDorst.Addresses.States.ApiController)
[Addresses.ZipCodes.ApiController](https://github.com/CDorst/Addresses.ZipCodes.ApiController) | [![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst/addresses-zipcodes-apicontroller.svg?label=AppVeyor&style=flat-square)](https://ci.appveyor.com/project/cdorst/addresses-zipcodes-apicontroller) [![NuGet package status](https://img.shields.io/nuget/v/CDorst.Addresses.ZipCodes.ApiController.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/CDorst.Addresses.ZipCodes.ApiController)
[Addresses.StreetAddressLines.ApiController](https://github.com/CDorst/Addresses.StreetAddressLines.ApiController) | [![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst/addresses-streetaddresslines-apicontroller.svg?label=AppVeyor&style=flat-square)](https://ci.appveyor.com/project/cdorst/addresses-streetaddresslines-apicontroller) [![NuGet package status](https://img.shields.io/nuget/v/CDorst.Addresses.StreetAddressLines.ApiController.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/CDorst.Addresses.StreetAddressLines.ApiController)
[Addresses.StreetAddresses.ApiController](https://github.com/CDorst/Addresses.StreetAddresses.ApiController) | [![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst/addresses-streetaddresses-apicontroller.svg?label=AppVeyor&style=flat-square)](https://ci.appveyor.com/project/cdorst/addresses-streetaddresses-apicontroller) [![NuGet package status](https://img.shields.io/nuget/v/CDorst.Addresses.StreetAddresses.ApiController.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/CDorst.Addresses.StreetAddresses.ApiController)
[Addresses.Cities.ApiController](https://github.com/CDorst/Addresses.Cities.ApiController) | [![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst/addresses-cities-apicontroller.svg?label=AppVeyor&style=flat-square)](https://ci.appveyor.com/project/cdorst/addresses-cities-apicontroller) [![NuGet package status](https://img.shields.io/nuget/v/CDorst.Addresses.Cities.ApiController.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/CDorst.Addresses.Cities.ApiController)
[Addresses.StateCities.ApiController](https://github.com/CDorst/Addresses.StateCities.ApiController) | [![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst/addresses-statecities-apicontroller.svg?label=AppVeyor&style=flat-square)](https://ci.appveyor.com/project/cdorst/addresses-statecities-apicontroller) [![NuGet package status](https://img.shields.io/nuget/v/CDorst.Addresses.StateCities.ApiController.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/CDorst.Addresses.StateCities.ApiController)
[Addresses.StateCityZips.ApiController](https://github.com/CDorst/Addresses.StateCityZips.ApiController) | [![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst/addresses-statecityzips-apicontroller.svg?label=AppVeyor&style=flat-square)](https://ci.appveyor.com/project/cdorst/addresses-statecityzips-apicontroller) [![NuGet package status](https://img.shields.io/nuget/v/CDorst.Addresses.StateCityZips.ApiController.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/CDorst.Addresses.StateCityZips.ApiController)
[Addresses.Addresses.ApiController](https://github.com/CDorst/Addresses.Addresses.ApiController) | [![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst/addresses-addresses-apicontroller.svg?label=AppVeyor&style=flat-square)](https://ci.appveyor.com/project/cdorst/addresses-addresses-apicontroller) [![NuGet package status](https://img.shields.io/nuget/v/CDorst.Addresses.Addresses.ApiController.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/CDorst.Addresses.Addresses.ApiController)
[Entities.FooBars.ApiController](https://github.com/CDorst/Entities.FooBars.ApiController) | [![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst/entities-foobars-apicontroller.svg?label=AppVeyor&style=flat-square)](https://ci.appveyor.com/project/cdorst/entities-foobars-apicontroller) [![NuGet package status](https://img.shields.io/nuget/v/CDorst.Entities.FooBars.ApiController.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/CDorst.Entities.FooBars.ApiController)
[Entities.StaticFooBars.ApiController](https://github.com/CDorst/Entities.StaticFooBars.ApiController) | [![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst/entities-staticfoobars-apicontroller.svg?label=AppVeyor&style=flat-square)](https://ci.appveyor.com/project/cdorst/entities-staticfoobars-apicontroller) [![NuGet package status](https://img.shields.io/nuget/v/CDorst.Entities.StaticFooBars.ApiController.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/CDorst.Entities.StaticFooBars.ApiController)

## NuGet


This project is published as a NuGet package at [https://www.nuget.org/packages/CDorst.DevOps.Code.DataAccess.Metapackages.ApiControllers](https://www.nuget.org/packages/CDorst.DevOps.Code.DataAccess.Metapackages.ApiControllers)

## Version

1.0.1

## Metaproject

DevOps.Code.DataAccess.Metapackages.ApiControllers is maintained by robots and exists because of a declarative template metaproject. View the metaproject's component directory at [https://github.com/CDorst/Project.Index](https://github.com/CDorst/Project.Index)

