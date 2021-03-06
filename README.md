# .Net Core Study 
>ASP.NET Core is a new open-source and cross-platofrm framework for buidling modern cloud based internet connected applications, such as web apps, IoT apps and mobile backends. 

## .NET CORE
* Cross platofrm version of .NET
* Flexible deployment options
* Subset of the Full .NET Framework
* Only supports a single app model: console apps
* Other app models can be built on top of it (ASP.net Core for instance)
  
## .NET CLI
* The .NET CLI is shipped as part of hte .NET Core SDK (Software deployment Kit)
* A set of commands that allows you to create, build, run, publish, test and package .NET Core apps from the command line
* Visual Studio delegates to the .NET CLI to build, run and publsih ASP.NET Core apps. 
  
## NuGet
* ASP.Net Core is delivered as a single set of granular and well factored NuGet packages
* Pay-for-what-you-use model
* Only deploy what your application needs

## Kestrel
* Need a new server to support running ASP.NET Core apps cross platform
* Kestrel is a cross-platform managed web server based on libuv (originally developed for Node.js)
* IIS is no longer directly supported
* IIS is used as a reverse proxy to Kestrel

## Performance 
* ASP.NET Core has exceeded 1.15 million requests per second
* 1.15 million repesents a 2300% gain over ASP.NET 4.6 or 800% gain over Node.js
* The second decimal place 0.05 million (e.g. 50,000) is around the number of request per second that ASP.NET 4.6 could perform of the same type, on the same hardware. 