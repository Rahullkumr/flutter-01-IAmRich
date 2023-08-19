<h1 align=center>Flutter ❤</h1>

## flutter-01-IAmRich
  > Create a flutter project and paste these files and folders in their respective places
- An app which has an appbar saying I Am Rich
- an image from the assets/images folder
- having details of how to change the app-icon in android and ios devices.

## use Image inside the Scaffold:

1. NetworkImage ('imageLink'): from the internet 

2. AssetImage ('images/imageName'): 
  - first you need to uncomment the assets folder in pubspec.yaml 
  - then, `flutter pub get` will automatically run(if not, run it manually)
  - add `AssetImage('images/imageName.extension')` to your code

## Custom app icon
1. for Android devices
  - goto `https://www.appicon.co/` and download your icon
  - go inside android/app/src/main/res/
  - replace all `mipmap` folders with downloaded ones
2. For ios devices
  - goto `https://www.appicon.co/` and download your icon
  - go inside ios/Runner/
  - replace `Assets.xcassets` folder with downloaded one
## The App
![](https://github.com/Rahullkumr/flutter-01-IAmRich/blob/main/iamrich.jpg)

