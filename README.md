# PASHA-TV-LITE-UPDATE

Public update metadata for the private Android TV / Fire TV application.

## Files

- `latest.json` — app update manifest. An APK is **not published yet**; `apkUrl` is currently `null`.
- `channels.json` — remote channel catalog. It starts empty; only tested streams with permission for redistribution should be added.

## Raw URLs

- https://raw.githubusercontent.com/smart222tech/PASHA-TV-LITE-UPDATE/main/latest.json
- https://raw.githubusercontent.com/smart222tech/PASHA-TV-LITE-UPDATE/main/channels.json

## App identity

- Package: `com.pasha.tvlite`
- Current source version: `versionCode 1`, `versionName 0.1.0`

## Important

This repository contains configuration only, not the private application source code. App updates require a signed APK built with the same persistent release key as the installed app. Android / Fire OS will show the system installation confirmation; updates cannot be silently installed by an ordinary app.

A stream being reachable does not establish redistribution rights. Do not add streams that require bypassing access controls or are not authorized for redistribution.
