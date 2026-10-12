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

## What's new in 1.0.12

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

## Previously, in 1.0.9

This update brings the desktop app everything the web app gained between
16 September and 3 October, so the two match again. The first section is for
practices with more than one clinic. If you run one clinic, skip it; everything
after it applies to you.

### Several clinics in one account

**Show one clinic, or all of them.** A clinic chooser now sits in the top bar,
beside the page title. On pages that list things it reads *Showing:*. Pick one
clinic or **All clinics**. Today, Appointments, Prescriptions and the Cash
Register follow your choice, and Patients, Receivables, Invoices, Revenue,
Patient Insights, Performance, Staff Performance, Services, Procedures and
Inventory show one section per clinic, each row marked with its clinic. A
record always opens at its own clinic. Settings pages read *Editing:* and
change one clinic at a time. If you switch clinics with unsaved changes, the
app asks first.

**Amounts in different currencies are never added together.** Each currency
gets its own total. A patient who owes at two clinics has a separate balance at
each, and each one is collected at the clinic it is owed to.

**Give each clinic a short name.** With more than one clinic you are asked for a
short name such as *Dokki*. Lists and queue numbers then read *Dokki·7*, so
rows from two clinics never look the same. You can change it in Clinic
Settings.

**Bookings and new patients say which clinic.** New Appointment and Add Patient
show which clinic the booking or record is for. If the patient you pick is
registered at another of your clinics, you choose: book them where they are
already known, or add them here as a new patient. A patient record shows
*Also at:* with a link to the same person at your other clinic. Each clinic
keeps its own name, number and balance for the patient.

**Today follows you between clinics.** A doctor who works at several clinics
sees *In your room* at the top of Today: every visit they have open, at any
clinic. *Next for you* shows who is waiting for you, and an *Also today* line
shows what is waiting at your other clinics, with a button to show that clinic.
Owners see one *Collected today* line per currency, added up across the clinics
they own. Today's shortcuts and the drawer button point at the clinic you are
working at, and you can change that from the shortcuts.

**Visits left open are caught.** A visit open for two hours or more, or since an
earlier day, moves to *Still in your room?*. From there you can **Complete
visit**, say **Still with patient** (it asks again later), or **Complete all**
for patients who have left. Completing from here collects nothing. Whatever the
patient owes stays on their account at that clinic. If a prescription with
medicines was written, completing the visit finalizes it.

**One cash drawer per clinic.** The Cash Register page lists *My drawers*. Each
clinic's drawer is opened, counted and closed on its own and never added to
another. The top bar says *Register open at Dokki*, and every collect form shows
which clinic the money is for.

**Staff who work at more than one clinic.** On the Staff page, **Works at**
lets you tick every clinic a person works at. They use one staff seat, however
many clinics you tick.

**Notifications show which clinic they are about**, with a small clinic tag
beside the time.

### Paying doctors and assistants

**A Compensation page for owners**, under Money. Set up a pay agreement for
each doctor or assistant. A doctor's pay can be a monthly salary, a percentage
of the cash collected on their visits or of what they billed, a fixed amount
per visit, a guaranteed monthly minimum, or a mix of these. Assistants are paid
a monthly salary. The page works out what each person earned month by month,
line by line, and what you still owe them.

Close a month to freeze it as a statement. Record the payments and advances you
hand over, including anything withheld, the payment method and a reference.
Recording a payment never takes money from the cash drawer and never adds an
expense. You can change someone's pay from a chosen date, end an agreement, or
void a payment or statement with a reason. Every change stays in the history.

**Doctor pay counted once in your profit and loss.** When you set up your first
pay agreement, it asks whether you already record doctor pay as a Salaries
expense. If you do, compensation stays out of your P&L. If you don't, the P&L
gets its own *Doctor compensation (earned)* line. You can change the answer
later in Clinic Settings. Staff Performance also gets a Compensation tab.

### Money reports

**Every money page now uses the same rules.** Revenue, Staff Performance and
Business Overview count cash on the day it was received, by your clinic's own
day and time zone. *Billed* is after discounts and write-offs. *Owed to you now*
is everything patients owe today. Pick the period at the top: Today, This
month, Last month or any month.

Until you dismiss it, a notice lists what may look different for past months.
For example, money taken for a booking before the visit now counts as revenue
on the day it was received. Expenses entered in another currency are listed on
their own line instead of being subtracted. Nothing you recorded has changed.

**On Staff Performance, "Collected on their visits" is now "Cash attributed".**
Each doctor is credited with the payments received in the period on their own
visits. Money that belongs to no one doctor is listed separately, below the
doctors. The page now has Money and Clinical tabs. **If you pay a doctor a
percentage of the old column, check past months before the next payout.** The
old figure is still on the Clinical tab as *Collected on these visits to date*.
The page reminds you too.

**For owners of more than one clinic, Business Overview adds a *Right now*
box**: package sessions paid for but not yet given, cash in open drawers, and
credit patients hold. It also breaks payments down by method and expenses by
category.

**Revenue and Clinic Settings have an *On this page* index**, so you can jump
straight to a section.

### Bookings and payments

**Create & collect now works for scheduled bookings, not only walk-ins.** You
can take payment when you book ahead, in full or as a deposit. For a scheduled
booking, *Just create appointment* stays the main button, so nothing is
collected unless you choose to. The money is held as a prepayment until the
visit starts. If the booking is cancelled, the money can be refunded or kept as
the patient's credit.

**Collect a prepayment later.** The page of an upcoming appointment has *Paid
ahead?* with a **Collect prepayment** button, for a patient who paid by
transfer, by card or with cash left at the desk.

**Money held on a booking that is not going ahead** can now be **kept as the
patient's credit** at your clinic, as well as refunded. Only a doctor or the
owner can do either. Keeping it as credit takes nothing out of the drawer. If a
booking now costs less than what was paid, the page explains what happens to
the difference. Appointment rows show *Prepaid 300* or *Held 300*.

**"Last session" on the appointments list.** When a visit uses the last session
of a prepaid service, its row carries a *Last session* label. Hover over it to
see *Session 6 of 6*. It is a good moment to offer a renewal while the patient
is still at the clinic.

**"Any doctor".** A booking with no doctor or assistant chosen now reads *Any
doctor* or *Any assistant*, with a short line saying that anyone in that role
at the clinic can take the patient.

**Closing a colleague's visit.** When you complete a visit booked with another
doctor, a tick box asks whether *I saw this patient*. Tick it and the visit and
its money are credited to you. Leave it unticked if you are only closing the
visit for them.

**Add to the catalogue without leaving the form.** An empty service or procedure
list no longer leaves you stuck. If your role may manage the list, you can add
the first item right from the booking form, every picker links to where the
list is managed, and an item you type can be added to the catalogue for next
time. Search finds Arabic names whether they are typed with or without hamza,
and with ه or ة, ي or ى.

### Patients

**Patient tags.** Label patients in your own words: VIP, Follow-up, Chronic or
anything your team uses. A patient can have up to ten tags, in nine colours.
You can add tags from the patient row, the patient record or the visit, and
create a new tag on the spot by typing its name. A clinic with no tags yet gets
five suggestions to start with. Filter the Patients list by tag, choosing *Has
all* or *Has any*. Patient Insights filters by tag too and adds a Tags column
to its table and CSV export.

Everyone at the clinic can add and remove tags, but only the owner can rename,
recolour or delete them, under Clinic setup → Patient tags. Tags are for staff
only. Patients never see them, and they are never printed.

**Correcting a date of birth shows what changed.** After you correct it from the
visit, a short note says how many days it moved, how many growth measurements
were re-scored and how many vaccine due dates were recalculated.

### Growth charts for children

**Record measurements on the Growth tab itself.** Each one is dated the day the
child was measured, with an optional note. **Record history** copies in a whole
growth card from home or from another clinic at once.

**Nothing is overwritten.** You can correct a wrong value, and the old one is
kept. Or you can withdraw it with a reason: it comes off the chart but stays in
the record. The measurement record lists every entry, who recorded it and when.

**The chart reads the trend, not just the latest point.** It says whether the
child is staying on a centile or crossing centiles, across which measurements
and by how much. A child sliding from the 50th to the 3rd centile is flagged
even when each step looks small on its own. When there is only one measurement,
the chart says it cannot show a trend yet. Each curve is labelled with its
centile, and you can choose which set of centile lines to draw.

**A second look before an unlikely value is saved**, such as a length lower than
at the last visit or a jump far too big for the time between visits.

### Veterinary clinics

**Every animal patient has an animal record**: which animal it is (dog, cat or
another), its breed, and whether it is neutered. You can also edit these from
inside the visit. They belong to the patient, so a change shows everywhere.

**Approximate age.** If nobody knows the birthday, enter roughly how old the
animal is, in weeks, months or years. Its age then shows with a ~.

**A vaccination card that follows the species**, with core and non-core
vaccines for dogs and cats. A course is dated from its first dose, so a missing
birthday doesn't stop the schedule.

**Recent weights.** An animal's last five weights appear on its record, with the
change since the previous one.

### Clinic setup

**Opening hours with two shifts.** A day can now have a morning and an evening
shift with the clinic closed in between, instead of calling the gap a "break".
**Apply to all open days** copies one day to the rest of the week, and
Saturday–Thursday or Sunday–Thursday presets fill the week in one go. The
editor shows which time zone the hours use. Suggested hours now say *nothing is
saved yet*, and you can save them as they are.

**New clinics start with opening hours.** A new clinic gets the usual hours
(Saturday to Thursday, 09:00–17:00, Friday closed) instead of none. When you set
up your first clinic, you see those hours and can confirm or change them. The
setup also asks for the clinic's time zone, and it picks the currency from the
clinic's phone number instead of your computer's language.

**Changing the clinic's specialty explains itself.** Before you confirm, a
dialog lists what will change, such as the form used for new visits and whether
treatment plans are on. If a change can't be made from settings, you can send a
request with your reason, and the reviewer's answer appears on the same screen.

**Staff changes are on record.** If the person you add already uses TabeebHub
elsewhere, they get an invitation and accept or decline it on their own screen.
You can cancel an invitation that is still waiting. Owners also get a **Change
history** on the Staff page that shows who added or removed whom, who changed a
role and who reset a password, and when.

**A shorter side menu.** Today's work stays at the top for every role, followed
by Money and Services & stock. Reports and Clinic setup stay folded until you
open them. A **Filter** box finds any page by name, in English or Arabic.
Profile, Notifications and Security have moved under your avatar, and the top
bar now shows the name of the page you are on. You may also see new menu rows
(Online requests, Online consultations or Payments to confirm, Consultation
balance, Public page and Online booking settings) and, for doctors who own
their clinic, a line on Today about a public page. These belong to the new
online booking and consultation features.

**Focus mode now hides the side menu too**, and its shortcut, Ctrl/Cmd + \,
works on every clinic screen.

**Back goes back to Today.** If you open an appointment or a visit from Today,
Back takes you to Today, not to the Appointments list.

### Prescriptions

**Share a prescription from the visit.** The visit's Prescription tab has
Print, Download, Share and Full page buttons, and a completed visit has Rx,
Print, Share and Empty Rx. Share copies a link or opens WhatsApp. For a child
without a phone, WhatsApp goes to the parent, and the message names your
clinic.

**Print brings you back to where you started**: the visit, the appointment, the
prescription or the prescriptions list.

### Plan and add-ons

**Each add-on now lasts a fixed number of days.** A top-up such as +100
appointments lasts the number of days stated on it, counted from the day you buy
it, whatever your renewal date. The monthly reset no longer touches it. Your
plan's own allowance is used first. Anything unused when the add-on ends is
lost. Billing shows how many extra you have and until when, for example *+100
extra until 30 Oct*.

### Faster, and always up to date

**Pages open faster and ask the server for less.**

**What you see stays current.** When something changes on another computer, on
a phone or on another page, the screens that show it update by themselves,
with no reload. Pages you leave open no longer keep checking the server in the
background.

### Fixed

- A doctor you have just added now appears in the *Assigned Doctor* list
  straight away, and a doctor you removed disappears from it, with no reload.
- The *previous balance* offered when completing a visit now matches the balance
  shown beside it.
- If your session was ended from another device, you now see the sign-in screen
  instead of a loading screen that never finishes.

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
