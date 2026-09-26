# Raster Tech Sheet

**Checks every device on your show network against your tech sheet, then writes
the result back into the sheet.**

> **Early beta.** Raster Tech Sheet is new and still changing. Expect rough edges,
> and please say what breaks.
>
> **Formerly Neon Tech Sheet.** Same app, new name. Installs update in place, and
> your settings and sign-in carry over.

This repository holds **installers only**. Download the latest from
[**Releases**](../../releases/latest).

---

## What it does

- Reads the gear list and addresses from your show's Google Sheet.
- Checks every device on the show LAN, VLAN by VLAN.
- Marks each one **Verified**, **Partial** or **Failed** in the sheet.
- Keeps a live dashboard running while the show is up, on the laptop and your phone.
- Builds a printable **Sub Packet** handoff from the sheet, for whoever runs the show
  when you can't.

It runs on a laptop connected to the show network.

## Install

### Windows 10 / 11

1. Download `RasterTechSheet-Setup-<version>.exe` from [Releases](../../releases/latest).
2. Run it. No admin rights needed. If Neon Tech Sheet is installed, it's replaced in
   place.
3. The beta build isn't code-signed yet, so Windows may show
   **"Windows protected your PC"**. Click **More info → Run anyway**.

### macOS

1. Download `RasterTechSheet-<version>.dmg` from [Releases](../../releases/latest), open it and
   drag **Raster Tech Sheet** into Applications. If you had Neon Tech Sheet, delete it.
2. The beta build isn't notarized yet, so macOS may block it the first time.
   Right-click the app and choose **Open**, or open **System Settings → Privacy &
   Security**, scroll down and click **Open Anyway** next to Raster Tech Sheet. Then
   open it again.

## First run

1. Choose **Show Device → Sign in with Google**, using the Google account that can open your show's sheet.
2. Paste the sheet's link.
3. Connect the laptop to the show network and run an audit.

During the beta, your Google account has to be added to the tester list before
sign-in works. Ask for it (see below). You may be asked to sign in again about once a week.

The full beta guide is attached to each release.

## Help

Questions or problems: message Kevin directly.

---

Tech Sheet by Raster. Built by Kevin Downing, a Broadway video engineer.
