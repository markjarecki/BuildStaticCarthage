# BuildStaticCarthage
This repository contains an example project for demonstrating how to build static frameworks under Carthage.

It leverages a simple BASH script - build-static-carthage.sh - to drive the `carthage build` command.

Read my Medium article  describing this example project. 

### Building static frameworks under Carthage
https://medium.com/@markjarecki/building-static-frameworks-under-carthage-ed010c904296

## Requirements

XCode 10.2

Carthage

## Installation

1. `git clone https://github.com/markjarecki/BuildStaticCarthage.git`
2. `cd BuildStaticCarthage`
3. `carthage update --no-build` 
4. Be patient for the download to finish
5. `bash build-static-carthage.sh -d realm-cocoa RxSwift RxGesture RxSwiftExt -p ios`
6. Go and make a cup of nice coffee - this will take a while
7. Open BuildStaticCarthage.xcworkspace in Xcode
8. Build the app and run

## Caveats

- Code is provided as-is
