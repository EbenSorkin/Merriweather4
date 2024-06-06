## FontBakery report

fontbakery version: 0.12.1



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] Merriweather[opsz,wdth,wght].ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Validate location, size and resolution of article images. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/variable does not have an article.</p>
 [code: lacks-article]



</div>
</details>
</div>
</details>

<details><summary>[2] Merriweather-Italic[opsz,wdth,wght].ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Validate location, size and resolution of article images. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/variable does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure the font's instances are in the correct order. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.varfont.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The fvar table instances are not in ascending order of weight:
- {'wght': 300.0, 'wdth': 100.0, 'opsz': 144.0}</p>
<pre><code>- {'wght': 400.0, 'wdth': 100.0, 'opsz': 144.0}

- {'wght': 500.0, 'wdth': 100.0, 'opsz': 144.0}

- {'wght': 700.0, 'wdth': 100.0, 'opsz': 144.0}

- {'wght': 600.0, 'wdth': 100.0, 'opsz': 144.0}

- {'wght': 800.0, 'wdth': 100.0, 'opsz': 144.0}

- {'wght': 900.0, 'wdth': 100.0, 'opsz': 144.0}
</code></pre>
 [code: instances-not-in-order]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[17] Merriweather[opsz,wdth,wght].ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Check mark characters are in GDEF mark glyph class. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following mark characters could be in the GDEF mark glyph class:
uni0488 (U+0488) and uni0489 (U+0489)</p>
 [code: mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Interpolation issues were found in the font:</p>
<pre><code>- Contour 0 point 21 has a kink between location wght=300,wdth=100,opsz=12 and location wght=900,wdth=87,opsz=144

- Contour 0 point 21 has a kink between location wght=900,wdth=112,opsz=144 and location wght=300,wdth=100,opsz=144

- Contour 0 point 0 has a kink between location wght=900,wdth=100,opsz=144 and location wght=900,wdth=87,opsz=12
</code></pre>
 [code: interpolation-issues]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 1338 among a set of 6 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 1281:
plus, plusminus</p>
<p>Width = 1289:
equal</p>
<p>Width = 1326:
logicalnot</p>
<p>Width = 1238:
multiply</p>
<p>Width = 1283:
divide</p>
<p>Width = 1224:
minus</p>
<p>Width = 1389:
approxequal</p>
<p>Width = 1279:
notequal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking with ots-sanitize. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>ots-sanitize passed this file, however warnings were printed:</p>
<p>ERROR: STAT: Invalid nameID: 24
ERROR: Table discarded</p>
 [code: ots-sanitize-warn]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- I.uc

- IJ_acutecomb

- acute.narrow

- belt_part..001

- caron.alt

- circumflex.narrow

- cy.i_part.

- dafrican.sc

- dieresis.narrow

- dotlessi_dotbelowcomb

- dotlessi_ogonek

- f_f.sc

- f_f_i.sc

- f_f_l.sc

- fhook.sc

- grave.narrow

- i.dot

- ij_acutecomb

- j.latnNLD

- lcslash_part.

- macron.narrow

- ocenteredtilde.sc

- ogonek.narrow

- omegabroadcy.sc

- tilde.narrow

- tildecomb_acutecomb

- u1d53

- uni00AD.case

- uni01310330

- uni01310331

- uni013B.latnMAH

- uni0145.latnMAH

- uni01A9.localGAD

- uni01B7.localGAD

- uni03000304

- uni03000358

- uni03010304

- uni03010307

- uni03010358

- uni03020358

- uni03030304

- uni03030308

- uni03040300

- uni03040301

- uni03040308

- uni03040358

- uni03060358

- uni03070304

- uni03080300

- uni03080301

- uni03080304

- uni0308030C

- uni030C0307

- uni030D0358

- uni0438.l.sc

- uni2071.dotless

- uniA64D.sc
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: i̯̇ i̯̊ i̯̋ i̯̍ i̯̐ i̯̒ i̯̓ i̯᷄ i̯᷅ i̯᷆ i̯᷇ i̯᷈ i̯᷉ i̯ꚞ i̴̇ i̴̊ i̴̋ i̴̍ i̴̐ i̴̒</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Ijo, Southeast (Latn, 2,471,000 speakers), Navajo (Latn, 166,319 speakers), Lithuanian (Latn, 2,357,094 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ekpeye (Latn, 226,000 speakers), Yala (Latn, 200,000 speakers), Nateni (Latn, 100,000 speakers), Ebira (Latn, 2,200,000 speakers), Cicipu (Latn, 44,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Bete-Bendi (Latn, 100,000 speakers), Dutch (Latn, 31,709,104 speakers), Ma’di (Latn, 584,000 speakers), Zapotec (Latn, 490,000 speakers), Nzakara (Latn, 50,000 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Lugbara (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Kom (Latn, 360,685 speakers), Makaa (Latn, 221,000 speakers), Mango (Latn, 77,000 speakers), Mundani (Latn, 34,000 speakers), Dii (Latn, 71,000 speakers), Bafut (Latn, 158,146 speakers), Aghem (Latn, 38,843 speakers), Fur (Latn, 1,230,163 speakers), Sar (Latn, 500,000 speakers), Avokaya (Latn, 100,000 speakers), Dan (Latn, 1,099,244 speakers), South Central Banda (Latn, 244,000 speakers), Southern Kisi (Latn, 360,000 speakers), Gulay (Latn, 250,478 speakers), Igbo (Latn, 27,823,640 speakers), Mfumte (Latn, 79,000 speakers), Ejagham (Latn, 120,000 speakers), Basaa (Latn, 332,940 speakers), Kpelle, Guinea (Latn, 622,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02B0 MODIFIER LETTER SMALL H: not included in any glyphset definition</li>
<li>U+02B7 MODIFIER LETTER SMALL W: not included in any glyphset definition</li>
<li>U+02B8 MODIFIER LETTER SMALL Y: not included in any glyphset definition</li>
<li>U+02B9 MODIFIER LETTER PRIME: not included in any glyphset definition</li>
<li>U+02BA MODIFIER LETTER DOUBLE PRIME: not included in any glyphset definition</li>
<li>U+02BD MODIFIER LETTER REVERSED COMMA: not included in any glyphset definition</li>
<li>U+02BE MODIFIER LETTER RIGHT HALF RING: not included in any glyphset definition</li>
<li>U+02BF MODIFIER LETTER LEFT HALF RING: not included in any glyphset definition</li>
<li>U+02C0 MODIFIER LETTER GLOTTAL STOP: not included in any glyphset definition</li>
<li>U+02C1 MODIFIER LETTER REVERSED GLOTTAL STOP: not included in any glyphset definition</li>
<li>U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh</li>
<li>U+02C8 MODIFIER LETTER VERTICAL LINE: not included in any glyphset definition</li>
<li>U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition</li>
<li>U+02CA MODIFIER LETTER ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+02CB MODIFIER LETTER GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+02CC MODIFIER LETTER LOW VERTICAL LINE: not included in any glyphset definition</li>
<li>U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition</li>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+02EC MODIFIER LETTER VOICING: not included in any glyphset definition</li>
<li>U+02EE MODIFIER LETTER DOUBLE APOSTROPHE: not included in any glyphset definition</li>
<li>U+02FB MODIFIER LETTER BEGIN LOW TONE: not included in any glyphset definition</li>
<li>U+02FC MODIFIER LETTER END LOW TONE: not included in any glyphset definition</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, coptic, cherokee, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: coptic, math, tifinagh, syriac, old-permic, canadian-aboriginal, malayalam, tai-le</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+030D COMBINING VERTICAL LINE ABOVE: not included in any glyphset definition</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0310 COMBINING CANDRABINDU: not included in any glyphset definition</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding coptic</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition</li>
<li>U+0313 COMBINING COMMA ABOVE: try adding old-permic</li>
<li>U+0315 COMBINING COMMA ABOVE RIGHT: not included in any glyphset definition</li>
<li>U+031B COMBINING HORN: not included in any glyphset definition</li>
<li>U+0320 COMBINING MINUS SIGN BELOW: try adding syriac</li>
<li>U+0324 COMBINING DIAERESIS BELOW: try adding one of: syriac, cherokee</li>
<li>U+0325 COMBINING RING BELOW: try adding syriac</li>
<li>U+0326 COMBINING COMMA BELOW: not included in any glyphset definition</li>
<li>U+0327 COMBINING CEDILLA: not included in any glyphset definition</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding syriac</li>
<li>U+032E COMBINING BREVE BELOW: try adding syriac</li>
<li>U+032F COMBINING INVERTED BREVE BELOW: not included in any glyphset definition</li>
<li>U+0330 COMBINING TILDE BELOW: try adding one of: syriac, math, cherokee</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: cherokee, tifinagh, syriac, gothic, caucasian-albanian</li>
<li>U+0332 COMBINING LOW LINE: not included in any glyphset definition</li>
<li>U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition</li>
<li>U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+0336 COMBINING LONG STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+0337 COMBINING SHORT SOLIDUS OVERLAY: not included in any glyphset definition</li>
<li>U+0338 COMBINING LONG SOLIDUS OVERLAY: not included in any glyphset definition</li>
<li>U+0358 COMBINING DOT ABOVE RIGHT: try adding osage</li>
<li>U+035C COMBINING DOUBLE BREVE BELOW: not included in any glyphset definition</li>
<li>U+035D COMBINING DOUBLE BREVE: not included in any glyphset definition</li>
<li>U+035F COMBINING DOUBLE MACRON BELOW: not included in any glyphset definition</li>
<li>U+0361 COMBINING DOUBLE INVERTED BREVE: try adding coptic</li>
<li>U+0362 COMBINING DOUBLE RIGHTWARDS ARROW BELOW: not included in any glyphset definition</li>
<li>U+058F ARMENIAN DRAM SIGN: try adding armenian</li>
<li>U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai</li>
<li>U+1D05 LATIN LETTER SMALL CAPITAL D: not included in any glyphset definition</li>
<li>U+1D3A MODIFIER LETTER CAPITAL N: not included in any glyphset definition</li>
<li>U+1D43 MODIFIER LETTER SMALL A: not included in any glyphset definition</li>
<li>U+1D49 MODIFIER LETTER SMALL E: not included in any glyphset definition</li>
<li>U+1D4B MODIFIER LETTER SMALL OPEN E: not included in any glyphset definition</li>
<li>U+1D4D MODIFIER LETTER SMALL G: not included in any glyphset definition</li>
<li>U+1D52 MODIFIER LETTER SMALL O: not included in any glyphset definition</li>
<li>U+1D53 MODIFIER LETTER SMALL OPEN O: not included in any glyphset definition</li>
<li>U+1D58 MODIFIER LETTER SMALL U: not included in any glyphset definition</li>
<li>U+1D5B MODIFIER LETTER SMALL V: not included in any glyphset definition</li>
<li>U+1D7B LATIN SMALL CAPITAL LETTER I WITH STROKE: not included in any glyphset definition</li>
<li>U+1D7D LATIN SMALL LETTER P WITH STROKE: not included in any glyphset definition</li>
<li>U+1D7E LATIN SMALL CAPITAL LETTER U WITH STROKE: not included in any glyphset definition</li>
<li>U+1D91 LATIN SMALL LETTER D WITH HOOK AND TAIL: not included in any glyphset definition</li>
<li>U+1DA4 MODIFIER LETTER SMALL I WITH STROKE: not included in any glyphset definition</li>
<li>U+1DB6 MODIFIER LETTER SMALL U BAR: not included in any glyphset definition</li>
<li>U+1DBB MODIFIER LETTER SMALL Z: not included in any glyphset definition</li>
<li>U+1DBF MODIFIER LETTER SMALL THETA: not included in any glyphset definition</li>
<li>U+1DC4 COMBINING MACRON-ACUTE: not included in any glyphset definition</li>
<li>U+1DC5 COMBINING GRAVE-MACRON: not included in any glyphset definition</li>
<li>U+1DC6 COMBINING MACRON-GRAVE: not included in any glyphset definition</li>
<li>U+1DC7 COMBINING ACUTE-MACRON: not included in any glyphset definition</li>
<li>U+1DC8 COMBINING GRAVE-ACUTE-GRAVE: not included in any glyphset definition</li>
<li>U+1DC9 COMBINING ACUTE-GRAVE-ACUTE: not included in any glyphset definition</li>
<li>U+1DCA COMBINING LATIN SMALL LETTER R BELOW: not included in any glyphset definition</li>
<li>U+2000 EN QUAD: not included in any glyphset definition</li>
<li>U+2001 EM QUAD: not included in any glyphset definition</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: not included in any glyphset definition</li>
<li>U+2005 FOUR-PER-EM SPACE: not included in any glyphset definition</li>
<li>U+2006 SIX-PER-EM SPACE: not included in any glyphset definition</li>
<li>U+2007 FIGURE SPACE: not included in any glyphset definition</li>
<li>U+2008 PUNCTUATION SPACE: not included in any glyphset definition</li>
<li>U+200A HAIR SPACE: not included in any glyphset definition</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: nko, myanmar, tai-tham, rejang, kaithi, grantha, sundanese, kannada, manichaean, hanifi-rohingya, bhaiksuki, javanese, meetei-mayek, batak, modi, oriya, tamil, zanabazar-square, chakma, lao, phags-pa, gunjala-gondi, sogdian, syloti-nagri, tai-viet, masaram-gondi, buhid, sinhala, tibetan, siddham, tagbanwa, takri, khojki, limbu, new-tai-lue, lepcha, pahawh-hmong, bengali, devanagari, syriac, thai, mongolian, dogra, tagalog, tai-le, hatran, tifinagh, hanunoo, gujarati, duployan, warang-citi, mahajani, arabic, cham, kayah-li, newa, telugu, khmer, thaana, tirhuta, khudawadi, sharada, mandaic, psalter-pahlavi, brahmi, hebrew, yi, kharoshthi, saurashtra, malayalam, gurmukhi, balinese, avestan, buginese</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: nko, myanmar, tai-tham, rejang, kaithi, grantha, sundanese, kannada, manichaean, hanifi-rohingya, bhaiksuki, javanese, meetei-mayek, batak, modi, oriya, tamil, zanabazar-square, chakma, lao, phags-pa, gunjala-gondi, sogdian, syloti-nagri, tai-viet, masaram-gondi, buhid, sinhala, tibetan, siddham, tagbanwa, takri, khojki, limbu, new-tai-lue, lepcha, pahawh-hmong, bengali, devanagari, syriac, thai, mongolian, dogra, tagalog, tai-le, tifinagh, hanunoo, gujarati, duployan, warang-citi, mahajani, old-hungarian, arabic, cham, kayah-li, newa, telugu, khmer, thaana, tirhuta, khudawadi, sharada, mandaic, psalter-pahlavi, brahmi, hebrew, yi, kharoshthi, saurashtra, malayalam, gurmukhi, balinese, avestan, buginese</li>
<li>U+2010 HYPHEN: try adding one of: armenian, coptic, arabic, cham, kayah-li, lisu, syloti-nagri, kaithi, sundanese, sora-sompeng, yi, hebrew, kharoshthi</li>
<li>U+2011 NON-BREAKING HYPHEN: try adding one of: yi, syloti-nagri, arabic</li>
<li>U+2012 FIGURE DASH: not included in any glyphset definition</li>
<li>U+2015 HORIZONTAL BAR: try adding adlam</li>
<li>U+2016 DOUBLE VERTICAL LINE: not included in any glyphset definition</li>
<li>U+201B SINGLE HIGH-REVERSED-9 QUOTATION MARK: try adding adlam</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2023 TRIANGULAR BULLET: not included in any glyphset definition</li>
<li>U+2027 HYPHENATION POINT: not included in any glyphset definition</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, mongolian</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+2034 TRIPLE PRIME: try adding math</li>
<li>U+203C DOUBLE EXCLAMATION MARK: not included in any glyphset definition</li>
<li>U+2042 ASTERISM: not included in any glyphset definition</li>
<li>U+204A TIRONIAN SIGN ET: not included in any glyphset definition</li>
<li>U+2052 COMMERCIAL MINUS SIGN: not included in any glyphset definition</li>
<li>U+2070 SUPERSCRIPT ZERO: not included in any glyphset definition</li>
<li>U+2071 SUPERSCRIPT LATIN SMALL LETTER I: not included in any glyphset definition</li>
<li>U+2075 SUPERSCRIPT FIVE: not included in any glyphset definition</li>
<li>U+2076 SUPERSCRIPT SIX: not included in any glyphset definition</li>
<li>U+2077 SUPERSCRIPT SEVEN: not included in any glyphset definition</li>
<li>U+2078 SUPERSCRIPT EIGHT: not included in any glyphset definition</li>
<li>U+2079 SUPERSCRIPT NINE: not included in any glyphset definition</li>
<li>U+207F SUPERSCRIPT LATIN SMALL LETTER N: not included in any glyphset definition</li>
<li>U+2080 SUBSCRIPT ZERO: not included in any glyphset definition</li>
<li>U+2081 SUBSCRIPT ONE: not included in any glyphset definition</li>
<li>U+2082 SUBSCRIPT TWO: not included in any glyphset definition</li>
<li>U+2083 SUBSCRIPT THREE: not included in any glyphset definition</li>
<li>U+2084 SUBSCRIPT FOUR: not included in any glyphset definition</li>
<li>U+2085 SUBSCRIPT FIVE: not included in any glyphset definition</li>
<li>U+2086 SUBSCRIPT SIX: not included in any glyphset definition</li>
<li>U+2087 SUBSCRIPT SEVEN: not included in any glyphset definition</li>
<li>U+2088 SUBSCRIPT EIGHT: not included in any glyphset definition</li>
<li>U+2089 SUBSCRIPT NINE: not included in any glyphset definition</li>
<li>U+2100 ACCOUNT OF: not included in any glyphset definition</li>
<li>U+2101 ADDRESSED TO THE SUBJECT: not included in any glyphset definition</li>
<li>U+2105 CARE OF: not included in any glyphset definition</li>
<li>U+2106 CADA UNA: not included in any glyphset definition</li>
<li>U+2117 SOUND RECORDING COPYRIGHT: not included in any glyphset definition</li>
<li>U+2126 OHM SIGN: not included in any glyphset definition</li>
<li>U+212E ESTIMATED SYMBOL: not included in any glyphset definition</li>
<li>U+2144 TURNED SANS-SERIF CAPITAL Y: not included in any glyphset definition</li>
<li>U+2150 VULGAR FRACTION ONE SEVENTH: not included in any glyphset definition</li>
<li>U+2151 VULGAR FRACTION ONE NINTH: not included in any glyphset definition</li>
<li>U+2152 VULGAR FRACTION ONE TENTH: not included in any glyphset definition</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: not included in any glyphset definition</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: not included in any glyphset definition</li>
<li>U+2155 VULGAR FRACTION ONE FIFTH: not included in any glyphset definition</li>
<li>U+2156 VULGAR FRACTION TWO FIFTHS: not included in any glyphset definition</li>
<li>U+2158 VULGAR FRACTION FOUR FIFTHS: not included in any glyphset definition</li>
<li>U+2159 VULGAR FRACTION ONE SIXTH: not included in any glyphset definition</li>
<li>U+215A VULGAR FRACTION FIVE SIXTHS: not included in any glyphset definition</li>
<li>U+215B VULGAR FRACTION ONE EIGHTH: not included in any glyphset definition</li>
<li>U+215C VULGAR FRACTION THREE EIGHTHS: not included in any glyphset definition</li>
<li>U+215D VULGAR FRACTION FIVE EIGHTHS: not included in any glyphset definition</li>
<li>U+215E VULGAR FRACTION SEVEN EIGHTHS: not included in any glyphset definition</li>
<li>U+2183 ROMAN NUMERAL REVERSED ONE HUNDRED: try adding symbols</li>
<li>U+2184 LATIN SMALL LETTER REVERSED C: not included in any glyphset definition</li>
<li>U+2190 LEFTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2194 LEFT RIGHT ARROW: try adding one of: symbols, math</li>
<li>U+2195 UP DOWN ARROW: try adding one of: symbols, math</li>
<li>U+2196 NORTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+2197 NORTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2198 SOUTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2199 SOUTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2205 EMPTY SET: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+2219 BULLET OPERATOR: try adding one of: yi, tai-tham, symbols, math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2236 RATIO: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+2266 LESS-THAN OVER EQUAL TO: try adding math</li>
<li>U+2267 GREATER-THAN OVER EQUAL TO: try adding math</li>
<li>U+2317 VIEWDATA SQUARE: try adding symbols</li>
<li>U+24B6 CIRCLED LATIN CAPITAL LETTER A: try adding symbols</li>
<li>U+24D0 CIRCLED LATIN SMALL LETTER A: try adding symbols</li>
<li>U+25A0 BLACK SQUARE: try adding symbols</li>
<li>U+25A1 WHITE SQUARE: try adding symbols</li>
<li>U+25AA BLACK SMALL SQUARE: try adding symbols</li>
<li>U+25AB WHITE SMALL SQUARE: try adding symbols</li>
<li>U+25B2 BLACK UP-POINTING TRIANGLE: try adding symbols</li>
<li>U+25B3 WHITE UP-POINTING TRIANGLE: try adding one of: symbols, math</li>
<li>U+25B4 BLACK UP-POINTING SMALL TRIANGLE: try adding symbols</li>
<li>U+25B5 WHITE UP-POINTING SMALL TRIANGLE: try adding symbols</li>
<li>U+25B6 BLACK RIGHT-POINTING TRIANGLE: try adding symbols</li>
<li>U+25B7 WHITE RIGHT-POINTING TRIANGLE: try adding one of: symbols, math</li>
<li>U+25B8 BLACK RIGHT-POINTING SMALL TRIANGLE: try adding symbols</li>
<li>U+25B9 WHITE RIGHT-POINTING SMALL TRIANGLE: try adding symbols</li>
<li>U+25BC BLACK DOWN-POINTING TRIANGLE: try adding symbols</li>
<li>U+25BD WHITE DOWN-POINTING TRIANGLE: try adding one of: symbols, math</li>
<li>U+25BE BLACK DOWN-POINTING SMALL TRIANGLE: try adding symbols</li>
<li>U+25BF WHITE DOWN-POINTING SMALL TRIANGLE: try adding symbols</li>
<li>U+25C0 BLACK LEFT-POINTING TRIANGLE: try adding symbols</li>
<li>U+25C1 WHITE LEFT-POINTING TRIANGLE: try adding one of: symbols, math</li>
<li>U+25C2 BLACK LEFT-POINTING SMALL TRIANGLE: try adding symbols</li>
<li>U+25C3 WHITE LEFT-POINTING SMALL TRIANGLE: try adding symbols</li>
<li>U+25C6 BLACK DIAMOND: try adding symbols</li>
<li>U+25C7 WHITE DIAMOND: try adding symbols</li>
<li>U+25C9 FISHEYE: try adding symbols</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+25CB WHITE CIRCLE: try adding symbols</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: tamil, kaithi, modi, manichaean, hanifi-rohingya, meetei-mayek, batak, zanabazar-square, phags-pa, gunjala-gondi, sogdian, tai-viet, canadian-aboriginal, math, lepcha, pahawh-hmong, adlam, tagalog, duployan, mahajani, yi, brahmi, hebrew, warang-citi, buginese, rejang, grantha, oriya, bhaiksuki, syloti-nagri, ahom, takri, khojki, coptic, limbu, new-tai-lue, thai, bassa-vah, caucasian-albanian, cham, thaana, telugu, khmer, khudawadi, mandaic, psalter-pahlavi, kharoshthi, saurashtra, gurmukhi, balinese, tai-le, myanmar, tai-tham, sundanese, javanese, symbols, chakma, masaram-gondi, sinhala, tibetan, tagbanwa, elbasan, mongolian, hanunoo, marchen, kayah-li, newa, sharada, music, armenian, nko, mende-kikakui, tifinagh, kannada, lao, old-permic, buhid, miao, siddham, wancho, bengali, devanagari, syriac, dogra, soyombo, gujarati, tirhuta, osage, malayalam</li>
<li>U+25CF BLACK CIRCLE: try adding symbols</li>
<li>U+25E6 WHITE BULLET: try adding symbols</li>
<li>U+25FC BLACK MEDIUM SQUARE: try adding symbols</li>
<li>U+2611 BALLOT BOX WITH CHECK: try adding symbols</li>
<li>U+2612 BALLOT BOX WITH X: try adding symbols</li>
<li>U+2661 WHITE HEART SUIT: try adding symbols</li>
<li>U+2665 BLACK HEART SUIT: try adding symbols</li>
<li>U+27A1 BLACK RIGHTWARDS ARROW: try adding symbols</li>
<li>U+27E8 MATHEMATICAL LEFT ANGLE BRACKET: try adding math</li>
<li>U+27E9 MATHEMATICAL RIGHT ANGLE BRACKET: try adding math</li>
<li>U+2B05 LEFTWARDS BLACK ARROW: try adding symbols</li>
<li>U+2B06 UPWARDS BLACK ARROW: try adding symbols</li>
<li>U+2B07 DOWNWARDS BLACK ARROW: try adding symbols</li>
<li>U+2B08 NORTH EAST BLACK ARROW: try adding symbols</li>
<li>U+2B09 NORTH WEST BLACK ARROW: try adding symbols</li>
<li>U+2B0A SOUTH EAST BLACK ARROW: try adding symbols</li>
<li>U+2B0B SOUTH WEST BLACK ARROW: try adding symbols</li>
<li>U+2B1B BLACK LARGE SQUARE: try adding symbols</li>
<li>U+2B1C WHITE LARGE SQUARE: try adding symbols</li>
<li>U+2B98 THREE-D TOP-LIGHTED LEFTWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B99 THREE-D RIGHT-LIGHTED UPWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9A THREE-D TOP-LIGHTED RIGHTWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9B THREE-D LEFT-LIGHTED DOWNWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9C BLACK LEFTWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9D BLACK UPWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9E BLACK RIGHTWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9F BLACK DOWNWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2E17 DOUBLE OBLIQUE HYPHEN: try adding coptic</li>
<li>U+2E38 TURNED DAGGER: not included in any glyphset definition</li>
<li>U+3003 DITTO MARK: try adding one of: phags-pa, chinese-simplified, japanese, chinese-hongkong, yi, chinese-traditional</li>
<li>U+A717 MODIFIER LETTER DOT VERTICAL BAR: not included in any glyphset definition</li>
<li>U+A718 MODIFIER LETTER DOT SLASH: not included in any glyphset definition</li>
<li>U+A719 MODIFIER LETTER DOT HORIZONTAL BAR: not included in any glyphset definition</li>
<li>U+A71A MODIFIER LETTER LOWER RIGHT CORNER ANGLE: not included in any glyphset definition</li>
<li>U+A7CB : not included in any glyphset definition</li>
<li>U+A7CC : not included in any glyphset definition</li>
<li>U+A7CD : not included in any glyphset definition</li>
<li>U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic</code>, <code>cyrillic-ext</code>, <code>greek-ext</code>, <code>latin</code>, <code>latin-ext</code>, <code>vietnamese</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Name table strings must not contain the string 'Reserved Font Name'. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.license.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Name table entry contains &quot;Reserved Font Name&quot; for a family name (&quot;Merriweather&quot;) that differs from the currently used family name (Merriweather), which is fine.</p>
 [code: legacy-familyname]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure files are not too large. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Font file is 4.4Mb; ideally it should be less than 1.0Mb</p>
 [code: large-font]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- f + i

- f + l
</code></pre>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Do we have the latest version of FontBakery installed? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Current FontBakery version is 0.12.1, while a newer 0.12.7 is already available. Please upgrade it with 'pip install -U fontbakery'</p>
 [code: outdated-fontbakery]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking with fontTools.ttx <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>WARNING: name id 24 missing from name table</p>
 



* 🔥 **FAIL** <p>WARNING: name id 48 missing from name table</p>
 



* 🔥 **FAIL** <p>WARNING: name id 64 missing from name table</p>
 



* 🔥 **FAIL** <p>WARNING: name id 72 missing from name table</p>
 



* 🔥 **FAIL** <p>WARNING: name id 144 missing from name table</p>
 





</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">cae_Latn (Lehar)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">kss_Latn (Southern Kisi)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">kzr_Latn (Karang)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ybb_Latn (Yemba)</td>
<td align="left">Shaper didn't attach uni0304 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">meq_Latn (Merey)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">snf_Latn (Noon)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bum_Latn (Bulu)</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">dow_Latn (Doyayo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">sld_Latn (Sissala)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ikx_Latn (Ik)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">csk_Latn (Jola-Kasa)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">gvl_Latn (Gulay)</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">tik_Latn (Tikar)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mbo_Latn (Mbo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">fue_Latn (Fulfulde, Borgu)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">cko_Latn (Anufo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">neb_Latn (Toura)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">lem_Latn (Nomaande)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ewo_Latn (Ewondo)</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">kia_Latn (Kim)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">kyq_Latn (Kenga)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bex_Latn (Jur Modo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mor_Latn (Moro)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">dag_Latn (Dagbani)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">tnr_Latn (Ménik)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bza_Latn (Bandi)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">kyf_Latn (Kouya)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">nku_Latn (Kulango, Bouna)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">sig_Latn (Paasaal)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bbj_Latn (Ghomala)</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mgo_Latn (Metaʼ)</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bim_Latn (Bimoba)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">yav_Latn (Yangben)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">wci_Latn (Gbe, Waci)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Requires Small-cap: ƒ; both buffers returned florin=0+1023</td>
</tr>
<tr>
<td align="left">avu_Latn (Avokaya)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">vag_Latn (Vagla)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">sil_Latn (Sisaala, Tumulung)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">dyo_Latn (Jola-Fonyi)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">wwa_Latn (Waama)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">sav_Latn (Saafi-Saafi)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">wo_Latn (Wolof)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mzw_Latn (Deg)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ncu_Latn (Chumburung)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">udu_Latn (Uduk)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">nfu_Latn (Mfumte)</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">yat_Latn (Yambeta)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mcn_Latn (Masana)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">fod_Latn (Foodo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">vut_Latn (Vute)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">dop_Latn (Lukpa)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mdt_Latn (Mbere)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ekm_Latn (Elip)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">soy_Latn (Miyobe)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">agc_Latn (Agatu)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">acd_Latn (Gikyode)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">kye_Latn (Krache)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">lmp_Latn (Limbum)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">spp_Latn (Sénoufo, Supyire)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mfq_Latn (Moba)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bqj_Latn (Bandial)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bib_Latn (Bissa)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mfd_Latn (Mendankwe-Nkwen)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">shz_Latn (Syenara Senoufo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">lee_Latn (Lyélé)</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">vai_Latn (Vai (Latin))</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">moa_Latn (Mwan)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">fan_Latn (Fang)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">dtm_Latn (Tomo Kan Dogon)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ttq_Latn (Tawallammat Tamajaq)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ntr_Latn (Delo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bm_Latn (Bambara)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">lg_Latn (Ganda)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">dyi_Latn (Sénoufo, Djimini)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">kpo_Latn (Ikposo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">rub_Latn (Gungu)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">dnj_Latn (Dan)</td>
<td align="left">Shaper didn't attach uni0302 to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030F to uni0264</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0264</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0264</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0264</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B to uni0264</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030F to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0264</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030F to uni0264</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030F to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0264</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0264</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0264</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B to uni0264</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0264</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030F to uni0264.sc</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030F to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0264.sc</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0264.sc</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0264.sc</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B to uni0264.sc</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0264.sc</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect uni0181</td>
</tr>
<tr>
<td align="left">mfi_Latn (Wandala)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">gux_Latn (Gourmanchéma)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">fvr_Latn (Fur)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">fuq_Latn (Central-Eastern Niger Fulfulde)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bkm_Latn (Kom)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">nym_Latn (Nyamwezi)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">nnh_Latn (Ngiemboon)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bss_Latn (Akoose)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">etu_Latn (Ejagham)</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">lnl_Latn (South Central Banda)</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0259</td>
</tr>
<tr>
<td align="left">sxw_Latn (Saxwe Gbe)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">daa_Latn (Dangaléat)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bqv_Latn (Koro Wachi)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bud_Latn (Ntcham)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">adj_Latn (Adioukrou)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">khq_Latn (Koyra Chiini)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">lia_Latn (Limba, West-Central)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">nus_Latn (Nuer)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">tem_Latn (Timne)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">gnd_Latn (Zulgo-Gemzek)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">pil_Latn (Yom)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">wan_Latn (Wan)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">log_Latn (Logo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">kao_Latn (Xaasongaxango)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mnf_Latn (Mundani)</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">twq_Latn (Tasawaq)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ksf_Latn (Bafia)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ksp_Latn (Kabba)</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0259</td>
</tr>
<tr>
<td align="left">dgi_Latn (Northern Dagara)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">nmg_Latn (Kwasio)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">blo_Latn (Anii)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">dnj_Latn_LR (Dan)</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0265</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0265</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0265</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0265</td>
</tr>
<tr>
<td align="left">ach_Latn (Acoli)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">kqp_Latn (Kimré)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">dyu_Latn (Dyula)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">fuh_Latn (Fulfulde, Western Niger)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">sbd_Latn (Southern Samo)</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ozm_Latn (Koonzime)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">dur_Latn (Dii)</td>
<td align="left">Shaper didn't attach uni0327 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0327.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0327.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0327.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0327.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0327.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0327.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">tcd_Latn (Tafi)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Requires Small-cap: ƒ; both buffers returned florin=0+1023</td>
</tr>
<tr>
<td align="left">bfa_Latn (Bari)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">hag_Latn (Hanga)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mge_Latn (Mango)</td>
<td align="left">Shaper didn't attach uni0330 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0330</td>
</tr>
<tr>
<td align="left">xon_Latn (Konkomba)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">dip_Latn (Dinka, Northeastern)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mev_Latn (Mano)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">azo_Latn (Awing)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">lam_Latn (Lamba)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">tuq_Latn (Tedaga)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bfd_Latn (Bafut)</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">laj_Latn (Lango [Uganda])</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mas_Latn (Masai)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">nmz_Latn (Nawdm)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">kqs_Latn (Kissi, Northern)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">idu_Latn (Idoma)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">las_Latn (Lama (Togo))</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">pnz_Latn (Pana (Central African Republic))</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">biv_Latn (Birifor, Southern)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">nuv_Latn (Nuni, Northern)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bcw_Latn (Bana)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bzw_Latn (Basa)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">avn_Latn (Avatime)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Requires Small-cap: ƒ; both buffers returned florin=0+1023</td>
</tr>
<tr>
<td align="left">maw_Latn (Mampruli)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">fuc_Latn (Pulaar)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">dua_Latn (Duala)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">dts_Latn (Dogon, Toro So)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mwk_Latn (Kita Maninkakan)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">kmy_Latn (Koma)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">sba_Latn (Ngambay)</td>
<td align="left">Shaper didn't attach uni0330 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0259</td>
</tr>
<tr>
<td align="left">lok_Latn (Loko)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bsc_Latn (Bassari)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">gjn_Latn (Gonja)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">kzc_Latn (Bondoukou Kulango)</td>
<td align="left">Shaper didn't attach tildecomb to uniA7B7</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uniA7AE</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uniA7B6</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uniA7AE</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uniA7B7</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uniA7B6</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uniA7AE.sc</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uniA7B7.sc</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uniA7B6</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">nza_Latn (Tigon Mbembe)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ife_Latn (Ifè)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ses_Latn (Koyraboro Senni)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">knf_Latn (Mankanya)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">agq_Latn (Aghem)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mnk_Latn (Mandinka)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">kdh_Latn (Tem)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ny_Latn (Nyanja)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bas_Latn (Basaa)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mfv_Latn (Mandjak)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">fuf_Latn (Pular)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mgc_Latn (Morokodo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">yas_Latn (Nugunu)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">gmm_Latn (Gbaya-Mbodomo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bjt_Latn (Balanta-Ganja)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">taq_Latn (Tamasheq, Latin)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">dzg_Latn (Dazaga)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">xrb_Latn (Karaboro, Eastern)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ted_Latn (Krumen, Tepo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">yam_Latn (Yamba)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">nhb_Latn (Beng)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">anv_Latn (Denya)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">krs_Latn (Gbaya (Sudan))</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bbo_Latn (Northern Bobo Madaré)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">pbi_Latn (Parkwa)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">fmp_Latn (Fe’fe’)</td>
<td align="left">Shaper didn't attach uni0304 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ktj_Latn (Krumen, Plapo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">kus_Latn (Kusaal)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mwm_Latn (Sar)</td>
<td align="left">Shaper didn't attach uni0304 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0259</td>
</tr>
<tr>
<td align="left">gej_Latn (Gen)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">gng_Latn (Ngangam)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">muy_Latn (Muyang)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mua_Latn (Mundang)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">boz_Latn (Tiéyaxo Bozo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">nnw_Latn (Southern Nuni)</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">gur_Latn (Frafra)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">emk_Latn (Maninkakan, Eastern)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ken_Latn (Kenyang)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">loq_Latn (Lobala)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ddn_Latn (Dendi)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">naw_Latn (Nawuri)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mls_Latn (Masalit)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mbu_Latn (Mbula-Bwazza)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bzx_Latn (Bozo, Hainyaxo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">xwe_Latn (Gbe, Xwela)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">fub_Latn (Fulfulde, Adamawa)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">tvu_Latn (Tunen)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">keu_Latn (Akebu)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">xed_Latn (Hdi)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">byv_Latn (Medumba)</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mmu_Latn (Mmaala)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">lns_Latn (Lamnso’)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">tod_Latn (Toma)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">lgg_Latn (Lugbara)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0328.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0328.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni0259.sc</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0259.sc</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0259.sc</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni025B.sc</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni025B.sc</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni025B.sc</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni0254.sc</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0254.sc</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0254.sc</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">knp_Latn (Kwanja)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">myk_Latn (Mamara Senoufo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">gud_Latn (Dida, Yocoboué)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bsp_Latn (Baga Sitemu)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">god_Latn (Godié)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">dno_Latn (Ndrulo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">nhu_Latn (Noone)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">toq_Latn (Toposa)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">kib_Latn (Koalib)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Requires Small-cap: ɐ; both buffers returned uni2C6F=0+1414</td>
</tr>
<tr>
<td align="left">xsm_Latn (Kasem)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">cme_Latn (Cerma)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mdj_Latn (Mangbetu)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">cou_Latn (Wamey)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ade_Latn (Adele)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ahs_Latn (Ashe)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ee_Latn (Ewe)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Requires Small-cap: ƒ; both buffers returned florin=0+1023</td>
</tr>
<tr>
<td align="left">kvf_Latn (Kabalai)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">gde_Latn (Gude)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ndz_Latn (Ndogo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bax_Latn (Bamun, Latin)</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mcu_Latn (Mambila, Cameroon)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">lig_Latn (Ligbi)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">tpm_Latn (Tampulma)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">sok_Latn (Sokoro)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">kbp_Latn (Kabiyé)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mcp_Latn (Makaa)</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">xuo_Latn (Kuo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">srr_Latn (Serer)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bze_Latn (Jenaama Bozo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ig_Latn (Igbo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">gaa_Latn (Ga)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect uni01A9</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect uni01B7</td>
</tr>
<tr>
<td align="left">gov_Latn (Goo)</td>
<td align="left">Shaper didn't attach uni0302 to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0264</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0264</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0264</td>
</tr>
<tr>
<td align="left">nko_Latn (Nkonya)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">sef_Latn (Cebaara Senoufo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">jgo_Latn (Ngomba)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">nfr_Latn (Nafaanra)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mur_Latn (Murle)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ffm_Latn (Maasina Fulfulde)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">pug_Latn (Phuie)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">lun_Latn (Lunda)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">dje_Latn (Zarma)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ahl_Latn (Igo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ajg_Latn (Aja)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">saf_Latn (Safaliba)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ndv_Latn (Ndut)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">nyb_Latn (Nyangbo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Requires Small-cap: ƒ; both buffers returned florin=0+1023</td>
</tr>
<tr>
<td align="left">kkj_Latn (Kako)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bav_Latn (Vengo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">gna_Latn (Kaansa)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kfo_Latn (Koro)</td>
<td align="left">No exemplar glyphs were defined for language Koro</td>
</tr>
<tr>
<td align="left">cch_Latn (Atsam)</td>
<td align="left">No exemplar glyphs were defined for language Atsam</td>
</tr>
<tr>
<td align="left">amo_Latn (Amo)</td>
<td align="left">No exemplar glyphs were defined for language Amo</td>
</tr>
<tr>
<td align="left">mgy_Latn (Mbunga)</td>
<td align="left">No exemplar glyphs were defined for language Mbunga</td>
</tr>
<tr>
<td align="left">ggn_Latn (Eastern Gurung, Latin)</td>
<td align="left">No exemplar glyphs were defined for language Eastern Gurung, Latin</td>
</tr>
<tr>
<td align="left">hna_Latn (Mina)</td>
<td align="left">No exemplar glyphs were defined for language Mina</td>
</tr>
<tr>
<td align="left">syi_Latn (Seki)</td>
<td align="left">No exemplar glyphs were defined for language Seki</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Combined length of family and style must not exceed 32 characters. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 14 Cnd' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 323 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 14 Cnd' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 323 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 14 Cnd' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 325 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 14 Cnd' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 325 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 16 Cnd' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 330 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 16 Cnd' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 330 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 16 Cnd' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 332 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 16 Cnd' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 332 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 24 Cnd' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 337 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 24 Cnd' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 337 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 24 Cnd' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 339 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 24 Cnd' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 339 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 48 Cnd' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 344 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 48 Cnd' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 344 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 48 Cnd' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 346 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 48 Cnd' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 346 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 64 Cnd' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 351 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 64 Cnd' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 351 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 64 Cnd' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 353 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 64 Cnd' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 353 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 72 Cnd' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 358 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 72 Cnd' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 358 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 72 Cnd' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 360 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 72 Cnd' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 360 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExtBold 72 Cnd' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 362 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExtBold 72 Cnd' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 362 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 144 Cnd' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 365 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 144 Cnd' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 365 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 144 Cnd' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 366 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 144 Cnd' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 366 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 144 Cnd' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 367 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 144 Cnd' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 367 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 144 Cnd' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 369 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 144 Cnd' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 369 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 144 Cond' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 370 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 144 Cond' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 370 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 14 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 379 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 14 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 379 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 14 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 380 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 14 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 380 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 14 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 381 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 14 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 381 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 14 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 383 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 14 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 383 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 16 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 386 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 16 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 386 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 16 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 387 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 16 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 387 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 16 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 388 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 16 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 388 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 16 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 390 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 16 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 390 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 24 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 393 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 24 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 393 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 24 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 394 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 24 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 394 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 24 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 395 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 24 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 395 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 24 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 397 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 24 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 397 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 48 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 400 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 48 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 400 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 48 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 401 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 48 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 401 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 48 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 402 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 48 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 402 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 48 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 404 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 48 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 404 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 64 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 407 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 64 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 407 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 64 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 408 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 64 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 408 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 64 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 409 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 64 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 409 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 64 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 411 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 64 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 411 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 72 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 414 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 72 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 414 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 72 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 415 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 72 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 415 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 72 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 416 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 72 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 416 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 72 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 418 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 72 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 418 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 144 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 420 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 144 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 420 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 144 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 421 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 144 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 421 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 144 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 422 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 144 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 422 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 144 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 423 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 144 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 423 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 144 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 425 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 144 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 425 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 144 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 426 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 144 Wide' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 426 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check variable font instances <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.varfont.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>fvar instances are incorrect:</p>
<ul>
<li>Add missing instances</li>
<li>Delete additional instances</li>
</ul>
<table>
<thead>
<tr>
<th align="left">Name</th>
<th align="left">current</th>
<th align="left">expected</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Black 72</td>
<td align="left">wght=900.0, wdth=100.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold Wide</td>
<td align="left">wght=600.0, wdth=112.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 48</td>
<td align="left">wght=800.0, wdth=100.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 14</td>
<td align="left">wght=800.0, wdth=100.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 24</td>
<td align="left">wght=600.0, wdth=100.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 48</td>
<td align="left">wght=900.0, wdth=100.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 24 Wide</td>
<td align="left">wght=300.0, wdth=112.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 72 Wide</td>
<td align="left">wght=500.0, wdth=112.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 16</td>
<td align="left">wght=900.0, wdth=100.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 24</td>
<td align="left">wght=700.0, wdth=100.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 64</td>
<td align="left">wght=300.0, wdth=100.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 72 Cnd</td>
<td align="left">wght=300.0, wdth=87.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 48 Cnd</td>
<td align="left">wght=600.0, wdth=87.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 64 Cnd</td>
<td align="left">wght=700.0, wdth=87.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 144 Cnd</td>
<td align="left">wght=800.0, wdth=87.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular Cnd</td>
<td align="left">wght=400.0, wdth=87.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 24 Wide</td>
<td align="left">wght=900.0, wdth=112.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 24 Cnd</td>
<td align="left">wght=700.0, wdth=87.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 48</td>
<td align="left">wght=600.0, wdth=100.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 24 Wide</td>
<td align="left">wght=800.0, wdth=112.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 144</td>
<td align="left">wght=500.0, wdth=100.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 144 Cnd</td>
<td align="left">wght=400.0, wdth=87.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 24 Wide</td>
<td align="left">wght=600.0, wdth=112.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 14 Wide</td>
<td align="left">wght=700.0, wdth=112.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 72</td>
<td align="left">wght=600.0, wdth=100.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 64 Cnd</td>
<td align="left">wght=900.0, wdth=87.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 64</td>
<td align="left">wght=900.0, wdth=100.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 64 Cnd</td>
<td align="left">wght=800.0, wdth=87.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 14 Cnd</td>
<td align="left">wght=400.0, wdth=87.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 144 Wide</td>
<td align="left">wght=800.0, wdth=112.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 72 Wide</td>
<td align="left">wght=300.0, wdth=112.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 14</td>
<td align="left">wght=900.0, wdth=100.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 48</td>
<td align="left">wght=300.0, wdth=100.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 16 Cnd</td>
<td align="left">wght=900.0, wdth=87.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 14 Wide</td>
<td align="left">wght=500.0, wdth=112.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 16 Wide</td>
<td align="left">wght=300.0, wdth=112.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 144</td>
<td align="left">wght=700.0, wdth=100.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 144 Cnd</td>
<td align="left">wght=700.0, wdth=87.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 64 Wide</td>
<td align="left">wght=500.0, wdth=112.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 16</td>
<td align="left">wght=600.0, wdth=100.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 16 Wide</td>
<td align="left">wght=700.0, wdth=112.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 72 Cnd</td>
<td align="left">wght=900.0, wdth=87.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 14 Cnd</td>
<td align="left">wght=600.0, wdth=87.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 48 Cnd</td>
<td align="left">wght=400.0, wdth=87.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 48 Cnd</td>
<td align="left">wght=300.0, wdth=87.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 64 Cnd</td>
<td align="left">wght=400.0, wdth=87.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black Cnd</td>
<td align="left">wght=900.0, wdth=87.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 16 Wide</td>
<td align="left">wght=900.0, wdth=112.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 24 Wide</td>
<td align="left">wght=400.0, wdth=112.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold Wide</td>
<td align="left">wght=800.0, wdth=112.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 24 Cnd</td>
<td align="left">wght=500.0, wdth=87.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 64 Wide</td>
<td align="left">wght=600.0, wdth=112.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 64</td>
<td align="left">wght=700.0, wdth=100.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 48 Wide</td>
<td align="left">wght=700.0, wdth=112.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 14 Wide</td>
<td align="left">wght=400.0, wdth=112.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 72 Wide</td>
<td align="left">wght=400.0, wdth=112.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 144 Wide</td>
<td align="left">wght=300.0, wdth=112.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular Wide</td>
<td align="left">wght=400.0, wdth=112.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 14</td>
<td align="left">wght=500.0, wdth=100.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 72 Wide</td>
<td align="left">wght=700.0, wdth=112.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 144 Wide</td>
<td align="left">wght=500.0, wdth=112.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 64 Cnd</td>
<td align="left">wght=500.0, wdth=87.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 144 Wide</td>
<td align="left">wght=600.0, wdth=112.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 24</td>
<td align="left">wght=500.0, wdth=100.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 48 Cnd</td>
<td align="left">wght=800.0, wdth=87.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 48</td>
<td align="left">wght=400.0, wdth=100.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 14 Cnd</td>
<td align="left">wght=800.0, wdth=87.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 14 Wide</td>
<td align="left">wght=900.0, wdth=112.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 24 Cnd</td>
<td align="left">wght=800.0, wdth=87.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 14</td>
<td align="left">wght=600.0, wdth=100.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 14</td>
<td align="left">wght=700.0, wdth=100.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 16</td>
<td align="left">wght=700.0, wdth=100.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 48 Cnd</td>
<td align="left">wght=500.0, wdth=87.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 64 Wide</td>
<td align="left">wght=700.0, wdth=112.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 14 Cnd</td>
<td align="left">wght=900.0, wdth=87.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 144</td>
<td align="left">wght=400.0, wdth=100.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 14</td>
<td align="left">wght=400.0, wdth=100.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 16 Cnd</td>
<td align="left">wght=700.0, wdth=87.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 144 Wide</td>
<td align="left">wght=700.0, wdth=112.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 16</td>
<td align="left">wght=400.0, wdth=100.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 48 Wide</td>
<td align="left">wght=800.0, wdth=112.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 64 Cnd</td>
<td align="left">wght=600.0, wdth=87.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 144 Wide</td>
<td align="left">wght=900.0, wdth=112.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 48</td>
<td align="left">wght=500.0, wdth=100.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 16</td>
<td align="left">wght=500.0, wdth=100.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 14 Wide</td>
<td align="left">wght=300.0, wdth=112.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 24 Wide</td>
<td align="left">wght=700.0, wdth=112.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 64</td>
<td align="left">wght=400.0, wdth=100.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 48 Wide</td>
<td align="left">wght=300.0, wdth=112.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 72 Cnd</td>
<td align="left">wght=400.0, wdth=87.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 14 Wide</td>
<td align="left">wght=600.0, wdth=112.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 144</td>
<td align="left">wght=900.0, wdth=100.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 24</td>
<td align="left">wght=900.0, wdth=100.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 16 Wide</td>
<td align="left">wght=600.0, wdth=112.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 16 Wide</td>
<td align="left">wght=800.0, wdth=112.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium Wide</td>
<td align="left">wght=500.0, wdth=112.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 14 Cnd</td>
<td align="left">wght=500.0, wdth=87.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 144</td>
<td align="left">wght=600.0, wdth=100.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 64 Wide</td>
<td align="left">wght=400.0, wdth=112.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 144 Cnd</td>
<td align="left">wght=600.0, wdth=87.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold Wide</td>
<td align="left">wght=700.0, wdth=112.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 14 Wide</td>
<td align="left">wght=800.0, wdth=112.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold Cnd</td>
<td align="left">wght=700.0, wdth=87.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 64 Wide</td>
<td align="left">wght=900.0, wdth=112.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold</td>
<td align="left">wght=800.0, wdth=100.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 48</td>
<td align="left">wght=700.0, wdth=100.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 16 Cnd</td>
<td align="left">wght=600.0, wdth=87.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 16 Cnd</td>
<td align="left">wght=500.0, wdth=87.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 72 Cnd</td>
<td align="left">wght=500.0, wdth=87.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 72 Cnd</td>
<td align="left">wght=700.0, wdth=87.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 72 Wide</td>
<td align="left">wght=600.0, wdth=112.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 16</td>
<td align="left">wght=800.0, wdth=100.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 16 Wide</td>
<td align="left">wght=400.0, wdth=112.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 72</td>
<td align="left">wght=800.0, wdth=100.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black Wide</td>
<td align="left">wght=900.0, wdth=112.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 72 Wide</td>
<td align="left">wght=800.0, wdth=112.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 144 Wide</td>
<td align="left">wght=400.0, wdth=112.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 48 Wide</td>
<td align="left">wght=500.0, wdth=112.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 24 Cnd</td>
<td align="left">wght=600.0, wdth=87.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 48 Wide</td>
<td align="left">wght=900.0, wdth=112.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 72 Cnd</td>
<td align="left">wght=600.0, wdth=87.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 24 Wide</td>
<td align="left">wght=500.0, wdth=112.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 24 Cnd</td>
<td align="left">wght=300.0, wdth=87.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 64 Wide</td>
<td align="left">wght=800.0, wdth=112.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 64 Wide</td>
<td align="left">wght=300.0, wdth=112.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold Cnd</td>
<td align="left">wght=800.0, wdth=87.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light Wide</td>
<td align="left">wght=300.0, wdth=112.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 64 Cnd</td>
<td align="left">wght=300.0, wdth=87.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 72</td>
<td align="left">wght=400.0, wdth=100.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 14 Cnd</td>
<td align="left">wght=700.0, wdth=87.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 48 Wide</td>
<td align="left">wght=400.0, wdth=112.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 16 Cnd</td>
<td align="left">wght=400.0, wdth=87.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 144</td>
<td align="left">wght=300.0, wdth=100.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 144 Cond</td>
<td align="left">wght=900.0, wdth=87.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 72</td>
<td align="left">wght=500.0, wdth=100.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 144 Cnd</td>
<td align="left">wght=300.0, wdth=87.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 64</td>
<td align="left">wght=600.0, wdth=100.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 24</td>
<td align="left">wght=300.0, wdth=100.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 24</td>
<td align="left">wght=800.0, wdth=100.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 64</td>
<td align="left">wght=800.0, wdth=100.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 24 Cnd</td>
<td align="left">wght=900.0, wdth=87.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 144 Cnd</td>
<td align="left">wght=500.0, wdth=87.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 48 Cnd</td>
<td align="left">wght=900.0, wdth=87.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold Cnd</td>
<td align="left">wght=600.0, wdth=87.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 14</td>
<td align="left">wght=300.0, wdth=100.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 72</td>
<td align="left">wght=300.0, wdth=100.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 16</td>
<td align="left">wght=300.0, wdth=100.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium Cnd</td>
<td align="left">wght=500.0, wdth=87.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 14 Cnd</td>
<td align="left">wght=300.0, wdth=87.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 16 Cnd</td>
<td align="left">wght=800.0, wdth=87.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 16 Wide</td>
<td align="left">wght=500.0, wdth=112.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 16 Cnd</td>
<td align="left">wght=300.0, wdth=87.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExtBold 72 Cnd</td>
<td align="left">wght=800.0, wdth=87.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 72 Wide</td>
<td align="left">wght=900.0, wdth=112.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 64</td>
<td align="left">wght=500.0, wdth=100.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light Cnd</td>
<td align="left">wght=300.0, wdth=87.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 24</td>
<td align="left">wght=400.0, wdth=100.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 144</td>
<td align="left">wght=800.0, wdth=100.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 24 Cnd</td>
<td align="left">wght=400.0, wdth=87.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 72</td>
<td align="left">wght=700.0, wdth=100.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 48 Wide</td>
<td align="left">wght=600.0, wdth=112.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 48 Cnd</td>
<td align="left">wght=700.0, wdth=87.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light</td>
<td align="left">wght=300.0, wdth=100.0, opsz=12.0</td>
<td align="left">wght=300.0, wdth=100.0, opsz=12.0</td>
</tr>
<tr>
<td align="left">Regular</td>
<td align="left">wght=400.0, wdth=100.0, opsz=12.0</td>
<td align="left">wght=400.0, wdth=100.0, opsz=12.0</td>
</tr>
<tr>
<td align="left">Medium</td>
<td align="left">wght=500.0, wdth=100.0, opsz=12.0</td>
<td align="left">wght=500.0, wdth=100.0, opsz=12.0</td>
</tr>
<tr>
<td align="left">SemiBold</td>
<td align="left">wght=600.0, wdth=100.0, opsz=12.0</td>
<td align="left">wght=600.0, wdth=100.0, opsz=12.0</td>
</tr>
<tr>
<td align="left">Bold</td>
<td align="left">wght=700.0, wdth=100.0, opsz=12.0</td>
<td align="left">wght=700.0, wdth=100.0, opsz=12.0</td>
</tr>
<tr>
<td align="left">ExtraBold</td>
<td align="left">N/A</td>
<td align="left">wght=800.0, wdth=100.0, opsz=12.0</td>
</tr>
<tr>
<td align="left">Black</td>
<td align="left">wght=900.0, wdth=100.0, opsz=12.0</td>
<td align="left">wght=900.0, wdth=100.0, opsz=12.0</td>
</tr>
</tbody>
</table>
 [code: bad-fvar-instances]



</div>
</details>

<details>
    <summary>💥 <b>ERROR</b> Validate STAT particle names and values match the fallback names in GFAxisRegistry. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.axisregistry.html#"></a></summary>
    <div>







* 💥 **ERROR** <p>Failed with AttributeError: 'NoneType' object has no attribute 'toUnicode'</p>
<pre><code>  File &quot;/home/runner/work/Merriweather4/Merriweather4/venv-test/lib/python3.10/site-packages/fontbakery/checkrunner.py&quot;, line 213, in _run_check
    subresults = list(subresults)
  File &quot;/home/runner/work/Merriweather4/Merriweather4/venv-test/lib/python3.10/site-packages/fontbakery/checks/googlefonts/axisregistry.py&quot;, line 191, in com_google_fonts_check_STAT_gf_axisregistry_names
    name = normalize_name(name_entry.toUnicode())

</code></pre>
 [code: failed-check]



</div>
</details>
</div>
</details>

<details><summary>[26] Merriweather-Italic[opsz,wdth,wght].ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Check mark characters are in GDEF mark glyph class. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following mark characters could be in the GDEF mark glyph class:
uni0488 (U+0488) and uni0489 (U+0489)</p>
 [code: mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Interpolation issues were found in the font:</p>
<pre><code>- Contour 0 point 25 has a kink between location wght=300,wdth=100,opsz=12 and location wght=900,wdth=87,opsz=144

- Contour 0 point 70 has a kink between location wght=900,wdth=87,opsz=144 and location wght=900,wdth=112,opsz=144

- Contour order differs in glyph 'uni030B.case': [0, 1] in wght=900,wdth=112,opsz=144, [1, 0] in wght=300,wdth=100,opsz=144.

- Contour order differs in glyph 'uni030B.case': [0, 1] in wght=300,wdth=100,opsz=144, [1, 0] in wght=300,wdth=87,opsz=12.

- Contour order differs in glyph 'uni030B.case': [0, 1] in wght=300,wdth=112,opsz=12, [1, 0] in wght=300,wdth=87,opsz=144.

- Contour 0 point 98 has a kink between location wght=900,wdth=112,opsz=144 and location wght=300,wdth=100,opsz=144

- Contour 0 point 29 has a kink between location wght=900,wdth=100,opsz=144 and location wght=900,wdth=87,opsz=12

- Contour 0 point 29 has a kink between location wght=900,wdth=112,opsz=144 and location wght=300,wdth=100,opsz=144

- Contour 0 point 14 has a kink between location wght=900,wdth=112,opsz=12 and location wght=300,wdth=100,opsz=12

- Contour 0 point 14 has a kink between location wght=300,wdth=100,opsz=12 and location wght=900,wdth=87,opsz=144

- Contour 0 point 53 has a kink between location wght=900,wdth=100,opsz=144 and location wght=900,wdth=87,opsz=12

- Contour 0 point 53 has a kink between location wght=300,wdth=100,opsz=144 and location wght=300,wdth=87,opsz=12
</code></pre>
 [code: interpolation-issues]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 1220 among a set of 2 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 1226:
less</p>
<p>Width = 1138:
notequal, equal</p>
<p>Width = 1225:
greater</p>
<p>Width = 1259:
lessequal, logicalnot</p>
<p>Width = 1262:
uni2266, multiply</p>
<p>Width = 1260:
divide</p>
<p>Width = 1184:
minus</p>
<p>Width = 1276:
approxequal</p>
<p>Width = 1264:
greaterequal</p>
<p>Width = 1270:
uni2267</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking with ots-sanitize. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>ots-sanitize passed this file, however warnings were printed:</p>
<p>ERROR: STAT: Invalid nameID: 24
ERROR: Table discarded</p>
 [code: ots-sanitize-warn]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- I.uc

- IJ_acutecomb

- acute.narrow

- caron.alt

- circumflex.narrow

- dafrican.sc

- dieresis.narrow

- dieresiscombcy.case

- dotlessi_ogonek

- f_f.sc

- f_f_i.sc

- f_f_l.sc

- grave.narrow

- i.dot

- ij_acutecomb

- iringbelow

- iringbelow.dotless

- j.latnNLD

- macron.narrow

- ntilde.sc.001

- ringacute.case

- tilde.narrow

- tildecomb_acutecomb

- uni013B.latnMAH

- uni0145.latnMAH

- uni01A9.localGAD

- uni01B7.localGAD

- uni028B.loclTOD0.ss04

- uni03000304

- uni03000358

- uni03010304

- uni03010307

- uni03010358

- uni03020358

- uni03030304

- uni03030308

- uni03040300

- uni03040301

- uni03040308

- uni03040358

- uni0306.narrow

- uni03060358

- uni03070304

- uni03080300

- uni03080301

- uni03080304

- uni0308030C

- uni030C0307

- uni030D0358

- uni0438.l.sc

- uni0442.locl

- uni2071.dotless

- uniA64D.sc
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: i̯̇ i̯̊ i̯̋ i̯̍ i̯̐ i̯̒ i̯̓ i̯᷄ i̯᷅ i̯᷆ i̯᷇ i̯᷈ i̯᷉ i̯ꚞ i̴̇ i̴̊ i̴̋ i̴̍ i̴̐ i̴̒</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Ijo, Southeast (Latn, 2,471,000 speakers), Navajo (Latn, 166,319 speakers), Lithuanian (Latn, 2,357,094 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ekpeye (Latn, 226,000 speakers), Yala (Latn, 200,000 speakers), Nateni (Latn, 100,000 speakers), Ebira (Latn, 2,200,000 speakers), Cicipu (Latn, 44,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Bete-Bendi (Latn, 100,000 speakers), Dutch (Latn, 31,709,104 speakers), Ma’di (Latn, 584,000 speakers), Zapotec (Latn, 490,000 speakers), Nzakara (Latn, 50,000 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Lugbara (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Kom (Latn, 360,685 speakers), Makaa (Latn, 221,000 speakers), Mango (Latn, 77,000 speakers), Mundani (Latn, 34,000 speakers), Dii (Latn, 71,000 speakers), Bafut (Latn, 158,146 speakers), Aghem (Latn, 38,843 speakers), Fur (Latn, 1,230,163 speakers), Sar (Latn, 500,000 speakers), Avokaya (Latn, 100,000 speakers), Dan (Latn, 1,099,244 speakers), South Central Banda (Latn, 244,000 speakers), Southern Kisi (Latn, 360,000 speakers), Gulay (Latn, 250,478 speakers), Igbo (Latn, 27,823,640 speakers), Mfumte (Latn, 79,000 speakers), Ejagham (Latn, 120,000 speakers), Basaa (Latn, 332,940 speakers), Kpelle, Guinea (Latn, 622,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02B0 MODIFIER LETTER SMALL H: not included in any glyphset definition</li>
<li>U+02B7 MODIFIER LETTER SMALL W: not included in any glyphset definition</li>
<li>U+02B8 MODIFIER LETTER SMALL Y: not included in any glyphset definition</li>
<li>U+02B9 MODIFIER LETTER PRIME: not included in any glyphset definition</li>
<li>U+02BA MODIFIER LETTER DOUBLE PRIME: not included in any glyphset definition</li>
<li>U+02BD MODIFIER LETTER REVERSED COMMA: not included in any glyphset definition</li>
<li>U+02BE MODIFIER LETTER RIGHT HALF RING: not included in any glyphset definition</li>
<li>U+02BF MODIFIER LETTER LEFT HALF RING: not included in any glyphset definition</li>
<li>U+02C0 MODIFIER LETTER GLOTTAL STOP: not included in any glyphset definition</li>
<li>U+02C1 MODIFIER LETTER REVERSED GLOTTAL STOP: not included in any glyphset definition</li>
<li>U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh</li>
<li>U+02C8 MODIFIER LETTER VERTICAL LINE: not included in any glyphset definition</li>
<li>U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition</li>
<li>U+02CA MODIFIER LETTER ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+02CB MODIFIER LETTER GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+02CC MODIFIER LETTER LOW VERTICAL LINE: not included in any glyphset definition</li>
<li>U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition</li>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+02EC MODIFIER LETTER VOICING: not included in any glyphset definition</li>
<li>U+02EE MODIFIER LETTER DOUBLE APOSTROPHE: not included in any glyphset definition</li>
<li>U+02FB MODIFIER LETTER BEGIN LOW TONE: not included in any glyphset definition</li>
<li>U+02FC MODIFIER LETTER END LOW TONE: not included in any glyphset definition</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, coptic, cherokee, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: coptic, math, tifinagh, syriac, old-permic, canadian-aboriginal, malayalam, tai-le</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+030D COMBINING VERTICAL LINE ABOVE: not included in any glyphset definition</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0310 COMBINING CANDRABINDU: not included in any glyphset definition</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding coptic</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition</li>
<li>U+0313 COMBINING COMMA ABOVE: try adding old-permic</li>
<li>U+0315 COMBINING COMMA ABOVE RIGHT: not included in any glyphset definition</li>
<li>U+031B COMBINING HORN: not included in any glyphset definition</li>
<li>U+0320 COMBINING MINUS SIGN BELOW: try adding syriac</li>
<li>U+0324 COMBINING DIAERESIS BELOW: try adding one of: syriac, cherokee</li>
<li>U+0325 COMBINING RING BELOW: try adding syriac</li>
<li>U+0326 COMBINING COMMA BELOW: not included in any glyphset definition</li>
<li>U+0327 COMBINING CEDILLA: not included in any glyphset definition</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding syriac</li>
<li>U+032E COMBINING BREVE BELOW: try adding syriac</li>
<li>U+032F COMBINING INVERTED BREVE BELOW: not included in any glyphset definition</li>
<li>U+0330 COMBINING TILDE BELOW: try adding one of: syriac, math, cherokee</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: cherokee, tifinagh, syriac, gothic, caucasian-albanian</li>
<li>U+0332 COMBINING LOW LINE: not included in any glyphset definition</li>
<li>U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition</li>
<li>U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+0336 COMBINING LONG STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+0337 COMBINING SHORT SOLIDUS OVERLAY: not included in any glyphset definition</li>
<li>U+0338 COMBINING LONG SOLIDUS OVERLAY: not included in any glyphset definition</li>
<li>U+0358 COMBINING DOT ABOVE RIGHT: try adding osage</li>
<li>U+035C COMBINING DOUBLE BREVE BELOW: not included in any glyphset definition</li>
<li>U+035D COMBINING DOUBLE BREVE: not included in any glyphset definition</li>
<li>U+035F COMBINING DOUBLE MACRON BELOW: not included in any glyphset definition</li>
<li>U+0361 COMBINING DOUBLE INVERTED BREVE: try adding coptic</li>
<li>U+0362 COMBINING DOUBLE RIGHTWARDS ARROW BELOW: not included in any glyphset definition</li>
<li>U+058F ARMENIAN DRAM SIGN: try adding armenian</li>
<li>U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai</li>
<li>U+1D05 LATIN LETTER SMALL CAPITAL D: not included in any glyphset definition</li>
<li>U+1D3A MODIFIER LETTER CAPITAL N: not included in any glyphset definition</li>
<li>U+1D43 MODIFIER LETTER SMALL A: not included in any glyphset definition</li>
<li>U+1D49 MODIFIER LETTER SMALL E: not included in any glyphset definition</li>
<li>U+1D4B MODIFIER LETTER SMALL OPEN E: not included in any glyphset definition</li>
<li>U+1D4D MODIFIER LETTER SMALL G: not included in any glyphset definition</li>
<li>U+1D52 MODIFIER LETTER SMALL O: not included in any glyphset definition</li>
<li>U+1D53 MODIFIER LETTER SMALL OPEN O: not included in any glyphset definition</li>
<li>U+1D58 MODIFIER LETTER SMALL U: not included in any glyphset definition</li>
<li>U+1D5B MODIFIER LETTER SMALL V: not included in any glyphset definition</li>
<li>U+1D7B LATIN SMALL CAPITAL LETTER I WITH STROKE: not included in any glyphset definition</li>
<li>U+1D7D LATIN SMALL LETTER P WITH STROKE: not included in any glyphset definition</li>
<li>U+1D7E LATIN SMALL CAPITAL LETTER U WITH STROKE: not included in any glyphset definition</li>
<li>U+1D91 LATIN SMALL LETTER D WITH HOOK AND TAIL: not included in any glyphset definition</li>
<li>U+1DA4 MODIFIER LETTER SMALL I WITH STROKE: not included in any glyphset definition</li>
<li>U+1DB6 MODIFIER LETTER SMALL U BAR: not included in any glyphset definition</li>
<li>U+1DBB MODIFIER LETTER SMALL Z: not included in any glyphset definition</li>
<li>U+1DBF MODIFIER LETTER SMALL THETA: not included in any glyphset definition</li>
<li>U+1DC4 COMBINING MACRON-ACUTE: not included in any glyphset definition</li>
<li>U+1DC5 COMBINING GRAVE-MACRON: not included in any glyphset definition</li>
<li>U+1DC6 COMBINING MACRON-GRAVE: not included in any glyphset definition</li>
<li>U+1DC7 COMBINING ACUTE-MACRON: not included in any glyphset definition</li>
<li>U+1DC8 COMBINING GRAVE-ACUTE-GRAVE: not included in any glyphset definition</li>
<li>U+1DC9 COMBINING ACUTE-GRAVE-ACUTE: not included in any glyphset definition</li>
<li>U+1DCA COMBINING LATIN SMALL LETTER R BELOW: not included in any glyphset definition</li>
<li>U+2000 EN QUAD: not included in any glyphset definition</li>
<li>U+2001 EM QUAD: not included in any glyphset definition</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: not included in any glyphset definition</li>
<li>U+2005 FOUR-PER-EM SPACE: not included in any glyphset definition</li>
<li>U+2006 SIX-PER-EM SPACE: not included in any glyphset definition</li>
<li>U+2007 FIGURE SPACE: not included in any glyphset definition</li>
<li>U+2008 PUNCTUATION SPACE: not included in any glyphset definition</li>
<li>U+200A HAIR SPACE: not included in any glyphset definition</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: nko, myanmar, tai-tham, rejang, kaithi, grantha, sundanese, kannada, manichaean, hanifi-rohingya, bhaiksuki, javanese, meetei-mayek, batak, modi, oriya, tamil, zanabazar-square, chakma, lao, phags-pa, gunjala-gondi, sogdian, syloti-nagri, tai-viet, masaram-gondi, buhid, sinhala, tibetan, siddham, tagbanwa, takri, khojki, limbu, new-tai-lue, lepcha, pahawh-hmong, bengali, devanagari, syriac, thai, mongolian, dogra, tagalog, tai-le, hatran, tifinagh, hanunoo, gujarati, duployan, warang-citi, mahajani, arabic, cham, kayah-li, newa, telugu, khmer, thaana, tirhuta, khudawadi, sharada, mandaic, psalter-pahlavi, brahmi, hebrew, yi, kharoshthi, saurashtra, malayalam, gurmukhi, balinese, avestan, buginese</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: nko, myanmar, tai-tham, rejang, kaithi, grantha, sundanese, kannada, manichaean, hanifi-rohingya, bhaiksuki, javanese, meetei-mayek, batak, modi, oriya, tamil, zanabazar-square, chakma, lao, phags-pa, gunjala-gondi, sogdian, syloti-nagri, tai-viet, masaram-gondi, buhid, sinhala, tibetan, siddham, tagbanwa, takri, khojki, limbu, new-tai-lue, lepcha, pahawh-hmong, bengali, devanagari, syriac, thai, mongolian, dogra, tagalog, tai-le, tifinagh, hanunoo, gujarati, duployan, warang-citi, mahajani, old-hungarian, arabic, cham, kayah-li, newa, telugu, khmer, thaana, tirhuta, khudawadi, sharada, mandaic, psalter-pahlavi, brahmi, hebrew, yi, kharoshthi, saurashtra, malayalam, gurmukhi, balinese, avestan, buginese</li>
<li>U+2010 HYPHEN: try adding one of: armenian, coptic, arabic, cham, kayah-li, lisu, syloti-nagri, kaithi, sundanese, sora-sompeng, yi, hebrew, kharoshthi</li>
<li>U+2011 NON-BREAKING HYPHEN: try adding one of: yi, syloti-nagri, arabic</li>
<li>U+2012 FIGURE DASH: not included in any glyphset definition</li>
<li>U+2015 HORIZONTAL BAR: try adding adlam</li>
<li>U+2016 DOUBLE VERTICAL LINE: not included in any glyphset definition</li>
<li>U+201B SINGLE HIGH-REVERSED-9 QUOTATION MARK: try adding adlam</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2023 TRIANGULAR BULLET: not included in any glyphset definition</li>
<li>U+2027 HYPHENATION POINT: not included in any glyphset definition</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, mongolian</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+2034 TRIPLE PRIME: try adding math</li>
<li>U+203C DOUBLE EXCLAMATION MARK: not included in any glyphset definition</li>
<li>U+2042 ASTERISM: not included in any glyphset definition</li>
<li>U+204A TIRONIAN SIGN ET: not included in any glyphset definition</li>
<li>U+2052 COMMERCIAL MINUS SIGN: not included in any glyphset definition</li>
<li>U+2070 SUPERSCRIPT ZERO: not included in any glyphset definition</li>
<li>U+2071 SUPERSCRIPT LATIN SMALL LETTER I: not included in any glyphset definition</li>
<li>U+2075 SUPERSCRIPT FIVE: not included in any glyphset definition</li>
<li>U+2076 SUPERSCRIPT SIX: not included in any glyphset definition</li>
<li>U+2077 SUPERSCRIPT SEVEN: not included in any glyphset definition</li>
<li>U+2078 SUPERSCRIPT EIGHT: not included in any glyphset definition</li>
<li>U+2079 SUPERSCRIPT NINE: not included in any glyphset definition</li>
<li>U+207F SUPERSCRIPT LATIN SMALL LETTER N: not included in any glyphset definition</li>
<li>U+2080 SUBSCRIPT ZERO: not included in any glyphset definition</li>
<li>U+2081 SUBSCRIPT ONE: not included in any glyphset definition</li>
<li>U+2082 SUBSCRIPT TWO: not included in any glyphset definition</li>
<li>U+2083 SUBSCRIPT THREE: not included in any glyphset definition</li>
<li>U+2084 SUBSCRIPT FOUR: not included in any glyphset definition</li>
<li>U+2085 SUBSCRIPT FIVE: not included in any glyphset definition</li>
<li>U+2086 SUBSCRIPT SIX: not included in any glyphset definition</li>
<li>U+2087 SUBSCRIPT SEVEN: not included in any glyphset definition</li>
<li>U+2088 SUBSCRIPT EIGHT: not included in any glyphset definition</li>
<li>U+2089 SUBSCRIPT NINE: not included in any glyphset definition</li>
<li>U+2100 ACCOUNT OF: not included in any glyphset definition</li>
<li>U+2101 ADDRESSED TO THE SUBJECT: not included in any glyphset definition</li>
<li>U+2105 CARE OF: not included in any glyphset definition</li>
<li>U+2106 CADA UNA: not included in any glyphset definition</li>
<li>U+2117 SOUND RECORDING COPYRIGHT: not included in any glyphset definition</li>
<li>U+2126 OHM SIGN: not included in any glyphset definition</li>
<li>U+212E ESTIMATED SYMBOL: not included in any glyphset definition</li>
<li>U+2144 TURNED SANS-SERIF CAPITAL Y: not included in any glyphset definition</li>
<li>U+2150 VULGAR FRACTION ONE SEVENTH: not included in any glyphset definition</li>
<li>U+2151 VULGAR FRACTION ONE NINTH: not included in any glyphset definition</li>
<li>U+2152 VULGAR FRACTION ONE TENTH: not included in any glyphset definition</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: not included in any glyphset definition</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: not included in any glyphset definition</li>
<li>U+2155 VULGAR FRACTION ONE FIFTH: not included in any glyphset definition</li>
<li>U+2156 VULGAR FRACTION TWO FIFTHS: not included in any glyphset definition</li>
<li>U+2158 VULGAR FRACTION FOUR FIFTHS: not included in any glyphset definition</li>
<li>U+2159 VULGAR FRACTION ONE SIXTH: not included in any glyphset definition</li>
<li>U+215A VULGAR FRACTION FIVE SIXTHS: not included in any glyphset definition</li>
<li>U+215B VULGAR FRACTION ONE EIGHTH: not included in any glyphset definition</li>
<li>U+215C VULGAR FRACTION THREE EIGHTHS: not included in any glyphset definition</li>
<li>U+215D VULGAR FRACTION FIVE EIGHTHS: not included in any glyphset definition</li>
<li>U+215E VULGAR FRACTION SEVEN EIGHTHS: not included in any glyphset definition</li>
<li>U+2183 ROMAN NUMERAL REVERSED ONE HUNDRED: try adding symbols</li>
<li>U+2184 LATIN SMALL LETTER REVERSED C: not included in any glyphset definition</li>
<li>U+2190 LEFTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2194 LEFT RIGHT ARROW: try adding one of: symbols, math</li>
<li>U+2195 UP DOWN ARROW: try adding one of: symbols, math</li>
<li>U+2196 NORTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+2197 NORTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2198 SOUTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2199 SOUTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2205 EMPTY SET: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+2219 BULLET OPERATOR: try adding one of: yi, tai-tham, symbols, math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2236 RATIO: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+2266 LESS-THAN OVER EQUAL TO: try adding math</li>
<li>U+2267 GREATER-THAN OVER EQUAL TO: try adding math</li>
<li>U+2317 VIEWDATA SQUARE: try adding symbols</li>
<li>U+24B6 CIRCLED LATIN CAPITAL LETTER A: try adding symbols</li>
<li>U+24D0 CIRCLED LATIN SMALL LETTER A: try adding symbols</li>
<li>U+25A0 BLACK SQUARE: try adding symbols</li>
<li>U+25A1 WHITE SQUARE: try adding symbols</li>
<li>U+25AA BLACK SMALL SQUARE: try adding symbols</li>
<li>U+25AB WHITE SMALL SQUARE: try adding symbols</li>
<li>U+25B2 BLACK UP-POINTING TRIANGLE: try adding symbols</li>
<li>U+25B3 WHITE UP-POINTING TRIANGLE: try adding one of: symbols, math</li>
<li>U+25B4 BLACK UP-POINTING SMALL TRIANGLE: try adding symbols</li>
<li>U+25B5 WHITE UP-POINTING SMALL TRIANGLE: try adding symbols</li>
<li>U+25B6 BLACK RIGHT-POINTING TRIANGLE: try adding symbols</li>
<li>U+25B7 WHITE RIGHT-POINTING TRIANGLE: try adding one of: symbols, math</li>
<li>U+25B8 BLACK RIGHT-POINTING SMALL TRIANGLE: try adding symbols</li>
<li>U+25B9 WHITE RIGHT-POINTING SMALL TRIANGLE: try adding symbols</li>
<li>U+25BC BLACK DOWN-POINTING TRIANGLE: try adding symbols</li>
<li>U+25BD WHITE DOWN-POINTING TRIANGLE: try adding one of: symbols, math</li>
<li>U+25BE BLACK DOWN-POINTING SMALL TRIANGLE: try adding symbols</li>
<li>U+25BF WHITE DOWN-POINTING SMALL TRIANGLE: try adding symbols</li>
<li>U+25C0 BLACK LEFT-POINTING TRIANGLE: try adding symbols</li>
<li>U+25C1 WHITE LEFT-POINTING TRIANGLE: try adding one of: symbols, math</li>
<li>U+25C2 BLACK LEFT-POINTING SMALL TRIANGLE: try adding symbols</li>
<li>U+25C3 WHITE LEFT-POINTING SMALL TRIANGLE: try adding symbols</li>
<li>U+25C6 BLACK DIAMOND: try adding symbols</li>
<li>U+25C7 WHITE DIAMOND: try adding symbols</li>
<li>U+25C9 FISHEYE: try adding symbols</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+25CB WHITE CIRCLE: try adding symbols</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: tamil, kaithi, modi, manichaean, hanifi-rohingya, meetei-mayek, batak, zanabazar-square, phags-pa, gunjala-gondi, sogdian, tai-viet, canadian-aboriginal, math, lepcha, pahawh-hmong, adlam, tagalog, duployan, mahajani, yi, brahmi, hebrew, warang-citi, buginese, rejang, grantha, oriya, bhaiksuki, syloti-nagri, ahom, takri, khojki, coptic, limbu, new-tai-lue, thai, bassa-vah, caucasian-albanian, cham, thaana, telugu, khmer, khudawadi, mandaic, psalter-pahlavi, kharoshthi, saurashtra, gurmukhi, balinese, tai-le, myanmar, tai-tham, sundanese, javanese, symbols, chakma, masaram-gondi, sinhala, tibetan, tagbanwa, elbasan, mongolian, hanunoo, marchen, kayah-li, newa, sharada, music, armenian, nko, mende-kikakui, tifinagh, kannada, lao, old-permic, buhid, miao, siddham, wancho, bengali, devanagari, syriac, dogra, soyombo, gujarati, tirhuta, osage, malayalam</li>
<li>U+25CF BLACK CIRCLE: try adding symbols</li>
<li>U+25E6 WHITE BULLET: try adding symbols</li>
<li>U+25FC BLACK MEDIUM SQUARE: try adding symbols</li>
<li>U+2611 BALLOT BOX WITH CHECK: try adding symbols</li>
<li>U+2612 BALLOT BOX WITH X: try adding symbols</li>
<li>U+2661 WHITE HEART SUIT: try adding symbols</li>
<li>U+2665 BLACK HEART SUIT: try adding symbols</li>
<li>U+27A1 BLACK RIGHTWARDS ARROW: try adding symbols</li>
<li>U+27E8 MATHEMATICAL LEFT ANGLE BRACKET: try adding math</li>
<li>U+27E9 MATHEMATICAL RIGHT ANGLE BRACKET: try adding math</li>
<li>U+2B05 LEFTWARDS BLACK ARROW: try adding symbols</li>
<li>U+2B06 UPWARDS BLACK ARROW: try adding symbols</li>
<li>U+2B07 DOWNWARDS BLACK ARROW: try adding symbols</li>
<li>U+2B08 NORTH EAST BLACK ARROW: try adding symbols</li>
<li>U+2B09 NORTH WEST BLACK ARROW: try adding symbols</li>
<li>U+2B0A SOUTH EAST BLACK ARROW: try adding symbols</li>
<li>U+2B0B SOUTH WEST BLACK ARROW: try adding symbols</li>
<li>U+2B1B BLACK LARGE SQUARE: try adding symbols</li>
<li>U+2B1C WHITE LARGE SQUARE: try adding symbols</li>
<li>U+2B98 THREE-D TOP-LIGHTED LEFTWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B99 THREE-D RIGHT-LIGHTED UPWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9A THREE-D TOP-LIGHTED RIGHTWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9B THREE-D LEFT-LIGHTED DOWNWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9C BLACK LEFTWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9D BLACK UPWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9E BLACK RIGHTWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9F BLACK DOWNWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2E17 DOUBLE OBLIQUE HYPHEN: try adding coptic</li>
<li>U+2E38 TURNED DAGGER: not included in any glyphset definition</li>
<li>U+3003 DITTO MARK: try adding one of: phags-pa, chinese-simplified, japanese, chinese-hongkong, yi, chinese-traditional</li>
<li>U+A717 MODIFIER LETTER DOT VERTICAL BAR: not included in any glyphset definition</li>
<li>U+A718 MODIFIER LETTER DOT SLASH: not included in any glyphset definition</li>
<li>U+A719 MODIFIER LETTER DOT HORIZONTAL BAR: not included in any glyphset definition</li>
<li>U+A71A MODIFIER LETTER LOWER RIGHT CORNER ANGLE: not included in any glyphset definition</li>
<li>U+A7CB : not included in any glyphset definition</li>
<li>U+A7CC : not included in any glyphset definition</li>
<li>U+A7CD : not included in any glyphset definition</li>
<li>U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic</code>, <code>cyrillic-ext</code>, <code>greek-ext</code>, <code>latin</code>, <code>latin-ext</code>, <code>vietnamese</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Name table strings must not contain the string 'Reserved Font Name'. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.license.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Name table entry contains &quot;Reserved Font Name&quot; for a family name (&quot;Merriweather&quot;) that differs from the currently used family name (Merriweather), which is fine.</p>
 [code: legacy-familyname]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure files are not too large. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Font file is 4.3Mb; ideally it should be less than 1.0Mb</p>
 [code: large-font]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- f + i

- f + l
</code></pre>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure Stylistic Sets have description. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gsub.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The stylistic set ss01 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss02 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss03 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss04 lacks a description string on the 'name' table.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check name table IDs 1, 2, 16, 17 to conform to Italic style. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.name.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name ID 17 (Typographic Subfamily Name) must contain 'Italic'.</p>
 [code: bad-typographicsubfamilyname]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to a name ID whose string is equal to the string of either name ID 2 or 17, and its postScriptNameID value is set to a name ID whose string is equal to the string of name ID 6. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.fvar.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>'Black Italic' instance has the same coordinates as the default instance; its subfamily name should be 'Black'</p>
 [code: invalid-default-instance-subfamily-name]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> STAT table has Axis Value tables? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.stat.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>STAT table is missing Axis Value for 'wght' value '450.0'</p>
 [code: missing-axis-value-table]



* 🔥 **FAIL** <p>STAT table is missing Axis Value for 'wght' value '533.3333282470703'</p>
 [code: missing-axis-value-table]



* 🔥 **FAIL** <p>STAT table is missing Axis Value for 'wght' value '720.0'</p>
 [code: missing-axis-value-table]



* 🔥 **FAIL** <p>STAT table is missing Axis Value for 'wght' value '819.2307739257812'</p>
 [code: missing-axis-value-table]



* 🔥 **FAIL** <p>STAT table is missing Axis Value for 'wght' value '450.0'</p>
 [code: missing-axis-value-table]



* 🔥 **FAIL** <p>STAT table is missing Axis Value for 'wght' value '533.3333282470703'</p>
 [code: missing-axis-value-table]



* 🔥 **FAIL** <p>STAT table is missing Axis Value for 'wght' value '716.0'</p>
 [code: missing-axis-value-table]



* 🔥 **FAIL** <p>STAT table is missing Axis Value for 'wght' value '819.2307739257812'</p>
 [code: missing-axis-value-table]



* 🔥 **FAIL** <p>STAT table is missing Axis Value for 'wght' value '450.0'</p>
 [code: missing-axis-value-table]



* 🔥 **FAIL** <p>STAT table is missing Axis Value for 'wght' value '533.3333282470703'</p>
 [code: missing-axis-value-table]



* 🔥 **FAIL** <p>STAT table is missing Axis Value for 'wght' value '716.0'</p>
 [code: missing-axis-value-table]



* 🔥 **FAIL** <p>STAT table is missing Axis Value for 'wght' value '819.2307739257812'</p>
 [code: missing-axis-value-table]



* 🔥 **FAIL** <p>STAT table is missing Axis Value for 'wght' value '450.0'</p>
 [code: missing-axis-value-table]



* 🔥 **FAIL** <p>STAT table is missing Axis Value for 'wght' value '533.3333282470703'</p>
 [code: missing-axis-value-table]



* 🔥 **FAIL** <p>STAT table is missing Axis Value for 'wght' value '716.0'</p>
 [code: missing-axis-value-table]



* 🔥 **FAIL** <p>STAT table is missing Axis Value for 'wght' value '819.2307739257812'</p>
 [code: missing-axis-value-table]



* 🔥 **FAIL** <p>STAT table is missing Axis Value for 'wght' value '450.0'</p>
 [code: missing-axis-value-table]



* 🔥 **FAIL** <p>STAT table is missing Axis Value for 'wght' value '533.3333282470703'</p>
 [code: missing-axis-value-table]



* 🔥 **FAIL** <p>STAT table is missing Axis Value for 'wght' value '716.0'</p>
 [code: missing-axis-value-table]



* 🔥 **FAIL** <p>STAT table is missing Axis Value for 'wght' value '819.2307739257812'</p>
 [code: missing-axis-value-table]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure the font supports case swapping for all its glyphs. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs lack their case-swapping counterparts:</p>
<table>
<thead>
<tr>
<th align="left">Glyph present in the font</th>
<th align="left">Missing case-swapping counterpart</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">U+0460: CYRILLIC CAPITAL LETTER OMEGA</td>
<td align="left">U+0461: CYRILLIC SMALL LETTER OMEGA</td>
</tr>
</tbody>
</table>
 [code: missing-case-counterparts]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Do we have the latest version of FontBakery installed? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Current FontBakery version is 0.12.1, while a newer 0.12.7 is already available. Please upgrade it with 'pip install -U fontbakery'</p>
 [code: outdated-fontbakery]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking with fontTools.ttx <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>WARNING: name id 24 missing from name table</p>
 



* 🔥 **FAIL** <p>WARNING: name id 48 missing from name table</p>
 



* 🔥 **FAIL** <p>WARNING: name id 64 missing from name table</p>
 



* 🔥 **FAIL** <p>WARNING: name id 72 missing from name table</p>
 



* 🔥 **FAIL** <p>WARNING: name id 144 missing from name table</p>
 





</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check name ID 25 to end with "Italic" for Italic VFs. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.metadata.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name ID 25 must end with &quot;Italic&quot; for Italic fonts.</p>
 [code: nameid25-missing-italic]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">cae_Latn (Lehar)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">kss_Latn (Southern Kisi)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">kzr_Latn (Karang)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ybb_Latn (Yemba)</td>
<td align="left">Shaper didn't attach uni0304.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">meq_Latn (Merey)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">snf_Latn (Noon)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bum_Latn (Bulu)</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">dow_Latn (Doyayo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">sld_Latn (Sissala)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ikx_Latn (Ik)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">csk_Latn (Jola-Kasa)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">gvl_Latn (Gulay)</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">tik_Latn (Tikar)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mbo_Latn (Mbo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">fue_Latn (Fulfulde, Borgu)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">cko_Latn (Anufo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">neb_Latn (Toura)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">lem_Latn (Nomaande)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ewo_Latn (Ewondo)</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">kia_Latn (Kim)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">kyq_Latn (Kenga)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bex_Latn (Jur Modo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mor_Latn (Moro)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Requires Small-cap: ꟈ; both buffers returned uniA7C8=0+1225</td>
</tr>
<tr>
<td align="left">dag_Latn (Dagbani)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">tnr_Latn (Ménik)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bza_Latn (Bandi)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">kyf_Latn (Kouya)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">nku_Latn (Kulango, Bouna)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">tuz_Latn (Turka)</td>
<td align="left">Shaper didn't attach tildecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">sig_Latn (Paasaal)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bbj_Latn (Ghomala)</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mgo_Latn (Metaʼ)</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bim_Latn (Bimoba)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">yav_Latn (Yangben)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">wci_Latn (Gbe, Waci)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Requires Small-cap: ƒ; both buffers returned florin=0+985</td>
</tr>
<tr>
<td align="left">avu_Latn (Avokaya)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">vag_Latn (Vagla)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">sil_Latn (Sisaala, Tumulung)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">dyo_Latn (Jola-Fonyi)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">wwa_Latn (Waama)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">sav_Latn (Saafi-Saafi)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">wo_Latn (Wolof)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mzw_Latn (Deg)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ncu_Latn (Chumburung)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">udu_Latn (Uduk)</td>
<td align="left">Shaper didn't attach uni0331.case to P</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to p</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to p</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331.case to P</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to p.sc</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331.case to P</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">nfu_Latn (Mfumte)</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">yat_Latn (Yambeta)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mcn_Latn (Masana)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">fod_Latn (Foodo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">vut_Latn (Vute)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">dop_Latn (Lukpa)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mdt_Latn (Mbere)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ekm_Latn (Elip)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">soy_Latn (Miyobe)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">agc_Latn (Agatu)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">acd_Latn (Gikyode)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">kye_Latn (Krache)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">lmp_Latn (Limbum)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">spp_Latn (Sénoufo, Supyire)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mfq_Latn (Moba)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bqj_Latn (Bandial)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bib_Latn (Bissa)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mfd_Latn (Mendankwe-Nkwen)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">shz_Latn (Syenara Senoufo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">lee_Latn (Lyélé)</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">vai_Latn (Vai (Latin))</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">moa_Latn (Mwan)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">fan_Latn (Fang)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">dtm_Latn (Tomo Kan Dogon)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ttq_Latn (Tawallammat Tamajaq)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ntr_Latn (Delo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bm_Latn (Bambara)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">lg_Latn (Ganda)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">dyi_Latn (Sénoufo, Djimini)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">kpo_Latn (Ikposo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">rub_Latn (Gungu)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">dnj_Latn (Dan)</td>
<td align="left">Shaper didn't attach uni0302 to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030F to uni0264</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0264</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0264</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0264</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B to uni0264</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030F to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0264</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030F to uni0264</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030F to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0264</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0264</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0264</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B to uni0264</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0264</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030F to uni0264.sc</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030F to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0264.sc</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0264.sc</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0264.sc</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B to uni0264.sc</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0264.sc</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect uni0181</td>
</tr>
<tr>
<td align="left">mfi_Latn (Wandala)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">gux_Latn (Gourmanchéma)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">fvr_Latn (Fur)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">fuq_Latn (Central-Eastern Niger Fulfulde)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bkm_Latn (Kom)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">nym_Latn (Nyamwezi)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">nnh_Latn (Ngiemboon)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bss_Latn (Akoose)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">etu_Latn (Ejagham)</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">lnl_Latn (South Central Banda)</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308.case to uni018F</td>
</tr>
<tr>
<td align="left">sxw_Latn (Saxwe Gbe)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">daa_Latn (Dangaléat)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bqv_Latn (Koro Wachi)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bud_Latn (Ntcham)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">adj_Latn (Adioukrou)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">khq_Latn (Koyra Chiini)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">lia_Latn (Limba, West-Central)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">nus_Latn (Nuer)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">tem_Latn (Timne)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">gnd_Latn (Zulgo-Gemzek)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">pil_Latn (Yom)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">wan_Latn (Wan)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">log_Latn (Logo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">kao_Latn (Xaasongaxango)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mnf_Latn (Mundani)</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">twq_Latn (Tasawaq)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ksf_Latn (Bafia)</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ksp_Latn (Kabba)</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308.case to uni018F</td>
</tr>
<tr>
<td align="left">dgi_Latn (Northern Dagara)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">nmg_Latn (Kwasio)</td>
<td align="left">Shaper didn't attach uni030C.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">blo_Latn (Anii)</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">dnj_Latn_LR (Dan)</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0265</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0265</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0265</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0265</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">ach_Latn (Acoli)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">kqp_Latn (Kimré)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">dyu_Latn (Dyula)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">fuh_Latn (Fulfulde, Western Niger)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">sbd_Latn (Southern Samo)</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ozm_Latn (Koonzime)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">dur_Latn (Dii)</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0327.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0327.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0327.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0327.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0327.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0327.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0327.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0327.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0327.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0327.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">tcd_Latn (Tafi)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Requires Small-cap: ƒ; both buffers returned florin=0+985</td>
</tr>
<tr>
<td align="left">bfa_Latn (Bari)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">hag_Latn (Hanga)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mge_Latn (Mango)</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0330</td>
</tr>
<tr>
<td align="left">xon_Latn (Konkomba)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">dip_Latn (Dinka, Northeastern)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mev_Latn (Mano)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">azo_Latn (Awing)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">lam_Latn (Lamba)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">tuq_Latn (Tedaga)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bfd_Latn (Bafut)</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">laj_Latn (Lango [Uganda])</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mas_Latn (Masai)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">nmz_Latn (Nawdm)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">kqs_Latn (Kissi, Northern)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">idu_Latn (Idoma)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">las_Latn (Lama (Togo))</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">pnz_Latn (Pana (Central African Republic))</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">biv_Latn (Birifor, Southern)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">nuv_Latn (Nuni, Northern)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bcw_Latn (Bana)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bzw_Latn (Basa)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">avn_Latn (Avatime)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Requires Small-cap: ƒ; both buffers returned florin=0+985</td>
</tr>
<tr>
<td align="left">maw_Latn (Mampruli)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">fuc_Latn (Pulaar)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">dua_Latn (Duala)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">dts_Latn (Dogon, Toro So)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mwk_Latn (Kita Maninkakan)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">kmy_Latn (Koma)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">sba_Latn (Ngambay)</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni018E</td>
</tr>
<tr>
<td align="left">lok_Latn (Loko)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bsc_Latn (Bassari)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">gjn_Latn (Gonja)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">kzc_Latn (Bondoukou Kulango)</td>
<td align="left">Shaper didn't attach tildecomb.case to uniA7B6</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uniA7B6</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uniA7AE.sc</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uniA7B7.sc</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uniA7B6</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">nza_Latn (Tigon Mbembe)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ife_Latn (Ifè)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ses_Latn (Koyraboro Senni)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">knf_Latn (Mankanya)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">agq_Latn (Aghem)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mnk_Latn (Mandinka)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">kdh_Latn (Tem)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ny_Latn (Nyanja)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bas_Latn (Basaa)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mfv_Latn (Mandjak)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">fuf_Latn (Pular)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mgc_Latn (Morokodo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">yas_Latn (Nugunu)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">gmm_Latn (Gbaya-Mbodomo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bjt_Latn (Balanta-Ganja)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">taq_Latn (Tamasheq, Latin)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">dzg_Latn (Dazaga)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">xrb_Latn (Karaboro, Eastern)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ted_Latn (Krumen, Tepo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">yam_Latn (Yamba)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">nhb_Latn (Beng)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">anv_Latn (Denya)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">krs_Latn (Gbaya (Sudan))</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bbo_Latn (Northern Bobo Madaré)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">pbi_Latn (Parkwa)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">fmp_Latn (Fe’fe’)</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ktj_Latn (Krumen, Plapo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">kus_Latn (Kusaal)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mwm_Latn (Sar)</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni018F</td>
</tr>
<tr>
<td align="left">gej_Latn (Gen)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">gng_Latn (Ngangam)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">muy_Latn (Muyang)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mua_Latn (Mundang)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">boz_Latn (Tiéyaxo Bozo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">nnw_Latn (Southern Nuni)</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">gur_Latn (Frafra)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">emk_Latn (Maninkakan, Eastern)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ken_Latn (Kenyang)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">loq_Latn (Lobala)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ddn_Latn (Dendi)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">naw_Latn (Nawuri)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mls_Latn (Masalit)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mbu_Latn (Mbula-Bwazza)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bzx_Latn (Bozo, Hainyaxo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">xwe_Latn (Gbe, Xwela)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">fub_Latn (Fulfulde, Adamawa)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">tvu_Latn (Tunen)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">keu_Latn (Akebu)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">xed_Latn (Hdi)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">byv_Latn (Medumba)</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mmu_Latn (Mmaala)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">lns_Latn (Lamnso’)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">tod_Latn (Toma)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect uni028B</td>
</tr>
<tr>
<td align="left">lgg_Latn (Lugbara)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0328.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0328.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni0259.sc</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0259.sc</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0259.sc</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0328.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0328.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni025B.sc</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni025B.sc</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni025B.sc</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni0254.sc</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0254.sc</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0254.sc</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">knp_Latn (Kwanja)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">myk_Latn (Mamara Senoufo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">gud_Latn (Dida, Yocoboué)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bsp_Latn (Baga Sitemu)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">god_Latn (Godié)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">dno_Latn (Ndrulo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">nhu_Latn (Noone)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">toq_Latn (Toposa)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">kib_Latn (Koalib)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Requires Small-cap: ɐ; both buffers returned uni2C6F=0+1320</td>
</tr>
<tr>
<td align="left">xsm_Latn (Kasem)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">cme_Latn (Cerma)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mdj_Latn (Mangbetu)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">cou_Latn (Wamey)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ade_Latn (Adele)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ahs_Latn (Ashe)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ee_Latn (Ewe)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Requires Small-cap: ƒ; both buffers returned florin=0+985</td>
</tr>
<tr>
<td align="left">kvf_Latn (Kabalai)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">gde_Latn (Gude)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ndz_Latn (Ndogo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bax_Latn (Bamun, Latin)</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mcu_Latn (Mambila, Cameroon)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">lig_Latn (Ligbi)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">tpm_Latn (Tampulma)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">sok_Latn (Sokoro)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">kbp_Latn (Kabiyé)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mcp_Latn (Makaa)</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">xuo_Latn (Kuo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">srr_Latn (Serer)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bze_Latn (Jenaama Bozo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ig_Latn (Igbo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">gaa_Latn (Ga)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect uni01A9</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">The locl feature did not affect uni01B7</td>
</tr>
<tr>
<td align="left">gov_Latn (Goo)</td>
<td align="left">Shaper didn't attach uni0302 to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0264</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0264</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uniA7CB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0264</td>
</tr>
<tr>
<td align="left">nko_Latn (Nkonya)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">sef_Latn (Cebaara Senoufo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">jgo_Latn (Ngomba)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">nfr_Latn (Nafaanra)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">mur_Latn (Murle)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ffm_Latn (Maasina Fulfulde)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">lob_Latn (Lobi)</td>
<td align="left">Shaper didn't attach tildecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">pug_Latn (Phuie)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">lun_Latn (Lunda)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">dje_Latn (Zarma)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ahl_Latn (Igo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ajg_Latn (Aja)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">saf_Latn (Safaliba)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">ndv_Latn (Ndut)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">nyb_Latn (Nyangbo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Requires Small-cap: ƒ; both buffers returned florin=0+985</td>
</tr>
<tr>
<td align="left">kkj_Latn (Kako)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">bav_Latn (Vengo)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
<tr>
<td align="left">gna_Latn (Kaansa)</td>
<td align="left">The locl feature did not affect Eng</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kfo_Latn (Koro)</td>
<td align="left">No exemplar glyphs were defined for language Koro</td>
</tr>
<tr>
<td align="left">cch_Latn (Atsam)</td>
<td align="left">No exemplar glyphs were defined for language Atsam</td>
</tr>
<tr>
<td align="left">amo_Latn (Amo)</td>
<td align="left">No exemplar glyphs were defined for language Amo</td>
</tr>
<tr>
<td align="left">mgy_Latn (Mbunga)</td>
<td align="left">No exemplar glyphs were defined for language Mbunga</td>
</tr>
<tr>
<td align="left">ggn_Latn (Eastern Gurung, Latin)</td>
<td align="left">No exemplar glyphs were defined for language Eastern Gurung, Latin</td>
</tr>
<tr>
<td align="left">hna_Latn (Mina)</td>
<td align="left">No exemplar glyphs were defined for language Mina</td>
</tr>
<tr>
<td align="left">syi_Latn (Seki)</td>
<td align="left">No exemplar glyphs were defined for language Seki</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Combined length of family and style must not exceed 32 characters. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 262 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 262 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 14 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 266 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 14 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 266 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 14 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 267 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 14 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 267 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 14 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 268 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 14 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 268 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 14 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 269 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 14 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 269 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 14 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 270 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 14 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 270 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 14 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 271 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 14 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 271 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 14 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 272 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 14 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 272 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 16 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 273 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 16 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 273 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 16 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 274 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 16 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 274 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 16 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 275 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 16 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 275 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 16 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 276 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 16 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 276 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 16 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 277 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 16 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 277 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 16 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 278 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 16 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 278 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 16 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 279 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 16 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 279 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 24 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 280 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 24 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 280 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 24 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 281 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 24 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 281 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 24 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 282 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 24 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 282 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 24 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 283 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 24 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 283 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 24 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 284 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 24 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 284 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 24 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 285 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 24 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 285 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 24 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 286 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 24 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 286 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 48 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 287 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 48 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 287 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 48 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 288 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 48 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 288 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 48 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 289 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 48 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 289 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 48 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 290 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 48 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 290 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 48 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 291 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 48 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 291 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 48 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 292 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 48 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 292 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 48 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 293 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 48 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 293 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 64 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 294 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 64 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 294 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 64 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 295 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 64 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 295 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 64 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 296 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 64 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 296 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 64 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 297 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 64 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 297 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 64 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 298 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 64 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 298 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 64 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 299 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 64 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 299 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 64 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 300 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 64 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 300 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 72 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 301 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 72 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 301 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 72 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 302 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 72 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 302 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 72 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 303 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 72 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 303 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 72 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 304 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 72 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 304 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 72 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 305 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 72 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 305 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 72 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 306 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 72 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 306 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 72 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 307 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 72 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 307 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 144 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 308 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 144 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 308 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 144 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 309 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 144 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 309 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 144 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 310 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 144 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 310 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 144 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 311 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 144 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 311 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 144 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 312 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 144 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 312 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExtraBold 144 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 313 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExtraBold 144 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 313 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 144 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 314 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 144 Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 314 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 315 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 315 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 316 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 316 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 317 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 317 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 318 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 318 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 319 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 319 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 320 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 320 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 321 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 321 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 14 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 322 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 14 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 322 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 14 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 323 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 14 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 323 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 14 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 324 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 14 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 324 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 14 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 325 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 14 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 325 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 14 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 326 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 14 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 326 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 14 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 327 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 14 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 327 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 14 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 328 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 14 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 328 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 16 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 329 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 16 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 329 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 16 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 330 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 16 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 330 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 16 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 331 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 16 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 331 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 16 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 332 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 16 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 332 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 16 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 333 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 16 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 333 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 16 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 334 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 16 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 334 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 16 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 335 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 16 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 335 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 24 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 336 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 24 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 336 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 24 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 337 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 24 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 337 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 24 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 338 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 24 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 338 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 24 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 339 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 24 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 339 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 24 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 340 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 24 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 340 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 24 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 341 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 24 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 341 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 24 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 342 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 24 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 342 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 48 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 343 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 48 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 343 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 48 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 344 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 48 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 344 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 48 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 345 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 48 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 345 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 48 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 346 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 48 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 346 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 48 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 347 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 48 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 347 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 48 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 348 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 48 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 348 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 48 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 349 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 48 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 349 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 64 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 350 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 64 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 350 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 64 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 351 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 64 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 351 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 64 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 352 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 64 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 352 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 64 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 353 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 64 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 353 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 64 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 354 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 64 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 354 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 64 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 355 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 64 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 355 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 64 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 356 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 64 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 356 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 72 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 357 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 72 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 357 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 72 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 358 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 72 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 358 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 72 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 359 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 72 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 359 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 72 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 360 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 72 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 360 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 72 Cond Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 361 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 72 Cond Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 361 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 72 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 362 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 72 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 362 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 72 Cond Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 363 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 72 Cond Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 363 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 144 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 364 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 144 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 364 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 144 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 365 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 144 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 365 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 144 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 366 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 144 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 366 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 144 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 367 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 144 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 367 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 144 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 368 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 144 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 368 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 144 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 369 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 144 Cnd Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 369 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 144 Cond Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 370 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 144 Cond Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 370 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 371 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 371 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 372 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 372 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 373 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 373 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 374 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 374 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 375 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 375 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 376 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 376 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 377 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 377 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 14 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 378 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 14 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 378 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 14 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 379 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 14 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 379 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 14 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 380 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 14 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 380 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 14 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 381 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 14 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 381 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 14 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 382 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 14 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 382 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExtraBold 14 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 383 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExtraBold 14 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 383 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 14 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 384 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 14 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 384 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 16 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 385 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 16 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 385 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 16 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 386 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 16 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 386 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 16 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 387 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 16 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 387 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 16 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 388 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 16 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 388 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 16 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 389 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 16 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 389 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 16 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 390 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 16 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 390 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 16 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 391 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 16 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 391 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 24 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 392 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 24 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 392 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 24 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 393 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 24 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 393 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 24 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 394 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 24 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 394 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 24 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 395 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 24 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 395 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 24 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 396 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 24 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 396 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExtraBold 24 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 397 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExtraBold 24 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 397 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 24 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 398 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 24 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 398 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 48 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 399 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 48 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 399 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 48 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 400 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 48 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 400 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 48 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 401 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 48 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 401 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 48 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 402 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 48 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 402 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 48 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 403 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 48 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 403 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 48 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 404 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 48 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 404 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 48 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 405 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 48 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 405 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 64 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 406 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 64 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 406 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 64 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 407 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 64 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 407 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 64 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 408 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 64 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 408 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 64 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 409 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 64 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 409 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 64 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 410 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 64 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 410 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 64 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 411 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 64 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 411 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 64 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 412 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 64 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 412 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 72 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 413 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 72 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 413 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 72 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 414 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 72 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 414 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 72 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 415 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 72 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 415 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 72 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 416 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 72 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 416 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 72 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 417 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 72 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 417 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 72 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 418 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 72 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 418 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 72 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 419 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 72 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 419 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 144 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 420 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Light 144 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 420 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 144 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 421 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Regular 144 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 421 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 144 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 422 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Medium 144 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 422 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 144 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 423 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black SemiBold 144 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 423 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 144 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 424 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Bold 144 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 424 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 144 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 425 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black ExBold 144 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 425 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 144 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 426 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Merriweather Black Black 144 Wide Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 426 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking file is named canonically. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Expected &quot;Merriweather[opsz,wdth,wght].ttf. Got Merriweather-Italic[opsz,wdth,wght].ttf.</p>
 [code: bad-filename]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font names are correct <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Font names are incorrect:</p>
<table>
<thead>
<tr>
<th align="left">nameID</th>
<th align="left">current</th>
<th align="left">expected</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Family Name</td>
<td align="left">Merriweather Black</td>
<td align="left">Merriweather Black</td>
</tr>
<tr>
<td align="left">Subfamily Name</td>
<td align="left"><strong>Italic</strong></td>
<td align="left"><strong>Regular</strong></td>
</tr>
<tr>
<td align="left">Full Name</td>
<td align="left">Merriweather Black</td>
<td align="left">Merriweather Black</td>
</tr>
<tr>
<td align="left">Postscript Name</td>
<td align="left">Merriweather-Black</td>
<td align="left">Merriweather-Black</td>
</tr>
<tr>
<td align="left">Typographic Family Name</td>
<td align="left">Merriweather</td>
<td align="left">Merriweather</td>
</tr>
<tr>
<td align="left">Typographic Subfamily Name</td>
<td align="left">Black</td>
<td align="left">Black</td>
</tr>
</tbody>
</table>
 [code: bad-names]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check variable font instances <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.varfont.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>fvar instances are incorrect:</p>
<ul>
<li>Add missing instances</li>
<li>Delete additional instances</li>
</ul>
<table>
<thead>
<tr>
<th align="left">Name</th>
<th align="left">current</th>
<th align="left">expected</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">SemiBold Italic</td>
<td align="left">wght=600.0, wdth=100.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 24 Cnd Italic</td>
<td align="left">wght=900.0, wdth=87.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 144 Wide Italic</td>
<td align="left">wght=700.0, wdth=112.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExtraBold 14 Wide Italic</td>
<td align="left">wght=819.2307739257812, wdth=112.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 48 Wide Italic</td>
<td align="left">wght=600.0, wdth=112.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium Italic</td>
<td align="left">wght=500.0, wdth=100.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 16 Cnd Italic</td>
<td align="left">wght=400.0, wdth=87.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 14 Cnd Italic</td>
<td align="left">wght=800.0, wdth=87.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 48 Wide Italic</td>
<td align="left">wght=500.0, wdth=112.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 64 Italic</td>
<td align="left">wght=300.0, wdth=100.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 144 Wide Italic</td>
<td align="left">wght=300.0, wdth=112.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 72 Wide Italic</td>
<td align="left">wght=700.0, wdth=112.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 144 Italic</td>
<td align="left">wght=600.0, wdth=100.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 48 Cnd Italic</td>
<td align="left">wght=800.0, wdth=87.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 14 Cnd Italic</td>
<td align="left">wght=500.0, wdth=87.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 48 Cnd Italic</td>
<td align="left">wght=600.0, wdth=87.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 72 Italic</td>
<td align="left">wght=800.0, wdth=100.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 14 Cnd Italic</td>
<td align="left">wght=300.0, wdth=87.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 16 Wide Italic</td>
<td align="left">wght=819.2307739257812, wdth=112.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 72 Italic</td>
<td align="left">wght=300.0, wdth=100.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 48 Italic</td>
<td align="left">wght=400.0, wdth=100.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 64 Cnd Italic</td>
<td align="left">wght=400.0, wdth=87.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 14 Wide Italic</td>
<td align="left">wght=716.0, wdth=112.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 48 Wide Italic</td>
<td align="left">wght=300.0, wdth=112.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black Italic</td>
<td align="left">wght=900.0, wdth=100.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light Wide Italic</td>
<td align="left">wght=300.0, wdth=112.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 144 Wide Italic</td>
<td align="left">wght=400.0, wdth=112.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 14 Italic</td>
<td align="left">wght=500.0, wdth=100.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 48 Cnd Italic</td>
<td align="left">wght=300.0, wdth=87.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 144 Wide Italic</td>
<td align="left">wght=600.0, wdth=112.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 16 Cnd Italic</td>
<td align="left">wght=900.0, wdth=87.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 64 Cnd Italic</td>
<td align="left">wght=800.0, wdth=87.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 24 Cnd Italic</td>
<td align="left">wght=400.0, wdth=87.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 48 Wide Italic</td>
<td align="left">wght=700.0, wdth=112.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 14 Wide Italic</td>
<td align="left">wght=533.3333282470703, wdth=112.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 144 Italic</td>
<td align="left">wght=700.0, wdth=100.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 14 Italic</td>
<td align="left">wght=700.0, wdth=100.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 64 Cnd Italic</td>
<td align="left">wght=700.0, wdth=87.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 72 Cnd Italic</td>
<td align="left">wght=300.0, wdth=87.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 16 Cnd Italic</td>
<td align="left">wght=300.0, wdth=87.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 24 Wide Italic</td>
<td align="left">wght=716.0, wdth=112.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 24 Cnd Italic</td>
<td align="left">wght=700.0, wdth=87.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold Wide Italic</td>
<td align="left">wght=700.0, wdth=112.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 24 Wide Italic</td>
<td align="left">wght=450.0, wdth=112.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 14 Cnd Italic</td>
<td align="left">wght=700.0, wdth=87.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 48 Cnd Italic</td>
<td align="left">wght=900.0, wdth=87.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 64 Wide Italic</td>
<td align="left">wght=600.0, wdth=112.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 24 Cnd Italic</td>
<td align="left">wght=800.0, wdth=87.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 144 Cond Italic</td>
<td align="left">wght=900.0, wdth=87.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 14 Wide Italic</td>
<td align="left">wght=400.0, wdth=112.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 72 Italic</td>
<td align="left">wght=400.0, wdth=100.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 24 Italic</td>
<td align="left">wght=400.0, wdth=100.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 14 Cnd Italic</td>
<td align="left">wght=600.0, wdth=87.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 72 Italic</td>
<td align="left">wght=500.0, wdth=100.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 64 Italic</td>
<td align="left">wght=900.0, wdth=100.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 14 Cnd Italic</td>
<td align="left">wght=900.0, wdth=87.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 48 Wide Italic</td>
<td align="left">wght=800.0, wdth=112.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 144 Cnd Italic</td>
<td align="left">wght=800.0, wdth=87.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold Cnd Italic</td>
<td align="left">wght=600.0, wdth=87.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold Wide Italic</td>
<td align="left">wght=600.0, wdth=112.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 144 Wide Italic</td>
<td align="left">wght=800.0, wdth=112.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular Wide Italic</td>
<td align="left">wght=400.0, wdth=112.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 144 Wide Italic</td>
<td align="left">wght=900.0, wdth=112.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 64 Wide Italic</td>
<td align="left">wght=300.0, wdth=112.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 14 Cnd Italic</td>
<td align="left">wght=400.0, wdth=87.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 24 Cnd Italic</td>
<td align="left">wght=300.0, wdth=87.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 64 Italic</td>
<td align="left">wght=500.0, wdth=100.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 144 Cnd Italic</td>
<td align="left">wght=500.0, wdth=87.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 144 Wide Italic</td>
<td align="left">wght=500.0, wdth=112.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 14 Italic</td>
<td align="left">wght=300.0, wdth=100.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 24 Italic</td>
<td align="left">wght=500.0, wdth=100.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 16 Cnd Italic</td>
<td align="left">wght=716.0, wdth=87.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 24 Wide Italic</td>
<td align="left">wght=533.3333282470703, wdth=112.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 144 Cnd Italic</td>
<td align="left">wght=400.0, wdth=87.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Italic</td>
<td align="left">wght=400.0, wdth=100.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 14 Italic</td>
<td align="left">wght=900.0, wdth=100.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 24 Italic</td>
<td align="left">wght=600.0, wdth=100.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 64 Cnd Italic</td>
<td align="left">wght=300.0, wdth=87.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 14 Italic</td>
<td align="left">wght=400.0, wdth=100.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light Italic</td>
<td align="left">wght=300.0, wdth=100.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 14 Italic</td>
<td align="left">wght=800.0, wdth=100.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 64 Italic</td>
<td align="left">wght=800.0, wdth=100.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black Wide Italic</td>
<td align="left">wght=900.0, wdth=112.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 48 Cnd Italic</td>
<td align="left">wght=400.0, wdth=87.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold Wide Italic</td>
<td align="left">wght=800.0, wdth=112.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExtraBold 144 Italic</td>
<td align="left">wght=800.0, wdth=100.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 144 Italic</td>
<td align="left">wght=900.0, wdth=100.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold Italic</td>
<td align="left">wght=700.0, wdth=100.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium Wide Italic</td>
<td align="left">wght=500.0, wdth=112.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 16 Italic</td>
<td align="left">wght=450.0, wdth=100.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 48 Wide Italic</td>
<td align="left">wght=400.0, wdth=112.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 72 Wide Italic</td>
<td align="left">wght=400.0, wdth=112.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 16 Wide Italic</td>
<td align="left">wght=900.0, wdth=112.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 24 Cnd Italic</td>
<td align="left">wght=600.0, wdth=87.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 64 Italic</td>
<td align="left">wght=700.0, wdth=100.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 16 Wide Italic</td>
<td align="left">wght=533.3333282470703, wdth=112.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 72 Cnd Italic</td>
<td align="left">wght=800.0, wdth=87.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 72 Italic</td>
<td align="left">wght=600.0, wdth=100.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 64 Wide Italic</td>
<td align="left">wght=700.0, wdth=112.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 64 Italic</td>
<td align="left">wght=600.0, wdth=100.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 72 Wide Italic</td>
<td align="left">wght=500.0, wdth=112.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExtraBold 24 Wide Italic</td>
<td align="left">wght=819.2307739257812, wdth=112.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 72 Wide Italic</td>
<td align="left">wght=300.0, wdth=112.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 16 Italic</td>
<td align="left">wght=900.0, wdth=100.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 64 Wide Italic</td>
<td align="left">wght=400.0, wdth=112.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light Cnd Italic</td>
<td align="left">wght=300.0, wdth=87.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 72 Cnd Italic</td>
<td align="left">wght=600.0, wdth=87.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 16 Cnd Italic</td>
<td align="left">wght=819.2307739257812, wdth=87.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 144 Italic</td>
<td align="left">wght=300.0, wdth=100.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold Italic</td>
<td align="left">wght=800.0, wdth=100.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 72 Italic</td>
<td align="left">wght=700.0, wdth=100.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 24 Italic</td>
<td align="left">wght=900.0, wdth=100.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 14 Italic</td>
<td align="left">wght=600.0, wdth=100.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 144 Italic</td>
<td align="left">wght=500.0, wdth=100.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium Cnd Italic</td>
<td align="left">wght=500.0, wdth=87.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 16 Wide Italic</td>
<td align="left">wght=300.0, wdth=112.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 72 Wide Italic</td>
<td align="left">wght=800.0, wdth=112.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 24 Cnd Italic</td>
<td align="left">wght=500.0, wdth=87.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 72 Wide Italic</td>
<td align="left">wght=900.0, wdth=112.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 16 Cnd Italic</td>
<td align="left">wght=533.3333282470703, wdth=87.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 144 Cnd Italic</td>
<td align="left">wght=300.0, wdth=87.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 72 Cond Italic</td>
<td align="left">wght=900.0, wdth=87.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 14 Wide Italic</td>
<td align="left">wght=300.0, wdth=112.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 72 Italic</td>
<td align="left">wght=900.0, wdth=100.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 64 Wide Italic</td>
<td align="left">wght=500.0, wdth=112.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 24 Italic</td>
<td align="left">wght=800.0, wdth=100.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 64 Cnd Italic</td>
<td align="left">wght=900.0, wdth=87.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 72 Cond Italic</td>
<td align="left">wght=700.0, wdth=87.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 48 Wide Italic</td>
<td align="left">wght=900.0, wdth=112.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 14 Wide Italic</td>
<td align="left">wght=450.0, wdth=112.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 48 Cnd Italic</td>
<td align="left">wght=500.0, wdth=87.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 64 Cnd Italic</td>
<td align="left">wght=500.0, wdth=87.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 144 Italic</td>
<td align="left">wght=400.0, wdth=100.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 48 Italic</td>
<td align="left">wght=500.0, wdth=100.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 48 Italic</td>
<td align="left">wght=600.0, wdth=100.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 48 Italic</td>
<td align="left">wght=900.0, wdth=100.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 144 Cnd Italic</td>
<td align="left">wght=600.0, wdth=87.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 16 Wide Italic</td>
<td align="left">wght=400.0, wdth=112.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 16 Italic</td>
<td align="left">wght=300.0, wdth=100.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 24 Wide Italic</td>
<td align="left">wght=300.0, wdth=112.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 48 Italic</td>
<td align="left">wght=800.0, wdth=100.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 48 Italic</td>
<td align="left">wght=300.0, wdth=100.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 64 Wide Italic</td>
<td align="left">wght=900.0, wdth=112.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 16 Wide Italic</td>
<td align="left">wght=716.0, wdth=112.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 16 Wide Italic</td>
<td align="left">wght=450.0, wdth=112.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 14 Wide Italic</td>
<td align="left">wght=900.0, wdth=112.0, opsz=14.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold Cnd Italic</td>
<td align="left">wght=700.0, wdth=87.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 16 Italic</td>
<td align="left">wght=400.0, wdth=100.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 64 Italic</td>
<td align="left">wght=400.0, wdth=100.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black Cnd Italic</td>
<td align="left">wght=900.0, wdth=87.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 144 Cnd Italic</td>
<td align="left">wght=700.0, wdth=87.0, opsz=144.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Black 24 Wide Italic</td>
<td align="left">wght=900.0, wdth=112.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 72 Cnd Italic</td>
<td align="left">wght=400.0, wdth=87.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 16 Italic</td>
<td align="left">wght=720.0, wdth=100.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 16 Italic</td>
<td align="left">wght=819.2307739257812, wdth=100.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 48 Cnd Italic</td>
<td align="left">wght=700.0, wdth=87.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 72 Cnd Italic</td>
<td align="left">wght=500.0, wdth=87.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 16 Italic</td>
<td align="left">wght=533.3333282470703, wdth=100.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 24 Italic</td>
<td align="left">wght=700.0, wdth=100.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light 24 Italic</td>
<td align="left">wght=300.0, wdth=100.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular 24 Wide Italic</td>
<td align="left">wght=400.0, wdth=112.0, opsz=24.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Bold 48 Italic</td>
<td align="left">wght=700.0, wdth=100.0, opsz=48.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold 64 Wide Italic</td>
<td align="left">wght=800.0, wdth=112.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 72 Wide Italic</td>
<td align="left">wght=600.0, wdth=112.0, opsz=72.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Regular Cnd Italic</td>
<td align="left">wght=400.0, wdth=87.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">SemiBold 64 Cnd Italic</td>
<td align="left">wght=600.0, wdth=87.0, opsz=64.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExBold Cnd Italic</td>
<td align="left">wght=800.0, wdth=87.0, opsz=12.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Medium 16 Cnd Italic</td>
<td align="left">wght=450.0, wdth=87.0, opsz=16.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Light</td>
<td align="left">N/A</td>
<td align="left">wght=300.0, wdth=100.0, opsz=12.0</td>
</tr>
<tr>
<td align="left">Regular</td>
<td align="left">N/A</td>
<td align="left">wght=400.0, wdth=100.0, opsz=12.0</td>
</tr>
<tr>
<td align="left">Medium</td>
<td align="left">N/A</td>
<td align="left">wght=500.0, wdth=100.0, opsz=12.0</td>
</tr>
<tr>
<td align="left">SemiBold</td>
<td align="left">N/A</td>
<td align="left">wght=600.0, wdth=100.0, opsz=12.0</td>
</tr>
<tr>
<td align="left">Bold</td>
<td align="left">N/A</td>
<td align="left">wght=700.0, wdth=100.0, opsz=12.0</td>
</tr>
<tr>
<td align="left">ExtraBold</td>
<td align="left">N/A</td>
<td align="left">wght=800.0, wdth=100.0, opsz=12.0</td>
</tr>
<tr>
<td align="left">Black</td>
<td align="left">N/A</td>
<td align="left">wght=900.0, wdth=100.0, opsz=12.0</td>
</tr>
</tbody>
</table>
 [code: bad-fvar-instances]



</div>
</details>

<details>
    <summary>💥 <b>ERROR</b> Validate STAT particle names and values match the fallback names in GFAxisRegistry. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.axisregistry.html#"></a></summary>
    <div>







* 💥 **ERROR** <p>Failed with AttributeError: 'NoneType' object has no attribute 'toUnicode'</p>
<pre><code>  File &quot;/home/runner/work/Merriweather4/Merriweather4/venv-test/lib/python3.10/site-packages/fontbakery/checkrunner.py&quot;, line 213, in _run_check
    subresults = list(subresults)
  File &quot;/home/runner/work/Merriweather4/Merriweather4/venv-test/lib/python3.10/site-packages/fontbakery/checks/googlefonts/axisregistry.py&quot;, line 191, in com_google_fonts_check_STAT_gf_axisregistry_names
    name = normalize_name(name_entry.toUnicode())

</code></pre>
 [code: failed-check]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 2 | 0 | 18 | 26 | 177 | 15 | 242 | 0 | 
| 0% | 0% | 4% | 5% | 37% | 3% | 50% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
