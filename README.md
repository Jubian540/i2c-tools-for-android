## I2C TOOLS FOR ANDROID

This package contains an heterogeneous set of I2C tools for Android.

## Usage

### Clone source code

On AOSP root path.

```
$ cd external
$ git clone https://github.com/Jubian540/i2c-tools-for-android.git
```

Configure on your device config file.

```
PRODUCT_PACKAGES += \
    i2cdetect \
    i2cget \
    i2cdump \
    i2cset
```

Build AOSP at last.
