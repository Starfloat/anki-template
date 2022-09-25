# anki-template

My Anki Template for Japanese card creation with Yomichan

# Fields to Yomichan Mapping

| Anki                 | Yomichan                                          | Description                                                             |
|----------------------|---------------------------------------------------|-------------------------------------------------------------------------|
| SentSentence         | {cloze-prefix}`<b>{cloze-body}</b>`{cloze-suffix} | Main Sentence                                                           |
| SentFuriganaSentence | {sentence-furigana}                               | Sentence in furigana form                                               |
| EnglishSentence      | manual                                            |                                                                         |
| VocabAudio           | {audio}                                           | Sent by Yomichan.                                                       |
| VocabKanji           | {expression}                                      | Word in Kanji Form.                                                     |
| VocabKanjiFurigana   | {furigana-plain}                                  | Term expressed as kanji with furigana displayed next to it in brackets. |
| VocabKana            | {reading}                                         | Word in Kana Form.                                                      |
| VocabKanaPitch       | {pitch-accents}                                   | Word in Kana Form with Pitch Lines.                                     |
| PitchGraph           | {pitch-accent-graphs}                             | Pitch Accent Image.                                                     |
| VocabPitchPos        | {pitch-accent-positions}                          | Pitch Accent Number.                                                    |
| SentAudio            | auto                                              | Single voiced line sent by mpvacious.                                   |
| VocabDef             | {glossary}                                        | Main field for definitions.                                             |
| VocabDefJP           | manual                                            | Sub field for definitions.                                              |
| Hint                 | manual                                            | Hint to be shown in the front.                                          |
| Image                | manual/auto                                       | Image received from animecards script or sharex.                        |
| SentenceContext      | auto/manual                                       | Script received from animecards script or pasted manually from source.  |
| SentenceContextAudio | Audio received from animecards script.            |                                                                         |
| Conjugation          | {conjugation}                                     | Conjugation path from the raw inflected term to the source term.        |