# WordWise word packs

Signed word packs for **WordWise**, a British English dictionary and thesaurus for Cambridge O Level English Language students. The dictionary runs offline on a Raspberry Pi and downloads new packs from this repo's [Releases](https://github.com/fidztech/wordwise-packs/releases) when a student taps **Check for updates**.

This repo holds pack data and credits only. There's no code here.

## What's in a release

| File | What it is |
| --- | --- |
| `wordwise-base-<version>.sqlite.xz` | The words: meanings, examples, pronunciations, levels, Similar Spells and opposites (SQLite, xz-compressed) |
| `wordwise-audio-<version>.sqlite.xz` | Spoken headwords (Ogg Opus clips in SQLite, xz-compressed) |
| `manifest.json` | Each pack's version, size, SHA-256 and Ed25519 signature, plus a signature over the manifest itself |
| `CREDITS.md` | Every source and its licence |

Versions are dates (`YYYY.MM.DD`, with `.1`, `.2` for a second build on the same day).

## Checking a pack

The dictionary checks every download before using it: the compressed file's SHA-256, then the unpacked pack's size, SHA-256 and Ed25519 signature, then that it opens as the right pack. It only switches to a pack that passes, keeps the previous version for rollback, and never installs an older version.

The Ed25519 public key (base64) is:

```
nd7wOiTJx43GszvkjoN42sXtPFv4lU5hPpYespW6taI=
```

## Licence

The word packs are released under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/), as Wiktionary's licence requires. They're built only from openly licensed sources, all of which allow redistribution. [CREDITS.md](CREDITS.md) lists each source with its licence; the same credits are inside every pack.
