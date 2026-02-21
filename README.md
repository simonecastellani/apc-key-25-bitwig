APC Key 25 Control Script for Bitwig
====================================

Introduction
------------

This is an attempt at getting
[APC Key 25](http://www.akaipro.com/product/apc-key-25) working with [Bitwig](http://www.bitwig.com).
The goal is to get it doing everything the official script does, plus more. Turn this affordable
piece of gear into a powerhouse with Bitwig and this script!

### Difference With Official Ableton Script:

* Shift + Sustain toggles velocity sensitivity on and off.
* Shift + clip button deletes a clip when in rec/arm mode.
* Shift + "Stop All Clips" returns to arrangement.
* Shift + Play/Pause does tap tempo.
* Shift + Record toggles Step Sequencer mode (see below).
* In mute mode, the light indicates that the track _is_ muted.

### Step Sequencer Mode

Press **Shift + Record** to toggle between Clip Launcher and Step Sequencer mode.

In Step Sequencer mode the 8×5 pad grid becomes a step editor for the currently selected clip:

| Control | Function |
|---------|----------|
| Grid pads | Toggle a step on/off (amber = active, off = inactive) |
| Playback position | Current step blinks green (active) or amber (empty) |
| Shift + Left / Right | Scroll to the previous / next page of 8 steps |
| Shift + Up / Down | Scroll the note range up / down by one semitone |
| Shift + Record | Exit Step Sequencer and return to Clip Launcher mode |

Each row of the grid represents a different note pitch (bottom row = lowest, top row = highest).
Each column represents one step within the 8-step page. Scrolling left/right lets you edit clips
longer than 8 steps; scrolling up/down shifts which pitches are displayed.

The 8 knobs continue to control track Volume / Pan / Send / Device parameters while in Step
Sequencer mode.

### Nice to Haves:

* Ability to remap Shift + [Sustain, Play/Pause, Rec] since there are more features we could add than just the three and different people have different workflows
* Marquee/image mode (like Bitwig logo or APC on startup)
* Ability to use clip launchers as a keyboard (with selectable modes)
* Per-step velocity control via knobs in Step Sequencer mode

Installation
------------

Copy the APCKey25.control.js script into your local controller scripts directory:

* `~/Documents/Bitwig\ Studio/Controller Scripts/` in macos
* `~/Bitwig Studio/Controller Scripts/` in linux
* `%userprofile%\Documents\Bitwig Studio\Controller Scripts\` in windows

License
-------

This is licensed under the very permissive BSD license. See LICENSE for more details.
Copyright 2014-2019 Osaka Red LLC, Thomas J. Webb and Johan Berntsson
