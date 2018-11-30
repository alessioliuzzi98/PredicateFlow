fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

Install _fastlane_ using
```
[sudo] gem install fastlane -NV
```
or alternatively using `brew cask install fastlane`

# Available Actions
## iOS
### ios linting
```
fastlane ios linting
```
Linting...
### ios linting_fixing
```
fastlane ios linting_fixing
```
Linting and fixing...
### ios test_debug
```
fastlane ios test_debug
```
Run tests for PredicateFlow (Debug config)
### ios test_release
```
fastlane ios test_release
```
Run tests for PredicateFlow (Release config)
### ios documentation
```
fastlane ios documentation
```
Create documentation
### ios deploy
```
fastlane ios deploy
```
Deploy to Cocoapods and push tag to master

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
