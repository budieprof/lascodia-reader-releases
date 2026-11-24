# Lascodia Reader releases

Android APKs of Lascodia Reader, an offline read-aloud reader. This repository holds releases only;
the source is kept elsewhere. Lascodia Reader checks here for updates.

Each release has two APKs (64-bit ARM phones and tablets, Android 8 or later):

- **`Lascodia-<version>-slim.apk` (about 33 MB): start with this one.** Everything is there; its
  browser uses Android's own engine (WebView).
- `Lascodia-<version>.apk` (about 122 MB): the same with Firefox's browser engine added. You don't
  need to download it yourself: in the slim app, Browser settings › Engine › Firefox gets it and
  installs it over the slim one, keeping your library.

Updates keep to the kind you have: the slim app updates to the next slim APK, the full app to the
next full one.

The release notes give each APK's SHA-256; the app checks it before installing an update.
