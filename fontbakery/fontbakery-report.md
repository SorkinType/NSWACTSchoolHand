## FontBakery report

fontbakery version: 0.9.2

<details><summary><b>[20] Nswact-Bold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x02D9 (DOT ABOVE)


	- 0x00A8 (DIAERESIS)


	- 0x00B4 (ACUTE ACCENT)


	- 0x02DD (DOUBLE ACUTE ACCENT)


	- 0x02C6 (MODIFIER LETTER CIRCUMFLEX ACCENT)


	- 0x02C7 (CARON)


	- 0x02D8 (BREVE)


	- 0x02DA (RING ABOVE)


	- 0x00AF (MACRON)


	- 0x00B8 (CEDILLA)


	- 0x02DB (OGONEK)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 3418, but got 2642 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 945, but got 926 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have no contours even though they were expected to have some:

	- Glyph name: section	Expected: 2

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: Aacute	Expected: 3

	- Glyph name: Acircumflex	Expected: 3

	- Glyph name: Adieresis	Expected: 4

	- Glyph name: Aring	Expected: 3 or 4

	- Glyph name: AE	Expected: 2

	- Glyph name: Ccedilla	Expected: 1 or 2

	- Glyph name: Eacute	Expected: 2

	- Glyph name: Ecircumflex	Expected: 2

	- Glyph name: Edieresis	Expected: 3

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Eth	Expected: 2

	- Glyph name: Oacute	Expected: 3

	- Glyph name: Ocircumflex	Expected: 3

	- Glyph name: Odieresis	Expected: 4

	- Glyph name: Oslash	Expected: 2 or 3

	- Glyph name: Uacute	Expected: 2

	- Glyph name: Ucircumflex	Expected: 2

	- Glyph name: Udieresis	Expected: 3

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Thorn	Expected: 1 or 2

	- Glyph name: oslash	Expected: 3

	- Glyph name: Amacron	Expected: 3

	- Glyph name: Abreve	Expected: 3

	- Glyph name: Aogonek	Expected: 2 or 3

	- Glyph name: Cacute	Expected: 2

	- Glyph name: Cdotaccent	Expected: 2

	- Glyph name: Ccaron	Expected: 2

	- Glyph name: Dcaron	Expected: 3

	- Glyph name: Dcroat	Expected: 2

	- Glyph name: dcroat	Expected: 2

	- Glyph name: Emacron	Expected: 2

	- Glyph name: Edotaccent	Expected: 2

	- Glyph name: Eogonek	Expected: 1 or 2

	- Glyph name: Ecaron	Expected: 2

	- Glyph name: Gbreve	Expected: 2

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: uni0122	Expected: 2

	- Glyph name: Hbar	Expected: 2

	- Glyph name: Imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: uni0136	Expected: 2 or 3

	- Glyph name: Lacute	Expected: 2

	- Glyph name: uni013B	Expected: 2

	- Glyph name: Lcaron	Expected: 2

	- Glyph name: Lslash	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: Nacute	Expected: 2

	- Glyph name: uni0145	Expected: 2

	- Glyph name: Ncaron	Expected: 2

	- Glyph name: Eng	Expected: 1

	- Glyph name: eng	Expected: 1

	- Glyph name: Omacron	Expected: 3

	- Glyph name: Ohungarumlaut	Expected: 4

	- Glyph name: OE	Expected: 2

	- Glyph name: Racute	Expected: 3

	- Glyph name: uni0156	Expected: 3

	- Glyph name: Rcaron	Expected: 3

	- Glyph name: Sacute	Expected: 2

	- Glyph name: Scedilla	Expected: 1 or 2

	- Glyph name: Scaron	Expected: 2

	- Glyph name: Tcaron	Expected: 2

	- Glyph name: Umacron	Expected: 2

	- Glyph name: Ubreve	Expected: 2

	- Glyph name: Uring	Expected: 3

	- Glyph name: Uhungarumlaut	Expected: 3

	- Glyph name: Uogonek	Expected: 1

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Zacute	Expected: 2

	- Glyph name: Zdotaccent	Expected: 2

	- Glyph name: Zcaron	Expected: 2

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: Wacute	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: quotesinglbase	Expected: 1

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: AE	Expected: 2

	- Glyph name: Aacute	Expected: 3

	- Glyph name: Abreve	Expected: 3

	- Glyph name: Acircumflex	Expected: 3

	- Glyph name: Adieresis	Expected: 4

	- Glyph name: Amacron	Expected: 3

	- Glyph name: Aogonek	Expected: 2 or 3

	- Glyph name: Aring	Expected: 3 or 4

	- Glyph name: Cacute	Expected: 2

	- Glyph name: Ccaron	Expected: 2

	- Glyph name: Ccedilla	Expected: 1 or 2

	- Glyph name: Cdotaccent	Expected: 2

	- Glyph name: Dcaron	Expected: 3

	- Glyph name: Dcroat	Expected: 2

	- Glyph name: Eacute	Expected: 2

	- Glyph name: Ecaron	Expected: 2

	- Glyph name: Ecircumflex	Expected: 2

	- Glyph name: Edieresis	Expected: 3

	- Glyph name: Edotaccent	Expected: 2

	- Glyph name: Emacron	Expected: 2

	- Glyph name: Eng	Expected: 1

	- Glyph name: Eogonek	Expected: 1 or 2

	- Glyph name: Eth	Expected: 2

	- Glyph name: Gbreve	Expected: 2

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: Hbar	Expected: 2

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: Imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: Lacute	Expected: 2

	- Glyph name: Lcaron	Expected: 2

	- Glyph name: Lslash	Expected: 1

	- Glyph name: Nacute	Expected: 2

	- Glyph name: Ncaron	Expected: 2

	- Glyph name: OE	Expected: 2

	- Glyph name: Oacute	Expected: 3

	- Glyph name: Ocircumflex	Expected: 3

	- Glyph name: Odieresis	Expected: 4

	- Glyph name: Ohungarumlaut	Expected: 4

	- Glyph name: Omacron	Expected: 3

	- Glyph name: Oslash	Expected: 2 or 3

	- Glyph name: Racute	Expected: 3

	- Glyph name: Rcaron	Expected: 3

	- Glyph name: Sacute	Expected: 2

	- Glyph name: Scaron	Expected: 2

	- Glyph name: Tcaron	Expected: 2

	- Glyph name: Thorn	Expected: 1 or 2

	- Glyph name: Uacute	Expected: 2

	- Glyph name: Ubreve	Expected: 2

	- Glyph name: Ucircumflex	Expected: 2

	- Glyph name: Udieresis	Expected: 3

	- Glyph name: Uhungarumlaut	Expected: 3

	- Glyph name: Umacron	Expected: 2

	- Glyph name: Uogonek	Expected: 1

	- Glyph name: Uring	Expected: 3

	- Glyph name: Wacute	Expected: 2

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Zacute	Expected: 2

	- Glyph name: Zcaron	Expected: 2

	- Glyph name: Zdotaccent	Expected: 2

	- Glyph name: dcroat	Expected: 2

	- Glyph name: eng	Expected: 1

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: oslash	Expected: 3

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: quotesinglbase	Expected: 1

	- Glyph name: section	Expected: 2

	- Glyph name: uni0122	Expected: 2

	- Glyph name: uni0136	Expected: 2 or 3

	- Glyph name: uni013B	Expected: 2

	- Glyph name: uni0145	Expected: 2

	- Glyph name: uni0156	Expected: 3

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni1E9E	Expected: 1
 [code: no-contour]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Atilde	Contours detected: 2	Expected: 3

	- Glyph name: Ntilde	Contours detected: 1	Expected: 2

	- Glyph name: Otilde	Contours detected: 2	Expected: 3

	- Glyph name: atilde	Contours detected: 2	Expected: 3

	- Glyph name: ntilde	Contours detected: 1	Expected: 2

	- Glyph name: otilde	Contours detected: 2	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Atilde	Contours detected: 2	Expected: 3

	- Glyph name: Ntilde	Contours detected: 1	Expected: 2

	- Glyph name: Otilde	Contours detected: 2	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: atilde	Contours detected: 2	Expected: 3

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: ntilde	Contours detected: 1	Expected: 2

	- Glyph name: otilde	Contours detected: 2	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* 🔥 **FAIL** Font is not italic, so post.italicAngle should be equal to zero. [code: non-zero-upright]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, coptic, tifinagh, cherokee
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, syriac, tai-le, math, old-permic, coptic, canadian-aboriginal, tifinagh
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2000 EN QUAD: not included in any glyphset definition
 * U+2001 EM QUAD: not included in any glyphset definition
 * U+2003 EM SPACE: try adding nushu
 * U+2004 THREE-PER-EM SPACE: not included in any glyphset definition
 * U+2005 FOUR-PER-EM SPACE: not included in any glyphset definition
 * U+2006 SIX-PER-EM SPACE: not included in any glyphset definition
 * U+2007 FIGURE SPACE: not included in any glyphset definition
 * U+2008 PUNCTUATION SPACE: not included in any glyphset definition
 * U+200A HAIR SPACE: not included in any glyphset definition
 * U+200C ZERO WIDTH NON-JOINER: try adding one of: grantha, warang-citi, nko, cham, brahmi, tai-tham, syriac, syloti-nagri, saurashtra, new-tai-lue, duployan, batak, rejang, devanagari, gujarati, dogra, tifinagh, phags-pa, kayah-li, yi, buhid, mongolian, manichaean, tai-le, telugu, hatran, balinese, modi, pahawh-hmong, bengali, meetei-mayek, thai, sogdian, siddham, chakma, kannada, tamil, avestan, lepcha, gunjala-gondi, gurmukhi, mahajani, oriya, takri, hanifi-rohingya, kaithi, mandaic, tagbanwa, thaana, khojki, tirhuta, hanunoo, psalter-pahlavi, malayalam, sundanese, limbu, kharoshthi, buginese, myanmar, sinhala, javanese, tai-viet, khmer, newa, sharada, tibetan, tagalog, khudawadi
 * U+200D ZERO WIDTH JOINER: try adding one of: grantha, warang-citi, nko, cham, brahmi, tai-tham, syriac, syloti-nagri, saurashtra, new-tai-lue, duployan, batak, rejang, devanagari, gujarati, dogra, tifinagh, phags-pa, kayah-li, yi, buhid, mongolian, manichaean, tai-le, telugu, balinese, modi, pahawh-hmong, old-hungarian, bengali, meetei-mayek, thai, siddham, chakma, kannada, tamil, avestan, lepcha, gunjala-gondi, gurmukhi, mahajani, oriya, takri, hanifi-rohingya, kaithi, mandaic, tagbanwa, thaana, khojki, tirhuta, hanunoo, psalter-pahlavi, malayalam, sundanese, limbu, kharoshthi, buginese, myanmar, sinhala, javanese, tai-viet, newa, sharada, tibetan, tagalog, khudawadi
 * U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, yi
 * U+205F MEDIUM MATHEMATICAL SPACE: not included in any glyphset definition
 * U+221E INFINITY: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.784x (3568) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 993 among a set of 3 math glyphs.
The following math glyphs have a different width, though:

Width = 990:
minus, plus

Width = 903:
less

Width = 902:
greater

Width = 909:
plusminus

Width = 994:
multiply

Width = 987:
divide

Width = 931:
lessequal

Width = 927:
greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* percent (U+0025): X=1287.0,Y=2.0 (should be at baseline 0?)

	* C (U+0043): X=1238.0,Y=2009.5 (should be at cap-height 2008?)

	* X (U+0058): X=469.0,Y=2009.0 (should be at cap-height 2008?)

	* X (U+0058): X=1449.5,Y=2007.0 (should be at cap-height 2008?)

	* X (U+0058): X=328.5,Y=2.0 (should be at baseline 0?)

	* Y (U+0059): X=393.0,Y=1.0 (should be at baseline 0?)

	* Z (U+005A): X=394.0,Y=2009.0 (should be at cap-height 2008?)

	* Z (U+005A): X=1398.0,Y=2009.0 (should be at cap-height 2008?)

	* c (U+0063): X=899.5,Y=1084.0 (should be at x-height 1082?)

	* g (U+0067): X=299.0,Y=-1.5 (should be at baseline 0?)

	* q (U+0071): X=715.5,Y=-925.0 (should be at descender -926?)

	* braceleft (U+007B): X=613.5,Y=2006.0 (should be at cap-height 2008?)

	* braceright (U+007D): X=-47.5,Y=-924.0 (should be at descender -926?)

	* braceright (U+007D): X=239.5,Y=2009.5 (should be at cap-height 2008?)

	* yen (U+00A5): X=273.0,Y=1.0 (should be at baseline 0?)

	* gbreve (U+011F): X=299.0,Y=-1.5 (should be at baseline 0?)

	* gdotaccent (U+0121): X=299.0,Y=-1.5 (should be at baseline 0?)

	* uni0123 (U+0123): X=299.0,Y=-1.5 (should be at baseline 0?)

	* Ygrave (U+1EF2): X=393.0,Y=1.0 (should be at baseline 0?)

	* notequal (U+2260): X=378.5,Y=-1.5 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* dollar (U+0024) contains a short segment B<<403.0,268.0>-<420.0,268.0>-<439.0,268.0>>

	* dollar (U+0024) contains a short segment B<<439.0,268.0>-<458.0,268.0>-<478.0,269.0>>

	* ampersand (U+0026) contains a short segment B<<1030.0,700.0>-<1038.0,713.0>-<1046.0,726.0>>

	* ampersand (U+0026) contains a short segment B<<1046.0,726.0>-<1054.0,739.0>-<1061.0,752.0>>

	* asterisk (U+002A) contains a short segment L<<350.0,1331.0>--<335.0,1321.0>>

	* asterisk (U+002A) contains a short segment L<<685.0,1865.0>--<697.0,1873.0>>

	* at (U+0040) contains a short segment B<<1134.0,122.0>-<1118.0,151.0>-<1110.0,184.0>>

	* at (U+0040) contains a short segment B<<1372.0,338.5>-<1374.0,286.0>-<1403.0,286.0>>

	* at (U+0040) contains a short segment B<<1172.0,-82.0>-<1196.0,-113.0>-<1203.0,-147.0>>

	* at (U+0040) contains a short segment B<<1203.0,-147.0>-<1210.0,-181.0>-<1185.0,-220.5>>

	* K (U+004B) contains a short segment B<<1509.0,174.5>-<1518.0,148.0>-<1518.0,125.0>>

	* W (U+0057) contains a short segment B<<2604.5,1906.0>-<2615.0,1864.0>-<2599.0,1826.0>>

	* p (U+0070) contains a short segment L<<467.0,252.0>--<471.0,252.0>>

	* v (U+0076) contains a short segment B<<470.0,256.0>-<475.0,237.0>-<488.0,237.0>>

	* cent (U+00A2) contains a short segment L<<304.0,-20.0>--<291.0,-20.0>>

	* cent (U+00A2) contains a short segment B<<532.0,497.0>-<533.0,502.0>-<533.0,500.0>>

	* yen (U+00A5) contains a short segment L<<240.0,362.0>--<235.0,362.0>>

	* yen (U+00A5) contains a short segment L<<524.0,1030.0>--<523.0,1032.0>>

	* yen (U+00A5) contains a short segment L<<1000.0,1023.0>--<1003.0,1023.0>>

	* ae (U+00E6) contains a short segment B<<1152.0,427.0>-<1151.0,411.0>-<1149.5,394.5>>

	* ae (U+00E6) contains a short segment B<<1149.5,394.5>-<1148.0,378.0>-<1147.0,364.0>>

	* thorn (U+00FE) contains a short segment L<<467.0,252.0>--<471.0,252.0>>

	* oe (U+0153) contains a short segment B<<1032.0,427.0>-<1031.0,411.0>-<1029.5,394.5>>

	* oe (U+0153) contains a short segment B<<1029.5,394.5>-<1028.0,378.0>-<1027.0,364.0>>

	* Wgrave (U+1E80) contains a short segment B<<2604.5,1906.0>-<2615.0,1864.0>-<2599.0,1826.0>>

	* Euro (U+20AC) contains a short segment B<<366.0,1059.0>-<368.0,1070.0>-<369.5,1080.0>>

	* Euro (U+20AC) contains a short segment B<<369.5,1080.0>-<371.0,1090.0>-<372.0,1100.0>>

	* notequal (U+2260) contains a short segment L<<837.0,1030.0>--<863.0,1030.0>>

	* lessequal (U+2264) contains a short segment L<<183.0,624.0>--<183.0,626.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* A (U+0041): L<<1017.0,1082.0>--<989.0,1455.0>> -> L<<989.0,1455.0>--<973.0,1644.0>>

	* A (U+0041): L<<973.0,1644.0>--<905.0,1459.0>> -> L<<905.0,1459.0>--<769.0,1082.0>>

	* Agrave (U+00C0): L<<1017.0,1082.0>--<989.0,1455.0>> -> L<<989.0,1455.0>--<973.0,1644.0>>

	* Agrave (U+00C0): L<<973.0,1644.0>--<905.0,1459.0>> -> L<<905.0,1459.0>--<769.0,1082.0>>

	* Atilde (U+00C3): L<<1017.0,1082.0>--<989.0,1455.0>> -> L<<989.0,1455.0>--<973.0,1644.0>>

	* Atilde (U+00C3): L<<973.0,1644.0>--<905.0,1459.0>> -> L<<905.0,1459.0>--<769.0,1082.0>>

	* V (U+0056): L<<563.0,1886.0>--<717.0,939.0>> -> L<<717.0,939.0>--<750.0,673.0>>

	* V (U+0056): L<<750.0,673.0>--<844.0,939.0>> -> L<<844.0,939.0>--<1253.0,1909.0>>

	* W (U+0057): L<<1379.0,1431.0>--<1327.0,1272.0>> -> L<<1327.0,1272.0>--<895.0,133.0>>

	* W (U+0057): L<<1572.0,99.0>--<1395.0,1272.0>> -> L<<1395.0,1272.0>--<1379.0,1431.0>>

	* W (U+0057): L<<1606.0,1886.0>--<1754.0,853.0>> -> L<<1754.0,853.0>--<1783.0,596.0>>

	* W (U+0057): L<<1783.0,596.0>--<1879.0,853.0>> -> L<<1879.0,853.0>--<2297.0,1904.0>>

	* W (U+0057): L<<563.0,1886.0>--<706.0,866.0>> -> L<<706.0,866.0>--<745.0,555.0>>

	* W (U+0057): L<<745.0,555.0>--<854.0,856.0>> -> L<<854.0,856.0>--<1252.0,1891.0>>

	* Wgrave (U+1E80): L<<1379.0,1431.0>--<1327.0,1272.0>> -> L<<1327.0,1272.0>--<895.0,133.0>>

	* Wgrave (U+1E80): L<<1572.0,99.0>--<1395.0,1272.0>> -> L<<1395.0,1272.0>--<1379.0,1431.0>>

	* Wgrave (U+1E80): L<<1606.0,1886.0>--<1754.0,853.0>> -> L<<1754.0,853.0>--<1783.0,596.0>>

	* Wgrave (U+1E80): L<<1783.0,596.0>--<1879.0,853.0>> -> L<<1879.0,853.0>--<2297.0,1904.0>>

	* Wgrave (U+1E80): L<<563.0,1886.0>--<706.0,866.0>> -> L<<706.0,866.0>--<745.0,555.0>>

	* Wgrave (U+1E80): L<<745.0,555.0>--<854.0,856.0>> -> L<<854.0,856.0>--<1252.0,1891.0>>

	* yen (U+00A5): L<<524.0,1030.0>--<523.0,1032.0>> -> L<<523.0,1032.0>--<158.0,1802.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* cent (U+00A2): L<<576.0,831.0>--<532.0,497.0>>/B<<532.0,497.0>-<533.0,502.0>-<533.0,500.0>> = 3.80520002340806 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details><details><summary><b>[19] Nswact-Medium.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x02D9 (DOT ABOVE)


	- 0x00A8 (DIAERESIS)


	- 0x00B4 (ACUTE ACCENT)


	- 0x02DD (DOUBLE ACUTE ACCENT)


	- 0x02C6 (MODIFIER LETTER CIRCUMFLEX ACCENT)


	- 0x02C7 (CARON)


	- 0x02D8 (BREVE)


	- 0x02DA (RING ABOVE)


	- 0x00AF (MACRON)


	- 0x00B8 (CEDILLA)


	- 0x02DB (OGONEK)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 3418, but got 2642 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 945, but got 926 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have no contours even though they were expected to have some:

	- Glyph name: section	Expected: 2

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: Aacute	Expected: 3

	- Glyph name: Acircumflex	Expected: 3

	- Glyph name: Adieresis	Expected: 4

	- Glyph name: Aring	Expected: 3 or 4

	- Glyph name: AE	Expected: 2

	- Glyph name: Ccedilla	Expected: 1 or 2

	- Glyph name: Eacute	Expected: 2

	- Glyph name: Ecircumflex	Expected: 2

	- Glyph name: Edieresis	Expected: 3

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Eth	Expected: 2

	- Glyph name: Oacute	Expected: 3

	- Glyph name: Ocircumflex	Expected: 3

	- Glyph name: Odieresis	Expected: 4

	- Glyph name: Oslash	Expected: 2 or 3

	- Glyph name: Uacute	Expected: 2

	- Glyph name: Ucircumflex	Expected: 2

	- Glyph name: Udieresis	Expected: 3

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Thorn	Expected: 1 or 2

	- Glyph name: oslash	Expected: 3

	- Glyph name: Amacron	Expected: 3

	- Glyph name: Abreve	Expected: 3

	- Glyph name: Aogonek	Expected: 2 or 3

	- Glyph name: Cacute	Expected: 2

	- Glyph name: Cdotaccent	Expected: 2

	- Glyph name: Ccaron	Expected: 2

	- Glyph name: Dcaron	Expected: 3

	- Glyph name: Dcroat	Expected: 2

	- Glyph name: dcroat	Expected: 2

	- Glyph name: Emacron	Expected: 2

	- Glyph name: Edotaccent	Expected: 2

	- Glyph name: Eogonek	Expected: 1 or 2

	- Glyph name: Ecaron	Expected: 2

	- Glyph name: Gbreve	Expected: 2

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: uni0122	Expected: 2

	- Glyph name: Hbar	Expected: 2

	- Glyph name: Imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: uni0136	Expected: 2 or 3

	- Glyph name: Lacute	Expected: 2

	- Glyph name: uni013B	Expected: 2

	- Glyph name: Lcaron	Expected: 2

	- Glyph name: Lslash	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: Nacute	Expected: 2

	- Glyph name: uni0145	Expected: 2

	- Glyph name: Ncaron	Expected: 2

	- Glyph name: Eng	Expected: 1

	- Glyph name: eng	Expected: 1

	- Glyph name: Omacron	Expected: 3

	- Glyph name: Ohungarumlaut	Expected: 4

	- Glyph name: OE	Expected: 2

	- Glyph name: Racute	Expected: 3

	- Glyph name: uni0156	Expected: 3

	- Glyph name: Rcaron	Expected: 3

	- Glyph name: Sacute	Expected: 2

	- Glyph name: Scedilla	Expected: 1 or 2

	- Glyph name: Scaron	Expected: 2

	- Glyph name: Tcaron	Expected: 2

	- Glyph name: Umacron	Expected: 2

	- Glyph name: Ubreve	Expected: 2

	- Glyph name: Uring	Expected: 3

	- Glyph name: Uhungarumlaut	Expected: 3

	- Glyph name: Uogonek	Expected: 1

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Zacute	Expected: 2

	- Glyph name: Zdotaccent	Expected: 2

	- Glyph name: Zcaron	Expected: 2

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: Wacute	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: quotesinglbase	Expected: 1

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: AE	Expected: 2

	- Glyph name: Aacute	Expected: 3

	- Glyph name: Abreve	Expected: 3

	- Glyph name: Acircumflex	Expected: 3

	- Glyph name: Adieresis	Expected: 4

	- Glyph name: Amacron	Expected: 3

	- Glyph name: Aogonek	Expected: 2 or 3

	- Glyph name: Aring	Expected: 3 or 4

	- Glyph name: Cacute	Expected: 2

	- Glyph name: Ccaron	Expected: 2

	- Glyph name: Ccedilla	Expected: 1 or 2

	- Glyph name: Cdotaccent	Expected: 2

	- Glyph name: Dcaron	Expected: 3

	- Glyph name: Dcroat	Expected: 2

	- Glyph name: Eacute	Expected: 2

	- Glyph name: Ecaron	Expected: 2

	- Glyph name: Ecircumflex	Expected: 2

	- Glyph name: Edieresis	Expected: 3

	- Glyph name: Edotaccent	Expected: 2

	- Glyph name: Emacron	Expected: 2

	- Glyph name: Eng	Expected: 1

	- Glyph name: Eogonek	Expected: 1 or 2

	- Glyph name: Eth	Expected: 2

	- Glyph name: Gbreve	Expected: 2

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: Hbar	Expected: 2

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: Imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: Lacute	Expected: 2

	- Glyph name: Lcaron	Expected: 2

	- Glyph name: Lslash	Expected: 1

	- Glyph name: Nacute	Expected: 2

	- Glyph name: Ncaron	Expected: 2

	- Glyph name: OE	Expected: 2

	- Glyph name: Oacute	Expected: 3

	- Glyph name: Ocircumflex	Expected: 3

	- Glyph name: Odieresis	Expected: 4

	- Glyph name: Ohungarumlaut	Expected: 4

	- Glyph name: Omacron	Expected: 3

	- Glyph name: Oslash	Expected: 2 or 3

	- Glyph name: Racute	Expected: 3

	- Glyph name: Rcaron	Expected: 3

	- Glyph name: Sacute	Expected: 2

	- Glyph name: Scaron	Expected: 2

	- Glyph name: Tcaron	Expected: 2

	- Glyph name: Thorn	Expected: 1 or 2

	- Glyph name: Uacute	Expected: 2

	- Glyph name: Ubreve	Expected: 2

	- Glyph name: Ucircumflex	Expected: 2

	- Glyph name: Udieresis	Expected: 3

	- Glyph name: Uhungarumlaut	Expected: 3

	- Glyph name: Umacron	Expected: 2

	- Glyph name: Uogonek	Expected: 1

	- Glyph name: Uring	Expected: 3

	- Glyph name: Wacute	Expected: 2

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Zacute	Expected: 2

	- Glyph name: Zcaron	Expected: 2

	- Glyph name: Zdotaccent	Expected: 2

	- Glyph name: dcroat	Expected: 2

	- Glyph name: eng	Expected: 1

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: oslash	Expected: 3

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: quotesinglbase	Expected: 1

	- Glyph name: section	Expected: 2

	- Glyph name: uni0122	Expected: 2

	- Glyph name: uni0136	Expected: 2 or 3

	- Glyph name: uni013B	Expected: 2

	- Glyph name: uni0145	Expected: 2

	- Glyph name: uni0156	Expected: 3

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni1E9E	Expected: 1
 [code: no-contour]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Atilde	Contours detected: 2	Expected: 3

	- Glyph name: Ntilde	Contours detected: 1	Expected: 2

	- Glyph name: Otilde	Contours detected: 2	Expected: 3

	- Glyph name: atilde	Contours detected: 2	Expected: 3

	- Glyph name: ntilde	Contours detected: 1	Expected: 2

	- Glyph name: otilde	Contours detected: 2	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Atilde	Contours detected: 2	Expected: 3

	- Glyph name: Ntilde	Contours detected: 1	Expected: 2

	- Glyph name: Otilde	Contours detected: 2	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: atilde	Contours detected: 2	Expected: 3

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: ntilde	Contours detected: 1	Expected: 2

	- Glyph name: otilde	Contours detected: 2	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* 🔥 **FAIL** Font is not italic, so post.italicAngle should be equal to zero. [code: non-zero-upright]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, coptic, tifinagh, cherokee
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, syriac, tai-le, math, old-permic, coptic, canadian-aboriginal, tifinagh
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2000 EN QUAD: not included in any glyphset definition
 * U+2001 EM QUAD: not included in any glyphset definition
 * U+2003 EM SPACE: try adding nushu
 * U+2004 THREE-PER-EM SPACE: not included in any glyphset definition
 * U+2005 FOUR-PER-EM SPACE: not included in any glyphset definition
 * U+2006 SIX-PER-EM SPACE: not included in any glyphset definition
 * U+2007 FIGURE SPACE: not included in any glyphset definition
 * U+2008 PUNCTUATION SPACE: not included in any glyphset definition
 * U+200A HAIR SPACE: not included in any glyphset definition
 * U+200C ZERO WIDTH NON-JOINER: try adding one of: grantha, warang-citi, nko, cham, brahmi, tai-tham, syriac, syloti-nagri, saurashtra, new-tai-lue, duployan, batak, rejang, devanagari, gujarati, dogra, tifinagh, phags-pa, kayah-li, yi, buhid, mongolian, manichaean, tai-le, telugu, hatran, balinese, modi, pahawh-hmong, bengali, meetei-mayek, thai, sogdian, siddham, chakma, kannada, tamil, avestan, lepcha, gunjala-gondi, gurmukhi, mahajani, oriya, takri, hanifi-rohingya, kaithi, mandaic, tagbanwa, thaana, khojki, tirhuta, hanunoo, psalter-pahlavi, malayalam, sundanese, limbu, kharoshthi, buginese, myanmar, sinhala, javanese, tai-viet, khmer, newa, sharada, tibetan, tagalog, khudawadi
 * U+200D ZERO WIDTH JOINER: try adding one of: grantha, warang-citi, nko, cham, brahmi, tai-tham, syriac, syloti-nagri, saurashtra, new-tai-lue, duployan, batak, rejang, devanagari, gujarati, dogra, tifinagh, phags-pa, kayah-li, yi, buhid, mongolian, manichaean, tai-le, telugu, balinese, modi, pahawh-hmong, old-hungarian, bengali, meetei-mayek, thai, siddham, chakma, kannada, tamil, avestan, lepcha, gunjala-gondi, gurmukhi, mahajani, oriya, takri, hanifi-rohingya, kaithi, mandaic, tagbanwa, thaana, khojki, tirhuta, hanunoo, psalter-pahlavi, malayalam, sundanese, limbu, kharoshthi, buginese, myanmar, sinhala, javanese, tai-viet, newa, sharada, tibetan, tagalog, khudawadi
 * U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, yi
 * U+205F MEDIUM MATHEMATICAL SPACE: not included in any glyphset definition
 * U+221E INFINITY: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.784x (3568) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 910 among a set of 3 math glyphs.
The following math glyphs have a different width, though:

Width = 820:
less

Width = 913:
approxequal, notequal, equal

Width = 821:
greater

Width = 822:
plusminus

Width = 912:
multiply

Width = 846:
lessequal

Width = 848:
greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* dollar (U+0024): X=485.0,Y=-2.0 (should be at baseline 0?)

	* parenleft (U+0028): X=494.5,Y=-927.5 (should be at descender -926?)

	* slash (U+002F): X=754.0,Y=2006.0 (should be at cap-height 2008?)

	* seven (U+0037): X=237.0,Y=2007.0 (should be at cap-height 2008?)

	* seven (U+0037): X=1095.0,Y=2007.0 (should be at cap-height 2008?)

	* B (U+0042): X=491.0,Y=2007.0 (should be at cap-height 2008?)

	* F (U+0046): X=485.0,Y=2009.0 (should be at cap-height 2008?)

	* F (U+0046): X=1469.0,Y=2009.0 (should be at cap-height 2008?)

	* U (U+0055): X=1327.0,Y=1.0 (should be at baseline 0?)

	* V (U+0056): X=606.0,Y=-2.0 (should be at baseline 0?)

	* V (U+0056): X=606.0,Y=-2.0 (should be at baseline 0?)

	* X (U+0058): X=1373.5,Y=2007.0 (should be at cap-height 2008?)

	* X (U+0058): X=176.5,Y=-1.0 (should be at baseline 0?)

	* backslash (U+005C): X=247.0,Y=2007.0 (should be at cap-height 2008?)

	* bracketright (U+005D): X=378.0,Y=-925.0 (should be at descender -926?)

	* bracketright (U+005D): X=-50.0,Y=-925.0 (should be at descender -926?)

	* c (U+0063): X=757.5,Y=1083.0 (should be at x-height 1082?)

	* f (U+0066): X=362.0,Y=-2.0 (should be at baseline 0?)

	* f (U+0066): X=362.0,Y=-2.0 (should be at baseline 0?)

	* p (U+0070): X=497.0,Y=1.0 (should be at baseline 0?)

	* p (U+0070): X=325.0,Y=1.0 (should be at baseline 0?)

	* x (U+0078): X=198.0,Y=-1.0 (should be at baseline 0?)

	* x (U+0078): X=903.0,Y=1083.0 (should be at x-height 1082?)

	* x (U+0078): X=198.0,Y=-1.0 (should be at baseline 0?)

	* braceright (U+007D): X=-79.5,Y=-924.0 (should be at descender -926?)

	* exclamdown (U+00A1): X=264.0,Y=2009.0 (should be at cap-height 2008?)

	* sterling (U+00A3): X=559.0,Y=2009.0 (should be at cap-height 2008?)

	* yen (U+00A5): X=185.0,Y=0.5 (should be at baseline 0?)

	* Ugrave (U+00D9): X=1327.0,Y=1.0 (should be at baseline 0?)

	* thorn (U+00FE): X=497.0,Y=1.0 (should be at baseline 0?)

	* thorn (U+00FE): X=325.0,Y=1.0 (should be at baseline 0?)

	* iogonek (U+012F): X=220.5,Y=1.0 (should be at baseline 0?)

	* lcaron (U+013E): X=522.0,Y=2007.0 (should be at cap-height 2008?)

	* uni0328 (U+0328): X=155.5,Y=1.0 (should be at baseline 0?)

	* trademark (U+2122): X=199.5,Y=2006.5 (should be at cap-height 2008?)

	* trademark (U+2122): X=909.5,Y=2006.0 (should be at cap-height 2008?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* numbersign (U+0023) contains a short segment B<<11.0,533.0>-<9.0,565.0>-<31.5,587.5>>

	* five (U+0035) contains a short segment B<<-35.0,210.0>-<-33.0,231.0>-<-21.0,250.0>>

	* five (U+0035) contains a short segment B<<-21.0,250.0>-<-9.0,269.0>-<9.0,278.0>>

	* at (U+0040) contains a short segment B<<1084.0,195.0>-<1080.0,220.0>-<1078.5,249.0>>

	* at (U+0040) contains a short segment B<<1078.5,249.0>-<1077.0,278.0>-<1077.0,307.0>>

	* at (U+0040) contains a short segment B<<1001.0,-51.0>-<1034.0,-52.0>-<1056.0,-79.0>>

	* G (U+0047) contains a short segment B<<1253.0,1040.0>-<1272.0,1071.0>-<1290.5,1082.0>>

	* G (U+0047) contains a short segment B<<1290.5,1082.0>-<1309.0,1093.0>-<1342.0,1093.0>>

	* H (U+0048) contains a short segment B<<1418.0,75.0>-<1415.0,46.0>-<1393.0,23.0>>

	* K (U+004B) contains a short segment B<<1449.0,1960.0>-<1473.0,1969.0>-<1496.0,1969.0>>

	* K (U+004B) contains a short segment B<<1360.0,147.0>-<1378.0,123.0>-<1383.5,104.5>>

	* K (U+004B) contains a short segment B<<1383.5,104.5>-<1389.0,86.0>-<1387.0,68.0>>

	* M (U+004D) contains a short segment B<<285.0,0.0>-<238.0,0.0>-<214.5,26.0>>

	* M (U+004D) contains a short segment B<<214.5,26.0>-<191.0,52.0>-<195.0,94.0>>

	* M (U+004D) contains a short segment B<<487.0,2008.0>-<530.0,2008.0>-<553.5,1989.0>>

	* M (U+004D) contains a short segment B<<553.5,1989.0>-<577.0,1970.0>-<595.0,1923.0>>

	* M (U+004D) contains a short segment B<<2201.0,1943.0>-<2224.0,1980.0>-<2245.5,1994.0>>

	* M (U+004D) contains a short segment B<<2245.5,1994.0>-<2267.0,2008.0>-<2314.0,2008.0>>

	* M (U+004D) contains a short segment B<<2204.0,85.0>-<2200.0,53.0>-<2181.0,26.5>>

	* M (U+004D) contains a short segment B<<2181.0,26.5>-<2162.0,0.0>-<2108.0,0.0>>

	* M (U+004D) contains a short segment B<<2108.0,0.0>-<2060.0,0.0>-<2037.0,27.0>>

	* M (U+004D) contains a short segment B<<2037.0,27.0>-<2014.0,54.0>-<2018.0,90.0>>

	* M (U+004D) contains a short segment B<<1306.0,76.0>-<1287.0,44.0>-<1266.5,22.0>>

	* M (U+004D) contains a short segment B<<1266.5,22.0>-<1246.0,0.0>-<1202.0,0.0>>

	* M (U+004D) contains a short segment B<<380.0,92.0>-<377.0,55.0>-<357.0,27.5>>

	* M (U+004D) contains a short segment B<<357.0,27.5>-<337.0,0.0>-<285.0,0.0>>

	* N (U+004E) contains a short segment B<<554.0,1991.5>-<580.0,1975.0>-<598.0,1943.0>>

	* N (U+004E) contains a short segment B<<1603.0,85.0>-<1599.0,45.0>-<1583.0,22.5>>

	* N (U+004E) contains a short segment B<<1517.0,0.0>-<1481.0,0.0>-<1458.0,15.5>>

	* N (U+004E) contains a short segment B<<1458.0,15.5>-<1435.0,31.0>-<1418.0,60.0>>

	* W (U+0057) contains a short segment B<<306.0,2008.0>-<360.0,2008.0>-<383.5,1984.0>>

	* W (U+0057) contains a short segment B<<383.5,1984.0>-<407.0,1960.0>-<411.0,1927.0>>

	* W (U+0057) contains a short segment B<<1239.0,1927.0>-<1252.0,1960.0>-<1276.5,1984.0>>

	* W (U+0057) contains a short segment B<<1276.5,1984.0>-<1301.0,2008.0>-<1346.0,2008.0>>

	* W (U+0057) contains a short segment B<<1346.0,2008.0>-<1404.0,2008.0>-<1428.5,1985.0>>

	* W (U+0057) contains a short segment B<<1428.5,1985.0>-<1453.0,1962.0>-<1459.0,1927.0>>

	* W (U+0057) contains a short segment B<<2293.0,1929.0>-<2309.0,1968.0>-<2333.0,1988.0>>

	* W (U+0057) contains a short segment B<<2333.0,1988.0>-<2357.0,2008.0>-<2406.0,2008.0>>

	* W (U+0057) contains a short segment B<<2406.0,2008.0>-<2455.0,2008.0>-<2477.5,1975.0>>

	* W (U+0057) contains a short segment B<<2477.5,1975.0>-<2500.0,1942.0>-<2481.0,1895.0>>

	* W (U+0057) contains a short segment B<<1753.0,80.0>-<1737.0,41.0>-<1716.5,20.5>>

	* W (U+0057) contains a short segment B<<1716.5,20.5>-<1696.0,0.0>-<1648.0,0.0>>

	* W (U+0057) contains a short segment B<<1648.0,0.0>-<1603.0,0.0>-<1579.0,22.5>>

	* W (U+0057) contains a short segment B<<1579.0,22.5>-<1555.0,45.0>-<1551.0,76.0>>

	* W (U+0057) contains a short segment B<<722.0,92.0>-<706.0,53.0>-<680.0,26.5>>

	* W (U+0057) contains a short segment B<<680.0,26.5>-<654.0,0.0>-<604.0,0.0>>

	* k (U+006B) contains a short segment B<<955.0,109.0>-<959.0,91.0>-<958.0,73.0>>

	* cent (U+00A2) contains a short segment L<<269.0,-10.0>--<261.0,-10.0>>

	* sterling (U+00A3) contains a short segment B<<-13.0,10.0>-<-32.0,20.0>-<-38.0,36.0>>

	* Ntilde (U+00D1) contains a short segment B<<554.0,1991.5>-<580.0,1975.0>-<598.0,1943.0>>

	* Ntilde (U+00D1) contains a short segment B<<1603.0,85.0>-<1599.0,45.0>-<1583.0,22.5>>

	* Ntilde (U+00D1) contains a short segment B<<1517.0,0.0>-<1481.0,0.0>-<1458.0,15.5>>

	* Ntilde (U+00D1) contains a short segment B<<1458.0,15.5>-<1435.0,31.0>-<1418.0,60.0>>

	* uni0137 (U+0137) contains a short segment B<<955.0,109.0>-<959.0,91.0>-<958.0,73.0>>

	* Wgrave (U+1E80) contains a short segment B<<306.0,2008.0>-<360.0,2008.0>-<383.5,1984.0>>

	* Wgrave (U+1E80) contains a short segment B<<383.5,1984.0>-<407.0,1960.0>-<411.0,1927.0>>

	* Wgrave (U+1E80) contains a short segment B<<1239.0,1927.0>-<1252.0,1960.0>-<1276.5,1984.0>>

	* Wgrave (U+1E80) contains a short segment B<<1276.5,1984.0>-<1301.0,2008.0>-<1346.0,2008.0>>

	* Wgrave (U+1E80) contains a short segment B<<1346.0,2008.0>-<1404.0,2008.0>-<1428.5,1985.0>>

	* Wgrave (U+1E80) contains a short segment B<<1428.5,1985.0>-<1453.0,1962.0>-<1459.0,1927.0>>

	* Wgrave (U+1E80) contains a short segment B<<2293.0,1929.0>-<2309.0,1968.0>-<2333.0,1988.0>>

	* Wgrave (U+1E80) contains a short segment B<<2333.0,1988.0>-<2357.0,2008.0>-<2406.0,2008.0>>

	* Wgrave (U+1E80) contains a short segment B<<2406.0,2008.0>-<2455.0,2008.0>-<2477.5,1975.0>>

	* Wgrave (U+1E80) contains a short segment B<<2477.5,1975.0>-<2500.0,1942.0>-<2481.0,1895.0>>

	* Wgrave (U+1E80) contains a short segment B<<1753.0,80.0>-<1737.0,41.0>-<1716.5,20.5>>

	* Wgrave (U+1E80) contains a short segment B<<1716.5,20.5>-<1696.0,0.0>-<1648.0,0.0>>

	* Wgrave (U+1E80) contains a short segment B<<1648.0,0.0>-<1603.0,0.0>-<1579.0,22.5>>

	* Wgrave (U+1E80) contains a short segment B<<1579.0,22.5>-<1555.0,45.0>-<1551.0,76.0>>

	* Wgrave (U+1E80) contains a short segment B<<722.0,92.0>-<706.0,53.0>-<680.0,26.5>>

	* Wgrave (U+1E80) contains a short segment B<<680.0,26.5>-<654.0,0.0>-<604.0,0.0>>

	* Euro (U+20AC) contains a short segment B<<37.0,767.0>-<34.0,801.0>-<57.0,822.5>>

	* Euro (U+20AC) contains a short segment B<<383.0,1052.0>-<387.0,1077.0>-<392.5,1101.5>>

	* Euro (U+20AC) contains a short segment B<<392.5,1101.5>-<398.0,1126.0>-<403.0,1151.0>>

	* Euro (U+20AC) contains a short segment B<<85.0,1233.0>-<82.0,1264.0>-<105.5,1287.0>>

	* Euro (U+20AC) contains a short segment B<<971.0,1230.0>-<974.0,1197.0>-<951.0,1174.0>>

	* Euro (U+20AC) contains a short segment B<<594.0,1151.0>-<588.0,1122.0>-<582.0,1092.0>>

	* lessequal (U+2264) contains a short segment L<<126.0,634.0>--<126.0,635.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* A (U+0041): L<<1006.0,1119.0>--<964.0,1488.0>> -> L<<964.0,1488.0>--<928.0,1771.0>>

	* A (U+0041): L<<928.0,1771.0>--<812.0,1489.0>> -> L<<812.0,1489.0>--<662.0,1119.0>>

	* Agrave (U+00C0): L<<1006.0,1119.0>--<964.0,1488.0>> -> L<<964.0,1488.0>--<928.0,1771.0>>

	* Agrave (U+00C0): L<<928.0,1771.0>--<812.0,1489.0>> -> L<<812.0,1489.0>--<662.0,1119.0>>

	* Atilde (U+00C3): L<<1006.0,1119.0>--<964.0,1488.0>> -> L<<964.0,1488.0>--<928.0,1771.0>>

	* Atilde (U+00C3): L<<928.0,1771.0>--<812.0,1489.0>> -> L<<812.0,1489.0>--<662.0,1119.0>>

	* V (U+0056): L<<411.0,1927.0>--<613.0,631.0>> -> L<<613.0,631.0>--<643.0,407.0>>

	* V (U+0056): L<<643.0,407.0>--<724.0,630.0>> -> L<<724.0,630.0>--<1251.0,1931.0>>

	* W (U+0057): L<<1318.0,1656.0>--<1245.0,1447.0>> -> L<<1245.0,1447.0>--<722.0,92.0>>

	* W (U+0057): L<<1459.0,1927.0>--<1640.0,678.0>> -> L<<1640.0,678.0>--<1680.0,364.0>>

	* W (U+0057): L<<1551.0,76.0>--<1348.0,1438.0>> -> L<<1348.0,1438.0>--<1318.0,1656.0>>

	* W (U+0057): L<<1680.0,364.0>--<1794.0,668.0>> -> L<<1794.0,668.0>--<2293.0,1929.0>>

	* W (U+0057): L<<411.0,1927.0>--<590.0,677.0>> -> L<<590.0,677.0>--<636.0,362.0>>

	* W (U+0057): L<<636.0,362.0>--<754.0,672.0>> -> L<<754.0,672.0>--<1239.0,1927.0>>

	* Wgrave (U+1E80): L<<1318.0,1656.0>--<1245.0,1447.0>> -> L<<1245.0,1447.0>--<722.0,92.0>>

	* Wgrave (U+1E80): L<<1459.0,1927.0>--<1640.0,678.0>> -> L<<1640.0,678.0>--<1680.0,364.0>>

	* Wgrave (U+1E80): L<<1551.0,76.0>--<1348.0,1438.0>> -> L<<1348.0,1438.0>--<1318.0,1656.0>>

	* Wgrave (U+1E80): L<<1680.0,364.0>--<1794.0,668.0>> -> L<<1794.0,668.0>--<2293.0,1929.0>>

	* Wgrave (U+1E80): L<<411.0,1927.0>--<590.0,677.0>> -> L<<590.0,677.0>--<636.0,362.0>>

	* Wgrave (U+1E80): L<<636.0,362.0>--<754.0,672.0>> -> L<<754.0,672.0>--<1239.0,1927.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details><details><summary><b>[19] Nswact-SemiBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x02D9 (DOT ABOVE)


	- 0x00A8 (DIAERESIS)


	- 0x00B4 (ACUTE ACCENT)


	- 0x02DD (DOUBLE ACUTE ACCENT)


	- 0x02C6 (MODIFIER LETTER CIRCUMFLEX ACCENT)


	- 0x02C7 (CARON)


	- 0x02D8 (BREVE)


	- 0x02DA (RING ABOVE)


	- 0x00AF (MACRON)


	- 0x00B8 (CEDILLA)


	- 0x02DB (OGONEK)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 3418, but got 2642 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 945, but got 926 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have no contours even though they were expected to have some:

	- Glyph name: section	Expected: 2

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: Aacute	Expected: 3

	- Glyph name: Acircumflex	Expected: 3

	- Glyph name: Adieresis	Expected: 4

	- Glyph name: Aring	Expected: 3 or 4

	- Glyph name: AE	Expected: 2

	- Glyph name: Ccedilla	Expected: 1 or 2

	- Glyph name: Eacute	Expected: 2

	- Glyph name: Ecircumflex	Expected: 2

	- Glyph name: Edieresis	Expected: 3

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Eth	Expected: 2

	- Glyph name: Oacute	Expected: 3

	- Glyph name: Ocircumflex	Expected: 3

	- Glyph name: Odieresis	Expected: 4

	- Glyph name: Oslash	Expected: 2 or 3

	- Glyph name: Uacute	Expected: 2

	- Glyph name: Ucircumflex	Expected: 2

	- Glyph name: Udieresis	Expected: 3

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Thorn	Expected: 1 or 2

	- Glyph name: oslash	Expected: 3

	- Glyph name: Amacron	Expected: 3

	- Glyph name: Abreve	Expected: 3

	- Glyph name: Aogonek	Expected: 2 or 3

	- Glyph name: Cacute	Expected: 2

	- Glyph name: Cdotaccent	Expected: 2

	- Glyph name: Ccaron	Expected: 2

	- Glyph name: Dcaron	Expected: 3

	- Glyph name: Dcroat	Expected: 2

	- Glyph name: dcroat	Expected: 2

	- Glyph name: Emacron	Expected: 2

	- Glyph name: Edotaccent	Expected: 2

	- Glyph name: Eogonek	Expected: 1 or 2

	- Glyph name: Ecaron	Expected: 2

	- Glyph name: Gbreve	Expected: 2

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: uni0122	Expected: 2

	- Glyph name: Hbar	Expected: 2

	- Glyph name: Imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: uni0136	Expected: 2 or 3

	- Glyph name: Lacute	Expected: 2

	- Glyph name: uni013B	Expected: 2

	- Glyph name: Lcaron	Expected: 2

	- Glyph name: Lslash	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: Nacute	Expected: 2

	- Glyph name: uni0145	Expected: 2

	- Glyph name: Ncaron	Expected: 2

	- Glyph name: Eng	Expected: 1

	- Glyph name: eng	Expected: 1

	- Glyph name: Omacron	Expected: 3

	- Glyph name: Ohungarumlaut	Expected: 4

	- Glyph name: OE	Expected: 2

	- Glyph name: Racute	Expected: 3

	- Glyph name: uni0156	Expected: 3

	- Glyph name: Rcaron	Expected: 3

	- Glyph name: Sacute	Expected: 2

	- Glyph name: Scedilla	Expected: 1 or 2

	- Glyph name: Scaron	Expected: 2

	- Glyph name: Tcaron	Expected: 2

	- Glyph name: Umacron	Expected: 2

	- Glyph name: Ubreve	Expected: 2

	- Glyph name: Uring	Expected: 3

	- Glyph name: Uhungarumlaut	Expected: 3

	- Glyph name: Uogonek	Expected: 1

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Zacute	Expected: 2

	- Glyph name: Zdotaccent	Expected: 2

	- Glyph name: Zcaron	Expected: 2

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: Wacute	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: quotesinglbase	Expected: 1

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: AE	Expected: 2

	- Glyph name: Aacute	Expected: 3

	- Glyph name: Abreve	Expected: 3

	- Glyph name: Acircumflex	Expected: 3

	- Glyph name: Adieresis	Expected: 4

	- Glyph name: Amacron	Expected: 3

	- Glyph name: Aogonek	Expected: 2 or 3

	- Glyph name: Aring	Expected: 3 or 4

	- Glyph name: Cacute	Expected: 2

	- Glyph name: Ccaron	Expected: 2

	- Glyph name: Ccedilla	Expected: 1 or 2

	- Glyph name: Cdotaccent	Expected: 2

	- Glyph name: Dcaron	Expected: 3

	- Glyph name: Dcroat	Expected: 2

	- Glyph name: Eacute	Expected: 2

	- Glyph name: Ecaron	Expected: 2

	- Glyph name: Ecircumflex	Expected: 2

	- Glyph name: Edieresis	Expected: 3

	- Glyph name: Edotaccent	Expected: 2

	- Glyph name: Emacron	Expected: 2

	- Glyph name: Eng	Expected: 1

	- Glyph name: Eogonek	Expected: 1 or 2

	- Glyph name: Eth	Expected: 2

	- Glyph name: Gbreve	Expected: 2

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: Hbar	Expected: 2

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: Imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: Lacute	Expected: 2

	- Glyph name: Lcaron	Expected: 2

	- Glyph name: Lslash	Expected: 1

	- Glyph name: Nacute	Expected: 2

	- Glyph name: Ncaron	Expected: 2

	- Glyph name: OE	Expected: 2

	- Glyph name: Oacute	Expected: 3

	- Glyph name: Ocircumflex	Expected: 3

	- Glyph name: Odieresis	Expected: 4

	- Glyph name: Ohungarumlaut	Expected: 4

	- Glyph name: Omacron	Expected: 3

	- Glyph name: Oslash	Expected: 2 or 3

	- Glyph name: Racute	Expected: 3

	- Glyph name: Rcaron	Expected: 3

	- Glyph name: Sacute	Expected: 2

	- Glyph name: Scaron	Expected: 2

	- Glyph name: Tcaron	Expected: 2

	- Glyph name: Thorn	Expected: 1 or 2

	- Glyph name: Uacute	Expected: 2

	- Glyph name: Ubreve	Expected: 2

	- Glyph name: Ucircumflex	Expected: 2

	- Glyph name: Udieresis	Expected: 3

	- Glyph name: Uhungarumlaut	Expected: 3

	- Glyph name: Umacron	Expected: 2

	- Glyph name: Uogonek	Expected: 1

	- Glyph name: Uring	Expected: 3

	- Glyph name: Wacute	Expected: 2

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Zacute	Expected: 2

	- Glyph name: Zcaron	Expected: 2

	- Glyph name: Zdotaccent	Expected: 2

	- Glyph name: dcroat	Expected: 2

	- Glyph name: eng	Expected: 1

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: oslash	Expected: 3

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: quotesinglbase	Expected: 1

	- Glyph name: section	Expected: 2

	- Glyph name: uni0122	Expected: 2

	- Glyph name: uni0136	Expected: 2 or 3

	- Glyph name: uni013B	Expected: 2

	- Glyph name: uni0145	Expected: 2

	- Glyph name: uni0156	Expected: 3

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni1E9E	Expected: 1
 [code: no-contour]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Atilde	Contours detected: 2	Expected: 3

	- Glyph name: Ntilde	Contours detected: 1	Expected: 2

	- Glyph name: Otilde	Contours detected: 2	Expected: 3

	- Glyph name: atilde	Contours detected: 2	Expected: 3

	- Glyph name: ntilde	Contours detected: 1	Expected: 2

	- Glyph name: otilde	Contours detected: 2	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Atilde	Contours detected: 2	Expected: 3

	- Glyph name: Ntilde	Contours detected: 1	Expected: 2

	- Glyph name: Otilde	Contours detected: 2	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: atilde	Contours detected: 2	Expected: 3

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: ntilde	Contours detected: 1	Expected: 2

	- Glyph name: otilde	Contours detected: 2	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* 🔥 **FAIL** Font is not italic, so post.italicAngle should be equal to zero. [code: non-zero-upright]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, coptic, tifinagh, cherokee
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, syriac, tai-le, math, old-permic, coptic, canadian-aboriginal, tifinagh
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2000 EN QUAD: not included in any glyphset definition
 * U+2001 EM QUAD: not included in any glyphset definition
 * U+2003 EM SPACE: try adding nushu
 * U+2004 THREE-PER-EM SPACE: not included in any glyphset definition
 * U+2005 FOUR-PER-EM SPACE: not included in any glyphset definition
 * U+2006 SIX-PER-EM SPACE: not included in any glyphset definition
 * U+2007 FIGURE SPACE: not included in any glyphset definition
 * U+2008 PUNCTUATION SPACE: not included in any glyphset definition
 * U+200A HAIR SPACE: not included in any glyphset definition
 * U+200C ZERO WIDTH NON-JOINER: try adding one of: grantha, warang-citi, nko, cham, brahmi, tai-tham, syriac, syloti-nagri, saurashtra, new-tai-lue, duployan, batak, rejang, devanagari, gujarati, dogra, tifinagh, phags-pa, kayah-li, yi, buhid, mongolian, manichaean, tai-le, telugu, hatran, balinese, modi, pahawh-hmong, bengali, meetei-mayek, thai, sogdian, siddham, chakma, kannada, tamil, avestan, lepcha, gunjala-gondi, gurmukhi, mahajani, oriya, takri, hanifi-rohingya, kaithi, mandaic, tagbanwa, thaana, khojki, tirhuta, hanunoo, psalter-pahlavi, malayalam, sundanese, limbu, kharoshthi, buginese, myanmar, sinhala, javanese, tai-viet, khmer, newa, sharada, tibetan, tagalog, khudawadi
 * U+200D ZERO WIDTH JOINER: try adding one of: grantha, warang-citi, nko, cham, brahmi, tai-tham, syriac, syloti-nagri, saurashtra, new-tai-lue, duployan, batak, rejang, devanagari, gujarati, dogra, tifinagh, phags-pa, kayah-li, yi, buhid, mongolian, manichaean, tai-le, telugu, balinese, modi, pahawh-hmong, old-hungarian, bengali, meetei-mayek, thai, siddham, chakma, kannada, tamil, avestan, lepcha, gunjala-gondi, gurmukhi, mahajani, oriya, takri, hanifi-rohingya, kaithi, mandaic, tagbanwa, thaana, khojki, tirhuta, hanunoo, psalter-pahlavi, malayalam, sundanese, limbu, kharoshthi, buginese, myanmar, sinhala, javanese, tai-viet, newa, sharada, tibetan, tagalog, khudawadi
 * U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, yi
 * U+205F MEDIUM MATHEMATICAL SPACE: not included in any glyphset definition
 * U+221E INFINITY: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.784x (3568) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 953 among a set of 4 math glyphs.
The following math glyphs have a different width, though:

Width = 950:
minus, plus

Width = 861:
less, greater

Width = 866:
plusminus

Width = 948:
divide

Width = 889:
lessequal

Width = 887:
greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* parenright (U+0029): X=160.5,Y=2008.5 (should be at cap-height 2008?)

	* asterisk (U+002A): X=586.5,Y=2010.0 (should be at cap-height 2008?)

	* B (U+0042): X=511.0,Y=2007.0 (should be at cap-height 2008?)

	* P (U+0050): X=491.0,Y=2007.0 (should be at cap-height 2008?)

	* R (U+0052): X=508.0,Y=2007.0 (should be at cap-height 2008?)

	* X (U+0058): X=1425.0,Y=2007.0 (should be at cap-height 2008?)

	* X (U+0058): X=1220.0,Y=1.0 (should be at baseline 0?)

	* Y (U+0059): X=326.0,Y=1.5 (should be at baseline 0?)

	* Z (U+005A): X=369.0,Y=2009.0 (should be at cap-height 2008?)

	* Z (U+005A): X=1383.0,Y=2009.0 (should be at cap-height 2008?)

	* g (U+0067): X=287.5,Y=-1.0 (should be at baseline 0?)

	* q (U+0071): X=710.5,Y=-924.5 (should be at descender -926?)

	* braceright (U+007D): X=-63.5,Y=-924.0 (should be at descender -926?)

	* braceright (U+007D): X=281.0,Y=2007.0 (should be at cap-height 2008?)

	* sterling (U+00A3): X=584.0,Y=2010.0 (should be at cap-height 2008?)

	* yen (U+00A5): X=215.5,Y=0.5 (should be at baseline 0?)

	* gbreve (U+011F): X=287.5,Y=-1.0 (should be at baseline 0?)

	* gdotaccent (U+0121): X=287.5,Y=-1.0 (should be at baseline 0?)

	* uni0123 (U+0123): X=287.5,Y=-1.0 (should be at baseline 0?)

	* Ygrave (U+1EF2): X=326.0,Y=1.5 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* dollar (U+0024) contains a short segment B<<466.0,-7.0>-<447.0,-8.0>-<427.5,-8.5>>

	* dollar (U+0024) contains a short segment B<<427.5,-8.5>-<408.0,-9.0>-<387.0,-9.0>>

	* five (U+0035) contains a short segment B<<-30.0,174.0>-<-37.0,195.0>-<-34.0,220.0>>

	* less (U+003C) contains a short segment L<<67.0,697.0>--<67.0,697.0>>

	* at (U+0040) contains a short segment B<<1308.5,297.0>-<1311.0,235.0>-<1345.0,235.0>>

	* K (U+004B) contains a short segment B<<1420.0,188.0>-<1439.0,162.0>-<1446.0,139.5>>

	* K (U+004B) contains a short segment B<<1446.0,139.5>-<1453.0,117.0>-<1452.0,97.0>>

	* M (U+004D) contains a short segment B<<2259.0,105.0>-<2255.0,65.0>-<2228.0,32.5>>

	* M (U+004D) contains a short segment B<<436.0,111.0>-<431.0,67.0>-<400.0,33.5>>

	* W (U+0057) contains a short segment B<<447.0,1978.5>-<482.0,1949.0>-<487.0,1907.0>>

	* W (U+0057) contains a short segment B<<1246.0,1909.0>-<1262.0,1951.0>-<1293.5,1979.5>>

	* W (U+0057) contains a short segment B<<1489.0,1980.0>-<1524.0,1952.0>-<1533.0,1907.0>>

	* W (U+0057) contains a short segment B<<2295.0,1917.0>-<2310.0,1952.0>-<2342.5,1980.0>>

	* W (U+0057) contains a short segment B<<1822.0,90.0>-<1805.0,47.0>-<1776.5,23.5>>

	* W (U+0057) contains a short segment B<<1599.0,26.5>-<1566.0,53.0>-<1561.0,88.0>>

	* q (U+0071) contains a short segment B<<741.0,-916.0>-<730.0,-923.0>-<710.5,-924.5>>

	* cent (U+00A2) contains a short segment L<<287.0,-15.0>--<276.0,-15.0>>

	* sterling (U+00A3) contains a short segment B<<-6.5,14.0>-<-31.0,28.0>-<-38.0,48.0>>

	* yen (U+00A5) contains a short segment L<<524.0,983.0>--<544.0,1019.0>>

	* Wgrave (U+1E80) contains a short segment B<<447.0,1978.5>-<482.0,1949.0>-<487.0,1907.0>>

	* Wgrave (U+1E80) contains a short segment B<<1246.0,1909.0>-<1262.0,1951.0>-<1293.5,1979.5>>

	* Wgrave (U+1E80) contains a short segment B<<1489.0,1980.0>-<1524.0,1952.0>-<1533.0,1907.0>>

	* Wgrave (U+1E80) contains a short segment B<<2295.0,1917.0>-<2310.0,1952.0>-<2342.5,1980.0>>

	* Wgrave (U+1E80) contains a short segment B<<1822.0,90.0>-<1805.0,47.0>-<1776.5,23.5>>

	* Wgrave (U+1E80) contains a short segment B<<1599.0,26.5>-<1566.0,53.0>-<1561.0,88.0>>

	* Euro (U+20AC) contains a short segment B<<374.0,1055.0>-<377.0,1073.0>-<380.5,1090.5>>

	* Euro (U+20AC) contains a short segment B<<380.5,1090.5>-<384.0,1108.0>-<388.0,1125.0>>

	* lessequal (U+2264) contains a short segment L<<155.0,629.0>--<155.0,630.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* A (U+0041): L<<1012.0,1100.0>--<976.0,1471.0>> -> L<<976.0,1471.0>--<951.0,1707.0>>

	* A (U+0041): L<<951.0,1707.0>--<858.0,1474.0>> -> L<<858.0,1474.0>--<715.0,1100.0>>

	* Agrave (U+00C0): L<<1012.0,1100.0>--<976.0,1471.0>> -> L<<976.0,1471.0>--<951.0,1707.0>>

	* Agrave (U+00C0): L<<951.0,1707.0>--<858.0,1474.0>> -> L<<858.0,1474.0>--<715.0,1100.0>>

	* Atilde (U+00C3): L<<1012.0,1100.0>--<976.0,1471.0>> -> L<<976.0,1471.0>--<951.0,1707.0>>

	* Atilde (U+00C3): L<<951.0,1707.0>--<858.0,1474.0>> -> L<<858.0,1474.0>--<715.0,1100.0>>

	* V (U+0056): L<<487.0,1907.0>--<665.0,785.0>> -> L<<665.0,785.0>--<696.0,540.0>>

	* V (U+0056): L<<696.0,540.0>--<784.0,784.0>> -> L<<784.0,784.0>--<1252.0,1920.0>>

	* W (U+0057): L<<1348.0,1544.0>--<1286.0,1359.0>> -> L<<1286.0,1359.0>--<808.0,112.0>>

	* W (U+0057): L<<1533.0,1907.0>--<1697.0,766.0>> -> L<<1697.0,766.0>--<1731.0,480.0>>

	* W (U+0057): L<<1561.0,88.0>--<1371.0,1355.0>> -> L<<1371.0,1355.0>--<1348.0,1544.0>>

	* W (U+0057): L<<1731.0,480.0>--<1837.0,760.0>> -> L<<1837.0,760.0>--<2295.0,1917.0>>

	* W (U+0057): L<<487.0,1907.0>--<648.0,772.0>> -> L<<648.0,772.0>--<691.0,458.0>>

	* W (U+0057): L<<691.0,458.0>--<804.0,764.0>> -> L<<804.0,764.0>--<1246.0,1909.0>>

	* Wgrave (U+1E80): L<<1348.0,1544.0>--<1286.0,1359.0>> -> L<<1286.0,1359.0>--<808.0,112.0>>

	* Wgrave (U+1E80): L<<1533.0,1907.0>--<1697.0,766.0>> -> L<<1697.0,766.0>--<1731.0,480.0>>

	* Wgrave (U+1E80): L<<1561.0,88.0>--<1371.0,1355.0>> -> L<<1371.0,1355.0>--<1348.0,1544.0>>

	* Wgrave (U+1E80): L<<1731.0,480.0>--<1837.0,760.0>> -> L<<1837.0,760.0>--<2295.0,1917.0>>

	* Wgrave (U+1E80): L<<487.0,1907.0>--<648.0,772.0>> -> L<<648.0,772.0>--<691.0,458.0>>

	* Wgrave (U+1E80): L<<691.0,458.0>--<804.0,764.0>> -> L<<804.0,764.0>--<1246.0,1909.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details><details><summary><b>[19] Nswact-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x02D9 (DOT ABOVE)


	- 0x00A8 (DIAERESIS)


	- 0x00B4 (ACUTE ACCENT)


	- 0x02DD (DOUBLE ACUTE ACCENT)


	- 0x02C6 (MODIFIER LETTER CIRCUMFLEX ACCENT)


	- 0x02C7 (CARON)


	- 0x02D8 (BREVE)


	- 0x02DA (RING ABOVE)


	- 0x00AF (MACRON)


	- 0x00B8 (CEDILLA)


	- 0x02DB (OGONEK)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 3418, but got 2642 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 945, but got 926 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have no contours even though they were expected to have some:

	- Glyph name: section	Expected: 2

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: Aacute	Expected: 3

	- Glyph name: Acircumflex	Expected: 3

	- Glyph name: Adieresis	Expected: 4

	- Glyph name: Aring	Expected: 3 or 4

	- Glyph name: AE	Expected: 2

	- Glyph name: Ccedilla	Expected: 1 or 2

	- Glyph name: Eacute	Expected: 2

	- Glyph name: Ecircumflex	Expected: 2

	- Glyph name: Edieresis	Expected: 3

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Eth	Expected: 2

	- Glyph name: Oacute	Expected: 3

	- Glyph name: Ocircumflex	Expected: 3

	- Glyph name: Odieresis	Expected: 4

	- Glyph name: Oslash	Expected: 2 or 3

	- Glyph name: Uacute	Expected: 2

	- Glyph name: Ucircumflex	Expected: 2

	- Glyph name: Udieresis	Expected: 3

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Thorn	Expected: 1 or 2

	- Glyph name: oslash	Expected: 3

	- Glyph name: Amacron	Expected: 3

	- Glyph name: Abreve	Expected: 3

	- Glyph name: Aogonek	Expected: 2 or 3

	- Glyph name: Cacute	Expected: 2

	- Glyph name: Cdotaccent	Expected: 2

	- Glyph name: Ccaron	Expected: 2

	- Glyph name: Dcaron	Expected: 3

	- Glyph name: Dcroat	Expected: 2

	- Glyph name: dcroat	Expected: 2

	- Glyph name: Emacron	Expected: 2

	- Glyph name: Edotaccent	Expected: 2

	- Glyph name: Eogonek	Expected: 1 or 2

	- Glyph name: Ecaron	Expected: 2

	- Glyph name: Gbreve	Expected: 2

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: uni0122	Expected: 2

	- Glyph name: Hbar	Expected: 2

	- Glyph name: Imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: uni0136	Expected: 2 or 3

	- Glyph name: Lacute	Expected: 2

	- Glyph name: uni013B	Expected: 2

	- Glyph name: Lcaron	Expected: 2

	- Glyph name: Lslash	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: Nacute	Expected: 2

	- Glyph name: uni0145	Expected: 2

	- Glyph name: Ncaron	Expected: 2

	- Glyph name: Eng	Expected: 1

	- Glyph name: eng	Expected: 1

	- Glyph name: Omacron	Expected: 3

	- Glyph name: Ohungarumlaut	Expected: 4

	- Glyph name: OE	Expected: 2

	- Glyph name: Racute	Expected: 3

	- Glyph name: uni0156	Expected: 3

	- Glyph name: Rcaron	Expected: 3

	- Glyph name: Sacute	Expected: 2

	- Glyph name: Scedilla	Expected: 1 or 2

	- Glyph name: Scaron	Expected: 2

	- Glyph name: Tcaron	Expected: 2

	- Glyph name: Umacron	Expected: 2

	- Glyph name: Ubreve	Expected: 2

	- Glyph name: Uring	Expected: 3

	- Glyph name: Uhungarumlaut	Expected: 3

	- Glyph name: Uogonek	Expected: 1

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Zacute	Expected: 2

	- Glyph name: Zdotaccent	Expected: 2

	- Glyph name: Zcaron	Expected: 2

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: Wacute	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: quotesinglbase	Expected: 1

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: AE	Expected: 2

	- Glyph name: Aacute	Expected: 3

	- Glyph name: Abreve	Expected: 3

	- Glyph name: Acircumflex	Expected: 3

	- Glyph name: Adieresis	Expected: 4

	- Glyph name: Amacron	Expected: 3

	- Glyph name: Aogonek	Expected: 2 or 3

	- Glyph name: Aring	Expected: 3 or 4

	- Glyph name: Cacute	Expected: 2

	- Glyph name: Ccaron	Expected: 2

	- Glyph name: Ccedilla	Expected: 1 or 2

	- Glyph name: Cdotaccent	Expected: 2

	- Glyph name: Dcaron	Expected: 3

	- Glyph name: Dcroat	Expected: 2

	- Glyph name: Eacute	Expected: 2

	- Glyph name: Ecaron	Expected: 2

	- Glyph name: Ecircumflex	Expected: 2

	- Glyph name: Edieresis	Expected: 3

	- Glyph name: Edotaccent	Expected: 2

	- Glyph name: Emacron	Expected: 2

	- Glyph name: Eng	Expected: 1

	- Glyph name: Eogonek	Expected: 1 or 2

	- Glyph name: Eth	Expected: 2

	- Glyph name: Gbreve	Expected: 2

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: Hbar	Expected: 2

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: Imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: Lacute	Expected: 2

	- Glyph name: Lcaron	Expected: 2

	- Glyph name: Lslash	Expected: 1

	- Glyph name: Nacute	Expected: 2

	- Glyph name: Ncaron	Expected: 2

	- Glyph name: OE	Expected: 2

	- Glyph name: Oacute	Expected: 3

	- Glyph name: Ocircumflex	Expected: 3

	- Glyph name: Odieresis	Expected: 4

	- Glyph name: Ohungarumlaut	Expected: 4

	- Glyph name: Omacron	Expected: 3

	- Glyph name: Oslash	Expected: 2 or 3

	- Glyph name: Racute	Expected: 3

	- Glyph name: Rcaron	Expected: 3

	- Glyph name: Sacute	Expected: 2

	- Glyph name: Scaron	Expected: 2

	- Glyph name: Tcaron	Expected: 2

	- Glyph name: Thorn	Expected: 1 or 2

	- Glyph name: Uacute	Expected: 2

	- Glyph name: Ubreve	Expected: 2

	- Glyph name: Ucircumflex	Expected: 2

	- Glyph name: Udieresis	Expected: 3

	- Glyph name: Uhungarumlaut	Expected: 3

	- Glyph name: Umacron	Expected: 2

	- Glyph name: Uogonek	Expected: 1

	- Glyph name: Uring	Expected: 3

	- Glyph name: Wacute	Expected: 2

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Zacute	Expected: 2

	- Glyph name: Zcaron	Expected: 2

	- Glyph name: Zdotaccent	Expected: 2

	- Glyph name: dcroat	Expected: 2

	- Glyph name: eng	Expected: 1

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: oslash	Expected: 3

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: quotesinglbase	Expected: 1

	- Glyph name: section	Expected: 2

	- Glyph name: uni0122	Expected: 2

	- Glyph name: uni0136	Expected: 2 or 3

	- Glyph name: uni013B	Expected: 2

	- Glyph name: uni0145	Expected: 2

	- Glyph name: uni0156	Expected: 3

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni1E9E	Expected: 1
 [code: no-contour]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Atilde	Contours detected: 2	Expected: 3

	- Glyph name: Ntilde	Contours detected: 1	Expected: 2

	- Glyph name: Otilde	Contours detected: 2	Expected: 3

	- Glyph name: atilde	Contours detected: 2	Expected: 3

	- Glyph name: ntilde	Contours detected: 1	Expected: 2

	- Glyph name: otilde	Contours detected: 2	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Atilde	Contours detected: 2	Expected: 3

	- Glyph name: Ntilde	Contours detected: 1	Expected: 2

	- Glyph name: Otilde	Contours detected: 2	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: atilde	Contours detected: 2	Expected: 3

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: ntilde	Contours detected: 1	Expected: 2

	- Glyph name: otilde	Contours detected: 2	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* 🔥 **FAIL** Font is not italic, so post.italicAngle should be equal to zero. [code: non-zero-upright]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, coptic, tifinagh, cherokee
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, syriac, tai-le, math, old-permic, coptic, canadian-aboriginal, tifinagh
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2000 EN QUAD: not included in any glyphset definition
 * U+2001 EM QUAD: not included in any glyphset definition
 * U+2003 EM SPACE: try adding nushu
 * U+2004 THREE-PER-EM SPACE: not included in any glyphset definition
 * U+2005 FOUR-PER-EM SPACE: not included in any glyphset definition
 * U+2006 SIX-PER-EM SPACE: not included in any glyphset definition
 * U+2007 FIGURE SPACE: not included in any glyphset definition
 * U+2008 PUNCTUATION SPACE: not included in any glyphset definition
 * U+200A HAIR SPACE: not included in any glyphset definition
 * U+200C ZERO WIDTH NON-JOINER: try adding one of: grantha, warang-citi, nko, cham, brahmi, tai-tham, syriac, syloti-nagri, saurashtra, new-tai-lue, duployan, batak, rejang, devanagari, gujarati, dogra, tifinagh, phags-pa, kayah-li, yi, buhid, mongolian, manichaean, tai-le, telugu, hatran, balinese, modi, pahawh-hmong, bengali, meetei-mayek, thai, sogdian, siddham, chakma, kannada, tamil, avestan, lepcha, gunjala-gondi, gurmukhi, mahajani, oriya, takri, hanifi-rohingya, kaithi, mandaic, tagbanwa, thaana, khojki, tirhuta, hanunoo, psalter-pahlavi, malayalam, sundanese, limbu, kharoshthi, buginese, myanmar, sinhala, javanese, tai-viet, khmer, newa, sharada, tibetan, tagalog, khudawadi
 * U+200D ZERO WIDTH JOINER: try adding one of: grantha, warang-citi, nko, cham, brahmi, tai-tham, syriac, syloti-nagri, saurashtra, new-tai-lue, duployan, batak, rejang, devanagari, gujarati, dogra, tifinagh, phags-pa, kayah-li, yi, buhid, mongolian, manichaean, tai-le, telugu, balinese, modi, pahawh-hmong, old-hungarian, bengali, meetei-mayek, thai, siddham, chakma, kannada, tamil, avestan, lepcha, gunjala-gondi, gurmukhi, mahajani, oriya, takri, hanifi-rohingya, kaithi, mandaic, tagbanwa, thaana, khojki, tirhuta, hanunoo, psalter-pahlavi, malayalam, sundanese, limbu, kharoshthi, buginese, myanmar, sinhala, javanese, tai-viet, newa, sharada, tibetan, tagalog, khudawadi
 * U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, yi
 * U+205F MEDIUM MATHEMATICAL SPACE: not included in any glyphset definition
 * U+221E INFINITY: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.784x (3568) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 873 among a set of 3 math glyphs.
The following math glyphs have a different width, though:

Width = 870:
minus, plus

Width = 778:
less

Width = 780:
greater

Width = 779:
plusminus

Width = 871:
multiply, divide

Width = 804:
lessequal

Width = 808:
greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* dollar (U+0024): X=433.0,Y=1.0 (should be at baseline 0?)

	* percent (U+0025): X=914.0,Y=2.0 (should be at baseline 0?)

	* percent (U+0025): X=914.0,Y=2.0 (should be at baseline 0?)

	* ampersand (U+0026): X=469.0,Y=2.0 (should be at baseline 0?)

	* ampersand (U+0026): X=469.0,Y=2.0 (should be at baseline 0?)

	* parenleft (U+0028): X=482.5,Y=-925.5 (should be at descender -926?)

	* parenleft (U+0028): X=786.0,Y=2006.5 (should be at cap-height 2008?)

	* seven (U+0037): X=214.0,Y=2007.0 (should be at cap-height 2008?)

	* seven (U+0037): X=1088.0,Y=2007.0 (should be at cap-height 2008?)

	* question (U+003F): X=673.0,Y=2006.0 (should be at cap-height 2008?)

	* B (U+0042): X=471.0,Y=2006.0 (should be at cap-height 2008?)

	* F (U+0046): X=471.0,Y=2009.0 (should be at cap-height 2008?)

	* F (U+0046): X=1433.0,Y=2009.0 (should be at cap-height 2008?)

	* U (U+0055): X=1304.0,Y=1.0 (should be at baseline 0?)

	* X (U+0058): X=1359.0,Y=2006.0 (should be at cap-height 2008?)

	* X (U+0058): X=123.0,Y=0.5 (should be at baseline 0?)

	* backslash (U+005C): X=217.0,Y=2009.0 (should be at cap-height 2008?)

	* bracketright (U+005D): X=348.0,Y=-925.0 (should be at descender -926?)

	* bracketright (U+005D): X=-89.0,Y=-925.0 (should be at descender -926?)

	* p (U+0070): X=508.0,Y=1.0 (should be at baseline 0?)

	* p (U+0070): X=267.0,Y=1.0 (should be at baseline 0?)

	* s (U+0073): X=369.5,Y=-1.0 (should be at baseline 0?)

	* x (U+0078): X=186.0,Y=-1.0 (should be at baseline 0?)

	* x (U+0078): X=933.0,Y=1083.0 (should be at x-height 1082?)

	* x (U+0078): X=186.0,Y=-1.0 (should be at baseline 0?)

	* braceright (U+007D): X=-95.5,Y=-924.0 (should be at descender -926?)

	* braceright (U+007D): X=287.5,Y=2007.0 (should be at cap-height 2008?)

	* exclamdown (U+00A1): X=244.0,Y=2009.0 (should be at cap-height 2008?)

	* yen (U+00A5): X=118.0,Y=-0.5 (should be at baseline 0?)

	* registered (U+00AE): X=1232.0,Y=2010.0 (should be at cap-height 2008?)

	* registered (U+00AE): X=417.5,Y=2010.0 (should be at cap-height 2008?)

	* degree (U+00B0): X=407.0,Y=2009.0 (should be at cap-height 2008?)

	* Agrave (U+00C0): X=723.0,Y=2640.5 (should be at ascender 2642?)

	* Egrave (U+00C8): X=787.0,Y=2640.5 (should be at ascender 2642?)

	* Igrave (U+00CC): X=342.0,Y=2640.5 (should be at ascender 2642?)

	* Ograve (U+00D2): X=738.0,Y=2640.5 (should be at ascender 2642?)

	* Ugrave (U+00D9): X=1304.0,Y=1.0 (should be at baseline 0?)

	* Ugrave (U+00D9): X=862.0,Y=2640.5 (should be at ascender 2642?)

	* germandbls (U+00DF): X=78.0,Y=-1.0 (should be at baseline 0?)

	* germandbls (U+00DF): X=78.0,Y=-1.0 (should be at baseline 0?)

	* ccedilla (U+00E7): X=307.0,Y=-2.0 (should be at baseline 0?)

	* thorn (U+00FE): X=508.0,Y=1.0 (should be at baseline 0?)

	* thorn (U+00FE): X=267.0,Y=1.0 (should be at baseline 0?)

	* iogonek (U+012F): X=324.0,Y=-2.0 (should be at baseline 0?)

	* sacute (U+015B): X=369.5,Y=-1.0 (should be at baseline 0?)

	* scedilla (U+015F): X=369.5,Y=-1.0 (should be at baseline 0?)

	* scedilla (U+015F): X=306.0,Y=-2.0 (should be at baseline 0?)

	* scaron (U+0161): X=369.5,Y=-1.0 (should be at baseline 0?)

	* uni0219 (U+0219): X=369.5,Y=-1.0 (should be at baseline 0?)

	* uni0327 (U+0327): X=-25.0,Y=-2.0 (should be at baseline 0?)

	* uni0328 (U+0328): X=328.0,Y=-2.0 (should be at baseline 0?)

	* Wgrave (U+1E80): X=1198.0,Y=2640.5 (should be at ascender 2642?)

	* Ygrave (U+1EF2): X=685.0,Y=2640.5 (should be at ascender 2642?)

	* Euro (U+20AC): X=865.0,Y=2.0 (should be at baseline 0?)

	* Euro (U+20AC): X=865.0,Y=2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* A (U+0041): L<<1001.0,1137.0>--<951.0,1504.0>> -> L<<951.0,1504.0>--<906.0,1834.0>>

	* A (U+0041): L<<906.0,1834.0>--<765.0,1504.0>> -> L<<765.0,1504.0>--<608.0,1137.0>>

	* Agrave (U+00C0): L<<1001.0,1137.0>--<951.0,1504.0>> -> L<<951.0,1504.0>--<906.0,1834.0>>

	* Agrave (U+00C0): L<<906.0,1834.0>--<765.0,1504.0>> -> L<<765.0,1504.0>--<608.0,1137.0>>

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

	* Wgrave (U+1E80): L<<1287.0,1769.0>--<1204.0,1534.0>> -> L<<1204.0,1534.0>--<635.0,71.0>>

	* Wgrave (U+1E80): L<<1386.0,1948.0>--<1583.0,591.0>> -> L<<1583.0,591.0>--<1628.0,248.0>>

	* Wgrave (U+1E80): L<<1540.0,65.0>--<1324.0,1521.0>> -> L<<1324.0,1521.0>--<1287.0,1769.0>>

	* Wgrave (U+1E80): L<<1628.0,248.0>--<1752.0,575.0>> -> L<<1752.0,575.0>--<2291.0,1942.0>>

	* Wgrave (U+1E80): L<<335.0,1948.0>--<532.0,583.0>> -> L<<532.0,583.0>--<582.0,265.0>>

	* Wgrave (U+1E80): L<<582.0,265.0>--<704.0,580.0>> -> L<<704.0,580.0>--<1233.0,1945.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* w (U+0077): L<<805.0,313.0>--<856.0,666.0>>/B<<856.0,666.0>-<750.0,403.0>-<662.5,253.5>> = 13.730520481405952

	* wacute (U+1E83): L<<805.0,313.0>--<856.0,666.0>>/B<<856.0,666.0>-<750.0,403.0>-<662.5,253.5>> = 13.730520481405952

	* wcircumflex (U+0175): L<<805.0,313.0>--<856.0,666.0>>/B<<856.0,666.0>-<750.0,403.0>-<662.5,253.5>> = 13.730520481405952

	* wdieresis (U+1E85): L<<805.0,313.0>--<856.0,666.0>>/B<<856.0,666.0>-<750.0,403.0>-<662.5,253.5>> = 13.730520481405952

	* wgrave (U+1E81): L<<805.0,313.0>--<856.0,666.0>>/B<<856.0,666.0>-<750.0,403.0>-<662.5,253.5>> = 13.730520481405952 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 12 | 24 | 41 | 486 | 21 | 361 | 0 |
| 1% | 3% | 4% | 51% | 2% | 38% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
