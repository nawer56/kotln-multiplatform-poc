# kotln-multiplatform-poc

## Setting up the environnement

### Sum up
Developement on Intelliji : 11.0.4
Xcode Version 11.1
Android Studio Version install with SDK Manager (Android SDK Tools 26.1.1 SDK Platform-tools 29.0.5)

1. Update in gradle-wrapper.proporties the version of gradle in this tutorial is 6.0.1
```
distributionUrl=https\://services.gradle.org/distributions/gradle-6.0.1-bin.zip
```
2. Update build.gradle dependencies the version of gradle in this tutorial is 3.5.2 
```
classpath 'com.android.tools.build:gradle:3.5.2'
```
3. If you are facing this issue : **e: org.jetbrains.kotlin.konan.KonanExternalToolFailure: The /usr/bin/xcrun command returned non-zero exit code: 1.** you need to provide a default [command Line Tools in Xcode](https://stackoverflow.com/questions/40743713/command-line-tool-error-xcrun-error-unable-to-find-utility-xcodebuild-n?utm_medium=organic&utm_source=google_rich_qa&utm_campaign=google_rich_qa)

