# KDownloader

A portable desktop video downloader for Windows. Paste a link, pick a format, and the file lands on your disk. KDownloader resolves single videos and whole playlists, lists every format with its size, and keeps a queue that can be paused, resumed and retried.

- **Download:** [latest release](https://github.com/kurtliu309/kdownloader-site/releases/latest) — `KDownloader.exe`, no installer
- **Website:** [kurtliu309.github.io/kdownloader-site](https://kurtliu309.github.io/kdownloader-site/)
- **Dev journal:** [seven days to v0.2.5](https://kurtliu309.github.io/kdownloader-site/journey/)

## Requirements

- Windows 10 or Windows 11
- No installation: copy the `.exe` anywhere and run it
- ffmpeg is fetched in the background on first run; downloads that need it wait their turn

## First launch

The app opens a short guided setup: language, theme, download folder, then ffmpeg. The interface is available in English and Chinese, in a dark or a light theme.

## The exe is not code-signed

The build has no Authenticode signature, so Windows SmartScreen may warn the first time you run it. Choose **More info**, then **Run anyway**. If your browser also warns about the download, keep the file and run it the same way.

## What it will not do

KDownloader does not bypass DRM, paywalls, or other access controls. Download only content you have the right to keep, and follow the terms of the sites you use.

## About this repository

This repository holds the public website: the landing page, the dev journal, and the screenshots used in it. The application source code is not published here.

The screenshots in the dev journal come from mockups and a preview build backed by fake data; they contain no real user data.
