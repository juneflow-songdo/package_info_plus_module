[![pub package](https://img.shields.io/pub/v/package_info_plus_module.svg)](https://pub.dartlang.org/packages/package_info_plus_module)

# package_info_plus_module
It's a module of package_info_plus.

##  Installation
1. If the juneflow project doesn't exist, please create it by following [this guide](https://doc.juneflow.org/get-started).
2. open terminal in the juneflow project root directory, enter the following command.
 ```bash
 june add package_info_plus_module
 ```

## Usage
```dart
PackageInfo packageInfo = await PackageInfo.fromPlatform();

  String appName = packageInfo.appName;
  String packageName = packageInfo.packageName;
  String version = packageInfo.version;
  String buildNumber = packageInfo.buildNumber;

  print("appName: $appName");
  print("packageName: $packageName");
  print("version: $version");
  print("buildNumber: $buildNumber");
```