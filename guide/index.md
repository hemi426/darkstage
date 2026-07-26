# User Guide

Everything you need to get going with DarkStage, organized by what you're actually trying to do.

## The Basic Workflow

DarkStage is built around one simple flow:

1. **Build your Library.** Add the songs you play — title, key, BPM, notes, whatever's useful — once each. See [Library](library.md).
2. **Create a Show.** Add the gig's details, then build its setlist by pulling songs in from your Library (or creating new ones on the spot) and adding any talk/intro blocks you need. See [Shows](shows.md).
3. **Perform.** Tap Play and you're in a full-screen, high-contrast view built to be readable and navigable on a dark stage, one-handed. See [Performance](performance.md).
4. **Adjust to taste.** Themes, brightness behavior, what shows on screen, and more — see [Settings](settings.md).

If you're a **DarkStage Pro** user, venue lookup is covered in [Shows](shows.md), and Google Drive backup is covered in [Settings](settings.md).

## The Four Sections

- **[Shows](shows.md)** — creating and managing gigs, building setlists, venue lookup and directions, calendar import
- **[Library](library.md)** — your master song list, notes and markdown, the chord/key picker toolbar
- **[Performance](performance.md)** — running an actual show: gestures, the screen layout, set breaks, exiting
- **[Settings](settings.md)** — every toggle, what it does, and what it defaults to

## Caveats and Things to Watch For

A few things worth knowing that don't fit neatly on any one page above:

- **DarkStage needs a real touchscreen.** Every gesture — swipe, pinch, the brightness drag — depends on actual touch input. It won't work properly on a non-touch Chromebook (keyboard and trackpad only).
- **Editing the same show from two devices at the same time isn't supported.** If you use DarkStage on more than one device, avoid editing the same show on both at once — whichever device's automatic backup lands on Drive last simply overwrites the other, with no merging. In practice this is easy to avoid (don't edit the same show from your phone and tablet in the same few minutes), but worth knowing rather than discovering the hard way.
- **Drive Backup Status may show no date after reinstalling DarkStage.** If you reinstall the app — a new device, or after uninstalling and reinstalling — Android's own built-in Auto Backup (separate from DarkStage's own Drive backup; see [Settings](settings.md)) automatically restores your library and shows in the background. Because that restore happens outside of DarkStage's own Drive-tracked state, Drive Backup Status won't show a date until you reconnect Google Drive. When you do reconnect, you'll be prompted to restore from your Drive backup — go ahead and do that, even though your data may already look current thanks to Android's Auto Backup, since it's what gets DarkStage's own backup tracking back in sync with what's actually on Drive.

## Deleting Your Data from Google Drive

If you've used DarkStage's Google Drive backup (Pro only) and want to remove what's stored there, the way to do it from within the app is:

1. Delete everything from your **Shows** screen and your **Library**.
2. Trigger a sync to Drive, either by waiting for Automatic Backup to run on its own or tapping **Back Up Now** in Settings.

If you use Back Up Now, DarkStage will show a warning first, since an empty device backing up over a real existing backup normally looks like a mistake. That's expected here — choose **Back Up Anyway** to confirm.

This overwrites your Drive backup with an empty one. The backup file itself still exists in your private Drive app-data folder—DarkStage doesn't have a way to remove the file outright, only to update what's in it—but it no longer contains any of your data.
