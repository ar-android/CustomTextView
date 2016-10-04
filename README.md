# CustomTextView
Simple library to change font of TextView

![alt tag](https://raw.githubusercontent.com/ar-android/CustomTextView/master/sample.png)

This is an Android project allowing to change font of TextView in the simplest way possible.

# Usage
To make a CustomTextView add in your layout XML and add CustomTextView library in your project or you can also grab it via Gradle:

Add it in your root build.gradle at the end of repositories:

```gradle
allprojects {
   repositories {
    maven { url "https://jitpack.io" }
   }
}
```

Add dependencies :
```gradle
dependencies {
     compile 'com.github.ar-android:PercentView:1.0'
}
```

# XML
```xml
<ahmadrosid.com.lib.CustomTextView
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:text="Lobster Regular"
    app:fontPath="@string/lobster_regular"/>
```
## String path font
```xml
<string name="lobster_regular">fonts/Lobster-Regular.ttf</string>
```
## Don't forget to add font in your asset folder

![alt tag](https://cdn-images-1.medium.com/max/600/1*vU3goucPlj6T9JTI4ybKUw.png)


Open this tutorial to learn how to create an android library in simple way
https://medium.com/@ocittwo/yuk-buat-library-android-8ed01a329856
