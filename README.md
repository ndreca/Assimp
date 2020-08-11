# Assimp as Swift Package and CocoaPod

The umbrella header contains both import and export features so takes some time to compile.
A prebuilt binary xcframework (for iOS & Catalyst only) is wrapped as swift package, and works in XCode 12 Beta only. 
This approach is experimental and has some issues with code signing.

https://github.com/assimp/assimp

### CocoaPods
```
  pod 'Assimp',  :git => 'https://github.com/ndreca/Assimp.git'
```

### SwiftPackage
```
  .package(name: "Assimp", url: "https://github.com/ndreca/Assimp.git", from: "5.0.1"),
```
