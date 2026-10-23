# Credits

Every source used in WordWise or its word packs, with its licence. All of them allow redistribution, because the packs are public. These credits ship inside each pack (the `credits` table, with full notices where a licence asks for them) and appear on the in-app Credits screen.

The word packs as a whole are released under **CC BY-SA 4.0**, as Wiktionary's licence requires.

## Word data (base pack)

| Name | Used for | URL | Licence |
| --- | --- | --- | --- |
| Wiktionary (English), via kaikki.org / wiktextract | Definitions, examples, IPA, word forms, synonyms, opposites, word family | https://kaikki.org/dictionary/English/ | CC BY-SA 4.0 (Wiktionary content) |
| wordfreq by Robyn Speer | Choosing the most common words | https://github.com/rspeer/wordfreq | Data CC BY-SA 4.0, code Apache 2.0. Includes SUBTLEX (Brysbaert et al., freely available, credit required), OpenSubtitles 2018, Wikipedia, Google Books Ngrams, Leeds Internet Corpus, ParaCrawl |
| Open English WordNet 2025 | Similar Spells (synonyms) and opposites | https://github.com/globalwordnet/english-wordnet | CC BY 4.0 |
| Tatoeba | Extra example sentences (sentence numbers kept in the pack) | https://tatoeba.org | CC BY 2.0 FR |
| VarCon 2020.12.07 by Kevin Atkinson and Benjamin Titze | British spellings | http://wordlist.aspell.net/varcon/ | Permissive; copyright and permission notice shipped in the pack |
| CEFR-J Wordlist 1.5, compiled by Yukio Tono, Tokyo University of Foreign Studies | CEFR levels A1–B2 | https://github.com/openlanguageprofiles/olp-en-cefrj | Free for research and commercial use with citation |
| Octanove Vocabulary Profile C1/C2 1.0, Octanove Labs | CEFR levels C1–C2 | https://github.com/openlanguageprofiles/olp-en-cefrj | CC BY-SA 4.0 |
| Britfone 3.0.1 by Jose Llarena | British IPA where Wiktionary has none (265 words) | https://github.com/JoseLlarena/Britfone | MIT; notice shipped in the pack |

## Voices and speech

| Name | Used for | URL | Licence |
| --- | --- | --- | --- |
| Piper voice "Cori" (en_GB), by Bryce Beattie | Spoken headwords (high quality, made on the Mac) and example sentences (medium quality, on the Pi) | https://huggingface.co/rhasspy/piper-voices/tree/main/en/en_GB/cori · https://brycebeattie.com/files/tts/ | Public domain (trained from scratch on public-domain LibriVox recordings) |

## Software (used to build the packs, not shipped in them)

| Name | Used for | URL | Licence |
| --- | --- | --- | --- |
| Piper (piper1-gpl) | Text-to-speech engine; its bundled eSpeak NG also gives British IPA for 776 words with no other source (marked "RP (eSpeak)" in the pack) | https://github.com/OHF-Voice/piper1-gpl | GPL-3.0-or-later. The audio and IPA it produces are not covered |
| opus-tools (opusenc) | Encoding headword audio as Ogg Opus | https://opus-codec.org | BSD-2-Clause |

## Fonts and artwork (app)

| Name | Used for | URL | Licence |
| --- | --- | --- | --- |
| Cinzel, by Natanael Gama (The Cinzel Project Authors) | Titles | https://github.com/google/fonts/tree/main/ofl/cinzel | SIL Open Font License 1.1 (`app/web/fonts/Cinzel-OFL.txt`) |
| IM Fell English, by Igino Marini | Headwords | https://github.com/google/fonts/tree/main/ofl/imfellenglish | SIL Open Font License 1.1 (`app/web/fonts/IMFellEnglish-OFL.txt`) |
| Atkinson Hyperlegible Next, Braille Institute (The Atkinson Hyperlegible Next Project Authors) | Text | https://github.com/google/fonts/tree/main/ofl/atkinsonhyperlegiblenext | SIL Open Font License 1.1 (`app/web/fonts/AtkinsonHyperlegibleNext-OFL.txt`) |
| Fredoka, The Fredoka Project Authors | Minion theme: titles and headwords | https://github.com/google/fonts/tree/main/ofl/fredoka | SIL Open Font License 1.1 (`app/web/fonts/Fredoka-OFL.txt`) |
| Grenze and Grenze Gotisch, Omnibus-Type (The Grenze Project Authors) | Dragon theme: headwords and titles | https://github.com/google/fonts/tree/main/ofl/grenze · https://github.com/google/fonts/tree/main/ofl/grenzegotisch | SIL Open Font License 1.1 (`app/web/fonts/Grenze-OFL.txt`, `GrenzeGotisch-OFL.txt`) |
| WordWise owl (Wizard), inventor owl with goggles (Minion), dragon (Dragon), icons and themes | Mascots and interface | `app/web/owl.svg`, `owl-goggles.svg`, `dragon.svg`, `app/web/src/` | Original artwork made for WordWise. The Minion and Dragon themes use no characters, likenesses, logos or fonts from any film or game |

IPA symbols fall back to DejaVu Sans, which Raspberry Pi OS already has.
