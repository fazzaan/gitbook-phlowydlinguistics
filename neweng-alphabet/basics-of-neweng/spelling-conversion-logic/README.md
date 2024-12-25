# Spelling conversion logic

## Primary Goals but written concisely

1. Simplify spellings.
   1. One letter has one sound, but one sound can be made by several letters. No digraphs.
   2. Diacritics are allowed for preserving spelling patterns; respelling is preferred.
   3. Phonetic consonant respelling (where reasonable).
   4. No double letters (unless necessary).
   5. Phonetic vowel respelling (if diacritics are too messy).
   6. No vowels split apart.
2. Increase visual consistency & distinction.
   1. Preserve etymological spelling patterns.
   2. Retain visual distinctions between homophones.
   3. Increase visual distinction between homographs & homonyms.
   4. Increase the ability for non-natives to decode English based on apparent patterns and logic.

## Primary Goals

### 1. Simplify spellings.

1. One letter has one sound (phoneme). E.g.:

* t is always /t/
* þ is always /θ/

2. One sound can be made by many letters. E.g.:

* /ʃ/ can be made by ʃ, š, ťiV, ʞ̌, ч̌, ç̌
* /k/ can be made by c, k, q, ʞ
* /ʤ/ can be made by j, ǧ, ď

3. Modifications are allowed using diacritics.
4. Multiple letters are allowed to produce the same phonemic values.
5. No double letters, unless necessary.
6. No vowel combinations split apart (like ⟨a⟩ in ⟨face⟩).
7. Phonetic respelling for standard pronunciation mutations.

* Voiced ⟨s⟩ suffix after voiced codas, compare ducks /dʌks/ & dogs /dɔɡz/.
* g as j /ʤ/ in ⟨ge/gi/gy⟩

8. Phonetic respelling for unreasonable or unresolvable vowel variations.

* ⟨ou⟩ is remarkably common and also remarkably nonsensical.

### 2. Retain & maximize visual & aural distinctions.

1. Preserve etymological spelling patterns.
2. Retain visual distinctions between homophones.
3. Not all homophones are homophones in every accent. Erasing distinctions is deleterious and culturally insensitive (see Gaal Dornick in _Foundation_). Grammatic homophones tend to exist in most accents, whereas semantic homophones tend to have arisen as a result of [phonological mergers](https://en.wikipedia.org/wiki/Category:Splits_and_mergers_in_English_phonology).
   1. Semantic: bow vs bough → baw vs báŭȝ
   2. Grammatic: passed vs past → pâsèd (or pâsd) vs pâst
   3. Rhotic: raw vs roar → råw vs ro̊r
   4. Mergers/splitters: too many examples to put here, see the dedicated section/page.
4. Increase visual distinction between homographs and homonyms.
5. Bow — /baw/ vs /bəw/ → baw vs bōw
6. Row — /ɹaw/ vs /ɹəw/ → raw vs rōw
7.

## Respelling of Vowels

Some vocabulary first

* A standard letter creates one sound at a time.
* A digraph is two letters that create one sound together, or create a diphthong that doesn't match the letters' base values.
* We define a monograph as one letter that creates two sounds at the same time — usually a díφþoŋ (diphthong).
* A díφþoŋ is two vowel sounds pronounced edge-to-edge.
* A mónoφþoŋ is one vowel sound pronounced independently.

### Monophthong Vowels

#### Monograph alterations

W modifies vowels in standard Eŋglish. This is messy and seemingly unnecessary in modern Eŋglish so we are removing it.

W is included in the _Monographs_ section because the W itself still produces the /w/ phoneme, but it modifies the proceeding vowel, which is a monograph.

* wa- and wha- as /wɔ/ (water, what) change to
* wo- and who- — because the letter ⟨a⟩ never makes the /ɔ/-vowels unless preceded by a ⟨w⟩.

#### Digraphs to monophthongs

There are not many digraph monophthong vowels in English. Most digraphs

* ⟨ae⟩ as /ɪː\~eː/ changes to æ
* ⟨oe⟩ as /ɪj\~yː/ changes to œ — protects pronunciation.

### Diphthong Vowels

#### Monograph compressions — Magic E

Monographs are (in this publication, at least) singular letters which carry a diphthong value — two vowel sounds together.

Magic E diphthongs are considered as monographs because, when the final E is removed to make way for a suffix, the Magic E vowel maintains its diphthong value.

* a as /ɛj/ in "face". The /ɛj/ is retained with the suffix -ing, _facing_.

#### Monographs alterations — no Magic E

Some vowels have diphthong values despite there being no Magic E.

* i in "kind" → ī = kīnd
* o in "go" → ō = gō

#### Digraph modifications

This can involve:

* changing the letters
* marking the letters
* changing and marking the letters.

**Examples**

* ⟨ow⟩ as /aw/ changes to:
  * ⟨aw⟩ at the end of a word
  * ⟨aw⟩ if a vowel follows it (maybe?)
  * ⟨aŭ⟩ if a consonant follows it.
* ⟨ow⟩ as /əw/ changes to:
  * /ōw/ at the end of a word
  * ⟨ōw⟩ if a vowel follows it (maybe?)
  * ⟨ōŭ⟩ if a consonant follows it. (maybe?) (shown → ʃōŭn)

### R-tail Vowels - rules retained

The Vowel+R rules are retained in NewEng.

#### Vowel+R

* -ar →
* -er → -r -- if the E is unpronounced or is unstressed /ɜː/\~/ə/
* -ir →
* -or →
* -oor → ꝏr
* -our → ȣr
* -ur →

Info/Tip: See section/page about -or and -er suffix reduction.

If a vowel is followed by R or RR but its phone is its base value, mark it with the inverted chevron, as such: ǒ.\
(This diacritic choice is under review, because it looks too similar to the breve diacritic: ŏ / ǒ.

* ar : carry → cǎry
* er : ferry → fěry
* ir : mirror → mǐror
* or : borrow → bǒrōw
* bury

If the vowel's pronunciation is of another value, mark it accordingly:

* our : courage → cȣ̂rȧj

#### Vowel+R+E

* -are → ăr for /ɛː(ɹ)/ in "mare", "square", "spare", "bare"
* -ere → ĕr for /ɛː(ɹ)/ in "there", "where"
* -ire → īr for /ɑjə(ɹ)/ in "fire," "dire", "mire", "wire"
* -ore → or for /ɔ:(ɹ)/ in "more", "core", "lore"
* -ure → ŭr or ūr

### W-tail Vowels - rules removed

The _Vowel+W_ rules from Current English are NOT retained in NewEng.

Vowels retain their base value, plus the /w/ closing position.

| New                      | Old                         | New fix for Old                                      |
| ------------------------ | --------------------------- | ---------------------------------------------------- |
| ⟨aw⟩ is /aw/             | ⟨aw⟩ was /ɔː/               | ⟨aw⟩ as /ɔː/ is ⟨åw⟩                                |
| ⟨ēw⟩ is /ɪjuw/          | ⟨ew⟩ was /ɪjuw/             | ⟨ew⟩ is invalid                                      |
| ⟨ow⟩ is /ɔw/ like "cold" | ⟨ow⟩ was /ɔw/ & /əw/ & /aw/ | <p>⟨ow⟩ as /aw/ is ⟨aw⟩<br>⟨ow⟩ as /əw/ is ⟨ōw⟩</p> |
| ⟨ōw⟩ is /əw/ like "tow" | ⟨ow⟩ was /ɔw/ & /əw/ & /aw/ | <p>⟨ow⟩ as /aw/ is ⟨aw⟩<br>⟨ow⟩ as /ow/ is ⟨ow⟩</p>  |
