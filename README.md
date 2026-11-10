# BlueSky legacy client

Standalone Android 2.3 compatible client for the Tailstter Bluesky bridge.
It uses direct HTTP requests to `http://tails1154.com:6483` and does not use
the original Twitter content provider or Android sync adapter.

Build with the Android SDK and Gradle:

```sh
ANDROID_HOME=/opt/android-sdk gradle :app:assembleDebug
```
