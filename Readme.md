<p align="center">
  <img src="https://i.imgur.com/kbuDKB5.png" />
</p>

### Introducing Project Elixir now based on Android 14 シ

<p>"Redefining your android experience with our new update which offers minimal UI enhancement and close to Stock android experience with customization."</p>

### ⊀ Unleash Innovation ⊁

Your experience while using our ROM will be buttery smooth without compromising the quality of the Android experience. 

[![Download Project Elixir [Custom ROM]](https://img.shields.io/sourceforge/dm/project-elixir.svg)](https://projectelixiros.com/download) <img src="https://komarev.com/ghpvc/?username=Project-Elixir&style=flat-square" alt="Project-Elixir" />  [![Download Project Elixir [Custom ROM]](https://img.shields.io/sourceforge/dt/project-elixir.svg)](https://projectelixiros.com/download) 

To get started, you'll need to get
familiar with [Repo](https://source.android.com/source/using-repo.html) and [Version Control with Git](https://source.android.com/source/version-control.html).

### Create a directory for the source files
> [!Tip]
> * You can name this directory however you want, just remember to replace
> * WORKSPACE with your directory for the rest of this guide.
> * This can be located anywhere (as long as the fs is case-sensitive)

```
mkdir WORKSPACE
```
```
cd WORKSPACE
```

### Install Repo in the created directory
```bash
repo init --depth=1 -u https://github.com/Project-Elixir/manifest -b UNO --git-lfs
```

### Download the source
```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Set up environment for Build
```
. build/envsetup.sh
```
### Choose a target
```
lunch aosp_$device-userdebug
```
### Build the code
```
mka bacon -jX
```

### Credits
 * [**AOSP**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**xdroidOSS**](https://github.com/xdroid-oss)
 * [**ParanoidAndroid**](https://github.com/AOSPA)
 * [**ProtonAOSP**](https://github.com/ProtonAOSP)
 * [**crDroid**](https://github.com/crdroidandroid)
 * [**ArrowOS**](https://github.com/ArrowOS)
 * And some other ROMs not mentioned above

<br>   

> [!Important]
> ### Adding Support
> For adding your device to the list of OFFICIALLY supported devices,
> - [**Maintainers Requirements**](https://projectelixiros.com/documentation)
> - [**Device Requirements**](https://projectelixiros.com/documentation)
> - [**Apply for Maintainership**](https://docs.google.com/forms/d/1eme8i0nXFNpv2fEfbskoANIwLUGy4KcYXssluWv6obE)
> - [**XDA Template**](https://github.com/Project-Elixir/docs/blob/UNO/xda_template.txt)

<br>

<p align="center">
  <img src="https://i.imgur.com/zY1Znpm.png" />
</p>
