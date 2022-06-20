## Fontbakery report

Fontbakery version: 0.8.9

<details><summary><b>[1] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoSansCanadianAboriginal/googlefonts/slim-variable-ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/variable-ttf'] [code: single-directory]
</div></details><br></div></details><details><summary><b>[18] NotoSansCanadianAboriginal[wght].ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table set to optimize rendering? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/gasp">com.google.fonts/check/gasp</a>)</summary><div>


* 🔥 **FAIL** Font is missing the 'gasp' table. Try exporting the font with autohinting enabled.
If you are dealing with an unhinted font, it can be fixed by running the fonts through the command 'gftools fix-nonhinting'
GFTools is available at https://pypi.org/project/gftools/ [code: lacks-gasp]
</div></details><details><summary>🔥 <b>FAIL:</b> Font enables smart dropout control in "prep" table instructions? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/smart_dropout">com.google.fonts/check/smart_dropout</a>)</summary><div>


* 🔥 **FAIL** The 'prep' table does not contain TrueType instructions enabling smart dropout control. To fix, export the font with autohinting enabled, or run ttfautohint on the font, or run the `gftools fix-nonhinting` script. [code: lacks-smart-dropout]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansCanadianAboriginal/googlefonts/slim-variable-ttf/NotoSansCanadianAboriginal[wght].ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Black.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Bold.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-ExtraBold.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-ExtraLight.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Light.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Medium.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Regular.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-SemiBold.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Thin.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/variable-ttf/NotoSansCanadianAboriginal[wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansCanadianAboriginal/googlefonts/slim-variable-ttf/NotoSansCanadianAboriginal[wght].ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Black.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Bold.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-ExtraBold.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-ExtraLight.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Light.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Medium.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Regular.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-SemiBold.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Thin.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/variable-ttf/NotoSansCanadianAboriginal[wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to either 2 or 17, and its postScriptNameID value is set to 6. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.adobe.fonts/check/varfont/valid_default_instance_nameids">com.adobe.fonts/check/varfont/valid_default_instance_nameids</a>)</summary><div>


* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 260. [code: invalid-default-instance-subfamily-nameid:260]
* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its postScriptNameID should be 6, instead of 269. [code: invalid-default-instance-postscript-nameid:269]
</div></details><details><summary>🔥 <b>FAIL:</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to either 2 or 17, and its postScriptNameID value is set to 6. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.adobe.fonts/check/varfont/valid_default_instance_nameids">com.adobe.fonts/check/varfont/valid_default_instance_nameids</a>)</summary><div>


* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 278. [code: invalid-default-instance-subfamily-nameid:278]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Canadian Aboriginal' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Canadian Aboriginal' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1

	- uni0307.1 

	- And g726
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1

	- uni0307.1 

	- And g726
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><br></div></details><details><summary><b>[12] NotoSansCanadianAboriginal-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansCanadianAboriginal/googlefonts/slim-variable-ttf/NotoSansCanadianAboriginal[wght].ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Black.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Bold.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-ExtraBold.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-ExtraLight.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Light.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Medium.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Regular.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-SemiBold.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Thin.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/variable-ttf/NotoSansCanadianAboriginal[wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni1600
	* uni162D
	* uni1653
	* uni1630
	* uni167C
	* uni15A7
	* uni1602
	* uni161D
	* uni1614
	* uni1654 and 207 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Canadian Aboriginal Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1 

	- And uni0307.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni166A (U+166A): L<<415.0,305.0>--<412.0,305.0>> -> L<<412.0,305.0>--<367.0,305.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<339.5,236.0>-<346.0,204.0>-<347.0,184.0>>/B<<347.0,184.0>-<349.0,204.0>-<354.5,235.5>> = 8.57299836361137

	* W (U+0057): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* W (U+0057): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* W (U+0057): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* Wacute (U+1E82): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wacute (U+1E82): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wacute (U+1E82): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* Wcircumflex (U+0174): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wcircumflex (U+0174): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wcircumflex (U+0174): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432 

	* And 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni15D6 (U+15D6): L<<380.0,562.0>--<379.0,714.0>>

	* uni15D6 (U+15D6): L<<382.0,335.0>--<381.0,481.0>>

	* uni15D6 (U+15D6): L<<476.0,481.0>--<475.0,337.0>>

	* uni15D6 (U+15D6): L<<478.0,714.0>--<477.0,562.0>>

	* uni15D7 (U+15D7): L<<379.0,0.0>--<380.0,152.0>>

	* uni15D7 (U+15D7): L<<381.0,233.0>--<382.0,379.0>>

	* uni15D7 (U+15D7): L<<475.0,377.0>--<476.0,233.0>> 

	* And uni15D7 (U+15D7): L<<477.0,152.0>--<478.0,0.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] NotoSansCanadianAboriginal-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table set to optimize rendering? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/gasp">com.google.fonts/check/gasp</a>)</summary><div>


* 🔥 **FAIL** Font is missing the 'gasp' table. Try exporting the font with autohinting enabled.
If you are dealing with an unhinted font, it can be fixed by running the fonts through the command 'gftools fix-nonhinting'
GFTools is available at https://pypi.org/project/gftools/ [code: lacks-gasp]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: FONT_FAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/familyname">com.google.fonts/check/name/familyname</a>)</summary><div>


* 🔥 **FAIL** Entry [FONT_FAMILY_NAME(1):WINDOWS(3)] on the "name" table: Expected "Noto Sans Canadian Aboriginal" but got "Noto Sans CanAborig". [code: mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: TYPOGRAPHIC_FAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/typographicfamilyname">com.google.fonts/check/name/typographicfamilyname</a>)</summary><div>


* 🔥 **FAIL** Font style is "Bold" and, for that reason, it is not expected to have a [TYPOGRAPHIC_FAMILY_NAME(16):WINDOWS(3)] entry! [code: ribbi]
</div></details><details><summary>🔥 <b>FAIL:</b> Font enables smart dropout control in "prep" table instructions? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/smart_dropout">com.google.fonts/check/smart_dropout</a>)</summary><div>


* 🔥 **FAIL** The 'prep' table does not contain TrueType instructions enabling smart dropout control. To fix, export the font with autohinting enabled, or run ttfautohint on the font, or run the `gftools fix-nonhinting` script. [code: lacks-smart-dropout]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansCanadianAboriginal/googlefonts/slim-variable-ttf/NotoSansCanadianAboriginal[wght].ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Black.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Bold.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-ExtraBold.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-ExtraLight.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Light.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Medium.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Regular.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-SemiBold.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Thin.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/variable-ttf/NotoSansCanadianAboriginal[wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Does full font name begin with the font family name? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/name/match_familyname_fullfont">com.google.fonts/check/name/match_familyname_fullfont</a>)</summary><div>


* 🔥 **FAIL** On the 'name' table, the full font name 'Noto Sans Canadian Aboriginal Bold' does not begin with the font family name 'Noto Sans CanAborig' in platformID 3, encodingID 1, languageID 1033(0409), and nameID 1. [code: mismatch-font-names]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni1600
	* uni162D
	* uni1653
	* uni1630
	* uni1666
	* uni167C
	* uni15A7
	* uni1602
	* uni161D
	* uni1614 and 182 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1 

	- And uni0307.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni165E (U+165E): L<<325.0,408.0>--<407.0,408.0>> -> L<<407.0,408.0>--<408.0,408.0>> 

	* And uni165E (U+165E): L<<408.0,307.0>--<407.0,307.0>> -> L<<407.0,307.0>--<325.0,307.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* W (U+0057): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* W (U+0057): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wacute (U+1E82): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wcircumflex (U+0174): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726 

	* And 10 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni15D0 (U+15D0): L<<374.0,324.0>--<371.0,714.0>>

	* uni15D0 (U+15D0): L<<489.0,714.0>--<486.0,324.0>>

	* uni15D1 (U+15D1): L<<371.0,0.0>--<374.0,390.0>>

	* uni15D1 (U+15D1): L<<486.0,390.0>--<489.0,0.0>>

	* uni15D6 (U+15D6): L<<379.0,539.0>--<378.0,714.0>>

	* uni15D6 (U+15D6): L<<381.0,309.0>--<380.0,454.0>>

	* uni15D6 (U+15D6): L<<480.0,454.0>--<479.0,309.0>>

	* uni15D6 (U+15D6): L<<482.0,714.0>--<481.0,539.0>>

	* uni15D7 (U+15D7): L<<378.0,0.0>--<379.0,175.0>>

	* uni15D7 (U+15D7): L<<380.0,260.0>--<381.0,405.0>>

	* uni15D7 (U+15D7): L<<479.0,405.0>--<480.0,260.0>> 

	* And uni15D7 (U+15D7): L<<481.0,175.0>--<482.0,0.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[11] NotoSansCanadianAboriginal-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansCanadianAboriginal/googlefonts/slim-variable-ttf/NotoSansCanadianAboriginal[wght].ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Black.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Bold.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-ExtraBold.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-ExtraLight.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Light.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Medium.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Regular.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-SemiBold.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Thin.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/variable-ttf/NotoSansCanadianAboriginal[wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni1600
	* uni162D
	* uni1653
	* uni1630
	* uni1666
	* uni167C
	* uni15A7
	* uni1602
	* uni161D
	* uni1614 and 197 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Canadian Aboriginal ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1 

	- And uni0307.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<326.0,209.5>-<333.0,177.0>-<335.0,156.0>>/B<<335.0,156.0>-<338.0,177.0>-<344.5,209.0>> = 13.570434385161475

	* W (U+0057): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357

	* W (U+0057): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111

	* Wacute (U+1E82): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357

	* Wacute (U+1E82): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111

	* Wcircumflex (U+0174): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357

	* Wcircumflex (U+0174): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111

	* Wdieresis (U+1E84): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357

	* Wdieresis (U+1E84): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111

	* Wgrave (U+1E80): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357 

	* And Wgrave (U+1E80): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni15D0 (U+15D0): L<<375.0,349.0>--<372.0,714.0>>

	* uni15D0 (U+15D0): L<<488.0,714.0>--<485.0,352.0>>

	* uni15D1 (U+15D1): L<<372.0,0.0>--<375.0,365.0>>

	* uni15D1 (U+15D1): L<<485.0,362.0>--<488.0,0.0>>

	* uni15D6 (U+15D6): L<<478.0,466.0>--<477.0,322.0>>

	* uni15D6 (U+15D6): L<<480.0,714.0>--<479.0,550.0>>

	* uni15D7 (U+15D7): L<<477.0,392.0>--<478.0,248.0>> 

	* And uni15D7 (U+15D7): L<<479.0,164.0>--<480.0,0.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[12] NotoSansCanadianAboriginal-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansCanadianAboriginal/googlefonts/slim-variable-ttf/NotoSansCanadianAboriginal[wght].ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Black.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Bold.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-ExtraBold.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-ExtraLight.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Light.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Medium.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Regular.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-SemiBold.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Thin.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/variable-ttf/NotoSansCanadianAboriginal[wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni1600
	* uni162D
	* uni1653
	* uni1630
	* uni1666
	* uni161D
	* uni1614
	* uni18DB
	* uni1660
	* uni15EC and 100 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Canadian Aboriginal ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1 

	- And uni0307.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni11AB6 (U+11AB6): L<<446.0,714.0>--<478.0,714.0>> -> L<<478.0,714.0>--<478.0,714.0>> 

	* And uni11AB7 (U+11AB7): L<<446.0,714.0>--<478.0,714.0>> -> L<<478.0,714.0>--<478.0,714.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni1614 (U+1614): B<<166.5,556.0>-<256.0,646.0>-<443.0,682.0>>/L<<443.0,682.0>--<80.0,682.0>> = 10.896890755325513

	* uni1615 (U+1615): L<<728.0,682.0>--<365.0,682.0>>/B<<365.0,682.0>-<551.0,646.0>-<641.0,556.0>> = 10.954062643398332

	* uni1616 (U+1616): B<<641.0,158.0>-<551.0,68.0>-<365.0,32.0>>/L<<365.0,32.0>--<728.0,32.0>> = 10.954062643398332

	* uni1617 (U+1617): L<<113.0,714.0>--<113.0,352.0>>/B<<113.0,352.0>-<151.0,550.0>-<243.5,638.0>> = 10.864059922087714

	* uni1618 (U+1618): L<<113.0,714.0>--<113.0,352.0>>/B<<113.0,352.0>-<151.0,550.0>-<243.5,638.0>> = 10.864059922087714

	* uni1619 (U+1619): L<<113.0,714.0>--<113.0,352.0>>/B<<113.0,352.0>-<151.0,550.0>-<243.5,638.0>> = 10.864059922087714

	* uni161A (U+161A): B<<243.5,78.0>-<151.0,166.0>-<113.0,363.0>>/L<<113.0,363.0>--<113.0,0.0>> = 10.917885360431406

	* uni161B (U+161B): L<<790.0,0.0>--<790.0,363.0>>/B<<790.0,363.0>-<752.0,166.0>-<659.5,78.0>> = 10.917885360431406

	* uni18F1 (U+18F1): L<<728.0,682.0>--<365.0,682.0>>/B<<365.0,682.0>-<551.0,646.0>-<641.0,556.0>> = 10.954062643398332 

	* And uni18F2 (U+18F2): L<<790.0,0.0>--<790.0,363.0>>/B<<790.0,363.0>-<752.0,166.0>-<659.5,78.0>> = 10.917885360431406 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni15D0 (U+15D0): L<<392.0,74.0>--<390.0,714.0>>

	* uni15D0 (U+15D0): L<<426.0,714.0>--<424.0,74.0>>

	* uni15D1 (U+15D1): L<<390.0,0.0>--<392.0,640.0>>

	* uni15D1 (U+15D1): L<<424.0,640.0>--<426.0,0.0>>

	* uni15D2 (U+15D2): L<<57.0,375.0>--<608.0,373.0>>

	* uni15D2 (U+15D2): L<<610.0,342.0>--<57.0,341.0>>

	* uni15D3 (U+15D3): L<<238.0,374.0>--<608.0,373.0>>

	* uni15D3 (U+15D3): L<<57.0,375.0>--<203.0,374.0>>

	* uni15D3 (U+15D3): L<<610.0,342.0>--<238.0,341.0>>

	* uni15D4 (U+15D4): L<<320.0,374.0>--<615.0,373.0>> 

	* And 22 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[11] NotoSansCanadianAboriginal-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansCanadianAboriginal/googlefonts/slim-variable-ttf/NotoSansCanadianAboriginal[wght].ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Black.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Bold.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-ExtraBold.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-ExtraLight.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Light.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Medium.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Regular.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-SemiBold.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Thin.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/variable-ttf/NotoSansCanadianAboriginal[wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni1600
	* uni162D
	* uni1653
	* uni1630
	* uni1666
	* uni161D
	* uni1614
	* uni1654
	* uni18DB
	* uni1660 and 107 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Canadian Aboriginal Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1 

	- And uni0307.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni1614 (U+1614): B<<74.0,312.0>-<74.0,591.0>-<401.0,668.0>>/L<<401.0,668.0>--<77.0,668.0>> = 13.250285686272614

	* uni1615 (U+1615): L<<737.0,668.0>--<412.0,668.0>>/B<<412.0,668.0>-<740.0,591.0>-<740.0,312.0>> = 13.21130724971388

	* uni1616 (U+1616): B<<740.0,402.0>-<740.0,123.0>-<412.0,46.0>>/L<<412.0,46.0>--<737.0,46.0>> = 13.21130724971388

	* uni1617 (U+1617): L<<126.0,714.0>--<126.0,396.0>>/B<<126.0,396.0>-<167.0,570.0>-<257.5,648.0>> = 13.258872182180678

	* uni1618 (U+1618): L<<126.0,714.0>--<126.0,396.0>>/B<<126.0,396.0>-<167.0,570.0>-<257.5,648.0>> = 13.258872182180678

	* uni1619 (U+1619): L<<126.0,714.0>--<126.0,396.0>>/B<<126.0,396.0>-<167.0,570.0>-<257.5,648.0>> = 13.258872182180678

	* uni161A (U+161A): B<<257.5,67.0>-<167.0,145.0>-<126.0,319.0>>/L<<126.0,319.0>--<126.0,0.0>> = 13.258872182180678

	* uni161B (U+161B): L<<783.0,0.0>--<783.0,319.0>>/B<<783.0,319.0>-<742.0,145.0>-<651.5,67.0>> = 13.258872182180678

	* uni18F1 (U+18F1): L<<737.0,668.0>--<412.0,668.0>>/B<<412.0,668.0>-<740.0,591.0>-<740.0,312.0>> = 13.21130724971388 

	* And uni18F2 (U+18F2): L<<783.0,0.0>--<783.0,319.0>>/B<<783.0,319.0>-<742.0,145.0>-<651.5,67.0>> = 13.258872182180678 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni15D0 (U+15D0): L<<386.0,123.0>--<383.0,714.0>>

	* uni15D0 (U+15D0): L<<435.0,714.0>--<431.0,123.0>>

	* uni15D1 (U+15D1): L<<383.0,0.0>--<386.0,591.0>>

	* uni15D1 (U+15D1): L<<431.0,591.0>--<435.0,0.0>>

	* uni15D2 (U+15D2): L<<54.0,382.0>--<578.0,379.0>>

	* uni15D2 (U+15D2): L<<580.0,337.0>--<54.0,334.0>>

	* uni15D3 (U+15D3): L<<191.0,335.0>--<54.0,334.0>>

	* uni15D3 (U+15D3): L<<239.0,381.0>--<578.0,379.0>>

	* uni15D3 (U+15D3): L<<54.0,382.0>--<191.0,381.0>>

	* uni15D3 (U+15D3): L<<580.0,337.0>--<239.0,335.0>> 

	* And 26 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[12] NotoSansCanadianAboriginal-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansCanadianAboriginal/googlefonts/slim-variable-ttf/NotoSansCanadianAboriginal[wght].ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Black.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Bold.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-ExtraBold.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-ExtraLight.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Light.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Medium.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Regular.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-SemiBold.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Thin.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/variable-ttf/NotoSansCanadianAboriginal[wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni1600
	* uni162D
	* uni1653
	* uni1630
	* uni1666
	* uni167C
	* uni15A7
	* uni1602
	* uni161D
	* uni1614 and 157 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Canadian Aboriginal Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1 

	- And uni0307.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni1564 (U+1564): L<<351.0,629.0>--<346.0,629.0>> -> L<<346.0,629.0>--<317.0,629.0>> 

	* And uni1565 (U+1565): L<<351.0,629.0>--<346.0,629.0>> -> L<<346.0,629.0>--<317.0,629.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni15C0 (U+15C0): L<<569.0,374.0>--<607.0,220.0>>/L<<607.0,220.0>--<607.0,714.0>> = 13.861027563021148

	* uni15C1 (U+15C1): L<<166.0,714.0>--<166.0,220.0>>/L<<166.0,220.0>--<204.0,374.0>> = 13.861027563021148

	* uni15C2 (U+15C2): L<<607.0,0.0>--<607.0,494.0>>/L<<607.0,494.0>--<569.0,340.0>> = 13.861027563021148

	* uni15C3 (U+15C3): L<<204.0,340.0>--<166.0,494.0>>/L<<166.0,494.0>--<166.0,0.0>> = 13.861027563021148 

	* And uni18EC (U+18EC): L<<607.0,0.0>--<607.0,494.0>>/L<<607.0,494.0>--<569.0,340.0>> = 13.861027563021148 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni15D0 (U+15D0): L<<374.0,242.0>--<370.0,714.0>>

	* uni15D0 (U+15D0): L<<460.0,714.0>--<456.0,242.0>>

	* uni15D1 (U+15D1): L<<370.0,0.0>--<374.0,472.0>>

	* uni15D1 (U+15D1): L<<456.0,472.0>--<460.0,0.0>>

	* uni15D6 (U+15D6): L<<369.0,237.0>--<368.0,427.0>> 

	* And uni15D7 (U+15D7): L<<375.0,287.0>--<376.0,477.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[15] NotoSansCanadianAboriginal-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table set to optimize rendering? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/gasp">com.google.fonts/check/gasp</a>)</summary><div>


* 🔥 **FAIL** Font is missing the 'gasp' table. Try exporting the font with autohinting enabled.
If you are dealing with an unhinted font, it can be fixed by running the fonts through the command 'gftools fix-nonhinting'
GFTools is available at https://pypi.org/project/gftools/ [code: lacks-gasp]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: FONT_FAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/familyname">com.google.fonts/check/name/familyname</a>)</summary><div>


* 🔥 **FAIL** Entry [FONT_FAMILY_NAME(1):WINDOWS(3)] on the "name" table: Expected "Noto Sans Canadian Aboriginal" but got "Noto Sans CanAborig". [code: mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: TYPOGRAPHIC_FAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/typographicfamilyname">com.google.fonts/check/name/typographicfamilyname</a>)</summary><div>


* 🔥 **FAIL** Font style is "Regular" and, for that reason, it is not expected to have a [TYPOGRAPHIC_FAMILY_NAME(16):WINDOWS(3)] entry! [code: ribbi]
</div></details><details><summary>🔥 <b>FAIL:</b> Font enables smart dropout control in "prep" table instructions? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/smart_dropout">com.google.fonts/check/smart_dropout</a>)</summary><div>


* 🔥 **FAIL** The 'prep' table does not contain TrueType instructions enabling smart dropout control. To fix, export the font with autohinting enabled, or run ttfautohint on the font, or run the `gftools fix-nonhinting` script. [code: lacks-smart-dropout]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansCanadianAboriginal/googlefonts/slim-variable-ttf/NotoSansCanadianAboriginal[wght].ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Black.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Bold.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-ExtraBold.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-ExtraLight.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Light.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Medium.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Regular.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-SemiBold.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Thin.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/variable-ttf/NotoSansCanadianAboriginal[wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Does full font name begin with the font family name? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/name/match_familyname_fullfont">com.google.fonts/check/name/match_familyname_fullfont</a>)</summary><div>


* 🔥 **FAIL** On the 'name' table, the full font name 'Noto Sans Canadian Aboriginal Regular' does not begin with the font family name 'Noto Sans CanAborig' in platformID 3, encodingID 1, languageID 1033(0409), and nameID 1. [code: mismatch-font-names]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni1600
	* uni162D
	* uni1653
	* uni1630
	* uni1666
	* uni161D
	* uni1614
	* uni1654
	* uni1648
	* uni18DB and 129 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1 

	- And uni0307.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni15C0 (U+15C0): L<<563.0,360.0>--<615.0,149.0>>/L<<615.0,149.0>--<615.0,714.0>> = 13.84440563731597

	* uni15C1 (U+15C1): L<<146.0,714.0>--<146.0,149.0>>/L<<146.0,149.0>--<198.0,360.0>> = 13.84440563731597

	* uni15C2 (U+15C2): L<<615.0,0.0>--<615.0,565.0>>/L<<615.0,565.0>--<563.0,354.0>> = 13.84440563731597

	* uni15C3 (U+15C3): L<<198.0,354.0>--<146.0,565.0>>/L<<146.0,565.0>--<146.0,0.0>> = 13.84440563731597 

	* And uni18EC (U+18EC): L<<615.0,0.0>--<615.0,565.0>>/L<<615.0,565.0>--<563.0,354.0>> = 13.84440563731597 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni15D0 (U+15D0): L<<374.0,207.0>--<370.0,714.0>>

	* uni15D0 (U+15D0): L<<448.0,714.0>--<444.0,207.0>>

	* uni15D1 (U+15D1): L<<370.0,0.0>--<374.0,507.0>>

	* uni15D1 (U+15D1): L<<444.0,507.0>--<448.0,0.0>>

	* uni15D2 (U+15D2): L<<49.0,394.0>--<525.0,390.0>>

	* uni15D2 (U+15D2): L<<527.0,327.0>--<49.0,323.0>>

	* uni15D3 (U+15D3): L<<170.0,324.0>--<49.0,323.0>>

	* uni15D3 (U+15D3): L<<240.0,392.0>--<525.0,390.0>>

	* uni15D3 (U+15D3): L<<49.0,394.0>--<170.0,393.0>>

	* uni15D3 (U+15D3): L<<527.0,327.0>--<240.0,325.0>> 

	* And 10 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[12] NotoSansCanadianAboriginal-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansCanadianAboriginal/googlefonts/slim-variable-ttf/NotoSansCanadianAboriginal[wght].ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Black.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Bold.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-ExtraBold.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-ExtraLight.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Light.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Medium.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Regular.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-SemiBold.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Thin.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/variable-ttf/NotoSansCanadianAboriginal[wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni1600
	* uni162D
	* uni1653
	* uni1630
	* uni1666
	* uni167C
	* uni15A7
	* uni1602
	* uni161D
	* uni1614 and 166 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Canadian Aboriginal SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1 

	- And uni0307.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni11AB6 (U+11AB6): L<<436.0,714.0>--<545.0,714.0>> -> L<<545.0,714.0>--<545.0,714.0>>

	* uni11AB7 (U+11AB7): L<<436.0,714.0>--<545.0,714.0>> -> L<<545.0,714.0>--<545.0,714.0>>

	* uni11AB8 (U+11AB8): L<<333.0,0.0>--<225.0,0.0>> -> L<<225.0,0.0>--<224.0,0.0>>

	* uni11AB9 (U+11AB9): L<<333.0,0.0>--<225.0,0.0>> -> L<<225.0,0.0>--<224.0,0.0>> 

	* And uni166A (U+166A): L<<422.0,313.0>--<415.0,313.0>> -> L<<415.0,313.0>--<361.0,313.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* W (U+0057): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wacute (U+1E82): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wacute (U+1E82): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wgrave (U+1E80): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wgrave (U+1E80): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726 

	* And 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni15D0 (U+15D0): L<<374.0,280.0>--<371.0,714.0>>

	* uni15D1 (U+15D1): L<<371.0,0.0>--<374.0,434.0>>

	* uni15D6 (U+15D6): L<<463.0,440.0>--<462.0,271.0>>

	* uni15D6 (U+15D6): L<<465.0,714.0>--<464.0,519.0>>

	* uni15D7 (U+15D7): L<<466.0,443.0>--<467.0,274.0>> 

	* And uni15D7 (U+15D7): L<<468.0,195.0>--<469.0,0.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[12] NotoSansCanadianAboriginal-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansCanadianAboriginal/googlefonts/slim-variable-ttf/NotoSansCanadianAboriginal[wght].ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Black.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Bold.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-ExtraBold.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-ExtraLight.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Light.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Medium.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Regular.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-SemiBold.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/ttf/NotoSansCanadianAboriginal-Thin.ttf', 'fonts/NotoSansCanadianAboriginal/googlefonts/variable-ttf/NotoSansCanadianAboriginal[wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni162D
	* uni1653
	* uni1630
	* uni1666
	* uni161D
	* uni1614
	* uni18DB
	* uni1660
	* uni15EC
	* uni1624 and 93 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Canadian Aboriginal Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1 

	- And uni0307.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni155D (U+155D): L<<266.0,659.0>--<263.0,657.0>> -> L<<263.0,657.0>--<80.0,530.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni1614 (U+1614): B<<175.0,566.5>-<271.0,657.0>-<476.0,691.0>>/L<<476.0,691.0>--<82.0,691.0>> = 9.416993277994541

	* uni1615 (U+1615): L<<722.0,691.0>--<328.0,691.0>>/B<<328.0,691.0>-<533.0,657.0>-<629.0,566.5>> = 9.416993277994541

	* uni1616 (U+1616): B<<629.0,147.5>-<533.0,57.0>-<328.0,23.0>>/L<<328.0,23.0>--<722.0,23.0>> = 9.416993277994541

	* uni1617 (U+1617): L<<105.0,714.0>--<105.0,315.0>>/B<<105.0,315.0>-<128.0,460.0>-<177.0,551.0>> = 9.01320435564271

	* uni1618 (U+1618): L<<105.0,714.0>--<105.0,315.0>>/B<<105.0,315.0>-<128.0,460.0>-<177.0,551.0>> = 9.01320435564271

	* uni1619 (U+1619): L<<105.0,714.0>--<105.0,315.0>>/B<<105.0,315.0>-<128.0,460.0>-<177.0,551.0>> = 9.01320435564271

	* uni161A (U+161A): B<<177.0,165.0>-<128.0,256.0>-<105.0,401.0>>/L<<105.0,401.0>--<105.0,0.0>> = 9.01320435564271

	* uni161B (U+161B): L<<794.0,0.0>--<794.0,401.0>>/B<<794.0,401.0>-<771.0,256.0>-<722.0,165.0>> = 9.01320435564271

	* uni18F1 (U+18F1): L<<722.0,691.0>--<328.0,691.0>>/B<<328.0,691.0>-<533.0,657.0>-<629.0,566.5>> = 9.416993277994541 

	* And uni18F2 (U+18F2): L<<794.0,0.0>--<794.0,401.0>>/B<<794.0,401.0>-<771.0,256.0>-<722.0,165.0>> = 9.01320435564271 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam (U+0021): L<<100.0,174.0>--<98.0,714.0>>

	* exclam (U+0021): L<<127.0,714.0>--<125.0,174.0>>

	* exclamdown (U+00A1): L<<122.0,354.0>--<124.0,-186.0>>

	* exclamdown (U+00A1): L<<96.0,-186.0>--<98.0,354.0>>

	* uni15D0 (U+15D0): L<<397.0,40.0>--<395.0,714.0>>

	* uni15D0 (U+15D0): L<<421.0,714.0>--<419.0,40.0>>

	* uni15D1 (U+15D1): L<<395.0,0.0>--<397.0,674.0>>

	* uni15D1 (U+15D1): L<<419.0,674.0>--<421.0,0.0>>

	* uni15D2 (U+15D2): L<<59.0,370.0>--<629.0,369.0>>

	* uni15D2 (U+15D2): L<<631.0,346.0>--<59.0,345.0>> 

	* And 22 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 48 | 84 | 1246 | 82 | 975 | 0 |
| 0% | 2% | 3% | 51% | 3% | 40% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
