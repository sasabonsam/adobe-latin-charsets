### Notice

These character sets are informative, not normative. They are guidelines.
We reserve the right to update, modify, replace or withdraw them at any time without prior notice.

The [Unicode](http://unicode.org/) standard is continually evolving, and for this reason these character sets are **not** *set in stone*.
The likelihood of the larger charsets to be changed is greater than that of the smaller ones.
For instance, it’s unlikely that AL1 or AL2 will ever change, but AL3 and above have changed since they were first defined — the original version of AL3 didn’t include the turkish lira nor the ruble.
Also, a change in the smaller charsets naturally triggers a change in the larger ones.

We consider AL5 an open-ended set. Additions to it may be the result of 1) changes in AL4 and below, 2) additions to Unicode that have a direct relationship to characters already supported, 3) requests and recommendations from external parties/sources, 4) internal decisions, and 5) eventual bug fixes.
The AL1 thru AL4 sets are definitely less volatile and any changes to them go thru a stricter vetting process. Any new characters that we decide to support for which there’s no strong justification to attach to AL1-4 end up added to AL5.

---

# [Adobe Latin Character Sets](http://adobe-type-tools.github.io/adobe-latin-charsets)

## [Adobe Latin 1](http://adobe-type-tools.github.io/adobe-latin-charsets/adobe-latin-1.html) (ISO-Adobe)

AL1 is the original character set from Type 1 fonts, including the later addition of the euro. It covers major Western European Latin languages (a.k.a. *Roman* languages) and some minor ones: [Afrikaans](http://en.wikipedia.org/wiki/Afrikaans_language), [Basque](http://en.wikipedia.org/wiki/Basque_language), [Breton](http://en.wikipedia.org/wiki/Breton_language), [Catalan](http://en.wikipedia.org/wiki/Catalan_language) (without the l-dot, added in #Adobe Latin 3), [Danish](http://en.wikipedia.org/wiki/Danish_language), [Dutch](http://en.wikipedia.org/wiki/Dutch_language), [English](http://en.wikipedia.org/wiki/English_language), [Faroese](http://en.wikipedia.org/wiki/Faroese_language), [Finnish](http://en.wikipedia.org/wiki/Finnish_language), [French](http://en.wikipedia.org/wiki/French_language), [Gaelic](http://en.wikipedia.org/wiki/Scottish_Gaelic), [German](http://en.wikipedia.org/wiki/German_language), [Icelandic](http://en.wikipedia.org/wiki/Icelandic_language), [Indonesian](http://en.wikipedia.org/wiki/Indonesian_language), [Irish](http://en.wikipedia.org/wiki/Irish_language), [Italian](http://en.wikipedia.org/wiki/Italian_language), [Javanese(Latin)](http://en.wikipedia.org/wiki/Javanese_language), [Malay(Latin)](http://en.wikipedia.org/wiki/Malay_language), [Norwegian](http://en.wikipedia.org/wiki/Norwegian_language), [Portuguese](http://en.wikipedia.org/wiki/Portuguese_language), [Sami(Southern)](http://en.wikipedia.org/wiki/Sami_languages), [Spanish](http://en.wikipedia.org/wiki/Spanish_language), [Swahili](http://en.wikipedia.org/wiki/Swahili_language), [Swedish](http://en.wikipedia.org/wiki/Swedish_language), and [Walloon](http://en.wikipedia.org/wiki/Walloon_language).

*(Note that the term* Roman *is to be avoided! It has multiple independent and often conflicting meanings in typography: upright vs italic/oblique, single-byte Latin vs CE/other, or in the style of classical Roman lettering vs not.)*


## [Adobe Latin 2](http://adobe-type-tools.github.io/adobe-latin-charsets/adobe-latin-2.html) (Adobe Western 2)

AL2 is the most basic OpenType character set for Adobe fonts, the minimum for **Std** fonts with Western language support.

Language coverage is the same as Adobe Latin 1; the added characters are various symbols:

* ℓ uni2113 (litre)
* ℮ estimated
* the 14 Mac *symbol substitution* characters
	* Ω uni2126 (Ohm/Omega)
	* π pi
	* ∂ partialdiff
	* ∆ uni2206 (Delta)
	* ∏ product
	* ∑ summation
	* √ radical
	* ∞ infinity
	* ∫ integral
	* ≈ approxequal
	* ≠ notequal
	* ≤ lessequal
	* ≥ greaterequal
	* ◊ lozenge
* and 4 characters using duplicated glyphs from other characters
	* uni00A0 from space
	* uni00AD from hyphen
	* uni02C9 from macron
	* uni2215 from fraction
	* uni2219 from periodcentered


## [Adobe Latin 3](http://adobe-type-tools.github.io/adobe-latin-charsets/adobe-latin-3.html) (Adobe CE)

AL3 is the union of the AL2 character set and the Adobe CE character set, which includes major Latin-based Central European (CE) languages. AL3 is the minimum character set for Western **Pro** fonts.

AL3 covers the same languages as AL1-2, plus [Croatian(Latin)](http://en.wikipedia.org/wiki/Croatian_language), [Czech](http://en.wikipedia.org/wiki/Czech_language), [Estonian](http://en.wikipedia.org/wiki/Estonian_language), [Gagauz(Latin)](http://en.wikipedia.org/wiki/Gagauz_language), [Hungarian](http://en.wikipedia.org/wiki/Hungarian_language), [Kashubian](http://en.wikipedia.org/wiki/Kashubian_language), [Latvian](http://en.wikipedia.org/wiki/Latvian_language), [Lithuanian](http://en.wikipedia.org/wiki/Lithuanian_language), [Moldovan(Latin)](http://en.wikipedia.org/wiki/Moldovan_language), [Polish](http://en.wikipedia.org/wiki/Polish_language), [Romanian(Latin)](http://en.wikipedia.org/wiki/Romanian_alphabet), [Sami(Northern, Inari, and Lule)](http://en.wikipedia.org/wiki/Sami_languages), [Serbian(Latin)](http://en.wikipedia.org/wiki/Serbian_Latin_alphabet), [Silesian](http://en.wikipedia.org/wiki/Silesian_language), [Sorbian](http://en.wikipedia.org/wiki/Sorbian_language), [Slovak](http://en.wikipedia.org/wiki/Slovak_language), [Slovenian](http://en.wikipedia.org/wiki/Slovenian_language) and [Turkish](http://en.wikipedia.org/wiki/Turkish_alphabet).

*Note: Lithuanian retains the dot in a lowercase i when followed by accents (refer to [Unicode's Special Casing](http://www.unicode.org/Public/UNIDATA/SpecialCasing.txt)).*


## [Adobe Latin 4](http://adobe-type-tools.github.io/adobe-latin-charsets/adobe-latin-4.html)

Compared to AL3, it adds support for: Afar, Azerbaijani(Latin), Belarusian(Latin), Chamorro, Chichewa, Esperanto, Filipino/Tagalog, Gikuyu, Greenlandic, Guarani, Hawaiian, Igo/Igbo, Kuskokwim, Luba (Ciluba), Maltese, Māori, Marquesan, Ndebele, Oromo, Samoan, Setswana, Sidamo, Somali, Sotho (Northern and Southern), Swazi, Tahitian, Tetum, Tongan, Tsonga, Tuareg, Uzbek(Latin), Vietnamese, Wallisian, Welsh, Xhosa, Yoruba, and Zulu.

For Latin-based transliteration, it supports several schemes for Indic and Arabic, as well as Cyrillic and Pinyin Chinese.


## [Adobe Latin 5](http://adobe-type-tools.github.io/adobe-latin-charsets/adobe-latin-5.html)

Additional languages supported are: Bambara, Baule, Northern Berber languages (Tarifit, Kabyle, Tachelhit, Tamashek, etc.), Bislama, Cornish, Croatian(Latin)<sup>1</sup>, Navajo, Dinka, Fula, Hausa, Latin<sup>2</sup>, Lingala, Luxembourgish, Malagasy, Marshallese, Mende, Skolt Sami, Venda, Wolof.

For transliteration, it adds support for International Phonetic Association (IPA), Khmer, Mongolian, another Hindi scheme, pan-Athapaskan native American languages, and the Americanist Phonetic Alphabet (APA). Note that most of the added characters are actually supporting transliteration/phonetic needs.

<sup>1</sup> Croatian(Latin) is already supported in AL3. The digraphs (in practice never used) are included in AL5.

<sup>2</sup> Latin requires these characters **ĬĭŎŏ(Ŭŭ)**.
