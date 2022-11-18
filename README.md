# Andorid + BTLEPlug setup

- Clone the repo and build the jniLib shared object

```
git clone --recurse-submodules https://github.com/waveywaves/android-btleplug
cd android-btleplug
cd native && cargo make build-android
cd ..
cp native/target/aarch64-linux-android/release/libnative.so androidapp/app/src/main/jniLibs/arm64-v8a/
```
