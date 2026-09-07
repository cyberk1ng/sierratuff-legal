# Privacy Policy for SierraTuff

**Last updated: 7 September 2026**

## The short version

**SierraTuff collects nothing, sends nothing, and has no server.**

Everything a learner types or earns stays on their phone. There is no account server, no
analytics, no advertising, and no third party receives anything — because there is nothing
to receive. This is not a promise about how carefully we handle data in transit; the app
has no way to transmit data at all.

## How you can check that for yourself

You do not have to take our word for it. The Android release build **does not request the
`INTERNET` permission**. That permission appears only in the debug and profile builds used
by developers on their own machines, never in the app published on Google Play. An app
without the `INTERNET` permission cannot open a network connection — Android refuses it at
the operating-system level, whatever the code asks for.

Anyone can verify this by inspecting the published app's manifest.

## What is stored on your phone

When a learner creates a profile, the app saves the following **on the device only**:

- **Full name** — as typed, shown on the profile and the sign-in screen
- **Username** — used to tell profiles apart when a phone is shared
- **A four-digit PIN** — held in Android's encrypted secure storage, not in the app's
  database
- **Avatar choice** — the face a learner builds for themselves
- **Exam plan and class/year** — NPSE, BECE or WASSCE, and the year selected
- **Progress** — which lessons are finished, stars earned, best scores, and the daily
  streak

That is the complete list. It is written to a database file inside the app's private
storage area, which Android makes unreadable to other apps.

## What the app does not collect

The app does **not** ask for, store, or transmit:

- Email addresses or phone numbers — there is no server to verify, mail, or reset anything
- Location of any kind
- Contacts, photos, camera, or microphone
- Advertising identifiers or any other device identifier
- Analytics, usage statistics, crash reports, or diagnostics

The app contains no advertising SDK, no analytics SDK, and no crash-reporting SDK.

## Children's privacy

SierraTuff is made for schoolchildren in Sierra Leone preparing for national examinations,
and many of its users are under 13.

Because the app transmits nothing, **no personal information is collected from a child by
us or by anyone else through this app.** There is no sign-in with a social account, no
messaging, no user-generated content shared between devices, no in-app purchases, and no
advertising. A child's name, username and progress exist only on the phone in their hand.

Parents and guardians who want that information removed can do so themselves, at any time,
without contacting us — see *Deleting your data* below.

## Backup and transfer are switched off deliberately

The app sets `allowBackup="false"` and supplies explicit data-extraction rules, which means:

- Learner data is **excluded from Android's automatic cloud backup**, so it is never copied
  to a Google account
- It is **excluded from device-to-device transfer**, so setting up a new phone does not
  carry it across

This is a deliberate choice. It has a cost worth stating plainly: **a learner who changes
or resets their phone starts again from the beginning.** We accept that cost so that a
child's work never leaves the device it was done on.

## Deleting your data

There are two ways, both entirely in your hands:

- **Delete the profile** inside the app. Its progress is deleted with it.
- **Uninstall the app.** Android removes the app's private storage, including the database
  and the stored PIN. Nothing survives, and nothing is held anywhere else.

There is no data of yours on any server for us to delete, because there is no server.

## Third parties

No data is shared with third parties. The app makes no network requests, so no third party
— including Google — receives anything from it about a learner.

The app is distributed through Google Play, and Google collects its own data about
downloads and installations under
[Google's Privacy Policy](https://policies.google.com/privacy). That is a matter between
you and Google, and is outside anything this app does or sees.

## Changes to this policy

If this policy changes, the updated version will be published at this address and the date
at the top will change. If a future version of the app ever collects or transmits anything
— which would be a significant change of design — this policy will be updated **before**
that version is released, and the change will be described here rather than buried.

## Contact

Questions about this policy, or about a learner's data, can be sent to:

**acepython001@gmail.com**

SierraTuff
