## Fontbakery report

Fontbakery version: 0.8.7

<details><summary><b>[15] SplineSansMono-LightItalic.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check METADATA.pb includes production subsets.</summary><div>
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
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters.</summary><div>
* [com.google.fonts/check/name/family_and_style_max_length](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length)

* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Spline Sans Mono Light' / SUBFAMILY_NAME = 'Italic'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description.</summary><div>
* [com.google.fonts/check/stylisticset_description](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description)

* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss08 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss09 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss10 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss11 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss12 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss14 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss15 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss16 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss17 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss18 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss19 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table.</summary><div>
* [com.google.fonts/check/meta/script_lang_tags](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags)

* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs</summary><div>
* [com.google.fonts/check/unreachable_glyphs](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs)

* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:
	- commaturnedabove
	- uni2154.ss19
	- IJ_acutecomb
	- ij_acutecomb
	- uni2159.ss19
	- .null 
	- And uni2153.ss19
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
	- Glyph name: Eth	Contours detected: 3	Expected: 2
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: Dcroat	Contours detected: 3	Expected: 2
	- Glyph name: dcroat	Contours detected: 3	Expected: 2
	- Glyph name: eogonek	Contours detected: 3	Expected: 2 
	- And 23 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks.</summary><div>
* [com.google.fonts/check/dotted_circle](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle)

* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata.</summary><div>
* [com.google.fonts/check/monospace](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/name.html#com.google.fonts/check/monospace)

* ⚠ **WARN** Font is monospaced but 18 glyphs (2.87%) have a different width. You should check the widths of: ['a', 'aacute', 'abreve', 'acircumflex', 'adieresis', 'agrave', 'amacron', 'aogonek', 'aring', 'aringacute', 'atilde', 'plus.alt', 'equal.alt', 'greaterarrow', 'exclamequal', 'lessergreater', 'greatergreaterarrow', 'equalequalarrow'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points?</summary><div>
* [com.google.fonts/check/outline_alignment_miss](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss)

* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* exclam (U+0021): X=413.0,Y=1.5 (should be at baseline 0?)
	* dollar (U+0024): X=649.0,Y=1452.0 (should be at cap-height 1454?)
	* dollar (U+0024): X=774.0,Y=1452.0 (should be at cap-height 1454?)
	* question (U+003F): X=987.0,Y=1454.5 (should be at cap-height 1454?)
	* question (U+003F): X=430.0,Y=-0.5 (should be at baseline 0?)
	* J (U+004A): X=291.0,Y=2.0 (should be at baseline 0?)
	* U (U+0055): X=229.0,Y=1456.0 (should be at cap-height 1454?)
	* U (U+0055): X=354.0,Y=1456.0 (should be at cap-height 1454?)
	* a (U+0061): X=952.5,Y=1093.0 (should be at x-height 1091?)
	* f (U+0066): X=258.0,Y=1092.0 (should be at x-height 1091?) and 59 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments?</summary><div>
* [com.google.fonts/check/outline_jaggy_segments](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments)

* ⚠ **WARN** The following glyphs have jaggy segments:
	* B (U+0042): B<<1040.5,900.5>-<957.0,799.0>-<812.0,773.0>>/B<<812.0,773.0>-<881.0,772.0>-<949.5,740.5>> = 10.996010365800657
	* OE (U+0152): L<<568.0,0.0>--<600.0,266.0>>/B<<600.0,266.0>-<557.0,143.0>-<475.0,61.5>> = 12.409534392942978
	* P (U+0050): B<<322.0,587.0>-<304.0,600.0>-<302.0,618.0>>/L<<302.0,618.0>--<226.0,0.0>> = 13.351073226830854
	* a (U+0061): L<<829.0,310.0>--<845.0,445.0>>/B<<845.0,445.0>-<813.0,309.0>-<742.5,206.0>> = 6.481438788216659
	* a (U+0061): L<<865.0,610.0>--<865.0,609.0>>/L<<865.0,609.0>--<911.0,986.0>> = 6.95660990518771
	* aacute (U+00E1): L<<829.0,310.0>--<845.0,445.0>>/B<<845.0,445.0>-<813.0,309.0>-<742.5,206.0>> = 6.481438788216659
	* aacute (U+00E1): L<<865.0,610.0>--<865.0,609.0>>/L<<865.0,609.0>--<911.0,986.0>> = 6.95660990518771
	* abreve (U+0103): L<<829.0,310.0>--<845.0,445.0>>/B<<845.0,445.0>-<813.0,309.0>-<742.5,206.0>> = 6.481438788216659
	* abreve (U+0103): L<<865.0,610.0>--<865.0,609.0>>/L<<865.0,609.0>--<911.0,986.0>> = 6.95660990518771
	* acircumflex (U+00E2): L<<829.0,310.0>--<845.0,445.0>>/B<<845.0,445.0>-<813.0,309.0>-<742.5,206.0>> = 6.481438788216659 and 134 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
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
* ⚠ **WARN** The stylistic set ss12 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss14 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss15 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss16 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss17 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss18 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss19 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table.</summary><div>
* [com.google.fonts/check/meta/script_lang_tags](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags)

* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs</summary><div>
* [com.google.fonts/check/unreachable_glyphs](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs)

* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:
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
	- Glyph name: Eth	Contours detected: 3	Expected: 2
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: Dcroat	Contours detected: 3	Expected: 2
	- Glyph name: Lslash	Contours detected: 2	Expected: 1
	- Glyph name: lslash	Contours detected: 2	Expected: 1 
	- And 16 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks.</summary><div>
* [com.google.fonts/check/dotted_circle](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle)

* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata.</summary><div>
* [com.google.fonts/check/monospace](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/name.html#com.google.fonts/check/monospace)

* ⚠ **WARN** Font is monospaced but 7 glyphs (1.26%) have a different width. You should check the widths of: ['plus.alt', 'equal.alt', 'greaterarrow', 'exclamequal', 'lessergreater', 'greatergreaterarrow', 'equalequalarrow'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points?</summary><div>
* [com.google.fonts/check/outline_alignment_miss](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss)

* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* U (U+0055): X=93.0,Y=1456.0 (should be at cap-height 1454?)
	* U (U+0055): X=370.0,Y=1456.0 (should be at cap-height 1454?)
	* f (U+0066): X=184.0,Y=1092.0 (should be at x-height 1091?)
	* f (U+0066): X=421.0,Y=1092.0 (should be at x-height 1091?)
	* f (U+0066): X=691.0,Y=1092.0 (should be at x-height 1091?)
	* f (U+0066): X=1017.0,Y=1092.0 (should be at x-height 1091?)
	* g (U+0067): X=146.5,Y=2.0 (should be at baseline 0?)
	* g (U+0067): X=770.0,Y=1092.0 (should be at x-height 1091?)
	* g (U+0067): X=331.5,Y=0.5 (should be at baseline 0?)
	* j (U+006A): X=265.0,Y=1092.0 (should be at x-height 1091?) and 62 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short?</summary><div>
* [com.google.fonts/check/outline_short_segments](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments)

* ⚠ **WARN** The following glyphs have segments which seem very short:
	* less (U+003C) contains a short segment L<<406.0,756.0>--<406.0,751.0>>
	* greater (U+003E) contains a short segment L<<794.0,751.0>--<794.0,756.0>>
	* at (U+0040) contains a short segment B<<716.0,342.0>-<718.0,361.0>-<722.5,392.0>>
	* M (U+004D) contains a short segment L<<598.0,661.0>--<604.0,661.0>>
	* M (U+004D) contains a short segment L<<917.0,1269.0>--<901.0,1269.0>>
	* M (U+004D) contains a short segment L<<298.0,1269.0>--<281.0,1269.0>>
	* N (U+004E) contains a short segment L<<872.0,278.0>--<879.0,278.0>>
	* N (U+004E) contains a short segment L<<333.0,1154.0>--<324.0,1154.0>>
	* V (U+0056) contains a short segment L<<596.0,244.0>--<606.0,244.0>>
	* W (U+0057) contains a short segment L<<838.0,191.0>--<846.0,191.0>> and 82 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments?</summary><div>
* [com.google.fonts/check/outline_jaggy_segments](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments)

* ⚠ **WARN** The following glyphs have jaggy segments:
	* B (U+0042): B<<993.5,878.0>-<923.0,793.0>-<808.0,778.0>>/B<<808.0,778.0>-<951.0,766.0>-<1042.0,683.5>> = 12.22820693800804
	* I (U+0049): B<<478.5,1178.5>-<497.0,1203.0>-<534.0,1211.0>>/L<<534.0,1211.0>--<143.0,1211.0>> = 12.200468727380786
	* I (U+0049): B<<720.5,275.5>-<702.0,251.0>-<665.0,243.0>>/L<<665.0,243.0>--<1057.0,243.0>> = 12.200468727380786
	* IJ (U+0132): B<<221.5,1170.5>-<240.0,1195.0>-<277.0,1203.0>>/L<<277.0,1203.0>--<33.0,1203.0>> = 12.200468727380786
	* IJ (U+0132): B<<459.5,837.0>-<441.0,812.0>-<404.0,805.0>>/L<<404.0,805.0>--<643.0,805.0>> = 10.713123022791033
	* Iacute (U+00CD): B<<478.5,1178.5>-<497.0,1203.0>-<534.0,1211.0>>/L<<534.0,1211.0>--<143.0,1211.0>> = 12.200468727380786
	* Iacute (U+00CD): B<<720.5,275.5>-<702.0,251.0>-<665.0,243.0>>/L<<665.0,243.0>--<1057.0,243.0>> = 12.200468727380786
	* Ibreve (U+012C): B<<478.5,1178.5>-<497.0,1203.0>-<534.0,1211.0>>/L<<534.0,1211.0>--<143.0,1211.0>> = 12.200468727380786
	* Ibreve (U+012C): B<<720.5,275.5>-<702.0,251.0>-<665.0,243.0>>/L<<665.0,243.0>--<1057.0,243.0>> = 12.200468727380786
	* Icircumflex (U+00CE): B<<478.5,1178.5>-<497.0,1203.0>-<534.0,1211.0>>/L<<534.0,1211.0>--<143.0,1211.0>> = 12.200468727380786 and 152 more.

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
 * Racute (U+0154): L<<597.0,1231.0>--<429.0,1232.0>> and 87 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[15] SplineSansMono-BoldItalic.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check METADATA.pb includes production subsets.</summary><div>
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
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description.</summary><div>
* [com.google.fonts/check/stylisticset_description](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description)

* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss08 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss09 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss10 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss11 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss12 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss14 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss15 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss16 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss17 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss18 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss19 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table.</summary><div>
* [com.google.fonts/check/meta/script_lang_tags](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags)

* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs</summary><div>
* [com.google.fonts/check/unreachable_glyphs](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs)

* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:
	- commaturnedabove
	- uni2154.ss19
	- IJ_acutecomb
	- ij_acutecomb
	- uni2159.ss19
	- .null 
	- And uni2153.ss19
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
	- Glyph name: Eth	Contours detected: 3	Expected: 2
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: Dcroat	Contours detected: 3	Expected: 2
	- Glyph name: dcroat	Contours detected: 3	Expected: 2
	- Glyph name: eogonek	Contours detected: 3	Expected: 2 
	- And 23 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks.</summary><div>
* [com.google.fonts/check/dotted_circle](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle)

* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata.</summary><div>
* [com.google.fonts/check/monospace](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/name.html#com.google.fonts/check/monospace)

* ⚠ **WARN** Font is monospaced but 7 glyphs (1.12%) have a different width. You should check the widths of: ['plus.alt', 'equal.alt', 'greaterarrow', 'exclamequal', 'lessergreater', 'greatergreaterarrow', 'equalequalarrow'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points?</summary><div>
* [com.google.fonts/check/outline_alignment_miss](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss)

* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* U (U+0055): X=190.0,Y=1456.0 (should be at cap-height 1454?)
	* U (U+0055): X=504.0,Y=1456.0 (should be at cap-height 1454?)
	* f (U+0066): X=219.0,Y=1092.0 (should be at x-height 1091?)
	* f (U+0066): X=464.0,Y=1092.0 (should be at x-height 1091?)
	* f (U+0066): X=768.0,Y=1092.0 (should be at x-height 1091?)
	* f (U+0066): X=1108.0,Y=1092.0 (should be at x-height 1091?)
	* j (U+006A): X=493.0,Y=-2.0 (should be at baseline 0?)
	* j (U+006A): X=272.0,Y=1092.0 (should be at x-height 1091?)
	* j (U+006A): X=946.0,Y=1092.0 (should be at x-height 1091?)
	* m (U+006D): X=123.0,Y=1092.0 (should be at x-height 1091?) and 55 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short?</summary><div>
* [com.google.fonts/check/outline_short_segments](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments)

* ⚠ **WARN** The following glyphs have segments which seem very short:
	* two (U+0032) contains a short segment B<<424.0,949.0>-<424.0,942.0>-<424.5,934.0>>
	* two (U+0032) contains a short segment B<<424.5,934.0>-<425.0,926.0>-<426.0,918.0>>
	* two (U+0032) contains a short segment B<<134.0,918.0>-<133.0,928.0>-<132.5,938.5>>
	* two (U+0032) contains a short segment B<<132.5,938.5>-<132.0,949.0>-<132.0,961.0>>
	* less (U+003C) contains a short segment L<<474.0,692.0>--<474.0,686.0>>
	* greater (U+003E) contains a short segment L<<780.0,702.0>--<781.0,708.0>>
	* question (U+003F) contains a short segment B<<431.0,539.0>-<429.0,550.0>-<427.5,562.5>>
	* question (U+003F) contains a short segment B<<427.5,562.5>-<426.0,575.0>-<427.0,588.0>>
	* at (U+0040) contains a short segment B<<711.0,332.0>-<716.0,355.0>-<724.0,384.0>>
	* at (U+0040) contains a short segment B<<791.5,978.0>-<828.0,962.0>-<844.0,948.0>> and 78 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments?</summary><div>
* [com.google.fonts/check/outline_jaggy_segments](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments)

* ⚠ **WARN** The following glyphs have jaggy segments:
	* B (U+0042): B<<1041.5,899.5>-<955.0,801.0>-<819.0,790.0>>/B<<819.0,790.0>-<971.0,774.0>-<1046.5,695.5>> = 10.633157285923572
	* I (U+0049): B<<562.0,1151.5>-<587.0,1178.0>-<632.0,1185.0>>/L<<632.0,1185.0>--<235.0,1185.0>> = 8.84181456019167
	* I (U+0049): B<<726.5,303.5>-<701.0,277.0>-<655.0,269.0>>/L<<655.0,269.0>--<1053.0,269.0>> = 9.865806943084365
	* IJ (U+0132): B<<297.5,1139.0>-<323.0,1165.0>-<368.0,1172.0>>/L<<368.0,1172.0>--<123.0,1172.0>> = 8.84181456019167
	* IJ (U+0132): B<<530.5,896.5>-<505.0,870.0>-<459.0,862.0>>/L<<459.0,862.0>--<695.0,862.0>> = 9.865806943084365
	* Iacute (U+00CD): B<<562.0,1151.5>-<587.0,1178.0>-<632.0,1185.0>>/L<<632.0,1185.0>--<235.0,1185.0>> = 8.84181456019167
	* Iacute (U+00CD): B<<726.5,303.5>-<701.0,277.0>-<655.0,269.0>>/L<<655.0,269.0>--<1053.0,269.0>> = 9.865806943084365
	* Ibreve (U+012C): B<<562.0,1151.5>-<587.0,1178.0>-<632.0,1185.0>>/L<<632.0,1185.0>--<235.0,1185.0>> = 8.84181456019167
	* Ibreve (U+012C): B<<726.5,303.5>-<701.0,277.0>-<655.0,269.0>>/L<<655.0,269.0>--<1053.0,269.0>> = 9.865806943084365
	* Icircumflex (U+00CE): B<<562.0,1151.5>-<587.0,1178.0>-<632.0,1185.0>>/L<<632.0,1185.0>--<235.0,1185.0>> = 8.84181456019167 and 148 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[15] SplineSansMono-Bold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check METADATA.pb includes production subsets.</summary><div>
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
* ⚠ **WARN** The stylistic set ss12 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss14 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss15 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss16 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss17 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss18 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss19 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table.</summary><div>
* [com.google.fonts/check/meta/script_lang_tags](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags)

* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs</summary><div>
* [com.google.fonts/check/unreachable_glyphs](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs)

* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:
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
	- Glyph name: Eth	Contours detected: 3	Expected: 2
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: Dcroat	Contours detected: 3	Expected: 2
	- Glyph name: Lslash	Contours detected: 2	Expected: 1
	- Glyph name: lslash	Contours detected: 2	Expected: 1 
	- And 16 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks.</summary><div>
* [com.google.fonts/check/dotted_circle](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle)

* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata.</summary><div>
* [com.google.fonts/check/monospace](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/name.html#com.google.fonts/check/monospace)

* ⚠ **WARN** Font is monospaced but 7 glyphs (1.26%) have a different width. You should check the widths of: ['plus.alt', 'equal.alt', 'greaterarrow', 'exclamequal', 'lessergreater', 'greatergreaterarrow', 'equalequalarrow'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points?</summary><div>
* [com.google.fonts/check/outline_alignment_miss](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss)

* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* at (U+0040): X=287.5,Y=-0.5 (should be at baseline 0?)
	* U (U+0055): X=78.0,Y=1456.0 (should be at cap-height 1454?)
	* U (U+0055): X=392.0,Y=1456.0 (should be at cap-height 1454?)
	* f (U+0066): X=166.0,Y=1092.0 (should be at x-height 1091?)
	* f (U+0066): X=400.0,Y=1092.0 (should be at x-height 1091?)
	* f (U+0066): X=709.0,Y=1092.0 (should be at x-height 1091?)
	* f (U+0066): X=1024.0,Y=1092.0 (should be at x-height 1091?)
	* g (U+0067): X=1083.0,Y=1090.0 (should be at x-height 1091?)
	* j (U+006A): X=597.0,Y=-2.0 (should be at baseline 0?)
	* j (U+006A): X=252.0,Y=1092.0 (should be at x-height 1091?) and 52 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments?</summary><div>
* [com.google.fonts/check/outline_jaggy_segments](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments)

* ⚠ **WARN** The following glyphs have jaggy segments:
	* B (U+0042): B<<997.5,882.5>-<925.0,801.0>-<802.0,790.0>>/B<<802.0,790.0>-<965.0,773.0>-<1049.5,687.5>> = 11.064524992196239
	* I (U+0049): B<<465.0,1151.0>-<487.0,1178.0>-<532.0,1185.0>>/L<<532.0,1185.0>--<135.0,1185.0>> = 8.84181456019167
	* I (U+0049): B<<734.0,303.5>-<712.0,277.0>-<667.0,269.0>>/L<<667.0,269.0>--<1065.0,269.0>> = 10.08059798754231
	* IJ (U+0132): B<<203.0,1138.0>-<225.0,1165.0>-<270.0,1172.0>>/L<<270.0,1172.0>--<25.0,1172.0>> = 8.84181456019167
	* IJ (U+0132): B<<466.0,896.5>-<444.0,870.0>-<399.0,862.0>>/L<<399.0,862.0>--<635.0,862.0>> = 10.08059798754231
	* Iacute (U+00CD): B<<465.0,1151.0>-<487.0,1178.0>-<532.0,1185.0>>/L<<532.0,1185.0>--<135.0,1185.0>> = 8.84181456019167
	* Iacute (U+00CD): B<<734.0,303.5>-<712.0,277.0>-<667.0,269.0>>/L<<667.0,269.0>--<1065.0,269.0>> = 10.08059798754231
	* Ibreve (U+012C): B<<465.0,1151.0>-<487.0,1178.0>-<532.0,1185.0>>/L<<532.0,1185.0>--<135.0,1185.0>> = 8.84181456019167
	* Ibreve (U+012C): B<<734.0,303.5>-<712.0,277.0>-<667.0,269.0>>/L<<667.0,269.0>--<1065.0,269.0>> = 10.08059798754231
	* Icircumflex (U+00CE): B<<465.0,1151.0>-<487.0,1178.0>-<532.0,1185.0>>/L<<532.0,1185.0>--<135.0,1185.0>> = 8.84181456019167 and 138 more.

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
 * a (U+0061): L<<758.0,0.0>--<760.0,255.0>> and 91 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[17] SplineSansMono-Medium.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check METADATA.pb includes production subsets.</summary><div>
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
* ⚠ **WARN** The stylistic set ss12 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss14 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss15 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss16 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss17 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss18 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss19 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table.</summary><div>
* [com.google.fonts/check/meta/script_lang_tags](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags)

* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs</summary><div>
* [com.google.fonts/check/unreachable_glyphs](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs)

* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:
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
	- Glyph name: Eth	Contours detected: 3	Expected: 2
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: Dcroat	Contours detected: 3	Expected: 2
	- Glyph name: Lslash	Contours detected: 2	Expected: 1
	- Glyph name: lslash	Contours detected: 2	Expected: 1 
	- And 16 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks.</summary><div>
* [com.google.fonts/check/dotted_circle](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle)

* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata.</summary><div>
* [com.google.fonts/check/monospace](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/name.html#com.google.fonts/check/monospace)

* ⚠ **WARN** Font is monospaced but 7 glyphs (1.26%) have a different width. You should check the widths of: ['plus.alt', 'equal.alt', 'greaterarrow', 'exclamequal', 'lessergreater', 'greatergreaterarrow', 'equalequalarrow'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points?</summary><div>
* [com.google.fonts/check/outline_alignment_miss](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss)

* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* dollar (U+0024): X=718.0,Y=1452.0 (should be at cap-height 1454?)
	* U (U+0055): X=115.0,Y=1456.0 (should be at cap-height 1454?)
	* U (U+0055): X=339.0,Y=1456.0 (should be at cap-height 1454?)
	* f (U+0066): X=210.0,Y=1092.0 (should be at x-height 1091?)
	* f (U+0066): X=451.0,Y=1092.0 (should be at x-height 1091?)
	* f (U+0066): X=664.0,Y=1092.0 (should be at x-height 1091?)
	* f (U+0066): X=1007.0,Y=1092.0 (should be at x-height 1091?)
	* g (U+0067): X=771.0,Y=1090.0 (should be at x-height 1091?)
	* g (U+0067): X=347.0,Y=1.5 (should be at baseline 0?)
	* j (U+006A): X=284.0,Y=1092.0 (should be at x-height 1091?) and 58 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short?</summary><div>
* [com.google.fonts/check/outline_short_segments](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments)

* ⚠ **WARN** The following glyphs have segments which seem very short:
	* less (U+003C) contains a short segment L<<346.0,744.0>--<346.0,740.0>>
	* greater (U+003E) contains a short segment L<<854.0,740.0>--<854.0,744.0>>
	* at (U+0040) contains a short segment B<<721.0,358.0>-<723.0,371.0>-<726.5,404.5>>
	* A (U+0041) contains a short segment L<<604.0,1284.0>--<596.0,1284.0>>
	* M (U+004D) contains a short segment L<<599.0,633.0>--<603.0,633.0>>
	* M (U+004D) contains a short segment L<<921.0,1274.0>--<905.0,1274.0>>
	* M (U+004D) contains a short segment L<<293.0,1274.0>--<277.0,1274.0>>
	* N (U+004E) contains a short segment L<<881.0,266.0>--<889.0,266.0>>
	* N (U+004E) contains a short segment L<<326.0,1174.0>--<318.0,1174.0>>
	* V (U+0056) contains a short segment L<<592.0,210.0>--<608.0,210.0>> and 86 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments?</summary><div>
* [com.google.fonts/check/outline_jaggy_segments](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments)

* ⚠ **WARN** The following glyphs have jaggy segments:
	* B (U+0042): B<<988.0,872.5>-<920.0,782.0>-<817.0,761.0>>/B<<817.0,761.0>-<893.0,758.0>-<965.0,722.0>> = 13.784223615038577
	* Thorn (U+00DE): B<<396.5,272.5>-<377.0,286.0>-<373.0,305.0>>/L<<373.0,305.0>--<373.0,0.0>> = 11.888658039627968
	* ae (U+00E6): B<<721.0,839.0>-<684.0,758.0>-<680.0,604.0>>/B<<680.0,604.0>-<685.0,645.0>-<708.0,660.5>> = 5.465089939346022
	* aeacute (U+01FD): B<<721.0,839.0>-<684.0,758.0>-<680.0,604.0>>/B<<680.0,604.0>-<685.0,645.0>-<708.0,660.5>> = 5.465089939346022
	* b (U+0062): L<<393.0,1068.0>--<393.0,864.0>>/B<<393.0,864.0>-<404.0,931.0>-<449.5,987.5>> = 9.323591778137999
	* braceleft (U+007B): B<<674.0,797.5>-<612.0,736.0>-<424.0,713.0>>/B<<424.0,713.0>-<616.0,690.0>-<674.5,631.5>> = 13.805935465347666
	* braceright (U+007D): B<<525.5,631.5>-<584.0,690.0>-<776.0,713.0>>/B<<776.0,713.0>-<588.0,736.0>-<526.5,797.5>> = 13.805935465347666
	* comma (U+002C): B<<604.5,-44.0>-<617.0,-15.0>-<678.0,0.0>>/L<<678.0,0.0>--<474.0,0.0>> = 13.81502534126161
	* d (U+0064): L<<821.0,0.0>--<819.0,243.0>>/B<<819.0,243.0>-<810.0,175.0>-<766.5,117.0>> = 8.011004693585441
	* dcaron (U+010F): L<<821.0,0.0>--<819.0,243.0>>/B<<819.0,243.0>-<810.0,175.0>-<766.5,117.0>> = 8.011004693585441 and 87 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines?</summary><div>
* [com.google.fonts/check/outline_semi_vertical](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical)

* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * Amacron (U+0100): L<<281.0,1811.0>--<921.0,1812.0>>
 * Amacron (U+0100): L<<918.0,1608.0>--<281.0,1607.0>>
 * Ccedilla (U+00C7): L<<480.0,-422.0>--<481.0,-260.0>>
 * Emacron (U+0112): L<<278.0,1811.0>--<918.0,1812.0>>
 * Emacron (U+0112): L<<915.0,1608.0>--<278.0,1607.0>>
 * G (U+0047): L<<1077.0,770.0>--<1075.0,155.0>>
 * Gbreve (U+011E): L<<1077.0,770.0>--<1075.0,155.0>>
 * Gcaron (U+01E6): L<<1077.0,770.0>--<1075.0,155.0>>
 * Gdotaccent (U+0120): L<<1077.0,770.0>--<1075.0,155.0>>
 * Hbar (U+0126): L<<1219.0,1093.0>--<1218.0,897.0>> and 79 more.

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
* ⚠ **WARN** The stylistic set ss12 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss14 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss15 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss16 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss17 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss18 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss19 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table.</summary><div>
* [com.google.fonts/check/meta/script_lang_tags](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags)

* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs</summary><div>
* [com.google.fonts/check/unreachable_glyphs](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs)

* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:
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
	- Glyph name: Eth	Contours detected: 3	Expected: 2
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: Dcroat	Contours detected: 3	Expected: 2
	- Glyph name: Lslash	Contours detected: 2	Expected: 1
	- Glyph name: lslash	Contours detected: 2	Expected: 1 
	- And 16 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks.</summary><div>
* [com.google.fonts/check/dotted_circle](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle)

* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata.</summary><div>
* [com.google.fonts/check/monospace](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/name.html#com.google.fonts/check/monospace)

* ⚠ **WARN** Font is monospaced but 8 glyphs (1.44%) have a different width. You should check the widths of: ['uni2155.ss18', 'plus.alt', 'equal.alt', 'greaterarrow', 'exclamequal', 'lessergreater', 'greatergreaterarrow', 'equalequalarrow'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points?</summary><div>
* [com.google.fonts/check/outline_alignment_miss](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss)

* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* dollar (U+0024): X=537.0,Y=1452.0 (should be at cap-height 1454?)
	* dollar (U+0024): X=706.0,Y=1452.0 (should be at cap-height 1454?)
	* parenleft (U+0028): X=488.5,Y=-1.0 (should be at baseline 0?)
	* parenright (U+0029): X=752.5,Y=-1.0 (should be at baseline 0?)
	* question (U+003F): X=1051.0,Y=1453.0 (should be at cap-height 1454?)
	* U (U+0055): X=115.0,Y=1456.0 (should be at cap-height 1454?)
	* U (U+0055): X=302.0,Y=1456.0 (should be at cap-height 1454?)
	* f (U+0066): X=214.0,Y=1092.0 (should be at x-height 1091?)
	* f (U+0066): X=454.0,Y=1092.0 (should be at x-height 1091?)
	* f (U+0066): X=634.0,Y=1092.0 (should be at x-height 1091?) and 72 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short?</summary><div>
* [com.google.fonts/check/outline_short_segments](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments)

* ⚠ **WARN** The following glyphs have segments which seem very short:
	* less (U+003C) contains a short segment L<<323.0,734.0>--<323.0,729.0>>
	* greater (U+003E) contains a short segment L<<877.0,729.0>--<877.0,734.0>>
	* at (U+0040) contains a short segment B<<721.0,364.0>-<723.0,382.0>-<726.0,412.5>>
	* A (U+0041) contains a short segment L<<603.0,1319.0>--<597.0,1319.0>>
	* M (U+004D) contains a short segment L<<600.0,612.0>--<603.0,612.0>>
	* M (U+004D) contains a short segment L<<935.0,1308.0>--<923.0,1308.0>>
	* M (U+004D) contains a short segment L<<277.0,1308.0>--<264.0,1308.0>>
	* N (U+004E) contains a short segment L<<907.0,196.0>--<914.0,196.0>>
	* N (U+004E) contains a short segment L<<298.0,1249.0>--<290.0,1249.0>>
	* V (U+0056) contains a short segment L<<594.0,178.0>--<607.0,178.0>> and 89 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments?</summary><div>
* [com.google.fonts/check/outline_jaggy_segments](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments)

* ⚠ **WARN** The following glyphs have jaggy segments:
	* B (U+0042): B<<991.5,874.5>-<922.0,787.0>-<814.0,766.0>>/B<<814.0,766.0>-<891.0,764.0>-<964.0,727.5>> = 12.491408380577253
	* P (U+0050): B<<368.5,542.0>-<349.0,557.0>-<345.0,583.0>>/L<<345.0,583.0>--<345.0,0.0>> = 8.746162262555211
	* Thorn (U+00DE): B<<368.0,282.5>-<348.0,296.0>-<344.0,314.0>>/L<<344.0,314.0>--<344.0,0.0>> = 12.528807709151492
	* ae (U+00E6): B<<713.5,855.5>-<669.0,762.0>-<664.0,589.0>>/B<<664.0,589.0>-<669.0,627.0>-<689.5,642.0>> = 5.8403711006105095
	* aeacute (U+01FD): B<<713.5,855.5>-<669.0,762.0>-<664.0,589.0>>/B<<664.0,589.0>-<669.0,627.0>-<689.5,642.0>> = 5.8403711006105095
	* b (U+0062): L<<362.0,1556.0>--<362.0,859.0>>/B<<362.0,859.0>-<375.0,932.0>-<423.5,989.5>> = 10.09750438407527
	* comma (U+002C): B<<603.5,-44.5>-<616.0,-13.0>-<675.0,0.0>>/L<<675.0,0.0>--<487.0,0.0>> = 12.425942865427485
	* d (U+0064): L<<850.0,0.0>--<849.0,244.0>>/B<<849.0,244.0>-<836.0,170.0>-<791.5,112.0>> = 10.198621643700793
	* dcaron (U+010F): L<<850.0,0.0>--<849.0,244.0>>/B<<849.0,244.0>-<836.0,170.0>-<791.5,112.0>> = 10.198621643700793
	* dcroat (U+0111): L<<850.0,0.0>--<849.0,244.0>>/B<<849.0,244.0>-<836.0,170.0>-<791.5,112.0>> = 10.198621643700793 and 93 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines?</summary><div>
* [com.google.fonts/check/outline_semi_vertical](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical)

* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * Amacron (U+0100): L<<289.0,1784.0>--<913.0,1785.0>>
 * Ccedilla (U+00C7): L<<476.0,-406.0>--<477.0,-262.0>>
 * Emacron (U+0112): L<<297.0,1784.0>--<921.0,1785.0>>
 * Eng (U+014A): L<<316.0,887.0>--<315.0,0.0>>
 * G (U+0047): L<<1077.0,757.0>--<1075.0,148.0>>
 * Gbreve (U+011E): L<<1077.0,757.0>--<1075.0,148.0>>
 * Gcaron (U+01E6): L<<1077.0,757.0>--<1075.0,148.0>>
 * Gdotaccent (U+0120): L<<1077.0,757.0>--<1075.0,148.0>>
 * Imacron (U+012A): L<<288.0,1784.0>--<912.0,1785.0>>
 * Lslash (U+0141): L<<24.0,606.0>--<23.0,796.0>> and 92 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[14] SplineSansMono-Italic.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check METADATA.pb includes production subsets.</summary><div>
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
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description.</summary><div>
* [com.google.fonts/check/stylisticset_description](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description)

* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss08 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss09 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss10 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss11 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss12 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss14 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss15 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss16 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss17 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss18 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss19 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table.</summary><div>
* [com.google.fonts/check/meta/script_lang_tags](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags)

* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs</summary><div>
* [com.google.fonts/check/unreachable_glyphs](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs)

* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:
	- commaturnedabove
	- uni2154.ss19
	- IJ_acutecomb
	- ij_acutecomb
	- uni2159.ss19
	- .null 
	- And uni2153.ss19
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
	- Glyph name: Eth	Contours detected: 3	Expected: 2
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: Dcroat	Contours detected: 3	Expected: 2
	- Glyph name: dcroat	Contours detected: 3	Expected: 2
	- Glyph name: eogonek	Contours detected: 3	Expected: 2 
	- And 23 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks.</summary><div>
* [com.google.fonts/check/dotted_circle](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle)

* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata.</summary><div>
* [com.google.fonts/check/monospace](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/name.html#com.google.fonts/check/monospace)

* ⚠ **WARN** Font is monospaced but 18 glyphs (2.87%) have a different width. You should check the widths of: ['a', 'aacute', 'abreve', 'acircumflex', 'adieresis', 'agrave', 'amacron', 'aogonek', 'aring', 'aringacute', 'atilde', 'plus.alt', 'equal.alt', 'greaterarrow', 'exclamequal', 'lessergreater', 'greatergreaterarrow', 'equalequalarrow'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points?</summary><div>
* [com.google.fonts/check/outline_alignment_miss](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss)

* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* dollar (U+0024): X=636.0,Y=1452.0 (should be at cap-height 1454?)
	* dollar (U+0024): X=805.0,Y=1452.0 (should be at cap-height 1454?)
	* U (U+0055): X=232.0,Y=1456.0 (should be at cap-height 1454?)
	* U (U+0055): X=418.0,Y=1456.0 (should be at cap-height 1454?)
	* f (U+0066): X=239.0,Y=1092.0 (should be at x-height 1091?)
	* f (U+0066): X=509.0,Y=1092.0 (should be at x-height 1091?)
	* f (U+0066): X=691.0,Y=1092.0 (should be at x-height 1091?)
	* f (U+0066): X=1063.0,Y=1092.0 (should be at x-height 1091?)
	* i (U+0069): X=911.5,Y=0.5 (should be at baseline 0?)
	* j (U+006A): X=998.0,Y=1456.0 (should be at cap-height 1454?) and 87 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments?</summary><div>
* [com.google.fonts/check/outline_jaggy_segments](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments)

* ⚠ **WARN** The following glyphs have jaggy segments:
	* B (U+0042): B<<973.5,836.5>-<907.0,782.0>-<820.0,766.0>>/B<<820.0,766.0>-<887.0,764.0>-<952.5,733.5>> = 12.130526440935991
	* P (U+0050): B<<420.0,527.0>-<359.0,527.0>-<356.0,582.0>>/L<<356.0,582.0>--<284.0,0.0>> = 10.174436469956868
	* a (U+0061): L<<792.0,383.0>--<801.0,446.0>>/B<<801.0,446.0>-<747.0,229.0>-<632.5,108.5>> = 5.843998210249424
	* aacute (U+00E1): L<<792.0,383.0>--<801.0,446.0>>/B<<801.0,446.0>-<747.0,229.0>-<632.5,108.5>> = 5.843998210249424
	* abreve (U+0103): L<<792.0,383.0>--<801.0,446.0>>/B<<801.0,446.0>-<747.0,229.0>-<632.5,108.5>> = 5.843998210249424
	* acircumflex (U+00E2): L<<792.0,383.0>--<801.0,446.0>>/B<<801.0,446.0>-<747.0,229.0>-<632.5,108.5>> = 5.843998210249424
	* adieresis (U+00E4): L<<792.0,383.0>--<801.0,446.0>>/B<<801.0,446.0>-<747.0,229.0>-<632.5,108.5>> = 5.843998210249424
	* ae (U+00E6): B<<767.0,854.5>-<704.0,757.0>-<670.0,589.0>>/B<<670.0,589.0>-<694.0,657.0>-<771.0,657.0>> = 7.998990959408728
	* ae (U+00E6): L<<434.0,0.0>--<489.0,355.0>>/B<<489.0,355.0>-<434.0,194.0>-<347.0,91.0>> = 10.054139205129857
	* aeacute (U+01FD): B<<767.0,854.5>-<704.0,757.0>-<670.0,589.0>>/B<<670.0,589.0>-<694.0,657.0>-<771.0,657.0>> = 7.998990959408728 and 138 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[16] SplineSansMono-Light.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check METADATA.pb includes production subsets.</summary><div>
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
* ⚠ **WARN** The stylistic set ss12 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss14 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss15 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss16 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss17 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss18 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss19 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table.</summary><div>
* [com.google.fonts/check/meta/script_lang_tags](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags)

* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs</summary><div>
* [com.google.fonts/check/unreachable_glyphs](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs)

* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:
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
	- Glyph name: Eth	Contours detected: 3	Expected: 2
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: Dcroat	Contours detected: 3	Expected: 2
	- Glyph name: Lslash	Contours detected: 2	Expected: 1
	- Glyph name: lslash	Contours detected: 2	Expected: 1 
	- And 16 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks.</summary><div>
* [com.google.fonts/check/dotted_circle](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle)

* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata.</summary><div>
* [com.google.fonts/check/monospace](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/name.html#com.google.fonts/check/monospace)

* ⚠ **WARN** Font is monospaced but 8 glyphs (1.44%) have a different width. You should check the widths of: ['uni2155.ss18', 'plus.alt', 'equal.alt', 'greaterarrow', 'exclamequal', 'lessergreater', 'greatergreaterarrow', 'equalequalarrow'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points?</summary><div>
* [com.google.fonts/check/outline_alignment_miss](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss)

* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* dollar (U+0024): X=560.0,Y=1452.0 (should be at cap-height 1454?)
	* dollar (U+0024): X=685.0,Y=1452.0 (should be at cap-height 1454?)
	* six (U+0036): X=780.0,Y=-0.5 (should be at baseline 0?)
	* nine (U+0039): X=418.0,Y=1455.0 (should be at cap-height 1454?)
	* J (U+004A): X=356.5,Y=2.0 (should be at baseline 0?)
	* U (U+0055): X=115.0,Y=1456.0 (should be at cap-height 1454?)
	* U (U+0055): X=240.0,Y=1456.0 (should be at cap-height 1454?)
	* f (U+0066): X=220.0,Y=1092.0 (should be at x-height 1091?)
	* f (U+0066): X=460.0,Y=1092.0 (should be at x-height 1091?)
	* f (U+0066): X=584.0,Y=1092.0 (should be at x-height 1091?) and 51 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments?</summary><div>
* [com.google.fonts/check/outline_jaggy_segments](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments)

* ⚠ **WARN** The following glyphs have jaggy segments:
	* B (U+0042): B<<996.5,879.0>-<925.0,796.0>-<808.0,773.0>>/B<<808.0,773.0>-<889.0,772.0>-<963.0,735.5>> = 11.828779563434608
	* OE (U+0152): L<<658.0,0.0>--<657.0,266.0>>/B<<657.0,266.0>-<629.0,143.0>-<557.0,61.5>> = 13.03979475484222
	* P (U+0050): B<<320.0,587.0>-<300.0,600.0>-<296.0,618.0>>/L<<296.0,618.0>--<296.0,0.0>> = 12.528807709151492
	* Thorn (U+00DE): B<<320.0,299.5>-<300.0,313.0>-<296.0,330.0>>/L<<296.0,330.0>--<296.0,0.0>> = 13.240519915187184
	* ae (U+00E6): B<<700.5,883.5>-<644.0,769.0>-<638.0,563.0>>/B<<638.0,563.0>-<648.0,625.0>-<706.0,625.0>> = 7.494009597428414
	* aeacute (U+01FD): B<<700.5,883.5>-<644.0,769.0>-<638.0,563.0>>/B<<638.0,563.0>-<648.0,625.0>-<706.0,625.0>> = 7.494009597428414
	* b (U+0062): L<<309.0,1556.0>--<309.0,849.0>>/B<<309.0,849.0>-<325.0,934.0>-<378.5,992.5>> = 10.66034829453532
	* comma (U+002C): B<<601.5,-45.5>-<615.0,-10.0>-<671.0,0.0>>/L<<671.0,0.0>--<509.0,0.0>> = 10.124671655397806
	* d (U+0064): L<<899.0,0.0>--<899.0,251.0>>/B<<899.0,251.0>-<876.0,124.0>-<785.5,56.0>> = 10.265140460213706
	* dcaron (U+010F): L<<899.0,0.0>--<899.0,251.0>>/B<<899.0,251.0>-<876.0,124.0>-<785.5,56.0>> = 10.265140460213706 and 83 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines?</summary><div>
* [com.google.fonts/check/outline_semi_vertical](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical)

* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * Aogonek (U+0104): L<<1052.0,1.0>--<1175.0,0.0>>
 * Aogonek (U+0104): L<<1172.0,-251.0>--<1173.0,-367.0>>
 * Eng (U+014A): L<<1060.0,1454.0>--<1059.0,0.0>>
 * Eng (U+014A): L<<263.0,949.0>--<262.0,0.0>>
 * Eogonek (U+0118): L<<1067.0,-251.0>--<1068.0,-367.0>>
 * Eogonek (U+0118): L<<947.0,1.0>--<1070.0,0.0>>
 * G (U+0047): L<<1077.0,734.0>--<1075.0,135.0>>
 * G (U+0047): L<<950.0,200.0>--<952.0,611.0>>
 * Gbreve (U+011E): L<<1077.0,734.0>--<1075.0,135.0>>
 * Gbreve (U+011E): L<<950.0,200.0>--<952.0,611.0>> and 66 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] SplineSansMono-SemiBoldItalic.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check METADATA.pb includes production subsets.</summary><div>
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
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters.</summary><div>
* [com.google.fonts/check/name/family_and_style_max_length](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length)

* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Spline Sans Mono SemiBold' / SUBFAMILY_NAME = 'Italic'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description.</summary><div>
* [com.google.fonts/check/stylisticset_description](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description)

* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss08 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss09 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss10 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss11 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss12 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss14 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss15 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss16 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss17 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss18 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss19 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table.</summary><div>
* [com.google.fonts/check/meta/script_lang_tags](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags)

* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs</summary><div>
* [com.google.fonts/check/unreachable_glyphs](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs)

* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:
	- commaturnedabove
	- uni2154.ss19
	- IJ_acutecomb
	- ij_acutecomb
	- uni2159.ss19
	- .null 
	- And uni2153.ss19
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
	- Glyph name: Eth	Contours detected: 3	Expected: 2
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: Dcroat	Contours detected: 3	Expected: 2
	- Glyph name: dcroat	Contours detected: 3	Expected: 2
	- Glyph name: eogonek	Contours detected: 3	Expected: 2 
	- And 23 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks.</summary><div>
* [com.google.fonts/check/dotted_circle](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle)

* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata.</summary><div>
* [com.google.fonts/check/monospace](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/name.html#com.google.fonts/check/monospace)

* ⚠ **WARN** Font is monospaced but 7 glyphs (1.12%) have a different width. You should check the widths of: ['plus.alt', 'equal.alt', 'greaterarrow', 'exclamequal', 'lessergreater', 'greatergreaterarrow', 'equalequalarrow'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points?</summary><div>
* [com.google.fonts/check/outline_alignment_miss](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss)

* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* U (U+0055): X=208.0,Y=1456.0 (should be at cap-height 1454?)
	* U (U+0055): X=485.0,Y=1456.0 (should be at cap-height 1454?)
	* a (U+0061): X=1009.5,Y=1089.0 (should be at x-height 1091?)
	* f (U+0066): X=222.0,Y=1092.0 (should be at x-height 1091?)
	* f (U+0066): X=473.0,Y=1092.0 (should be at x-height 1091?)
	* f (U+0066): X=741.0,Y=1092.0 (should be at x-height 1091?)
	* f (U+0066): X=1089.0,Y=1092.0 (should be at x-height 1091?)
	* j (U+006A): X=279.0,Y=1092.0 (should be at x-height 1091?)
	* j (U+006A): X=941.0,Y=1092.0 (should be at x-height 1091?)
	* m (U+006D): X=129.0,Y=1092.0 (should be at x-height 1091?) and 87 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short?</summary><div>
* [com.google.fonts/check/outline_short_segments](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments)

* ⚠ **WARN** The following glyphs have segments which seem very short:
	* two (U+0032) contains a short segment B<<402.0,972.0>-<401.0,950.0>-<402.0,931.0>>
	* two (U+0032) contains a short segment B<<141.0,931.0>-<141.0,939.0>-<140.0,948.5>>
	* two (U+0032) contains a short segment B<<140.0,948.5>-<139.0,958.0>-<139.0,968.0>>
	* less (U+003C) contains a short segment L<<438.0,691.0>--<438.0,686.0>>
	* greater (U+003E) contains a short segment L<<808.0,706.0>--<809.0,711.0>>
	* at (U+0040) contains a short segment B<<709.0,343.0>-<712.0,357.0>-<721.5,395.0>>
	* at (U+0040) contains a short segment B<<790.0,986.0>-<825.0,972.0>-<846.0,954.0>>
	* at (U+0040) contains a short segment B<<858.5,378.5>-<853.0,351.0>-<853.0,349.0>>
	* at (U+0040) contains a short segment B<<853.0,349.0>-<852.0,313.0>-<854.0,296.5>>
	* at (U+0040) contains a short segment B<<854.0,296.5>-<856.0,280.0>-<871.0,280.0>> and 77 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments?</summary><div>
* [com.google.fonts/check/outline_jaggy_segments](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments)

* ⚠ **WARN** The following glyphs have jaggy segments:
	* B (U+0042): B<<975.5,840.0>-<908.0,789.0>-<821.0,778.0>>/B<<821.0,778.0>-<951.0,767.0>-<1032.5,693.5>> = 12.042640447118545
	* I (U+0049): B<<584.5,1178.0>-<606.0,1203.0>-<644.0,1211.0>>/L<<644.0,1211.0>--<252.0,1211.0>> = 11.888658039627968
	* I (U+0049): B<<743.0,349.0>-<732.0,259.0>-<655.0,243.0>>/L<<655.0,243.0>--<1048.0,243.0>> = 11.73857120672233
	* IJ (U+0132): B<<312.0,1170.5>-<334.0,1195.0>-<371.0,1203.0>>/L<<371.0,1203.0>--<127.0,1203.0>> = 12.200468727380786
	* IJ (U+0132): B<<536.0,910.0>-<525.0,820.0>-<449.0,805.0>>/L<<449.0,805.0>--<688.0,805.0>> = 11.164880177548593
	* Iacute (U+00CD): B<<584.5,1178.0>-<606.0,1203.0>-<644.0,1211.0>>/L<<644.0,1211.0>--<252.0,1211.0>> = 11.888658039627968
	* Iacute (U+00CD): B<<743.0,349.0>-<732.0,259.0>-<655.0,243.0>>/L<<655.0,243.0>--<1048.0,243.0>> = 11.73857120672233
	* Ibreve (U+012C): B<<584.5,1178.0>-<606.0,1203.0>-<644.0,1211.0>>/L<<644.0,1211.0>--<252.0,1211.0>> = 11.888658039627968
	* Ibreve (U+012C): B<<743.0,349.0>-<732.0,259.0>-<655.0,243.0>>/L<<655.0,243.0>--<1048.0,243.0>> = 11.73857120672233
	* Icircumflex (U+00CE): B<<584.5,1178.0>-<606.0,1203.0>-<644.0,1211.0>>/L<<644.0,1211.0>--<252.0,1211.0>> = 11.888658039627968 and 157 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[15] SplineSansMono-MediumItalic.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check METADATA.pb includes production subsets.</summary><div>
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
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters.</summary><div>
* [com.google.fonts/check/name/family_and_style_max_length](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length)

* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Spline Sans Mono Medium' / SUBFAMILY_NAME = 'Italic'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description.</summary><div>
* [com.google.fonts/check/stylisticset_description](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description)

* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss08 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss09 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss10 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss11 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss12 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss14 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss15 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss16 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss17 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss18 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss19 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table.</summary><div>
* [com.google.fonts/check/meta/script_lang_tags](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags)

* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs</summary><div>
* [com.google.fonts/check/unreachable_glyphs](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs)

* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:
	- commaturnedabove
	- uni2154.ss19
	- IJ_acutecomb
	- ij_acutecomb
	- uni2159.ss19
	- .null 
	- And uni2153.ss19
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
	- Glyph name: Eth	Contours detected: 3	Expected: 2
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: Dcroat	Contours detected: 3	Expected: 2
	- Glyph name: dcroat	Contours detected: 3	Expected: 2
	- Glyph name: eogonek	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks.</summary><div>
* [com.google.fonts/check/dotted_circle](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle)

* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata.</summary><div>
* [com.google.fonts/check/monospace](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/name.html#com.google.fonts/check/monospace)

* ⚠ **WARN** Font is monospaced but 7 glyphs (1.12%) have a different width. You should check the widths of: ['plus.alt', 'equal.alt', 'greaterarrow', 'exclamequal', 'lessergreater', 'greatergreaterarrow', 'equalequalarrow'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points?</summary><div>
* [com.google.fonts/check/outline_alignment_miss](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss)

* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* dollar (U+0024): X=823.0,Y=1452.0 (should be at cap-height 1454?)
	* U (U+0055): X=233.0,Y=1456.0 (should be at cap-height 1454?)
	* U (U+0055): X=457.0,Y=1456.0 (should be at cap-height 1454?)
	* f (U+0066): X=227.0,Y=1092.0 (should be at x-height 1091?)
	* f (U+0066): X=486.0,Y=1092.0 (should be at x-height 1091?)
	* f (U+0066): X=702.0,Y=1092.0 (should be at x-height 1091?)
	* f (U+0066): X=1062.0,Y=1092.0 (should be at x-height 1091?)
	* j (U+006A): X=290.0,Y=1092.0 (should be at x-height 1091?)
	* j (U+006A): X=934.0,Y=1092.0 (should be at x-height 1091?)
	* p (U+0070): X=217.0,Y=1092.0 (should be at x-height 1091?) and 65 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments?</summary><div>
* [com.google.fonts/check/outline_jaggy_segments](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments)

* ⚠ **WARN** The following glyphs have jaggy segments:
	* B (U+0042): B<<970.0,833.0>-<906.0,777.0>-<824.0,761.0>>/B<<824.0,761.0>-<891.0,759.0>-<954.5,728.5>> = 12.75075422446524
	* P (U+0050): B<<407.0,514.0>-<390.0,530.0>-<389.0,561.0>>/L<<389.0,561.0>--<319.0,0.0>> = 8.960056237846423
	* a (U+0061): L<<722.0,0.0>--<769.0,420.0>>/B<<769.0,420.0>-<713.0,210.0>-<608.5,99.0>> = 8.546311059786886
	* aacute (U+00E1): L<<722.0,0.0>--<769.0,420.0>>/B<<769.0,420.0>-<713.0,210.0>-<608.5,99.0>> = 8.546311059786886
	* abreve (U+0103): L<<722.0,0.0>--<769.0,420.0>>/B<<769.0,420.0>-<713.0,210.0>-<608.5,99.0>> = 8.546311059786886
	* acircumflex (U+00E2): L<<722.0,0.0>--<769.0,420.0>>/B<<769.0,420.0>-<713.0,210.0>-<608.5,99.0>> = 8.546311059786886
	* adieresis (U+00E4): L<<722.0,0.0>--<769.0,420.0>>/B<<769.0,420.0>-<713.0,210.0>-<608.5,99.0>> = 8.546311059786886
	* ae (U+00E6): B<<772.0,839.0>-<720.0,753.0>-<689.0,604.0>>/B<<689.0,604.0>-<703.0,645.0>-<729.0,660.5>> = 7.100226513754948
	* ae (U+00E6): L<<432.0,0.0>--<485.0,354.0>>/B<<485.0,354.0>-<425.0,184.0>-<339.5,86.0>> = 10.925098967656218
	* aeacute (U+01FD): B<<772.0,839.0>-<720.0,753.0>-<689.0,604.0>>/B<<689.0,604.0>-<703.0,645.0>-<729.0,660.5>> = 7.100226513754948 and 120 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 60 | 0 | 96 | 998 | 61 | 871 | 0 |
| 3% | 0% | 5% | 48% | 3% | 42% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
