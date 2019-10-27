# google-cast-sdk-dynamic-ios

According to [documentation](https://developers.google.com/cast/docs/developers) of Google cast, Starting with version 4.3.1, Cocoapods uses static libraries which is a ~200MB download and a ~600MB framework.

There is also a dynamic sdk that is  ~20MB download and ~50MB framework.

This repo hosts the dynamic library in Cocoapods which for some unknown reason google haven't done.

## Installation

### CocoaPods

Specify it in your `Podfile`:

```ruby
pod 'google-cast-sdk-dynamic-ios'
```
