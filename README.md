# GladLive.PatchingService.ASP

GladLive is network session service comparable to Xboxlive or Steam. 

GladLive.PatchingService.ASP is a web scalable ASP.NET core patching webservice/web-api for the GladLive distributed network and preforms this role by providing:
  - Services Versioning details requests for the GladLive distributed network
  - Delivers Patching URLs/Data to clients
  - Vertically and horizontally scalable
  - Web and cloud ready

## GladLive Services

GladLive.ProxyLoadBalancer: https://github.com/GladLive/GladLive.ProxyLoadBalancer

GladLive.AuthService.ASP: https://github.com/GladLive/GladLive.AuthService.ASP

GladLive.AuthService.ASP: https://github.com/GladLive/GladLive.PatchingService.ASP

## Setup

To use this project you'll first need a couple of things:
  - Visual Studio 2015 RC 3
  - Dotnet Core VS Toooling
  - Dotnet Core SDK
  - Add Nuget Feed https://www.myget.org/F/hellokitty/api/v2 in VS (Options -> NuGet -> Package Sources)

## Builds

(CD will be setup in the future; will not be available on NuGet)

##Tests

#### Linux/Mono - Unit Tests
||Debug x86|Debug x64|Release x86|Release x64|
|:--:|:--:|:--:|:--:|:--:|:--:|
|**master**| N/A | N/A | N/A | [![Build Status](https://travis-ci.org/GladLive/GladLive.PatchingService.ASP.svg?branch=master)](https://travis-ci.org/GladLive/GladLive.PatchingService.ASP) |
|**dev**| N/A | N/A | N/A | [![Build Status](https://travis-ci.org/GladLive/GladLive.PatchingService.ASP.svg?branch=dev)](https://travis-ci.org/GladLive/GladLive.PatchingService.ASP)|

#### Windows - Unit Tests

(Done locally)

##Licensing

This project is licensed under the MIT license with the additional requirement of adding the GladLive splashscreen to your product.
