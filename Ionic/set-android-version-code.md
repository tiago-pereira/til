# Set android version code

When generating a android build with `cordova build --release android`
the file platforms/android/AndroidManifest.xml is built with the version code.

Inside the project config.xml, in the widget tag, add the attribute `android-versionCode=""`.

```xml
<widget id="id" android-versionCode="coooode" xmlns="http://www.w3.org/ns/widgets" xmlns:cdv="http://cordova.apache.org/ns/1.0">
```
