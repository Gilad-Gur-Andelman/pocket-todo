# Pocket Todo

A tiny, fully offline Android to-do app. It is written in Kotlin with Jetpack Compose and has a single screen: type a task, tap **Add**, tick it off, or delete it. There is no network access, no login, and no persistence.

- Package: `com.example.pockettodo`
- minSdk 26, targetSdk 36

## Build

Requirements: JDK 17 or newer and the Android SDK (platform 36). Point Gradle at the SDK with `ANDROID_HOME` or a `local.properties` file containing `sdk.dir=...`.

```sh
./gradlew :app:assembleDebug
```

The APK is written to `app/build/outputs/apk/debug/app-debug.apk`. Install it on a running emulator or device with:

```sh
adb install -r app/build/outputs/apk/debug/app-debug.apk
```

## License

MIT, see [LICENSE](LICENSE).
