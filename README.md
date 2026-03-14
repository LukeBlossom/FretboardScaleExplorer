# 🎸 Fretboard Scale Explorer

An interactive scale visualizer for guitar and bass — no installation, no account, no internet required. Open the HTML file in any browser and start playing.

[Scale Explorer screenshot](screenshot.png)

## Features

- **Guitar & Bass support** — 6-string guitar, 4-string bass, and 5-string bass modes
- **14 scales** — Major, Natural Minor, Harmonic Minor, Melodic Minor, Pentatonic Major/Minor, Blues, Dorian, Phrygian, Lydian, Mixolydian, Locrian, Whole Tone, Diminished
- **Multiple tunings** — Standard, Drop D, Open G, Open D, Half Step Down, Full Step Down for guitar; Standard, Drop D, Half Step Down for bass
- **Adjustable fret range** — 12, 15, 17, 22, or 24 frets
- **Three display modes** — Note Names, Intervals, Scale Degrees
- **Click to hear** — every note plays via Web Audio API (no plugin needed)
- **Song Key Lookup** — 270+ songs with auto key/scale detection
- **YouTube Backing Track generator** — builds a search query from your current key, scale, and tempo
- **Works completely offline** — single self-contained HTML file

## Quick Start

1. [Download `index.html`](index.html)
2. Open it in Chrome, Firefox, Safari, or Edge
3. Select your instrument, root note, and scale
4. Click any dot on the fretboard to hear the note

No build step. No dependencies. No server.

## Usage

### Picking a Scale
Use the **Root Note** and **Scale** dropdowns to set your key. The fretboard updates instantly — red dots show the root, blue dots show all other scale tones.

### Switching to Bass
Select **Bass (4-string)** or **Bass (5-string)** from the Instrument dropdown. The string layout, tuning options, and audio playback all adjust automatically.

### Display Modes
- **Note Names** — shows the letter name of each note (C, D#, G, etc.)
- **Intervals** — shows the interval relative to the root (R, b3, 5, b7, etc.)
- **Scale Degrees** — shows Roman numeral degrees (I, II, III, etc.)

### Song Key Lookup
Type any song title and press Search. If it's in the database, the fretboard jumps to that song's key and scale automatically. Over 270 songs across rock, blues, metal, jazz, pop, country, and funk.

### YouTube Backing Tracks
Set a BPM with the slider, choose filter tags (Blues, Rock, Funk, etc.), and click **Search on YouTube** to find a matching backing track for your current scale.

## Scales Reference

|         Scale        |     Pattern     | Common Genres           |
|----------------------|-----------------|-------------------------|
| Major                | W W H W W W H   | Pop, Country, Classical |
| Natural Minor        | W H W W H W W   | Rock, Metal, Classical  |
| Pentatonic Minor     | m3 W W m3 W     | Rock, Blues, Metal      |
| Pentatonic Major     | W W m3 W m3     | Country, Blues, Pop     |
| Blues                | m3 W H H m3 W   | Blues, Rock, R&B        |
| Dorian               | W H W W W H W   | Jazz, Funk, Celtic      |
| Phrygian             | H W W W H W W   | Metal, Flamenco         |
| Mixolydian           | W W H W W H W   | Rock, Blues, Country    |
| Lydian               | W W W H W W H   | Film, Prog Rock, Jazz   |
| Harmonic Minor       | W H W W H A H   | Classical, Metal        |
| Whole Tone           | W W W W W W     | Jazz, Impressionist     |
| Diminished           | W H W H W H W H | Jazz, Metal             |

*W = whole step · H = half step · m3 = minor third · A = augmented second*

## Guitar Tunings

| Name           | Strings (low → high) |
|----------------|----------------------|
| Standard       | E A D G B e          |
| Drop D         | D A D G B e          |
| Open G         | D G D G B d          |
| Open D         | D A D F# A d         |
| Half Step Down | Eb Ab Db Gb Bb eb    |
| Full Step Down | D G C F A d          |

## Bass Tunings

| Name               | Strings (low → high) |
|--------------------|----------------------|
| Standard 4-string  | E A D G              |
| Drop D             | D A D G              |
| Half Step Down     | Eb Ab Db Gb          |
| Standard 5-string  | B E A D G            |
| Drop A             | A E A D G            |

## Teacher's Resource Pack

A printable PDF companion is available for music educators, including:

- Scale quick reference chart (all 14 scales)
- Fretboard diagrams for guitar and bass in the key of A
- Blank fretboard worksheets for students
- Week-by-week practice routines (beginner → intermediate)

[Download the Teacher's Pack PDF](Fretboard%20Scale%20Explorer%20-%20Teachers%20Pack.pdf)

## Browser Support

Works in any modern browser with Web Audio API support:

|       Browser        |          Support             |
|----------------------|------------------------------|
| Chrome / Edge        | ✅ Full                      |
| Firefox              | ✅ Full                      |
| Safari               | ✅ Full                      |
| Mobile (iOS/Android) | ✅ Works (tap to hear notes) |

## Contributing

Contributions welcome — especially:

- Additional songs for the key lookup database
- New alternate tunings
- Translations / localization

Please open an issue or pull request.

## License

MIT — free to use, share, and modify.

---

*If this tool helped you, consider [buying me a coffee ☕](https://ko-fi.com/lukeblossom)*
