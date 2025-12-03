# Boost-iOS Binary Package

Swift package manager binary distribution for iOS Boost Frameworks.

See [iOSBoostFramework repo](https://github.com/Cogosense/iOSBoostFramework.git)
for source.

Use the Xcode packages feature to include it into a project.
See [Adding package dependencies to your app](https://developer.apple.com/documentation/xcode/adding-package-dependencies-to-your-app)

This framework is a static framework, so when including it into your project
ensure that it is not signed or embedded into the app bundle. If you do
accidently embed it, Xcode will be unable to load your app bundle on to an
iOS device.
[Here is an example](https://github.com/Cogosense/iOSBoostFramework/issues/11)

