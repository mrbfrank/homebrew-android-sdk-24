# homebrew-android-sdk-24

### Why
The latest version of Android SDK Tools (v25.3.0) contains some [breaking changes](https://issues.apache.org/jira/browse/CB-12544) to the Cordova build process. Specifically, the ```android``` command line tool and [a few others](https://developer.android.com/studio/releases/sdk-tools.html) have been deprecated in the latest Android SDK release. Until the next major release of Cordova is published, Homebrew users will likely require v24 of the Android SDK for a working development environment.

A few hours ago, Homebrew moved the android-sdk Formula from homebrew-core into a new Cask making it difficult or impossible to downgrade versions.

### What
This is a Homebrew Tap that installs the previous version of android-sdk which will work with Cordova projects & frameworks such as Ionic.

### How
```
brew install mrbfrank/android-sdk-24/android-sdk
```

### Note
- The Android Platform-Tools need to be installed as part of the SDK.
