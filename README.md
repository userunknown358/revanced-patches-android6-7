# YouTube ReVanced for Android 5.0-6.0
ReVanced Extended fork for YouTube 15.33.34.  **THIS IS JUST A TEST**
A fork of inotia00's [ReVanced Extended](https://github.com/inotia00/revanced-patches) (RVX) Patches.

## How to patch
See [[How to build]](https://github.com/kitadai31/revanced-patches-android6-7/wiki/How-to-build) page in documentations.

Other information is also available on [[documentations]](https://github.com/kitadai31/revanced-patches-android6-7/wiki) (GitHub Wiki).

## About
This is an experiment of integrating RVX patches to YouTube 15.33.34

### ~~Avoid "Switch to YouTube.com"~~
This version of YouTube shut down in March 2023

## 📣 Announcement of major update
In January 2025, the biggest update was released!  
Since then, this fork is **based on the latest RVX Patches.**

Previously, this patch was based on RVX v2.160.1 (released in Feb 13, 2023).  
v2.160.1 was the last version that works on 15.33.34.  
But it was too old and has fewer features than now.  
For example, the current RVX Patches contains a lot of new features that should also be available in 15.33.34, but this fork didn't have such features.  
So I moved to latest version of RVX Patches and added only minimal changes for 15.33.34.

**Almost all RVX features are available now!**  
And it will always follow the RVX's update!  
I keep the diff commits clean, so I will be able to follow the RVX updates easily by just rebase my diff commits.

## 📋 List of patches in this repository

### [📦 `com.google.android.youtube`](https://play.google.com/store/apps/details?id=com.google.android.youtube)
<details>

| 💊 Patch | 📜 Description | 🏹 Target Version |
|:--------:|:--------------:|:-----------------:|
| `Alternative thumbnails` | Adds options to replace video thumbnails using the DeArrow API or image captures from the video. | 15.33.34 |
| `Bypass URL redirects` | Adds an option to bypass URL redirects and open the original URL directly. | 15.33.34 |
| `Bypass image region restrictions` | Adds an option to use a different host for static images, so that images blocked in some countries can be received. | 15.33.34 |
| `Change layout` | Adds an option to change the dp in order to use a tablet or phone layout. | 15.33.34 |
| `Change live ring click action` | Adds an option to open the channel instead of the live stream when clicking on the live ring. | 15.33.34 |
| `Change start page` | Adds an option to set which page the app opens in instead of the homepage. | 15.33.34 |
| `Custom Shorts action buttons` | Changes, at compile time, the icon of the action buttons of the Shorts player. | 15.33.34 |
| `Custom branding icon for YouTube` | Changes the YouTube app icon to the icon specified in patch options. | 15.33.34 |
| `Custom branding name for YouTube` | Changes the YouTube app name to the name specified in patch options. | 15.33.34 |
| `Custom double tap length` | Adds Double-tap to seek values that are specified in patch options. | 15.33.34 |
| `Custom header for YouTube` | Applies a custom header in the top left corner within the app. | 15.33.34 |
| `Description components` | Adds options to hide and disable description components. | 15.33.34 |
| `Disable QUIC protocol` | Adds an option to disable CronetEngine's QUIC protocol. | 15.33.34 |
| `Disable forced auto audio tracks` | Adds an option to disable audio tracks from being automatically enabled. | 15.33.34 |
| `Disable forced auto captions` | Adds an option to disable captions from being automatically enabled. | 15.33.34 |
| `Disable haptic feedback` | Adds options to disable haptic feedback when swiping in the video player. | 15.33.34 |
| `Disable resuming Shorts on startup` | Adds an option to disable the Shorts player from resuming on app startup when Shorts were last being watched. | 15.33.34 |
| `Disable update screen` | Disable the force update screen ("Switch to YouTube.com" or "Update your app") | 15.33.34 |
| `Enable OPUS codec` | Adds an option to enable the OPUS audio codec if the player response includes it. | 15.33.34 |
| `Enable debug logging` | Adds an option to enable debug logging. | 15.33.34 |
| `Force hide player buttons background` | Removes, at compile time, the dark background surrounding the video player controls. | 15.33.34 |
| `Fullscreen components` | Adds options to hide or change components related to fullscreen. | 15.33.34 |
| `GmsCore support` | Allows patched Google apps to run without root and under a different package name by using GmsCore instead of Google Play Services. | 15.33.34 |
| `Hide Shorts dimming` | Removes, at compile time, the dimming effect at the top and bottom of Shorts videos. | 15.33.34 |
| `Hide accessibility controls dialog` | Removes, at compile time, accessibility controls dialog 'Turn on accessibility controls for the video player?'. | 15.33.34 |
| `Hide action buttons` | Adds options to hide action buttons under videos. | 15.33.34 |
| `Hide ads` | Adds options to hide ads. | 15.33.34 |
| `Hide comments components` | Adds options to hide components related to comments. | 15.33.34 |
| `Hide feed components` | Adds options to hide components related to feeds. | 15.33.34 |
| `Hide feed flyout menu` | Adds the ability to hide feed flyout menu components using a custom filter. | 15.33.34 |
| `Hide layout components` | Adds options to hide general layout components. | 15.33.34 |
| `Hide player buttons` | Adds options to hide buttons in the video player. | 15.33.34 |
| `Hide player flyout menu` | Adds options to hide player flyout menu components. | 15.33.34 |
| `Hide shortcuts` | Remove, at compile time, the app shortcuts that appears when the app icon is long pressed. | 15.33.34 |
| `Hook YouTube Music actions` | Adds support for opening music in RVX Music using the in-app YouTube Music button. | 15.33.34 |
| `Hook download actions` | Adds support to download videos with an external downloader app using the in-app download button. | 15.33.34 |
| `MaterialYou` | Applies the MaterialYou theme for Android 12+ devices. | 15.33.34 |
| `Miniplayer` | Adds options to change the in-app minimized player, and if patching target 19.16+ adds options to use modern miniplayers. | 15.33.34 |
| `Navigation bar components` | Adds options to hide or change components related to the navigation bar. | 15.33.34 |
| `Open links externally` | Adds an option to always open links in your browser instead of the in-app browser. | 15.33.34 |
| `Overlay buttons` | Adds options to display useful overlay buttons in the video player. | 15.33.34 |
| `Player components` | Adds options to hide or change components related to the video player. | 15.33.34 |
| `Remove background playback restrictions` | Removes restrictions on background playback, including for music and kids videos. | 15.33.34 |
| `Remove viewer discretion dialog` | Adds an option to remove the dialog that appears when opening a video that has been age-restricted by accepting it automatically. This does not bypass the age restriction. | 15.33.34 |
| `Return YouTube Dislike` | Adds an option to show the dislike count of videos using the Return YouTube Dislike API. | 15.33.34 |
| `Return YouTube Username` | Adds an option to replace YouTube handles with usernames in comments using YouTube Data API v3. | 15.33.34 |
| `Sanitize sharing links` | Adds an option to sanitize sharing links by removing tracking query parameters. | 15.33.34 |
| `Seekbar components` | Adds options to hide or change components related to the seekbar. | 15.33.34 |
| `Settings for YouTube` | Applies mandatory patches to implement ReVanced Extended settings into the application. | 15.33.34 |
| `Shorts components` | Adds options to hide or change components related to YouTube Shorts. | 15.33.34 |
| `Shorts seek` | Adds an option to replace toolbar buttons in Shorts player with skip/rewind buttons. | 15.33.34 |
| `Snack bar components` | Adds options to hide or change components related to the snack bar. | 15.33.34 |
| `SponsorBlock` | Adds options to enable and configure SponsorBlock, which can skip undesired video segments, such as sponsored content. | 15.33.34 |
| `Spoof app version` | [ONLY FOR DEBUG PURPOSE] Adds options to spoof the YouTube client version. But there is no useful target version for 15.33.34. (17.39.xx enables some new UI, but video description crashes if it contains YouTube links. 17.40.xx+ completely breaks the app.) | 15.33.34 |
| `Spoof streaming data` | Adds options to spoof the streaming data to allow playback. | 15.33.34 |
| `Swipe controls` | Adds options for controlling volume and brightness with swiping, and whether to enter fullscreen when swiping down below the player. | 15.33.34 |
| `Theme` | Changes the app's themes to the values specified in patch options. | 15.33.34 |
| `Toolbar components` | Adds options to hide or change components located on the toolbar, such as the search bar, header, and toolbar buttons. | 15.33.34 |
| `Translations for YouTube` | Add translations or remove string resources. | 15.33.34 |
| `Video playback` | Adds options to customize settings related to video playback, such as default video quality and playback speed. | 15.33.34 |
| `Visual preferences icons for YouTube` | Adds icons to specific preferences in the settings. | 15.33.34 |
| `Watch history` | Adds an option to change the domain of the watch history or check its status. | 15.33.34 |
</details>

