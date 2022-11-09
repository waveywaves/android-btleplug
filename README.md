# android-btleplug-build-setup

- Clone https://github.com/gedgygedgy/jni-utils-rs and run the following command in the repo. This will build the required library for building btleplug for Android, also called droidplug.
```
cargo build --features=build-java-support
```

- Clone https://github.com/deviceplug/btleplug and go to the src/