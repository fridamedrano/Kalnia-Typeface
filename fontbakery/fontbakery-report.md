## Fontbakery report

Fontbakery version: 0.8.8

<details><summary><b>[13] Kalnia-RegularExtended.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/ttf/Kalnia-RegularExtended.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: TYPOGRAPHIC_SUBFAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/typographicsubfamilyname">com.google.fonts/check/name/typographicsubfamilyname</a>)</summary><div>


* 🔥 **FAIL** TYPOGRAPHIC_SUBFAMILY_NAME entry for Win "Regular Extended" must be "Regular". Please note, since the font style is RIBBI, this record can be safely deleted. [code: bad-win-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Name table records must not have trailing spaces. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/name/trailing_spaces">com.google.fonts/check/name/trailing_spaces</a>)</summary><div>


* 🔥 **FAIL** Name table record with key = (3, 1, 1033, 10) has trailing spaces that must be removed: 'Kalnia is [...]dth axes. ' [code: trailing-space]
</div></details><details><summary>🔥 <b>FAIL:</b> Does full font name begin with the font family name? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/name.html#com.google.fonts/check/name/match_familyname_fullfont">com.google.fonts/check/name/match_familyname_fullfont</a>)</summary><div>


* 🔥 **FAIL** On the 'name' table, the full font name (NameID 4 - FULL_FONT_NAME: 'Kalnia Extended') does not begin with font family name (NameID 1 - FONT_FAMILY_NAME: 'Kalnia Regular Extended') [code: does-not]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Description strings in the name table must not exceed 200 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/description_max_length">com.google.fonts/check/name/description_max_length</a>)</summary><div>


* ⚠ **WARN** A few name table entries with ID=10 (NameID.DESCRIPTION) are longer than 200 characters. Please check whether those entries are copyright notices mistakenly stored in the description string entries by a bug in an old FontLab version. If that's the case, then such copyright notices must be removed from these entries. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:
	- f + b
	- b + f
	- f + h
	- h + i
	- i + j
	- j + k
	- k + l

   [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: NULL	Contours detected: 3	Expected: 0
	- Glyph name: uni00AD	Contours detected: 1	Expected: 0
	- Glyph name: NULL	Contours detected: 3	Expected: 0
	- Glyph name: fi	Contours detected: 1	Expected: 3
	- Glyph name: fl	Contours detected: 1	Expected: 2 
	- And Glyph name: uni00AD	Contours detected: 1	Expected: 0
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* dollar (U+0024): X=610.0,Y=1.0 (should be at baseline 0?)
	* dollar (U+0024): X=561.0,Y=709.0 (should be at cap-height 708?)
	* ampersand (U+0026): X=758.5,Y=709.0 (should be at cap-height 708?)
	* ampersand (U+0026): X=610.0,Y=710.0 (should be at cap-height 708?)
	* parenleft (U+0028): X=360.0,Y=1.5 (should be at baseline 0?)
	* parenright (U+0029): X=402.0,Y=1.5 (should be at baseline 0?)
	* comma (U+002C): X=353.5,Y=2.0 (should be at baseline 0?)
	* two (U+0032): X=550.0,Y=-1.0 (should be at baseline 0?)
	* three (U+0033): X=446.0,Y=2.0 (should be at baseline 0?)
	* three (U+0033): X=451.0,Y=707.0 (should be at cap-height 708?) and 77 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* fi (U+FB01): L<<439.0,500.0>--<621.0,492.0>> -> L<<621.0,492.0>--<1082.0,515.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * AE (U+00C6): L<<1301.0,692.0>--<942.0,693.0>>
 * AE (U+00C6): L<<942.0,15.0>--<1309.0,16.0>>
 * E (U+0045): L<<430.0,15.0>--<797.0,16.0>>
 * E (U+0045): L<<790.0,692.0>--<430.0,693.0>>
 * Eacute (U+00C9): L<<430.0,15.0>--<797.0,16.0>>
 * Eacute (U+00C9): L<<790.0,692.0>--<430.0,693.0>>
 * Ecircumflex (U+00CA): L<<430.0,15.0>--<797.0,16.0>>
 * Ecircumflex (U+00CA): L<<790.0,692.0>--<430.0,693.0>>
 * Edieresis (U+00CB): L<<430.0,15.0>--<797.0,16.0>>
 * Edieresis (U+00CB): L<<790.0,692.0>--<430.0,693.0>> and 10 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[11] Kalnia-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Name table records must not have trailing spaces. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/name/trailing_spaces">com.google.fonts/check/name/trailing_spaces</a>)</summary><div>


* 🔥 **FAIL** Name table record with key = (3, 1, 1033, 10) has trailing spaces that must be removed: 'Kalnia is [...]dth axes. ' [code: trailing-space]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Description strings in the name table must not exceed 200 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/description_max_length">com.google.fonts/check/name/description_max_length</a>)</summary><div>


* ⚠ **WARN** A few name table entries with ID=10 (NameID.DESCRIPTION) are longer than 200 characters. Please check whether those entries are copyright notices mistakenly stored in the description string entries by a bug in an old FontLab version. If that's the case, then such copyright notices must be removed from these entries. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:
	- f + b
	- b + f
	- f + h
	- h + i
	- i + j
	- j + k
	- k + l

   [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: NULL	Contours detected: 3	Expected: 0
	- Glyph name: uni00AD	Contours detected: 1	Expected: 0
	- Glyph name: NULL	Contours detected: 3	Expected: 0
	- Glyph name: fi	Contours detected: 1	Expected: 3
	- Glyph name: fl	Contours detected: 1	Expected: 2 
	- And Glyph name: uni00AD	Contours detected: 1	Expected: 0
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* percent (U+0025): X=239.0,Y=709.0 (should be at cap-height 708?)
	* ampersand (U+0026): X=158.5,Y=2.0 (should be at baseline 0?)
	* ampersand (U+0026): X=640.5,Y=1.5 (should be at baseline 0?)
	* ampersand (U+0026): X=358.0,Y=709.0 (should be at cap-height 708?)
	* comma (U+002C): X=68.0,Y=-2.0 (should be at baseline 0?)
	* zero (U+0030): X=321.0,Y=1.0 (should be at baseline 0?)
	* zero (U+0030): X=321.0,Y=707.0 (should be at cap-height 708?)
	* zero (U+0030): X=321.0,Y=1.0 (should be at baseline 0?)
	* two (U+0032): X=87.5,Y=-2.0 (should be at baseline 0?)
	* two (U+0032): X=202.0,Y=707.0 (should be at cap-height 708?) and 73 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* four (U+0034): L<<410.0,204.0>--<410.0,546.0>> -> L<<410.0,546.0>--<415.0,724.0>>
	* onequarter (U+00BC): L<<392.0,93.0>--<392.0,230.0>> -> L<<392.0,230.0>--<395.0,302.0>>
	* threequarters (U+00BE): L<<502.0,93.0>--<502.0,230.0>> -> L<<502.0,230.0>--<505.0,302.0>> and uni2074 (U+2074): L<<171.0,509.0>--<171.0,646.0>> -> L<<171.0,646.0>--<174.0,718.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* seven (U+0037): L<<85.0,709.0>--<84.0,592.0>>/B<<84.0,592.0>-<98.0,666.0>-<126.5,694.5>> = 10.223427429661783 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * seven (U+0037): L<<85.0,709.0>--<84.0,592.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[11] Kalnia-LightExtended.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/ttf/Kalnia-LightExtended.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: TYPOGRAPHIC_SUBFAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/typographicsubfamilyname">com.google.fonts/check/name/typographicsubfamilyname</a>)</summary><div>


* 🔥 **FAIL** TYPOGRAPHIC_SUBFAMILY_NAME for Win "Light Extended" is incorrect. It must be "Light". [code: bad-typo-win]
</div></details><details><summary>🔥 <b>FAIL:</b> Name table records must not have trailing spaces. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/name/trailing_spaces">com.google.fonts/check/name/trailing_spaces</a>)</summary><div>


* 🔥 **FAIL** Name table record with key = (3, 1, 1033, 10) has trailing spaces that must be removed: 'Kalnia is [...]dth axes. ' [code: trailing-space]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Description strings in the name table must not exceed 200 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/description_max_length">com.google.fonts/check/name/description_max_length</a>)</summary><div>


* ⚠ **WARN** A few name table entries with ID=10 (NameID.DESCRIPTION) are longer than 200 characters. Please check whether those entries are copyright notices mistakenly stored in the description string entries by a bug in an old FontLab version. If that's the case, then such copyright notices must be removed from these entries. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:
	- f + b
	- b + f
	- f + h
	- h + i
	- i + j
	- j + k
	- k + l

   [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Kalnia Light Extended' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: NULL	Contours detected: 3	Expected: 0
	- Glyph name: uni00AD	Contours detected: 1	Expected: 0
	- Glyph name: NULL	Contours detected: 3	Expected: 0
	- Glyph name: fi	Contours detected: 1	Expected: 3
	- Glyph name: fl	Contours detected: 1	Expected: 2 
	- And Glyph name: uni00AD	Contours detected: 1	Expected: 0
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * B (U+0042): L<<316.0,376.0>--<572.0,378.0>>
 * B (U+0042): L<<572.0,363.0>--<316.0,365.0>> and four (U+0034): L<<839.0,203.0>--<997.0,204.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[13] Kalnia-BoldExtended.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/ttf/Kalnia-BoldExtended.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: TYPOGRAPHIC_SUBFAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/typographicsubfamilyname">com.google.fonts/check/name/typographicsubfamilyname</a>)</summary><div>


* 🔥 **FAIL** TYPOGRAPHIC_SUBFAMILY_NAME entry for Win "Bold Extended" must be "Bold". Please note, since the font style is RIBBI, this record can be safely deleted. [code: bad-win-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Name table records must not have trailing spaces. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/name/trailing_spaces">com.google.fonts/check/name/trailing_spaces</a>)</summary><div>


* 🔥 **FAIL** Name table record with key = (3, 1, 1033, 10) has trailing spaces that must be removed: 'Kalnia is [...]dth axes. ' [code: trailing-space]
</div></details><details><summary>🔥 <b>FAIL:</b> Does full font name begin with the font family name? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/name.html#com.google.fonts/check/name/match_familyname_fullfont">com.google.fonts/check/name/match_familyname_fullfont</a>)</summary><div>


* 🔥 **FAIL** On the 'name' table, the full font name (NameID 4 - FULL_FONT_NAME: 'Kalnia Extended') does not begin with font family name (NameID 1 - FONT_FAMILY_NAME: 'Kalnia Bold Extended') [code: does-not]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Description strings in the name table must not exceed 200 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/description_max_length">com.google.fonts/check/name/description_max_length</a>)</summary><div>


* ⚠ **WARN** A few name table entries with ID=10 (NameID.DESCRIPTION) are longer than 200 characters. Please check whether those entries are copyright notices mistakenly stored in the description string entries by a bug in an old FontLab version. If that's the case, then such copyright notices must be removed from these entries. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:
	- f + b
	- b + f
	- f + h
	- h + i
	- i + j
	- j + k
	- k + l

   [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: NULL	Contours detected: 3	Expected: 0
	- Glyph name: uni00AD	Contours detected: 1	Expected: 0
	- Glyph name: NULL	Contours detected: 3	Expected: 0
	- Glyph name: fi	Contours detected: 1	Expected: 3
	- Glyph name: fl	Contours detected: 1	Expected: 2 
	- And Glyph name: uni00AD	Contours detected: 1	Expected: 0
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* exclam (U+0021): X=482.0,Y=-0.5 (should be at baseline 0?)
	* exclam (U+0021): X=214.5,Y=-0.5 (should be at baseline 0?)
	* dollar (U+0024): X=638.0,Y=1.0 (should be at baseline 0?)
	* dollar (U+0024): X=566.0,Y=709.0 (should be at cap-height 708?)
	* ampersand (U+0026): X=855.5,Y=709.5 (should be at cap-height 708?)
	* parenleft (U+0028): X=361.0,Y=708.5 (should be at cap-height 708?)
	* parenright (U+0029): X=559.0,Y=708.5 (should be at cap-height 708?)
	* comma (U+002C): X=157.5,Y=-0.5 (should be at baseline 0?)
	* period (U+002E): X=425.0,Y=-0.5 (should be at baseline 0?)
	* period (U+002E): X=157.5,Y=-0.5 (should be at baseline 0?) and 71 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* fi (U+FB01): L<<580.0,500.0>--<697.0,495.0>> -> L<<697.0,495.0>--<1318.0,515.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * AE (U+00C6): L<<1188.0,15.0>--<1343.0,16.0>>
 * AE (U+00C6): L<<1343.0,692.0>--<1188.0,693.0>>
 * E (U+0045): L<<590.0,15.0>--<745.0,16.0>>
 * E (U+0045): L<<745.0,692.0>--<590.0,693.0>>
 * Eacute (U+00C9): L<<590.0,15.0>--<745.0,16.0>>
 * Eacute (U+00C9): L<<745.0,692.0>--<590.0,693.0>>
 * Ecircumflex (U+00CA): L<<590.0,15.0>--<745.0,16.0>>
 * Ecircumflex (U+00CA): L<<745.0,692.0>--<590.0,693.0>>
 * Edieresis (U+00CB): L<<590.0,15.0>--<745.0,16.0>>
 * Edieresis (U+00CB): L<<745.0,692.0>--<590.0,693.0>> and 9 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[10] Kalnia-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Name table records must not have trailing spaces. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/name/trailing_spaces">com.google.fonts/check/name/trailing_spaces</a>)</summary><div>


* 🔥 **FAIL** Name table record with key = (3, 1, 1033, 10) has trailing spaces that must be removed: 'Kalnia is [...]dth axes. ' [code: trailing-space]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Description strings in the name table must not exceed 200 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/description_max_length">com.google.fonts/check/name/description_max_length</a>)</summary><div>


* ⚠ **WARN** A few name table entries with ID=10 (NameID.DESCRIPTION) are longer than 200 characters. Please check whether those entries are copyright notices mistakenly stored in the description string entries by a bug in an old FontLab version. If that's the case, then such copyright notices must be removed from these entries. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:
	- f + b
	- b + f
	- f + h
	- h + i
	- i + j
	- j + k
	- k + l

   [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: NULL	Contours detected: 3	Expected: 0
	- Glyph name: uni00AD	Contours detected: 1	Expected: 0
	- Glyph name: NULL	Contours detected: 3	Expected: 0
	- Glyph name: fi	Contours detected: 1	Expected: 3
	- Glyph name: fl	Contours detected: 1	Expected: 2 
	- And Glyph name: uni00AD	Contours detected: 1	Expected: 0
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* cent (U+00A2): L<<315.0,53.0>--<324.0,53.0>> -> L<<324.0,53.0>--<324.0,53.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* seven (U+0037): L<<78.0,709.0>--<76.0,585.0>>/B<<76.0,585.0>-<91.0,659.0>-<126.5,691.0>> = 10.534706993104438 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * AE (U+00C6): L<<856.0,97.0>--<857.0,253.0>>
 * C (U+0043): L<<592.0,379.0>--<593.0,522.0>>
 * Ccedilla (U+00C7): L<<592.0,379.0>--<593.0,522.0>>
 * E (U+0045): L<<558.0,97.0>--<559.0,253.0>>
 * Eacute (U+00C9): L<<558.0,97.0>--<559.0,253.0>>
 * Ecircumflex (U+00CA): L<<558.0,97.0>--<559.0,253.0>>
 * Edieresis (U+00CB): L<<558.0,97.0>--<559.0,253.0>>
 * Egrave (U+00C8): L<<558.0,97.0>--<559.0,253.0>>
 * M (U+004D): L<<751.0,24.0>--<752.0,606.0>>
 * Y (U+0059): L<<370.0,307.0>--<371.0,25.0>> and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[12] Kalnia-ThinExtended.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/ttf/Kalnia-ThinExtended.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: TYPOGRAPHIC_SUBFAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/typographicsubfamilyname">com.google.fonts/check/name/typographicsubfamilyname</a>)</summary><div>


* 🔥 **FAIL** TYPOGRAPHIC_SUBFAMILY_NAME for Win "Thin Extended" is incorrect. It must be "Thin". [code: bad-typo-win]
</div></details><details><summary>🔥 <b>FAIL:</b> Name table records must not have trailing spaces. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/name/trailing_spaces">com.google.fonts/check/name/trailing_spaces</a>)</summary><div>


* 🔥 **FAIL** Name table record with key = (3, 1, 1033, 10) has trailing spaces that must be removed: 'Kalnia is [...]dth axes. ' [code: trailing-space]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Description strings in the name table must not exceed 200 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/description_max_length">com.google.fonts/check/name/description_max_length</a>)</summary><div>


* ⚠ **WARN** A few name table entries with ID=10 (NameID.DESCRIPTION) are longer than 200 characters. Please check whether those entries are copyright notices mistakenly stored in the description string entries by a bug in an old FontLab version. If that's the case, then such copyright notices must be removed from these entries. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:
	- f + b
	- b + f
	- f + h
	- h + i
	- i + j
	- j + k
	- k + l

   [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: NULL	Contours detected: 3	Expected: 0
	- Glyph name: uni00AD	Contours detected: 1	Expected: 0
	- Glyph name: NULL	Contours detected: 3	Expected: 0
	- Glyph name: fi	Contours detected: 1	Expected: 3
	- Glyph name: fl	Contours detected: 1	Expected: 2 
	- And Glyph name: uni00AD	Contours detected: 1	Expected: 0
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* percent (U+0025): X=294.0,Y=709.0 (should be at cap-height 708?)
	* ampersand (U+0026): X=209.5,Y=2.0 (should be at baseline 0?)
	* ampersand (U+0026): X=1071.0,Y=2.0 (should be at baseline 0?)
	* ampersand (U+0026): X=950.0,Y=1.5 (should be at baseline 0?)
	* ampersand (U+0026): X=495.5,Y=-0.5 (should be at baseline 0?)
	* ampersand (U+0026): X=518.0,Y=707.0 (should be at cap-height 708?)
	* parenleft (U+0028): X=264.5,Y=-0.5 (should be at baseline 0?)
	* parenright (U+0029): X=294.5,Y=-0.5 (should be at baseline 0?)
	* zero (U+0030): X=557.0,Y=1.0 (should be at baseline 0?)
	* zero (U+0030): X=557.0,Y=707.0 (should be at cap-height 708?) and 89 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* four (U+0034): L<<720.0,204.0>--<720.0,546.0>> -> L<<720.0,546.0>--<725.0,724.0>>
	* onequarter (U+00BC): L<<566.0,93.0>--<566.0,230.0>> -> L<<566.0,230.0>--<567.0,302.0>>
	* threequarters (U+00BE): L<<697.0,93.0>--<697.0,230.0>> -> L<<697.0,230.0>--<698.0,302.0>> and uni2074 (U+2074): L<<293.0,509.0>--<293.0,646.0>> -> L<<293.0,646.0>--<294.0,718.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * H (U+0048): L<<225.0,342.0>--<945.0,348.0>>
 * ae (U+00E6): L<<785.0,286.0>--<1545.0,290.0>>
 * e (U+0065): L<<83.0,286.0>--<843.0,290.0>>
 * eacute (U+00E9): L<<83.0,286.0>--<843.0,290.0>>
 * ecircumflex (U+00EA): L<<83.0,286.0>--<843.0,290.0>>
 * edieresis (U+00EB): L<<83.0,286.0>--<843.0,290.0>>
 * egrave (U+00E8): L<<83.0,286.0>--<843.0,290.0>>
 * four (U+0034): L<<735.0,204.0>--<910.0,205.0>>
 * four (U+0034): L<<84.0,200.0>--<720.0,204.0>>
 * oe (U+0153): L<<946.0,284.0>--<1704.0,288.0>> and seven (U+0037): L<<106.0,709.0>--<105.0,592.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[11] Kalnia-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Name table records must not have trailing spaces. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/name/trailing_spaces">com.google.fonts/check/name/trailing_spaces</a>)</summary><div>


* 🔥 **FAIL** Name table record with key = (3, 1, 1033, 10) has trailing spaces that must be removed: 'Kalnia is [...]dth axes. ' [code: trailing-space]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Description strings in the name table must not exceed 200 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/description_max_length">com.google.fonts/check/name/description_max_length</a>)</summary><div>


* ⚠ **WARN** A few name table entries with ID=10 (NameID.DESCRIPTION) are longer than 200 characters. Please check whether those entries are copyright notices mistakenly stored in the description string entries by a bug in an old FontLab version. If that's the case, then such copyright notices must be removed from these entries. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:
	- f + b
	- b + f
	- f + h
	- h + i
	- i + j
	- j + k
	- k + l

   [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: NULL	Contours detected: 3	Expected: 0
	- Glyph name: uni00AD	Contours detected: 1	Expected: 0
	- Glyph name: AE	Contours detected: 1	Expected: 2
	- Glyph name: AE	Contours detected: 1	Expected: 2
	- Glyph name: NULL	Contours detected: 3	Expected: 0
	- Glyph name: fi	Contours detected: 1	Expected: 3
	- Glyph name: fl	Contours detected: 1	Expected: 2 
	- And Glyph name: uni00AD	Contours detected: 1	Expected: 0
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* two (U+0032): X=336.0,Y=1.5 (should be at baseline 0?)
	* three (U+0033): X=262.0,Y=2.0 (should be at baseline 0?)
	* three (U+0033): X=264.0,Y=707.0 (should be at cap-height 708?)
	* six (U+0036): X=394.0,Y=706.0 (should be at cap-height 708?)
	* seven (U+0037): X=583.5,Y=706.0 (should be at cap-height 708?)
	* nine (U+0039): X=261.0,Y=2.0 (should be at baseline 0?)
	* C (U+0043): X=380.0,Y=710.0 (should be at cap-height 708?)
	* G (U+0047): X=376.0,Y=710.0 (should be at cap-height 708?)
	* J (U+004A): X=186.0,Y=1.0 (should be at baseline 0?)
	* O (U+004F): X=388.0,Y=710.0 (should be at cap-height 708?) and 43 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* W (U+0057): L<<573.0,445.0>--<573.0,445.0>> -> L<<573.0,445.0>--<573.0,445.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* seven (U+0037): L<<68.0,708.0>--<65.0,575.0>>/B<<65.0,575.0>-<99.0,723.0>-<247.0,723.0>> = 11.64588943093649 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * AE (U+00C6): L<<576.0,15.0>--<776.0,16.0>>
 * AE (U+00C6): L<<768.0,692.0>--<576.0,693.0>>
 * E (U+0045): L<<249.0,15.0>--<449.0,16.0>>
 * E (U+0045): L<<441.0,692.0>--<249.0,693.0>>
 * Eacute (U+00C9): L<<249.0,15.0>--<449.0,16.0>>
 * Eacute (U+00C9): L<<441.0,692.0>--<249.0,693.0>>
 * Ecircumflex (U+00CA): L<<249.0,15.0>--<449.0,16.0>>
 * Ecircumflex (U+00CA): L<<441.0,692.0>--<249.0,693.0>>
 * Edieresis (U+00CB): L<<249.0,15.0>--<449.0,16.0>>
 * Edieresis (U+00CB): L<<441.0,692.0>--<249.0,693.0>> and 17 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[10] Kalnia-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Name table records must not have trailing spaces. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/name/trailing_spaces">com.google.fonts/check/name/trailing_spaces</a>)</summary><div>


* 🔥 **FAIL** Name table record with key = (3, 1, 1033, 10) has trailing spaces that must be removed: 'Kalnia is [...]dth axes. ' [code: trailing-space]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Description strings in the name table must not exceed 200 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/description_max_length">com.google.fonts/check/name/description_max_length</a>)</summary><div>


* ⚠ **WARN** A few name table entries with ID=10 (NameID.DESCRIPTION) are longer than 200 characters. Please check whether those entries are copyright notices mistakenly stored in the description string entries by a bug in an old FontLab version. If that's the case, then such copyright notices must be removed from these entries. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:
	- f + b
	- b + f
	- f + h
	- h + i
	- i + j
	- j + k
	- k + l

   [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: NULL	Contours detected: 3	Expected: 0
	- Glyph name: uni00AD	Contours detected: 1	Expected: 0
	- Glyph name: NULL	Contours detected: 3	Expected: 0
	- Glyph name: fi	Contours detected: 1	Expected: 3
	- Glyph name: fl	Contours detected: 1	Expected: 2 
	- And Glyph name: uni00AD	Contours detected: 1	Expected: 0
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* dollar (U+0024): X=168.5,Y=2.0 (should be at baseline 0?)
	* dollar (U+0024): X=469.5,Y=2.0 (should be at baseline 0?)
	* three (U+0033): X=238.0,Y=706.0 (should be at cap-height 708?)
	* G (U+0047): X=516.5,Y=-1.0 (should be at baseline 0?)
	* J (U+004A): X=191.0,Y=1.0 (should be at baseline 0?)
	* a (U+0061): X=218.5,Y=502.0 (should be at x-height 500?)
	* b (U+0062): X=420.0,Y=502.0 (should be at x-height 500?)
	* b (U+0062): X=470.0,Y=-0.5 (should be at baseline 0?)
	* b (U+0062): X=264.0,Y=2.0 (should be at baseline 0?)
	* c (U+0063): X=462.0,Y=499.5 (should be at x-height 500?) and 51 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* seven (U+0037): L<<55.0,708.0>--<50.0,562.0>>/B<<50.0,562.0>-<70.0,639.0>-<128.0,681.0>> = 12.598857951586536 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * M (U+004D): L<<677.0,20.0>--<678.0,592.0>>
 * Y (U+0059): L<<515.0,319.0>--<516.0,25.0>>
 * Yacute (U+00DD): L<<515.0,319.0>--<516.0,25.0>>
 * Ydieresis (U+0178): L<<515.0,319.0>--<516.0,25.0>>
 * k (U+006B): L<<423.0,305.0>--<552.0,306.0>>
 * trademark (U+2122): L<<611.0,436.0>--<612.0,661.0>>
 * u (U+0075): L<<286.0,515.0>--<287.0,126.0>>
 * u (U+0075): L<<631.0,515.0>--<632.0,36.0>>
 * uacute (U+00FA): L<<286.0,515.0>--<287.0,126.0>>
 * uacute (U+00FA): L<<631.0,515.0>--<632.0,36.0>> and 7 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 18 | 73 | 875 | 49 | 673 | 0 |
| 0% | 1% | 4% | 52% | 3% | 40% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
