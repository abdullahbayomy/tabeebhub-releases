# TabeebHub — Downloads

Official installer downloads for **TabeebHub**, clinic management software.

> This repository contains distribution binaries only. **No source code is published here.**

---

## Download

### Windows

**[⬇ Download TabeebHub for Windows](https://github.com/abdullahbayomy/tabeebhub-releases/releases/latest/download/TabeebHub-Setup.exe)**

Windows 10 or Windows 11, 64-bit. About 91 MB.

### macOS

**[⬇ Download TabeebHub for Mac — Apple Silicon](https://github.com/abdullahbayomy/tabeebhub-releases/releases/latest/download/TabeebHub-arm64.dmg)**

For Macs with an M1, M2, M3 or M4 chip. About 115 MB.

**[⬇ Download TabeebHub for Mac — Intel](https://github.com/abdullahbayomy/tabeebhub-releases/releases/latest/download/TabeebHub-x64.dmg)**

For older Macs with an Intel processor. About 120 MB.

> **Not sure which Mac you have?** Click the  menu in the top-left corner of your
> screen and choose **About This Mac**. If it says *Apple M1/M2/M3/M4*, choose Apple
> Silicon. If it says *Intel*, choose Intel.

These links always serve the newest version — they do not change when we release an update.

---

## What's new in 1.0.7

**You choose which files a patient can see.** Every file attached to a visit
used to appear in the patient's records automatically. Now each one is marked
**Private** or **Shared**, and the label sits on the file itself, so a glance at
the visit tells you what the patient can open.

New files start **Private**. Sharing one asks you to confirm; making a file
private again is immediate and never asks. That is deliberate — un-sharing takes
a file out of the patient's list, but if they have already opened the link it may
keep working for them, so sharing is the step worth pausing on.

You can change this at any time, including long after the visit is finished.
Only doctors can share or un-share a file; assistants can still attach them.

**New procedures and medicines show up straight away.** Adding a procedure or a
medicine and going back to an open visit used to leave it missing from the list
until the app was reloaded. It appears immediately now.

**A small display fix.** Patients who chose not to state their gender showed a
line of internal text on the patient list and profile. It now reads correctly, in
both English and Arabic.

> **Nothing to download.** If you are on 1.0.5 or later, this update installs
> itself — it downloads in the background and applies when you next quit the app.

---

## Previously, in 1.0.6

**Book a course of visits in one go.** A patient attending three days a week no
longer means filling in the New Appointment form a dozen times. Pick the days on
a calendar — or generate them from a weekday pattern, "every Sunday and Tuesday
for four weeks" — and book the whole course at once. It is available from the
appointments page, the front-desk checkout, and the doctor's Complete Visit
dialog. Each date reports its own result, so if a day was already booked or a
prepaid course ran out of sessions, you are told which days were skipped and
why, rather than finding out later.

**Your monthly plan is applied while you choose the days.** The picker stops at
whatever your appointment allowance has left, instead of accepting twelve days
and quietly booking four. Completing a visit is never blocked by this — only
booking.

**Prepaid sessions read plainly.** "3 of 4 sessions left" is now
"1 completed · 3 remaining", everywhere a prepaid service appears.

**The Appointments list no longer flickers.** Booking a visit for a future date
briefly showed it under Today before it jumped to Upcoming. It now goes straight
to Upcoming, and the confirmation no longer says the patient was added to
today's queue when they were not.

---

## Previously, in 1.0.5

**Reception can close out a visit.** The front desk gets a checkout on the
appointment screen: what the visit came to, the procedures and services it was
for, the payment — full or partial — and the next booking. All of it without
opening the clinical workspace, which stays with the doctor.

**Services keep up with the doctor.** When the doctor adds a service or marks a
session used, the front desk sees it straight away, with the session that was
just completed called out. A finished course stays on screen instead of
disappearing mid-checkout, and a service bought more than once is now
distinguishable by when it was started.

**From this version the app updates itself.** New releases download in the
background and install when you quit — no more downloading an installer.

> Updating **from 1.0.4 or earlier** still needs a one-time manual download using
> the links above. Those versions have no updater in them; 1.0.5 is the first
> that can update on its own.

---

## Fixed in 1.0.4 — being returned to the login screen

Earlier releases could send you back to the login screen while you were working:
after the app had been left open for a long time, after the machine woke from
sleep, or simply after the app was reloaded. Nothing had actually rejected your
sign-in, and on some occasions signing in again did not hold.

**This is fixed in 1.0.4.** Sessions now renew on their own, a brief network
problem no longer ends one, and your sign-in survives a reload and a restart.

If you are running an older version, update using the links above. Your data was
never affected by any of this.

---

## Installing on macOS

1. Open the downloaded `.dmg` file.
2. Drag the **TabeebHub** icon onto the **Applications** folder shown beside it.
3. Open TabeebHub from your Applications folder or Launchpad.

That's it. TabeebHub is notarized by Apple, so macOS will not show a security warning.

---

## Installing on Windows

1. Click the Windows download link above and wait for the file to finish downloading.
2. Open **TabeebHub-Setup.exe**.
3. **Windows will show a blue warning screen.** This is expected — see below.
4. Choose the install location (or accept the default) and click **Install**.
5. TabeebHub installs for the current user only. **No administrator password is required.**

### About the "Windows protected your PC" warning

When you open the installer, Windows SmartScreen will show:

> **Windows protected your PC**
> Microsoft Defender SmartScreen prevented an unrecognized app from starting.

**To continue: click "More info", then click "Run anyway".**

This warning does **not** mean the file is unsafe or damaged. Windows shows it for any
application it has not yet seen downloaded many times. It will disappear on its own as
more clinics install TabeebHub.

If your clinic's IT policy blocks unrecognised applications, give your IT administrator
the checksum below — it lets them confirm the file is exactly the one we published.

---

## Verifying the download (for IT administrators)

Every release includes a `SHA256SUMS.txt` file listing the expected hash for each file.

**Windows (PowerShell):**

```powershell
Get-FileHash .\TabeebHub-Setup.exe -Algorithm SHA256
```

**macOS:**

```bash
shasum -a 256 TabeebHub-arm64.dmg
```

Compare the result against `SHA256SUMS.txt` on the
[latest release page](https://github.com/abdullahbayomy/tabeebhub-releases/releases/latest).
If they match, the file is byte-for-byte what we published.

The macOS builds are additionally signed with an Apple Developer ID certificate and
notarized by Apple. You can confirm this yourself:

```bash
spctl --assess --type execute --verbose=4 /Applications/TabeebHub.app
# expected: accepted   source=Notarized Developer ID
```

---

## Previous versions

Every release is kept permanently. Browse them on the
[Releases page](https://github.com/abdullahbayomy/tabeebhub-releases/releases) if you
need to reinstall a specific version.

---

## Support

Questions, or trouble installing? Contact **support@tabeeb-hub.com** or your clinic
administrator.

Website: [tabeeb-hub.com](https://tabeeb-hub.com)

---

Copyright © TabeebHub. All rights reserved.
