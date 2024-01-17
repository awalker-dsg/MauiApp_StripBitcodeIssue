This project was created to submit a MAUI issue ticket about the following .NET 8 build error:

`
C:\Program Files\dotnet\packs\Microsoft.iOS.Sdk\17.0.8490\targets\Xamarin.Shared.Sdk.targets(743,3): warning MT7091: The framework C:/Users/xxxx/.nuget/packages/xamarin.firebase.ios.core/8.10.0.3/lib/net6.0-ios15.4/Firebase.Core.resources/GoogleUtilitiesComponents.xcframework/ios-arm64/GoogleUtilitiesComponents.framework is a framework of static libraries, and will not be copied to the app.
"$(xcrun -find bitcode_strip)"  -r -o
C:\Users\xxxx\.nuget\packages\xamarin.firebase.ios.core\8.10.0.3\buildTransitive\Xamarin.Firebase.iOS.Core.targets(216,5): error : /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/bitcode_strip: missing argument(s) to: -o option
Usage: /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/bitcode_strip input [-r | -m | -l] [-keep_cs] -o output
C:\Users\xxxx\.nuget\packages\xamarin.firebase.ios.core\8.10.0.3\buildTransitive\Xamarin.Firebase.iOS.Core.targets(216,5): error MSB3073: The command ""$(xcrun -find bitcode_strip)"  -r -o " exited with code 1.
`
