## Fontbakery report

Fontbakery version: 0.8.10

<details><summary><b>[6] NotoSansLinearA-Regular.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* u106C7 (U+106C7): L<<127.0,374.0>--<32.0,513.0>> -> L<<32.0,513.0>--<20.0,528.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* u10649 (U+10649): B<<148.0,681.0>-<184.0,724.0>-<239.0,737.0>>/L<<239.0,737.0>--<50.0,737.0>> = 13.298570330494275

	* u10649 (U+10649): L<<504.0,737.0>--<314.0,737.0>>/B<<314.0,737.0>-<369.0,724.0>-<405.5,681.0>> = 13.298570330494275

	* u106DF (U+106DF): B<<518.0,681.0>-<554.0,724.0>-<609.0,737.0>>/L<<609.0,737.0>--<420.0,737.0>> = 13.298570330494275

	* u106DF (U+106DF): L<<874.0,737.0>--<684.0,737.0>>/B<<684.0,737.0>-<739.0,724.0>-<775.5,681.0>> = 13.298570330494275

	* u106EC (U+106EC): B<<148.0,681.0>-<184.0,724.0>-<239.0,737.0>>/L<<239.0,737.0>--<50.0,737.0>> = 13.298570330494275

	* u106EC (U+106EC): L<<504.0,737.0>--<314.0,737.0>>/B<<314.0,737.0>-<369.0,724.0>-<405.5,681.0>> = 13.298570330494275

	* u106ED (U+106ED): B<<148.0,681.0>-<184.0,724.0>-<239.0,737.0>>/L<<239.0,737.0>--<50.0,737.0>> = 13.298570330494275

	* u106ED (U+106ED): L<<504.0,737.0>--<314.0,737.0>>/B<<314.0,737.0>-<369.0,724.0>-<405.5,681.0>> = 13.298570330494275

	* u106EF (U+106EF): B<<148.0,681.0>-<184.0,724.0>-<239.0,737.0>>/L<<239.0,737.0>--<50.0,737.0>> = 13.298570330494275

	* u106EF (U+106EF): L<<504.0,737.0>--<314.0,737.0>>/B<<314.0,737.0>-<369.0,724.0>-<405.5,681.0>> = 13.298570330494275 

	* And 20 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 0 | 6 | 111 | 7 | 103 | 0 |
| 0% | 0% | 3% | 49% | 3% | 45% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
