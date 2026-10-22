---
layout: default
title: Privacy Policy — Elderly Care
---

# Elderly Care — Privacy Policy

**Last updated 22 October 2026.**
Applies to Elderly Care for iPhone, published by School Fab Lab.
{: .meta}

Contact for anything on this page: **nader@schoolfablab.com**

## The short version

Elderly Care keeps what you tell it on your iPhone.

There is no account to create. There is no server of ours. There is no
analytics, no crash reporting service, no advertising, and no third-party
company that receives anything about you. Nothing you record is sold, shared
with anyone you have not chosen, or used to train anything. Paying for the app
is done through Apple; we never see your card.

Seven things can leave your iPhone. Two happen only if you switch them on, one
only if you choose to sign in, one only if you invite someone into your
circle, two happen while you are using features that need them, and one is a
download — Smith's voice, fetched once. All seven are described below, in
full. An eighth item is there for completeness and goes the other way: a
message from us, which your iPhone reads and which carries nothing about you.

## What Elderly Care holds, and where it lives

<div class="tablewrap" markdown="1">

| What | Where it is kept |
|---|---|
| Memories, body notes, the mood you note each day, medication history, settings | A database file inside the app on your iPhone |
| The full text of a document you import | The same database, whole and unabridged |
| Your picture, and the colours read from it | The app's own storage on your iPhone |
| Routines you ask Smith for (their words, days and times) | The same database on your iPhone; the reminders themselves are held by iOS on this iPhone |
| Your circle: who is in it, what they see, and their suggestions and notes | The same database on your iPhone. What you choose to share is also kept in a space in your own iCloud that you share with them (section 7) |
| Scanned place maps | The app's own storage on your iPhone |
| The picture of each object you scanned in the Lab, beside its memory | The app's own storage on your iPhone |
| Your chosen voice | iOS preferences on your iPhone |
| Apple Health figures | **Not copied.** Read live when shown, and not stored |

</div>

When you import a document, iOS gives the app a temporary copy. Elderly Care
reads the words out of that copy and deletes it. Your original file is never
moved or changed.

## What leaves your iPhone

### 1. Your memories in your own iCloud — only if you switch sync on, or sign in with Apple

iCloud sync is **off by default**. It is switched on in two ways, both of
them yours: by turning it on in Settings, or by signing in with your Apple ID,
which turns it on for you the first time. Signing in is a deliberate act, and
keeping your memories safe and in step is most of what it is for. If you have
ever switched sync off yourself, signing in again does not switch it back on.

When it is on, your memories are kept in **your own iCloud private database**
and in step across your iPhones: a memory you add or remove on one iPhone is
added to or removed from your iCloud a few seconds later, and appears on, or
disappears from, any other iPhone signed in to the same iCloud when that
iPhone next opens the app. A memory already on an iPhone is never overwritten
by the copy in iCloud.

That is your iCloud account, not a server belonging to us. School Fab Lab has
no credentials for it, no way to read it, and no way to list who has records in
it. Apple keeps it encrypted, on its servers and on the way there, with keys
Apple holds, as it does for most iCloud data: Apple can decrypt it on your
behalf. Turning on Advanced Data Protection for iCloud does not change that for
these copies, because Apple's end-to-end protection for an app's data covers
its encrypted fields, and Elderly Care keeps your memories in ordinary ones.
What you share with your circle is kept differently (section 7).

For each memory, the copy contains exactly:

- what kind of memory it is
- its text
- when it happened, and when it was filed
- the people, places, emotions and themes tagged on it
- the full text of a document, if that memory came from one

**Not included, and never synced:** your picture, the colours read from it,
the pictures of objects you scanned, your name, your Apple identifier, your
body notes, your mood notes, your medication diary, your hand-typed health
figures, and the diagnostics log. Activity brought in from Apple Health
becomes a memory on your iPhone but is **not** copied to iCloud, in line with
Apple's rules for apps that read Health.

"Forget everything" with sync on removes your memories from your iCloud and
from every iPhone that syncs with it; the app says so before you confirm.
Turning sync off stops the copying and leaves what is already in your iCloud
where it is — it is your storage.

### 2. Sign in with Apple — only if you choose it

Signing in is optional and skippable, and nothing in the app is locked behind
it. If you do sign in, Apple returns an identifier that is specific to this app
and, on the first sign-in only, your name.

Both are written to the database on your iPhone and go nowhere else, because
there is no server to send them to.

**Your email address is never requested.** The app asks Apple only for your
name.

### 3. Speech recognition

When you speak to Elderly Care, it asks iOS to transcribe on the device
wherever your iPhone supports it. On a device or a language where on-device
recognition is not available, iOS sends that audio to Apple's speech
recognition service. An app cannot force an on-device model to exist, so we
tell you rather than imply otherwise.

### 4. Turning a position into a place name — a photo's, or a scan's in the Lab

If you import photos, the coordinates stored in them are sent to Apple's
geocoding service to turn them into a place name — "Lakeview", not a latitude.
The photographs themselves are never sent anywhere.

When you keep something you scanned in the Lab as a memory, Elderly Care takes
one location fix, if you allow location, and sends it to the same Apple
service to name the place. The name is kept with the memory; the position
itself is not kept at all. With no connection or no fix, the memory is kept
without a place. Nothing tracks you between scans, and the picture of the
object is never sent anywhere.

What is *in* a photograph is worked out on your iPhone. Apple's Vision
framework names what it recognises, and on iOS 27 one photograph from each day
is shown to Apple's on-device model, which writes a sentence about it and
picks the themes and the feeling the app files it under — from the app's own
short lists, never a name. That happens entirely on the phone; it is the same
model that answers Smith, and it needs no network.

Separately, choosing to open a place in Maps hands that location to Apple Maps.

### 5. Fetching Smith's voice — once, when he first speaks

Smith speaks in a voice that is not one of Apple's: a small, open speech model
(Kokoro) that runs on your iPhone itself. The first time the app starts it
fetches about 89 MB of model files from Hugging Face, a public site that hosts
open machine-learning models, so that he can speak. It happens once; the files
stay on your iPhone through every update.

What travels is the download itself, in one direction. Nothing about you goes
with it: not your name, not a memory, not a word you have spoken. Once the
files are on your iPhone the voice works with no connection at all, and
everything it says is produced on the device.

If you would rather he used one of Apple's voices, Settings → *Smith* → *How he
sounds* offers them, and the model files can be removed from the same screen.
The download is model weights only; it is not a way of collecting anything
about you.

### 6. Asking a bigger model — only if you switch it on

Smith answers your questions with a model that runs on your iPhone. Settings
can offer a switch, **Let Smith ask a bigger model**, which uses a larger
Apple model that runs on Apple's servers, through what Apple calls Private
Cloud Compute. The switch is off unless you turn it on, and it only appears
on iPhones and builds that can use it.

While it is on, each question you ask Smith, and the short excerpts of your
memories he needs to answer it — the same few he would read on the phone — are
sent to Apple's servers to be answered. Apple states that Private Cloud
Compute uses this data only to answer the request, does not store it, and
that it is not accessible to Apple. We do not run those servers and we do not
see the requests. Nothing else goes: not your picture, not your health
records, not your diagnostics log, not your name.

Every answer says where it came from — press and hold it — so you can see
which model spoke. There is a daily allowance set by Apple, which an iCloud+
plan can raise; past it, or without a connection, Smith answers on your
iPhone as before. Turn the switch off and nothing is sent again.

### 7. Your circle — only if you invite someone

You can let the people who look after you — family, a friend, a carer — see
some of what is on your iPhone. Nobody sees anything until you invite them and
choose what they see, in Settings → *Your circle* or by asking Smith.

**Nobody can join yet.** The people you invite would see what you share in a
caregiver app, and Elderly Care does not have one of its own yet. Its
invitations ask them to use Shaterian Caregiver, our caregiver app for another
app of ours, and that app cannot open an Elderly Care circle. Until Elderly
Care has a caregiver app, an invitation puts what you choose to share in your
iCloud, as described below, but nobody can join and see it. *Stop sharing*
removes it. This page will change when that does.

**Where it goes.** Elderly Care keeps one space in **your own iCloud private
database** and shares it, through iCloud, with the people you invite and with
nobody else. There is no server of ours in between: School Fab Lab has no
credentials for it and no way to read it. What is in it is kept in iCloud's
encrypted fields. If you have turned on Advanced Data Protection for iCloud, it
is end-to-end encrypted and not even Apple can read it; otherwise Apple holds
the keys, as it does for most iCloud data.

**What they could see — only what you switch on:**

- **Routines and reminders**: their words, days and times, any note on them,
  whether one is a medicine, and when you press Taken or Done on one, with the
  time it was due.
- **Memories you choose**: only the ones you switch on — one by one, all at
  once, or, if you turn it on, each new memory as you add it. For each: its
  text, what kind of memory it is, when it happened and when it was filed, and
  the people, places, emotions and themes tagged on it.
- **Always, once somebody is in your circle**: the name the app greets you by,
  your time zone, what you have chosen to share, whether their suggestions wait
  for your yes, and whether your notifications are on.

**Never shared with your circle:** anything from Apple Health, a question you
ask Smith, your body notes, your mood, your medication diary, the full text of
a document, your picture, the pictures of things you scan, and every memory
you have not switched on.

**Inviting.** An invitation is a link you send however you like — in
Messages, by email, anywhere. It lets in the first person who opens it, and
after that it works for nobody else. A link nobody has opened can be
withdrawn. On iOS 17, Apple's own sharing sheet is used instead, and you name
the people you invite.

**Taking it back.** *Stop sharing*, in Settings → *Your circle*, deletes the
shared space from your iCloud, so nobody can read any of it; nothing on your
iPhone changes. Forget everything, and deleting your account and data, stop
sharing too. Deleting Elderly Care from your iPhone does **not** stop sharing:
stop first, or delete Elderly Care's data from your iCloud, as described under
*Removing your data*.

### 8. A message from us — and it only ever comes *to* you

Now and then we may have something to say to everybody using Elderly Care: a
get-together, or news about the app. When we do, we write it once, and your
iPhone reads it the next time you open the app. It appears as a card on your
Today screen.

**Nothing about you goes out to fetch it.** The message is the same for
everybody, so there is nothing to tell us apart by: no name, no account, no
identifier of any kind, and nothing you have recorded. We have no way of
knowing who read it, who came, or even how many of you there are.

Settings offers a switch, **Remind me before one**, which is **off unless you
turn it on**. With it on, and if what we have told you about has a date,
Elderly Care sets a reminder on your own iPhone for the evening before — the
same way it sets the daily nudge and your routines. **Nothing is sent to your
iPhone from outside**: no push, no message from us, and nothing that needs an
iCloud account. Your iPhone reads the message when you open the app, and
leaves the reminder for itself. Turn the switch off whenever you like, and it
is withdrawn.

It is only ever about Elderly Care itself. Never advertising, never anybody
else's message, and never more than a few a year.

Putting a message away with **No thanks** is remembered on your iPhone only.

## What Elderly Care never does

- No analytics or telemetry of any kind
- No crash-reporting service
- No advertising, no advertising identifier, no tracking across apps or sites
- Nothing sold, rented or shared with data brokers
- Nothing used to train any model, ours or anyone's
- No third-party company receives your data

The only third-party components in the app are local ones: an on-device
database, a file-path helper, the system web view, and the open speech library
that gives Smith his voice. None of them sends anything about you anywhere;
the voice library's one connection is the download of its own model files,
described in section 5.

## Permissions, and what each is for

<div class="tablewrap" markdown="1">

| Permission | What it is used for |
|---|---|
| Microphone and Speech Recognition | Speaking a memory, and asking questions |
| Photos | Optional import of days and places from your library |
| Calendar and Reminders | Your calendar is **read, never copied**: when you ask Smith what is on today or when your next appointment is, the events for those days are read on your iPhone to answer, and not stored. Smith asks for this permission the first time you ask; without it he answers from your routines and reminders and can open the Calendar app for you. Reminders are treated the same way: if you connect them, what is due is read to answer and for the daily reminder, and nothing is copied in. Adding an appointment you ask Smith for goes through Apple's own Add Event screen, which needs no permission and shows the app nothing |
| Contacts | Names, so people in your life are recognised — and, when you ask Smith to call or message someone, that person's number. Read at the moment you ask; never kept |
| Apple Health | **Read only.** Steps, resting heart rate, HRV, sleep, walking speed and steadiness. Elderly Care never writes to Health |
| Camera | Scanning a room so the app can recognise where you are later, and taking your picture, if you choose the camera for it. In the Lab: lifting out an object you scan, to keep as a memory |
| Location (while using the app) | Answering "where am I" and guiding you home. In the Lab: noting where you kept something you scanned, named by Apple's map service (section 4) |
| Notifications | One daily reminder, if you want it — written on your iPhone from your calendar for that day and your own earlier years, never sent anywhere; any reminder you ask Smith to set; routines — repeating reminders such as pills at 8 and 8, with a Taken button that records the dose; and, if you have a circle, a note when somebody in it suggests something, joins or leaves |

</div>

Every source can be switched off in **Your things**, and what has already come
in can be removed at the same time — you are asked about those separately,
because stopping and erasing are different wishes.

What the app cannot do is hand a permission back. iOS has no way for an app to
revoke its own access, by design. The system-level switch stays on until you
turn it off in **iOS Settings → Privacy & Security**.

## Things Smith does on your iPhone

You can ask Smith to call someone, FaceTime them, start a message, put an
appointment in your calendar, or remind you of something. Each works the same
way, and none of it happens on its own:

- **He proposes first.** "Shall I call Reza on the mobile?" Nothing is dialled,
  sent or saved until you say yes — a tap, or the word, in a conversation.
- **Then Apple asks again.** A call goes to the iPhone's own dialler, which
  confirms before it rings. A message opens in Messages with the words typed
  in and Send left to you. An appointment opens Apple's own Add Event screen
  with the details filled in, for you to check and add. A reminder is a
  notification on this iPhone at the time you named.
- **Nothing is kept.** To find a number he searches your Contacts for the
  name you said, once, when you ask; the numbers he is shown are used for that
  proposal and then forgotten. He does not read your calendar to add to it.
  What you asked for is filed as a memory in your own words, like anything
  else you tell him — the number is not.

"My daughter" and the like: the only relationship Smith knows is the trusted
contact you set in Settings. If none is set, he says he does not know who
that is rather than guessing.

## The Lab

The Lab, in Settings, holds Health — your body notes, your medicines and the
summary for your doctor, all described on this page — and one thing we are
trying out: **Scan an object**. Point the camera at something, and Elderly
Care lifts it out of the picture, says what it is, and — if you choose — keeps
it as a memory with its picture.

- **The camera** runs only while you are scanning. Apple's Vision framework
  separates the object from what is around it and recognises what it is, on
  your iPhone. On iOS 27 with Apple Intelligence switched on, Apple's
  on-device model names and describes it — on the phone, with no network.
- **What it keeps.** Only what you choose to keep: a memory, like any other,
  with the object's name, what was said about it, and when and where — and
  its picture beside it in the app's own storage. With sync on, the memory's
  words go to your iCloud like any memory's; the picture never does.
- **What leaves your iPhone.** Only the place name for a scan you keep, from
  Apple's map service (section 4).
- **Removing it.** Like any memory: on its own, or with Forget everything. Its
  picture goes with it.

## Paying for Elderly Care

On the App Store, Elderly Care will be free for two weeks, then a small
monthly subscription — the price is shown in your own currency before you
subscribe. Test versions, through Apple's TestFlight, have no subscription:
nothing is offered and nothing is paid.

The payment is taken by Apple, through your Apple Account, on Apple's own
screens. We never see your card, your bank, your billing address or your
Apple Account details, and there is no server of ours for them to be sent
to.

What the app learns from Apple is only this: whether your subscription is
active, whether you are in the free two weeks, when the current period ends,
and whether it will renew. That comes from Apple's own signed record on your
iPhone (StoreKit); the app keeps the last answer on the phone so it can open
without a connection, and sends it nowhere. Apple keeps its own record of
the purchase under [Apple's privacy policy](https://www.apple.com/legal/privacy/).

Cancelling is done in Settings › your name › Subscriptions on your iPhone,
not in the app, so nothing of ours stands between you and stopping a
payment. If the subscription ends, the app opens on a page that offers to
subscribe again — and that same page opens *Your data*, so your memories can
be read, shared and removed without paying. A lapsed card, a refund or a
cancelled trial never locks you away from what is yours.

## Your picture, and your face

**Elderly Care does not capture your face.** Shaterian, the app of ours that
Elderly Care began as, can measure a face with the iPhone's TrueDepth camera
to build a likeness of you. That part of the code is still inside Elderly
Care, but nothing in the app leads to it: the camera is never used for it,
and no face data is collected.

**Your picture.** In Settings → *Looks* you can add a picture of yourself,
taken with the camera or chosen from your photos. Smith's screen shows it. It
is kept in the app's own storage on your iPhone, is not part of the iCloud
copy of memories, and is never sent anywhere. Three colours are read from it
on the device — skin tone, hair colour and eye colour — as six hex digits
each. Nothing about your shape, age, health or identity is derived or kept,
and the colours are cleared when you change or remove the picture.

## Health information

Elderly Care reads from Apple Health and **never writes to it**. Figures are
read when they are shown, and are not copied into the app's own storage.

Health information is never used for advertising, never shared with anyone you
have not chosen, and never used to make decisions about you. If you share your
routines with your circle (section 7), the people you invite would see your
medication routines and when you press Taken; nothing from Apple Health is
ever shared with them.

If you import activity from Apple Health it becomes a memory on your iPhone.
It is **not** copied to your iCloud, even with sync on — nothing that came
from Apple Health, and none of your body notes, medication diary or hand-typed
figures, ever is.

**Elderly Care is not a medical device.** It does not diagnose, treat or give
medical advice, and it is not a substitute for your doctor, nurse or
specialist. Questions that call for a medical decision are redirected to your
care team before they reach any model.

## The diagnostics log

Settings → **Help** → **Diagnosis and logs** keeps a record of what the app
did, so a fault can be described instead of guessed at. It is the one thing in
the app built to be sent to us, and two rules hold it:

1. **Events only.** Counts, codes, outcomes, source names. Never a memory,
   never a transcript, never a person's name, a place, a filename, or the
   contents of a file.
2. **Nothing goes silently.** The whole log is on screen before the share sheet
   opens. What you can read is exactly what you would send, and you choose
   where it goes. It has no destination of its own.

It holds the last 500 lines and you can clear it from that screen.

## Removing your data

Each of these can be removed on its own, inside the app: your memories, your
body notes, your mood notes, your picture, health figures you typed yourself,
and your medication history. Something you scanned in the Lab is a memory, and
goes the same way, its picture with it. There is also a twice-confirmed
**Forget everything**.

Three things you should know, because they are true and it would be easy to
leave them out:

- **Forget everything reaches your iCloud only while sync is on.** With sync
  on, forgetting everything removes your memories from your iCloud and from
  every iPhone that syncs with it, and the app says so before you confirm.
  With sync off, it clears this iPhone only, and anything already in your
  iCloud from earlier stays there; to remove that, go to **iOS Settings → your
  name → iCloud → Manage Account Storage** and delete Elderly Care's data, or
  use *Delete your account and data*. We cannot do it for you: it is your
  private database and we have no access to it.
- **Your circle has its own copy.** *Stop sharing*, in Settings → Your circle,
  deletes the space you share from your iCloud, and Forget everything does the
  same. Deleting the app does not: if you delete it without stopping, delete
  Elderly Care's data from your iCloud as above, which removes the shared space
  too.
- **Scanned place maps cannot yet be removed inside the app.** They are held by
  a component the app cannot currently delete from. They stay on your iPhone
  and go nowhere; deleting the app removes them.

Signing out of Apple is available in your profile. Because signing in creates
nothing on any server of ours, signing out and deleting the app removes
everything that sign-in produced.

Deleting the app removes the database, your picture and the pictures of
objects you scanned from your iPhone. It does not remove an iCloud copy, which
is removed as described above.

## Children

Elderly Care is made for adults and is not directed at children.

## Changes to this policy

If what the app does changes, this page changes in the same release, and the
date at the top changes with it.

This is Elderly Care's first policy, published on 22 October 2026. Elderly
Care began on 20 October 2026 as a copy of Shaterian, another app of ours, and
still shares its code, so this page began as Shaterian's policy. It differs
where the apps do: Elderly Care does not capture your face, its circle has no
caregiver app yet, and Health is in the Lab.

## Contact

Questions, corrections, or a request about your data:

**nader@schoolfablab.com**

School Fab Lab
