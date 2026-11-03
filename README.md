もちろんです。`README.md` 用に、見やすく整理した形でまとめるとこんな感じです。

```md
# SUPER ESELATOR Ver. 4.5.5

## Update Details / 更新内容

### English
- Added a shortcut key reference table
- Increased the number of FX types
  - Added tape wobble and lo-fi degradation effects
- Adjusted preset sound volumes
- Added 7th and 9th chord options to the chord buttons
- Added a strum function to the chord buttons

### 日本語
- キーのショートカット表を追加
- FX種類の増加
  - テープ揺れ・ローファイ劣化表現の追加
- プリセット音色の音量調整
- コードボタンに7th/9thを追加
- コードボタンにストラム機能を追加

---

## SUPER ESELATOR Overview

SUPER ESELATOR is a retro-style Web Audio performance tool for touch screens, keyboards, gamepads, and mobile devices.

It includes:

- Live sound performance
- Loop recording and overdubbing
- Chord pads
- Deck-based sound switching
- Real-time FX
- WAV recording
- Project save/load

---

## 1. Deck System

The app has four independent decks:

- DECK A
- DECK B
- DECK C
- DECK D

Each deck can hold its own preset sound, mute state, and playback behavior.

### Use cases
- Switch between different instruments quickly
- Keep multiple sound roles available at once
- Play one sound set while preparing another
- Save different setups into a project

### Deck controls
- Select a deck
- Mute / unmute a deck
- Change the preset assigned to each deck
- Use different sounds on different decks during performance

---

## 2. Preset Sound Engine

Each deck can be assigned a preset sound from a large preset library.

### Preset categories
- Bass
- Lead
- Chord / Pad
- Piano
- SFX / FX
- Drum Kits
- Ambient / Nature

### Preset types
The engine includes many sound behaviors, such as:

- Synth waves
- Chord stacks
- Piano models
- Drum kit voices
- Ambient noise textures
- Effect-style SFX
- Arpeggio or laser-type sounds

### Preset volume
Each preset can have its own volume multiplier, so you can balance loudness per sound independently.

---

## 3. Touch Pad Performance

The large screen area acts as the main performance pad.

### Touch pad behavior
- Horizontal position controls pitch or scale note
- Vertical position controls filter cutoff
- Different touch positions trigger different tones
- Works like a performance instrument

### Visual feedback
- Grid lines show note zones
- Note names are displayed across the pad
- Particles appear when notes are triggered
- A looping time bar shows playback position
- The display changes with octave shift and scale selection

### Touch pad role
This is the main live-play area for:

- Melody playing
- Drum triggering
- Performance gestures
- Loop recording input

---

## 4. Scale and Key System

You can choose both:

- Key
- Scale / Mode

### Supported scale types
- Chromatic
- Major
- Natural Minor
- Pentatonic Major
- Pentatonic Minor
- Blues
- Dorian
- Phrygian
- Lydian
- Mixolydian
- Locrian
- Harmonic Minor
- Melodic Minor
- Japanese scales
- Arabic / Double Harmonic
- Whole Tone
- Diminished
- Chiptune Triad Arp

### Why this is useful
- Quickly change musical mood
- Match chords and melody to a key
- Create different musical flavors from the same pad layout

---

## 5. Octave Shift

The pad system supports octave shifting.

### Features
- Shift pitch up or down
- Affects touch pad notes and chord pads
- Useful for switching between bass ranges and lead ranges

### Behavior
- Octave display updates on screen
- Touch pad theme changes visually depending on octave
- The pad stays usable while transposed

---

## 6. Chord Pads

There are five chord pads under the touch pad.

### Chord pad functions
- Trigger harmony chords instantly
- Each pad has a scale-aware chord name
- Pads follow the current key and scale
- Can generate triads, 7th chords, or 9th chords

### Chord extension modes
- TRIAD
- 7th
- 9th

### What chord pads are for
- Building harmonic progressions
- Playing backing chords live
- Creating chord loops
- Quickly changing the harmony of a performance

---

## 7. Strum Mode

Chord pads can be played in strum style.

### Strum mode features
- Notes in the chord are triggered one by one
- Low note to high note order
- Adjustable gap time between notes

### Controls
- Turn strum mode on or off
- Adjust strum interval
- Adjust chord length

### Why this matters
It creates a more human, guitar-like or keyboard-like chord feel instead of all notes sounding exactly at once.

---

## 8. Loop Recording

The app supports live loop recording.

### Recording states
- STANDBY
- REC FREE
- WAIT HEAD
- PLAYING
- OVERDUB

### Loop recording features
- Record your performance into a loop
- Play back the recorded material continuously
- Add overdubs while the loop is running
- Use touch pad notes and chord pads in the loop
- Keep timing data for each note

### Timing behavior
The app stores:

- Note time offsets
- Duration
- Deck assignment
- Preset ID
- Chord grouping
- Drum type if used

This makes loop playback accurate and flexible.

---

## 9. Overdub Support

You can layer new notes on top of an existing loop.

### Overdub lets you
- Add extra melody lines
- Add chord changes later
- Fill in percussion or accents
- Build arrangements step by step

---

## 10. Undo

The `UNDO` function restores the previous loop state.

### Undo behavior
- Reverts the latest recording change
- Works after recording, overdubbing, and note edits
- Can restore the previous musical state without clearing everything

### Use cases
- Remove a bad take
- Roll back an accidental overdub
- Recover from a mistaken edit

---

## 11. Clear Active Deck

The `CLEAR` function removes notes only for the currently selected deck.

### Clear behavior
- Deletes all notes assigned to the active deck
- Leaves other decks intact
- Useful for performance cleanup
- Safer than clearing the whole project

---

## 12. Select / Double Sequence

The `SEL` function duplicates the current loop material.

### What it does
- Duplicates the recorded sequence
- Doubles the loop length
- Keeps the musical content aligned
- Useful for extending song structure

### Performance use
This is ideal for:

- Quickly making a longer arrangement
- Repeating a section
- Building a full song form from a short loop

---

## 13. Start / Stop Playback

The `START` button controls loop playback.

### Behavior
- Start playback from the loop
- Stop playback cleanly
- Resume if needed
- Keeps loop timing and notes in sync

---

## 14. FX Engine

SUPER ESELATOR includes a master FX engine.

### FX types
- Hall Reverb
- Echo Delay
- Lowpass Filter
- Delay + Filter
- Tape Wobble
- Tape Wobble + Filter
- Lo-Fi Cassette

### FX controls
- Global FX on/off
- FX type selection
- Two main XY-linked parameters
- Extra per-FX controls

### FX behavior
The engine affects live audio output in real time and can change the tone dramatically.

---

## 15. XY FX Pad

There is a dedicated XY control pad for effects.

### XY pad features
- X-axis controls one parameter
- Y-axis controls another parameter
- Visual pointer shows the current position
- Real-time parameter movement

### Why it is useful
- Fast hands-on effect control
- Good for live performance
- Easier than using only sliders

---

## 16. FX Extra Parameters

Each FX type has its own detailed parameters.

### Examples
- Reverb: pre-delay, decay, damping, size, mix
- Delay: time, feedback, tone, mix
- Filter: cutoff, resonance, drive, mix
- Tape effects: wow rate, wow depth, delay time, feedback, cutoff
- Lo-fi: wobble, dust, drive, cutoff, noise

### Purpose
These parameters let you shape the sound more precisely, beyond the main XY controls.

---

## 17. Deck Mute Controls

Each deck can be muted independently.

### Mute behavior
- Silences a deck’s output
- Does not delete notes
- Can be toggled live during playback

### Use cases
- Drop instruments out
- Isolate a specific part
- Create arrangement changes in real time

---

## 18. WAV Recording

The app can record the final audio output as a WAV file.

### WAV recording features
- Records the full master output
- Captures live performance and FX
- Converts the recorded stream into WAV
- Allows audio export at the end of a session

### Notes
- On some browsers, especially in-app browsers, download behavior may be limited
- Safari usually works more reliably on iPhone

---

## 19. Project Save / Load

You can save and reload your entire setup as a JSON project.

### Saved project includes
- Current key
- Current scale
- Active deck
- Deck presets
- Deck mute states
- FX state and parameters
- Preset volume multipliers
- Chord settings
- Loop data
- Recorded notes

### Why this is useful
- Restore a performance later
- Keep your setup portable
- Share sessions or continue editing after reloading

---

## 20. Keyboard Support

The app supports keyboard performance and control.

### Common keyboard functions
- `1` - `4`: select decks
- `Shift` + `1` - `4`: mute decks
- `5` - `9`: chord pads
- `A S D F G H J K`: touch pad notes
- `E`: FX on/off
- `R`: record / arm / overdub
- `U`: undo
- `C`: clear active deck
- `Space`: play / stop
- `Z`: previous sound
- `X`: next sound
- `Q`: octave down
- `W`: octave up

---

## 21. Gamepad Support

Gamepad control is also supported.

### Common gamepad functions
- `R`: record / arm / overdub
- `START` + `L`: play / stop
- `SELECT` + `L` / `R`: deck switching
- `SELECT` + `Y`: FX toggle
- `SELECT` + `X`: sequence double
- `SELECT` + `A`: undo
- `SELECT` + `B`: clear active deck
- `L` + directions: chord pads
- `A` / `B` / `X` / `Y`: touch pad performance
- `START` + directions: sound and octave controls

### Why gamepad support matters
- Better for hands-on live performance
- Easier on mobile setups with controllers
- Good for arcade-style playing

---

## 22. Mobile and Browser Compatibility

The app is designed with mobile and touch-first use in mind.

### Mobile-friendly features
- Touchpad gestures
- Large on-screen buttons
- No pinch zoom
- iPhone support
- Gamepad support on compatible browsers

### Browser note
Some in-app browsers, especially Instagram, may limit file saving.  
Safari is usually the best choice for recording and export.

---

## 23. Visual Feedback and UI Design

The interface is styled like a retro game console.

### Visual elements
- Glowing LED indicators
- Scanline-style screen effect
- Deck status highlights
- Active button feedback
- Live waveform-style or grid-style display elements

### Why this matters
It makes the app feel like a playable instrument, not just a music utility.

---

## 24. Performance-Oriented Design

The whole system is meant for live use.

### Designed for
- Quick switching
- Fast recording
- Improvisation
- Real-time editing
- Stage-like performance flow
```
