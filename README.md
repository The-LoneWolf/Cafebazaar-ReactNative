# Cafebazaar-ReactNative

A simple react native sample for cafebazaar in app billing

1.Copy and edit this source code. important tips are mentioned in next steps.

2.Change ```package name``` in every part of app. (gradle.build - manifest - main java files included packages)

3.Add your CafeBazaar RSA license key as a line to your `android/app/src/main/res/values/strings.xml` with the name `RNB_GOOGLE_PLAY_LICENSE_KEY`. For example:

```xml
<string name="RNB_GOOGLE_PLAY_LICENSE_KEY">YOUR_GOOGLE_PLAY_LICENSE_KEY_HERE</string>
```

4.In App.js there is a line ```productId: "vipuser",``` change the value with your product sku-code.(```vipuser``` is sample sku).

5. run your app and enjoy :))


### a code derived https://github.com/idehub/react-native-billing
