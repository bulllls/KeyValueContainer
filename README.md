# KeyValueContainer
[![Travis CI](https://travis-ci.org/almazrafi/KeyValueContainer.svg?branch=master)](https://travis-ci.org/almazrafi/KeyValueContainer)
[![Codecov](https://codecov.io/gh/almazrafi/KeyValueContainer/branch/master/graph/badge.svg)](https://codecov.io/gh/almazrafi/KeyValueContainer)
[![Cocoapods](https://img.shields.io/cocoapods/v/KeyValueContainer.svg?style=flat)](http://cocoapods.org/pods/KeyValueContainer)
[![Carthage compatible](https://img.shields.io/badge/Carthage-Compatible-brightgreen.svg?style=flat)](https://github.com/Carthage/Carthage)
[![SPM compatible](https://img.shields.io/badge/SPM-Compatible-brightgreen.svg?style=flat)](https://swift.org/package-manager/)
[![Platforms](https://img.shields.io/cocoapods/p/KeyValueContainer.svg?style=flat)](https://developer.apple.com/discover/)
[![Xcode](https://img.shields.io/badge/Xcode-11-blue.svg)](https://developer.apple.com/xcode)
[![Swift](https://img.shields.io/badge/Swift-5.0-orange.svg)](https://swift.org)
[![License](https://img.shields.io/github/license/almazrafi/KeyValueContainer.svg?style=flat)](https://opensource.org/licenses/MIT)

## Requirements
- iOS 10.0+ / macOS 10.12+ / watchOS 3.0+ / tvOS 10.0+
- Xcode 10.2+
- Swift 5.0+

## Installation
### CocoaPods
[CocoaPods](http://cocoapods.org) is a dependency manager for Cocoa projects. You can install it with the following command:
```bash
$ gem install cocoapods
```

To integrate KeyValueContainer into your Xcode project using [CocoaPods](http://cocoapods.org), specify it in your `Podfile`:
```ruby
platform :ios, '10.0'
use_frameworks!

target '<Your Target Name>' do
    pod 'KeyValueContainer'
end
```

Finally run the following command:
```bash
$ pod install
```

### Carthage
[Carthage](https://github.com/Carthage/Carthage) is a decentralized dependency manager that builds your dependencies and provides you with binary frameworks. You can install Carthage with Homebrew using the following command:
```bash
$ brew update
$ brew install carthage
```

To integrate KeyValueContainer into your Xcode project using Carthage, specify it in your `Cartfile`:
```ogdl
github "almazrafi/KeyValueContainer" ~> 1.0.0
```

Finally run `carthage update` to build the framework and drag the built `KeyValueContainer.framework` into your Xcode project.

### Swift Package Manager

The [Swift Package Manager](https://swift.org/package-manager/) is a tool for managing the distribution of Swift code. It’s integrated with the Swift build system to automate the process of downloading, compiling, and linking dependencies.

To integrate KeyValueContainer into your Xcode project using Swift Package Manager,
add the following as a dependency to your `Package.swift`:
```swift
.package(url: "https://github.com/almazrafi/KeyValueContainer.git", from: "1.0.0")
```
and then specify `"KeyValueContainer"` as a dependency of the Target in which you wish to use KeyValueContainer.

Here's an example `Package.swift`:
```swift
// swift-tools-version:5.0
import PackageDescription

let package = Package(
    name: "MyPackage",
    products: [
        .library(name: "MyPackage", targets: ["MyPackage"])
    ],
    dependencies: [
        .package(url: "https://github.com/almazrafi/KeyValueContainer.git", from: "1.0.0")
    ],
    targets: [
        .target(name: "MyPackage", dependencies: ["KeyValueContainer"])
    ]
)
```

### Manually
If you prefer not to use dependency managers, you can integrate KeyValueContainer into your project manually
by adding the [KeyValueContainer](KeyValueContainer) folder to your Xcode project.

## Communication
- If you need help, open an issue.
- If you found a bug, open an issue.
- If you have a feature request, open an issue.
- If you want to contribute, submit a pull request.

## License
KeyValueContainer is available under the MIT license. See the [LICENSE](LICENSE) file for more info.