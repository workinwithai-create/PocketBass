# PocketBass

Four-bar live pocket bass desk for bedroom producers and AI-music finishers.

Suno and loop DAWs leave the bass on the root. Session players write a pocket groove under the chords so the loop finally moves and the track finishes.

Live FluidR3 electric bass (finger) samples pinned to commit 044fab8e1456bfafc5776e86dfd6bb8697149aef. Supporting kick/snare/hat from percussion bank.

## Distinct from yesterday and the line

| Tool | Job |
|------|-----|
| WalkBass | Walking upright under roots |
| CHORDLOCK | Scale-locked arps + basslines |
| HookLine | Singable motif |
| **PocketBass** | Four-bar electric bass pocket (root / octave / syncopated / walk-lite) under your 4 chords |

## Features

- BPM 60–180, key selector, 4-chord entry (Am F C G)
- Styles: Root, Octave, Syncopated, Walk-lite
- Live changes apply on next step
- Lookahead scheduler on AudioContext clock
- WAV + MIDI export (48 kHz 24-bit, exact bar length, first downbeat at sample 0, tail folded)
- localStorage persistence
- Preload with progress; names missing instruments
- Hardware MIDI support planned; on-screen is fallback

## Pricing recommendation

One-time $29 via Lemon Squeezy (Merchant of Record). Finite tool, no subscription needed. Best place: Lemon Squeezy for automatic tax, or Gumroad.

README says free for this MVP; license gate for paid version.

## Acceptance

(1) Export 92 BPM 8 bars 48kHz: 1001739 samples, transient at 0.
(2) Loop in DAW: no clicks, no drift.
(3) Background tab: stops cleanly.
(4) Live changes within one bar.
(5) Missing samples named.
(6) Pads sustain (bass notes hold).
(7) No @main, no Math.random in export, names match.

## License

MIT. Free for this ship.
