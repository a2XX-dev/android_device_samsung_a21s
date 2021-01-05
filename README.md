# Orange Fox Project for the Samsung Galaxy A21s

### How to build ###

```bash
# Create dirs
$ mkdir ofr; cd ofr

# Init rsync
$ rsync rsync://sources.orangefox.download/sources/fox_10.0 . --progress -a

# Clone a21s repo
$ cd fox_10.0; git clone https://github.com/a2XX-dev/android_device_samsung_a21s -b fox-10.0 device/samsung/a21s

# Build
$ mv device/samsung/a21s/build_ofox.sh .; chmod +x build_ofox.sh; ./build.sh
```

### Credits
* Astrako: For build_ofox.sh base
