# AOSP

## Before beginning... ##
This is just a fork of the latest AOSP manifest with some of my own repos being tracked and some AOSP apps removed.

## Building Android ##
[Setting Up Build Environment](https://raw.githubusercontent.com/nathanchance/Android-Tools/master/Guides/Building_AOSP.txt)

## Repo Init ##
```bash
repo init -u https://github.com/sourajitk/aosp_manifest.git -b 10
```
## Sync Source ##
```bash
repo sync --force-sync --no-clone-bundle --current-branch --no-tags -j$(nproc --all)
