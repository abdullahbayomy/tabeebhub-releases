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

For Macs with an M1, M2, M3 or M4 chip. About 121 MB.

**[⬇ Download TabeebHub for Mac — Intel](https://github.com/abdullahbayomy/tabeebhub-releases/releases/latest/download/TabeebHub-x64.dmg)**

For older Macs with an Intel processor. About 127 MB.

> **Not sure which Mac you have?** Click the  menu in the top-left corner of your
> screen and choose **About This Mac**. If it says *Apple M1/M2/M3/M4*, choose Apple
> Silicon. If it says *Intel*, choose Intel.

These links always serve the newest version — they do not change when we release an update.

---

## What's new in 1.0.13

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

## Previously, in 1.0.12

This update brings the desktop app the new features and fixes the web app
gained since 1.0.11. Most of it is one new feature: WhatsApp appointment
reminders.

### WhatsApp appointment reminders

TabeebHub switches WhatsApp reminders on, so they may not be available for
your clinic yet. Until they are, Clinic Settings → Notifications shows them as
*Coming soon*. What follows applies once they are available for your clinic.

- **What the patient gets.** Before the appointment, a WhatsApp message sent
  by TabeebHub on behalf of your clinic, with the clinic's name, the
  appointment time and the number to call. It has three buttons: *I'll be
  there*, *I need to change it* and *Stop reminders*. Reminders go only to
  people who agreed to them for your clinic, and only to Egyptian mobile
  numbers. When the patient has no Egyptian mobile of their own, the reminder
  goes to a guardian linked at your clinic. An animal's reminder always goes
  to its owner.
- **When it goes.** The first reminder goes 12, 24 or 48 hours before the
  appointment. An optional second one goes 1, 2 or 3 hours before, on the
  day. Nothing is sent between 9 pm and 9 am clinic time: a first reminder
  that would fall then moves to 20:30 or 9:00, if that still leaves time, and
  a same-day reminder that would fall then is skipped. An appointment booked
  after its reminder time still gets one, at least an hour after it was
  booked, if there is still time.
- **See where it stands.** When a reminder is on its way, the appointment
  shows a small WhatsApp tag on the Today board and the Appointments list,
  such as *Reminder delivered* or *Reminder read*, then *Confirmed on
  WhatsApp* when the patient taps *I'll be there*. If the balance has run
  out, it reads *Reminder waiting for credits*. For an upcoming appointment
  that can't get a reminder, the tag says why, for example *No WhatsApp
  consent* or *No WhatsApp number*. Hover over a tag for details. The lists
  show the tag while the appointment is still booked; the appointment's own
  page always shows it. Tags appear only at clinics that have reminders
  switched on, and they update on their own.
- **"Asked to reschedule."** When the patient taps *I need to change it*, the
  tag reads *Asked to reschedule* and the clinic's staff get a notification,
  *Change requested on WhatsApp*, that opens the appointment. The appointment
  itself is never changed or cancelled: call the patient to agree a new time.
- **Stop reminders.** A patient who taps *Stop reminders* gets no more
  WhatsApp reminders or updates from your clinic on that number.

### Recording consent at the desk

The card and the tick below appear once TabeebHub switches WhatsApp messages
on, so you may not see them yet.

- **The patient's page has a WhatsApp messages card.** It lists each number
  that reaches the patient at your clinic: their own, and each guardian's (an
  animal's owner's), partly hidden. Each line says whether that person agreed,
  turned messages off or has not been asked yet, and where the answer came
  from, for example the desk, an online booking or the patient's own reply.
- **Record consent** shows a short sentence to read to the patient. Tick that
  the patient agreed, then press **Save consent**. **Turn off** is one click.
- **The patient's own "off" wins.** If the patient turned messages off
  themselves, by replying STOP, with the *Stop reminders* button or in their
  TabeebHub patient account, the desk can't turn them back on. Only the
  patient can.
- **Add Patient has the same tick** once the form has a phone number, the
  patient's own or a guardian's. It starts unticked, and the consent is
  recorded for those numbers right after the patient is added.
- **Consent is per clinic.** A patient who agreed at one clinic still needs to
  agree at each other clinic, even another one of your own.

### For the practice owner

Once WhatsApp reminders are available for your clinic:

- **Turn reminders on for each clinic** in Clinic Settings → Notifications.
  Choose when the first reminder goes (24 hours before is recommended) and
  whether to add a same-day one. The card also shows the number reminders ask
  patients to call (the clinic needs a phone number first), how many of the
  next 14 days' booked appointments can get a reminder and why the rest
  can't, and a preview of the message in Arabic and English, with your
  clinic's real name and phone. Only the clinic's owner can change these
  settings.
- **Switching reminders off** cancels the reminders already waiting to go
  out. **Changing the timing** cancels the ones planned for the old time and
  plans them again for the new one. The app says how many were cancelled.
- **Free trial.** The first time you switch reminders on, your practice gets
  30 free credits, valid for 30 days. This happens once.
- **Credits.** Each reminder WhatsApp delivers uses one credit, and a
  same-day reminder uses a second one. A reminder that is not delivered, or
  not sent, costs nothing. There is one balance per practice owner, shared by
  all your clinics.
- **Money → WhatsApp reminders** (owner only) shows the balance: credits
  available, credits held for reminders on their way, reminders waiting for
  credits, the next credits to expire, and how many each clinic used this
  month. Below it are the reminder settings for any of your clinics, every
  reminder with what it cost and the patient's answer (filter by clinic,
  status and dates), your credit batches and purchases, and how credits work.
  Credits added by TabeebHub show as *Added by TabeebHub*.
- **When the balance runs out,** new reminders wait. They go out as soon as
  credits are added, if there is still time before the appointment. You are
  told when the balance is low, when it runs out, about reminders that could
  not go out the day before, and before credits expire.
- **Buying credits,** when packs are on sale: press **Buy credits** on the
  page, or **+ Buy more** on the WhatsApp reminders card under Plan usage on
  Today. Pick a pack (prices include VAT, and each shows its price per
  reminder) and pay by card or mobile wallet. The payment page opens in your
  web browser. Pack credits are valid for 365 days. **Packs are
  non-refundable, including unused credits,** and you tick a box to accept
  this before paying. Only the practice owner can buy.
- **On Today,** Plan usage has a WhatsApp reminders card with the credits
  left, when the next ones expire and a *Low*, *Empty* or *Trial* badge. It
  opens the WhatsApp reminders page.

### Plan usage

- **+ Buy more is always on the Appointments and Prescriptions cards** under
  Plan usage on Today, not only when you are close to the limit. Unlimited
  plans don't show it.

### Fixed

- **Clinic Settings → Notifications no longer shows four switches that did
  nothing:** SMS and WhatsApp reminders, missed-visit follow-up and marketing
  messages, all marked *Coming soon*, with two of them drawn as on. The
  section is now WhatsApp appointment reminders, marked *Coming soon* until
  they are available for your clinic.
- On the Public page screen, **Preview** no longer shows the doctor's title
  twice, as in *د. د.محمد*, when the name was typed with a title such as
  *Dr/* or *د.*.

> **Nothing to download.** If you are on 1.0.5 or later, this update installs
> itself. It downloads in the background and applies the next time you quit the
> app. The download links at the top of this page have not changed.

---

## Previously, in 1.0.11

This update brings the desktop app the new features and fixes the web app
gained since 1.0.10.

### Dental clinics

- **Mark a tooth "In progress".** For treatment that takes several visits,
  such as a root canal, select the tooth on the Dental Chart during a visit
  and press **Mark in progress**. The tooth keeps its condition colour, its
  number is shown in a solid pill with a small half-filled circle on the
  tooth, and a line above the chart reads *In progress: 16, 36*. Every later
  visit opens with those teeth already marked. You can add a note, such as
  *next: obturation*.
- **Finish or stop it when the work is done.** **Mark done** can record the
  result, such as Filling, Root canal or Crown, in the same click, or leave
  the chart as it is. **Stop treatment…** ends it and keeps it in the tooth's
  history, or removes it if it was set by mistake. Complete visit lists the
  teeth still in progress and lets you mark them done there, but never stops
  you completing. The patient's Dental tab shows the same, read-only.
- **Charge a procedure per tooth.** In the procedure editor, each procedure
  is now **Charged per: Procedure** or **Tooth**. Added to three teeth on the
  Dental Chart, a per-tooth procedure is billed three times and uses its
  materials three times; a per-procedure one is billed once (*Billed once for
  3 teeth*). Existing procedures and visits already recorded don't change.
  The owner sees a banner listing the procedures whose description says "per
  tooth", so they can switch them in one step.
- **Set the price on the Dental Chart.** Doctors and owners can type a price
  for this visit, or a price per tooth, when adding a procedure from the
  chart, as they already could on the visit's Overview. The procedure's own
  price never changes.

### Materials a visit used

- **Record what was really used.** In a clinic that keeps inventory, the
  visit's procedures card is now **Procedures & materials**. Each procedure
  still takes its default materials off stock. Open **Materials** on its row
  to record what this visit actually used: more, less, *Not used*, or another
  item from stock. Then press **Save materials**. The procedure's default
  materials never change, so the next patient starts from them again.
- **+ Other material** records what belongs to no procedure, such as an
  extra pack of gloves.
- **On the Dental Chart** you can adjust the materials before pressing **Add
  to visit**, so stock moves once, by exactly what is on screen.
- **Removing a procedure** now asks first and says what will happen: its
  charge is cancelled and everything it used, including your changes, goes
  back to stock.
- **An item's stock history names the visit,** for example *Used · Filling ·
  Ahmed Ali*, and opens it.
- **Who can change materials:** the owner, a doctor or an assistant while the
  visit is in progress; only the owner once the visit is completed or
  cancelled. Reception adds procedures as before, without the materials
  editor.
- **If your clinic blocks stock from going below zero,** the message names
  the item and how many are in stock. The owner can **Update stock** right
  there, and the add is then tried again by itself.
- The procedure editor now asks *Discard your changes?* before it closes
  with unsaved changes.

### Patients

- **The clinic owner can delete a patient record:** a test, a duplicate or
  one added by mistake. Use **⋯ → Delete patient** on the Patients list or on
  the patient's page, and pick a reason. Deleting doesn't give back plan
  usage: appointments already used still count. Visits, payments and
  invoices stay in your records and reports. Plain upcoming appointments are
  cancelled, without notifying anyone. If the patient isn't registered at
  another clinic and doesn't use the patient app, the phone number is taken
  off the record so you can use it for a new patient.
- **Money and open work come first.** If the patient owes money, holds
  credit, has a paid booking or an open visit, the dialog lists each one with
  a button that takes you there, and the record can be deleted once they are
  settled.
- **Restore at any time.** **Undo** shows for 10 seconds after a delete
  (**Restore** if appointments were cancelled), and a **Deleted (n)** link at
  the end of the Patients header lists deleted patients. Restoring brings the
  record back with its patient number and history. Its phone number comes
  back too, unless another patient has taken it since. Appointments the
  delete cancelled don't come back. Only the clinic owner sees Delete and
  Restore.
- **Adding a patient with a deleted patient's number** tells you so. The
  owner can restore that record instead; other staff are asked to check with
  the owner.

### Prescriptions

- **Print on your own prescription paper.** Print now has a small ▾ beside
  it: **Full prescription** (still the default, unchanged), **On my
  prescription paper** (or *On Dr. …'s prescription paper* for a colleague's
  prescription), and **Prescription paper settings**. Paper printing
  puts only the medicines, their instructions, the notes and the follow-up
  date into the blank area of your pre-printed pad.
- **Set it up once per doctor, per clinic, in about a minute.** Choose the
  paper size, print a measuring sheet on one pad sheet, and type the two
  numbers you read off it: where the printed header ends and where the footer
  starts. Tick what your pad already shows, such as the doctor's name or a
  line for the date. A long prescription continues on a second sheet without
  splitting a medicine. If this computer prints slightly off, you can nudge
  it by half a millimetre.
- **Make it the default** if you like. Then anyone who presses Print on that
  doctor's prescriptions at that clinic prints on the paper, and the button
  reads **Print on Rx paper**. Doctors also find the setting on their
  Profile.
- **The desktop app opens the print window already set to the right paper
  size** (A5 or A4).

### Specialties

- **Neurosurgery has its own chief complaint.** Neurosurgery clinics used to
  get the general form. Complaints are now chips, such as low back pain,
  sciatica, neck pain, headache and fits, with the side in one tap. The
  questions for a complaint appear once you tick it. Warning signs that need
  action the same day, such as saddle numbness, a thunderclap headache or a
  head injury on blood thinners, turn red and are counted on the summary.
  Diagnosis chips build the working diagnosis, the note writes itself in
  English or Arabic, and Continue carries the problem into the next visit and
  asks again about today.
- **Veterinary: parasite control on the vaccination card.** Deworming and
  flea & tick treatment for dogs and cats sit under a new **Parasite
  control** heading. Choose the schedule (deworming every 2 weeks, monthly,
  every 2 months or every 3 months; flea & tick monthly or every 12 weeks)
  and the next date counts from the last dose. Nothing is chased until the
  first dose is recorded. A young animal's first record opens on the
  schedule for its age, and the row says so when the animal has outgrown it.
- **Record dose has a search box.** On an animal's card it finds rows by the
  words vets actually type, such as «تطعيم الديدان», «تطعيم الحشرات», worms or
  fleas, and by brand names.

### Several clinics

If you run one clinic, only a few labels change here.

- **"Working at" is the clinic you are at.** It is marked with a pin
  wherever it appears. Your cash drawer, calls from your team and Today's
  shortcuts use it. The *Showing:* menu has a new first choice, **Where I'm
  working**, that follows it.
- **The first time you open a practice with two or more clinics on this
  computer,** the card on Today now asks *Where are you working?* and also
  what your lists should show. Nothing is saved until you press **Done**.
- **Clearer choices.** New Appointment and Add Patient mark your clinic
  *You're here*. Moving to clinics where you work for another doctor is
  labelled, for example *Switches to Dr. Y's clinics · you're a doctor
  there*. Call staff names the clinic it calls.
- **The short name is optional.** New Clinic no longer asks for a short name,
  for the new clinic or any other. A line under the name shows how the clinic
  will appear in lists, with **Change**. You can also clear a short name. The
  amber "give each clinic a short name" banner is gone; a quiet hint appears
  only when two of your clinics really look alike.
- **New Clinic sets the currency and time zone from the clinic's phone
  number.** It used to guess the currency from your computer's language and
  leave every new clinic on Cairo time.

### Cash register

- **The register pill follows the screen.** The pill in the top bar shows the
  drawer of the clinic the page shows, for example *Register closed ·
  Dokki*, and opens it. Under *All clinics* it shows the drawer where you are
  working, marked with the pin.
- **Every drawer at once.** With *Showing: All clinics*, the Cash register
  page opens with *Your drawers · 1 of 3 open*: one row per clinic, each in
  its own currency, with **Open drawer** or **Count & close**. Drawers are
  never added together.
- **The owner can count and close a colleague's forgotten drawer.** Any
  shortfall or surplus is recorded on that person's shift, and the sessions
  list says *Closed by …*. Before, a forgotten drawer could only close
  itself, uncounted, at the end of the clinic's day.
- **Clearer words.** Your card says *Your drawer is closed* rather than
  *Register closed*, so it no longer reads as if the clinic's whole till were
  closed while a colleague's drawer is open. A line under it lists
  colleagues' drawers open at the same clinic, for example *Also open here:
  Sara since 09:05*.

### Menu and names

- **One name per screen,** the same in the menu and the page title:
  *Revenue*, *Staff pay* (was Compensation), *Clinic performance* (was
  Performance), *Prescriptions* (was Prescription Command Center), *My
  clinics*, *Billing & subscription*. Today's *Schedule* shortcut is now
  *Appointments*.
- Owners have a menu row for **Online consultation settings** under Clinic
  setup. **Patient tags** has moved to the end of Services & stock.
- Only one menu row is highlighted at a time, and assistants no longer see a
  count on *Payments to confirm*, which they can't confirm; the page says
  *View only*.
- Your Profile has a **Sign-in & security** card for every role. Its
  *Previous session* shows your own last sign-in on this computer, never
  someone else's on a shared computer.

### Notifications

- **Notifications in Arabic.** If you use the app in Arabic, notices that
  still showed in English (cash checks, subscription and trial reminders,
  payment problems, consultation case results) now read in Arabic, with
  Arabic buttons. This includes notices already in your list, and the
  summary cards on the Notifications page.
- **Clearer cash notices.** *Yesterday's cash needs a look* now names the
  days the check covers, for example *Cash from the last 2 days needs a
  look*, and counts read *1 drawer*, not *1 drawer(s)*. *Your books balance
  again* now reads *Nothing needs a look now*.
- **An empty bell says what it will show you,** depending on your role: for
  example a patient booked, checked in or ready for you, or a visit ready to
  collect.

### Staying signed in and up to date

- **A dropped connection no longer signs you out.** If the internet drops,
  or the server is restarting for an update, when your session needs
  renewing, the app keeps you signed in and keeps trying until it gets
  through. Only a sign-in the server actually refuses ends your session.
- **More money pages refresh on their own while live updates are down:**
  Business overview, Profit and loss, and the Revenue page's Collections
  panel.

### Fixed

- **The alert sound now plays in the desktop app,** for new notifications
  and when a doctor calls staff. The sound was missing from the app, so it
  stayed silent. You can turn it off with *Alert sounds* in the
  notifications panel.
- Reception's full prescription printout now shows each medicine's
  instructions and notes, instead of a dash.
- The full prescription now waits for its QR code before printing, so the
  code no longer prints as an empty box.
- Staff pay accepts Arabic digits in percentages and in the withholding note.
- In Arabic, the New Clinic dialog's messages about the name, address,
  specialty and currency are now in Arabic, not English.

> **Nothing to download.** If you are on 1.0.5 or later, this update installs
> itself. It downloads in the background and applies the next time you quit the
> app. The download links at the top of this page have not changed.

---

## Previously, in 1.0.10

This update brings the desktop app everything the web app gained since 1.0.9,
including fixes for three problems clinics reported.

### Live updates that stay live

- **Today comes back to Live on its own.** After you signed in, Today could
  read *Connecting…* and show no new patients until the app was reloaded. Live
  updates now connect as soon as you sign in, and come back by themselves after
  a server update or a dropped connection.
- **Nothing goes stale while the connection is down.** Today, Appointments,
  Completed visits and the money pages keep refreshing on their own until live
  updates are back.
- **The badge says what is happening:** *Live*, *Connecting…*, *Reconnecting…*
  or *Not live*.

### The language button

- **Switching between English and Arabic keeps you exactly where you were:**
  the same page, tab, filters and clinic. It used to drop them, and on a
  patient's Financial tab the page could freeze.
- **It never hangs.** If the other language is slow to load, the page simply
  opens again in the new language.
- **A patient link that does not say which clinic** now asks *Which clinic's
  record?* instead of loading forever.

### Several clinics

- **Online consultations work across your clinics.** Under *All clinics* the
  list shows every clinic's consultations, each marked with its clinic.
  Consultation settings have their own page with an *Editing:* control, and
  the owner can move where consultations are recorded with *Move here*.
  Money for a consultation always lands at the clinic it belongs to.
- **Every page that shows a clinic's data has the right control:** *Showing:*
  on lists and reports, *Editing:* on settings. If you run one clinic, nothing
  changes.

### Faster

- **Pages make no more requests than they need**, and the patient page loads
  fewer.

### Fixed

- The vaccination card's summary no longer squeezes into one word per line.
- The account menu closes when you click anywhere else on the page.
- Switching language on a print page no longer opens the print dialog a second time.

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
