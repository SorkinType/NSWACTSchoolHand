## FontBakery report

fontbakery version: 0.9.2

<details><summary><b>[19] Nswact-Bold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 2925, but got 2642 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 945, but got 926 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* 🔥 **FAIL** Font is not italic, so post.italicAngle should be equal to zero. [code: non-zero-upright]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, cherokee, coptic
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, old-permic, malayalam, tai-le, math, canadian-aboriginal, coptic, syriac
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
 * U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
 * U+2000 EN QUAD: not included in any glyphset definition
 * U+2001 EM QUAD: not included in any glyphset definition
 * U+2003 EM SPACE: try adding nushu
 * U+2004 THREE-PER-EM SPACE: not included in any glyphset definition
 * U+2005 FOUR-PER-EM SPACE: not included in any glyphset definition
 * U+2006 SIX-PER-EM SPACE: not included in any glyphset definition
 * U+2007 FIGURE SPACE: not included in any glyphset definition
 * U+2008 PUNCTUATION SPACE: not included in any glyphset definition
 * U+200A HAIR SPACE: not included in any glyphset definition
 * U+200C ZERO WIDTH NON-JOINER: try adding one of: syloti-nagri, tibetan, khmer, pahawh-hmong, duployan, kaithi, malayalam, javanese, phags-pa, warang-citi, tai-tham, buhid, thai, khojki, mandaic, bengali, psalter-pahlavi, sharada, tirhuta, myanmar, tai-le, nko, rejang, devanagari, dogra, kayah-li, manichaean, mongolian, sundanese, telugu, yi, tagalog, hanifi-rohingya, thaana, lepcha, gujarati, oriya, hanunoo, gunjala-gondi, cham, balinese, newa, siddham, batak, brahmi, kharoshthi, avestan, syriac, tai-viet, new-tai-lue, mahajani, saurashtra, sinhala, tamil, tifinagh, tagbanwa, meetei-mayek, sogdian, hatran, grantha, takri, kannada, chakma, gurmukhi, khudawadi, modi, buginese, limbu
 * U+200D ZERO WIDTH JOINER: try adding one of: syloti-nagri, tibetan, pahawh-hmong, duployan, kaithi, malayalam, old-hungarian, javanese, phags-pa, warang-citi, tai-tham, buhid, thai, khojki, mandaic, bengali, psalter-pahlavi, sharada, tirhuta, myanmar, tai-le, nko, rejang, devanagari, dogra, kayah-li, manichaean, mongolian, sundanese, telugu, yi, tagalog, hanifi-rohingya, thaana, lepcha, gujarati, oriya, hanunoo, gunjala-gondi, cham, balinese, newa, siddham, batak, brahmi, kharoshthi, avestan, syriac, tai-viet, new-tai-lue, mahajani, saurashtra, sinhala, tamil, tifinagh, tagbanwa, meetei-mayek, grantha, takri, kannada, chakma, gurmukhi, khudawadi, modi, buginese, limbu
 * U+202F NARROW NO-BREAK SPACE: try adding one of: yi, mongolian
 * U+205F MEDIUM MATHEMATICAL SPACE: not included in any glyphset definition
 * U+2116 NUMERO SIGN: try adding cyrillic
 * U+221E INFINITY: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25CC DOTTED CIRCLE: try adding one of: malayalam, elbasan, ahom, khojki, miao, sharada, math, osage, dogra, kayah-li, tagalog, soyombo, gujarati, hanunoo, symbols, kharoshthi, syriac, sinhala, tagbanwa, gurmukhi, pahawh-hmong, modi, bassa-vah, javanese, buhid, psalter-pahlavi, manichaean, sundanese, cham, balinese, tai-viet, tirhuta, mahajani, takri, kannada, chakma, khudawadi, buginese, marchen, khmer, duployan, kaithi, old-permic, thai, bengali, tai-le, nko, mongolian, telugu, yi, masaram-gondi, thaana, adlam, bhaiksuki, gunjala-gondi, new-tai-lue, zanabazar-square, meetei-mayek, grantha, limbu, lao, syloti-nagri, tibetan, hebrew, phags-pa, myanmar, rejang, devanagari, hanifi-rohingya, mende-kikakui, lepcha, oriya, wancho, newa, siddham, batak, brahmi, caucasian-albanian, tamil, tifinagh, music, sogdian, coptic, mandaic
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.784x (3568) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- eacute.cv02

	- eacute.cv03

	- eacute.cv04

	- eacute.cv05

	- eacute.cv06

	- eacute.cv07

	- eacute.fina
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 1170 among a set of 2 math glyphs.
The following math glyphs have a different width, though:

Width = 1083:
less

Width = 1173:
equal, approxequal

Width = 1082:
greater

Width = 1089:
plusminus

Width = 1174:
notequal, multiply

Width = 1167:
divide

Width = 1111:
lessequal

Width = 1107:
greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* percent (U+0025): X=1387.0,Y=2.0 (should be at baseline 0?)

	* C (U+0043): X=1238.0,Y=2009.5 (should be at cap-height 2008?)

	* X (U+0058): X=469.0,Y=2009.0 (should be at cap-height 2008?)

	* X (U+0058): X=1449.5,Y=2007.0 (should be at cap-height 2008?)

	* X (U+0058): X=328.5,Y=2.0 (should be at baseline 0?)

	* Y (U+0059): X=393.0,Y=1.0 (should be at baseline 0?)

	* Z (U+005A): X=394.0,Y=2009.0 (should be at cap-height 2008?)

	* Z (U+005A): X=1398.0,Y=2009.0 (should be at cap-height 2008?)

	* g (U+0067): X=299.0,Y=-1.5 (should be at baseline 0?)

	* q (U+0071): X=715.5,Y=-925.0 (should be at descender -926?)

	* braceleft (U+007B): X=713.5,Y=2006.0 (should be at cap-height 2008?)

	* braceright (U+007D): X=52.5,Y=-924.0 (should be at descender -926?)

	* braceright (U+007D): X=339.5,Y=2009.5 (should be at cap-height 2008?)

	* yen (U+00A5): X=393.0,Y=1.0 (should be at baseline 0?)

	* Ccedilla (U+00C7): X=1238.0,Y=2009.5 (should be at cap-height 2008?)

	* Yacute (U+00DD): X=393.0,Y=1.0 (should be at baseline 0?)

	* Thorn (U+00DE): X=533.0,Y=2009.0 (should be at cap-height 2008?)

	* germandbls (U+00DF): X=950.0,Y=2010.0 (should be at cap-height 2008?)

	* Cacute (U+0106): X=1238.0,Y=2009.5 (should be at cap-height 2008?)

	* Ccircumflex (U+0108): X=1238.0,Y=2009.5 (should be at cap-height 2008?)

	* Cdotaccent (U+010A): X=1238.0,Y=2009.5 (should be at cap-height 2008?)

	* Ccaron (U+010C): X=1238.0,Y=2009.5 (should be at cap-height 2008?)

	* gcircumflex (U+011D): X=299.0,Y=-1.5 (should be at baseline 0?)

	* gbreve (U+011F): X=299.0,Y=-1.5 (should be at baseline 0?)

	* gdotaccent (U+0121): X=299.0,Y=-1.5 (should be at baseline 0?)

	* uni0123 (U+0123): X=299.0,Y=-1.5 (should be at baseline 0?)

	* Ycircumflex (U+0176): X=393.0,Y=1.0 (should be at baseline 0?)

	* Ydieresis (U+0178): X=393.0,Y=1.0 (should be at baseline 0?)

	* Zacute (U+0179): X=394.0,Y=2009.0 (should be at cap-height 2008?)

	* Zacute (U+0179): X=1398.0,Y=2009.0 (should be at cap-height 2008?)

	* Zdotaccent (U+017B): X=394.0,Y=2009.0 (should be at cap-height 2008?)

	* Zdotaccent (U+017B): X=1398.0,Y=2009.0 (should be at cap-height 2008?)

	* Zcaron (U+017D): X=394.0,Y=2009.0 (should be at cap-height 2008?)

	* Zcaron (U+017D): X=1398.0,Y=2009.0 (should be at cap-height 2008?)

	* uni1E21 (U+1E21): X=299.0,Y=-1.5 (should be at baseline 0?)

	* Ygrave (U+1EF2): X=393.0,Y=1.0 (should be at baseline 0?)

	* uni1EF8 (U+1EF8): X=393.0,Y=1.0 (should be at baseline 0?)

	* notequal (U+2260): X=468.5,Y=-1.5 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* dollar (U+0024) contains a short segment B<<523.0,268.0>-<540.0,268.0>-<559.0,268.0>>

	* dollar (U+0024) contains a short segment B<<559.0,268.0>-<578.0,268.0>-<598.0,269.0>>

	* ampersand (U+0026) contains a short segment B<<1110.0,700.0>-<1118.0,713.0>-<1126.0,726.0>>

	* ampersand (U+0026) contains a short segment B<<1126.0,726.0>-<1134.0,739.0>-<1141.0,752.0>>

	* asterisk (U+002A) contains a short segment L<<440.0,1331.0>--<425.0,1321.0>>

	* asterisk (U+002A) contains a short segment L<<775.0,1865.0>--<787.0,1873.0>>

	* at (U+0040) contains a short segment B<<1204.0,122.0>-<1188.0,151.0>-<1180.0,184.0>>

	* at (U+0040) contains a short segment B<<1442.0,338.5>-<1444.0,286.0>-<1473.0,286.0>>

	* at (U+0040) contains a short segment B<<1242.0,-82.0>-<1266.0,-113.0>-<1273.0,-147.0>>

	* at (U+0040) contains a short segment B<<1273.0,-147.0>-<1280.0,-181.0>-<1255.0,-220.5>>

	* K (U+004B) contains a short segment B<<1514.0,174.5>-<1523.0,148.0>-<1523.0,125.0>>

	* W (U+0057) contains a short segment B<<2604.5,1906.0>-<2615.0,1864.0>-<2599.0,1826.0>>

	* p (U+0070) contains a short segment L<<457.0,252.0>--<461.0,252.0>>

	* v (U+0076) contains a short segment B<<470.0,256.0>-<475.0,237.0>-<488.0,237.0>>

	* cent (U+00A2) contains a short segment L<<394.0,-20.0>--<381.0,-20.0>>

	* cent (U+00A2) contains a short segment B<<622.0,497.0>-<623.0,502.0>-<623.0,500.0>>

	* yen (U+00A5) contains a short segment L<<360.0,362.0>--<355.0,362.0>>

	* yen (U+00A5) contains a short segment L<<644.0,1030.0>--<643.0,1032.0>>

	* yen (U+00A5) contains a short segment L<<1120.0,1023.0>--<1123.0,1023.0>>

	* Oslash (U+00D8) contains a short segment L<<649.0,-20.0>--<649.0,-20.0>>

	* ae (U+00E6) contains a short segment B<<971.0,388.5>-<970.0,375.0>-<969.0,364.0>>

	* thorn (U+00FE) contains a short segment L<<461.0,252.0>--<465.0,252.0>>

	* uni0136 (U+0136) contains a short segment B<<1514.0,174.5>-<1523.0,148.0>-<1523.0,125.0>>

	* lslash (U+0142) contains a short segment L<<549.0,1103.0>--<563.0,1108.0>>

	* Wcircumflex (U+0174) contains a short segment B<<2604.5,1906.0>-<2615.0,1864.0>-<2599.0,1826.0>>

	* Wgrave (U+1E80) contains a short segment B<<2604.5,1906.0>-<2615.0,1864.0>-<2599.0,1826.0>>

	* Wacute (U+1E82) contains a short segment B<<2604.5,1906.0>-<2615.0,1864.0>-<2599.0,1826.0>>

	* Wdieresis (U+1E84) contains a short segment B<<2604.5,1906.0>-<2615.0,1864.0>-<2599.0,1826.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<829.0,0.0>-<807.0,1.0>-<771.0,11.5>>

	* Euro (U+20AC) contains a short segment B<<486.0,1059.0>-<488.0,1070.0>-<489.5,1080.0>>

	* Euro (U+20AC) contains a short segment B<<489.5,1080.0>-<491.0,1090.0>-<492.0,1100.0>>

	* notequal (U+2260) contains a short segment L<<927.0,1030.0>--<953.0,1030.0>>

	* lessequal (U+2264) contains a short segment L<<273.0,624.0>--<273.0,626.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* A (U+0041): L<<1017.0,1082.0>--<989.0,1455.0>> -> L<<989.0,1455.0>--<973.0,1644.0>>

	* A (U+0041): L<<973.0,1644.0>--<905.0,1459.0>> -> L<<905.0,1459.0>--<769.0,1082.0>>

	* Aacute (U+00C1): L<<1017.0,1082.0>--<989.0,1455.0>> -> L<<989.0,1455.0>--<973.0,1644.0>>

	* Aacute (U+00C1): L<<973.0,1644.0>--<905.0,1459.0>> -> L<<905.0,1459.0>--<769.0,1082.0>>

	* Abreve (U+0102): L<<1017.0,1082.0>--<989.0,1455.0>> -> L<<989.0,1455.0>--<973.0,1644.0>>

	* Abreve (U+0102): L<<973.0,1644.0>--<905.0,1459.0>> -> L<<905.0,1459.0>--<769.0,1082.0>>

	* Acircumflex (U+00C2): L<<1017.0,1082.0>--<989.0,1455.0>> -> L<<989.0,1455.0>--<973.0,1644.0>>

	* Acircumflex (U+00C2): L<<973.0,1644.0>--<905.0,1459.0>> -> L<<905.0,1459.0>--<769.0,1082.0>>

	* Adieresis (U+00C4): L<<1017.0,1082.0>--<989.0,1455.0>> -> L<<989.0,1455.0>--<973.0,1644.0>>

	* Adieresis (U+00C4): L<<973.0,1644.0>--<905.0,1459.0>> -> L<<905.0,1459.0>--<769.0,1082.0>>

	* Agrave (U+00C0): L<<1017.0,1082.0>--<989.0,1455.0>> -> L<<989.0,1455.0>--<973.0,1644.0>>

	* Agrave (U+00C0): L<<973.0,1644.0>--<905.0,1459.0>> -> L<<905.0,1459.0>--<769.0,1082.0>>

	* Amacron (U+0100): L<<1017.0,1082.0>--<989.0,1455.0>> -> L<<989.0,1455.0>--<973.0,1644.0>>

	* Amacron (U+0100): L<<973.0,1644.0>--<905.0,1459.0>> -> L<<905.0,1459.0>--<769.0,1082.0>>

	* Aogonek (U+0104): L<<1017.0,1082.0>--<989.0,1455.0>> -> L<<989.0,1455.0>--<973.0,1644.0>>

	* Aogonek (U+0104): L<<973.0,1644.0>--<905.0,1459.0>> -> L<<905.0,1459.0>--<769.0,1082.0>>

	* Aring (U+00C5): L<<1017.0,1082.0>--<989.0,1455.0>> -> L<<989.0,1455.0>--<973.0,1644.0>>

	* Aring (U+00C5): L<<973.0,1644.0>--<905.0,1459.0>> -> L<<905.0,1459.0>--<769.0,1082.0>>

	* Atilde (U+00C3): L<<1017.0,1082.0>--<989.0,1455.0>> -> L<<989.0,1455.0>--<973.0,1644.0>>

	* Atilde (U+00C3): L<<973.0,1644.0>--<905.0,1459.0>> -> L<<905.0,1459.0>--<769.0,1082.0>>

	* W (U+0057): L<<1379.0,1431.0>--<1327.0,1272.0>> -> L<<1327.0,1272.0>--<895.0,133.0>>

	* W (U+0057): L<<1572.0,99.0>--<1395.0,1272.0>> -> L<<1395.0,1272.0>--<1379.0,1431.0>>

	* W (U+0057): L<<1606.0,1886.0>--<1754.0,853.0>> -> L<<1754.0,853.0>--<1783.0,596.0>>

	* W (U+0057): L<<1783.0,596.0>--<1879.0,853.0>> -> L<<1879.0,853.0>--<2297.0,1904.0>>

	* W (U+0057): L<<563.0,1886.0>--<706.0,866.0>> -> L<<706.0,866.0>--<745.0,555.0>>

	* W (U+0057): L<<745.0,555.0>--<854.0,856.0>> -> L<<854.0,856.0>--<1252.0,1891.0>>

	* Wacute (U+1E82): L<<1379.0,1431.0>--<1327.0,1272.0>> -> L<<1327.0,1272.0>--<895.0,133.0>>

	* Wacute (U+1E82): L<<1572.0,99.0>--<1395.0,1272.0>> -> L<<1395.0,1272.0>--<1379.0,1431.0>>

	* Wacute (U+1E82): L<<1606.0,1886.0>--<1754.0,853.0>> -> L<<1754.0,853.0>--<1783.0,596.0>>

	* Wacute (U+1E82): L<<1783.0,596.0>--<1879.0,853.0>> -> L<<1879.0,853.0>--<2297.0,1904.0>>

	* Wacute (U+1E82): L<<563.0,1886.0>--<706.0,866.0>> -> L<<706.0,866.0>--<745.0,555.0>>

	* Wacute (U+1E82): L<<745.0,555.0>--<854.0,856.0>> -> L<<854.0,856.0>--<1252.0,1891.0>>

	* Wcircumflex (U+0174): L<<1379.0,1431.0>--<1327.0,1272.0>> -> L<<1327.0,1272.0>--<895.0,133.0>>

	* Wcircumflex (U+0174): L<<1572.0,99.0>--<1395.0,1272.0>> -> L<<1395.0,1272.0>--<1379.0,1431.0>>

	* Wcircumflex (U+0174): L<<1606.0,1886.0>--<1754.0,853.0>> -> L<<1754.0,853.0>--<1783.0,596.0>>

	* Wcircumflex (U+0174): L<<1783.0,596.0>--<1879.0,853.0>> -> L<<1879.0,853.0>--<2297.0,1904.0>>

	* Wcircumflex (U+0174): L<<563.0,1886.0>--<706.0,866.0>> -> L<<706.0,866.0>--<745.0,555.0>>

	* Wcircumflex (U+0174): L<<745.0,555.0>--<854.0,856.0>> -> L<<854.0,856.0>--<1252.0,1891.0>>

	* Wdieresis (U+1E84): L<<1379.0,1431.0>--<1327.0,1272.0>> -> L<<1327.0,1272.0>--<895.0,133.0>>

	* Wdieresis (U+1E84): L<<1572.0,99.0>--<1395.0,1272.0>> -> L<<1395.0,1272.0>--<1379.0,1431.0>>

	* Wdieresis (U+1E84): L<<1606.0,1886.0>--<1754.0,853.0>> -> L<<1754.0,853.0>--<1783.0,596.0>>

	* Wdieresis (U+1E84): L<<1783.0,596.0>--<1879.0,853.0>> -> L<<1879.0,853.0>--<2297.0,1904.0>>

	* Wdieresis (U+1E84): L<<563.0,1886.0>--<706.0,866.0>> -> L<<706.0,866.0>--<745.0,555.0>>

	* Wdieresis (U+1E84): L<<745.0,555.0>--<854.0,856.0>> -> L<<854.0,856.0>--<1252.0,1891.0>>

	* Wgrave (U+1E80): L<<1379.0,1431.0>--<1327.0,1272.0>> -> L<<1327.0,1272.0>--<895.0,133.0>>

	* Wgrave (U+1E80): L<<1572.0,99.0>--<1395.0,1272.0>> -> L<<1395.0,1272.0>--<1379.0,1431.0>>

	* Wgrave (U+1E80): L<<1606.0,1886.0>--<1754.0,853.0>> -> L<<1754.0,853.0>--<1783.0,596.0>>

	* Wgrave (U+1E80): L<<1783.0,596.0>--<1879.0,853.0>> -> L<<1879.0,853.0>--<2297.0,1904.0>>

	* Wgrave (U+1E80): L<<563.0,1886.0>--<706.0,866.0>> -> L<<706.0,866.0>--<745.0,555.0>>

	* Wgrave (U+1E80): L<<745.0,555.0>--<854.0,856.0>> -> L<<854.0,856.0>--<1252.0,1891.0>>

	* oslash (U+00F8): L<<390.0,351.0>--<494.0,543.0>> -> L<<494.0,543.0>--<633.0,837.0>>

	* uni01CD (U+01CD): L<<1017.0,1082.0>--<989.0,1455.0>> -> L<<989.0,1455.0>--<973.0,1644.0>>

	* uni01CD (U+01CD): L<<973.0,1644.0>--<905.0,1459.0>> -> L<<905.0,1459.0>--<769.0,1082.0>>

	* uni01DE (U+01DE): L<<1017.0,1082.0>--<989.0,1455.0>> -> L<<989.0,1455.0>--<973.0,1644.0>>

	* uni01DE (U+01DE): L<<973.0,1644.0>--<905.0,1459.0>> -> L<<905.0,1459.0>--<769.0,1082.0>>

	* uni0226 (U+0226): L<<1017.0,1082.0>--<989.0,1455.0>> -> L<<989.0,1455.0>--<973.0,1644.0>>

	* uni0226 (U+0226): L<<973.0,1644.0>--<905.0,1459.0>> -> L<<905.0,1459.0>--<769.0,1082.0>>

	* yen (U+00A5): L<<644.0,1030.0>--<643.0,1032.0>> -> L<<643.0,1032.0>--<278.0,1802.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Oslash (U+00D8): B<<903.0,61.0>-<778.0,-15.0>-<649.0,-20.0>>/L<<649.0,-20.0>--<649.0,-20.0>> = 2.219655553197814

	* cent (U+00A2): L<<666.0,831.0>--<622.0,497.0>>/B<<622.0,497.0>-<623.0,502.0>-<623.0,500.0>> = 3.80520002340806 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[17] Nswact-Medium.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 2925, but got 2642 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 945, but got 926 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* 🔥 **FAIL** Font is not italic, so post.italicAngle should be equal to zero. [code: non-zero-upright]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, cherokee, coptic
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, old-permic, malayalam, tai-le, math, canadian-aboriginal, coptic, syriac
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
 * U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
 * U+2000 EN QUAD: not included in any glyphset definition
 * U+2001 EM QUAD: not included in any glyphset definition
 * U+2003 EM SPACE: try adding nushu
 * U+2004 THREE-PER-EM SPACE: not included in any glyphset definition
 * U+2005 FOUR-PER-EM SPACE: not included in any glyphset definition
 * U+2006 SIX-PER-EM SPACE: not included in any glyphset definition
 * U+2007 FIGURE SPACE: not included in any glyphset definition
 * U+2008 PUNCTUATION SPACE: not included in any glyphset definition
 * U+200A HAIR SPACE: not included in any glyphset definition
 * U+200C ZERO WIDTH NON-JOINER: try adding one of: syloti-nagri, tibetan, khmer, pahawh-hmong, duployan, kaithi, malayalam, javanese, phags-pa, warang-citi, tai-tham, buhid, thai, khojki, mandaic, bengali, psalter-pahlavi, sharada, tirhuta, myanmar, tai-le, nko, rejang, devanagari, dogra, kayah-li, manichaean, mongolian, sundanese, telugu, yi, tagalog, hanifi-rohingya, thaana, lepcha, gujarati, oriya, hanunoo, gunjala-gondi, cham, balinese, newa, siddham, batak, brahmi, kharoshthi, avestan, syriac, tai-viet, new-tai-lue, mahajani, saurashtra, sinhala, tamil, tifinagh, tagbanwa, meetei-mayek, sogdian, hatran, grantha, takri, kannada, chakma, gurmukhi, khudawadi, modi, buginese, limbu
 * U+200D ZERO WIDTH JOINER: try adding one of: syloti-nagri, tibetan, pahawh-hmong, duployan, kaithi, malayalam, old-hungarian, javanese, phags-pa, warang-citi, tai-tham, buhid, thai, khojki, mandaic, bengali, psalter-pahlavi, sharada, tirhuta, myanmar, tai-le, nko, rejang, devanagari, dogra, kayah-li, manichaean, mongolian, sundanese, telugu, yi, tagalog, hanifi-rohingya, thaana, lepcha, gujarati, oriya, hanunoo, gunjala-gondi, cham, balinese, newa, siddham, batak, brahmi, kharoshthi, avestan, syriac, tai-viet, new-tai-lue, mahajani, saurashtra, sinhala, tamil, tifinagh, tagbanwa, meetei-mayek, grantha, takri, kannada, chakma, gurmukhi, khudawadi, modi, buginese, limbu
 * U+202F NARROW NO-BREAK SPACE: try adding one of: yi, mongolian
 * U+205F MEDIUM MATHEMATICAL SPACE: not included in any glyphset definition
 * U+2116 NUMERO SIGN: try adding cyrillic
 * U+221E INFINITY: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25CC DOTTED CIRCLE: try adding one of: malayalam, elbasan, ahom, khojki, miao, sharada, math, osage, dogra, kayah-li, tagalog, soyombo, gujarati, hanunoo, symbols, kharoshthi, syriac, sinhala, tagbanwa, gurmukhi, pahawh-hmong, modi, bassa-vah, javanese, buhid, psalter-pahlavi, manichaean, sundanese, cham, balinese, tai-viet, tirhuta, mahajani, takri, kannada, chakma, khudawadi, buginese, marchen, khmer, duployan, kaithi, old-permic, thai, bengali, tai-le, nko, mongolian, telugu, yi, masaram-gondi, thaana, adlam, bhaiksuki, gunjala-gondi, new-tai-lue, zanabazar-square, meetei-mayek, grantha, limbu, lao, syloti-nagri, tibetan, hebrew, phags-pa, myanmar, rejang, devanagari, hanifi-rohingya, mende-kikakui, lepcha, oriya, wancho, newa, siddham, batak, brahmi, caucasian-albanian, tamil, tifinagh, music, sogdian, coptic, mandaic
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.784x (3568) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- eacute.cv02

	- eacute.cv03

	- eacute.cv04

	- eacute.cv05

	- eacute.cv06

	- eacute.cv07

	- eacute.fina
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 1093 among a set of 4 math glyphs.
The following math glyphs have a different width, though:

Width = 1091:
plus, minus

Width = 1001:
less

Width = 1002:
greater

Width = 1004:
plusminus

Width = 1092:
approxequal

Width = 1028:
greaterequal, lessequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* asterisk (U+002A): X=506.0,Y=2007.0 (should be at cap-height 2008?)

	* slash (U+002F): X=802.0,Y=2006.0 (should be at cap-height 2008?)

	* seven (U+0037): X=277.0,Y=2007.0 (should be at cap-height 2008?)

	* seven (U+0037): X=1128.0,Y=2007.0 (should be at cap-height 2008?)

	* B (U+0042): X=496.0,Y=2007.0 (should be at cap-height 2008?)

	* F (U+0046): X=488.0,Y=2009.0 (should be at cap-height 2008?)

	* F (U+0046): X=1480.0,Y=2009.0 (should be at cap-height 2008?)

	* P (U+0050): X=483.0,Y=2006.0 (should be at cap-height 2008?)

	* R (U+0052): X=494.0,Y=2006.0 (should be at cap-height 2008?)

	* U (U+0055): X=1333.0,Y=1.0 (should be at baseline 0?)

	* V (U+0056): X=621.0,Y=-2.0 (should be at baseline 0?)

	* V (U+0056): X=621.0,Y=-2.0 (should be at baseline 0?)

	* X (U+0058): X=1380.0,Y=2007.5 (should be at cap-height 2008?)

	* X (U+0058): X=198.0,Y=-1.0 (should be at baseline 0?)

	* backslash (U+005C): X=295.0,Y=2006.0 (should be at cap-height 2008?)

	* bracketright (U+005D): X=500.0,Y=-925.0 (should be at descender -926?)

	* bracketright (U+005D): X=77.0,Y=-925.0 (should be at descender -926?)

	* grave (U+0060): X=195.0,Y=2007.0 (should be at cap-height 2008?)

	* c (U+0063): X=776.5,Y=1081.0 (should be at x-height 1082?)

	* f (U+0066): X=368.0,Y=-2.0 (should be at baseline 0?)

	* f (U+0066): X=368.0,Y=-2.0 (should be at baseline 0?)

	* p (U+0070): X=483.0,Y=1.0 (should be at baseline 0?)

	* p (U+0070): X=338.0,Y=1.0 (should be at baseline 0?)

	* q (U+0071): X=708.0,Y=-924.0 (should be at descender -926?)

	* x (U+0078): X=202.0,Y=-1.0 (should be at baseline 0?)

	* x (U+0078): X=891.0,Y=1083.0 (should be at x-height 1082?)

	* x (U+0078): X=202.0,Y=-1.0 (should be at baseline 0?)

	* braceright (U+007D): X=30.5,Y=-924.0 (should be at descender -926?)

	* braceright (U+007D): X=387.0,Y=2006.5 (should be at cap-height 2008?)

	* exclamdown (U+00A1): X=498.0,Y=2009.0 (should be at cap-height 2008?)

	* sterling (U+00A3): X=681.0,Y=2009.0 (should be at cap-height 2008?)

	* yen (U+00A5): X=327.0,Y=1.0 (should be at baseline 0?)

	* Aring (U+00C5): X=797.0,Y=2644.0 (should be at ascender 2642?)

	* Oslash (U+00D8): X=1024.0,Y=2006.0 (should be at cap-height 2008?)

	* Ugrave (U+00D9): X=1333.0,Y=1.0 (should be at baseline 0?)

	* Uacute (U+00DA): X=1333.0,Y=1.0 (should be at baseline 0?)

	* Ucircumflex (U+00DB): X=1333.0,Y=1.0 (should be at baseline 0?)

	* Udieresis (U+00DC): X=1333.0,Y=1.0 (should be at baseline 0?)

	* germandbls (U+00DF): X=923.0,Y=2009.0 (should be at cap-height 2008?)

	* thorn (U+00FE): X=496.0,Y=1.0 (should be at baseline 0?)

	* thorn (U+00FE): X=352.0,Y=1.0 (should be at baseline 0?)

	* Abreve (U+0102): X=844.0,Y=2643.0 (should be at ascender 2642?)

	* Ccaron (U+010C): X=685.5,Y=2641.0 (should be at ascender 2642?)

	* Dcaron (U+010E): X=792.5,Y=2641.0 (should be at ascender 2642?)

	* Ecaron (U+011A): X=753.5,Y=2641.0 (should be at ascender 2642?)

	* Gbreve (U+011E): X=835.0,Y=2643.0 (should be at ascender 2642?)

	* Iogonek (U+012E): X=111.0,Y=1.0 (should be at baseline 0?)

	* iogonek (U+012F): X=154.0,Y=-1.0 (should be at baseline 0?)

	* Ncaron (U+0147): X=923.5,Y=2641.0 (should be at ascender 2642?)

	* Racute (U+0154): X=494.0,Y=2006.0 (should be at cap-height 2008?)

	* uni0156 (U+0156): X=494.0,Y=2006.0 (should be at cap-height 2008?)

	* Rcaron (U+0158): X=494.0,Y=2006.0 (should be at cap-height 2008?)

	* Rcaron (U+0158): X=751.5,Y=2641.0 (should be at ascender 2642?)

	* Scaron (U+0160): X=676.5,Y=2641.0 (should be at ascender 2642?)

	* Tcaron (U+0164): X=654.5,Y=2641.0 (should be at ascender 2642?)

	* Utilde (U+0168): X=1333.0,Y=1.0 (should be at baseline 0?)

	* Umacron (U+016A): X=1333.0,Y=1.0 (should be at baseline 0?)

	* Ubreve (U+016C): X=1333.0,Y=1.0 (should be at baseline 0?)

	* Ubreve (U+016C): X=901.0,Y=2643.0 (should be at ascender 2642?)

	* Uring (U+016E): X=1333.0,Y=1.0 (should be at baseline 0?)

	* Uring (U+016E): X=854.0,Y=2644.0 (should be at ascender 2642?)

	* Uhungarumlaut (U+0170): X=1333.0,Y=1.0 (should be at baseline 0?)

	* Uogonek (U+0172): X=1333.0,Y=1.0 (should be at baseline 0?)

	* Zcaron (U+017D): X=695.5,Y=2641.0 (should be at ascender 2642?)

	* uni01CD (U+01CD): X=780.5,Y=2641.0 (should be at ascender 2642?)

	* uni01CF (U+01CF): X=324.5,Y=2641.0 (should be at ascender 2642?)

	* uni01D3 (U+01D3): X=1333.0,Y=1.0 (should be at baseline 0?)

	* uni01D3 (U+01D3): X=837.5,Y=2641.0 (should be at ascender 2642?)

	* Gcaron (U+01E6): X=771.5,Y=2641.0 (should be at ascender 2642?)

	* uni1E02 (U+1E02): X=496.0,Y=2007.0 (should be at cap-height 2008?)

	* uni1E1E (U+1E1E): X=488.0,Y=2009.0 (should be at cap-height 2008?)

	* uni1E1E (U+1E1E): X=1480.0,Y=2009.0 (should be at cap-height 2008?)

	* uni1E9E (U+1E9E): X=979.0,Y=-1.0 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=763.0,Y=1.0 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=506.0,Y=2007.0 (should be at cap-height 2008?)

	* uni1E9E (U+1E9E): X=1667.0,Y=2007.0 (should be at cap-height 2008?)

	* uni1E9E (U+1E9E): X=979.0,Y=-1.0 (should be at baseline 0?)

	* fi (U+FB01): X=368.0,Y=-2.0 (should be at baseline 0?)

	* fi (U+FB01): X=368.0,Y=-2.0 (should be at baseline 0?)

	* fl (U+FB02): X=368.0,Y=-2.0 (should be at baseline 0?)

	* fl (U+FB02): X=368.0,Y=-2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* A (U+0041): L<<1008.0,1111.0>--<969.0,1481.0>> -> L<<969.0,1481.0>--<937.0,1745.0>>

	* A (U+0041): L<<937.0,1745.0>--<830.0,1483.0>> -> L<<830.0,1483.0>--<683.0,1111.0>>

	* AE (U+00C6): L<<1059.0,1734.0>--<960.0,1488.0>> -> L<<960.0,1488.0>--<777.0,1121.0>>

	* AE (U+00C6): L<<1088.0,1121.0>--<1060.0,1478.0>> -> L<<1060.0,1478.0>--<1059.0,1734.0>>

	* Aacute (U+00C1): L<<1008.0,1111.0>--<969.0,1481.0>> -> L<<969.0,1481.0>--<937.0,1745.0>>

	* Aacute (U+00C1): L<<937.0,1745.0>--<830.0,1483.0>> -> L<<830.0,1483.0>--<683.0,1111.0>>

	* Abreve (U+0102): L<<1008.0,1111.0>--<969.0,1481.0>> -> L<<969.0,1481.0>--<937.0,1745.0>>

	* Abreve (U+0102): L<<937.0,1745.0>--<830.0,1483.0>> -> L<<830.0,1483.0>--<683.0,1111.0>>

	* Acircumflex (U+00C2): L<<1008.0,1111.0>--<969.0,1481.0>> -> L<<969.0,1481.0>--<937.0,1745.0>>

	* Acircumflex (U+00C2): L<<937.0,1745.0>--<830.0,1483.0>> -> L<<830.0,1483.0>--<683.0,1111.0>>

	* Adieresis (U+00C4): L<<1008.0,1111.0>--<969.0,1481.0>> -> L<<969.0,1481.0>--<937.0,1745.0>>

	* Adieresis (U+00C4): L<<937.0,1745.0>--<830.0,1483.0>> -> L<<830.0,1483.0>--<683.0,1111.0>>

	* Agrave (U+00C0): L<<1008.0,1111.0>--<969.0,1481.0>> -> L<<969.0,1481.0>--<937.0,1745.0>>

	* Agrave (U+00C0): L<<937.0,1745.0>--<830.0,1483.0>> -> L<<830.0,1483.0>--<683.0,1111.0>>

	* Amacron (U+0100): L<<1008.0,1111.0>--<969.0,1481.0>> -> L<<969.0,1481.0>--<937.0,1745.0>>

	* Amacron (U+0100): L<<937.0,1745.0>--<830.0,1483.0>> -> L<<830.0,1483.0>--<683.0,1111.0>>

	* Aogonek (U+0104): L<<1008.0,1111.0>--<969.0,1481.0>> -> L<<969.0,1481.0>--<937.0,1745.0>>

	* Aogonek (U+0104): L<<937.0,1745.0>--<830.0,1483.0>> -> L<<830.0,1483.0>--<683.0,1111.0>>

	* Aring (U+00C5): L<<1008.0,1111.0>--<969.0,1481.0>> -> L<<969.0,1481.0>--<937.0,1745.0>>

	* Aring (U+00C5): L<<937.0,1745.0>--<830.0,1483.0>> -> L<<830.0,1483.0>--<683.0,1111.0>>

	* Atilde (U+00C3): L<<1008.0,1111.0>--<969.0,1481.0>> -> L<<969.0,1481.0>--<937.0,1745.0>>

	* Atilde (U+00C3): L<<937.0,1745.0>--<830.0,1483.0>> -> L<<830.0,1483.0>--<683.0,1111.0>>

	* V (U+0056): L<<441.0,1919.0>--<634.0,693.0>> -> L<<634.0,693.0>--<658.0,410.0>>

	* V (U+0056): L<<658.0,410.0>--<748.0,692.0>> -> L<<748.0,692.0>--<1251.0,1927.0>>

	* W (U+0057): L<<1330.0,1611.0>--<1261.0,1412.0>> -> L<<1261.0,1412.0>--<756.0,100.0>>

	* W (U+0057): L<<1489.0,1919.0>--<1663.0,713.0>> -> L<<1663.0,713.0>--<1700.0,410.0>>

	* W (U+0057): L<<1555.0,81.0>--<1357.0,1405.0>> -> L<<1357.0,1405.0>--<1330.0,1611.0>>

	* W (U+0057): L<<1700.0,410.0>--<1811.0,705.0>> -> L<<1811.0,705.0>--<2294.0,1924.0>>

	* W (U+0057): L<<441.0,1919.0>--<613.0,715.0>> -> L<<613.0,715.0>--<658.0,400.0>>

	* W (U+0057): L<<658.0,400.0>--<774.0,709.0>> -> L<<774.0,709.0>--<1242.0,1920.0>>

	* Wacute (U+1E82): L<<1330.0,1611.0>--<1261.0,1412.0>> -> L<<1261.0,1412.0>--<756.0,100.0>>

	* Wacute (U+1E82): L<<1489.0,1919.0>--<1663.0,713.0>> -> L<<1663.0,713.0>--<1700.0,410.0>>

	* Wacute (U+1E82): L<<1555.0,81.0>--<1357.0,1405.0>> -> L<<1357.0,1405.0>--<1330.0,1611.0>>

	* Wacute (U+1E82): L<<1700.0,410.0>--<1811.0,705.0>> -> L<<1811.0,705.0>--<2294.0,1924.0>>

	* Wacute (U+1E82): L<<441.0,1919.0>--<613.0,715.0>> -> L<<613.0,715.0>--<658.0,400.0>>

	* Wacute (U+1E82): L<<658.0,400.0>--<774.0,709.0>> -> L<<774.0,709.0>--<1242.0,1920.0>>

	* Wcircumflex (U+0174): L<<1330.0,1611.0>--<1261.0,1412.0>> -> L<<1261.0,1412.0>--<756.0,100.0>>

	* Wcircumflex (U+0174): L<<1489.0,1919.0>--<1663.0,713.0>> -> L<<1663.0,713.0>--<1700.0,410.0>>

	* Wcircumflex (U+0174): L<<1555.0,81.0>--<1357.0,1405.0>> -> L<<1357.0,1405.0>--<1330.0,1611.0>>

	* Wcircumflex (U+0174): L<<1700.0,410.0>--<1811.0,705.0>> -> L<<1811.0,705.0>--<2294.0,1924.0>>

	* Wcircumflex (U+0174): L<<441.0,1919.0>--<613.0,715.0>> -> L<<613.0,715.0>--<658.0,400.0>>

	* Wcircumflex (U+0174): L<<658.0,400.0>--<774.0,709.0>> -> L<<774.0,709.0>--<1242.0,1920.0>>

	* Wdieresis (U+1E84): L<<1330.0,1611.0>--<1261.0,1412.0>> -> L<<1261.0,1412.0>--<756.0,100.0>>

	* Wdieresis (U+1E84): L<<1489.0,1919.0>--<1663.0,713.0>> -> L<<1663.0,713.0>--<1700.0,410.0>>

	* Wdieresis (U+1E84): L<<1555.0,81.0>--<1357.0,1405.0>> -> L<<1357.0,1405.0>--<1330.0,1611.0>>

	* Wdieresis (U+1E84): L<<1700.0,410.0>--<1811.0,705.0>> -> L<<1811.0,705.0>--<2294.0,1924.0>>

	* Wdieresis (U+1E84): L<<441.0,1919.0>--<613.0,715.0>> -> L<<613.0,715.0>--<658.0,400.0>>

	* Wdieresis (U+1E84): L<<658.0,400.0>--<774.0,709.0>> -> L<<774.0,709.0>--<1242.0,1920.0>>

	* Wgrave (U+1E80): L<<1330.0,1611.0>--<1261.0,1412.0>> -> L<<1261.0,1412.0>--<756.0,100.0>>

	* Wgrave (U+1E80): L<<1489.0,1919.0>--<1663.0,713.0>> -> L<<1663.0,713.0>--<1700.0,410.0>>

	* Wgrave (U+1E80): L<<1555.0,81.0>--<1357.0,1405.0>> -> L<<1357.0,1405.0>--<1330.0,1611.0>>

	* Wgrave (U+1E80): L<<1700.0,410.0>--<1811.0,705.0>> -> L<<1811.0,705.0>--<2294.0,1924.0>>

	* Wgrave (U+1E80): L<<441.0,1919.0>--<613.0,715.0>> -> L<<613.0,715.0>--<658.0,400.0>>

	* Wgrave (U+1E80): L<<658.0,400.0>--<774.0,709.0>> -> L<<774.0,709.0>--<1242.0,1920.0>>

	* oslash (U+00F8): L<<319.0,258.0>--<475.0,561.0>> -> L<<475.0,561.0>--<635.0,899.0>>

	* oslash (U+00F8): L<<758.0,838.0>--<580.0,510.0>> -> L<<580.0,510.0>--<425.0,174.0>>

	* uni01CD (U+01CD): L<<1008.0,1111.0>--<969.0,1481.0>> -> L<<969.0,1481.0>--<937.0,1745.0>>

	* uni01CD (U+01CD): L<<937.0,1745.0>--<830.0,1483.0>> -> L<<830.0,1483.0>--<683.0,1111.0>>

	* uni01DE (U+01DE): L<<1008.0,1111.0>--<969.0,1481.0>> -> L<<969.0,1481.0>--<937.0,1745.0>>

	* uni01DE (U+01DE): L<<937.0,1745.0>--<830.0,1483.0>> -> L<<830.0,1483.0>--<683.0,1111.0>>

	* uni0226 (U+0226): L<<1008.0,1111.0>--<969.0,1481.0>> -> L<<969.0,1481.0>--<937.0,1745.0>>

	* uni0226 (U+0226): L<<937.0,1745.0>--<830.0,1483.0>> -> L<<830.0,1483.0>--<683.0,1111.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[18] Nswact-SemiBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 2925, but got 2642 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 945, but got 926 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* 🔥 **FAIL** Font is not italic, so post.italicAngle should be equal to zero. [code: non-zero-upright]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, cherokee, coptic
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, old-permic, malayalam, tai-le, math, canadian-aboriginal, coptic, syriac
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
 * U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
 * U+2000 EN QUAD: not included in any glyphset definition
 * U+2001 EM QUAD: not included in any glyphset definition
 * U+2003 EM SPACE: try adding nushu
 * U+2004 THREE-PER-EM SPACE: not included in any glyphset definition
 * U+2005 FOUR-PER-EM SPACE: not included in any glyphset definition
 * U+2006 SIX-PER-EM SPACE: not included in any glyphset definition
 * U+2007 FIGURE SPACE: not included in any glyphset definition
 * U+2008 PUNCTUATION SPACE: not included in any glyphset definition
 * U+200A HAIR SPACE: not included in any glyphset definition
 * U+200C ZERO WIDTH NON-JOINER: try adding one of: syloti-nagri, tibetan, khmer, pahawh-hmong, duployan, kaithi, malayalam, javanese, phags-pa, warang-citi, tai-tham, buhid, thai, khojki, mandaic, bengali, psalter-pahlavi, sharada, tirhuta, myanmar, tai-le, nko, rejang, devanagari, dogra, kayah-li, manichaean, mongolian, sundanese, telugu, yi, tagalog, hanifi-rohingya, thaana, lepcha, gujarati, oriya, hanunoo, gunjala-gondi, cham, balinese, newa, siddham, batak, brahmi, kharoshthi, avestan, syriac, tai-viet, new-tai-lue, mahajani, saurashtra, sinhala, tamil, tifinagh, tagbanwa, meetei-mayek, sogdian, hatran, grantha, takri, kannada, chakma, gurmukhi, khudawadi, modi, buginese, limbu
 * U+200D ZERO WIDTH JOINER: try adding one of: syloti-nagri, tibetan, pahawh-hmong, duployan, kaithi, malayalam, old-hungarian, javanese, phags-pa, warang-citi, tai-tham, buhid, thai, khojki, mandaic, bengali, psalter-pahlavi, sharada, tirhuta, myanmar, tai-le, nko, rejang, devanagari, dogra, kayah-li, manichaean, mongolian, sundanese, telugu, yi, tagalog, hanifi-rohingya, thaana, lepcha, gujarati, oriya, hanunoo, gunjala-gondi, cham, balinese, newa, siddham, batak, brahmi, kharoshthi, avestan, syriac, tai-viet, new-tai-lue, mahajani, saurashtra, sinhala, tamil, tifinagh, tagbanwa, meetei-mayek, grantha, takri, kannada, chakma, gurmukhi, khudawadi, modi, buginese, limbu
 * U+202F NARROW NO-BREAK SPACE: try adding one of: yi, mongolian
 * U+205F MEDIUM MATHEMATICAL SPACE: not included in any glyphset definition
 * U+2116 NUMERO SIGN: try adding cyrillic
 * U+221E INFINITY: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25CC DOTTED CIRCLE: try adding one of: malayalam, elbasan, ahom, khojki, miao, sharada, math, osage, dogra, kayah-li, tagalog, soyombo, gujarati, hanunoo, symbols, kharoshthi, syriac, sinhala, tagbanwa, gurmukhi, pahawh-hmong, modi, bassa-vah, javanese, buhid, psalter-pahlavi, manichaean, sundanese, cham, balinese, tai-viet, tirhuta, mahajani, takri, kannada, chakma, khudawadi, buginese, marchen, khmer, duployan, kaithi, old-permic, thai, bengali, tai-le, nko, mongolian, telugu, yi, masaram-gondi, thaana, adlam, bhaiksuki, gunjala-gondi, new-tai-lue, zanabazar-square, meetei-mayek, grantha, limbu, lao, syloti-nagri, tibetan, hebrew, phags-pa, myanmar, rejang, devanagari, hanifi-rohingya, mende-kikakui, lepcha, oriya, wancho, newa, siddham, batak, brahmi, caucasian-albanian, tamil, tifinagh, music, sogdian, coptic, mandaic
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.784x (3568) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- eacute.cv02

	- eacute.cv03

	- eacute.cv04

	- eacute.cv05

	- eacute.cv06

	- eacute.cv07

	- eacute.fina
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 1140 among a set of 2 math glyphs.
The following math glyphs have a different width, though:

Width = 1052:
greater, less

Width = 1143:
equal, approxequal

Width = 1057:
plusminus

Width = 1144:
notequal, multiply

Width = 1139:
divide

Width = 1080:
lessequal

Width = 1077:
greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* parenleft (U+0028): X=436.5,Y=0.5 (should be at baseline 0?)

	* at (U+0040): X=1397.0,Y=1.0 (should be at baseline 0?)

	* P (U+0050): X=497.0,Y=2007.0 (should be at cap-height 2008?)

	* R (U+0052): X=517.0,Y=2007.0 (should be at cap-height 2008?)

	* X (U+0058): X=1435.0,Y=2006.5 (should be at cap-height 2008?)

	* X (U+0058): X=1231.0,Y=0.5 (should be at baseline 0?)

	* Y (U+0059): X=353.0,Y=1.5 (should be at baseline 0?)

	* Z (U+005A): X=379.0,Y=2009.0 (should be at cap-height 2008?)

	* Z (U+005A): X=1389.0,Y=2009.0 (should be at cap-height 2008?)

	* g (U+0067): X=292.0,Y=-1.5 (should be at baseline 0?)

	* q (U+0071): X=713.0,Y=-925.0 (should be at descender -926?)

	* s (U+0073): X=653.0,Y=1083.5 (should be at x-height 1082?)

	* braceright (U+007D): X=44.5,Y=-924.0 (should be at descender -926?)

	* braceright (U+007D): X=381.5,Y=2006.5 (should be at cap-height 2008?)

	* cent (U+00A2): X=257.5,Y=2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=711.0,Y=2010.0 (should be at cap-height 2008?)

	* yen (U+00A5): X=356.5,Y=0.5 (should be at baseline 0?)

	* brokenbar (U+00A6): X=662.0,Y=2006.0 (should be at cap-height 2008?)

	* brokenbar (U+00A6): X=662.0,Y=2006.0 (should be at cap-height 2008?)

	* Aring (U+00C5): X=1243.0,Y=2644.0 (should be at ascender 2642?)

	* Yacute (U+00DD): X=353.0,Y=1.5 (should be at baseline 0?)

	* Thorn (U+00DE): X=518.0,Y=2009.0 (should be at cap-height 2008?)

	* germandbls (U+00DF): X=940.0,Y=2010.0 (should be at cap-height 2008?)

	* Aogonek (U+0104): X=1042.5,Y=1.0 (should be at baseline 0?)

	* Eogonek (U+0118): X=1067.5,Y=1.0 (should be at baseline 0?)

	* gcircumflex (U+011D): X=292.0,Y=-1.5 (should be at baseline 0?)

	* gbreve (U+011F): X=292.0,Y=-1.5 (should be at baseline 0?)

	* gdotaccent (U+0121): X=292.0,Y=-1.5 (should be at baseline 0?)

	* uni0123 (U+0123): X=292.0,Y=-1.5 (should be at baseline 0?)

	* Iogonek (U+012E): X=116.5,Y=-1.0 (should be at baseline 0?)

	* iogonek (U+012F): X=371.0,Y=1.0 (should be at baseline 0?)

	* Racute (U+0154): X=517.0,Y=2007.0 (should be at cap-height 2008?)

	* uni0156 (U+0156): X=517.0,Y=2007.0 (should be at cap-height 2008?)

	* Rcaron (U+0158): X=517.0,Y=2007.0 (should be at cap-height 2008?)

	* Uring (U+016E): X=1298.0,Y=2644.0 (should be at ascender 2642?)

	* uogonek (U+0173): X=811.5,Y=1.0 (should be at baseline 0?)

	* Ycircumflex (U+0176): X=353.0,Y=1.5 (should be at baseline 0?)

	* Ydieresis (U+0178): X=353.0,Y=1.5 (should be at baseline 0?)

	* Zacute (U+0179): X=379.0,Y=2009.0 (should be at cap-height 2008?)

	* Zacute (U+0179): X=1389.0,Y=2009.0 (should be at cap-height 2008?)

	* Zdotaccent (U+017B): X=379.0,Y=2009.0 (should be at cap-height 2008?)

	* Zdotaccent (U+017B): X=1389.0,Y=2009.0 (should be at cap-height 2008?)

	* Zcaron (U+017D): X=379.0,Y=2009.0 (should be at cap-height 2008?)

	* Zcaron (U+017D): X=1389.0,Y=2009.0 (should be at cap-height 2008?)

	* uni1E21 (U+1E21): X=292.0,Y=-1.5 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=1028.0,Y=-2.0 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=324.0,Y=-2.0 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=1028.0,Y=-2.0 (should be at baseline 0?)

	* Ygrave (U+1EF2): X=353.0,Y=1.5 (should be at baseline 0?)

	* uni1EF8 (U+1EF8): X=353.0,Y=1.5 (should be at baseline 0?)

	* trademark (U+2122): X=2440.0,Y=2009.0 (should be at cap-height 2008?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* dollar (U+0024) contains a short segment B<<510.0,239.0>-<531.0,239.0>-<554.5,239.5>>

	* at (U+0040) contains a short segment B<<1186.0,144.0>-<1173.0,178.0>-<1167.0,221.0>>

	* at (U+0040) contains a short segment B<<1400.5,313.5>-<1403.0,255.0>-<1435.0,255.0>>

	* at (U+0040) contains a short segment B<<1204.0,-81.0>-<1226.0,-110.0>-<1231.5,-142.5>>

	* at (U+0040) contains a short segment B<<1231.5,-142.5>-<1237.0,-175.0>-<1212.0,-213.0>>

	* G (U+0047) contains a short segment B<<1274.5,1086.5>-<1298.0,1112.0>-<1323.0,1120.5>>

	* K (U+004B) contains a short segment B<<1473.0,153.5>-<1481.0,130.0>-<1481.0,108.0>>

	* M (U+004D) contains a short segment B<<2284.0,113.0>-<2279.0,69.0>-<2248.5,34.5>>

	* W (U+0057) contains a short segment B<<2296.0,1912.0>-<2311.0,1945.0>-<2346.5,1976.5>>

	* W (U+0057) contains a short segment B<<2529.5,1982.5>-<2560.0,1957.0>-<2569.0,1919.5>>

	* W (U+0057) contains a short segment B<<2569.0,1919.5>-<2578.0,1882.0>-<2564.0,1847.0>>

	* W (U+0057) contains a short segment B<<1607.0,28.0>-<1571.0,56.0>-<1566.0,92.0>>

	* q (U+0071) contains a short segment B<<746.0,-916.0>-<734.0,-924.0>-<713.0,-925.0>>

	* cent (U+00A2) contains a short segment L<<381.0,-17.0>--<369.0,-17.0>>

	* sterling (U+00A3) contains a short segment B<<563.0,1740.0>-<542.0,1729.0>-<532.5,1706.5>>

	* sterling (U+00A3) contains a short segment B<<532.5,1706.5>-<523.0,1684.0>-<523.0,1660.0>>

	* yen (U+00A5) contains a short segment L<<362.0,377.0>--<323.0,377.0>>

	* yen (U+00A5) contains a short segment L<<642.0,1002.0>--<654.0,1024.0>>

	* yen (U+00A5) contains a short segment L<<1052.0,996.0>--<1086.0,996.0>>

	* Oslash (U+00D8) contains a short segment B<<613.0,-20.0>-<609.0,-20.0>-<606.0,-20.0>>

	* oslash (U+00F8) contains a short segment B<<634.0,861.0>-<634.0,861.0>-<627.0,861.0>>

	* Gcircumflex (U+011C) contains a short segment B<<1274.5,1086.5>-<1298.0,1112.0>-<1323.0,1120.5>>

	* Gbreve (U+011E) contains a short segment B<<1274.5,1086.5>-<1298.0,1112.0>-<1323.0,1120.5>>

	* Gdotaccent (U+0120) contains a short segment B<<1274.5,1086.5>-<1298.0,1112.0>-<1323.0,1120.5>>

	* uni0122 (U+0122) contains a short segment B<<1274.5,1086.5>-<1298.0,1112.0>-<1323.0,1120.5>>

	* uni0136 (U+0136) contains a short segment B<<1473.0,153.5>-<1481.0,130.0>-<1481.0,108.0>>

	* lslash (U+0142) contains a short segment L<<217.0,742.0>--<206.0,738.0>>

	* Wcircumflex (U+0174) contains a short segment B<<2296.0,1912.0>-<2311.0,1945.0>-<2346.5,1976.5>>

	* Wcircumflex (U+0174) contains a short segment B<<2529.5,1982.5>-<2560.0,1957.0>-<2569.0,1919.5>>

	* Wcircumflex (U+0174) contains a short segment B<<2569.0,1919.5>-<2578.0,1882.0>-<2564.0,1847.0>>

	* Wcircumflex (U+0174) contains a short segment B<<1607.0,28.0>-<1571.0,56.0>-<1566.0,92.0>>

	* Gcaron (U+01E6) contains a short segment B<<1274.5,1086.5>-<1298.0,1112.0>-<1323.0,1120.5>>

	* uni1E20 (U+1E20) contains a short segment B<<1274.5,1086.5>-<1298.0,1112.0>-<1323.0,1120.5>>

	* Wgrave (U+1E80) contains a short segment B<<2296.0,1912.0>-<2311.0,1945.0>-<2346.5,1976.5>>

	* Wgrave (U+1E80) contains a short segment B<<2529.5,1982.5>-<2560.0,1957.0>-<2569.0,1919.5>>

	* Wgrave (U+1E80) contains a short segment B<<2569.0,1919.5>-<2578.0,1882.0>-<2564.0,1847.0>>

	* Wgrave (U+1E80) contains a short segment B<<1607.0,28.0>-<1571.0,56.0>-<1566.0,92.0>>

	* Wacute (U+1E82) contains a short segment B<<2296.0,1912.0>-<2311.0,1945.0>-<2346.5,1976.5>>

	* Wacute (U+1E82) contains a short segment B<<2529.5,1982.5>-<2560.0,1957.0>-<2569.0,1919.5>>

	* Wacute (U+1E82) contains a short segment B<<2569.0,1919.5>-<2578.0,1882.0>-<2564.0,1847.0>>

	* Wacute (U+1E82) contains a short segment B<<1607.0,28.0>-<1571.0,56.0>-<1566.0,92.0>>

	* Wdieresis (U+1E84) contains a short segment B<<2296.0,1912.0>-<2311.0,1945.0>-<2346.5,1976.5>>

	* Wdieresis (U+1E84) contains a short segment B<<2529.5,1982.5>-<2560.0,1957.0>-<2569.0,1919.5>>

	* Wdieresis (U+1E84) contains a short segment B<<2569.0,1919.5>-<2578.0,1882.0>-<2564.0,1847.0>>

	* Wdieresis (U+1E84) contains a short segment B<<1607.0,28.0>-<1571.0,56.0>-<1566.0,92.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<804.0,0.0>-<784.0,1.0>-<752.0,10.5>>

	* uni1E9E (U+1E9E) contains a short segment B<<752.0,10.5>-<720.0,20.0>-<694.5,46.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<1812.0,1938.0>-<1830.0,1909.0>-<1830.5,1870.0>>

	* Euro (U+20AC) contains a short segment B<<488.0,1057.0>-<490.0,1072.0>-<493.0,1086.5>>

	* Euro (U+20AC) contains a short segment B<<493.0,1086.5>-<496.0,1101.0>-<498.0,1115.0>>

	* lessequal (U+2264) contains a short segment L<<253.0,627.0>--<253.0,629.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* A (U+0041): L<<1014.0,1093.0>--<981.0,1465.0>> -> L<<981.0,1465.0>--<960.0,1682.0>>

	* A (U+0041): L<<960.0,1682.0>--<877.0,1468.0>> -> L<<877.0,1468.0>--<737.0,1093.0>>

	* AE (U+00C6): L<<1078.0,1658.0>--<987.0,1424.0>> -> L<<987.0,1424.0>--<829.0,1109.0>>

	* Aacute (U+00C1): L<<1014.0,1093.0>--<981.0,1465.0>> -> L<<981.0,1465.0>--<960.0,1682.0>>

	* Aacute (U+00C1): L<<960.0,1682.0>--<877.0,1468.0>> -> L<<877.0,1468.0>--<737.0,1093.0>>

	* Abreve (U+0102): L<<1014.0,1093.0>--<981.0,1465.0>> -> L<<981.0,1465.0>--<960.0,1682.0>>

	* Abreve (U+0102): L<<960.0,1682.0>--<877.0,1468.0>> -> L<<877.0,1468.0>--<737.0,1093.0>>

	* Acircumflex (U+00C2): L<<1014.0,1093.0>--<981.0,1465.0>> -> L<<981.0,1465.0>--<960.0,1682.0>>

	* Acircumflex (U+00C2): L<<960.0,1682.0>--<877.0,1468.0>> -> L<<877.0,1468.0>--<737.0,1093.0>>

	* Adieresis (U+00C4): L<<1014.0,1093.0>--<981.0,1465.0>> -> L<<981.0,1465.0>--<960.0,1682.0>>

	* Adieresis (U+00C4): L<<960.0,1682.0>--<877.0,1468.0>> -> L<<877.0,1468.0>--<737.0,1093.0>>

	* Agrave (U+00C0): L<<1014.0,1093.0>--<981.0,1465.0>> -> L<<981.0,1465.0>--<960.0,1682.0>>

	* Agrave (U+00C0): L<<960.0,1682.0>--<877.0,1468.0>> -> L<<877.0,1468.0>--<737.0,1093.0>>

	* Amacron (U+0100): L<<1014.0,1093.0>--<981.0,1465.0>> -> L<<981.0,1465.0>--<960.0,1682.0>>

	* Amacron (U+0100): L<<960.0,1682.0>--<877.0,1468.0>> -> L<<877.0,1468.0>--<737.0,1093.0>>

	* Aogonek (U+0104): L<<1014.0,1093.0>--<981.0,1465.0>> -> L<<981.0,1465.0>--<960.0,1682.0>>

	* Aogonek (U+0104): L<<960.0,1682.0>--<877.0,1468.0>> -> L<<877.0,1468.0>--<737.0,1093.0>>

	* Aring (U+00C5): L<<1014.0,1093.0>--<981.0,1465.0>> -> L<<981.0,1465.0>--<960.0,1682.0>>

	* Aring (U+00C5): L<<960.0,1682.0>--<877.0,1468.0>> -> L<<877.0,1468.0>--<737.0,1093.0>>

	* Atilde (U+00C3): L<<1014.0,1093.0>--<981.0,1465.0>> -> L<<981.0,1465.0>--<960.0,1682.0>>

	* Atilde (U+00C3): L<<960.0,1682.0>--<877.0,1468.0>> -> L<<877.0,1468.0>--<737.0,1093.0>>

	* V (U+0056): L<<517.0,1898.0>--<686.0,847.0>> -> L<<686.0,847.0>--<707.0,508.0>>

	* W (U+0057): L<<1361.0,1499.0>--<1302.0,1324.0>> -> L<<1302.0,1324.0>--<843.0,121.0>>

	* W (U+0057): L<<1562.0,1898.0>--<1720.0,801.0>> -> L<<1720.0,801.0>--<1752.0,526.0>>

	* W (U+0057): L<<1566.0,92.0>--<1381.0,1322.0>> -> L<<1381.0,1322.0>--<1361.0,1499.0>>

	* W (U+0057): L<<1752.0,526.0>--<1854.0,797.0>> -> L<<1854.0,797.0>--<2296.0,1912.0>>

	* W (U+0057): L<<517.0,1898.0>--<671.0,809.0>> -> L<<671.0,809.0>--<712.0,497.0>>

	* W (U+0057): L<<712.0,497.0>--<824.0,801.0>> -> L<<824.0,801.0>--<1248.0,1902.0>>

	* Wacute (U+1E82): L<<1361.0,1499.0>--<1302.0,1324.0>> -> L<<1302.0,1324.0>--<843.0,121.0>>

	* Wacute (U+1E82): L<<1562.0,1898.0>--<1720.0,801.0>> -> L<<1720.0,801.0>--<1752.0,526.0>>

	* Wacute (U+1E82): L<<1566.0,92.0>--<1381.0,1322.0>> -> L<<1381.0,1322.0>--<1361.0,1499.0>>

	* Wacute (U+1E82): L<<1752.0,526.0>--<1854.0,797.0>> -> L<<1854.0,797.0>--<2296.0,1912.0>>

	* Wacute (U+1E82): L<<517.0,1898.0>--<671.0,809.0>> -> L<<671.0,809.0>--<712.0,497.0>>

	* Wacute (U+1E82): L<<712.0,497.0>--<824.0,801.0>> -> L<<824.0,801.0>--<1248.0,1902.0>>

	* Wcircumflex (U+0174): L<<1361.0,1499.0>--<1302.0,1324.0>> -> L<<1302.0,1324.0>--<843.0,121.0>>

	* Wcircumflex (U+0174): L<<1562.0,1898.0>--<1720.0,801.0>> -> L<<1720.0,801.0>--<1752.0,526.0>>

	* Wcircumflex (U+0174): L<<1566.0,92.0>--<1381.0,1322.0>> -> L<<1381.0,1322.0>--<1361.0,1499.0>>

	* Wcircumflex (U+0174): L<<1752.0,526.0>--<1854.0,797.0>> -> L<<1854.0,797.0>--<2296.0,1912.0>>

	* Wcircumflex (U+0174): L<<517.0,1898.0>--<671.0,809.0>> -> L<<671.0,809.0>--<712.0,497.0>>

	* Wcircumflex (U+0174): L<<712.0,497.0>--<824.0,801.0>> -> L<<824.0,801.0>--<1248.0,1902.0>>

	* Wdieresis (U+1E84): L<<1361.0,1499.0>--<1302.0,1324.0>> -> L<<1302.0,1324.0>--<843.0,121.0>>

	* Wdieresis (U+1E84): L<<1562.0,1898.0>--<1720.0,801.0>> -> L<<1720.0,801.0>--<1752.0,526.0>>

	* Wdieresis (U+1E84): L<<1566.0,92.0>--<1381.0,1322.0>> -> L<<1381.0,1322.0>--<1361.0,1499.0>>

	* Wdieresis (U+1E84): L<<1752.0,526.0>--<1854.0,797.0>> -> L<<1854.0,797.0>--<2296.0,1912.0>>

	* Wdieresis (U+1E84): L<<517.0,1898.0>--<671.0,809.0>> -> L<<671.0,809.0>--<712.0,497.0>>

	* Wdieresis (U+1E84): L<<712.0,497.0>--<824.0,801.0>> -> L<<824.0,801.0>--<1248.0,1902.0>>

	* Wgrave (U+1E80): L<<1361.0,1499.0>--<1302.0,1324.0>> -> L<<1302.0,1324.0>--<843.0,121.0>>

	* Wgrave (U+1E80): L<<1562.0,1898.0>--<1720.0,801.0>> -> L<<1720.0,801.0>--<1752.0,526.0>>

	* Wgrave (U+1E80): L<<1566.0,92.0>--<1381.0,1322.0>> -> L<<1381.0,1322.0>--<1361.0,1499.0>>

	* Wgrave (U+1E80): L<<1752.0,526.0>--<1854.0,797.0>> -> L<<1854.0,797.0>--<2296.0,1912.0>>

	* Wgrave (U+1E80): L<<517.0,1898.0>--<671.0,809.0>> -> L<<671.0,809.0>--<712.0,497.0>>

	* Wgrave (U+1E80): L<<712.0,497.0>--<824.0,801.0>> -> L<<824.0,801.0>--<1248.0,1902.0>>

	* oslash (U+00F8): L<<362.0,315.0>--<487.0,550.0>> -> L<<487.0,550.0>--<634.0,861.0>>

	* oslash (U+00F8): L<<769.0,797.0>--<598.0,501.0>> -> L<<598.0,501.0>--<473.0,224.0>>

	* uni01CD (U+01CD): L<<1014.0,1093.0>--<981.0,1465.0>> -> L<<981.0,1465.0>--<960.0,1682.0>>

	* uni01CD (U+01CD): L<<960.0,1682.0>--<877.0,1468.0>> -> L<<877.0,1468.0>--<737.0,1093.0>>

	* uni01DE (U+01DE): L<<1014.0,1093.0>--<981.0,1465.0>> -> L<<981.0,1465.0>--<960.0,1682.0>>

	* uni01DE (U+01DE): L<<960.0,1682.0>--<877.0,1468.0>> -> L<<877.0,1468.0>--<737.0,1093.0>>

	* uni0226 (U+0226): L<<1014.0,1093.0>--<981.0,1465.0>> -> L<<981.0,1465.0>--<960.0,1682.0>>

	* uni0226 (U+0226): L<<960.0,1682.0>--<877.0,1468.0>> -> L<<877.0,1468.0>--<737.0,1093.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[18] Nswact-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 2925, but got 2642 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 945, but got 926 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* 🔥 **FAIL** Font is not italic, so post.italicAngle should be equal to zero. [code: non-zero-upright]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, cherokee, coptic
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, old-permic, malayalam, tai-le, math, canadian-aboriginal, coptic, syriac
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
 * U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
 * U+2000 EN QUAD: not included in any glyphset definition
 * U+2001 EM QUAD: not included in any glyphset definition
 * U+2003 EM SPACE: try adding nushu
 * U+2004 THREE-PER-EM SPACE: not included in any glyphset definition
 * U+2005 FOUR-PER-EM SPACE: not included in any glyphset definition
 * U+2006 SIX-PER-EM SPACE: not included in any glyphset definition
 * U+2007 FIGURE SPACE: not included in any glyphset definition
 * U+2008 PUNCTUATION SPACE: not included in any glyphset definition
 * U+200A HAIR SPACE: not included in any glyphset definition
 * U+200C ZERO WIDTH NON-JOINER: try adding one of: syloti-nagri, tibetan, khmer, pahawh-hmong, duployan, kaithi, malayalam, javanese, phags-pa, warang-citi, tai-tham, buhid, thai, khojki, mandaic, bengali, psalter-pahlavi, sharada, tirhuta, myanmar, tai-le, nko, rejang, devanagari, dogra, kayah-li, manichaean, mongolian, sundanese, telugu, yi, tagalog, hanifi-rohingya, thaana, lepcha, gujarati, oriya, hanunoo, gunjala-gondi, cham, balinese, newa, siddham, batak, brahmi, kharoshthi, avestan, syriac, tai-viet, new-tai-lue, mahajani, saurashtra, sinhala, tamil, tifinagh, tagbanwa, meetei-mayek, sogdian, hatran, grantha, takri, kannada, chakma, gurmukhi, khudawadi, modi, buginese, limbu
 * U+200D ZERO WIDTH JOINER: try adding one of: syloti-nagri, tibetan, pahawh-hmong, duployan, kaithi, malayalam, old-hungarian, javanese, phags-pa, warang-citi, tai-tham, buhid, thai, khojki, mandaic, bengali, psalter-pahlavi, sharada, tirhuta, myanmar, tai-le, nko, rejang, devanagari, dogra, kayah-li, manichaean, mongolian, sundanese, telugu, yi, tagalog, hanifi-rohingya, thaana, lepcha, gujarati, oriya, hanunoo, gunjala-gondi, cham, balinese, newa, siddham, batak, brahmi, kharoshthi, avestan, syriac, tai-viet, new-tai-lue, mahajani, saurashtra, sinhala, tamil, tifinagh, tagbanwa, meetei-mayek, grantha, takri, kannada, chakma, gurmukhi, khudawadi, modi, buginese, limbu
 * U+202F NARROW NO-BREAK SPACE: try adding one of: yi, mongolian
 * U+205F MEDIUM MATHEMATICAL SPACE: not included in any glyphset definition
 * U+2116 NUMERO SIGN: try adding cyrillic
 * U+221E INFINITY: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25CC DOTTED CIRCLE: try adding one of: malayalam, elbasan, ahom, khojki, miao, sharada, math, osage, dogra, kayah-li, tagalog, soyombo, gujarati, hanunoo, symbols, kharoshthi, syriac, sinhala, tagbanwa, gurmukhi, pahawh-hmong, modi, bassa-vah, javanese, buhid, psalter-pahlavi, manichaean, sundanese, cham, balinese, tai-viet, tirhuta, mahajani, takri, kannada, chakma, khudawadi, buginese, marchen, khmer, duployan, kaithi, old-permic, thai, bengali, tai-le, nko, mongolian, telugu, yi, masaram-gondi, thaana, adlam, bhaiksuki, gunjala-gondi, new-tai-lue, zanabazar-square, meetei-mayek, grantha, limbu, lao, syloti-nagri, tibetan, hebrew, phags-pa, myanmar, rejang, devanagari, hanifi-rohingya, mende-kikakui, lepcha, oriya, wancho, newa, siddham, batak, brahmi, caucasian-albanian, tamil, tifinagh, music, sogdian, coptic, mandaic
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.784x (3568) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- eacute.cv02

	- eacute.cv03

	- eacute.cv04

	- eacute.cv05

	- eacute.cv06

	- eacute.cv07

	- eacute.fina
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 1023 among a set of 3 math glyphs.
The following math glyphs have a different width, though:

Width = 1021:
plus, minus

Width = 929:
plusminus, less

Width = 932:
greater

Width = 1028:
divide

Width = 1022:
approxequal

Width = 956:
lessequal

Width = 958:
greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* dollar (U+0024): X=537.0,Y=1.0 (should be at baseline 0?)

	* percent (U+0025): X=999.0,Y=2.0 (should be at baseline 0?)

	* percent (U+0025): X=999.0,Y=2.0 (should be at baseline 0?)

	* ampersand (U+0026): X=529.0,Y=2.0 (should be at baseline 0?)

	* ampersand (U+0026): X=529.0,Y=2.0 (should be at baseline 0?)

	* parenleft (U+0028): X=587.5,Y=-925.5 (should be at descender -926?)

	* parenleft (U+0028): X=891.0,Y=2006.5 (should be at cap-height 2008?)

	* seven (U+0037): X=244.0,Y=2007.0 (should be at cap-height 2008?)

	* seven (U+0037): X=1118.0,Y=2007.0 (should be at cap-height 2008?)

	* question (U+003F): X=717.0,Y=2006.0 (should be at cap-height 2008?)

	* B (U+0042): X=461.0,Y=2006.0 (should be at cap-height 2008?)

	* F (U+0046): X=461.0,Y=2009.0 (should be at cap-height 2008?)

	* F (U+0046): X=1423.0,Y=2009.0 (should be at cap-height 2008?)

	* U (U+0055): X=1294.0,Y=1.0 (should be at baseline 0?)

	* X (U+0058): X=1359.0,Y=2006.0 (should be at cap-height 2008?)

	* X (U+0058): X=123.0,Y=0.5 (should be at baseline 0?)

	* backslash (U+005C): X=250.0,Y=2009.0 (should be at cap-height 2008?)

	* bracketright (U+005D): X=468.0,Y=-925.0 (should be at descender -926?)

	* bracketright (U+005D): X=31.0,Y=-925.0 (should be at descender -926?)

	* p (U+0070): X=498.0,Y=1.0 (should be at baseline 0?)

	* p (U+0070): X=257.0,Y=1.0 (should be at baseline 0?)

	* s (U+0073): X=369.5,Y=-1.0 (should be at baseline 0?)

	* x (U+0078): X=186.0,Y=-1.0 (should be at baseline 0?)

	* x (U+0078): X=933.0,Y=1083.0 (should be at x-height 1082?)

	* x (U+0078): X=186.0,Y=-1.0 (should be at baseline 0?)

	* braceright (U+007D): X=11.5,Y=-924.0 (should be at descender -926?)

	* braceright (U+007D): X=394.5,Y=2007.0 (should be at cap-height 2008?)

	* exclamdown (U+00A1): X=471.0,Y=2009.0 (should be at cap-height 2008?)

	* yen (U+00A5): X=229.0,Y=-0.5 (should be at baseline 0?)

	* registered (U+00AE): X=1307.0,Y=2010.0 (should be at cap-height 2008?)

	* registered (U+00AE): X=492.5,Y=2010.0 (should be at cap-height 2008?)

	* degree (U+00B0): X=482.0,Y=2009.0 (should be at cap-height 2008?)

	* cedilla (U+00B8): X=60.0,Y=-2.0 (should be at baseline 0?)

	* Agrave (U+00C0): X=792.0,Y=2640.5 (should be at ascender 2642?)

	* Aring (U+00C5): X=967.5,Y=2640.5 (should be at ascender 2642?)

	* Ccedilla (U+00C7): X=492.0,Y=-2.0 (should be at baseline 0?)

	* Egrave (U+00C8): X=777.0,Y=2640.5 (should be at ascender 2642?)

	* Igrave (U+00CC): X=342.0,Y=2640.5 (should be at ascender 2642?)

	* Ograve (U+00D2): X=738.0,Y=2640.5 (should be at ascender 2642?)

	* Oslash (U+00D8): X=440.0,Y=-2.0 (should be at baseline 0?)

	* Ugrave (U+00D9): X=1294.0,Y=1.0 (should be at baseline 0?)

	* Ugrave (U+00D9): X=852.0,Y=2640.5 (should be at ascender 2642?)

	* Uacute (U+00DA): X=1294.0,Y=1.0 (should be at baseline 0?)

	* Ucircumflex (U+00DB): X=1294.0,Y=1.0 (should be at baseline 0?)

	* Udieresis (U+00DC): X=1294.0,Y=1.0 (should be at baseline 0?)

	* germandbls (U+00DF): X=218.0,Y=-1.0 (should be at baseline 0?)

	* germandbls (U+00DF): X=218.0,Y=-1.0 (should be at baseline 0?)

	* ccedilla (U+00E7): X=307.0,Y=-2.0 (should be at baseline 0?)

	* thorn (U+00FE): X=520.0,Y=1.0 (should be at baseline 0?)

	* thorn (U+00FE): X=279.0,Y=1.0 (should be at baseline 0?)

	* Iogonek (U+012E): X=103.5,Y=2.0 (should be at baseline 0?)

	* Lcaron (U+013D): X=1092.0,Y=2009.0 (should be at cap-height 2008?)

	* lcaron (U+013E): X=633.5,Y=2008.5 (should be at cap-height 2008?)

	* sacute (U+015B): X=369.5,Y=-1.0 (should be at baseline 0?)

	* Scedilla (U+015E): X=480.0,Y=-2.0 (should be at baseline 0?)

	* scedilla (U+015F): X=369.5,Y=-1.0 (should be at baseline 0?)

	* scedilla (U+015F): X=306.0,Y=-2.0 (should be at baseline 0?)

	* scaron (U+0161): X=369.5,Y=-1.0 (should be at baseline 0?)

	* uni0162 (U+0162): X=483.0,Y=-2.0 (should be at baseline 0?)

	* uni0163 (U+0163): X=293.0,Y=-2.0 (should be at baseline 0?)

	* tcaron (U+0165): X=979.5,Y=2010.0 (should be at cap-height 2008?)

	* Utilde (U+0168): X=1294.0,Y=1.0 (should be at baseline 0?)

	* Umacron (U+016A): X=1294.0,Y=1.0 (should be at baseline 0?)

	* Ubreve (U+016C): X=1294.0,Y=1.0 (should be at baseline 0?)

	* Uring (U+016E): X=1294.0,Y=1.0 (should be at baseline 0?)

	* Uring (U+016E): X=1027.5,Y=2640.5 (should be at ascender 2642?)

	* Uhungarumlaut (U+0170): X=1294.0,Y=1.0 (should be at baseline 0?)

	* Uogonek (U+0172): X=1294.0,Y=1.0 (should be at baseline 0?)

	* uni01D3 (U+01D3): X=1294.0,Y=1.0 (should be at baseline 0?)

	* uni0219 (U+0219): X=369.5,Y=-1.0 (should be at baseline 0?)

	* ogonek (U+02DB): X=413.0,Y=-2.0 (should be at baseline 0?)

	* uni0327 (U+0327): X=60.0,Y=-2.0 (should be at baseline 0?)

	* uni0328 (U+0328): X=413.0,Y=-2.0 (should be at baseline 0?)

	* uni1E02 (U+1E02): X=461.0,Y=2006.0 (should be at cap-height 2008?)

	* uni1E1E (U+1E1E): X=461.0,Y=2009.0 (should be at cap-height 2008?)

	* uni1E1E (U+1E1E): X=1423.0,Y=2009.0 (should be at cap-height 2008?)

	* Wgrave (U+1E80): X=1198.0,Y=2640.5 (should be at ascender 2642?)

	* uni1E9E (U+1E9E): X=706.0,Y=1.0 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=474.0,Y=2007.0 (should be at cap-height 2008?)

	* uni1E9E (U+1E9E): X=1642.0,Y=2007.0 (should be at cap-height 2008?)

	* Ygrave (U+1EF2): X=685.0,Y=2640.5 (should be at ascender 2642?)

	* Euro (U+20AC): X=970.0,Y=2.0 (should be at baseline 0?)

	* Euro (U+20AC): X=970.0,Y=2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* A (U+0041): L<<1001.0,1137.0>--<951.0,1504.0>> -> L<<951.0,1504.0>--<906.0,1834.0>>

	* A (U+0041): L<<906.0,1834.0>--<765.0,1504.0>> -> L<<765.0,1504.0>--<608.0,1137.0>>

	* AE (U+00C6): L<<1031.0,1840.0>--<923.0,1579.0>> -> L<<923.0,1579.0>--<704.0,1139.0>>

	* AE (U+00C6): L<<1073.0,1139.0>--<1041.0,1561.0>> -> L<<1041.0,1561.0>--<1031.0,1840.0>>

	* Aacute (U+00C1): L<<1001.0,1137.0>--<951.0,1504.0>> -> L<<951.0,1504.0>--<906.0,1834.0>>

	* Aacute (U+00C1): L<<906.0,1834.0>--<765.0,1504.0>> -> L<<765.0,1504.0>--<608.0,1137.0>>

	* Abreve (U+0102): L<<1001.0,1137.0>--<951.0,1504.0>> -> L<<951.0,1504.0>--<906.0,1834.0>>

	* Abreve (U+0102): L<<906.0,1834.0>--<765.0,1504.0>> -> L<<765.0,1504.0>--<608.0,1137.0>>

	* Acircumflex (U+00C2): L<<1001.0,1137.0>--<951.0,1504.0>> -> L<<951.0,1504.0>--<906.0,1834.0>>

	* Acircumflex (U+00C2): L<<906.0,1834.0>--<765.0,1504.0>> -> L<<765.0,1504.0>--<608.0,1137.0>>

	* Adieresis (U+00C4): L<<1001.0,1137.0>--<951.0,1504.0>> -> L<<951.0,1504.0>--<906.0,1834.0>>

	* Adieresis (U+00C4): L<<906.0,1834.0>--<765.0,1504.0>> -> L<<765.0,1504.0>--<608.0,1137.0>>

	* Agrave (U+00C0): L<<1001.0,1137.0>--<951.0,1504.0>> -> L<<951.0,1504.0>--<906.0,1834.0>>

	* Agrave (U+00C0): L<<906.0,1834.0>--<765.0,1504.0>> -> L<<765.0,1504.0>--<608.0,1137.0>>

	* Amacron (U+0100): L<<1001.0,1137.0>--<951.0,1504.0>> -> L<<951.0,1504.0>--<906.0,1834.0>>

	* Amacron (U+0100): L<<906.0,1834.0>--<765.0,1504.0>> -> L<<765.0,1504.0>--<608.0,1137.0>>

	* Aogonek (U+0104): L<<1001.0,1137.0>--<951.0,1504.0>> -> L<<951.0,1504.0>--<906.0,1834.0>>

	* Aogonek (U+0104): L<<906.0,1834.0>--<765.0,1504.0>> -> L<<765.0,1504.0>--<608.0,1137.0>>

	* Aring (U+00C5): L<<1001.0,1137.0>--<951.0,1504.0>> -> L<<951.0,1504.0>--<906.0,1834.0>>

	* Aring (U+00C5): L<<906.0,1834.0>--<765.0,1504.0>> -> L<<765.0,1504.0>--<608.0,1137.0>>

	* Atilde (U+00C3): L<<1001.0,1137.0>--<951.0,1504.0>> -> L<<951.0,1504.0>--<906.0,1834.0>>

	* Atilde (U+00C3): L<<906.0,1834.0>--<765.0,1504.0>> -> L<<765.0,1504.0>--<608.0,1137.0>>

	* V (U+0056): L<<335.0,1948.0>--<561.0,477.0>> -> L<<561.0,477.0>--<589.0,274.0>>

	* V (U+0056): L<<589.0,274.0>--<664.0,475.0>> -> L<<664.0,475.0>--<1250.0,1942.0>>

	* W (U+0057): L<<1287.0,1769.0>--<1204.0,1534.0>> -> L<<1204.0,1534.0>--<635.0,71.0>>

	* W (U+0057): L<<1386.0,1948.0>--<1583.0,591.0>> -> L<<1583.0,591.0>--<1628.0,248.0>>

	* W (U+0057): L<<1540.0,65.0>--<1324.0,1521.0>> -> L<<1324.0,1521.0>--<1287.0,1769.0>>

	* W (U+0057): L<<1628.0,248.0>--<1752.0,575.0>> -> L<<1752.0,575.0>--<2291.0,1942.0>>

	* W (U+0057): L<<335.0,1948.0>--<532.0,583.0>> -> L<<532.0,583.0>--<582.0,265.0>>

	* W (U+0057): L<<582.0,265.0>--<704.0,580.0>> -> L<<704.0,580.0>--<1233.0,1945.0>>

	* Wacute (U+1E82): L<<1287.0,1769.0>--<1204.0,1534.0>> -> L<<1204.0,1534.0>--<635.0,71.0>>

	* Wacute (U+1E82): L<<1386.0,1948.0>--<1583.0,591.0>> -> L<<1583.0,591.0>--<1628.0,248.0>>

	* Wacute (U+1E82): L<<1540.0,65.0>--<1324.0,1521.0>> -> L<<1324.0,1521.0>--<1287.0,1769.0>>

	* Wacute (U+1E82): L<<1628.0,248.0>--<1752.0,575.0>> -> L<<1752.0,575.0>--<2291.0,1942.0>>

	* Wacute (U+1E82): L<<335.0,1948.0>--<532.0,583.0>> -> L<<532.0,583.0>--<582.0,265.0>>

	* Wacute (U+1E82): L<<582.0,265.0>--<704.0,580.0>> -> L<<704.0,580.0>--<1233.0,1945.0>>

	* Wcircumflex (U+0174): L<<1287.0,1769.0>--<1204.0,1534.0>> -> L<<1204.0,1534.0>--<635.0,71.0>>

	* Wcircumflex (U+0174): L<<1386.0,1948.0>--<1583.0,591.0>> -> L<<1583.0,591.0>--<1628.0,248.0>>

	* Wcircumflex (U+0174): L<<1540.0,65.0>--<1324.0,1521.0>> -> L<<1324.0,1521.0>--<1287.0,1769.0>>

	* Wcircumflex (U+0174): L<<1628.0,248.0>--<1752.0,575.0>> -> L<<1752.0,575.0>--<2291.0,1942.0>>

	* Wcircumflex (U+0174): L<<335.0,1948.0>--<532.0,583.0>> -> L<<532.0,583.0>--<582.0,265.0>>

	* Wcircumflex (U+0174): L<<582.0,265.0>--<704.0,580.0>> -> L<<704.0,580.0>--<1233.0,1945.0>>

	* Wdieresis (U+1E84): L<<1287.0,1769.0>--<1204.0,1534.0>> -> L<<1204.0,1534.0>--<635.0,71.0>>

	* Wdieresis (U+1E84): L<<1386.0,1948.0>--<1583.0,591.0>> -> L<<1583.0,591.0>--<1628.0,248.0>>

	* Wdieresis (U+1E84): L<<1540.0,65.0>--<1324.0,1521.0>> -> L<<1324.0,1521.0>--<1287.0,1769.0>>

	* Wdieresis (U+1E84): L<<1628.0,248.0>--<1752.0,575.0>> -> L<<1752.0,575.0>--<2291.0,1942.0>>

	* Wdieresis (U+1E84): L<<335.0,1948.0>--<532.0,583.0>> -> L<<532.0,583.0>--<582.0,265.0>>

	* Wdieresis (U+1E84): L<<582.0,265.0>--<704.0,580.0>> -> L<<704.0,580.0>--<1233.0,1945.0>>

	* Wgrave (U+1E80): L<<1287.0,1769.0>--<1204.0,1534.0>> -> L<<1204.0,1534.0>--<635.0,71.0>>

	* Wgrave (U+1E80): L<<1386.0,1948.0>--<1583.0,591.0>> -> L<<1583.0,591.0>--<1628.0,248.0>>

	* Wgrave (U+1E80): L<<1540.0,65.0>--<1324.0,1521.0>> -> L<<1324.0,1521.0>--<1287.0,1769.0>>

	* Wgrave (U+1E80): L<<1628.0,248.0>--<1752.0,575.0>> -> L<<1752.0,575.0>--<2291.0,1942.0>>

	* Wgrave (U+1E80): L<<335.0,1948.0>--<532.0,583.0>> -> L<<532.0,583.0>--<582.0,265.0>>

	* Wgrave (U+1E80): L<<582.0,265.0>--<704.0,580.0>> -> L<<704.0,580.0>--<1233.0,1945.0>>

	* oslash (U+00F8): L<<263.0,179.0>--<459.0,577.0>> -> L<<459.0,577.0>--<636.0,950.0>>

	* oslash (U+00F8): L<<739.0,896.0>--<555.0,523.0>> -> L<<555.0,523.0>--<357.0,106.0>>

	* uni01CD (U+01CD): L<<1001.0,1137.0>--<951.0,1504.0>> -> L<<951.0,1504.0>--<906.0,1834.0>>

	* uni01CD (U+01CD): L<<906.0,1834.0>--<765.0,1504.0>> -> L<<765.0,1504.0>--<608.0,1137.0>>

	* uni01DE (U+01DE): L<<1001.0,1137.0>--<951.0,1504.0>> -> L<<951.0,1504.0>--<906.0,1834.0>>

	* uni01DE (U+01DE): L<<906.0,1834.0>--<765.0,1504.0>> -> L<<765.0,1504.0>--<608.0,1137.0>>

	* uni0226 (U+0226): L<<1001.0,1137.0>--<951.0,1504.0>> -> L<<951.0,1504.0>--<906.0,1834.0>>

	* uni0226 (U+0226): L<<906.0,1834.0>--<765.0,1504.0>> -> L<<765.0,1504.0>--<608.0,1137.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* w (U+0077): L<<805.0,313.0>--<856.0,666.0>>/B<<856.0,666.0>-<750.0,403.0>-<662.5,253.5>> = 13.730520481405952

	* wacute (U+1E83): L<<805.0,313.0>--<856.0,666.0>>/B<<856.0,666.0>-<750.0,403.0>-<662.5,253.5>> = 13.730520481405952

	* wcircumflex (U+0175): L<<805.0,313.0>--<856.0,666.0>>/B<<856.0,666.0>-<750.0,403.0>-<662.5,253.5>> = 13.730520481405952

	* wdieresis (U+1E85): L<<805.0,313.0>--<856.0,666.0>>/B<<856.0,666.0>-<750.0,403.0>-<662.5,253.5>> = 13.730520481405952

	* wgrave (U+1E81): L<<805.0,313.0>--<856.0,666.0>>/B<<856.0,666.0>-<750.0,403.0>-<662.5,253.5>> = 13.730520481405952 [code: found-jaggy-segments]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 12 | 12 | 48 | 478 | 21 | 374 | 0 |
| 1% | 1% | 5% | 51% | 2% | 40% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
