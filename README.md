# Neon Tech Sheet

**Checks every device on your show network against your tech sheet, then writes
the result back into the sheet.**

> **Early beta.** Neon Tech Sheet is new and still changing. Expect rough edges,
> and please say what breaks.

This repository holds **installers only**. Download the latest from
[**Releases**](../../releases/latest).

---

## What it does

- Reads the gear list and addresses from your show's Google Sheet.
- Checks every device on the show LAN, VLAN by VLAN.
- Marks each one **Verified**, **Partial** or **Failed** in the sheet.
- Keeps a live dashboard running while the show is up.

It runs on a laptop connected to the show network.

## Install

### Windows 10 / 11

1. Download `NeonTechSheet-Setup-<version>.exe` from [Releases](../../releases/latest).
2. Run it. No admin rights needed.
3. The beta build isn't code-signed yet, so Windows may show
   **"Windows protected your PC"**. Click **More info → Run anyway**.

### macOS

1. Download `NeonTechSheet-<version>.dmg` from [Releases](../../releases/latest), open it and
   drag **Neon Tech Sheet** into Applications.
2. The beta build isn't notarized yet, so macOS may block it the first time.
   Open **System Settings → Privacy & Security**, scroll down and click
   **Open Anyway** next to Neon Tech Sheet. Then open it again.

## First run

1. Choose **Show Device → Sign in with Google**, using the Google account that can open your show's sheet.
2. Paste the sheet's link.
3. Connect the laptop to the show network and run an audit.

During the beta, your Google account has to be added to the tester list before
sign-in works. Ask for it (see below). You may be asked to sign in again about once a week.

## Help

Questions or problems: message Kevin directly.

---

Built by Kevin Downing, a Broadway video engineer.
