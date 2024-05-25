# Ancient/Biblical Hebrew braille

## Introduction

Hebrew is a Semitic language like Arabic or Aramaic. In Semitic languages, the consonants carry the core meaning, often referred to as the skeleton. The vowels fill this skeleton to create verb forms, nouns, and other word forms.

In Hebrew, consonants are so important that vowels can often be predicted by a good knowledge of the language in the context of sentences. In Modern Hebrew, almost no vowels are written.

Hebrew has 22 consonants. The Hebrew script for sighted people has very different letter forms from Western languages and is written from right to left. Hebrew Braille is written from left to right, like latin based languages, using mostly the same Braille characters used for Western scripts. Converting Hebrew texts to Braille is simple: the Hebrew letter ג (gimel) is represented as ⠛ (dots 1245), ד (dalet) as ⠙ (dots 145).

In addition to the 22 consonant characters, Hebrew script also has vowel signs. This additional system developed when Hebrew was no longer the common spoken language of the Jews, and there was a need to record the correct pronunciation. In sighted script, these signs appear as dots or dashes above, below, or next to the consonants. In Hebrew Braille, the vowels are placed between the consonants. Texts where vowel signs are written are called vocalized. In Hebrew, this is referred to as ניקוד (nikud).

Modern Hebrew is also called Ivrit, which simply means Hebrew. Modern Hebrew generally does not require vowel signs; Biblical Hebrew does. There are also accent marks (cantillation): these are important for correct stress and recitation but less often for understanding the text.

## Consonants

### Letter 1: Alef

- א ⠁ dot 1

### Letter 2: Bet

The Bet has two braille forms:

- בּ (Bet) ⠃ dot 12, usually constructed of two unicode characters, \u5D1 and \U5BC
- ב (Pronounced like Vet) ⠧ dot 1236, only \u5D1

The sighted Hebrew uses the same character for these two forms. The two values (בּ or ב) are distinguished in sighted script by a dot in the middle of the letter called dagesh. In Braille, we use separate characters.

### Letter 3: Gimel

- ג ⠛ dot 1245

### Letter 4: Dalet

- ד ⠙ dot 145

### Letter 5: He

- ה ⠓ dot 125

### Letter 6: Vav

- ו ⠺ dot 2456

Note that the Vav can be accompanied by a Dagesh, in which case it becomes a vowel (Shuruq).

### Letter 7: Zayin

- ז ⠵ dot 1356

### Letter 8: Het

- ח ⠳ dot 1346

### Letter 9: Tet

- ט ⠾ dot 2345

### Letter 10: Yod

- י ⠚ dot 245

### Letter 11: Kaf

The Kaf has two braille forms:

- כּ (Kaf) ⠅ dot 13, usually constructed of two unicode characters, \u5DB and \U5BC
- כ (Khaf) ⠡ dot 16, only \u5DB

Sighted Hebrew uses the same character for these two consonants, distinguished by a dot in the middle of the letter, the dagesh. In Braille, we use separate characters.

### Letter 12: Lamed

- ל ⠇ dot 123

### Letter 13: Mem

- מ (Normal Mem) ⠍ dot 134
- ם (Final mem) ⠍ dot 134, used at the end of a word

### Letter 14: Nun

- נ (Normal Nun) ⠝ dot 1345
- ן (Final Nun) ⠝ dot 1345, used at the end of a word

### Letter 15: Samekh

- ס ⠎ dot 234

### Letter 16: Ayin

- ע ⠵ dot 1246

### Letter 17: Pe

The Pe  has two braille forms:

- פּ (Pe) ⠏ dot 1234, usually constructed of two unicode characters, \u5E4 and \U5BC
- פ (Fe) ⠋ dot 124, only \u5E4

In sighted script, these two forms are distinguished by a dot in the middle of the letter, the dagesh.

note that there is also a Final Pe (ף)

### Letter 18: Tsadi

- צ (Normal Tsadi) ⠮ dot 2346
- ץ (Final Tsadi) ⠮ dot 2346

### Letter 19: Qof

- ק ⠟ dot 12345

### Letter 20: Resh

- ר ⠗ dot 1235

### Letter 21: Shin

For Biblical Hebrew, the Shin has two forms that are also separated in most dictionaries (first all words with Sin, then all words with Shin). In other words, you could propose that Biblical Hebrew actually has 23 letters.

- The Sin variant has the Sin Dot modifier (ׂ, , \u5C2)
- The Shin variant has the Shin Dot modifier (ׁ, \u5C1)

The undifferenciated variant (Shin without dot) is very rare, only known in the Biblical name יִשָּׂשכָר (Issachar).

The Shin  therefore has two braille forms:

- ש (Sin) ⠱ dot 156
- שׁ (Shin) ⠩ dot 146

### Letter 22: Tav

The Tav  has two braille forms:

- תּ (Tav) ⠳ dot 1256
- ת (Sav) ⠹ dot 1456

## Vowels

Note that as Unicode is concerned, the Hebrew vowels are considered modifiers on top of the consonants. IN braille, they follow the consonants.

- ָ (Qamats) ⠣ dot 126
- ֳ (Hataf Qamats) ⠜ dot 345
- ַ (Patah) ⠉ dot 14
- ַ (Hataf patah) ⠒ dot 25

- ֵ (Tsere) ⠌ dot 34
- ֶ (Segol) ⠑ dot 15
- ֱ (Hataf Segol) ⠢ dot 26

- ִ (Hiriq) ⠊ dot 24

  Note that when the ִ is followed by a י (⠊⠚, dots 24-245), this is usually contracted to ⠔ (dot 35)

- ֹ (holam) ⠕ dot 135

  Note that when the ֹ is part of a holam-vav and therefore followed by a ו (⠕⠺, dots 135-2456), this is usually contracted to ⠪ (dot 246)

- ֻ (Kubuts) ⠥ dot 136

- וּ (Shuruq) ⠬ dot 346

- ְ (Sheva) ⠄ dot 3

  The Sheva indicates that a vowel has disappeared, leaving nothing or a brief fleeting sound.

## Other Signs

- ־ (Maqaf) ⠤ dot 36

### Dagesh

The same Hebrew character (ּ) is referred to in Unicode as Dagesh or Mapiq.

- Dagesh ⠐ dot 5
- Mapiq ⠘ dot 45


## Unicode modifier ordering

Modifiers like the vowels, dagesh or accents can appear on a consonant in an arbitrary order. Visually, בְּ (Bet Sheva Dagesh) looks equal to בְּ (Bet Dagesh Sheva). From a Braille translator perspective, they are obviously different and should all be treated as a Bet with Dagesh and following Sheva (⠃⠄).
