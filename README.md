# aosp-project

 Getting Started
---------------

To initialize your local repository, use command:

```bash
repo init -u https://github.com/aosp-project/android_manifest.git -b aosp-13.0
```

Then sync up:

```bash
repo sync -c
```

Building the System
-------------------
 Initialize the ROM environment with the envsetup.sh script.

```bash
. build/envsetup.sh
```

Lunch your device after cloning all device sources if needed.

```bash
lunch aosp_devicecodename-buildtype
```

Start compilation

```bash
mka otapackage
```

OR

```bash
mka bacon
```
