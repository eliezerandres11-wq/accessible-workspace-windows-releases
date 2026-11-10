# Accessible Workspace for Windows — releases

Accessible Workspace is a Gmail app for Windows built for JAWS, laid out like Outlook classic with the reading pane off.

This repository holds only the releases. Each release has:

- `AccessibleWorkspace.exe`: the app. It needs no installer and no .NET install.
- `latest.json`: the version, what's new, and the exe's size and SHA-256 fingerprint. The app reads it to update itself.

## Installing

1. Open the newest release under Releases and download `AccessibleWorkspace.exe`.
2. Put it in a folder of your own, such as Documents, so the app can update itself there.
3. Run it. The app isn't code-signed yet, so Windows SmartScreen warns the first time: choose More info, then Run anyway.

## Updates

The app checks for a new version a minute after it starts and once a day. It downloads the new version in the background, checks its fingerprint, and uses it the next time you start the app. Turn this off with Tools, Update Automatically; Help, Check for Updates checks at any time.
