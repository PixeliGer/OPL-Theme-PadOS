# PadOS Theme

<p align="center">
  <img src="https://github.com/PixeliGer/OPL-Theme-PadOS/blob/main/assets/logo.png">
</p>

<div align=center>
  
</div>

**PadOS** theme for Open PS2 Loader based on the iOS iPad interface, offers a streamlined and elegant design. It provides a familiar and user-friendly experience, perfect for those who appreciate Apple's aesthetic.


<div align = middle>
  <br>
  
  &ensp;[<kbd> <br> Installation <br> </kbd>](#-installation)&ensp;
  &ensp;[<kbd> <br> Features <br> </kbd>](#-features)&ensp;
  &ensp;[<kbd> <br> Screenshots <br> </kbd>](#-screenshots)&ensp;
  &ensp;[<kbd> <br> Recommendations <br> </kbd>](#-recommendations)&ensp;
  &ensp;[<kbd> <br> More Themes <br> </kbd>](https://pixeliger.github.io/opl-themes/)&ensp;
    
  <br>  
</div>


## 🌱 Inspiration

<p align="middle">
  <img width="48%" src="https://cdn.idropnews.com/wp-content/uploads/2021/07/22103306/Game-Center-Widget-for-iPad.jpg">
  <img width="48%" src="https://ph-files.imgix.net/144119fe-6098-4ead-9c89-a648bbb9988e.png?auto=format&fit=crop&frame=1&h=610&w=1024">
  <img width="48%" src="https://cdn.macstories.net/thursday-14-sep-2023-13-37-06-1694691434249.png">
  <img width="24%" src="https://image.winudf.com/v2/image1/MjEyMzQyMDJfMTc0MTkxOTIxNF8wNzc/screen-0.png?fakeurl=1&type=png">
  <img width="24%" src="https://image.winudf.com/v2/image1/MjEyMzQyMDJfMTc0MTkxOTIxNl8wOTQ/screen-1.png?fakeurl=1&type=png">
</p>

## ✨ Features

* Minimalist navigation bar inpired by iOS dockbar
* Two different styles, full and single widget.
* Dedicated versions for 4:3 and widescreen
* Working with HD/Full-HD on 16:9 and 4:3
* Compatible with the latest versions of [Open Ps2 Loader 1.2](https://github.com/ps2homebrew/Open-PS2-Loader/releases)

## 📸 Screenshots


#### Main Widgets

<p align="middle">  
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-PadOS/blob/main/assets/screenshots/screenshot1.png">
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-PadOS/blob/main/assets/screenshots/screenshot2.png">
</p>

#### Single Widget

<p align="middle">  
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-PadOS/blob/main/assets/screenshots/screenshot4.png">
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-PadOS/blob/main/assets/screenshots/screenshot5.png">
</p>

## 💾 Installation

**1. Initially, ensure your OPL folder is structured like this on your Device or in your Shared folder**
```
APPS/
ART/
CD/
CFG/
CHT/
DVD/
POPS/
THM/
VMC/
```

**2. Download one of the zip files that contains one of the Theme variants from the [Releases](https://github.com/PixeliGer/OPL-Theme-Pixel-Prime/releases/latest) page or using the green `DOWNLOAD` button at the top, (make sure it's one with the `thm_` prefix in its name)**
```
thm_PadOS
thm_PadOS-S
thm_PadOS-WIDE
thm_PadOS-S-WIDE
```

**3. Extract the ZIP file and move the theme folder to your `THM` directory.**
```
THM/
├─ thm_PadOS/
├─ thm_PadOS-S/
├─ thm_PadOS-WIDE/
├─ thm_PadOS-S-WIDE/
```

> [!NOTE]  
> Themes must be placed inside a folder named `THM` (in uppercase) for any of the devices: SMB share, HDD, USB, SD (MX4SIO), once the device starts, OPL will list the themes found in these locations

* **SMB** (Network Share)

In the root directory or drive you set as your PS2SMB share, in a THM folder

```
PS2SMB/THM/thm_PadOS/
```

* **USB**, **SD** device

In the root of the drive or partition set for OPL, in a THM folder

```
mass:/THM/thm_PadOS/
```

* **HDD** (Internal hard drive)

Place the THM folder in the `OPL Partition` of the HDD `+OPL`, you can create the partition if it doesn't exist, by using `uLaunchELF`: [FileBrowser > MISC > HddManager]

```
hdd0:/+OPL/THM/thm_PadOS/
```

> [!IMPORTANT]  
> Themes on any of these devices won’t display unless the device is enabled, so make sure to enable the device where your themes are stored through the OPL settings.

> [!WARNING]
> Avoid installing themes on the Memory Card, as their storage size can impact the proper functioning of the themes and cause issues with OPL.


**4. Launch OPL, if it was already open, restart it.**

**5. Go to OPL Settings and then `Display Settings`. In the `Theme` option, find and select your theme, then click `OK` to apply it.**


## 💡 Recommendations

To enhance your experience with the theme, consider these recommendations:

* To ensure proper and optimal viewing, activate the `Widescreen` mode for **Widescreen** versions and deactivate it for normal versions in `OPL Settings`
* Make sure you are using an updated or recent version of [Open Ps2 Loader 1.2](https://github.com/ps2homebrew/Open-PS2-Loader/releases/tag/latest)
* Download the assets for the `ART` folder (Background Image, Cover, Disc Cover, etc.) using the latest version of [OPL Manager](https://oplmanager.com/site/)


