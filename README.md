# # Firestick Store (Self-Hosted)

This repo hosts a custom app catalog (`stores.json`) for Firestick sideloading.

## How to Add Apps
1. Open `stores.json`.
2. Add a new entry under `"apps"` with:
   - `name` → Display name
   - `package` → Android package ID
   - `version` → App version
   - `url` → Direct APK link
   - `icon` → (Optional) App icon URL

Example:
```json
{
  "name": "VLC",
  "package": "org.videolan.vlc",
  "version": "3.7.4",
  "url": "https://get.videolan.org/vlc-android/last/VLC.apk",
  "icon": "https://upload.wikimedia.org/wikipedia/commons/3/3a/VLC_Icon.svg"
}
