# Build from Source
Some Arch Linux bash scripts to make custom binary from source code

~~[ffmpeg_full_ocheb](ffmpeg_full_ocheb) - lets you to build and use ffmpeg-full from AUR without breaking any default system dependencies. [There is a video demonstration of it](https://youtu.be/CYMWXSBstpI)~~

~~[ffmpeg_full_amd_ocheb](ffmpeg_full_amd_ocheb) - same as previous, but works with another main PKGBUILD~~
>**The idea to use overlayed chrooted environment as a safe virtual environment don't work with newer Linux Kernel. Because Linux Kernel Developers did break overlayfs functionality.**

[get_ffmpeg-full_arch](get_ffmpeg-full_arch) - Semi-automatic script to download build and install ffmpeg-full (with support hw encoders) on arch linux (used by ocheb scripts but it may be used as standalone script if you want integrate ffmpeg-full into your system. By the way if some of used PKGBUILDs from AUR required update this script may fail. In that case try to run this script later, after updates.)

get_last_vlc_arch - Semi-automatic script to download build and install vlc-git (4.0xx)

get_mpc-qt_arch - Semi-automatic script to download build and install mpc-qt (it's more for example of how to use some of my scripts in a build process than for actual use this software)
