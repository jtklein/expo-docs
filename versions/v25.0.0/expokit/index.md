---
title: ExpoKit
---

ExpoKit is an Objective-C and Java library that allows you to use the Expo platform and your existing Expo project as part of a larger standard native project -- one that you would normally create using Xcode, Android Studio, or `react-native init`.

Because Expo already provides the ability to [render native binaries for the App Store](../guides/building-standalone-apps.html), most Expo developers do not need to use ExpoKit. In some cases, projects need to make use of third-party Objective-C or Java native code that is not included in the core Expo SDK. ExpoKit provides this ability.

This documentation will discuss:

- [Detaching](../guides/detach.html) your normal (JS) Expo project into a JS-and-native ExpoKit project
- [Changing your workflow](../guides/expokit.html) to use custom native code with ExpoKit
- Other [advanced ExpoKit topics](../guides/advanced-expokit-topics.html)