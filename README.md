# Ezra

Notes that live in tables: rows, typed columns, totals, and backup to your own
cloud accounts or to a folder on your device.

This repository holds **release builds only**. The source is kept private.

## Install

Download the latest `.apk` from [Releases](../../releases/latest) and open it on your phone.
Android will ask you to allow installing from this source the first time.

Builds are signed with a consistent key, so a new version upgrades an existing install
in place and keeps your data.

### Upgrading from 1.0.0

Version 1.0.1 renamed the app from Table Notes to Ezra, and the application ID changed
with it. Android treats that as a different app, so **1.0.1 installs alongside 1.0.0
rather than replacing it**, and it starts with an empty database.

To carry your data across:

1. Open the old app and back up, to a cloud account or to a folder
2. Install Ezra and restore from that backup
3. Remove the old app once you have checked everything came over

Only this one version behaves that way. Releases after 1.0.1 upgrade normally.

## Staying up to date

[Obtainium](https://github.com/ImranR98/Obtainium) can watch this repository and install
updates automatically. Add this repo's URL as an app source.

## What it does

- Tables with typed columns: text, number, amount with currency, date, time, duration,
  checkbox, choice and image
- Totals per column, with sum or average
- Templates, CSV and XLSX import, CSV export
- Backup and sync to Google Drive, OneDrive, Dropbox, or a folder on the device
- Several accounts at once, with one chosen as primary for two-way merges
- Snapshots taken before a sync can overwrite anything, restorable from the app
- Themes, pinned tables, daily reminders

## Requirements

Android 8.0 (API 26) or newer.

## Notes

Issues and questions are welcome here. Because the source is private, this repository
carries no code, only the built app.
