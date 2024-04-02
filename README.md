[![pub package](https://img.shields.io/pub/v/package_info_plus_module.svg)](https://pub.dartlang.org/packages/package_info_plus_module)

[![](https://img.shields.io/badge/Module-Hub-007bff?style=for-the-badge&logo=flutter)](https://module.juneflow.org/)
[![](https://img.shields.io/badge/View-Hub-007bff?style=for-the-badge&logo=flutter)](https://view.juneflow.org/)

[![](https://img.shields.io/badge/DISCORD-JOIN%20SERVER-5663F7?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/zXXHvAXCug)
[![](https://img.shields.io/badge/KakaoTalk-Join%20Room-FEE500?style=for-the-badge&logo=kakao)](https://open.kakao.com/o/gEwrffbg)

# package_info_plus_module
this module is a part of the juneflow project, it provides a package_info_plus module for flutter project.

##  Installation
1. If the juneflow project doesn't exist, please create it by following [this guide](https://doc.juneflow.org/).
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

