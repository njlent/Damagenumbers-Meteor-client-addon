# Damage Numbers Meteor Addon

Meteor Client addon for Minecraft 26.1.2. Adds a Combat module named `damage-numbers` that shows floating damage text when nearby living entities take damage.

## Features

- Floating damage numbers above damaged entities.
- Optional damage numbers when the local player takes damage.
- Optional Meteor chat/text feedback for each damage number.
- Native Meteor settings for display duration and colors.
- Particle-limit behavior follows the Minecraft particle setting.

## Settings

- `show-player-damage`: show damage numbers for damage taken by you.
- `text-feedback`: print damage values to Meteor chat feedback.
- `display-ticks`: how long each number stays visible.
- `custom-colors`: use configured damage colors instead of white.
- `small-color`, `medium-color`, `large-color`, `critical-color`: color ramp matching the original mod behavior.

## Build

```powershell
.\gradlew.bat build
```

The addon jar is written to `build/libs`.
