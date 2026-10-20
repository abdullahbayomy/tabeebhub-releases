# TabeebHub — Downloads

Official installer downloads for **TabeebHub**, clinic management software.

> This repository contains distribution binaries only. **No source code is published here.**

---

## Download

### Windows

**[⬇ Download TabeebHub for Windows](https://github.com/abdullahbayomy/tabeebhub-releases/releases/latest/download/TabeebHub-Setup.exe)**

Windows 10 or Windows 11, 64-bit. About 96 MB.

### macOS

**[⬇ Download TabeebHub for Mac — Apple Silicon](https://github.com/abdullahbayomy/tabeebhub-releases/releases/latest/download/TabeebHub-arm64.dmg)**

For Macs with an M1, M2, M3 or M4 chip. About 122 MB.

**[⬇ Download TabeebHub for Mac — Intel](https://github.com/abdullahbayomy/tabeebhub-releases/releases/latest/download/TabeebHub-x64.dmg)**

For older Macs with an Intel processor. About 128 MB.

> **Not sure which Mac you have?** Click the  menu in the top-left corner of your
> screen and choose **About This Mac**. If it says *Apple M1/M2/M3/M4*, choose Apple
> Silicon. If it says *Intel*, choose Intel.

These links always serve the newest version — they do not change when we release an update.

---

## What's new in 1.0.16

This update brings the desktop app the WhatsApp changes the web app gained
since 1.0.15: a patient who says no at the desk is remembered, and the
reminder tag says who turned WhatsApp off.

### A "no" at the desk is remembered

- **Untick it, and it's recorded.** On the booking review step and in **Add
  Patient**, the box *The patient agreed to WhatsApp reminders* still starts
  ticked. If the patient doesn't want WhatsApp messages, untick it: that
  "no" is now saved for their number.
- **The next booking starts unticked.** When you book that patient again,
  the box starts unticked, with *Declined WhatsApp reminders before. Tick
  only if the patient agrees now.* Tick it only if they've changed their
  mind; that records their agreement.
- **A recorded "no" is never undone by mistake.** If you add a new patient
  on a number that already declined and leave the box ticked, the number
  stays off, and the app tells you so. A computer or phone still on an older
  version can't switch it back on by leaving the box ticked either.
- **Unticking doesn't cancel an agreement.** If a number already agreed,
  unticking the box doesn't stop its reminders; the app says so, and you
  can turn them off from the patient's WhatsApp card.
- **One answer per phone number.** The answer belongs to the number, so
  children booked on their mother's number share her answer.
- A patient who turned WhatsApp off themselves, or replied **STOP**, stays
  off as before. Only they can turn it back on, by replying **START**.

### The reminder tag says who turned WhatsApp off

On Today, the Appointments list and the appointment page, a booking whose
patient declined at the desk now reads **Declined WhatsApp**. Point at it to
see how to record a yes: on the patient's profile, or by ticking the box at
their next booking. A patient who turned WhatsApp off themselves still reads
**Turned WhatsApp off**.

### Same-day reminders before 09:00

No reminder is ever sent between 21:00 and 09:00. A same-day reminder whose
time falls before 09:00 used to be skipped. It now goes at 09:00, as long as
that is still at least 47 minutes before the appointment. For example, with
**1 hour before**, a 09:50 appointment is reminded at 09:00. The
**WhatsApp appointment reminders** card in **Clinic settings** says so.

> **Nothing to download.** If you are on 1.0.5 or later, this update installs
> itself. It downloads in the background and applies the next time you quit the
> app. The download links at the top of this page have not changed.

---

## Previously, in 1.0.15

This update brings the desktop app the new features and fixes the web app
gained since 1.0.14: a colour for each doctor across the schedule, a warning
before you book a time that is already taken, and WhatsApp reminders that
start ticked at the desk.

### Each doctor's patients, at a glance

When two or more doctors work in the clinics on your screen, every
appointment on Today, the Appointments list and the calendar shows whose
patient it is. A clinic with one doctor, viewed on its own, looks exactly as
before.

- **A colour for each doctor.** Each doctor gets a colour, the same on Today,
  the Appointments list and the calendar, and in the updated TabeebHub phone
  app. Colours follow the doctor list (the owner first, then A–Z), and with
  more than eight doctors they repeat. An appointment booked without a doctor
  reads **Any doctor**, in grey, until a doctor starts the visit; then it
  shows that doctor.
- **Filter by doctor.** A row of chips, **All doctors**, one per doctor and
  **Any doctor**, on Today and on Appointments (the list and the calendar).
  On Today, if you are a doctor, your own chip reads **Mine**: your patients
  plus anyone booked without a doctor. On Today the chips filter the lists
  below; the card at the top stays your own next patient. On Appointments the
  chosen doctor is remembered when you switch between list and calendar, go
  back, or reload the window. The **Completed** list has no chips or doctor
  tags and always shows everyone.
- **The calendar in each doctor's colour.** In Month, Week and Day, every
  appointment wears its doctor's colour. A finished visit is paler, a
  cancelled or missed one turns grey but keeps the doctor's coloured edge,
  and a patient who is already in the clinic has an amber dot. The legend
  under the calendar says so. In the Day view, and in the Week view when an
  appointment has its column to itself, the doctor's short name (for example
  *Dr. Ahmed A.*) is written on it. Point at any appointment to see the full
  name.
- **Booking for the doctor you are looking at.** With the calendar showing
  one doctor, the **+** on today or a later day (or a click on an empty time)
  opens the booking already assigned to that doctor. You can still change it.
  The doctor field when booking, booking a series or editing an appointment
  shows the chosen doctor's colour.
- A search on Today looks through everyone on today's board, whichever
  doctor or **Mine** is chosen.

### "This time is already booked"

When you schedule a time that overlaps another patient's booking with the
same doctor, or where either booking is for **Any doctor**, the booking form
shows an amber **This time is already booked** notice: who, when, the visit
type and the doctor. It appears as you choose the time. You can still book,
since two patients at once is sometimes exactly what you want, or choose
**Pick another time**. The same notice appears when you reschedule,
reinstate, or accept an online request. If you picked a doctor and the other
booking is with a different doctor, it is not a clash: the review step just
notes it.

### WhatsApp reminders start ticked

- **The booking form asks.** On the review step, *The patient agreed to
  WhatsApp reminders (read the script aloud)* starts ticked, with the
  sentence to read to the patient. Untick it if the patient doesn't want
  WhatsApp messages. **Add Patient** starts ticked too, once a phone number
  is entered.
- A patient who already agreed shows *Already agreed to WhatsApp reminders
  at this clinic*. A patient who turned WhatsApp off themselves, or replied
  **STOP**, stays off, and the form says so.

### Also

- Doctor sign-up now says, just above **Create Account**: *We'll send a
  welcome message on WhatsApp to this number, with our support team's
  contact.*
- On Today and in the new doctor tags, a doctor whose name was saved with
  "Dr" in front no longer shows as "Dr. Dr …".

### For TabeebHub admins

- **Admin → WhatsApp** has a **Doctor welcome message** card. It shows the
  message in Arabic and English (as Meta approved it, once synced; it says
  when it isn't synced yet), **Turn the welcome on** / **Stop the welcome**
  (each asks for a reason), and **Send a test to my WhatsApp**, which sends
  it to your own phone once Meta has approved that language.

> **Nothing to download.** If you are on 1.0.5 or later, this update installs
> itself. It downloads in the background and applies the next time you quit the
> app. The download links at the top of this page have not changed.

---

## Previously, in 1.0.14

This update brings the desktop app the new features and fixes the web app
gained since 1.0.13: root canal records in the Dental Chart, a 12-hour or
24-hour choice for the times your patients see, and a simpler billing page.

### Root canal records in the Dental Chart

A tooth with a root canal treatment in progress now has a root canal card
where you record each canal, instead of a free-text note.

- **Record canals.** The card lists the usual canals for that tooth, grouped
  under their root, and suggests the one that is often missed (such as a
  second MB canal) without ever assuming it. Type the working length of each
  canal one after another, and the final file size as *25/.06* or *F2*
  (**Same for all** gives every canal the same size). **+ Add canal** adds
  one more.
- **Two short dialogs.** **Dress & seal…** records the dressing and the
  temporary for a treatment that continues. **Fill canals…** records the
  technique, sealer and cones on the last visit, then **Fill & mark done
  (chart: Root canal)** or **Fill only**.
- **Every visit picks up where the last one stopped.** The next visit opens
  on the last values, with a *Visit log* that shows one line per visit and
  only what changed. The chart marks a tooth with a root canal in progress
  with an **RCT** tag.
- **Retreatment and children.** A tooth that already had a root canal opens
  as a **Retreatment**, with the previous filling and the old lengths beside
  the new ones. Baby teeth get a **Pulpectomy** card.
- **Mistakes are easy to undo.** A root canal marked done by accident is
  reopened with **Undo done to change it** in the message that appears, or
  **Undo done** in the tooth's history. You can still record on a completed
  visit until the end of that clinic day.
- **Saving.** Changes are saved when you leave the tooth or the tab, or when
  you complete the visit. If someone else saved the same tooth first, their
  changes are kept and you are asked only about the fields you both changed.

**Print a root canal record.** **Print record**, on the root canal card and on
each record in the tooth's history, opens a one-page sheet, *Root canal record
— tooth 36*, for referrals and the patient's file. It has your clinic's
letterhead, the patient, the tooth, the treatment, the doctor and dates, a
table of the final canals (length, file size, cone, state and any
complication) and the visit log. Press **Print**.

**Finished treatments keep their last note.** A treatment marked done or
stopped used to lose its *Next* note from the tooth's history. The history now
shows it as *Last note: …* under the result, on the visit's chart and on the
patient profile.

### 12-hour or 24-hour times for your patients

**Online booking settings** and **Online consultation settings** each have a
new choice, **Time format for patients**: **12-hour** or **24-hour**. It
changes only how times are written for patients: the times they pick from
when booking, their booking and consultation pages, and their appointment
pages for online bookings and consultations. Your hours, available times and bookings stay exactly the same.
Every clinic starts on 24-hour, as before, until you change it.

### Plans and billing

- **New plans:** **Free**, **1 Clinic**, **3 Clinics** and **9 Clinics**. Paid
  plans give unlimited visits, and prescriptions are unlimited on every plan,
  Free included. Some plans let you add extra clinics or extra staff members
  on top.
- **The billing page leads with *Your plan*:** your plan, what your next
  renewal costs line by line, the dates, and how much of each limit you use.
  **Renew**, **Change plan** and **Upgrade** are right there.
- **Buy one more clinic or staff seat.** When you reach your clinic or staff
  limit, on **My clinics**, **Staff**, the limit message or the billing page,
  you can add one more to the plan you have, if your plan offers extras, next
  to the cheapest upgrade.
  You pay now only for the days left in your current period; after that it is
  part of your renewal. Close to your renewal date, you get **Renew with 1 more
  staff member** (or clinic) instead. Only the clinic owner can buy; staff see
  *Ask the clinic owner to add a seat*.
- **"All in use" instead of a red "Full".** Using every clinic or staff seat
  your plan includes is normal, so it now reads **All in use**, in a calm
  colour. It turns red only when you are over a limit.
- **The Free plan now includes 2 staff members** (you, the owner, don't
  count). If you already have more on Free, nobody loses access.

### Your clinic's location

Clinic settings, clinic setup and **Create clinic** now have a **Where
patients find you** card, with your city, governorate and a **Location on
the map** section. Patients on your public
page get directions to your exact map pin once you have confirmed it, or to
your written address when there is no pin. In this version of the desktop
app, the pin itself is set on tabeeb-hub.com or in the TabeebHub phone app;
the desktop app shows the pin you set there, opens it with **Open in Google
Maps**, and can **Remove** it.

### Smaller changes

- **Credential documents each have their own place.** When you send your
  documents for verification, each one (for example a licence and a degree)
  has its own slot under *Your documents*. Files already sent stay attached,
  and **Replace** changes only that one.
- **Announcements in your language.** TabeebHub announcements are shown in
  English or Arabic, matching your app's language when both are written,
  with phone numbers written and linked correctly.
- **Attachments: up to 10 MB each, judged after the photo is shrunk.** A large
  photo is made smaller first, so most camera photos still upload. A PDF or
  photo that is still over 10 MB gets a clear *too large* message.

### Also

- The sign-up page now scrolls in the desktop app, so the **Create** button
  is always reachable. Its last step is shorter, with **Edit** to change your
  account details.
- A sharper TabeebHub app icon (the same design, redrawn), and a purple
  loading spinner while the app starts.
- Image attachments can be opened with **Open full size**.

### For TabeebHub admins

- **Admin → Payments** lists every payment made into TabeebHub, including
  **Declined** ones.
- **Admin → Subscriptions** sorts by closest to the limit, marks accounts
  with a **Near limit (80%+)** chip, and has **Move to Free** and **Set
  extras**.
- Announcements can be written in English, Arabic or both, with a live
  preview.

> **Nothing to download.** If you are on 1.0.5 or later, this update installs
> itself. It downloads in the background and applies the next time you quit the
> app. The download links at the top of this page have not changed.

---

## Previously, in 1.0.13

This update brings the desktop app the new features and fixes the web app
gained since 1.0.12. Most of it is about one thing: not booking the same
patient twice by mistake.

### The same patient booked twice

Until now, the app stopped a second booking only when it was for the same
patient, at the same clinic, at exactly the same time. Now it also tells you
when a new time clashes with a booking the patient already has, before
anything is saved.

- **New appointment.** If the patient already has an appointment at that
  time, the review step (*Review charges*) says so, for example *Ahmed Ali
  already has an appointment at this time*, with that booking's day, time,
  visit type, doctor and status. **Go back** to change the time, or press
  **Book anyway** (or **Book anyway & collect**). Nothing is booked until you
  choose.
- **The very same booking is still refused:** the same clinic and start time,
  or a second booking with no fixed time on the same day. There is no *Book
  anyway* then: press **Open appointment** to go to the one that exists, or
  **Go back**.
- **Walk-ins.** Adding a walk-in for a patient who is already in today's
  queue, or who has an appointment here today that hasn't been checked in,
  asks first too. When they have a booking here today, **Check in the 9:00 AM
  appointment instead** checks that booking in rather than adding a second
  one.
- **Reschedule, reinstate and accept.** Moving an appointment with
  **Reschedule**, bringing back a no-show with **Reinstate appointment**, and
  accepting a request on **Online requests** ask the same question, with
  **Move anyway**, **Reinstate anyway** or **Accept anyway**.
- **Book a series.** Each date that clashes is marked, for example *Already
  booked 9:00 PM*, and is skipped unless you tick its **Book anyway** box.
  In a series, any other booking the patient has that day at the same clinic
  counts as a clash. A date already booked at exactly that time is always
  skipped.
- **Next visit.** When you book the next visit while completing a visit, a
  note shows if the patient is already booked then. It never stops you
  completing the visit.
- **Two quiet lines on the review step** that never stop you, for a patient
  already on your list: their other bookings that day (*Also booked that day:
  9:00 PM · Examination*) and how many other patients are booked at that time
  (*2 other bookings at this time*). You can still book several patients at
  the same time.
- **What counts.** Only the same patient: brothers and sisters sharing a
  phone, or two animals of one owner, never clash. Finished, cancelled and
  no-show appointments don't count, and back-to-back appointments don't
  overlap. A booking with no end time counts as 30 minutes. A request the
  patient sent online that is still waiting for your reply counts too. A
  clash at another of your clinics is marked with that clinic's name, such as
  *at Dokki*.

### Online booking

- **Your buffer is kept around every booking.** The *Buffer between slots* in
  Clinic setup → Online booking settings now keeps time free before and after
  every booking, including bookings made at the desk, so your public page may
  offer a few fewer times on busy days. **What patients see**, on the same
  page, now says so under the times, and it updates by itself when a booking
  is made, moved or cancelled.
- **One time, one patient.** When two patients try to book the same last
  place at the same moment, only one of them gets it. A patient also can't
  book online at a time that overlaps an appointment they already have at one
  of your clinics.

### Fixed

- **The WhatsApp reminders card no longer loads forever.** Once WhatsApp
  reminders are available for your clinic, if the card in Clinic Settings →
  Notifications or on Money → WhatsApp reminders can't load its settings, it
  now says what went wrong and offers **Try again**, instead of a spinner that
  never stops.
- **The Share menu on the Invoices page opens on top.** It used to open under
  the rows below it, so it looked as if nothing had happened. It now opens
  over the page, and above the button when there is no room below.

### Coming soon

- **Google Calendar sync** is being tried with a small group of doctors
  first. We'll let you know when it is available to everyone.

> **Nothing to download.** If you are on 1.0.5 or later, this update installs
> itself. It downloads in the background and applies the next time you quit the
> app. The download links at the top of this page have not changed.

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
