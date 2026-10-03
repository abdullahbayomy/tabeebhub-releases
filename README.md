# TabeebHub — Downloads

Official installer downloads for **TabeebHub**, clinic management software.

> This repository contains distribution binaries only. **No source code is published here.**

---

## Download

### Windows

**[⬇ Download TabeebHub for Windows](https://github.com/abdullahbayomy/tabeebhub-releases/releases/latest/download/TabeebHub-Setup.exe)**

Windows 10 or Windows 11, 64-bit. About 95 MB.

### macOS

**[⬇ Download TabeebHub for Mac — Apple Silicon](https://github.com/abdullahbayomy/tabeebhub-releases/releases/latest/download/TabeebHub-arm64.dmg)**

For Macs with an M1, M2, M3 or M4 chip. About 120 MB.

**[⬇ Download TabeebHub for Mac — Intel](https://github.com/abdullahbayomy/tabeebhub-releases/releases/latest/download/TabeebHub-x64.dmg)**

For older Macs with an Intel processor. About 126 MB.

> **Not sure which Mac you have?** Click the  menu in the top-left corner of your
> screen and choose **About This Mac**. If it says *Apple M1/M2/M3/M4*, choose Apple
> Silicon. If it says *Intel*, choose Intel.

These links always serve the newest version — they do not change when we release an update.

---

## What's new in 1.0.9

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

## Previously, in 1.0.8

This is the largest update the desktop app has had. It carries everything the
web app gained between 23 August and 16 September, so the two now match again.
It is long; skim the headings for the parts that apply to your clinic.

### Appointments and the calendar

**An appointment can have an end time.** New Appointment and Reschedule gain an
optional **End time** beside the start, with one-click lengths — 15 min, 30 min,
45 min, 1 h, 1 h 30 min, 2 h — and the slot reads back as *3:00 PM – 4:00 PM ·
1 h*. Moving the start keeps the length; clearing the start clears the end. An
end before or equal to the start, or a slot longer than 12 hours, is refused
with a sentence saying why. Booking a series, and the next visit booked at
checkout, take a plain start and end pair. Nothing is forced: an appointment
without an end looks exactly as it always did.

**The calendar draws appointments as long as they are.** In Week and Day view a
block is as tall as its slot, so a two-hour procedure and a fifteen-minute check
no longer look identical; appointments that overlap sit side by side by their
real times, and one without an end keeps the 30-minute block it always had. A
taller block carries more — name, time range, visit type, status — and hovering
shows the full details. Cancelled and no-show appointments are struck through
and dimmed in every view.

**Click an empty slot to book at that time.** In Week or Day view, clicking an
empty spot on today or a future day opens New Appointment with that day and
quarter hour already filled in, and the form says *Booking for Sat, Sep 20 ·
3:00 PM* above the patient search. Past days are shaded and cannot be clicked.

**The calendar answers the keyboard.** While it has focus, ← and → move by a
week or a day, **T** jumps to today, and **M**, **W**, **D** switch views. The
red line marking the current time now moves every minute, the view opens near
the day's first booking, Today is greyed out when today is already on screen,
and each day in Week view shows how many appointments it holds. The Week heading
that read "Sep 13 – 2026 (day: 19)" now reads "Sep 13 – 19, 2026", and weekday
headings are correct on computers set to a timezone west of Greenwich.

**Hold bookings to your working hours.** A new switch in Clinic Settings refuses
any booking outside the hours you have set — and for a single booking or a
reschedule it looks at the *end* of the slot, so a 4:30 PM ninety-minute booking
at a clinic that closes at 5:00 PM is refused too. It is off by default; leave it off to book emergencies, evenings,
or a day you opened anyway.

**Appointments show their range wherever they are listed.** The appointments
list reads *Today • 3:00 PM – 4:00 PM*, the appointment page header shows the
range, and so do the patient portal and the *Next:* line on Today.

### Today, patients and money

**Today replaces the dashboard.** The home page is now called **Today** and is
built around the patients in front of you rather than statistics: Expected
today, Waiting, With assistant, Ready for doctor, In room, To collect — in the
order that matters for your role, with one highlighted patient at the top for
clinical roles and a single button that starts or opens that visit. Search the
board by name, number or phone; a patient who has waited 20 minutes turns amber.
In a clinic with more than one doctor, doctors and owners can switch between
Everyone and Mine. The **New appointment** button offers Walk-in now, Book an
appointment, or New patient record. Starting a patient booked with another
doctor asks *Start anyway?* first, and if a colleague moved the patient a moment
earlier the board says so and refreshes. Owners keep a side column with Money
today and Plan usage; the Cash register tile shows Open with what the shift has
collected, or Closed.

**The side menu is regrouped by what you are doing.** Today's work, Money (Cash
register, Receivables, Invoices, Revenue), Clinic setup, Reports, Clinic
management and Account. Dashboard is now Today and Billing is Billing &
subscription.

**Patient rows say where each patient stands.** Each row on the Patients page
reads *In the queue*, *Booked today*, *Next: date*, *Owes amount* or *Not seen
yet*. Clicking anywhere on the row opens the record; WhatsApp and Book sit
beside the name, and Preview and Edit are under a ⋯ menu. The patient record
gains Book appointment and WhatsApp buttons in its header, and when an edit
contradicts what is on file — a different date of birth or sex, notes that would
be replaced — the dialog explains what it found and asks you to *Save anyway*
rather than overwriting silently.

**The Financial tab leads with what is owed.** One amber **Collect {amount}**
button comes first; Add charge, Record previous visits, Defer all, Apply credit
and Refund credit sit under **More**. Arriving from an appointment row, Today,
Receivables or the visit page opens the collect form already filled with that
visit's balance, and that visit is settled first. Refunds now ask *Refund
from*: cash from the drawer, or not from the drawer (a card, transfer or wallet
reversal), so a card refund no longer fails because a drawer happens to be open.

**The cash register behaves the same at every door.** Booking, Start & collect,
Complete & collect, the Financial tab, refunds and the Cash register page all
read the drawer the same way: a quiet *Register open* line, an amber notice when
it is closed (card, transfer and wallet still work), and Retry when it could not
be checked. Pressing **Open register** opens the drawer in place — what you had
typed stays put and the payment carries on. Cash is re-checked at the moment
you press the button, so a drawer closed on another machine is caught before
the visit starts rather than after.

**Booking shows the charges before you commit.** New Appointment now has a
procedure search and shows visit types as cards with their price. Before
anything is saved you review what the patient will be charged, then choose
**Just create appointment** or — for a walk-in, if you may collect —
**Create & collect {amount}**, which takes the payment right there, lets you
type a smaller amount as a deposit, and can settle the patient's earlier balance
in the same payment. If the appointment was created but the money could not be
taken, one message says exactly that and why. A greyed-out button now says what
is missing.

**The appointment page is grouped, and Start Visit is one decision.** On wide
screens the page is two columns under plain headings — Next step, Charges &
payment, Appointment information, Documents. Starting a visit is a choice of
who sees the patient first, Doctor or Assistant, and one button that names the
amount — *Start & collect 225* — or *Start without collecting*; a booking that
is already paid, prepaid from a package, or free says so instead of asking for
money. Procedures can be added before the visit starts, and the charge summary
stays on screen throughout, marked Paid, Partly paid, Unpaid or Deferred, and
reads the visit's real charges once it has started — a procedure the doctor
performed, an extra charge, a discount, money already taken. Rescheduling shows
the current slot, lets you keep the time, and warns that removing the time turns
the booking into a flexible day with no reminder. Money collected for a booking
that never went ahead shows as **Money held for this appointment** with a Refund
button for doctors and owners.

**The doctor's Complete & collect works like reception's.** The completion
dialog shows the itemised charges, an amount to collect pre-filled with what is
outstanding, the payment method, what remains and a *Defer the remaining
balance* choice, and an *Also collect previous balance* option with a
three-line breakdown. Money collected for this visit now settles this visit —
it used to be applied to an older debt first while the screen said the visit was
paid. Start & collect and Complete & collect can also take an earlier balance on
its own, a typed 0 no longer collects the entire balance, and if the visit
completes but the payment is refused the app says so plainly.

**Start, check in and collect from the Appointments list.** Each row carries the
same buttons as Today — Check in, Start visit, Start intake, Mark ready, Collect,
Defer — and WhatsApp.

**Record visits a patient paid for before TabeebHub.** When adding an existing
patient, or later from the Financial tab (More → Record previous visits), enter
the date and amount of visits they paid for before your clinic joined, naming
the services and procedures if you like. They join the patient's history as
already paid — nothing becomes outstanding, no drawer is touched — each one uses
one appointment from your plan, and they carry a *Before TabeebHub* badge and
stay out of your revenue reports.

**Revenue shows money held for visits that have not happened yet.** Owners get a
Prepaid appointments card whenever money has been collected for visits still to
come, split into Upcoming, Visit under way, and Cancelled or no-show.

### Children, parents and families

**Book a child on a parent's number.** The booking and Add Patient forms ask
whose number this is: the patient's own, or a guardian's. Choosing a guardian
records the child without a phone of their own and keeps the number on the
parent, so every child booked on one family number stays a separate record
instead of landing on a sibling's chart. The date of birth now sits above the
phone field; once it makes the patient under 18 the number is assumed to be a
guardian's. As you type a number that is already on file, the form shows the
guardian's name and the children she already brings, each openable or bookable
in one click. A patient with their own number can also have a guardian, via a
checkbox that opens a separate Guardian's phone number field.

**A Guardians section on every patient record.** See who brings this patient,
with their relation and number; add a guardian, link one already on file, edit
her details (the change applies to every child she brings), remove her from
this patient, mark the primary one, and jump to the other children she brings.
Within a year of a guarded child's 18th birthday the section says *Turning 18
soon* and offers to add the young adult's own number, since a phone is how they
will sign in to their own history.

**Find a child by the parent's phone number.** Searching the patients list or
the booking form by a parent's number brings up every child she brings, and each
result says who brings them.

**Siblings are told apart on every list.** The queue, the appointments list,
Start Next Patient, the appointment page and the visit header now show the
patient's number, their age and who brings them beneath the name — so every
patient with a clinic number now shows *#42* under their name, and two siblings
who share a surname and a guardian are no longer identical rows.

**Parents can see their children's records in the portal.** A parent who signs
in to the patient portal can link the records a clinic holds under her number
with a verification code, then switch between herself and each child; their
appointments and prescriptions follow.

**A patient can be recorded as a person or an animal.** Every patient record has
a *Who is this patient?* section. An animal carries an *Animal* badge, and the
allergy, interaction and dose checks — built for people — say *Not assessed*
for it rather than all clear. Veterinary clinics book an animal and its owner:
the phone field is *Owner's phone number*, there is no relation picker, and an
owner's children at a human clinic are never offered as patients of the other.

### Pediatric clinics

**Growth charts.** A **Growth** tab on the record of every child (and inside the
visit, after Chief Complaint). Every weight, height, head circumference and
mid-upper arm circumference recorded in the assessment is scored against the WHO
Child Growth Standards and plotted with its z-score, percentile and a status
such as *Low* or *Within normal range*; each measurement can carry the date it
was actually taken. When a percentile cannot be produced the chart says exactly
why — no date of birth, no recorded sex, older than five, or a reference that
only starts at three months — and still lists the raw values. Beyond five years
the chart offers the CDC Growth Charts for weight and height up to twenty, and
every number says which reference produced it; nothing switches on its own.

**Corrected age for babies born early.** Record the gestational age at birth in
weeks and days from the Growth tab and growth is scored at the corrected age up
to two years, so a preterm infant no longer reads as failing to grow. A Down
syndrome head-circumference curve can be drawn alongside, and when an
assessment records a GMFCS level the chart notes whether the child's weight is
below the published cerebral-palsy threshold.

**The pediatric assessment is rebuilt.** A Vitals section of its own —
temperature, heart rate, respiratory rate, oxygen saturation, blood pressure —
and an examination organised by body system: tick the systems with findings and
each unfolds into structured choices with a free-text box beside it. A Neonatal
Jaundice section records everything a bilirubin decision is made from, and the
visit's Growth tab then opens with a jaundice panel plotting every reading
against hours of life. Vitals entered in the assessment flow to the visit's
vitals card and the patient's timeline, and a new assessment pre-fills the
vitals already on the card so nobody retypes them — weight and height are
deliberately never pre-filled, because they must be measured at this visit.
Everything recorded on the old form still shows.

**A vaccination card.** A **Vaccinations** tab on every child's record, in the
visit after Growth, and a summary card at the top of the overview. It lays out
the government schedule and optional vaccines dose by dose — Given, Due,
Overdue, Upcoming, Not applicable, or Covered by another vaccine — with a
*Next: vaccine · dose · due date* line. Record a dose as given today or on
another date, here or transcribed from the paper card, with product, lot number
and notes; *Record history* transcribes a whole card in one go. Mark a dose or a
whole vaccine not applicable with a reason, switch the product being tracked,
and see a warning when a dose is early or out of order. Every dose also appears
on the patient timeline. Recording is for owners, doctors and assistants.

**A child's exact age.** Ages are no longer rounded down to whole years, so a
six-week-old no longer reads as *0 years*: days, then months and days under a
year, years and months up to twelve, years alone after that — everywhere a
patient is shown, in English and Arabic.

### Other specialties

**Orthopedic surgery: the chief complaint is built from chips.** Region, exact
site, side (and the worse side when both), the symptoms as reported, how it
started and for how long — tapped, not typed twice. Injury details, spine
screens, the cast check and post-op events appear only when the answer they
belong to is chosen; a live Summary shows the sentence as it is built and
becomes the headline on lists. Continuing an assessment into a new visit carries
the problem and asks again only about today. Old assessments keep their typed
complaint exactly as written.

**OB/GYN: obstetric history one row per pregnancy.** Outcome, gestational age,
year, delivery mode, number of babies, how the child is now, gestational
diabetes and complications, replacing the two Gravida/Para boxes; GTPAL and
living children are entered as a summary of that table, with a reminder that
Para counts deliveries. Current-pregnancy dates have their own section, plus
Risk flags and Medical history. Any assessment table wider than four columns
now renders as one labelled card per row instead of a squeezed spreadsheet.

### Across the app

**Patient notes that stay on file.** The appointment page has a Patient notes
panel under the patient card. Write a reminder such as *Call before booking —
works night shifts* and it stays on the patient's file at your clinic for every
future visit, visible to staff and never to the patient. You can edit your own
notes; owners can also delete anyone's.

**Message a patient on WhatsApp from anywhere.** A WhatsApp button on patient
rows, the quick preview, the profile header, appointment rows and details,
Today and guardian rows. It opens a chat with the number that actually reaches
the patient — the guardian's for a child without a phone, and the label says so.

**Phone numbers are checked against the selected country.** Every phone field
now checks the number against the country's real numbering rules and explains a
problem under the field — *Not a valid phone number for Egypt*, *This phone
number looks incomplete* — once you have finished typing. Arabic digits are
accepted. Sign-in only asks that the number looks plausible, so existing
accounts are never locked out, and a stored number you did not touch is never
re-checked.

**The visit workspace folds its side panels away.** The Queue and Clinical
alerts panels each collapse to a narrow strip, and **Focus** in the top bar (or
Ctrl/Cmd + \) folds both to give the clinical form the full width. Your choice
is remembered, the section tabs page sideways when there are more than fit, and
the whole page scrolls as one. The patient details card always shows Gender and
lets a doctor or assistant set it there, since an unrecorded sex is what keeps
growth scoring and Women's Health from appearing.

**Patient Insights starts with everyone.** It opens on All patients, followed by
the follow-up lists; a Filters button narrows any list by birthday (today or
this month), an age or date-of-birth range, number of visits, and — for owners —
total paid, each shown as a chip you can remove. The CSV export is the whole
list, not the first page.

**A forgotten visit is flagged.** A visit left open with the doctor for more
than four hours carries an *Open 5h* badge on its appointment card; in the last
four hours before the 16-hour mark it turns red and reads *Auto-closes in 2h*.
A visit still open at 16 hours is closed by the system with no payment and no
doctor credited, so the badge is there to get the desk to close it properly.

**Collect says when a payment will count as an appointment.** Opening Collect
on a patient's Financial tab tells you, before any money changes hands, when
settling a balance for a patient last seen more than a day ago will use one of
this month's appointments — and if none are left, the button is disabled and
the message says what to do first.

**Owners can correct a drawer's opening balance.** On the Cash Register page, a
pencil beside any drawer that nobody has counted yet. Enter the right float and
a reason; expected cash is recalculated, and the person holding that drawer sees
*Opening balance corrected* with the old and new figure, who changed it and
why. Once a drawer has been counted, its float is frozen.

**Business Overview reports expenses and net profit** alongside revenue, per
currency and per clinic, with the margin shown once every clinic in the group
has costs recorded — a clinic with no costs shows a dash and a notice, because a
profit with no costs behind it is only revenue. Pricing now sits directly under
Basic Information in Clinic Settings.

### Fixed

- Refusals are shown with their real reason — *Open a cash register before
  collecting cash*, *The drawer does not hold that much cash*, *This appointment
  was already updated by another staff member* — instead of *something went
  wrong* or *Please try again*.
- Add-on capacity is counted correctly: a doctor at 300 of 300 who bought 100
  more could previously book only 50 of them.
- Patient search waits for you to stop typing instead of searching on every
  keystroke and flashing *no patient found* in between.
- Signing in after a session expired returns owners and assistants to the page
  they were opening, as it already did for doctors and receptionists.
- Dialogs opened inside the booking form — Add phone number, Upgrade plan, Open
  register — no longer close the booking form underneath them.
- The patient timeline no longer shows internal label codes for Scheduled,
  Cancelled, No-show or imported past records.
- Editing an appointment's medical information no longer fails over a blood
  pressure you did not touch; impossible readings such as 80/120 are refused.
- Cancelling a prepaid service says *moved to patient credit* rather than
  *refunded* when no cash left the till.
- After collecting at the start of a visit, the charge summary and an open
  Revenue page refresh instead of showing the old figures.
- Closing the register with a blank or negative counted amount is refused
  rather than recorded as 0.

> **Nothing to download.** If you are on 1.0.5 or later, this update installs
> itself — it downloads in the background and applies when you next quit the app.

---

## Previously, in 1.0.7

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
