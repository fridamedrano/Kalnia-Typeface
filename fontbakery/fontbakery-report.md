## FontBakery report

fontbakery version: 0.9.2

<details><summary><b>[10] Kalnia-Medium.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.1 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, tifinagh, yi
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, math, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, math, canadian-aboriginal, coptic, malayalam, tifinagh, syriac, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+03BC GREEK SMALL LETTER MU: try adding one of: math, greek
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+2030 PER MILLE SIGN: try adding adlam
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25CC DOTTED CIRCLE: try adding one of: gunjala-gondi, symbols, sharada, syriac, marchen, kannada, bassa-vah, limbu, wancho, mongolian, takri, thaana, balinese, masaram-gondi, lao, batak, kaithi, malayalam, tirhuta, khmer, dogra, miao, hebrew, tagalog, duployan, mende-kikakui, modi, bhaiksuki, old-permic, elbasan, mahajani, lepcha, tifinagh, new-tai-lue, mandaic, music, oriya, yi, siddham, tibetan, caucasian-albanian, brahmi, math, tamil, zanabazar-square, chakma, myanmar, hanifi-rohingya, cham, pahawh-hmong, manichaean, rejang, coptic, tagbanwa, hanunoo, grantha, meetei-mayek, buhid, kayah-li, javanese, tai-viet, psalter-pahlavi, sinhala, devanagari, sundanese, khojki, ahom, osage, syloti-nagri, nko, phags-pa, kharoshthi, gujarati, gurmukhi, newa, adlam, sogdian, khudawadi, tai-le, telugu, buginese, bengali, soyombo, thai
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + b

	- b + f

	- f + h

	- h + i

	- i + j

	- j + k

	- k + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: AE	Contours detected: 1	Expected: 2

	- Glyph name: multiply	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: AE	Contours detected: 1	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: multiply	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=481.5,Y=710.0 (should be at cap-height 708?)

	* two (U+0032): X=336.0,Y=1.5 (should be at baseline 0?)

	* six (U+0036): X=395.0,Y=706.0 (should be at cap-height 708?)

	* seven (U+0037): X=584.0,Y=706.0 (should be at cap-height 708?)

	* nine (U+0039): X=252.0,Y=2.0 (should be at baseline 0?)

	* C (U+0043): X=380.0,Y=710.0 (should be at cap-height 708?)

	* G (U+0047): X=376.0,Y=710.0 (should be at cap-height 708?)

	* O (U+004F): X=389.0,Y=-2.0 (should be at baseline 0?)

	* Q (U+0051): X=389.0,Y=-2.0 (should be at baseline 0?)

	* b (U+0062): X=33.0,Y=709.0 (should be at cap-height 708?)

	* d (U+0064): X=344.0,Y=499.0 (should be at x-height 500?)

	* h (U+0068): X=31.0,Y=709.0 (should be at cap-height 708?)

	* i (U+0069): X=83.0,Y=707.0 (should be at cap-height 708?)

	* i (U+0069): X=228.0,Y=707.0 (should be at cap-height 708?)

	* k (U+006B): X=31.0,Y=709.0 (should be at cap-height 708?)

	* l (U+006C): X=31.0,Y=709.0 (should be at cap-height 708?)

	* p (U+0070): X=321.5,Y=1.0 (should be at baseline 0?)

	* t (U+0074): X=266.0,Y=2.0 (should be at baseline 0?)

	* ordfeminine (U+00AA): X=168.0,Y=707.0 (should be at cap-height 708?)

	* uni00B5 (U+00B5): X=38.0,Y=1.0 (should be at baseline 0?)

	* onehalf (U+00BD): X=403.5,Y=-1.0 (should be at baseline 0?)

	* Ccedilla (U+00C7): X=380.0,Y=710.0 (should be at cap-height 708?)

	* Ograve (U+00D2): X=389.0,Y=-2.0 (should be at baseline 0?)

	* Oacute (U+00D3): X=389.0,Y=-2.0 (should be at baseline 0?)

	* Ocircumflex (U+00D4): X=389.0,Y=-2.0 (should be at baseline 0?)

	* Otilde (U+00D5): X=389.0,Y=-2.0 (should be at baseline 0?)

	* Odieresis (U+00D6): X=389.0,Y=-2.0 (should be at baseline 0?)

	* Oslash (U+00D8): X=287.0,Y=-2.0 (should be at baseline 0?)

	* Oslash (U+00D8): X=389.0,Y=-2.0 (should be at baseline 0?)

	* oslash (U+00F8): X=202.0,Y=1.0 (should be at baseline 0?)

	* thorn (U+00FE): X=321.5,Y=1.0 (should be at baseline 0?)

	* Cacute (U+0106): X=380.0,Y=710.0 (should be at cap-height 708?)

	* Cdotaccent (U+010A): X=380.0,Y=710.0 (should be at cap-height 708?)

	* Ccaron (U+010C): X=380.0,Y=710.0 (should be at cap-height 708?)

	* Gbreve (U+011E): X=376.0,Y=710.0 (should be at cap-height 708?)

	* Gdotaccent (U+0120): X=376.0,Y=710.0 (should be at cap-height 708?)

	* uni0122 (U+0122): X=376.0,Y=710.0 (should be at cap-height 708?)

	* hbar (U+0127): X=31.0,Y=709.0 (should be at cap-height 708?)

	* iogonek (U+012F): X=83.0,Y=707.0 (should be at cap-height 708?)

	* iogonek (U+012F): X=228.0,Y=707.0 (should be at cap-height 708?)

	* ij (U+0133): X=83.0,Y=707.0 (should be at cap-height 708?)

	* ij (U+0133): X=228.0,Y=707.0 (should be at cap-height 708?)

	* uni0137 (U+0137): X=31.0,Y=709.0 (should be at cap-height 708?)

	* lacute (U+013A): X=31.0,Y=709.0 (should be at cap-height 708?)

	* uni013C (U+013C): X=31.0,Y=709.0 (should be at cap-height 708?)

	* lcaron (U+013E): X=31.0,Y=709.0 (should be at cap-height 708?)

	* ldot (U+0140): X=31.0,Y=709.0 (should be at cap-height 708?)

	* lslash (U+0142): X=31.0,Y=709.0 (should be at cap-height 708?)

	* Omacron (U+014C): X=389.0,Y=-2.0 (should be at baseline 0?)

	* Ohungarumlaut (U+0150): X=389.0,Y=-2.0 (should be at baseline 0?)

	* tcaron (U+0165): X=266.0,Y=2.0 (should be at baseline 0?)

	* uni021B (U+021B): X=266.0,Y=2.0 (should be at baseline 0?)

	* uni03BC (U+03BC): X=38.0,Y=1.0 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=476.0,Y=2.0 (should be at baseline 0?)

	* daggerdbl (U+2021): X=280.0,Y=1.5 (should be at baseline 0?)

	* daggerdbl (U+2021): X=192.0,Y=1.5 (should be at baseline 0?)

	* Euro (U+20AC): X=454.0,Y=710.0 (should be at cap-height 708?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* seven (U+0037): L<<65.0,708.0>--<65.0,575.0>>/B<<65.0,575.0>-<99.0,723.0>-<248.0,723.0>> = 12.938056317186438 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[9] Kalnia-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.1 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, tifinagh, yi
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, math, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, math, canadian-aboriginal, coptic, malayalam, tifinagh, syriac, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+03BC GREEK SMALL LETTER MU: try adding one of: math, greek
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+2030 PER MILLE SIGN: try adding adlam
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25CC DOTTED CIRCLE: try adding one of: gunjala-gondi, symbols, sharada, syriac, marchen, kannada, bassa-vah, limbu, wancho, mongolian, takri, thaana, balinese, masaram-gondi, lao, batak, kaithi, malayalam, tirhuta, khmer, dogra, miao, hebrew, tagalog, duployan, mende-kikakui, modi, bhaiksuki, old-permic, elbasan, mahajani, lepcha, tifinagh, new-tai-lue, mandaic, music, oriya, yi, siddham, tibetan, caucasian-albanian, brahmi, math, tamil, zanabazar-square, chakma, myanmar, hanifi-rohingya, cham, pahawh-hmong, manichaean, rejang, coptic, tagbanwa, hanunoo, grantha, meetei-mayek, buhid, kayah-li, javanese, tai-viet, psalter-pahlavi, sinhala, devanagari, sundanese, khojki, ahom, osage, syloti-nagri, nko, phags-pa, kharoshthi, gujarati, gurmukhi, newa, adlam, sogdian, khudawadi, tai-le, telugu, buginese, bengali, soyombo, thai
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + b

	- b + f

	- f + h

	- h + i

	- i + j

	- j + k

	- k + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: multiply	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: multiply	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* seven (U+0037): L<<69.0,708.0>--<69.0,579.0>>/B<<69.0,579.0>-<86.0,654.0>-<127.0,688.5>> = 12.771242564901412 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[9] Kalnia-Light.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.1 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, tifinagh, yi
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, math, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, math, canadian-aboriginal, coptic, malayalam, tifinagh, syriac, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+03BC GREEK SMALL LETTER MU: try adding one of: math, greek
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+2030 PER MILLE SIGN: try adding adlam
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25CC DOTTED CIRCLE: try adding one of: gunjala-gondi, symbols, sharada, syriac, marchen, kannada, bassa-vah, limbu, wancho, mongolian, takri, thaana, balinese, masaram-gondi, lao, batak, kaithi, malayalam, tirhuta, khmer, dogra, miao, hebrew, tagalog, duployan, mende-kikakui, modi, bhaiksuki, old-permic, elbasan, mahajani, lepcha, tifinagh, new-tai-lue, mandaic, music, oriya, yi, siddham, tibetan, caucasian-albanian, brahmi, math, tamil, zanabazar-square, chakma, myanmar, hanifi-rohingya, cham, pahawh-hmong, manichaean, rejang, coptic, tagbanwa, hanunoo, grantha, meetei-mayek, buhid, kayah-li, javanese, tai-viet, psalter-pahlavi, sinhala, devanagari, sundanese, khojki, ahom, osage, syloti-nagri, nko, phags-pa, kharoshthi, gujarati, gurmukhi, newa, adlam, sogdian, khudawadi, tai-le, telugu, buginese, bengali, soyombo, thai
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + b

	- b + f

	- f + h

	- h + i

	- i + j

	- j + k

	- k + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: multiply	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: multiply	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* seven (U+0037): L<<77.0,708.0>--<77.0,586.0>>/B<<77.0,586.0>-<92.0,660.0>-<126.5,691.5>> = 11.458752345877198 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[9] Kalnia-SemiBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.1 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, tifinagh, yi
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, math, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, math, canadian-aboriginal, coptic, malayalam, tifinagh, syriac, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+03BC GREEK SMALL LETTER MU: try adding one of: math, greek
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+2030 PER MILLE SIGN: try adding adlam
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25CC DOTTED CIRCLE: try adding one of: gunjala-gondi, symbols, sharada, syriac, marchen, kannada, bassa-vah, limbu, wancho, mongolian, takri, thaana, balinese, masaram-gondi, lao, batak, kaithi, malayalam, tirhuta, khmer, dogra, miao, hebrew, tagalog, duployan, mende-kikakui, modi, bhaiksuki, old-permic, elbasan, mahajani, lepcha, tifinagh, new-tai-lue, mandaic, music, oriya, yi, siddham, tibetan, caucasian-albanian, brahmi, math, tamil, zanabazar-square, chakma, myanmar, hanifi-rohingya, cham, pahawh-hmong, manichaean, rejang, coptic, tagbanwa, hanunoo, grantha, meetei-mayek, buhid, kayah-li, javanese, tai-viet, psalter-pahlavi, sinhala, devanagari, sundanese, khojki, ahom, osage, syloti-nagri, nko, phags-pa, kharoshthi, gujarati, gurmukhi, newa, adlam, sogdian, khudawadi, tai-le, telugu, buginese, bengali, soyombo, thai
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + b

	- b + f

	- f + h

	- h + i

	- i + j

	- j + k

	- k + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: multiply	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: multiply	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* seven (U+0037): L<<57.0,708.0>--<57.0,568.0>>/B<<57.0,568.0>-<95.0,723.0>-<262.0,723.0>> = 13.77501831967461 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[9] Kalnia-ExtraLight.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.1 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, tifinagh, yi
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, math, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, math, canadian-aboriginal, coptic, malayalam, tifinagh, syriac, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+03BC GREEK SMALL LETTER MU: try adding one of: math, greek
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+2030 PER MILLE SIGN: try adding adlam
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25CC DOTTED CIRCLE: try adding one of: gunjala-gondi, symbols, sharada, syriac, marchen, kannada, bassa-vah, limbu, wancho, mongolian, takri, thaana, balinese, masaram-gondi, lao, batak, kaithi, malayalam, tirhuta, khmer, dogra, miao, hebrew, tagalog, duployan, mende-kikakui, modi, bhaiksuki, old-permic, elbasan, mahajani, lepcha, tifinagh, new-tai-lue, mandaic, music, oriya, yi, siddham, tibetan, caucasian-albanian, brahmi, math, tamil, zanabazar-square, chakma, myanmar, hanifi-rohingya, cham, pahawh-hmong, manichaean, rejang, coptic, tagbanwa, hanunoo, grantha, meetei-mayek, buhid, kayah-li, javanese, tai-viet, psalter-pahlavi, sinhala, devanagari, sundanese, khojki, ahom, osage, syloti-nagri, nko, phags-pa, kharoshthi, gujarati, gurmukhi, newa, adlam, sogdian, khudawadi, tai-le, telugu, buginese, bengali, soyombo, thai
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + b

	- b + f

	- f + h

	- h + i

	- i + j

	- j + k

	- k + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: multiply	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: multiply	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* seven (U+0037): L<<80.0,708.0>--<80.0,588.0>>/B<<80.0,588.0>-<94.0,662.0>-<126.0,692.5>> = 10.713123022791033 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[11] Kalnia-Thin.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.1 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, tifinagh, yi
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, math, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, math, canadian-aboriginal, coptic, malayalam, tifinagh, syriac, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+03BC GREEK SMALL LETTER MU: try adding one of: math, greek
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+2030 PER MILLE SIGN: try adding adlam
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25CC DOTTED CIRCLE: try adding one of: gunjala-gondi, symbols, sharada, syriac, marchen, kannada, bassa-vah, limbu, wancho, mongolian, takri, thaana, balinese, masaram-gondi, lao, batak, kaithi, malayalam, tirhuta, khmer, dogra, miao, hebrew, tagalog, duployan, mende-kikakui, modi, bhaiksuki, old-permic, elbasan, mahajani, lepcha, tifinagh, new-tai-lue, mandaic, music, oriya, yi, siddham, tibetan, caucasian-albanian, brahmi, math, tamil, zanabazar-square, chakma, myanmar, hanifi-rohingya, cham, pahawh-hmong, manichaean, rejang, coptic, tagbanwa, hanunoo, grantha, meetei-mayek, buhid, kayah-li, javanese, tai-viet, psalter-pahlavi, sinhala, devanagari, sundanese, khojki, ahom, osage, syloti-nagri, nko, phags-pa, kharoshthi, gujarati, gurmukhi, newa, adlam, sogdian, khudawadi, tai-le, telugu, buginese, bengali, soyombo, thai
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + b

	- b + f

	- f + h

	- h + i

	- i + j

	- j + k

	- k + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: multiply	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: multiply	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=641.0,Y=1.5 (should be at baseline 0?)

	* comma (U+002C): X=68.0,Y=-2.0 (should be at baseline 0?)

	* two (U+0032): X=87.5,Y=-2.0 (should be at baseline 0?)

	* two (U+0032): X=202.0,Y=706.0 (should be at cap-height 708?)

	* three (U+0033): X=192.0,Y=2.0 (should be at baseline 0?)

	* three (U+0033): X=195.0,Y=706.0 (should be at cap-height 708?)

	* five (U+0035): X=207.0,Y=2.0 (should be at baseline 0?)

	* seven (U+0037): X=544.5,Y=706.0 (should be at cap-height 708?)

	* semicolon (U+003B): X=68.0,Y=-2.0 (should be at baseline 0?)

	* G (U+0047): X=511.0,Y=2.0 (should be at baseline 0?)

	* grave (U+0060): X=50.0,Y=710.0 (should be at cap-height 708?)

	* f (U+0066): X=245.0,Y=709.0 (should be at cap-height 708?)

	* k (U+006B): X=298.5,Y=500.5 (should be at x-height 500?)

	* k (U+006B): X=386.0,Y=501.5 (should be at x-height 500?)

	* r (U+0072): X=266.5,Y=501.0 (should be at x-height 500?)

	* r (U+0072): X=361.5,Y=500.5 (should be at x-height 500?)

	* x (U+0078): X=71.0,Y=1.5 (should be at baseline 0?)

	* x (U+0078): X=568.0,Y=499.0 (should be at x-height 500?)

	* ordfeminine (U+00AA): X=177.0,Y=710.0 (should be at cap-height 708?)

	* uni00B2 (U+00B2): X=146.0,Y=710.0 (should be at cap-height 708?)

	* uni00B3 (U+00B3): X=145.0,Y=710.0 (should be at cap-height 708?)

	* acute (U+00B4): X=210.0,Y=710.0 (should be at cap-height 708?)

	* onehalf (U+00BD): X=421.0,Y=-2.0 (should be at baseline 0?)

	* onehalf (U+00BD): X=324.0,Y=-1.0 (should be at baseline 0?)

	* threequarters (U+00BE): X=155.0,Y=710.0 (should be at cap-height 708?)

	* germandbls (U+00DF): X=431.0,Y=710.0 (should be at cap-height 708?)

	* agrave (U+00E0): X=186.0,Y=710.0 (should be at cap-height 708?)

	* aacute (U+00E1): X=421.0,Y=710.0 (should be at cap-height 708?)

	* egrave (U+00E8): X=188.0,Y=710.0 (should be at cap-height 708?)

	* eacute (U+00E9): X=423.0,Y=710.0 (should be at cap-height 708?)

	* igrave (U+00EC): X=17.0,Y=710.0 (should be at cap-height 708?)

	* iacute (U+00ED): X=252.0,Y=710.0 (should be at cap-height 708?)

	* ograve (U+00F2): X=186.0,Y=710.0 (should be at cap-height 708?)

	* oacute (U+00F3): X=421.0,Y=710.0 (should be at cap-height 708?)

	* ugrave (U+00F9): X=205.0,Y=710.0 (should be at cap-height 708?)

	* uacute (U+00FA): X=440.0,Y=710.0 (should be at cap-height 708?)

	* yacute (U+00FD): X=405.0,Y=710.0 (should be at cap-height 708?)

	* cacute (U+0107): X=435.0,Y=710.0 (should be at cap-height 708?)

	* Gbreve (U+011E): X=511.0,Y=2.0 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=511.0,Y=2.0 (should be at baseline 0?)

	* uni0122 (U+0122): X=511.0,Y=2.0 (should be at baseline 0?)

	* nacute (U+0144): X=460.0,Y=710.0 (should be at cap-height 708?)

	* ohungarumlaut (U+0151): X=526.0,Y=710.0 (should be at cap-height 708?)

	* ohungarumlaut (U+0151): X=406.0,Y=710.0 (should be at cap-height 708?)

	* racute (U+0155): X=344.0,Y=710.0 (should be at cap-height 708?)

	* sacute (U+015B): X=378.0,Y=710.0 (should be at cap-height 708?)

	* uhungarumlaut (U+0171): X=545.0,Y=710.0 (should be at cap-height 708?)

	* uhungarumlaut (U+0171): X=425.0,Y=710.0 (should be at cap-height 708?)

	* zacute (U+017A): X=407.0,Y=710.0 (should be at cap-height 708?)

	* florin (U+0192): X=378.0,Y=709.0 (should be at cap-height 708?)

	* hungarumlaut (U+02DD): X=330.0,Y=710.0 (should be at cap-height 708?)

	* hungarumlaut (U+02DD): X=210.0,Y=710.0 (should be at cap-height 708?)

	* gravecomb (U+0300): X=-110.0,Y=710.0 (should be at cap-height 708?)

	* acutecomb (U+0301): X=110.0,Y=710.0 (should be at cap-height 708?)

	* uni030B (U+030B): X=210.0,Y=710.0 (should be at cap-height 708?)

	* uni030B (U+030B): X=90.0,Y=710.0 (should be at cap-height 708?)

	* wgrave (U+1E81): X=324.0,Y=710.0 (should be at cap-height 708?)

	* wacute (U+1E83): X=559.0,Y=710.0 (should be at cap-height 708?)

	* uni1E9E (U+1E9E): X=327.5,Y=2.0 (should be at baseline 0?)

	* ygrave (U+1EF3): X=170.0,Y=710.0 (should be at cap-height 708?)

	* quotesinglbase (U+201A): X=68.0,Y=-2.0 (should be at baseline 0?)

	* quotedblbase (U+201E): X=68.0,Y=-2.0 (should be at baseline 0?)

	* quotedblbase (U+201E): X=206.0,Y=-2.0 (should be at baseline 0?)

	* uni25CC (U+25CC): X=429.0,Y=706.0 (should be at cap-height 708?)

	* uni25CC (U+25CC): X=405.0,Y=706.0 (should be at cap-height 708?)

	* uni25CC (U+25CC): X=429.0,Y=1.0 (should be at baseline 0?)

	* uni25CC (U+25CC): X=405.0,Y=1.0 (should be at baseline 0?)

	* fi (U+FB01): X=435.0,Y=709.5 (should be at cap-height 708?)

	* fl (U+FB02): X=435.5,Y=710.0 (should be at cap-height 708?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* four (U+0034): L<<410.0,204.0>--<410.0,546.0>> -> L<<410.0,546.0>--<420.0,724.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* seven (U+0037): L<<84.0,708.0>--<84.0,592.0>>/B<<84.0,592.0>-<98.0,666.0>-<126.5,694.5>> = 10.713123022791033 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[10] Kalnia-Bold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.1 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, tifinagh, yi
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, math, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, math, canadian-aboriginal, coptic, malayalam, tifinagh, syriac, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+03BC GREEK SMALL LETTER MU: try adding one of: math, greek
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+2030 PER MILLE SIGN: try adding adlam
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25CC DOTTED CIRCLE: try adding one of: gunjala-gondi, symbols, sharada, syriac, marchen, kannada, bassa-vah, limbu, wancho, mongolian, takri, thaana, balinese, masaram-gondi, lao, batak, kaithi, malayalam, tirhuta, khmer, dogra, miao, hebrew, tagalog, duployan, mende-kikakui, modi, bhaiksuki, old-permic, elbasan, mahajani, lepcha, tifinagh, new-tai-lue, mandaic, music, oriya, yi, siddham, tibetan, caucasian-albanian, brahmi, math, tamil, zanabazar-square, chakma, myanmar, hanifi-rohingya, cham, pahawh-hmong, manichaean, rejang, coptic, tagbanwa, hanunoo, grantha, meetei-mayek, buhid, kayah-li, javanese, tai-viet, psalter-pahlavi, sinhala, devanagari, sundanese, khojki, ahom, osage, syloti-nagri, nko, phags-pa, kharoshthi, gujarati, gurmukhi, newa, adlam, sogdian, khudawadi, tai-le, telugu, buginese, bengali, soyombo, thai
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + b

	- b + f

	- f + h

	- h + i

	- i + j

	- j + k

	- k + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: multiply	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: multiply	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma (U+002C): X=207.0,Y=1.5 (should be at baseline 0?)

	* five (U+0035): X=96.0,Y=710.0 (should be at cap-height 708?)

	* semicolon (U+003B): X=208.0,Y=1.5 (should be at baseline 0?)

	* G (U+0047): X=516.5,Y=-1.5 (should be at baseline 0?)

	* a (U+0061): X=218.5,Y=502.0 (should be at x-height 500?)

	* b (U+0062): X=420.0,Y=502.0 (should be at x-height 500?)

	* b (U+0062): X=470.0,Y=-0.5 (should be at baseline 0?)

	* b (U+0062): X=264.0,Y=2.0 (should be at baseline 0?)

	* c (U+0063): X=462.0,Y=499.5 (should be at x-height 500?)

	* c (U+0063): X=428.5,Y=498.5 (should be at x-height 500?)

	* d (U+0064): X=325.0,Y=498.5 (should be at x-height 500?)

	* k (U+006B): X=610.0,Y=502.0 (should be at x-height 500?)

	* p (U+0070): X=368.5,Y=1.5 (should be at baseline 0?)

	* q (U+0071): X=256.5,Y=-2.0 (should be at baseline 0?)

	* q (U+0071): X=206.0,Y=500.5 (should be at x-height 500?)

	* q (U+0071): X=411.0,Y=498.0 (should be at x-height 500?)

	* s (U+0073): X=212.0,Y=1.0 (should be at baseline 0?)

	* s (U+0073): X=308.5,Y=-0.5 (should be at baseline 0?)

	* s (U+0073): X=244.0,Y=501.5 (should be at x-height 500?)

	* braceleft (U+007B): X=151.0,Y=1.0 (should be at baseline 0?)

	* braceright (U+007D): X=446.0,Y=1.0 (should be at baseline 0?)

	* section (U+00A7): X=405.0,Y=707.5 (should be at cap-height 708?)

	* uni00B2 (U+00B2): X=125.0,Y=707.0 (should be at cap-height 708?)

	* uni00B3 (U+00B3): X=112.0,Y=706.0 (should be at cap-height 708?)

	* onehalf (U+00BD): X=425.5,Y=-1.5 (should be at baseline 0?)

	* onehalf (U+00BD): X=366.0,Y=1.0 (should be at baseline 0?)

	* threequarters (U+00BE): X=132.0,Y=706.0 (should be at cap-height 708?)

	* germandbls (U+00DF): X=534.5,Y=1.0 (should be at baseline 0?)

	* thorn (U+00FE): X=368.5,Y=1.5 (should be at baseline 0?)

	* Gbreve (U+011E): X=516.5,Y=-1.5 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=516.5,Y=-1.5 (should be at baseline 0?)

	* uni0122 (U+0122): X=516.5,Y=-1.5 (should be at baseline 0?)

	* sacute (U+015B): X=212.0,Y=1.0 (should be at baseline 0?)

	* sacute (U+015B): X=308.5,Y=-0.5 (should be at baseline 0?)

	* scedilla (U+015F): X=212.0,Y=1.0 (should be at baseline 0?)

	* scedilla (U+015F): X=308.5,Y=-0.5 (should be at baseline 0?)

	* scaron (U+0161): X=212.0,Y=1.0 (should be at baseline 0?)

	* scaron (U+0161): X=308.5,Y=-0.5 (should be at baseline 0?)

	* uni0219 (U+0219): X=212.0,Y=1.0 (should be at baseline 0?)

	* uni0219 (U+0219): X=308.5,Y=-0.5 (should be at baseline 0?)

	* uni02BB (U+02BB): X=230.0,Y=709.0 (should be at cap-height 708?)

	* quoteleft (U+2018): X=230.0,Y=709.0 (should be at cap-height 708?)

	* quotesinglbase (U+201A): X=207.0,Y=1.5 (should be at baseline 0?)

	* quotedblleft (U+201C): X=465.0,Y=709.0 (should be at cap-height 708?)

	* quotedblleft (U+201C): X=230.0,Y=709.0 (should be at cap-height 708?)

	* quotedblbase (U+201E): X=207.0,Y=1.5 (should be at baseline 0?)

	* quotedblbase (U+201E): X=423.0,Y=1.5 (should be at baseline 0?)

	* uni25CC (U+25CC): X=285.0,Y=706.0 (should be at cap-height 708?)

	* uni25CC (U+25CC): X=548.0,Y=1.0 (should be at baseline 0?)

	* uni25CC (U+25CC): X=286.0,Y=1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* ampersand (U+0026): L<<440.0,164.0>--<439.0,165.0>> -> L<<439.0,165.0>--<232.0,380.0>> [code: found-colinear-vectors]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 21 | 7 | 39 | 828 | 43 | 703 | 0 |
| 1% | 0% | 2% | 50% | 3% | 43% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
