# User Guide

Everything you need to get going with DarkStage, organized by what you're actually trying to do.

## The Basic Workflow

DarkStage is built around one simple flow:

1. **Build your Library.** Add the songs you play—title, key, BPM, notes, whatever's useful—once each. See [Library](library.md).
2. **Create a Show.** Add the gig's details, then build its setlist by pulling songs in from your Library (or creating new ones on the spot) and adding any talk/intro blocks you need. See [Shows](shows.md).
3. **Perform.** Tap Play and you're in a full-screen, high-contrast view built to be readable and navigable on a dark stage, one-handed. See [Performance](performance.md).
4. **Adjust to taste.** Themes, brightness behavior, what shows on screen, and more—see [Settings](settings.md).

If you're a **DarkStage Pro** user, venue lookup is covered in [Shows](shows.md), and Google Drive backup is covered in [Settings](settings.md).

## The Four Screens

- **[Shows](shows.md)**: creating and managing gigs, building setlists, venue lookup and directions, calendar import
- **[Library](library.md)**: your master song list, notes and markdown, the chord/key picker toolbar
- **[Performance](performance.md)**: what you see when running an actual show, including gestures, the screen layout, set breaks, exiting
- **[Settings](settings.md)**: every configuration option, what it does, and what it defaults to

## Tips

Practical advice from actually using DarkStage at real gigs...Not required reading, but worth a look.

### Library

- Entering one or two songs on your phone or tablet keyboard is fine, but if you're building out a big library, it's worth connecting a physical keyboard (Bluetooth or USB) and typing your way through it. You'll get through a long song-entry session much faster and much more easily with a physical keyboard.
- If you already have chord charts or lyrics hosted somewhere online, the Resource Link field can point straight at them instead of retyping everything into Notes.
- It's worth building your Library out ahead of time, even for songs you're not gigging yet. If your band has the song available, it's probably a good idea to enter it into your library as well. Every show you create afterward just pulls from what's already there, so the fuller your Library is, the faster setlists come together later.
- Try to keep song titles and artists accurate to the actual released track, rather than shorthand or however you personally think of them. It makes communicating about songs with bandmates—or anyone else—much easier down the line.

### Shows

- If you play a lot of gigs with similar setlists, Duplicate is usually much faster than starting from scratch. Duplicating a show from one in Past Shows is a great way to work up a new setlist very quickly.
- If you already track your gigs in a calendar, Calendar Import can save you re-entering the date, venue, and times by hand.
- Build your setlist ahead of time rather than the day of, so you actually have a chance to look it over—and fix anything that's off—before you're standing on stage with it.

### Performance

- If you're going to be in Performance mode for a while, consider hooking up a USB power supply of some sort—a charger, a power bank, whatever you've got—to make sure your device has enough battery to last the whole show.
- Consider turning off Wi-Fi and mobile data during a performance. No network connection will save battery, and it means no notifications or connectivity hiccups pulling your attention back to your screen unnecessarily.
- If a venue tends to be dim, or your device seems to dim on its own during a show, check Full Bright by Default or Pin Brightness on Performance Launch in Settings before you hit the stage.
- On the other hand, if the stage is genuinely very dim, don't be afraid to turn your own brightness down rather than up. A screen that's too bright relative to a dark room costs you your night vision every time you glance away from it, which can be worse than a screen that's a little harder to read.

## Caveats and Things to Watch For

A few things worth knowing that don't fit neatly on any one page above:

- **DarkStage needs a real touchscreen.** Every gesture—swipe, pinch, the brightness drag—depends on actual touch input. It won't work properly on a non-touch Chromebook (keyboard and trackpad only).
- **Editing the same show from two devices at the same time isn't supported.** If you use DarkStage on more than one device, avoid editing the same show on both at once—whichever device's automatic backup lands on Drive last simply overwrites the other, with no merging. In practice this is easy to avoid (don't edit the same show from your phone and tablet in the same few minutes), but worth knowing rather than discovering the hard way.
- **Drive Backup Status may show no date after reinstalling DarkStage.** If you reinstall the app—a new device, or after uninstalling and reinstalling—Android's own built-in Auto Backup (separate from DarkStage's own Drive backup; see [Settings](settings.md)) automatically restores your library and shows in the background. Because that restore happens outside of DarkStage's own Drive-tracked state, Drive Backup Status won't show a date until you reconnect Google Drive. When you do reconnect, you'll be prompted to restore from your Drive backup—go ahead and do that, even though your data may already look current thanks to Android's Auto Backup, since it's what gets DarkStage's own backup tracking back in sync with what's actually on Drive.

## Deleting Your Data from Google Drive

If you've used DarkStage's Google Drive backup (Pro only) and want to remove what's stored there, the way to do it from within the app is:

1. Delete everything from your **Shows** screen and your **Library**.
2. Trigger a sync to Drive, by either waiting for Automatic Backup to run on its own, or tapping **Back Up Now** in Settings.

If you use Back Up Now, DarkStage will show a warning first, since an empty device backing up over a real existing backup normally looks like a mistake. That's expected here; choose **Back Up Anyway** to confirm.

This overwrites your Drive backup with an empty one. The backup file itself still exists in your private Drive app-data folder (DarkStage doesn't have a way to remove the file outright, only to update what's in it), but it no longer contains any of your data.
