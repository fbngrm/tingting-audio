# tingting-audio

Audio CDN for the [tingting](https://github.com/fbngrm/tingting) Mandarin learning app, served via GitHub Pages.

**Base URL:** `https://fbngrm.github.io/tingting-audio`

## Structure

```
words/hsk1/   300 files  ~7.6 MB   HSK 1 vocabulary
words/hsk2/   200 files  ~5.0 MB   HSK 2 vocabulary
words/hsk3/   218 files  ~5.6 MB   HSK 3 vocabulary
tones/          7 files  ~0.1 MB   Tone-teaching syllables
```

Files are named by word number within each HSK level (e.g. `words/hsk1/1.mp3`).
Metadata is in [`manifest.json`](manifest.json).

`words/aishell/hsk7/` holds 43 AISHELL-3 recordings (Apache License 2.0) for
HSK 7-9 words without another recording; see
[`words/aishell/NOTICE.md`](words/aishell/NOTICE.md).
