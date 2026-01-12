```bash
npx expo prebuild --clean don't do this if already API is setup

cd android

./gradlew assembleRelease


cd ..

adb install android\app\build\outputs\apk\release\app-release.apk

or copy the apk from this path and install it in phone
