# Groove Studio kit, November 2026

The 30 drum sounds that Groove Studio loads. Each file is one hit, made from a free sample pack.

Every sound has five recordings, so a repeated hit does not sound the same every time: `snare.mp3` is the first, `snare_2.mp3` to `snare_5.mp3` are the others (150 files).

| Sounds | Source | Licence |
|---|---|---|
| Snare (`snare*.mp3`, `buzz.mp3`) | [Virtuosity Drums](https://github.com/sfzinstruments/virtuosity_drums) by Versilian Studios and Karoryfer Samples | CC0 1.0 |
| Toms and kick (`tom-*.mp3`, `kick*.mp3`) | [Naked Drums](https://github.com/sfzinstruments/WilkinsonAudio.NakedDrums) by Wilkinson Audio, SFZ version by kinwie | CC BY 4.0 |
| Cymbals, hi-hat and cowbell (`hh-*.mp3`, `crash*.mp3`, `china*.mp3`, `splash.mp3`, `ride*.mp3`, `cowbell.mp3`) | [Salamander Drumkit](https://github.com/studiorack/salamander-drumkit) by Alexander Holm (Rytmenpinne) | CC BY-SA 3.0 |

## What was changed

- Five recordings per sound were picked from the pack. Toms, kick, cymbals, hi-hat and cowbell: five recordings of the same hit. Snare: the pack has one recording per loudness level, so the five are neighbouring levels. For every sound, files 2 to 5 were set to the loudness of the first file.
- Snare, toms and kick: the pack stores one hit as several microphone recordings. These were added together into one stereo file. The snare uses the snare, kick, overhead and mid microphones. The toms and the kick use all positions of the pack's default preset, with the tuning that preset gives toms 3 and 4.
- All files: the volume was changed, silence was trimmed from the start and the end, and the result was saved as mp3. The crashes and the open hi-hat are cut at 8 seconds with a fade. The names in the first table also cover the other four files of each sound (`snare_2.mp3`, `crash2_3.mp3`).

## Licences

- The files made from Salamander Drumkit are adapted from it and have the same licence as the original: [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
- The files made from Naked Drums: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
- The files made from Virtuosity Drums: [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/).

The `LICENSE` file in the root of this repository does not apply to this folder.
