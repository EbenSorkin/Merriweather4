## Fontbakery report

Fontbakery version: 0.8.9

<details><summary><b>[1] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Fonts have consistent underline thickness? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/family/underline_thickness">com.google.fonts/check/family/underline_thickness</a>)</summary><div>


* 🔥 **FAIL** Thickness of the underline is not the same across this family. In order to fix this, please make sure that the underlineThickness value is the same in the 'post' table of all of this family font files.
Detected underlineThickness values are:
	fonts/ttf/Merriweather-BoldItalic.ttf: 90
	fonts/ttf/Merriweather-Bold.ttf: 104
	fonts/ttf/Merriweather-LightItalic.ttf: 90
	fonts/ttf/Merriweather-BlackItalic.ttf: 90
	fonts/ttf/Merriweather-Italic.ttf: 90
	fonts/ttf/Merriweather-Black.ttf: 110
	fonts/ttf/Merriweather-Regular.ttf: 96
	fonts/ttf/Merriweather-Light.ttf: 90
 [code: inconsistent-underline-thickness]
</div></details><br></div></details><details><summary><b>[14] Merriweather-BoldItalic.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
* ⚠ **WARN** GF_Latin_Minorities is almost fulfilled. Missing codepoints:

	- 0xA78B (LATIN CAPITAL LETTER SALTILLO)
 

	- And 0xA78C (LATIN SMALL LETTER SALTILLO)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Arabic is almost fulfilled. Missing codepoints:

	- 0x1E34 (LATIN CAPITAL LETTER K WITH LINE BELOW)


	- 0x1E35 (LATIN SMALL LETTER K WITH LINE BELOW)


	- 0x1E96 (LATIN SMALL LETTER H WITH LINE BELOW)
 

	- And 0x02BD (MODIFIER LETTER REVERSED COMMA)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 625, but got 606 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=14] [code: http-in-license-info]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* quotedblleft.ss01
	* uni25FC
	* Acircumflex
	* uni03060301.case
	* bracketleft
	* Ohungarumlaut
	* ntilde
	* uni03020309.case
	* uni04ED
	* six.lf and 309 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Name table strings must not contain the string 'Reserved Font Name'. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/rfn">com.google.fonts/check/name/rfn</a>)</summary><div>


* ⚠ **WARN** Name table entry contains "Reserved Font Name" for a family name ("Merriweather") that differs from the currently used family name (Merriweather), which is fine. [code: legacy-familyname]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- logicalnot.case

	- notequal.case

	- infinity.case

	- emptyset.case

	- minus.case

	- greaterequal.case

	- figuredash.case

	- ij_acutecomb

	- uni2236.case

	- i.dot 

	- And 13 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: B	Contours detected: 4	Expected: 2 or 3

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1 

	- And 72 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* at (U+0040): B<<1211.0,287.0>-<1215.0,365.0>-<1232.0,438.0>>/B<<1232.0,438.0>-<1183.0,310.0>-<1124.5,201.5>> = 7.83826238879679

	* r (U+0072): L<<456.0,924.0>--<449.0,848.0>>/B<<449.0,848.0>-<471.0,918.0>-<519.5,984.0>> = 12.18479302368706

	* racute (U+0155): L<<456.0,924.0>--<449.0,848.0>>/B<<449.0,848.0>-<471.0,918.0>-<519.5,984.0>> = 12.18479302368706

	* rcaron (U+0159): L<<456.0,924.0>--<449.0,848.0>>/B<<449.0,848.0>-<471.0,918.0>-<519.5,984.0>> = 12.18479302368706

	* uni0157 (U+0157): L<<456.0,924.0>--<449.0,848.0>>/B<<449.0,848.0>-<471.0,918.0>-<519.5,984.0>> = 12.18479302368706

	* uni0211 (U+0211): L<<456.0,924.0>--<449.0,848.0>>/B<<449.0,848.0>-<471.0,918.0>-<519.5,984.0>> = 12.18479302368706

	* uni0213 (U+0213): L<<456.0,924.0>--<449.0,848.0>>/B<<449.0,848.0>-<471.0,918.0>-<519.5,984.0>> = 12.18479302368706

	* uni0431 (U+0431): B<<372.0,1070.0>-<299.0,943.0>-<266.0,725.0>>/B<<266.0,725.0>-<302.0,821.0>-<367.5,902.0>> = 11.94818284587733

	* uni0510 (U+0510): B<<199.0,673.5>-<307.0,777.0>-<514.0,785.0>>/B<<514.0,785.0>-<366.0,804.0>-<278.0,900.5>> = 9.528753480792071

	* uni1E5B (U+1E5B): L<<456.0,924.0>--<449.0,848.0>>/B<<449.0,848.0>-<471.0,918.0>-<519.5,984.0>> = 12.18479302368706 

	* And uni1E5F (U+1E5F): L<<456.0,924.0>--<449.0,848.0>>/B<<449.0,848.0>-<471.0,918.0>-<519.5,984.0>> = 12.18479302368706 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[14] Merriweather-Bold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
* ⚠ **WARN** GF_Latin_Minorities is almost fulfilled. Missing codepoints:

	- 0xA78B (LATIN CAPITAL LETTER SALTILLO)
 

	- And 0xA78C (LATIN SMALL LETTER SALTILLO)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Arabic is almost fulfilled. Missing codepoints:

	- 0x1E34 (LATIN CAPITAL LETTER K WITH LINE BELOW)


	- 0x1E35 (LATIN SMALL LETTER K WITH LINE BELOW)


	- 0x1E96 (LATIN SMALL LETTER H WITH LINE BELOW)
 

	- And 0x02BD (MODIFIER LETTER REVERSED COMMA)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 625, but got 606 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=14] [code: http-in-license-info]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* quotedblleft.ss01
	* uni25FC
	* uni03060301.case
	* uni04ED
	* quotereversed.ss01
	* one
	* quotedblbase.ss01
	* uni04F6
	* uni0495
	* uni0525 and 212 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Name table strings must not contain the string 'Reserved Font Name'. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/rfn">com.google.fonts/check/name/rfn</a>)</summary><div>


* ⚠ **WARN** Name table entry contains "Reserved Font Name" for a family name ("Merriweather") that differs from the currently used family name (Merriweather), which is fine. [code: legacy-familyname]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- quoteright.001

	- figuredash.case

	- ij_acutecomb

	- i.dot

	- I.uc

	- IJ_acutecomb

	- ij_acutecomb.ss02

	- ij.ss02 

	- And five.001
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 4	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2 

	- And 45 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* B (U+0042): B<<1156.5,914.0>-<1067.0,815.0>-<926.0,793.0>>/B<<926.0,793.0>-<1120.0,795.0>-<1234.0,704.0>> = 8.277605618560903

	* at (U+0040): B<<1239.0,157.0>-<1234.0,239.0>-<1269.0,437.0>>/B<<1269.0,437.0>-<1226.0,321.0>-<1166.5,214.5>> = 10.314735316705564

	* three (U+0033): B<<766.5,866.0>-<678.0,812.0>-<581.0,778.0>>/B<<581.0,778.0>-<714.0,790.0>-<818.0,754.0>> = 14.160768502097877

	* threeeighths (U+215C): B<<606.5,1208.5>-<523.0,1140.0>-<408.0,1107.0>>/B<<408.0,1107.0>-<517.0,1122.0>-<589.5,1097.5>> = 8.175652372319918

	* threequarters (U+00BE): B<<606.5,1208.5>-<523.0,1140.0>-<408.0,1107.0>>/B<<408.0,1107.0>-<517.0,1122.0>-<589.5,1097.5>> = 8.175652372319918

	* uni00B3 (U+00B3): B<<606.5,1428.5>-<523.0,1360.0>-<408.0,1327.0>>/B<<408.0,1327.0>-<517.0,1342.0>-<589.5,1317.5>> = 8.175652372319918

	* uni0412 (U+0412): B<<1156.5,914.0>-<1067.0,815.0>-<926.0,793.0>>/B<<926.0,793.0>-<1120.0,795.0>-<1234.0,704.0>> = 8.277605618560903

	* uni0417 (U+0417): B<<893.0,842.0>-<809.0,798.0>-<728.0,784.0>>/B<<728.0,784.0>-<932.0,775.0>-<1046.5,677.5>> = 12.332209671516617

	* uni0498 (U+0498): B<<893.0,842.0>-<809.0,798.0>-<728.0,784.0>>/B<<728.0,784.0>-<932.0,775.0>-<1046.5,677.5>> = 12.332209671516617

	* uni04DE (U+04DE): B<<893.0,842.0>-<809.0,798.0>-<728.0,784.0>>/B<<728.0,784.0>-<932.0,775.0>-<1046.5,677.5>> = 12.332209671516617 

	* And 9 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* A (U+0041): L<<-27.0,0.0>--<-28.0,119.0>>

	* Aacute (U+00C1): L<<-27.0,0.0>--<-28.0,119.0>>

	* Abreve (U+0102): L<<-27.0,0.0>--<-28.0,119.0>>

	* Acircumflex (U+00C2): L<<-27.0,0.0>--<-28.0,119.0>>

	* Adieresis (U+00C4): L<<-27.0,0.0>--<-28.0,119.0>>

	* Agrave (U+00C0): L<<-27.0,0.0>--<-28.0,119.0>>

	* Amacron (U+0100): L<<-27.0,0.0>--<-28.0,119.0>>

	* Aogonek (U+0104): L<<-27.0,0.0>--<-28.0,119.0>>

	* Aring (U+00C5): L<<-27.0,0.0>--<-28.0,119.0>>

	* Aringacute (U+01FA): L<<-27.0,0.0>--<-28.0,119.0>> 

	* And 111 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[14] Merriweather-LightItalic.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
* ⚠ **WARN** GF_Latin_Minorities is almost fulfilled. Missing codepoints:

	- 0xA78B (LATIN CAPITAL LETTER SALTILLO)
 

	- And 0xA78C (LATIN SMALL LETTER SALTILLO)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Arabic is almost fulfilled. Missing codepoints:

	- 0x1E34 (LATIN CAPITAL LETTER K WITH LINE BELOW)


	- 0x1E35 (LATIN SMALL LETTER K WITH LINE BELOW)


	- 0x1E96 (LATIN SMALL LETTER H WITH LINE BELOW)
 

	- And 0x02BD (MODIFIER LETTER REVERSED COMMA)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 625, but got 606 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=14] [code: http-in-license-info]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* quotedblleft.ss01
	* uni25FC
	* Acircumflex
	* bracketleft
	* ntilde
	* uni04ED
	* six.lf
	* quotereversed.ss01
	* one
	* uni0424.loclBGR and 217 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Name table strings must not contain the string 'Reserved Font Name'. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/rfn">com.google.fonts/check/name/rfn</a>)</summary><div>


* ⚠ **WARN** Name table entry contains "Reserved Font Name" for a family name ("Merriweather") that differs from the currently used family name (Merriweather), which is fine. [code: legacy-familyname]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- logicalnot.case

	- notequal.case

	- infinity.case

	- emptyset.case

	- minus.case

	- greaterequal.case

	- figuredash.case

	- ij_acutecomb

	- uni2236.case

	- i.dot 

	- And 13 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2 

	- And 66 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Q (U+0051): L<<525.0,-18.0>--<538.0,-17.0>>/B<<538.0,-17.0>-<396.0,0.0>-<300.5,86.0>> = 11.225567693469172

	* at (U+0040): B<<1158.5,276.0>-<1170.0,354.0>-<1192.0,444.0>>/B<<1192.0,444.0>-<1160.0,365.0>-<1117.0,281.0>> = 8.314794413454118

	* threeeighths (U+215C): B<<591.5,1193.0>-<533.0,1150.0>-<470.0,1127.0>>/B<<470.0,1127.0>-<582.0,1140.0>-<650.0,1095.0>> = 13.435318654260453

	* threequarters (U+00BE): B<<591.5,1193.0>-<533.0,1150.0>-<470.0,1127.0>>/B<<470.0,1127.0>-<582.0,1140.0>-<650.0,1095.0>> = 13.435318654260453

	* uni00B3 (U+00B3): B<<621.5,1413.0>-<563.0,1370.0>-<500.0,1347.0>>/B<<500.0,1347.0>-<612.0,1360.0>-<680.0,1315.0>> = 13.435318654260453

	* uni0431 (U+0431): B<<320.0,1052.0>-<265.0,930.0>-<226.0,733.0>>/B<<226.0,733.0>-<267.0,828.0>-<332.5,908.0>> = 12.145984164623489

	* uni051A (U+051A): L<<525.0,-18.0>--<538.0,-17.0>>/B<<538.0,-17.0>-<396.0,0.0>-<300.5,86.0>> = 11.225567693469172

	* uni2083 (U+2083): B<<464.5,272.0>-<406.0,229.0>-<343.0,206.0>>/B<<343.0,206.0>-<455.0,219.0>-<523.0,174.0>> = 13.435318654260453

	* uni2153 (U+2153): B<<1592.5,568.0>-<1534.0,525.0>-<1471.0,502.0>>/B<<1471.0,502.0>-<1583.0,515.0>-<1651.0,470.0>> = 13.435318654260453 

	* And uni2154 (U+2154): B<<1658.5,568.0>-<1600.0,525.0>-<1537.0,502.0>>/B<<1537.0,502.0>-<1649.0,515.0>-<1717.0,470.0>> = 13.435318654260453 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[14] Merriweather-BlackItalic.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
* ⚠ **WARN** GF_Latin_Minorities is almost fulfilled. Missing codepoints:

	- 0xA78B (LATIN CAPITAL LETTER SALTILLO)
 

	- And 0xA78C (LATIN SMALL LETTER SALTILLO)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Arabic is almost fulfilled. Missing codepoints:

	- 0x1E34 (LATIN CAPITAL LETTER K WITH LINE BELOW)


	- 0x1E35 (LATIN SMALL LETTER K WITH LINE BELOW)


	- 0x1E96 (LATIN SMALL LETTER H WITH LINE BELOW)
 

	- And 0x02BD (MODIFIER LETTER REVERSED COMMA)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 625, but got 606 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=14] [code: http-in-license-info]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* quotedblleft.ss01
	* uni25FC
	* uni03060301.case
	* bracketleft
	* Ohungarumlaut
	* uni1ECD
	* ntilde
	* uni03020309.case
	* uni04ED
	* six.lf and 349 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Name table strings must not contain the string 'Reserved Font Name'. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/rfn">com.google.fonts/check/name/rfn</a>)</summary><div>


* ⚠ **WARN** Name table entry contains "Reserved Font Name" for a family name ("Merriweather") that differs from the currently used family name (Merriweather), which is fine. [code: legacy-familyname]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- logicalnot.case

	- notequal.case

	- infinity.case

	- emptyset.case

	- minus.case

	- greaterequal.case

	- figuredash.case

	- ij_acutecomb

	- uni2236.case

	- i.dot 

	- And 13 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: B	Contours detected: 4	Expected: 2 or 3

	- Glyph name: D	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: Eth	Contours detected: 4	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcaron	Contours detected: 4	Expected: 3

	- Glyph name: Dcroat	Contours detected: 4	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1 

	- And 90 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* B (U+0042): B<<1231.0,925.5>-<1139.0,829.0>-<953.0,784.0>>/B<<953.0,784.0>-<1064.0,787.0>-<1143.5,745.5>> = 12.052384817680782

	* Q (U+0051): B<<1061.0,109.5>-<946.0,25.0>-<790.0,-5.0>>/L<<790.0,-5.0>--<801.0,-4.0>> = 5.691098146923909

	* at (U+0040): B<<1236.0,341.0>-<1239.0,392.0>-<1249.0,436.0>>/B<<1249.0,436.0>-<1198.0,297.0>-<1141.0,189.5>> = 7.344148075001017

	* r (U+0072): L<<484.0,919.0>--<479.0,846.0>>/B<<479.0,846.0>-<501.0,923.0>-<546.5,989.0>> = 12.027147036855423

	* racute (U+0155): L<<484.0,919.0>--<479.0,846.0>>/B<<479.0,846.0>-<501.0,923.0>-<546.5,989.0>> = 12.027147036855423

	* rcaron (U+0159): L<<484.0,919.0>--<479.0,846.0>>/B<<479.0,846.0>-<501.0,923.0>-<546.5,989.0>> = 12.027147036855423

	* uni0157 (U+0157): L<<484.0,919.0>--<479.0,846.0>>/B<<479.0,846.0>-<501.0,923.0>-<546.5,989.0>> = 12.027147036855423

	* uni0211 (U+0211): L<<484.0,919.0>--<479.0,846.0>>/B<<479.0,846.0>-<501.0,923.0>-<546.5,989.0>> = 12.027147036855423

	* uni0213 (U+0213): L<<484.0,919.0>--<479.0,846.0>>/B<<479.0,846.0>-<501.0,923.0>-<546.5,989.0>> = 12.027147036855423

	* uni0412 (U+0412): B<<1231.0,925.5>-<1139.0,829.0>-<953.0,784.0>>/B<<953.0,784.0>-<1064.0,787.0>-<1143.5,745.5>> = 12.052384817680782 

	* And 11 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[14] Merriweather-Italic.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
* ⚠ **WARN** GF_Latin_Minorities is almost fulfilled. Missing codepoints:

	- 0xA78B (LATIN CAPITAL LETTER SALTILLO)
 

	- And 0xA78C (LATIN SMALL LETTER SALTILLO)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Arabic is almost fulfilled. Missing codepoints:

	- 0x1E34 (LATIN CAPITAL LETTER K WITH LINE BELOW)


	- 0x1E35 (LATIN SMALL LETTER K WITH LINE BELOW)


	- 0x1E96 (LATIN SMALL LETTER H WITH LINE BELOW)
 

	- And 0x02BD (MODIFIER LETTER REVERSED COMMA)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 625, but got 606 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=14] [code: http-in-license-info]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* quotedblleft.ss01
	* uni25FC
	* uni043D.loclBGR
	* bracketleft
	* uni04ED
	* Iogonek
	* six.lf
	* quotereversed.ss01
	* one
	* uni01F2 and 293 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Name table strings must not contain the string 'Reserved Font Name'. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/rfn">com.google.fonts/check/name/rfn</a>)</summary><div>


* ⚠ **WARN** Name table entry contains "Reserved Font Name" for a family name ("Merriweather") that differs from the currently used family name (Merriweather), which is fine. [code: legacy-familyname]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- logicalnot.case

	- notequal.case

	- infinity.case

	- emptyset.case

	- minus.case

	- greaterequal.case

	- figuredash.case

	- ij_acutecomb

	- uni2236.case

	- i.dot 

	- And 13 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2 

	- And 66 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* at (U+0040): B<<1182.0,281.0>-<1190.0,359.0>-<1210.0,441.0>>/B<<1210.0,441.0>-<1176.0,355.0>-<1133.5,270.0>> = 7.864346187174729

	* r (U+0072): L<<421.0,931.0>--<411.0,851.0>>/B<<411.0,851.0>-<434.0,912.0>-<485.5,977.5>> = 13.533893714405663

	* racute (U+0155): L<<421.0,931.0>--<411.0,851.0>>/B<<411.0,851.0>-<434.0,912.0>-<485.5,977.5>> = 13.533893714405663

	* rcaron (U+0159): L<<421.0,931.0>--<411.0,851.0>>/B<<411.0,851.0>-<434.0,912.0>-<485.5,977.5>> = 13.533893714405663

	* threeeighths (U+215C): B<<601.0,1194.0>-<540.0,1150.0>-<478.0,1127.0>>/B<<478.0,1127.0>-<589.0,1140.0>-<660.5,1094.0>> = 13.67334308484625

	* threequarters (U+00BE): B<<601.0,1194.0>-<540.0,1150.0>-<478.0,1127.0>>/B<<478.0,1127.0>-<589.0,1140.0>-<660.5,1094.0>> = 13.67334308484625

	* uni00B3 (U+00B3): B<<631.0,1414.0>-<570.0,1370.0>-<508.0,1347.0>>/B<<508.0,1347.0>-<619.0,1360.0>-<690.5,1314.0>> = 13.67334308484625

	* uni0157 (U+0157): L<<421.0,931.0>--<411.0,851.0>>/B<<411.0,851.0>-<434.0,912.0>-<485.5,977.5>> = 13.533893714405663

	* uni0211 (U+0211): L<<421.0,931.0>--<411.0,851.0>>/B<<411.0,851.0>-<434.0,912.0>-<485.5,977.5>> = 13.533893714405663

	* uni0213 (U+0213): L<<421.0,931.0>--<411.0,851.0>>/B<<411.0,851.0>-<434.0,912.0>-<485.5,977.5>> = 13.533893714405663 

	* And 7 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[14] Merriweather-Black.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
* ⚠ **WARN** GF_Latin_Minorities is almost fulfilled. Missing codepoints:

	- 0xA78B (LATIN CAPITAL LETTER SALTILLO)
 

	- And 0xA78C (LATIN SMALL LETTER SALTILLO)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Arabic is almost fulfilled. Missing codepoints:

	- 0x1E34 (LATIN CAPITAL LETTER K WITH LINE BELOW)


	- 0x1E35 (LATIN SMALL LETTER K WITH LINE BELOW)


	- 0x1E96 (LATIN SMALL LETTER H WITH LINE BELOW)
 

	- And 0x02BD (MODIFIER LETTER REVERSED COMMA)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 625, but got 606 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=14] [code: http-in-license-info]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* quotedblleft.ss01
	* uni25FC
	* uni03060301.case
	* Ohungarumlaut
	* uni1ECD
	* ntilde
	* uni03020309.case
	* uni04ED
	* uni0401
	* six.lf and 280 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Name table strings must not contain the string 'Reserved Font Name'. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/rfn">com.google.fonts/check/name/rfn</a>)</summary><div>


* ⚠ **WARN** Name table entry contains "Reserved Font Name" for a family name ("Merriweather") that differs from the currently used family name (Merriweather), which is fine. [code: legacy-familyname]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- quoteright.001

	- figuredash.case

	- ij_acutecomb

	- i.dot

	- I.uc

	- IJ_acutecomb

	- ij_acutecomb.ss02

	- ij.ss02 

	- And five.001
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 4	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2 

	- And 55 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* B (U+0042): B<<1125.0,854.5>-<1050.0,807.0>-<957.0,794.0>>/B<<957.0,794.0>-<1154.0,794.0>-<1270.5,705.5>> = 7.957525226917127

	* at (U+0040): B<<1267.0,268.5>-<1275.0,336.0>-<1293.0,438.0>>/B<<1293.0,438.0>-<1251.0,322.0>-<1191.5,215.0>> = 9.895769735866496

	* three (U+0033): B<<776.0,859.0>-<687.0,804.0>-<587.0,769.0>>/B<<587.0,769.0>-<719.0,781.0>-<824.5,747.0>> = 14.095617311453914

	* threeeighths (U+215C): B<<621.0,1206.0>-<542.0,1137.0>-<423.0,1103.0>>/B<<423.0,1103.0>-<582.0,1118.0>-<663.5,1056.0>> = 10.55608414094943

	* threequarters (U+00BE): B<<621.0,1206.0>-<542.0,1137.0>-<423.0,1103.0>>/B<<423.0,1103.0>-<582.0,1118.0>-<663.5,1056.0>> = 10.55608414094943

	* uni00B3 (U+00B3): B<<621.0,1426.0>-<542.0,1357.0>-<423.0,1323.0>>/B<<423.0,1323.0>-<582.0,1338.0>-<663.5,1276.0>> = 10.55608414094943

	* uni040E (U+040E): B<<579.0,412.0>-<578.0,428.0>-<574.0,444.0>>/L<<574.0,444.0>--<579.0,412.0>> = 5.15558431740624

	* uni040E (U+040E): L<<574.0,444.0>--<579.0,412.0>>/B<<579.0,412.0>-<578.0,428.0>-<574.0,444.0>> = 5.304324775522795

	* uni0412 (U+0412): B<<1125.0,854.5>-<1050.0,807.0>-<957.0,794.0>>/B<<957.0,794.0>-<1154.0,794.0>-<1270.5,705.5>> = 7.957525226917127

	* uni0417 (U+0417): B<<933.0,842.0>-<848.0,799.0>-<764.0,784.0>>/B<<764.0,784.0>-<970.0,774.0>-<1085.5,680.0>> = 12.903838519469893 

	* And 19 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* Ccedilla (U+00C7): L<<486.0,-484.0>--<487.0,-299.0>>

	* Lcaron (U+013D): L<<1114.0,1177.0>--<947.0,1178.0>>

	* Scedilla (U+015E): L<<358.0,-484.0>--<359.0,-299.0>>

	* Thorn (U+00DE): L<<744.0,1487.0>--<745.0,1349.0>>

	* arrowright (U+2192): L<<51.0,655.0>--<50.0,875.0>>

	* ccedilla (U+00E7): L<<297.0,-484.0>--<298.0,-299.0>>

	* cedilla (U+00B8): L<<180.0,-484.0>--<181.0,-299.0>>

	* dcaron (U+010F): L<<1376.0,1176.0>--<1209.0,1177.0>>

	* dollar (U+0024): L<<583.0,-252.0>--<585.0,-20.0>>

	* dollar (U+0024): L<<760.0,-16.0>--<758.0,-252.0>> 

	* And 77 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[14] Merriweather-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
* ⚠ **WARN** GF_Latin_Minorities is almost fulfilled. Missing codepoints:

	- 0xA78B (LATIN CAPITAL LETTER SALTILLO)
 

	- And 0xA78C (LATIN SMALL LETTER SALTILLO)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Arabic is almost fulfilled. Missing codepoints:

	- 0x1E34 (LATIN CAPITAL LETTER K WITH LINE BELOW)


	- 0x1E35 (LATIN SMALL LETTER K WITH LINE BELOW)


	- 0x1E96 (LATIN SMALL LETTER H WITH LINE BELOW)
 

	- And 0x02BD (MODIFIER LETTER REVERSED COMMA)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 625, but got 606 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=14] [code: http-in-license-info]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* quotedblleft.ss01
	* uni25FC
	* uni03060301.case
	* uni01CD
	* uni1EA6
	* quotereversed.ss01
	* one
	* quotedblbase.ss01
	* uni04FB
	* uni050A and 151 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Name table strings must not contain the string 'Reserved Font Name'. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/rfn">com.google.fonts/check/name/rfn</a>)</summary><div>


* ⚠ **WARN** Name table entry contains "Reserved Font Name" for a family name ("Merriweather") that differs from the currently used family name (Merriweather), which is fine. [code: legacy-familyname]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- quoteright.001

	- figuredash.case

	- ij_acutecomb

	- i.dot

	- I.uc

	- IJ_acutecomb

	- ij_acutecomb.ss02

	- ij.ss02 

	- And five.001
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 4	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2 

	- And 45 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* B (U+0042): B<<1100.0,921.5>-<1019.0,819.0>-<875.0,793.0>>/B<<875.0,793.0>-<1067.0,797.0>-<1176.0,702.0>> = 9.041313339441118

	* at (U+0040): B<<1206.5,265.5>-<1213.0,335.0>-<1231.0,435.0>>/B<<1231.0,435.0>-<1188.0,321.0>-<1127.0,215.0>> = 10.46214970922158

	* three (U+0033): B<<751.5,877.5>-<665.0,824.0>-<570.0,791.0>>/B<<570.0,791.0>-<707.0,803.0>-<808.0,765.0>> = 14.149779892488562

	* threeeighths (U+215C): B<<522.5,1171.5>-<456.0,1134.0>-<383.0,1113.0>>/B<<383.0,1113.0>-<497.0,1136.0>-<571.5,1113.5>> = 4.642452208560689

	* threequarters (U+00BE): B<<522.5,1171.5>-<456.0,1134.0>-<383.0,1113.0>>/B<<383.0,1113.0>-<497.0,1136.0>-<571.5,1113.5>> = 4.642452208560689

	* uni00B3 (U+00B3): B<<522.5,1391.5>-<456.0,1354.0>-<383.0,1333.0>>/B<<383.0,1333.0>-<497.0,1356.0>-<571.5,1333.5>> = 4.642452208560689

	* uni0412 (U+0412): B<<1100.0,921.5>-<1019.0,819.0>-<875.0,793.0>>/B<<875.0,793.0>-<1067.0,797.0>-<1176.0,702.0>> = 9.041313339441118

	* uni0417 (U+0417): B<<789.0,821.5>-<727.0,794.0>-<670.0,784.0>>/B<<670.0,784.0>-<871.0,777.0>-<983.5,674.0>> = 11.945195989193437

	* uni0498 (U+0498): B<<789.0,821.5>-<727.0,794.0>-<670.0,784.0>>/B<<670.0,784.0>-<871.0,777.0>-<983.5,674.0>> = 11.945195989193437

	* uni04DE (U+04DE): B<<789.0,821.5>-<727.0,794.0>-<670.0,784.0>>/B<<670.0,784.0>-<871.0,777.0>-<983.5,674.0>> = 11.945195989193437 

	* And 9 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* Eng (U+014A): L<<1219.0,300.0>--<1218.0,1362.0>>

	* Eng (U+014A): L<<1353.0,1362.0>--<1359.0,306.0>>

	* Lcaron (U+013D): L<<1014.0,1196.0>--<898.0,1197.0>>

	* arrowleft (U+2190): L<<1341.0,831.0>--<1340.0,674.0>>

	* asterisk (U+002A): L<<743.0,621.0>--<556.0,620.0>>

	* copyright (U+00A9): L<<1355.0,1403.0>--<1354.0,1181.0>>

	* dcaron (U+010F): L<<1263.0,1196.0>--<1147.0,1197.0>>

	* dollar (U+0024): L<<577.0,-252.0>--<579.0,-20.0>>

	* dollar (U+0024): L<<718.0,-19.0>--<716.0,-252.0>>

	* h (U+0068): L<<421.0,1608.0>--<422.0,1144.0>> 

	* And 77 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[14] Merriweather-Light.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
* ⚠ **WARN** GF_Latin_Minorities is almost fulfilled. Missing codepoints:

	- 0xA78B (LATIN CAPITAL LETTER SALTILLO)
 

	- And 0xA78C (LATIN SMALL LETTER SALTILLO)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Arabic is almost fulfilled. Missing codepoints:

	- 0x1E34 (LATIN CAPITAL LETTER K WITH LINE BELOW)


	- 0x1E35 (LATIN SMALL LETTER K WITH LINE BELOW)


	- 0x1E96 (LATIN SMALL LETTER H WITH LINE BELOW)
 

	- And 0x02BD (MODIFIER LETTER REVERSED COMMA)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 625, but got 606 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=14] [code: http-in-license-info]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* quotedblleft.ss01
	* uni25FC
	* Acircumflex
	* uni01CD
	* uni1EA6
	* quotereversed.ss01
	* one
	* quotedblbase.ss01
	* asciicircum
	* uni04FB and 147 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Name table strings must not contain the string 'Reserved Font Name'. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/rfn">com.google.fonts/check/name/rfn</a>)</summary><div>


* ⚠ **WARN** Name table entry contains "Reserved Font Name" for a family name ("Merriweather") that differs from the currently used family name (Merriweather), which is fine. [code: legacy-familyname]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- quoteright.001

	- figuredash.case

	- ij_acutecomb

	- i.dot

	- I.uc

	- IJ_acutecomb

	- ij_acutecomb.ss02

	- ij.ss02 

	- And five.001
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 4	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2 

	- And 45 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* B (U+0042): B<<1064.0,926.0>-<989.0,821.0>-<843.0,792.0>>/B<<843.0,792.0>-<1034.0,798.0>-<1139.5,700.5>> = 9.435168283007993

	* at (U+0040): B<<1182.5,265.0>-<1188.0,335.0>-<1206.0,434.0>>/B<<1206.0,434.0>-<1163.0,320.0>-<1101.5,214.5>> = 10.361276962187272

	* three (U+0033): B<<742.0,884.5>-<656.0,832.0>-<564.0,800.0>>/B<<564.0,800.0>-<702.0,812.0>-<801.5,772.0>> = 14.209267297700373

	* threeeighths (U+215C): B<<505.5,1175.0>-<438.0,1138.0>-<368.0,1117.0>>/B<<368.0,1117.0>-<484.0,1145.0>-<560.0,1123.5>> = 3.1288098488320695

	* threequarters (U+00BE): B<<505.5,1175.0>-<438.0,1138.0>-<368.0,1117.0>>/B<<368.0,1117.0>-<484.0,1145.0>-<560.0,1123.5>> = 3.1288098488320695

	* uni00B3 (U+00B3): B<<505.5,1395.0>-<438.0,1358.0>-<368.0,1337.0>>/B<<368.0,1337.0>-<484.0,1365.0>-<560.0,1343.5>> = 3.1288098488320695

	* uni0412 (U+0412): B<<1064.0,926.0>-<989.0,821.0>-<843.0,792.0>>/B<<843.0,792.0>-<1034.0,798.0>-<1139.5,700.5>> = 9.435168283007993

	* uni0417 (U+0417): B<<749.0,821.5>-<688.0,794.0>-<633.0,784.0>>/B<<633.0,784.0>-<766.0,781.0>-<860.5,730.5>> = 11.59701335501595

	* uni0498 (U+0498): B<<749.0,821.5>-<688.0,794.0>-<633.0,784.0>>/B<<633.0,784.0>-<766.0,781.0>-<860.5,730.5>> = 11.59701335501595

	* uni04DE (U+04DE): B<<749.0,821.5>-<688.0,794.0>-<633.0,784.0>>/B<<633.0,784.0>-<766.0,781.0>-<860.5,730.5>> = 11.59701335501595 

	* And 9 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* Eng (U+014A): L<<1214.0,263.0>--<1212.0,1378.0>>

	* Eng (U+014A): L<<1326.0,1378.0>--<1334.0,270.0>>

	* dollar (U+0024): L<<574.0,-252.0>--<576.0,-20.0>>

	* dollar (U+0024): L<<702.0,-20.0>--<700.0,-252.0>>

	* ij (U+0133): L<<842.0,50.0>--<840.0,970.0>>

	* j (U+006A): L<<248.0,50.0>--<246.0,970.0>>

	* jcircumflex (U+0135): L<<248.0,50.0>--<246.0,970.0>>

	* peseta (U+20A7): L<<150.0,1100.0>--<287.0,1099.0>>

	* peseta (U+20A7): L<<451.0,1097.0>--<1059.0,1092.0>>

	* seveneighths (U+215E): L<<414.0,625.0>--<219.0,626.0>> 

	* And 39 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 8 | 9 | 96 | 886 | 57 | 719 | 0 |
| 0% | 1% | 5% | 50% | 3% | 41% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
