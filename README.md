```bash
npx expo prebuild --clean don't do this if already API is setup
```bash
cd android
```bash
./gradlew assembleRelease

```bash
cd ..
```bash
adb install android\app\build\outputs\apk\release\app-release.apk
```bash
or copy the apk from this path and install it in phone
