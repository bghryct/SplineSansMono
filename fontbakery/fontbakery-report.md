## Fontbakery report

Fontbakery version: 0.8.7

<details><summary><b>[18] SplineSansMono-Medium.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check METADATA.pb includes production subsets.</summary><div>
* [com.google.fonts/check/metadata/includes_production_subsets](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/includes_production_subsets)

* 💔 **ERROR** The condition <FontBakeryCondition:production_metadata> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Version number has increased since previous release on Google Fonts?</summary><div>
* [com.google.fonts/check/version_bump](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/version_bump)

* 💔 **ERROR** The condition <FontBakeryCondition:api_gfonts_ttFont> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Glyphs are similiar to Google Fonts version?</summary><div>
* [com.google.fonts/check/production_glyphs_similarity](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity)

* 💔 **ERROR** The condition <FontBakeryCondition:api_gfonts_ttFont> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts.</summary><div>
* [com.google.fonts/check/vertical_metrics_regressions](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions)

* 💔 **ERROR** The condition <FontBakeryCondition:regular_remote_style> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Check font follows the Google Fonts CJK vertical metric schema</summary><div>
* [com.google.fonts/check/cjk_vertical_metrics](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_vertical_metrics)

* 💔 **ERROR** The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Check if the vertical metrics of a CJK family are similar to the same family hosted on Google Fonts.</summary><div>
* [com.google.fonts/check/cjk_vertical_metrics_regressions](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_vertical_metrics_regressions)

* 💔 **ERROR** The condition <FontBakeryCondition:regular_remote_style> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string.</summary><div>
* [com.google.fonts/check/license/OFL_copyright](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright)

* 🔥 **FAIL** First line in license file does not match expected format: "copyright 20** the my font project authors (https://github.com/googlefonts/my-font-repository)"
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata.</summary><div>
* [com.google.fonts/check/monospace](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/name.html#com.google.fonts/check/monospace)

* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** Font is monospaced but 7 glyphs (1.29%) have a different width. You should check the widths of: ['plus.alt', 'equal.alt', 'greaterarrow', 'exclamequal', 'lessergreater', 'greatergreaterarrow', 'equalequalarrow'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID.</summary><div>
* [com.google.fonts/check/vendor_id](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id)

* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters.</summary><div>
* [com.google.fonts/check/name/family_and_style_max_length](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length)

* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Spline Sans Mono Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description.</summary><div>
* [com.google.fonts/check/stylisticset_description](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description)

* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss05 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss08 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss09 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss10 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss11 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss14 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss15 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss16 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss17 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table.</summary><div>
* [com.google.fonts/check/meta/script_lang_tags](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags)

* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs</summary><div>
* [com.google.fonts/check/unreachable_glyphs](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs)

* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:
	- two.ss12
	- zerodot_part.
	- uni2155.ss01
	- commaturnedabove
	- IJ_acutecomb
	- ij_acutecomb 
	- And .null
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours.</summary><div>
* [com.google.fonts/check/contour_count](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count)

* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Q	Contours detected: 3	Expected: 2
	- Glyph name: uni00AD	Contours detected: 1	Expected: 0
	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4
	- Glyph name: onehalf	Contours detected: 2	Expected: 3
	- Glyph name: threequarters	Contours detected: 2	Expected: 3 or 4
	- Glyph name: eth	Contours detected: 3	Expected: 2
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: uni01F5	Contours detected: 4	Expected: 3
	- Glyph name: uni2153	Contours detected: 2	Expected: 3 
	- And 20 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks.</summary><div>
* [com.google.fonts/check/dotted_circle](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle)

* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points?</summary><div>
* [com.google.fonts/check/outline_alignment_miss](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss)

* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* ampersand (U+0026): X=1175.0,Y=-1.0 (should be at baseline 0?)
	* ampersand (U+0026): X=947.0,Y=-1.0 (should be at baseline 0?)
	* U (U+0055): X=110.0,Y=1456.0 (should be at cap-height 1454?)
	* U (U+0055): X=346.0,Y=1456.0 (should be at cap-height 1454?)
	* f (U+0066): X=204.0,Y=1092.0 (should be at x-height 1091?)
	* f (U+0066): X=444.0,Y=1092.0 (should be at x-height 1091?)
	* f (U+0066): X=670.0,Y=1092.0 (should be at x-height 1091?)
	* f (U+0066): X=1009.0,Y=1092.0 (should be at x-height 1091?)
	* g (U+0067): X=771.0,Y=1090.0 (should be at x-height 1091?)
	* g (U+0067): X=343.5,Y=1.0 (should be at baseline 0?) and 58 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments?</summary><div>
* [com.google.fonts/check/outline_jaggy_segments](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments)

* ⚠ **WARN** The following glyphs have jaggy segments:
	* B (U+0042): B<<989.0,873.5>-<920.0,784.0>-<815.0,765.0>>/B<<815.0,765.0>-<895.0,761.0>-<967.5,724.0>> = 13.119225067808111
	* Lslash (U+0141): L<<407.0,1454.0>--<407.0,909.0>>/B<<407.0,909.0>-<410.0,930.0>-<424.5,951.5>> = 8.13010235415596
	* a (U+0061): L<<813.0,0.0>--<813.0,245.0>>/B<<813.0,245.0>-<786.0,132.0>-<691.5,60.0>> = 13.438188158350638
	* aacute (U+00E1): L<<813.0,0.0>--<813.0,245.0>>/B<<813.0,245.0>-<786.0,132.0>-<691.5,60.0>> = 13.438188158350638
	* abreve (U+0103): L<<813.0,0.0>--<813.0,245.0>>/B<<813.0,245.0>-<786.0,132.0>-<691.5,60.0>> = 13.438188158350638
	* acircumflex (U+00E2): L<<813.0,0.0>--<813.0,245.0>>/B<<813.0,245.0>-<786.0,132.0>-<691.5,60.0>> = 13.438188158350638
	* adieresis (U+00E4): L<<813.0,0.0>--<813.0,245.0>>/B<<813.0,245.0>-<786.0,132.0>-<691.5,60.0>> = 13.438188158350638
	* ae (U+00E6): B<<721.5,833.0>-<686.0,752.0>-<683.0,598.0>>/B<<683.0,598.0>-<688.0,641.0>-<711.5,657.5>> = 5.516504223731211
	* aeacute (U+01FD): B<<721.5,833.0>-<686.0,752.0>-<683.0,598.0>>/B<<683.0,598.0>-<688.0,641.0>-<711.5,657.5>> = 5.516504223731211
	* agrave (U+00E0): L<<813.0,0.0>--<813.0,245.0>>/B<<813.0,245.0>-<786.0,132.0>-<691.5,60.0>> = 13.438188158350638 and 112 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines?</summary><div>
* [com.google.fonts/check/outline_semi_vertical](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical)

* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * Amacron (U+0100): L<<280.0,1815.0>--<922.0,1816.0>>
 * Amacron (U+0100): L<<919.0,1607.0>--<280.0,1606.0>>
 * Ccedilla (U+00C7): L<<472.0,-427.0>--<473.0,-260.0>>
 * Emacron (U+0112): L<<280.0,1815.0>--<922.0,1816.0>>
 * Emacron (U+0112): L<<919.0,1607.0>--<280.0,1606.0>>
 * F (U+0046): L<<1056.0,1454.0>--<1057.0,1252.0>>
 * G (U+0047): L<<1080.0,776.0>--<1078.0,158.0>>
 * Gbreve (U+011E): L<<1080.0,776.0>--<1078.0,158.0>>
 * Gcaron (U+01E6): L<<1080.0,776.0>--<1078.0,158.0>>
 * Gdotaccent (U+0120): L<<1080.0,776.0>--<1078.0,158.0>> and 85 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[17] SplineSansMono-Bold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check METADATA.pb includes production subsets.</summary><div>
* [com.google.fonts/check/metadata/includes_production_subsets](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/includes_production_subsets)

* 💔 **ERROR** The condition <FontBakeryCondition:production_metadata> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Version number has increased since previous release on Google Fonts?</summary><div>
* [com.google.fonts/check/version_bump](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/version_bump)

* 💔 **ERROR** The condition <FontBakeryCondition:api_gfonts_ttFont> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Glyphs are similiar to Google Fonts version?</summary><div>
* [com.google.fonts/check/production_glyphs_similarity](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity)

* 💔 **ERROR** The condition <FontBakeryCondition:api_gfonts_ttFont> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts.</summary><div>
* [com.google.fonts/check/vertical_metrics_regressions](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions)

* 💔 **ERROR** The condition <FontBakeryCondition:regular_remote_style> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Check font follows the Google Fonts CJK vertical metric schema</summary><div>
* [com.google.fonts/check/cjk_vertical_metrics](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_vertical_metrics)

* 💔 **ERROR** The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Check if the vertical metrics of a CJK family are similar to the same family hosted on Google Fonts.</summary><div>
* [com.google.fonts/check/cjk_vertical_metrics_regressions](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_vertical_metrics_regressions)

* 💔 **ERROR** The condition <FontBakeryCondition:regular_remote_style> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string.</summary><div>
* [com.google.fonts/check/license/OFL_copyright](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright)

* 🔥 **FAIL** First line in license file does not match expected format: "copyright 20** the my font project authors (https://github.com/googlefonts/my-font-repository)"
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata.</summary><div>
* [com.google.fonts/check/monospace](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/name.html#com.google.fonts/check/monospace)

* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** Font is monospaced but 7 glyphs (1.29%) have a different width. You should check the widths of: ['plus.alt', 'equal.alt', 'greaterarrow', 'exclamequal', 'lessergreater', 'greatergreaterarrow', 'equalequalarrow'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID.</summary><div>
* [com.google.fonts/check/vendor_id](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id)

* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description.</summary><div>
* [com.google.fonts/check/stylisticset_description](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description)

* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss05 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss08 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss09 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss10 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss11 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss14 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss15 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss16 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss17 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table.</summary><div>
* [com.google.fonts/check/meta/script_lang_tags](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags)

* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs</summary><div>
* [com.google.fonts/check/unreachable_glyphs](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs)

* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:
	- two.ss12
	- zerodot_part.
	- uni2155.ss01
	- commaturnedabove
	- IJ_acutecomb
	- ij_acutecomb 
	- And .null
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours.</summary><div>
* [com.google.fonts/check/contour_count](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count)

* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Q	Contours detected: 3	Expected: 2
	- Glyph name: uni00AD	Contours detected: 1	Expected: 0
	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4
	- Glyph name: onehalf	Contours detected: 2	Expected: 3
	- Glyph name: threequarters	Contours detected: 2	Expected: 3 or 4
	- Glyph name: eth	Contours detected: 3	Expected: 2
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: uni01F5	Contours detected: 4	Expected: 3
	- Glyph name: uni2153	Contours detected: 2	Expected: 3 
	- And 20 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks.</summary><div>
* [com.google.fonts/check/dotted_circle](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle)

* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points?</summary><div>
* [com.google.fonts/check/outline_alignment_miss](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss)

* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* ampersand (U+0026): X=1192.0,Y=-1.0 (should be at baseline 0?)
	* ampersand (U+0026): X=895.0,Y=-1.0 (should be at baseline 0?)
	* at (U+0040): X=287.5,Y=-0.5 (should be at baseline 0?)
	* U (U+0055): X=78.0,Y=1456.0 (should be at cap-height 1454?)
	* U (U+0055): X=392.0,Y=1456.0 (should be at cap-height 1454?)
	* f (U+0066): X=166.0,Y=1092.0 (should be at x-height 1091?)
	* f (U+0066): X=400.0,Y=1092.0 (should be at x-height 1091?)
	* f (U+0066): X=709.0,Y=1092.0 (should be at x-height 1091?)
	* f (U+0066): X=1024.0,Y=1092.0 (should be at x-height 1091?)
	* g (U+0067): X=1083.0,Y=1090.0 (should be at x-height 1091?) and 64 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments?</summary><div>
* [com.google.fonts/check/outline_jaggy_segments](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments)

* ⚠ **WARN** The following glyphs have jaggy segments:
	* B (U+0042): B<<997.5,882.5>-<925.0,801.0>-<802.0,790.0>>/B<<802.0,790.0>-<965.0,773.0>-<1049.5,687.5>> = 11.064524992196239
	* I (U+0049): B<<463.0,1148.0>-<485.0,1175.0>-<530.0,1182.0>>/L<<530.0,1182.0>--<135.0,1182.0>> = 8.84181456019167
	* I (U+0049): B<<736.0,306.5>-<714.0,280.0>-<669.0,272.0>>/L<<669.0,272.0>--<1065.0,272.0>> = 10.08059798754231
	* IJ (U+0132): B<<203.0,1138.0>-<225.0,1165.0>-<270.0,1172.0>>/L<<270.0,1172.0>--<25.0,1172.0>> = 8.84181456019167
	* IJ (U+0132): B<<466.0,896.5>-<444.0,870.0>-<399.0,862.0>>/L<<399.0,862.0>--<635.0,862.0>> = 10.08059798754231
	* Iacute (U+00CD): B<<463.0,1148.0>-<485.0,1175.0>-<530.0,1182.0>>/L<<530.0,1182.0>--<135.0,1182.0>> = 8.84181456019167
	* Iacute (U+00CD): B<<736.0,306.5>-<714.0,280.0>-<669.0,272.0>>/L<<669.0,272.0>--<1065.0,272.0>> = 10.08059798754231
	* Ibreve (U+012C): B<<463.0,1148.0>-<485.0,1175.0>-<530.0,1182.0>>/L<<530.0,1182.0>--<135.0,1182.0>> = 8.84181456019167
	* Ibreve (U+012C): B<<736.0,306.5>-<714.0,280.0>-<669.0,272.0>>/L<<669.0,272.0>--<1065.0,272.0>> = 10.08059798754231
	* Icircumflex (U+00CE): B<<463.0,1148.0>-<485.0,1175.0>-<530.0,1182.0>>/L<<530.0,1182.0>--<135.0,1182.0>> = 8.84181456019167 and 145 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines?</summary><div>
* [com.google.fonts/check/outline_semi_vertical](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical)

* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * Ccedilla (U+00C7): L<<418.0,-461.0>--<419.0,-262.0>>
 * F (U+0046): L<<1018.0,846.0>--<1017.0,574.0>>
 * F (U+0046): L<<1092.0,1454.0>--<1094.0,1173.0>>
 * Lcaron (U+013D): L<<694.0,1175.0>--<696.0,1561.0>>
 * R (U+0052): L<<619.0,1210.0>--<467.0,1211.0>>
 * Racute (U+0154): L<<619.0,1210.0>--<467.0,1211.0>>
 * Rcaron (U+0158): L<<619.0,1210.0>--<467.0,1211.0>>
 * Scedilla (U+015E): L<<458.0,-461.0>--<459.0,-262.0>>
 * Uogonek (U+0172): L<<880.0,-210.0>--<881.0,-385.0>>
 * a (U+0061): L<<758.0,0.0>--<760.0,255.0>> and 99 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[17] SplineSansMono-SemiBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check METADATA.pb includes production subsets.</summary><div>
* [com.google.fonts/check/metadata/includes_production_subsets](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/includes_production_subsets)

* 💔 **ERROR** The condition <FontBakeryCondition:production_metadata> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Version number has increased since previous release on Google Fonts?</summary><div>
* [com.google.fonts/check/version_bump](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/version_bump)

* 💔 **ERROR** The condition <FontBakeryCondition:api_gfonts_ttFont> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Glyphs are similiar to Google Fonts version?</summary><div>
* [com.google.fonts/check/production_glyphs_similarity](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity)

* 💔 **ERROR** The condition <FontBakeryCondition:api_gfonts_ttFont> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts.</summary><div>
* [com.google.fonts/check/vertical_metrics_regressions](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions)

* 💔 **ERROR** The condition <FontBakeryCondition:regular_remote_style> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Check font follows the Google Fonts CJK vertical metric schema</summary><div>
* [com.google.fonts/check/cjk_vertical_metrics](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_vertical_metrics)

* 💔 **ERROR** The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Check if the vertical metrics of a CJK family are similar to the same family hosted on Google Fonts.</summary><div>
* [com.google.fonts/check/cjk_vertical_metrics_regressions](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_vertical_metrics_regressions)

* 💔 **ERROR** The condition <FontBakeryCondition:regular_remote_style> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string.</summary><div>
* [com.google.fonts/check/license/OFL_copyright](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright)

* 🔥 **FAIL** First line in license file does not match expected format: "copyright 20** the my font project authors (https://github.com/googlefonts/my-font-repository)"
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata.</summary><div>
* [com.google.fonts/check/monospace](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/name.html#com.google.fonts/check/monospace)

* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** Font is monospaced but 7 glyphs (1.29%) have a different width. You should check the widths of: ['plus.alt', 'equal.alt', 'greaterarrow', 'exclamequal', 'lessergreater', 'greatergreaterarrow', 'equalequalarrow'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID.</summary><div>
* [com.google.fonts/check/vendor_id](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id)

* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters.</summary><div>
* [com.google.fonts/check/name/family_and_style_max_length](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length)

* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Spline Sans Mono SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description.</summary><div>
* [com.google.fonts/check/stylisticset_description](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description)

* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss05 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss08 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss09 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss10 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss11 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss14 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss15 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss16 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss17 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table.</summary><div>
* [com.google.fonts/check/meta/script_lang_tags](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags)

* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs</summary><div>
* [com.google.fonts/check/unreachable_glyphs](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs)

* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:
	- two.ss12
	- zerodot_part.
	- uni2155.ss01
	- commaturnedabove
	- IJ_acutecomb
	- ij_acutecomb 
	- And .null
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours.</summary><div>
* [com.google.fonts/check/contour_count](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count)

* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Q	Contours detected: 3	Expected: 2
	- Glyph name: uni00AD	Contours detected: 1	Expected: 0
	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4
	- Glyph name: onehalf	Contours detected: 2	Expected: 3
	- Glyph name: threequarters	Contours detected: 2	Expected: 3 or 4
	- Glyph name: eth	Contours detected: 3	Expected: 2
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: uni01F5	Contours detected: 4	Expected: 3
	- Glyph name: uni2153	Contours detected: 2	Expected: 3 
	- And 20 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks.</summary><div>
* [com.google.fonts/check/dotted_circle](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle)

* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments?</summary><div>
* [com.google.fonts/check/outline_jaggy_segments](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments)

* ⚠ **WARN** The following glyphs have jaggy segments:
	* B (U+0042): B<<993.5,878.0>-<923.0,793.0>-<808.0,778.0>>/B<<808.0,778.0>-<951.0,766.0>-<1042.0,683.5>> = 12.22820693800804
	* I (U+0049): B<<477.5,1176.5>-<496.0,1201.0>-<533.0,1209.0>>/L<<533.0,1209.0>--<143.0,1209.0>> = 12.200468727380786
	* I (U+0049): B<<721.5,277.5>-<703.0,253.0>-<666.0,245.0>>/L<<666.0,245.0>--<1057.0,245.0>> = 12.200468727380786
	* IJ (U+0132): B<<221.5,1170.5>-<240.0,1195.0>-<277.0,1203.0>>/L<<277.0,1203.0>--<33.0,1203.0>> = 12.200468727380786
	* IJ (U+0132): B<<459.5,837.0>-<441.0,812.0>-<404.0,805.0>>/L<<404.0,805.0>--<643.0,805.0>> = 10.713123022791033
	* Iacute (U+00CD): B<<477.5,1176.5>-<496.0,1201.0>-<533.0,1209.0>>/L<<533.0,1209.0>--<143.0,1209.0>> = 12.200468727380786
	* Iacute (U+00CD): B<<721.5,277.5>-<703.0,253.0>-<666.0,245.0>>/L<<666.0,245.0>--<1057.0,245.0>> = 12.200468727380786
	* Ibreve (U+012C): B<<477.5,1176.5>-<496.0,1201.0>-<533.0,1209.0>>/L<<533.0,1209.0>--<143.0,1209.0>> = 12.200468727380786
	* Ibreve (U+012C): B<<721.5,277.5>-<703.0,253.0>-<666.0,245.0>>/L<<666.0,245.0>--<1057.0,245.0>> = 12.200468727380786
	* Icircumflex (U+00CE): B<<477.5,1176.5>-<496.0,1201.0>-<533.0,1209.0>>/L<<533.0,1209.0>--<143.0,1209.0>> = 12.200468727380786 and 161 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines?</summary><div>
* [com.google.fonts/check/outline_semi_vertical](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical)

* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * Ccedilla (U+00C7): L<<443.0,-445.0>--<444.0,-261.0>>
 * F (U+0046): L<<1075.0,1454.0>--<1077.0,1210.0>>
 * F (U+0046): L<<997.0,840.0>--<996.0,601.0>>
 * G (U+0047): L<<1091.0,796.0>--<1090.0,170.0>>
 * Gbreve (U+011E): L<<1091.0,796.0>--<1090.0,170.0>>
 * Gcaron (U+01E6): L<<1091.0,796.0>--<1090.0,170.0>>
 * Gdotaccent (U+0120): L<<1091.0,796.0>--<1090.0,170.0>>
 * M (U+004D): L<<913.0,0.0>--<908.0,604.0>>
 * R (U+0052): L<<597.0,1231.0>--<429.0,1232.0>>
 * Racute (U+0154): L<<597.0,1231.0>--<429.0,1232.0>> and 88 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[17] SplineSansMono-Light.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check METADATA.pb includes production subsets.</summary><div>
* [com.google.fonts/check/metadata/includes_production_subsets](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/includes_production_subsets)

* 💔 **ERROR** The condition <FontBakeryCondition:production_metadata> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Version number has increased since previous release on Google Fonts?</summary><div>
* [com.google.fonts/check/version_bump](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/version_bump)

* 💔 **ERROR** The condition <FontBakeryCondition:api_gfonts_ttFont> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Glyphs are similiar to Google Fonts version?</summary><div>
* [com.google.fonts/check/production_glyphs_similarity](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity)

* 💔 **ERROR** The condition <FontBakeryCondition:api_gfonts_ttFont> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts.</summary><div>
* [com.google.fonts/check/vertical_metrics_regressions](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions)

* 💔 **ERROR** The condition <FontBakeryCondition:regular_remote_style> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Check font follows the Google Fonts CJK vertical metric schema</summary><div>
* [com.google.fonts/check/cjk_vertical_metrics](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_vertical_metrics)

* 💔 **ERROR** The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Check if the vertical metrics of a CJK family are similar to the same family hosted on Google Fonts.</summary><div>
* [com.google.fonts/check/cjk_vertical_metrics_regressions](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_vertical_metrics_regressions)

* 💔 **ERROR** The condition <FontBakeryCondition:regular_remote_style> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string.</summary><div>
* [com.google.fonts/check/license/OFL_copyright](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright)

* 🔥 **FAIL** First line in license file does not match expected format: "copyright 20** the my font project authors (https://github.com/googlefonts/my-font-repository)"
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata.</summary><div>
* [com.google.fonts/check/monospace](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/name.html#com.google.fonts/check/monospace)

* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** Font is monospaced but 8 glyphs (1.48%) have a different width. You should check the widths of: ['uni2155', 'plus.alt', 'equal.alt', 'greaterarrow', 'exclamequal', 'lessergreater', 'greatergreaterarrow', 'equalequalarrow'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID.</summary><div>
* [com.google.fonts/check/vendor_id](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id)

* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters.</summary><div>
* [com.google.fonts/check/name/family_and_style_max_length](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length)

* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Spline Sans Mono Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description.</summary><div>
* [com.google.fonts/check/stylisticset_description](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description)

* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss05 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss08 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss09 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss10 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss11 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss14 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss15 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss16 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss17 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table.</summary><div>
* [com.google.fonts/check/meta/script_lang_tags](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags)

* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs</summary><div>
* [com.google.fonts/check/unreachable_glyphs](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs)

* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:
	- two.ss12
	- zerodot_part.
	- uni2155.ss01
	- commaturnedabove
	- IJ_acutecomb
	- ij_acutecomb 
	- And .null
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours.</summary><div>
* [com.google.fonts/check/contour_count](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count)

* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Q	Contours detected: 3	Expected: 2
	- Glyph name: uni00AD	Contours detected: 1	Expected: 0
	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4
	- Glyph name: onehalf	Contours detected: 2	Expected: 3
	- Glyph name: threequarters	Contours detected: 2	Expected: 3 or 4
	- Glyph name: eth	Contours detected: 3	Expected: 2
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: uni01F5	Contours detected: 4	Expected: 3
	- Glyph name: uni2153	Contours detected: 2	Expected: 3 
	- And 20 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks.</summary><div>
* [com.google.fonts/check/dotted_circle](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle)

* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments?</summary><div>
* [com.google.fonts/check/outline_jaggy_segments](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments)

* ⚠ **WARN** The following glyphs have jaggy segments:
	* B (U+0042): B<<996.5,879.0>-<925.0,796.0>-<808.0,773.0>>/B<<808.0,773.0>-<889.0,772.0>-<963.0,735.5>> = 11.828779563434608
	* Lslash (U+0141): L<<297.0,1454.0>--<297.0,923.0>>/B<<297.0,923.0>-<300.0,940.0>-<312.5,957.0>> = 10.007979801441312
	* OE (U+0152): L<<658.0,0.0>--<657.0,266.0>>/B<<657.0,266.0>-<629.0,143.0>-<557.0,61.5>> = 13.03979475484222
	* P (U+0050): B<<320.0,587.0>-<300.0,600.0>-<296.0,618.0>>/L<<296.0,618.0>--<296.0,0.0>> = 12.528807709151492
	* Thorn (U+00DE): B<<320.0,299.5>-<300.0,313.0>-<296.0,330.0>>/L<<296.0,330.0>--<296.0,0.0>> = 13.240519915187184
	* ae (U+00E6): B<<700.5,883.5>-<644.0,769.0>-<638.0,563.0>>/B<<638.0,563.0>-<648.0,625.0>-<706.0,625.0>> = 7.494009597428414
	* aeacute (U+01FD): B<<700.5,883.5>-<644.0,769.0>-<638.0,563.0>>/B<<638.0,563.0>-<648.0,625.0>-<706.0,625.0>> = 7.494009597428414
	* b (U+0062): L<<309.0,1556.0>--<309.0,849.0>>/B<<309.0,849.0>-<325.0,934.0>-<378.5,992.5>> = 10.66034829453532
	* comma (U+002C): B<<601.5,-45.5>-<615.0,-10.0>-<671.0,0.0>>/L<<671.0,0.0>--<509.0,0.0>> = 10.124671655397806
	* d (U+0064): L<<899.0,0.0>--<899.0,251.0>>/B<<899.0,251.0>-<876.0,124.0>-<785.5,56.0>> = 10.265140460213706 and 91 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines?</summary><div>
* [com.google.fonts/check/outline_semi_vertical](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical)

* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * Aogonek (U+0104): L<<1172.0,-251.0>--<1173.0,-367.0>>
 * Eng (U+014A): L<<1060.0,1454.0>--<1059.0,0.0>>
 * Eng (U+014A): L<<263.0,949.0>--<262.0,0.0>>
 * Eogonek (U+0118): L<<1067.0,-251.0>--<1068.0,-367.0>>
 * G (U+0047): L<<1077.0,734.0>--<1075.0,135.0>>
 * G (U+0047): L<<950.0,200.0>--<952.0,611.0>>
 * Gbreve (U+011E): L<<1077.0,734.0>--<1075.0,135.0>>
 * Gbreve (U+011E): L<<950.0,200.0>--<952.0,611.0>>
 * Gcaron (U+01E6): L<<1077.0,734.0>--<1075.0,135.0>>
 * Gcaron (U+01E6): L<<950.0,200.0>--<952.0,611.0>> and 72 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] SplineSansMono-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check METADATA.pb includes production subsets.</summary><div>
* [com.google.fonts/check/metadata/includes_production_subsets](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/includes_production_subsets)

* 💔 **ERROR** The condition <FontBakeryCondition:production_metadata> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Version number has increased since previous release on Google Fonts?</summary><div>
* [com.google.fonts/check/version_bump](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/version_bump)

* 💔 **ERROR** The condition <FontBakeryCondition:api_gfonts_ttFont> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Glyphs are similiar to Google Fonts version?</summary><div>
* [com.google.fonts/check/production_glyphs_similarity](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity)

* 💔 **ERROR** The condition <FontBakeryCondition:api_gfonts_ttFont> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts.</summary><div>
* [com.google.fonts/check/vertical_metrics_regressions](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions)

* 💔 **ERROR** The condition <FontBakeryCondition:regular_remote_style> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Check font follows the Google Fonts CJK vertical metric schema</summary><div>
* [com.google.fonts/check/cjk_vertical_metrics](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_vertical_metrics)

* 💔 **ERROR** The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Check if the vertical metrics of a CJK family are similar to the same family hosted on Google Fonts.</summary><div>
* [com.google.fonts/check/cjk_vertical_metrics_regressions](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_vertical_metrics_regressions)

* 💔 **ERROR** The condition <FontBakeryCondition:regular_remote_style> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string.</summary><div>
* [com.google.fonts/check/license/OFL_copyright](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright)

* 🔥 **FAIL** First line in license file does not match expected format: "copyright 20** the my font project authors (https://github.com/googlefonts/my-font-repository)"
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata.</summary><div>
* [com.google.fonts/check/monospace](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/name.html#com.google.fonts/check/monospace)

* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** Font is monospaced but 8 glyphs (1.48%) have a different width. You should check the widths of: ['uni2155', 'plus.alt', 'equal.alt', 'greaterarrow', 'exclamequal', 'lessergreater', 'greatergreaterarrow', 'equalequalarrow'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID.</summary><div>
* [com.google.fonts/check/vendor_id](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id)

* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description.</summary><div>
* [com.google.fonts/check/stylisticset_description](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description)

* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss05 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss08 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss09 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss10 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss11 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss14 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss15 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss16 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss17 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table.</summary><div>
* [com.google.fonts/check/meta/script_lang_tags](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags)

* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs</summary><div>
* [com.google.fonts/check/unreachable_glyphs](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs)

* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:
	- two.ss12
	- zerodot_part.
	- uni2155.ss01
	- commaturnedabove
	- IJ_acutecomb
	- ij_acutecomb 
	- And .null
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours.</summary><div>
* [com.google.fonts/check/contour_count](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count)

* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Q	Contours detected: 3	Expected: 2
	- Glyph name: uni00AD	Contours detected: 1	Expected: 0
	- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4
	- Glyph name: onehalf	Contours detected: 2	Expected: 3
	- Glyph name: threequarters	Contours detected: 2	Expected: 3 or 4
	- Glyph name: eth	Contours detected: 3	Expected: 2
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: uni01F5	Contours detected: 4	Expected: 3
	- Glyph name: uni2153	Contours detected: 2	Expected: 3 
	- And 20 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks.</summary><div>
* [com.google.fonts/check/dotted_circle](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle)

* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments?</summary><div>
* [com.google.fonts/check/outline_jaggy_segments](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments)

* ⚠ **WARN** The following glyphs have jaggy segments:
	* B (U+0042): B<<991.5,874.5>-<922.0,787.0>-<814.0,766.0>>/B<<814.0,766.0>-<891.0,763.0>-<964.0,727.0>> = 13.23471545978075
	* Lslash (U+0141): L<<354.0,1454.0>--<354.0,913.0>>/B<<354.0,913.0>-<357.0,932.0>-<370.5,951.5>> = 8.972626614896358
	* P (U+0050): B<<367.0,543.5>-<347.0,560.0>-<345.0,588.0>>/L<<345.0,588.0>--<345.0,0.0>> = 4.085616779974798
	* Thorn (U+00DE): B<<368.0,282.5>-<348.0,296.0>-<344.0,314.0>>/L<<344.0,314.0>--<344.0,0.0>> = 12.528807709151492
	* ae (U+00E6): B<<713.5,855.5>-<669.0,762.0>-<664.0,589.0>>/B<<664.0,589.0>-<670.0,626.0>-<690.0,641.5>> = 7.5555400016973575
	* aeacute (U+01FD): B<<713.5,855.5>-<669.0,762.0>-<664.0,589.0>>/B<<664.0,589.0>-<670.0,626.0>-<690.0,641.5>> = 7.5555400016973575
	* b (U+0062): L<<362.0,1068.0>--<362.0,858.0>>/B<<362.0,858.0>-<374.0,932.0>-<422.5,989.0>> = 9.211026540816649
	* comma (U+002C): B<<603.5,-44.5>-<616.0,-13.0>-<675.0,0.0>>/L<<675.0,0.0>--<487.0,0.0>> = 12.425942865427485
	* d (U+0064): L<<850.0,0.0>--<849.0,246.0>>/B<<849.0,246.0>-<837.0,171.0>-<792.5,113.0>> = 9.323185310742842
	* dcaron (U+010F): L<<844.0,0.0>--<843.0,246.0>>/B<<843.0,246.0>-<831.0,171.0>-<786.5,113.0>> = 9.323185310742842 and 101 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines?</summary><div>
* [com.google.fonts/check/outline_semi_vertical](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical)

* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * Amacron (U+0100): L<<289.0,1776.0>--<913.0,1777.0>>
 * Ccedilla (U+00C7): L<<476.0,-406.0>--<477.0,-262.0>>
 * Emacron (U+0112): L<<297.0,1776.0>--<921.0,1777.0>>
 * Eng (U+014A): L<<316.0,887.0>--<315.0,0.0>>
 * G (U+0047): L<<1077.0,757.0>--<1075.0,148.0>>
 * Gbreve (U+011E): L<<1077.0,757.0>--<1075.0,148.0>>
 * Gcaron (U+01E6): L<<1077.0,757.0>--<1075.0,148.0>>
 * Gdotaccent (U+0120): L<<1077.0,757.0>--<1075.0,148.0>>
 * Lslash (U+0141): L<<24.0,606.0>--<23.0,796.0>>
 * OE (U+0152): L<<632.0,1271.0>--<633.0,1454.0>> and 91 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 30 | 10 | 45 | 498 | 31 | 437 | 0 |
| 3% | 1% | 4% | 47% | 3% | 42% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
