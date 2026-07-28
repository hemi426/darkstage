# Settings

A rundown of everything you can adjust, grouped the same way they're grouped in the app itself.

## Performance

- **Full Bright by Default**: forces your screen to maximum brightness the instant you start a performance. This is a deliberate choice, not a fix for anything. Turn this on if you always want max brightness on stage regardless of what your device's own brightness happened to be set to beforehand. Note that brightness control is still available via the right-side drag.
- **Max Font Size on Launch**: starts your notes text at its largest pinch-zoom size the moment you enter a performance, rather than wherever it was left. Off by default; pairs naturally with Auto-fit Notes below, which will still shrink things back down on a per-song basis if the combined notes are too long to fit at full size.
- **Auto-fit Notes**: shrinks your notes text just enough to keep your Song Notes and Show Notes from overflowing the screen, without you having to manually pinch it down every time. It won't ever grow text past whatever size you've pinched to. This setting will not affect the size you've got things set at, so if the next song or talk card's notes fit at the larger size, they will not be shrunk to fit. On by default.

### Advanced

Tucked away since most people will never need to touch these settings. They exist to work around a handful of devices' unusual behavior ; most users shouldn't need to adjust these.

- **Keep Screen On**: prevents your screen from timing out and sleeping mid-performance. On by default; there's no real reason to want this off.
- **Pin Brightness on Performance Launch**: locks your screen brightness to whatever it already is the moment you enter a performance, rather than letting your device's automatic brightness adjust it further on its own. Off by default, since most devices never need this, but if you notice your screen mysteriously dimming during a show—some devices are more prone to this than others—turning this on should fix it. Has no effect if Full Bright by Default (above) is also on, since that already takes over brightness entirely.

## Display

- **Show Next Song Preview**: toggles the small "up next" preview at the bottom of the Performance screen
- **Show BPM** / **Show Key** / **Show Time Signature**: toggle each of these independently in the Performance header
- **Song Title Line Limit**: how many lines a song title can wrap to before it's cut off with "…". Defaults to Unlimited; choose 1, 2, or 3 lines if you'd rather it never take up more space than that.
- **'Next' Line Limit**: the same idea, for the "up next" preview. Defaults to Unlimited; choose 1 or 2 lines.
- **Theme**: Dark (the default), Amber on Black, Green on Black, Dark on Light, Dark on Warm White, and two fully customizable slots (Custom 1 and Custom 2) where you pick your own text and background colors.

## Notes Toolbar

- **Chord Picker**: the on-screen chord/key insertion toolbar described in [Library](library.md). On by default.
- **Enhanced Chord Picker**: adds space, dash, and slash keys to the Chord Picker for typing chord sequences and slash chords. On by default.
- **Markdown Formatting**: the Bold/Italic/Monospace toolbar on the Notes field. On by default.

## DarkStage Pro

A one-time unlock. See [About](../about.md) for why it's priced this way, not a subscription. Tapping the unlock button shows the real price from the Play Store and walks you through a normal Google Play purchase. Once purchased, this section just shows a quiet "Thank you" instead.

Pro unlocks:
- Unlimited real performance sessions (the free tier gives you 3 before a one-time prompt to upgrade)
- Venue lookup via Google Places, from the Shows screen
- Google Drive backup and restore (below)

## Backup (Pro only)

- **Connect Google Drive**: a one-time sign-in; DarkStage only ever writes to a private, app-specific folder in your Drive that isn't visible in your normal Drive UI and isn't accessible to any other app.
- **Drive Backup Status**: shows when your most recent backup actually landed on Drive.
- **Automatic Backup**: on by default. Backs your library and shows up to Drive automatically shortly after you make changes, with no action needed from you.
- **Back Up Now**: a manual backup, any time you want one.
- **Restore from Backup**: pulls your most recent Drive backup down and replaces what's on this device. You'll always see the backup's date before confirming, so you're never restoring something unexpected. This is meant for picking up where you left off on a different device, not as your main safety net; if your device itself is ever lost, wiped, or replaced, Android's own built-in Auto Backup—separate from DarkStage's Drive backup above, and requiring no setup at all—already restores your data automatically the next time you install the app.
