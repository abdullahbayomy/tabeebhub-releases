# TabeebHub — Downloads

Official installer downloads for **TabeebHub**, clinic management software.

> This repository contains distribution binaries only. **No source code is published here.**

---

## Download

### Windows

**[⬇ Download TabeebHub for Windows](https://github.com/abdullahbayomy/tabeebhub-releases/releases/latest/download/TabeebHub-Setup.exe)**

Windows 10 or Windows 11, 64-bit. About 97 MB.

### macOS

**[⬇ Download TabeebHub for Mac — Apple Silicon](https://github.com/abdullahbayomy/tabeebhub-releases/releases/latest/download/TabeebHub-arm64.dmg)**

For Macs with an M1, M2, M3 or M4 chip. About 123 MB.

**[⬇ Download TabeebHub for Mac — Intel](https://github.com/abdullahbayomy/tabeebhub-releases/releases/latest/download/TabeebHub-x64.dmg)**

For older Macs with an Intel processor. About 129 MB.

> **Not sure which Mac you have?** Click the  menu in the top-left corner of your
> screen and choose **About This Mac**. If it says *Apple M1/M2/M3/M4*, choose Apple
> Silicon. If it says *Intel*, choose Intel.

These links always serve the newest version — they do not change when we release an update.

---

## What's new in 1.0.18

This update brings a calendar that keeps busy days readable, a new structured
Cardiology Chief Complaint, and a clearer "today" for clinics whose day starts
after midnight. Continue, vitals and prescribing alerts are more careful about
what they claim, and a patient account can now join a clinic's staff.

### For every clinic

- **Busy days on the calendar.** In **Day** and **Week**, short appointments
  back to back no longer pile up on top of each other. A busy stretch of the
  day grows taller so each appointment is tall enough to show its name, in
  time order, and quiet hours keep their usual height. Appointments at the
  very same time still sit side by side. An hour that grew shows extra *:30*
  (or *:15* and *:45*) marks with their own lines, and a click on a line
  books that time. When a booking, a move or a cancellation, here or at
  another desk, makes a busy stretch grow or shrink, the part of the day you
  were reading stays where it was. In a narrow column, the patient's name
  gets the space instead of the start time.
- **"Today" when your clinic's day starts after midnight.** Some clinics count
  their day from a later hour. If yours starts at 12:00 AM, nothing changes.
  If it starts later:
  - On **Appointments**, a row says *Today*, *Tomorrow* or *Yesterday* only
    when the clinic's day and the calendar agree; otherwise it shows the
    date. So a booking for tomorrow evening no longer says "Today" under
    **Upcoming**.
  - The **Today** board shows the date it is counting, and until the
    clinic's day changes it says so: *The clinic's day changes at 3:00 PM —
    until then, Today is Sunday.*
  - Where the board shows **Collected Today**, it says which day it counts
    (*Sunday · until 3:00 PM*). An owner looking at all their clinics sees,
    under **Collected today**, a note when a clinic is still counting its
    previous day. Both refresh on their own when the clinic's day changes.
  - The calendar opens on today's date, and its **Today** button goes there,
    even before the clinic's day has changed. A booking you make appears
    straight away under Today or Upcoming by the clinic's day.
- **The series calendar marks today.** In **Book a series of appointments**,
  the calendar now rings today's date, not yesterday's.
- **Continue starts today fresh.** When you press **Continue** on an
  earlier assessment in **Chief Complaint**, the new note now leaves behind
  what belonged to the last visit (on most forms the complaint, the
  examination and the findings) and brings across what belongs to the
  patient, such as the history and, on many forms, the diagnosis. So last
  visit's examination no longer comes across as today's. The specialty
  sections below say what changed. On forms where the complaint is a typed
  box, it starts blank, and the note can't be saved until you type today's.
  Computers and phones that haven't updated yet follow the same rules.
- **Continue says what it carried.** The message after **Continue** names
  only what really came across: *Carried forward — only “Course” and
  “Working Diagnosis” came across; the rest of the note starts blank*. When
  more came across, it says so and asks you to *check each one is still true
  today*. When the complaint needs typing, it adds *Type today's complaint to
  save the note.*
- **A 0–10 scale can be cleared.** An unanswered severity, pain or itch scale
  is drawn faded, showing "—". The first click records the value, including
  0 (a click on 0 used to record nothing), and **Clear** takes the answer
  away.
- **Only this visit's vitals count as today's.** On the visit page,
  **Vitals** shows a reading taken at this visit with its time. A reading
  from an earlier visit is shown faded with *Last:* and its date. It is never
  copied into today's boxes, and the Chief Complaint forms don't take it as
  today's either. When you edit, a box starts empty unless the reading was
  taken at this visit, so type today's value if you measured it. When BMI
  uses today's weight with an earlier height, it says so (*Height from* and
  the date).
- **Weight and height at the desk.** On the appointment page, **Medical
  information** opens weight and height empty unless they were measured for
  this appointment. Doctors and assistants see the earlier value inside the
  empty box as a hint (*Last:* with the value and date). Saving only a
  weight no longer copies the last visit's blood pressure, oxygen, glucose
  or breathing rate into today's reading.
- **No false *All Clear*.** The allergy check can only check against a list
  somebody recorded, so **Clinical Alerts** on the visit page no longer shows
  a green *All Clear*. When the patient has no allergy list on file, doctors
  and assistants see **Allergies not recorded**: *No allergy list on file, so
  this prescription was not checked against one. Ask the patient before
  prescribing.* A recorded list shows in its allergy card, as before.
- **Trying to conceive.** For a woman recorded as trying to conceive, doctors
  and assistants see **Recorded as trying to conceive** in **Clinical
  Alerts**: *Ask before prescribing teratogenic medicines — the safety checks
  here don't cover pregnancy.*
- **The prescription page says what it checked.** The **Safety** tab says
  *No interaction, dosage or duplicate issues* instead of "passes all safety
  checks", and reminds you that allergies and pregnancy aren't checked on
  that page. For doctors and assistants, the patient card no longer says *No
  known allergies* or *No chronic conditions* about lists it doesn't load.
  Instead it says *Not shown on this page — check the patient's record
  before prescribing.*
- **The diagnosis on the PDF.** The prescription PDF (**Download PDF**, and
  the PDF behind a shared link) now prints the diagnosis written on the
  prescription.

### Cardiology clinics

For cardiology and cardiothoracic surgery clinics.

- **A structured cardiology consultation.** The **Chief Complaint** form
  replaces the old form's free-text boxes with a guided consultation:
  **Visit** (visit type and the patient's own words), **Since last visit**,
  **Anticoagulation (warfarin)** with today's INR, symptom cards (**Chest
  pain**, **Breathlessness**, **Palpitations**, **Fainting**, **Swelling and
  fluid**, **Leg pain on walking**, **Stroke-like symptoms**, **Cough and
  fever**), a **Background** that carries from visit to visit, **Today's
  vitals**, an **Examination** with a murmur table (**Add murmur**), **ECG**,
  **Echo**, **Tests and labs**, **Assessment** and **Plan**. A note for a
  follow-up booking starts with the visit type set to **Follow-up**.
- **Continue first.** When the patient has an earlier Cardiology note, the
  form offers **Continue from** its date, or **Start blank**. Continue brings
  the history, medicines and conditions; today's symptoms, findings and plan
  start blank. On a return visit, the summary lists the medicines as
  *Cardiac medicines (carried, not reviewed today)* until you record today's
  decision on them.
- **A summary that leads with the decision.** The summary reads Assessment
  and Plan first, then the story, background, examination and tests. When
  today's findings add something the Background doesn't hold yet, it opens
  with *Add to Background:*. Today's diagnosis is what you assessed today,
  and a condition carried from before that wasn't reviewed is listed as
  *Known, not reviewed today*. If LVEF, a valve's severity, the rhythm or the
  INR wasn't recorded today, it shows the *Last known* value with its date.
  Where the note holds what they need, CHA₂DS₂-VA, HAS-BLED, RCRI (before an
  operation), eGFR and whether the LDL is at goal are worked out and printed
  under *Calculated*. A long summary folds, with **Show all**.
- **Warnings that ask for a decision.** Some warning signs call for a
  referral and some can be handled in clinic. While an emergency warning has
  no referral decision, the form adds *Emergency warning with no referral
  decision — record ER, admission, urgent referral or “declined” in Plan*.
  **Disposition** in Plan records the decision, from **Acted on in clinic
  today** to **Urgent same-day referral**, **Send to ER now**, **Admit** or
  **Declined the advised referral**. If warnings are still waiting for a
  decision when you press **Mark Complete**, the app lists them under
  **Warning signs still raised** and offers **Go to Plan** or **Complete
  anyway**.
- **Numbers you can trust.** Number boxes accept Arabic digits and "1,250".
  An impossible value is marked *Outside the possible range* and the note
  can't be completed until it's fixed; an unusual one is marked so you can
  check it.
- **Unsaved answers are kept.** Switching tabs on the visit keeps what you
  typed, and closing the form with unsaved answers asks **Leave without
  saving?** (**Keep editing** or **Discard changes**).
- **Today's vitals, read-only.** **Today's vitals** shows the readings from
  the visit's vitals panel (edit them there), and says the day when a
  reading isn't today's.
- **Older notes.** A note written in the old form still opens with all its
  answers. Its old free-text examination boxes are kept, marked *No longer
  asked*, and the summary prints them as *Earlier exam notes*.
- **Update every computer.** A computer that hasn't updated to 1.0.18 can't
  save a Cardiology note. It asks to be updated first, so nothing written in
  the new form is overwritten.

### Psychiatry and psychology clinics

- **The booking note is for the doctor.** A note the patient leaves when
  booking online is now for the doctor, as at OB/GYN clinics. Reception sees
  *The patient left a note — it's for the doctor.*
- **Continue** brings across only the **Working Diagnosis**. The **Risk
  Assessment** and today's complaint start blank.

### Neurosurgery clinics

- **Continue** now leaves the headache pattern behind, and a warning can't
  light from carried answers alone.
- **Spine and cancer.** With a cancer history, the warning for spine or cord
  symptoms now needs a neurological symptom or sign answered today: a red
  flag or myelopathy symptom ticked, a deficit on today's examination, or
  sciatica, arm pain, claudication, weakness, leg numbness or an unsteady
  walk with today's spine questions answered. Spinal pain with a cancer
  history and no such sign adds a line to the summary instead: *cancer
  history with spinal pain: MRI within a week (NICE NG234)*.

### Other specialties

What **Continue** brings across, and what else changed:

- **General and family medicine, and every specialty without its own
  form:** **Past Medical History**, **Current Medications**, **Allergies**
  and the **Working Diagnosis**. The **Allergies** box now says the
  prescription allergy check reads the patient's profile, not this box, and
  **Objective / Examination** and **Plan** open unfolded.
- **Internal medicine and the specialties that use its form:**
  **Comorbidities** and the **Working Diagnosis**. **Systems Review
  (positive)** gains **No other symptoms**, and **Examination** opens
  unfolded.
- **Eye clinics:** the **Affected Eye**, the **Working Diagnosis** and the
  **Management Plan** (so the drops written there carry over).
  **Examination** opens unfolded.
- **Dermatology, cosmetic, aesthetic, laser and hair transplant clinics:**
  the **Course** and the **Working Diagnosis**.
- **ENT clinics:** the **Symptoms** and the **Side**.
- **Dental clinics:** the **Tooth Number(s)**.
- **Orthopaedic clinics:** the region and the complaint you picked still
  come across, but **Cast / splint check** and **For how long** now start
  blank.
- **Physiotherapy and sports medicine:** the problem, its history, the
  diagnosis, goals and the plan of care. Findings, the pain score, red flags
  and the session note start blank. **Session Note (Quick Format)** moves up
  to second place and opens unfolded, **Occupation** and **Referring
  Physician** are back, and **Red Flags** opens unfolded and gains **None
  (screened)**.
- **Pediatric clinics:** Continue now asks again for the plan, the follow-up
  and the milestones. On the growth chart, a weight or height that was only
  sent again, not measured again, is no longer plotted as a new point.
- **Veterinary clinics:** only the **Working diagnosis**. A follow-up now
  asks **Since the last visit** (**Resolved**, **Improving**, **About the
  same** or **Getting worse**), and **Examination** and **Plan** open
  unfolded.

### Clinic owners

- **Hire someone who has a patient account.** In **Staff → Invite Staff**,
  the number of an existing patient account is no longer refused. You can
  invite them as a doctor, an assistant or a receptionist. The form says *An
  existing TabeebHub patient account — they'll be asked to accept and keep
  their patient records.* Their name stays hidden (the pending list and the
  staff history show the number you typed) until they accept. Someone who
  already holds a staff role can still join only as that role, and the form
  says which one.
- **What they see.** The invitation appears on their patient home, and its
  notification opens it there. The card explains that accepting makes the
  account clinic staff too and keeps their patient records. **Accept** sends
  a code to their WhatsApp. They enter it, press **Confirm and join**, and
  the clinic opens. One login keeps both their patient records and their
  clinic work, and the menu switches between them, whichever way they signed
  in. On **Enable Patient Access**, the way back now reads **Continue as
  clinic staff** instead of "Continue as Doctor".
- **The day-start setting explains itself.** In **Clinic settings →
  Operational day**, the hour is now called **The clinic's day changes at**.
  The setting says it is not your opening time and what it does to Today,
  the board and Collected today. It warns when your clinic closes well
  before midnight, or when the hour falls inside your working hours and
  would split a session across two days.

### Also

- **Unsaved work asks before closing.** With unsaved changes on a visit (in
  the Glasses Rx, Laser or Cardiology forms, for example), closing the
  window, quitting or reloading now asks *You have unsaved changes* with
  **Leave** or **Stay**. Before, the app just stayed open and didn't say
  why.
- A receptionist who is also a patient now sees their own prescriptions in
  full, instructions and notes included.
- In Arabic, a phone number in the staff history keeps its "+" in the right
  place.

> **Nothing to download.** If you are on 1.0.5 or later, this update installs
> itself. It downloads in the background and applies the next time you quit the
> app. The download links at the top of this page have not changed.

---

## Previously, in 1.0.17

This update brings the desktop app everything the web app gained since
1.0.16: amending a completed visit, a calendar without cancelled
appointments, and new tools for dental, eye, laser and OB/GYN clinics.

### For every clinic

- **Amend a completed visit.** On a paid plan with unlimited visits, the
  clinic owner or the doctor who treated the visit can press **Amend visit**
  on a completed visit until the end of the seventh clinic day after it. Add
  findings, notes, an assessment or files: each is marked *Added after
  completion* and listed under **Changes after completion**, and the
  prescription and the bill don't change. The plans that include it now say
  *Edit completed visits for 7 days*.
- **Cancelled appointments leave the calendar.** In Month, Week and Day, a
  cancelled appointment is no longer drawn, so its time looks free again and
  the day's count and *+N more* leave it out. A no-show stays on the
  calendar, so it can still be reinstated. The legend no longer lists
  cancelled appointments, and when the calendar shows several doctors its
  grey key now reads **Missed**.
- **A pregnancy check before prescribing.** In **Clinical Alerts** on the
  visit page, a pregnant patient never shows *All Clear*: a **Pregnant** card
  reminds you to check every medicine for use in pregnancy. For a woman aged
  12 to 55 with no pregnancy status on file, it asks **Could she be
  pregnant?** *Ask before prescribing.*
- **Consumables on a service.** In **Services**, a service can list its
  **Consumables per visit** (gel or tips, for example). They come out of
  stock once for each visit that uses the service, and are never billed.

### Dental clinics

- **Pulp Caries.** A new condition for decay that has reached the pulp, in
  **Record Condition**, as a procedure's **Resulting status**, or as the
  result when you mark a treatment done. **Caries** now colours the crown
  only, while **Pulp Caries** colours the whole tooth and draws the pulp and
  a thin line down each root, so it never looks like a root canal. A computer
  or phone that hasn't updated yet shows it as **Caries**, and nothing is
  lost.
- **The chart reads the same in Arabic.** The Dental Chart keeps the order
  dentists chart in, **18 … 11 | 21 … 28** over **48 … 41 | 31 … 38**, left
  to right in both languages. The buttons, summary and legend around it still
  read right to left.

### Eye clinics

- **A Glasses Rx tab.** At ophthalmology clinics, the visit page has a
  **Glasses Rx** tab after Chief Complaint: SPH, CYL, AXIS and ADD for each
  eye, prism (BI/BO and BU/BD), a balance lens, PD, lens type, use and lens
  options. Type values the way you say them (−2.25, +1, or pl for Plano), or
  step by 0.25 with ↑ and ↓, and **Copy the last prescription** starts from
  the previous one.
- **Checked before it goes out.** *Check before issuing* warns about things
  like eyes more than 2.00 D apart or a bifocal lens with no ADD, and a wrong
  value says the allowed range or *Did you mean −1.50?*. An assistant or a
  doctor can **Save draft**; only a doctor can press **Issue to patient**,
  and the patient then sees it in their app. A complete draft still waiting
  when a doctor completes the visit is issued then.
- **Correct, withdraw, print.** An issued prescription is never edited: a
  doctor can **Correct** it, which issues a new version with a reason, or
  **Withdraw** it. **Print** gives an A5 page for the optician, and the desk
  prints it from the appointment page with **Print glasses Rx**.

### Laser clinics

For dermatology, cosmetic dermatology, aesthetic medicine and laser clinics.

- **The laser record.** A **Laser** tab on the visit records the
  **Operator**, the supervising doctor, skin type and consent, then each area
  treated: status, device, settings, pulses, endpoint and reaction. Each area
  starts from its last session, muted until you change it, and warnings (a
  big jump in settings, a reaction last time, too soon since the last
  session) never stop you. A clinic set up as a laser clinic opens every
  visit on this tab.
- **Prices per area or per pulse.** On **Procedures**, **Laser price list**
  turns the areas you tick into priced procedures the desk books, billed per
  area with no consultation fee. A procedure can also be charged **Per
  pulse**, with a **Rate per pulse** and optional volume tiers.
- **Pulse cards.** In **Services**, choose **By pulse** to set up a card of
  pulses to sell, with gift pulses, how long it stays valid, a device type
  and refund terms. On the visit, **Deduct pulses** takes the session's
  pulses (a total, or the device counter's start and end) off the patient's
  cards, and offers **Sell another card** or billing the rest per pulse when
  they run short.
- **Booking.** A laser booking is paid by its areas, a card or course, or
  follows a paid session within 60 days at no charge, and the form says when
  a card could cover the areas instead. On the Appointments list, **Card
  nearly empty** marks the moment to offer a new one.
- **Cards on the patient's profile.** The **Services** tab shows each card's
  pulses left, expiry and history. The owner can **Extend** it or **Put on
  hold**, and the owner or a doctor can **Settle** a card that has been
  used, showing what was used, what the clinic keeps and the credit to the
  patient. A **Laser** tab lists every session and each area's settings over
  time.
- **Devices and the register.** **Clinic settings → Laser devices** keeps
  each device's type, serial number, starting counter and NILES certificate,
  and **Laser register** lists every session in a date range, to print or
  save as CSV. **Services** lists the clinic's pulse cards, soonest to expire
  first, and **Financial policies** sets your **Pulse card refunds**. In
  **Add Patient**, the owner can carry over a card bought before TabeebHub
  with **A pulse card (custom)**.

### OB/GYN clinics

- **Reception fills it in, the doctor dates it.** When booking, reception
  records what the patient reports (pregnancy status, last period and cycle
  length), marked *As the patient reported — the doctor confirms the
  dating.* Doctors and assistants see the gestational age and estimated due
  date while she is pregnant; reception never sees the due date.
- **Continue starts today fresh.** **Continue** on an OB/GYN assessment
  brings the history and risks across, and today's complaint, findings,
  diagnosis and plan start blank.
- **A booking note for the doctor.** A note the patient leaves when booking
  online is for the doctor; reception sees *The patient left a note — it's
  for the doctor.*
- **Teenagers' privacy.** From age 13, a guardian sees only the appointments
  they booked here, as a date and the clinic. Under **Guardians** on the
  patient's profile, a doctor can let a guardian see this clinic's visits,
  prescriptions and files, and the app asks first.

### Reception

- **Invoices without the clinic's totals.** On **Invoices**, reception no
  longer sees **Total billed** or **Collected**. The number of invoices,
  **Outstanding** and each invoice's own amounts stay.
- **One question at X-ray, lab and laser desks.** At radiology, laboratory,
  dermatology, cosmetic dermatology, aesthetic medicine and laser clinics,
  booking a woman asks **Could she be pregnant?** (**Yes**, **No** or **Not
  sure**) in plain view. The answer is for the doctor and isn't shown at the
  desk again.
- **Women's-health questions only where they belong.** At other clinics
  (not OB/GYN), reception no longer sees them. A patient with pregnancy or
  period information on file can't have her sex changed from the desk; a
  doctor who can see that record has to change it.

### Clinic owners

- **A first WhatsApp reminder on the day.** In **WhatsApp appointment
  reminders**, the **First reminder** can now be **1**, **2** or **3 hours
  before (on the day)**. It is the only reminder, so the same-day second
  reminder is off. It's never sent within an hour of the booking, and one
  that would fall at night goes at 09:00 if that's still at least 47 minutes
  before the appointment; otherwise it isn't sent.
- **Each clinic's own reminder number.** On **Money → WhatsApp reminders**,
  when you own more than one clinic, the card names the clinic it's for
  (*Reminders from* and the clinic's name, then the number) and remembers
  your pick when you reload. **Change**, next to the number, opens where it's set:
  Clinic settings, or your public page when that's the number used.

### Also

- An update never restarts the app while you're amending a visit.
- On a completed visit, the **Growth** tab records measurements too.
- The QR code on a printed prescription is now drawn by the app itself,
  instead of by an outside service.

> **Nothing to download.** If you are on 1.0.5 or later, this update installs
> itself. It downloads in the background and applies the next time you quit the
> app. The download links at the top of this page have not changed.

---

## Previously, in 1.0.16

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
