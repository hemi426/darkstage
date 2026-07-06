# DarkStage Privacy Policy

*Last updated: July 6, 2026*

DarkStage is a setlist and performance management app for musicians. This
policy explains what information DarkStage accesses, how it's used, and what
choices you have.

DarkStage does not have its own servers or user accounts. There is no
DarkStage-operated backend collecting or storing your data. Everything below
either stays entirely on your device, or is sent directly to a Google service
under your own Google account, never passing through anything operated by
the developer.

---

## What DarkStage stores

Your songs, shows, setlists, and notes are stored locally on your device in
a private app database. This data is never transmitted anywhere unless you
use one of the optional features below.

## Google Calendar (optional, read-only)

If you use the "Import from Calendar" feature, DarkStage reads calendar
events from your device's calendar (title, date/time, and location) so you
can pre-fill a show's details. This requires Android's calendar read
permission.

- DarkStage never writes to, modifies, or deletes anything in your calendar.
- Calendar data is only read at the moment you choose to import an event; it
  is not monitored, synced, or accessed in the background.
- Nothing about your calendar is transmitted anywhere -- it's read on-device
  and copied into a new Show record you control, exactly like manually
  typing the same details in yourself.

## Google Drive backup (optional, paid feature)

If you unlock DarkStage Pro and choose to connect Google Drive, DarkStage
can back up your song/show/setlist data as a single file to a private,
app-specific storage area in your own Google Drive account (Google calls
this an "appDataFolder"). This area is not visible in your normal Google
Drive file browser and cannot be accessed by any other app, including by the
developer of DarkStage.

- This uses Google's own sign-in and authorization system. DarkStage never
  sees or stores your Google password.
- Only the minimum access needed for this feature is requested (Google calls
  this scope `drive.appdata`) -- DarkStage cannot see, browse, or modify any
  other file in your Google Drive.
- Backing up is optional and off by default until you explicitly connect
  Google Drive. You can disconnect at any time by revoking DarkStage's
  access in your Google Account's security settings
  (myaccount.google.com/permissions).
- Revoking access does not automatically delete a prior backup file --
  Google's account-level data controls govern that, independent of
  DarkStage.

## Directions (all users, free)

Tapping a venue's address in a show's details opens your device's own maps
app (Google Maps or whichever app you have set as default) via Android's
standard `geo:` link mechanism. DarkStage does not look anything up itself
here, does not make any network request, and does not know which maps app
you use or what happens after it opens -- it simply hands the address to
Android, the same as tapping any address link anywhere else on your device.
This is separate from the Places venue search feature below, and is
available on both the free and paid tiers.

## Google Places (optional, paid feature)

If you unlock DarkStage Pro and use the venue search button when adding a
show, the venue name you type is sent to Google's Places API to look up a
matching address. This only happens when you explicitly tap the search
button -- never automatically or as you type. The results (venue name,
address, coordinates) are saved into your show's details on your device.

## Google Play Billing

Purchasing the one-time DarkStage Pro unlock is handled entirely by Google
Play's billing system. DarkStage never sees your payment details -- only
whether your purchase was successful, so the app can unlock Pro features.

## Android Auto Backup

Android's built-in Auto Backup system may back up DarkStage's app data to
your Google Account as a normal part of Android's device backup/restore
process (for example, when setting up a new phone). This is a standard
Android OS feature available to any app, governed by Google's own backup
policies, not something DarkStage controls directly beyond declaring that
it's enabled.

## What DarkStage does not do

- No advertising, ever, and no third-party ad networks
- No analytics or tracking SDKs
- No account creation within the app itself
- No data is sold or shared with third parties for advertising or marketing
  purposes
- No data collection from anyone knowingly under the age of 13; DarkStage is
  not directed at children

## Your choices

- Calendar import, Google Drive backup, and Places venue lookup are all
  optional -- the app is fully usable without any of them.
- You can revoke DarkStage's Google Drive access at any time from your
  Google Account settings.
- Uninstalling DarkStage removes all locally stored data from your device
  (subject to Android's own Auto Backup behavior, above).

## Changes to this policy

If this policy changes, the "Last updated" date at the top will change
accordingly. Continued use of DarkStage after an update means you accept
the revised policy.

## Contact

Questions about this policy or DarkStage's data practices can be sent to:
**hemi.puresimplicity.net@gmail.com**.

---

*This document is maintained alongside the DarkStage project.*
