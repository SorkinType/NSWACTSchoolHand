## FontBakery report

fontbakery version: 0.9.2

<details><summary><b>[19] NSWACTSchoolHand-Medium.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check family name for GF Guide compliance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_name_compliance">com.google.fonts/check/name/family_name_compliance</a>)</summary><div>


* 🔥 **FAIL** "NSW ACT School Hand" contains an abbreviation. [code: abbreviation]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 3023, but got 2642 instead [code: ascent]
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
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, malayalam, canadian-aboriginal, tai-le, math, tifinagh, old-permic, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
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
 * U+200C ZERO WIDTH NON-JOINER: try adding one of: yi, thai, tibetan, bengali, hanunoo, limbu, mandaic, meetei-mayek, pahawh-hmong, avestan, duployan, syloti-nagri, malayalam, manichaean, nko, sundanese, gunjala-gondi, khmer, phags-pa, dogra, gurmukhi, mongolian, brahmi, tifinagh, kharoshthi, gujarati, hanifi-rohingya, myanmar, sogdian, batak, chakma, rejang, tai-tham, siddham, syriac, javanese, balinese, kannada, tagalog, tai-le, khojki, warang-citi, new-tai-lue, mahajani, tagbanwa, tai-viet, takri, hatran, sharada, thaana, modi, saurashtra, telugu, kayah-li, tirhuta, grantha, tamil, newa, devanagari, lepcha, oriya, sinhala, kaithi, cham, psalter-pahlavi, buhid, buginese, khudawadi
 * U+200D ZERO WIDTH JOINER: try adding one of: yi, thai, tibetan, bengali, hanunoo, limbu, mandaic, meetei-mayek, pahawh-hmong, avestan, duployan, syloti-nagri, malayalam, manichaean, nko, sundanese, gunjala-gondi, phags-pa, dogra, gurmukhi, mongolian, brahmi, tifinagh, kharoshthi, gujarati, hanifi-rohingya, myanmar, batak, chakma, rejang, tai-tham, siddham, syriac, javanese, balinese, kannada, tagalog, tai-le, old-hungarian, khojki, warang-citi, new-tai-lue, mahajani, tagbanwa, tai-viet, takri, sharada, thaana, modi, saurashtra, telugu, kayah-li, tirhuta, grantha, tamil, newa, devanagari, lepcha, oriya, sinhala, kaithi, cham, psalter-pahlavi, buhid, buginese, khudawadi
 * U+202F NARROW NO-BREAK SPACE: try adding one of: yi, mongolian
 * U+205F MEDIUM MATHEMATICAL SPACE: not included in any glyphset definition
 * U+221E INFINITY: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'NSW ACT School Hand Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.784x (3568) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- i.loclTRK

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case

	- uni004A0301

	- uni006A0301

	- uni013B.loclMAH

	- uni013C.loclMAH

	- uni0145.loclMAH

	- uni0146.loclMAH
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


* ⚠ **WARN** The most common width is 910 among a set of 3 math glyphs.
The following math glyphs have a different width, though:

Width = 820:
less

Width = 913:
equal, notequal, approxequal

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

	* Aacute (U+00C1): X=1171.0,Y=2641.0 (should be at ascender 2642?)

	* Eacute (U+00C9): X=1219.0,Y=2641.0 (should be at ascender 2642?)

	* Iacute (U+00CD): X=780.0,Y=2641.0 (should be at ascender 2642?)

	* Oacute (U+00D3): X=1185.0,Y=2641.0 (should be at ascender 2642?)

	* Oslash (U+00D8): X=307.0,Y=-2.0 (should be at baseline 0?)

	* Ugrave (U+00D9): X=1327.0,Y=1.0 (should be at baseline 0?)

	* Uacute (U+00DA): X=1327.0,Y=1.0 (should be at baseline 0?)

	* Uacute (U+00DA): X=1300.0,Y=2641.0 (should be at ascender 2642?)

	* Ucircumflex (U+00DB): X=1327.0,Y=1.0 (should be at baseline 0?)

	* Udieresis (U+00DC): X=1327.0,Y=1.0 (should be at baseline 0?)

	* Yacute (U+00DD): X=1145.0,Y=2641.0 (should be at ascender 2642?)

	* germandbls (U+00DF): X=916.0,Y=2009.0 (should be at cap-height 2008?)

	* thorn (U+00FE): X=503.0,Y=1.0 (should be at baseline 0?)

	* thorn (U+00FE): X=331.0,Y=1.0 (should be at baseline 0?)

	* Cacute (U+0106): X=1138.0,Y=2641.0 (should be at ascender 2642?)

	* Iogonek (U+012E): X=105.5,Y=1.0 (should be at baseline 0?)

	* iogonek (U+012F): X=116.5,Y=1.0 (should be at baseline 0?)

	* Lacute (U+0139): X=1197.0,Y=2641.0 (should be at ascender 2642?)

	* lacute (U+013A): X=730.0,Y=2641.0 (should be at ascender 2642?)

	* Lcaron (U+013D): X=1163.0,Y=2009.0 (should be at cap-height 2008?)

	* Nacute (U+0143): X=1391.0,Y=2641.0 (should be at ascender 2642?)

	* Racute (U+0154): X=1215.0,Y=2641.0 (should be at ascender 2642?)

	* Sacute (U+015A): X=1128.0,Y=2641.0 (should be at ascender 2642?)

	* Utilde (U+0168): X=1327.0,Y=1.0 (should be at baseline 0?)

	* Umacron (U+016A): X=1327.0,Y=1.0 (should be at baseline 0?)

	* Ubreve (U+016C): X=1327.0,Y=1.0 (should be at baseline 0?)

	* Uring (U+016E): X=1327.0,Y=1.0 (should be at baseline 0?)

	* Uhungarumlaut (U+0170): X=1327.0,Y=1.0 (should be at baseline 0?)

	* Uogonek (U+0172): X=1327.0,Y=1.0 (should be at baseline 0?)

	* Zacute (U+0179): X=1153.0,Y=2641.0 (should be at ascender 2642?)

	* ogonek (U+02DB): X=155.5,Y=1.0 (should be at baseline 0?)

	* uni0328 (U+0328): X=155.5,Y=1.0 (should be at baseline 0?)

	* Wacute (U+1E82): X=1655.0,Y=2641.0 (should be at ascender 2642?)

	* uni1E9E (U+1E9E): X=965.0,Y=-1.0 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=752.0,Y=1.0 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=502.0,Y=2007.0 (should be at cap-height 2008?)

	* uni1E9E (U+1E9E): X=1665.0,Y=2007.0 (should be at cap-height 2008?)

	* uni1E9E (U+1E9E): X=965.0,Y=-1.0 (should be at baseline 0?)

	* trademark (U+2122): X=199.5,Y=2006.5 (should be at cap-height 2008?)

	* trademark (U+2122): X=909.5,Y=2006.0 (should be at cap-height 2008?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* A (U+0041): L<<1006.0,1119.0>--<964.0,1488.0>> -> L<<964.0,1488.0>--<928.0,1771.0>>

	* A (U+0041): L<<928.0,1771.0>--<812.0,1489.0>> -> L<<812.0,1489.0>--<662.0,1119.0>>

	* AE (U+00C6): L<<1051.0,1764.0>--<950.0,1514.0>> -> L<<950.0,1514.0>--<756.0,1126.0>>

	* AE (U+00C6): L<<1084.0,1126.0>--<1054.0,1502.0>> -> L<<1054.0,1502.0>--<1051.0,1764.0>>

	* Aacute (U+00C1): L<<1006.0,1119.0>--<964.0,1488.0>> -> L<<964.0,1488.0>--<928.0,1771.0>>

	* Aacute (U+00C1): L<<928.0,1771.0>--<812.0,1489.0>> -> L<<812.0,1489.0>--<662.0,1119.0>>

	* Abreve (U+0102): L<<1006.0,1119.0>--<964.0,1488.0>> -> L<<964.0,1488.0>--<928.0,1771.0>>

	* Abreve (U+0102): L<<928.0,1771.0>--<812.0,1489.0>> -> L<<812.0,1489.0>--<662.0,1119.0>>

	* Acircumflex (U+00C2): L<<1006.0,1119.0>--<964.0,1488.0>> -> L<<964.0,1488.0>--<928.0,1771.0>>

	* Acircumflex (U+00C2): L<<928.0,1771.0>--<812.0,1489.0>> -> L<<812.0,1489.0>--<662.0,1119.0>>

	* Adieresis (U+00C4): L<<1006.0,1119.0>--<964.0,1488.0>> -> L<<964.0,1488.0>--<928.0,1771.0>>

	* Adieresis (U+00C4): L<<928.0,1771.0>--<812.0,1489.0>> -> L<<812.0,1489.0>--<662.0,1119.0>>

	* Agrave (U+00C0): L<<1006.0,1119.0>--<964.0,1488.0>> -> L<<964.0,1488.0>--<928.0,1771.0>>

	* Agrave (U+00C0): L<<928.0,1771.0>--<812.0,1489.0>> -> L<<812.0,1489.0>--<662.0,1119.0>>

	* Amacron (U+0100): L<<1006.0,1119.0>--<964.0,1488.0>> -> L<<964.0,1488.0>--<928.0,1771.0>>

	* Amacron (U+0100): L<<928.0,1771.0>--<812.0,1489.0>> -> L<<812.0,1489.0>--<662.0,1119.0>>

	* Aogonek (U+0104): L<<1006.0,1119.0>--<964.0,1488.0>> -> L<<964.0,1488.0>--<928.0,1771.0>>

	* Aogonek (U+0104): L<<928.0,1771.0>--<812.0,1489.0>> -> L<<812.0,1489.0>--<662.0,1119.0>>

	* Aring (U+00C5): L<<1006.0,1119.0>--<964.0,1488.0>> -> L<<964.0,1488.0>--<928.0,1771.0>>

	* Aring (U+00C5): L<<928.0,1771.0>--<812.0,1489.0>> -> L<<812.0,1489.0>--<662.0,1119.0>>

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

	* Wacute (U+1E82): L<<1318.0,1656.0>--<1245.0,1447.0>> -> L<<1245.0,1447.0>--<722.0,92.0>>

	* Wacute (U+1E82): L<<1459.0,1927.0>--<1640.0,678.0>> -> L<<1640.0,678.0>--<1680.0,364.0>>

	* Wacute (U+1E82): L<<1551.0,76.0>--<1348.0,1438.0>> -> L<<1348.0,1438.0>--<1318.0,1656.0>>

	* Wacute (U+1E82): L<<1680.0,364.0>--<1794.0,668.0>> -> L<<1794.0,668.0>--<2293.0,1929.0>>

	* Wacute (U+1E82): L<<411.0,1927.0>--<590.0,677.0>> -> L<<590.0,677.0>--<636.0,362.0>>

	* Wacute (U+1E82): L<<636.0,362.0>--<754.0,672.0>> -> L<<754.0,672.0>--<1239.0,1927.0>>

	* Wcircumflex (U+0174): L<<1318.0,1656.0>--<1245.0,1447.0>> -> L<<1245.0,1447.0>--<722.0,92.0>>

	* Wcircumflex (U+0174): L<<1459.0,1927.0>--<1640.0,678.0>> -> L<<1640.0,678.0>--<1680.0,364.0>>

	* Wcircumflex (U+0174): L<<1551.0,76.0>--<1348.0,1438.0>> -> L<<1348.0,1438.0>--<1318.0,1656.0>>

	* Wcircumflex (U+0174): L<<1680.0,364.0>--<1794.0,668.0>> -> L<<1794.0,668.0>--<2293.0,1929.0>>

	* Wcircumflex (U+0174): L<<411.0,1927.0>--<590.0,677.0>> -> L<<590.0,677.0>--<636.0,362.0>>

	* Wcircumflex (U+0174): L<<636.0,362.0>--<754.0,672.0>> -> L<<754.0,672.0>--<1239.0,1927.0>>

	* Wdieresis (U+1E84): L<<1318.0,1656.0>--<1245.0,1447.0>> -> L<<1245.0,1447.0>--<722.0,92.0>>

	* Wdieresis (U+1E84): L<<1459.0,1927.0>--<1640.0,678.0>> -> L<<1640.0,678.0>--<1680.0,364.0>>

	* Wdieresis (U+1E84): L<<1551.0,76.0>--<1348.0,1438.0>> -> L<<1348.0,1438.0>--<1318.0,1656.0>>

	* Wdieresis (U+1E84): L<<1680.0,364.0>--<1794.0,668.0>> -> L<<1794.0,668.0>--<2293.0,1929.0>>

	* Wdieresis (U+1E84): L<<411.0,1927.0>--<590.0,677.0>> -> L<<590.0,677.0>--<636.0,362.0>>

	* Wdieresis (U+1E84): L<<636.0,362.0>--<754.0,672.0>> -> L<<754.0,672.0>--<1239.0,1927.0>>

	* Wgrave (U+1E80): L<<1318.0,1656.0>--<1245.0,1447.0>> -> L<<1245.0,1447.0>--<722.0,92.0>>

	* Wgrave (U+1E80): L<<1459.0,1927.0>--<1640.0,678.0>> -> L<<1640.0,678.0>--<1680.0,364.0>>

	* Wgrave (U+1E80): L<<1551.0,76.0>--<1348.0,1438.0>> -> L<<1348.0,1438.0>--<1318.0,1656.0>>

	* Wgrave (U+1E80): L<<1680.0,364.0>--<1794.0,668.0>> -> L<<1794.0,668.0>--<2293.0,1929.0>>

	* Wgrave (U+1E80): L<<411.0,1927.0>--<590.0,677.0>> -> L<<590.0,677.0>--<636.0,362.0>>

	* Wgrave (U+1E80): L<<636.0,362.0>--<754.0,672.0>> -> L<<754.0,672.0>--<1239.0,1927.0>>

	* oslash (U+00F8): L<<303.0,235.0>--<471.0,566.0>> -> L<<471.0,566.0>--<636.0,914.0>>

	* oslash (U+00F8): L<<753.0,854.0>--<573.0,514.0>> -> L<<573.0,514.0>--<406.0,154.0>>

	* uni01CD (U+01CD): L<<1006.0,1119.0>--<964.0,1488.0>> -> L<<964.0,1488.0>--<928.0,1771.0>>

	* uni01CD (U+01CD): L<<928.0,1771.0>--<812.0,1489.0>> -> L<<812.0,1489.0>--<662.0,1119.0>>

	* uni01DE (U+01DE): L<<1006.0,1119.0>--<964.0,1488.0>> -> L<<964.0,1488.0>--<928.0,1771.0>>

	* uni01DE (U+01DE): L<<928.0,1771.0>--<812.0,1489.0>> -> L<<812.0,1489.0>--<662.0,1119.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details><details><summary><b>[19] NSWACTSchoolHand-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check family name for GF Guide compliance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_name_compliance">com.google.fonts/check/name/family_name_compliance</a>)</summary><div>


* 🔥 **FAIL** "NSW ACT School Hand" contains an abbreviation. [code: abbreviation]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 3023, but got 2642 instead [code: ascent]
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
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, malayalam, canadian-aboriginal, tai-le, math, tifinagh, old-permic, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
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
 * U+200C ZERO WIDTH NON-JOINER: try adding one of: yi, thai, tibetan, bengali, hanunoo, limbu, mandaic, meetei-mayek, pahawh-hmong, avestan, duployan, syloti-nagri, malayalam, manichaean, nko, sundanese, gunjala-gondi, khmer, phags-pa, dogra, gurmukhi, mongolian, brahmi, tifinagh, kharoshthi, gujarati, hanifi-rohingya, myanmar, sogdian, batak, chakma, rejang, tai-tham, siddham, syriac, javanese, balinese, kannada, tagalog, tai-le, khojki, warang-citi, new-tai-lue, mahajani, tagbanwa, tai-viet, takri, hatran, sharada, thaana, modi, saurashtra, telugu, kayah-li, tirhuta, grantha, tamil, newa, devanagari, lepcha, oriya, sinhala, kaithi, cham, psalter-pahlavi, buhid, buginese, khudawadi
 * U+200D ZERO WIDTH JOINER: try adding one of: yi, thai, tibetan, bengali, hanunoo, limbu, mandaic, meetei-mayek, pahawh-hmong, avestan, duployan, syloti-nagri, malayalam, manichaean, nko, sundanese, gunjala-gondi, phags-pa, dogra, gurmukhi, mongolian, brahmi, tifinagh, kharoshthi, gujarati, hanifi-rohingya, myanmar, batak, chakma, rejang, tai-tham, siddham, syriac, javanese, balinese, kannada, tagalog, tai-le, old-hungarian, khojki, warang-citi, new-tai-lue, mahajani, tagbanwa, tai-viet, takri, sharada, thaana, modi, saurashtra, telugu, kayah-li, tirhuta, grantha, tamil, newa, devanagari, lepcha, oriya, sinhala, kaithi, cham, psalter-pahlavi, buhid, buginese, khudawadi
 * U+202F NARROW NO-BREAK SPACE: try adding one of: yi, mongolian
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
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- i.loclTRK

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case

	- uni004A0301

	- uni006A0301

	- uni013B.loclMAH

	- uni013C.loclMAH

	- uni0145.loclMAH

	- uni0146.loclMAH
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
divide, multiply

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

	* cedilla (U+00B8): X=-25.0,Y=-2.0 (should be at baseline 0?)

	* Agrave (U+00C0): X=723.0,Y=2640.5 (should be at ascender 2642?)

	* Aring (U+00C5): X=898.5,Y=2640.5 (should be at ascender 2642?)

	* Ccedilla (U+00C7): X=492.0,Y=-2.0 (should be at baseline 0?)

	* Egrave (U+00C8): X=787.0,Y=2640.5 (should be at ascender 2642?)

	* Igrave (U+00CC): X=342.0,Y=2640.5 (should be at ascender 2642?)

	* Ograve (U+00D2): X=738.0,Y=2640.5 (should be at ascender 2642?)

	* Oslash (U+00D8): X=440.0,Y=-2.0 (should be at baseline 0?)

	* Ugrave (U+00D9): X=1304.0,Y=1.0 (should be at baseline 0?)

	* Ugrave (U+00D9): X=862.0,Y=2640.5 (should be at ascender 2642?)

	* Uacute (U+00DA): X=1304.0,Y=1.0 (should be at baseline 0?)

	* Ucircumflex (U+00DB): X=1304.0,Y=1.0 (should be at baseline 0?)

	* Udieresis (U+00DC): X=1304.0,Y=1.0 (should be at baseline 0?)

	* germandbls (U+00DF): X=218.0,Y=-1.0 (should be at baseline 0?)

	* germandbls (U+00DF): X=218.0,Y=-1.0 (should be at baseline 0?)

	* ccedilla (U+00E7): X=307.0,Y=-2.0 (should be at baseline 0?)

	* thorn (U+00FE): X=520.0,Y=1.0 (should be at baseline 0?)

	* thorn (U+00FE): X=279.0,Y=1.0 (should be at baseline 0?)

	* Iogonek (U+012E): X=103.5,Y=2.0 (should be at baseline 0?)

	* Lcaron (U+013D): X=1102.0,Y=2009.0 (should be at cap-height 2008?)

	* lcaron (U+013E): X=633.5,Y=2008.5 (should be at cap-height 2008?)

	* sacute (U+015B): X=369.5,Y=-1.0 (should be at baseline 0?)

	* Scedilla (U+015E): X=480.0,Y=-2.0 (should be at baseline 0?)

	* scedilla (U+015F): X=369.5,Y=-1.0 (should be at baseline 0?)

	* scedilla (U+015F): X=306.0,Y=-2.0 (should be at baseline 0?)

	* scaron (U+0161): X=369.5,Y=-1.0 (should be at baseline 0?)

	* uni0162 (U+0162): X=453.0,Y=-2.0 (should be at baseline 0?)

	* uni0163 (U+0163): X=293.0,Y=-2.0 (should be at baseline 0?)

	* tcaron (U+0165): X=979.5,Y=2010.0 (should be at cap-height 2008?)

	* Utilde (U+0168): X=1304.0,Y=1.0 (should be at baseline 0?)

	* Umacron (U+016A): X=1304.0,Y=1.0 (should be at baseline 0?)

	* Ubreve (U+016C): X=1304.0,Y=1.0 (should be at baseline 0?)

	* Uring (U+016E): X=1304.0,Y=1.0 (should be at baseline 0?)

	* Uring (U+016E): X=1037.5,Y=2640.5 (should be at ascender 2642?)

	* Uhungarumlaut (U+0170): X=1304.0,Y=1.0 (should be at baseline 0?)

	* Uogonek (U+0172): X=1304.0,Y=1.0 (should be at baseline 0?)

	* uni0219 (U+0219): X=369.5,Y=-1.0 (should be at baseline 0?)

	* ogonek (U+02DB): X=328.0,Y=-2.0 (should be at baseline 0?)

	* uni0327 (U+0327): X=-25.0,Y=-2.0 (should be at baseline 0?)

	* uni0328 (U+0328): X=328.0,Y=-2.0 (should be at baseline 0?)

	* Wgrave (U+1E80): X=1198.0,Y=2640.5 (should be at ascender 2642?)

	* uni1E9E (U+1E9E): X=716.0,Y=1.0 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=484.0,Y=2007.0 (should be at cap-height 2008?)

	* uni1E9E (U+1E9E): X=1652.0,Y=2007.0 (should be at cap-height 2008?)

	* Ygrave (U+1EF2): X=685.0,Y=2640.5 (should be at ascender 2642?)

	* Euro (U+20AC): X=865.0,Y=2.0 (should be at baseline 0?)

	* Euro (U+20AC): X=865.0,Y=2.0 (should be at baseline 0?) [code: found-misalignments]
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

	* uni01DE (U+01DE): L<<906.0,1834.0>--<765.0,1504.0>> -> L<<765.0,1504.0>--<608.0,1137.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* w (U+0077): L<<805.0,313.0>--<856.0,666.0>>/B<<856.0,666.0>-<750.0,403.0>-<662.5,253.5>> = 13.730520481405952

	* wacute (U+1E83): L<<805.0,313.0>--<856.0,666.0>>/B<<856.0,666.0>-<750.0,403.0>-<662.5,253.5>> = 13.730520481405952

	* wcircumflex (U+0175): L<<805.0,313.0>--<856.0,666.0>>/B<<856.0,666.0>-<750.0,403.0>-<662.5,253.5>> = 13.730520481405952

	* wdieresis (U+1E85): L<<805.0,313.0>--<856.0,666.0>>/B<<856.0,666.0>-<750.0,403.0>-<662.5,253.5>> = 13.730520481405952

	* wgrave (U+1E81): L<<805.0,313.0>--<856.0,666.0>>/B<<856.0,666.0>-<750.0,403.0>-<662.5,253.5>> = 13.730520481405952 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details><details><summary><b>[20] NSWACTSchoolHand-SemiBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check family name for GF Guide compliance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_name_compliance">com.google.fonts/check/name/family_name_compliance</a>)</summary><div>


* 🔥 **FAIL** "NSW ACT School Hand" contains an abbreviation. [code: abbreviation]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 3023, but got 2642 instead [code: ascent]
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
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, malayalam, canadian-aboriginal, tai-le, math, tifinagh, old-permic, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
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
 * U+200C ZERO WIDTH NON-JOINER: try adding one of: yi, thai, tibetan, bengali, hanunoo, limbu, mandaic, meetei-mayek, pahawh-hmong, avestan, duployan, syloti-nagri, malayalam, manichaean, nko, sundanese, gunjala-gondi, khmer, phags-pa, dogra, gurmukhi, mongolian, brahmi, tifinagh, kharoshthi, gujarati, hanifi-rohingya, myanmar, sogdian, batak, chakma, rejang, tai-tham, siddham, syriac, javanese, balinese, kannada, tagalog, tai-le, khojki, warang-citi, new-tai-lue, mahajani, tagbanwa, tai-viet, takri, hatran, sharada, thaana, modi, saurashtra, telugu, kayah-li, tirhuta, grantha, tamil, newa, devanagari, lepcha, oriya, sinhala, kaithi, cham, psalter-pahlavi, buhid, buginese, khudawadi
 * U+200D ZERO WIDTH JOINER: try adding one of: yi, thai, tibetan, bengali, hanunoo, limbu, mandaic, meetei-mayek, pahawh-hmong, avestan, duployan, syloti-nagri, malayalam, manichaean, nko, sundanese, gunjala-gondi, phags-pa, dogra, gurmukhi, mongolian, brahmi, tifinagh, kharoshthi, gujarati, hanifi-rohingya, myanmar, batak, chakma, rejang, tai-tham, siddham, syriac, javanese, balinese, kannada, tagalog, tai-le, old-hungarian, khojki, warang-citi, new-tai-lue, mahajani, tagbanwa, tai-viet, takri, sharada, thaana, modi, saurashtra, telugu, kayah-li, tirhuta, grantha, tamil, newa, devanagari, lepcha, oriya, sinhala, kaithi, cham, psalter-pahlavi, buhid, buginese, khudawadi
 * U+202F NARROW NO-BREAK SPACE: try adding one of: yi, mongolian
 * U+205F MEDIUM MATHEMATICAL SPACE: not included in any glyphset definition
 * U+221E INFINITY: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'NSW ACT School Hand SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.784x (3568) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- i.loclTRK

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case

	- uni004A0301

	- uni006A0301

	- uni013B.loclMAH

	- uni013C.loclMAH

	- uni0145.loclMAH

	- uni0146.loclMAH
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

	* Yacute (U+00DD): X=326.0,Y=1.5 (should be at baseline 0?)

	* Thorn (U+00DE): X=508.0,Y=2009.0 (should be at cap-height 2008?)

	* germandbls (U+00DF): X=933.0,Y=2009.0 (should be at cap-height 2008?)

	* Abreve (U+0102): X=1282.0,Y=2644.0 (should be at ascender 2642?)

	* Gbreve (U+011E): X=1345.0,Y=2644.0 (should be at ascender 2642?)

	* gbreve (U+011F): X=287.5,Y=-1.0 (should be at baseline 0?)

	* gdotaccent (U+0121): X=287.5,Y=-1.0 (should be at baseline 0?)

	* uni0123 (U+0123): X=287.5,Y=-1.0 (should be at baseline 0?)

	* Iogonek (U+012E): X=107.0,Y=-0.5 (should be at baseline 0?)

	* iogonek (U+012F): X=344.0,Y=2.0 (should be at baseline 0?)

	* Racute (U+0154): X=508.0,Y=2007.0 (should be at cap-height 2008?)

	* uni0156 (U+0156): X=508.0,Y=2007.0 (should be at cap-height 2008?)

	* Rcaron (U+0158): X=508.0,Y=2007.0 (should be at cap-height 2008?)

	* Ubreve (U+016C): X=1401.0,Y=2644.0 (should be at ascender 2642?)

	* Ycircumflex (U+0176): X=326.0,Y=1.5 (should be at baseline 0?)

	* Ydieresis (U+0178): X=326.0,Y=1.5 (should be at baseline 0?)

	* Zacute (U+0179): X=369.0,Y=2009.0 (should be at cap-height 2008?)

	* Zacute (U+0179): X=1383.0,Y=2009.0 (should be at cap-height 2008?)

	* Zdotaccent (U+017B): X=369.0,Y=2009.0 (should be at cap-height 2008?)

	* Zdotaccent (U+017B): X=1383.0,Y=2009.0 (should be at cap-height 2008?)

	* Zcaron (U+017D): X=369.0,Y=2009.0 (should be at cap-height 2008?)

	* Zcaron (U+017D): X=1383.0,Y=2009.0 (should be at cap-height 2008?)

	* uni1E21 (U+1E21): X=287.5,Y=-1.0 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=1008.0,Y=-2.0 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=1008.0,Y=-2.0 (should be at baseline 0?)

	* Ygrave (U+1EF2): X=326.0,Y=1.5 (should be at baseline 0?)

	* uni1EF8 (U+1EF8): X=326.0,Y=1.5 (should be at baseline 0?) [code: found-misalignments]
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

	* Oslash (U+00D8) contains a short segment B<<598.0,-20.0>-<587.0,-20.0>-<577.0,-19.0>>

	* uni0136 (U+0136) contains a short segment B<<1420.0,188.0>-<1439.0,162.0>-<1446.0,139.5>>

	* uni0136 (U+0136) contains a short segment B<<1446.0,139.5>-<1453.0,117.0>-<1452.0,97.0>>

	* Wcircumflex (U+0174) contains a short segment B<<447.0,1978.5>-<482.0,1949.0>-<487.0,1907.0>>

	* Wcircumflex (U+0174) contains a short segment B<<1246.0,1909.0>-<1262.0,1951.0>-<1293.5,1979.5>>

	* Wcircumflex (U+0174) contains a short segment B<<1489.0,1980.0>-<1524.0,1952.0>-<1533.0,1907.0>>

	* Wcircumflex (U+0174) contains a short segment B<<2295.0,1917.0>-<2310.0,1952.0>-<2342.5,1980.0>>

	* Wcircumflex (U+0174) contains a short segment B<<1822.0,90.0>-<1805.0,47.0>-<1776.5,23.5>>

	* Wcircumflex (U+0174) contains a short segment B<<1599.0,26.5>-<1566.0,53.0>-<1561.0,88.0>>

	* Wgrave (U+1E80) contains a short segment B<<447.0,1978.5>-<482.0,1949.0>-<487.0,1907.0>>

	* Wgrave (U+1E80) contains a short segment B<<1246.0,1909.0>-<1262.0,1951.0>-<1293.5,1979.5>>

	* Wgrave (U+1E80) contains a short segment B<<1489.0,1980.0>-<1524.0,1952.0>-<1533.0,1907.0>>

	* Wgrave (U+1E80) contains a short segment B<<2295.0,1917.0>-<2310.0,1952.0>-<2342.5,1980.0>>

	* Wgrave (U+1E80) contains a short segment B<<1822.0,90.0>-<1805.0,47.0>-<1776.5,23.5>>

	* Wgrave (U+1E80) contains a short segment B<<1599.0,26.5>-<1566.0,53.0>-<1561.0,88.0>>

	* Wacute (U+1E82) contains a short segment B<<447.0,1978.5>-<482.0,1949.0>-<487.0,1907.0>>

	* Wacute (U+1E82) contains a short segment B<<1246.0,1909.0>-<1262.0,1951.0>-<1293.5,1979.5>>

	* Wacute (U+1E82) contains a short segment B<<1489.0,1980.0>-<1524.0,1952.0>-<1533.0,1907.0>>

	* Wacute (U+1E82) contains a short segment B<<2295.0,1917.0>-<2310.0,1952.0>-<2342.5,1980.0>>

	* Wacute (U+1E82) contains a short segment B<<1822.0,90.0>-<1805.0,47.0>-<1776.5,23.5>>

	* Wacute (U+1E82) contains a short segment B<<1599.0,26.5>-<1566.0,53.0>-<1561.0,88.0>>

	* Wdieresis (U+1E84) contains a short segment B<<447.0,1978.5>-<482.0,1949.0>-<487.0,1907.0>>

	* Wdieresis (U+1E84) contains a short segment B<<1246.0,1909.0>-<1262.0,1951.0>-<1293.5,1979.5>>

	* Wdieresis (U+1E84) contains a short segment B<<1489.0,1980.0>-<1524.0,1952.0>-<1533.0,1907.0>>

	* Wdieresis (U+1E84) contains a short segment B<<2295.0,1917.0>-<2310.0,1952.0>-<2342.5,1980.0>>

	* Wdieresis (U+1E84) contains a short segment B<<1822.0,90.0>-<1805.0,47.0>-<1776.5,23.5>>

	* Wdieresis (U+1E84) contains a short segment B<<1599.0,26.5>-<1566.0,53.0>-<1561.0,88.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<788.0,0.0>-<768.0,1.0>-<739.5,10.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<739.5,10.0>-<711.0,19.0>-<687.5,42.5>>

	* uni1E9E (U+1E9E) contains a short segment B<<1794.0,1944.0>-<1811.0,1917.0>-<1811.0,1881.0>>

	* Euro (U+20AC) contains a short segment B<<374.0,1055.0>-<377.0,1073.0>-<380.5,1090.5>>

	* Euro (U+20AC) contains a short segment B<<380.5,1090.5>-<384.0,1108.0>-<388.0,1125.0>>

	* lessequal (U+2264) contains a short segment L<<155.0,629.0>--<155.0,630.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* A (U+0041): L<<1012.0,1100.0>--<976.0,1471.0>> -> L<<976.0,1471.0>--<951.0,1707.0>>

	* A (U+0041): L<<951.0,1707.0>--<858.0,1474.0>> -> L<<858.0,1474.0>--<715.0,1100.0>>

	* AE (U+00C6): L<<1070.0,1689.0>--<976.0,1450.0>> -> L<<976.0,1450.0>--<808.0,1114.0>>

	* AE (U+00C6): L<<1094.0,1114.0>--<1068.0,1442.0>> -> L<<1068.0,1442.0>--<1070.0,1689.0>>

	* Aacute (U+00C1): L<<1012.0,1100.0>--<976.0,1471.0>> -> L<<976.0,1471.0>--<951.0,1707.0>>

	* Aacute (U+00C1): L<<951.0,1707.0>--<858.0,1474.0>> -> L<<858.0,1474.0>--<715.0,1100.0>>

	* Abreve (U+0102): L<<1012.0,1100.0>--<976.0,1471.0>> -> L<<976.0,1471.0>--<951.0,1707.0>>

	* Abreve (U+0102): L<<951.0,1707.0>--<858.0,1474.0>> -> L<<858.0,1474.0>--<715.0,1100.0>>

	* Acircumflex (U+00C2): L<<1012.0,1100.0>--<976.0,1471.0>> -> L<<976.0,1471.0>--<951.0,1707.0>>

	* Acircumflex (U+00C2): L<<951.0,1707.0>--<858.0,1474.0>> -> L<<858.0,1474.0>--<715.0,1100.0>>

	* Adieresis (U+00C4): L<<1012.0,1100.0>--<976.0,1471.0>> -> L<<976.0,1471.0>--<951.0,1707.0>>

	* Adieresis (U+00C4): L<<951.0,1707.0>--<858.0,1474.0>> -> L<<858.0,1474.0>--<715.0,1100.0>>

	* Agrave (U+00C0): L<<1012.0,1100.0>--<976.0,1471.0>> -> L<<976.0,1471.0>--<951.0,1707.0>>

	* Agrave (U+00C0): L<<951.0,1707.0>--<858.0,1474.0>> -> L<<858.0,1474.0>--<715.0,1100.0>>

	* Amacron (U+0100): L<<1012.0,1100.0>--<976.0,1471.0>> -> L<<976.0,1471.0>--<951.0,1707.0>>

	* Amacron (U+0100): L<<951.0,1707.0>--<858.0,1474.0>> -> L<<858.0,1474.0>--<715.0,1100.0>>

	* Aogonek (U+0104): L<<1012.0,1100.0>--<976.0,1471.0>> -> L<<976.0,1471.0>--<951.0,1707.0>>

	* Aogonek (U+0104): L<<951.0,1707.0>--<858.0,1474.0>> -> L<<858.0,1474.0>--<715.0,1100.0>>

	* Aring (U+00C5): L<<1012.0,1100.0>--<976.0,1471.0>> -> L<<976.0,1471.0>--<951.0,1707.0>>

	* Aring (U+00C5): L<<951.0,1707.0>--<858.0,1474.0>> -> L<<858.0,1474.0>--<715.0,1100.0>>

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

	* Wacute (U+1E82): L<<1348.0,1544.0>--<1286.0,1359.0>> -> L<<1286.0,1359.0>--<808.0,112.0>>

	* Wacute (U+1E82): L<<1533.0,1907.0>--<1697.0,766.0>> -> L<<1697.0,766.0>--<1731.0,480.0>>

	* Wacute (U+1E82): L<<1561.0,88.0>--<1371.0,1355.0>> -> L<<1371.0,1355.0>--<1348.0,1544.0>>

	* Wacute (U+1E82): L<<1731.0,480.0>--<1837.0,760.0>> -> L<<1837.0,760.0>--<2295.0,1917.0>>

	* Wacute (U+1E82): L<<487.0,1907.0>--<648.0,772.0>> -> L<<648.0,772.0>--<691.0,458.0>>

	* Wacute (U+1E82): L<<691.0,458.0>--<804.0,764.0>> -> L<<804.0,764.0>--<1246.0,1909.0>>

	* Wcircumflex (U+0174): L<<1348.0,1544.0>--<1286.0,1359.0>> -> L<<1286.0,1359.0>--<808.0,112.0>>

	* Wcircumflex (U+0174): L<<1533.0,1907.0>--<1697.0,766.0>> -> L<<1697.0,766.0>--<1731.0,480.0>>

	* Wcircumflex (U+0174): L<<1561.0,88.0>--<1371.0,1355.0>> -> L<<1371.0,1355.0>--<1348.0,1544.0>>

	* Wcircumflex (U+0174): L<<1731.0,480.0>--<1837.0,760.0>> -> L<<1837.0,760.0>--<2295.0,1917.0>>

	* Wcircumflex (U+0174): L<<487.0,1907.0>--<648.0,772.0>> -> L<<648.0,772.0>--<691.0,458.0>>

	* Wcircumflex (U+0174): L<<691.0,458.0>--<804.0,764.0>> -> L<<804.0,764.0>--<1246.0,1909.0>>

	* Wdieresis (U+1E84): L<<1348.0,1544.0>--<1286.0,1359.0>> -> L<<1286.0,1359.0>--<808.0,112.0>>

	* Wdieresis (U+1E84): L<<1533.0,1907.0>--<1697.0,766.0>> -> L<<1697.0,766.0>--<1731.0,480.0>>

	* Wdieresis (U+1E84): L<<1561.0,88.0>--<1371.0,1355.0>> -> L<<1371.0,1355.0>--<1348.0,1544.0>>

	* Wdieresis (U+1E84): L<<1731.0,480.0>--<1837.0,760.0>> -> L<<1837.0,760.0>--<2295.0,1917.0>>

	* Wdieresis (U+1E84): L<<487.0,1907.0>--<648.0,772.0>> -> L<<648.0,772.0>--<691.0,458.0>>

	* Wdieresis (U+1E84): L<<691.0,458.0>--<804.0,764.0>> -> L<<804.0,764.0>--<1246.0,1909.0>>

	* Wgrave (U+1E80): L<<1348.0,1544.0>--<1286.0,1359.0>> -> L<<1286.0,1359.0>--<808.0,112.0>>

	* Wgrave (U+1E80): L<<1533.0,1907.0>--<1697.0,766.0>> -> L<<1697.0,766.0>--<1731.0,480.0>>

	* Wgrave (U+1E80): L<<1561.0,88.0>--<1371.0,1355.0>> -> L<<1371.0,1355.0>--<1348.0,1544.0>>

	* Wgrave (U+1E80): L<<1731.0,480.0>--<1837.0,760.0>> -> L<<1837.0,760.0>--<2295.0,1917.0>>

	* Wgrave (U+1E80): L<<487.0,1907.0>--<648.0,772.0>> -> L<<648.0,772.0>--<691.0,458.0>>

	* Wgrave (U+1E80): L<<691.0,458.0>--<804.0,764.0>> -> L<<804.0,764.0>--<1246.0,1909.0>>

	* oslash (U+00F8): L<<345.0,292.0>--<482.0,554.0>> -> L<<482.0,554.0>--<635.0,876.0>>

	* oslash (U+00F8): L<<764.0,813.0>--<591.0,504.0>> -> L<<591.0,504.0>--<454.0,204.0>>

	* uni01CD (U+01CD): L<<1012.0,1100.0>--<976.0,1471.0>> -> L<<976.0,1471.0>--<951.0,1707.0>>

	* uni01CD (U+01CD): L<<951.0,1707.0>--<858.0,1474.0>> -> L<<858.0,1474.0>--<715.0,1100.0>>

	* uni01DE (U+01DE): L<<1012.0,1100.0>--<976.0,1471.0>> -> L<<976.0,1471.0>--<951.0,1707.0>>

	* uni01DE (U+01DE): L<<951.0,1707.0>--<858.0,1474.0>> -> L<<858.0,1474.0>--<715.0,1100.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details><details><summary><b>[20] NSWACTSchoolHand-Bold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check family name for GF Guide compliance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_name_compliance">com.google.fonts/check/name/family_name_compliance</a>)</summary><div>


* 🔥 **FAIL** "NSW ACT School Hand" contains an abbreviation. [code: abbreviation]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 3023, but got 2642 instead [code: ascent]
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
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, malayalam, canadian-aboriginal, tai-le, math, tifinagh, old-permic, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
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
 * U+200C ZERO WIDTH NON-JOINER: try adding one of: yi, thai, tibetan, bengali, hanunoo, limbu, mandaic, meetei-mayek, pahawh-hmong, avestan, duployan, syloti-nagri, malayalam, manichaean, nko, sundanese, gunjala-gondi, khmer, phags-pa, dogra, gurmukhi, mongolian, brahmi, tifinagh, kharoshthi, gujarati, hanifi-rohingya, myanmar, sogdian, batak, chakma, rejang, tai-tham, siddham, syriac, javanese, balinese, kannada, tagalog, tai-le, khojki, warang-citi, new-tai-lue, mahajani, tagbanwa, tai-viet, takri, hatran, sharada, thaana, modi, saurashtra, telugu, kayah-li, tirhuta, grantha, tamil, newa, devanagari, lepcha, oriya, sinhala, kaithi, cham, psalter-pahlavi, buhid, buginese, khudawadi
 * U+200D ZERO WIDTH JOINER: try adding one of: yi, thai, tibetan, bengali, hanunoo, limbu, mandaic, meetei-mayek, pahawh-hmong, avestan, duployan, syloti-nagri, malayalam, manichaean, nko, sundanese, gunjala-gondi, phags-pa, dogra, gurmukhi, mongolian, brahmi, tifinagh, kharoshthi, gujarati, hanifi-rohingya, myanmar, batak, chakma, rejang, tai-tham, siddham, syriac, javanese, balinese, kannada, tagalog, tai-le, old-hungarian, khojki, warang-citi, new-tai-lue, mahajani, tagbanwa, tai-viet, takri, sharada, thaana, modi, saurashtra, telugu, kayah-li, tirhuta, grantha, tamil, newa, devanagari, lepcha, oriya, sinhala, kaithi, cham, psalter-pahlavi, buhid, buginese, khudawadi
 * U+202F NARROW NO-BREAK SPACE: try adding one of: yi, mongolian
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
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- i.loclTRK

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case

	- uni004A0301

	- uni006A0301

	- uni013B.loclMAH

	- uni013C.loclMAH

	- uni0145.loclMAH

	- uni0146.loclMAH
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

	* g (U+0067): X=299.0,Y=-1.5 (should be at baseline 0?)

	* q (U+0071): X=715.5,Y=-925.0 (should be at descender -926?)

	* braceleft (U+007B): X=613.5,Y=2006.0 (should be at cap-height 2008?)

	* braceright (U+007D): X=-47.5,Y=-924.0 (should be at descender -926?)

	* braceright (U+007D): X=239.5,Y=2009.5 (should be at cap-height 2008?)

	* yen (U+00A5): X=273.0,Y=1.0 (should be at baseline 0?)

	* Ccedilla (U+00C7): X=1238.0,Y=2009.5 (should be at cap-height 2008?)

	* Yacute (U+00DD): X=393.0,Y=1.0 (should be at baseline 0?)

	* Thorn (U+00DE): X=528.0,Y=2009.0 (should be at cap-height 2008?)

	* germandbls (U+00DF): X=950.0,Y=2010.0 (should be at cap-height 2008?)

	* Cacute (U+0106): X=1238.0,Y=2009.5 (should be at cap-height 2008?)

	* Cdotaccent (U+010A): X=1238.0,Y=2009.5 (should be at cap-height 2008?)

	* Ccaron (U+010C): X=1238.0,Y=2009.5 (should be at cap-height 2008?)

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

	* Oslash (U+00D8) contains a short segment L<<649.0,-20.0>--<649.0,-20.0>>

	* ae (U+00E6) contains a short segment B<<971.0,388.5>-<970.0,375.0>-<969.0,364.0>>

	* thorn (U+00FE) contains a short segment L<<461.0,252.0>--<465.0,252.0>>

	* uni0136 (U+0136) contains a short segment B<<1509.0,174.5>-<1518.0,148.0>-<1518.0,125.0>>

	* lslash (U+0142) contains a short segment L<<549.0,1103.0>--<563.0,1108.0>>

	* Wcircumflex (U+0174) contains a short segment B<<2604.5,1906.0>-<2615.0,1864.0>-<2599.0,1826.0>>

	* Wgrave (U+1E80) contains a short segment B<<2604.5,1906.0>-<2615.0,1864.0>-<2599.0,1826.0>>

	* Wacute (U+1E82) contains a short segment B<<2604.5,1906.0>-<2615.0,1864.0>-<2599.0,1826.0>>

	* Wdieresis (U+1E84) contains a short segment B<<2604.5,1906.0>-<2615.0,1864.0>-<2599.0,1826.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<824.0,0.0>-<802.0,1.0>-<766.0,11.5>>

	* Euro (U+20AC) contains a short segment B<<366.0,1059.0>-<368.0,1070.0>-<369.5,1080.0>>

	* Euro (U+20AC) contains a short segment B<<369.5,1080.0>-<371.0,1090.0>-<372.0,1100.0>>

	* notequal (U+2260) contains a short segment L<<837.0,1030.0>--<863.0,1030.0>>

	* lessequal (U+2264) contains a short segment L<<183.0,624.0>--<183.0,626.0>> [code: found-short-segments]
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

	* V (U+0056): L<<563.0,1886.0>--<717.0,939.0>> -> L<<717.0,939.0>--<750.0,673.0>>

	* V (U+0056): L<<750.0,673.0>--<844.0,939.0>> -> L<<844.0,939.0>--<1253.0,1909.0>>

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

	* yen (U+00A5): L<<524.0,1030.0>--<523.0,1032.0>> -> L<<523.0,1032.0>--<158.0,1802.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Oslash (U+00D8): B<<903.0,61.0>-<778.0,-15.0>-<649.0,-20.0>>/L<<649.0,-20.0>--<649.0,-20.0>> = 2.219655553197814

	* cent (U+00A2): L<<576.0,831.0>--<532.0,497.0>>/B<<532.0,497.0>-<533.0,502.0>-<533.0,500.0>> = 3.80520002340806 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 12 | 16 | 50 | 486 | 21 | 360 | 0 |
| 1% | 2% | 5% | 51% | 2% | 38% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
