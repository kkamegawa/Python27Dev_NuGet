# Python 2.7(Unofficial) Dev Nuget Package

Python 2.7 Dev Nuget Package is  unofficial dev packages(only lib/header files) for Nuget.

![](https://clueup.visualstudio.com/_apis/public/build/definitions/0fa03a7b-e8d2-46c1-9a00-a5160c41a569/81/badge)

## What's this?
This project re-packaging Python 2.7's header and Library files to NuGet package.  

## How to use it.
Package console in Visual Studio 2015.
install-package Python27Dev  
see:[Package Manager Console](https://docs.nuget.org/consume/package-manager-console)

## How to build it.

> cd nuget  
> .\download-nuget.cmd  
> .\build-nupkg.cmd  

## Issue
Some library files for debugging does not include.
(_bsddb.lib, _hashlib.lib, _sqlite3.lib, _ssl.lib, bz2.lib)

## Roadmap
I will updating with Python 2.x.
