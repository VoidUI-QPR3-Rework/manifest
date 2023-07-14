![VoidUI_Welcome_logo](https://github.com/VoidUI-Tiramisu/manifest/assets/34755141/34db2823-4fe0-4d21-ae68-d144165aec26)

# VoidUI Tiramisu Project - Android 13.0 - QPR3


### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/VoidUI-T-Unofficial/manifest -b aosp-13

# Use this if you want to save some space
repo init -u https://github.com/VoidUI-T-Unofficial/manifest -b aosp-13 --depth=10

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_devicecodename-userdebug

# Build the code
$ mka bacon -j$(nproc --all)
```
