This project was created to support [MAUI issue 19946](https://github.com/dotnet/maui/issues/19946) about the following .NET 8 build error:

    C:\Users\xxxx\.nuget\packages\xamarin.firebase.ios.core\8.10.0.3\buildTransitive\Xamarin.Firebase.iOS.Core.targets(216,5): error : /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain /usr/bin/bitcode_strip: missing argument(s) to: -o option
    Usage: /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/bitcode_strip input [-r | -m | -l] [-keep_cs] -o output
    C:\Users\xxxx\.nuget\packages\xamarin.firebase.ios.core\8.10.0.3\buildTransitive\Xamarin.Firebase.iOS.Core.targets(216,5): error MSB3073: The command ""$(xcrun -find bitcode_strip)"  -r -o " exited with code 1.
