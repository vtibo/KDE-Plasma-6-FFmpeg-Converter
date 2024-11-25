# Note 
This script was originally made by NuVanDibe
https://github.com/NuVanDibe/dolphin-context-convert

I change some stuff in the ffmpeg encoder and the script path to my taste.

# KDE Plasma FFmpeg Converter

Right-click to convert audio/video/images in KDE Plasma. Uses FFmpeg. I only deal in KDE rn, feel free to PR for more compatibility

## Requirements
1. ffmpeg
2. zenity
3. imagemagick

## Install

1. put `ffmpegconvert.sh` in `~/Apps/`
2. Put `.desktop` files in `/usr/share/kio/servicemenus/`.
3. `chmod +x ~/Apps/ffmpegconvert.sh`

## Use

Right-click file in Dolphin -> Choose format. Can converet video to mp3 as a bonus

## Formats

- Audio: MP3, AAC, OGG, WMA, FLAC, ALAC, WAV, AIFF
- Video: MP4, AVI, MOV, MKV, WMV, FLV, MPG, OGV, GIF
- Image: JPG, PNG, GIF, BMP, TIFF, WEBP, EPS, RAW, ICO, PSD (only supports converting from)
