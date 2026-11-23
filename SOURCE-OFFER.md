# Source offer for the FFmpeg tools inside Sclip

Sclip contains two command-line programs, `ffmpeg` and `ffprobe`, that run as separate processes. They are **free software under the GNU General Public License, version 3**. Sclip itself is
not covered by the GPL (see the Terms of Use). This page is the written offer required by GPLv3 section 6.

## The exact build

```
ffmpeg version 8.1.2-https://www.martin-riedl.de
configuration: --prefix=/Volumes/ffmpeg_arm64/out --pkg-config-flags=--static --extra-version='https://www.martin-riedl.de' --enable-gray --enable-libxml2 --enable-version3 --enable-gpl
  --enable-openssl --enable-libfreetype --enable-fontconfig --enable-libharfbuzz --enable-libsnappy --enable-libsrt --enable-libvmaf --enable-libass --enable-libklvanc --enable-libzimg
  --enable-libzvbi --enable-libaom --enable-libdav1d --enable-libopenh264 --enable-libopenjpeg --enable-librav1e --enable-libsvtav1 --enable-libvpx --enable-libvvenc --enable-libwebp
  --enable-libx264 --enable-libx265 --enable-libmp3lame --enable-libopus --enable-libvorbis --enable-libtheora
binary origin: https://ffmpeg.martin-riedl.de/download/macos/arm64/1783011502_8.1.2/ffmpeg.zip
```

It was not built with `--enable-nonfree`.

## Where the source is

- **FFmpeg 8.1.2 source code**, exactly as released: https://github.com/Adityasamant011/sclip/releases/tag/ffmpeg-8.1.2-source (file `ffmpeg-8.1.2.tar.xz`, with its SHA-256).
- **The libraries compiled into the build** (x264, x265, libvvenc, libaom, SVT-AV1, rav1e, libopenh264, libass, zimg and the others listed above) and the **build scripts and configuration** for this build:
  published by the builder at https://ffmpeg.martin-riedl.de/ for the build id above.
- **Anything else:** if you cannot get the complete corresponding source from those places, open an issue at https://github.com/Adityasamant011/sclip/issues and the source will be provided. This offer is valid for at least
  three years from the date you received Sclip, for as long as Sclip with these programs is distributed, and for anyone who has a copy.

The GPL licence text ships inside the app at `Resources/ffmpeg/LICENSE.txt`.
