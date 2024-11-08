## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[9] NotoSansLinearA-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansLinearA/googlefonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, cherokee, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, canadian-aboriginal, duployan, todhri, coptic, hebrew, old-permic, tai-le, math, syriac, malayalam</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+10100 AEGEAN WORD SEPARATOR LINE: try adding one of: cypro-minoan, cypriot, linear-b</li>
<li>U+10101 AEGEAN WORD SEPARATOR DOT: try adding one of: cypro-minoan, cypriot, linear-b</li>
<li>U+10102 AEGEAN CHECK MARK: try adding one of: cypriot, linear-b</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code>, <code>linear-a</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Fur (Latn, 1,230,163 speakers), Kom (Latn, 360,685 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Dan (Latn, 1,099,244 speakers), Vute (Latn, 21,000 speakers), Ebira (Latn, 2,200,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Kaska (Latn, 125 speakers), Aghem (Latn, 38,843 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Gulay (Latn, 250,478 speakers), Avokaya (Latn, 100,000 speakers), Heiltsuk (Latn, 300 speakers), Igbo (Latn, 27,823,640 speakers), Nzakara (Latn, 50,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Zapotec (Latn, 490,000 speakers), Ma’di (Latn, 584,000 speakers), South Central Banda (Latn, 244,000 speakers), Lugbara (Latn, 2,200,000 speakers), Makaa (Latn, 221,000 speakers), Yala (Latn, 200,000 speakers), Basaa (Latn, 332,940 speakers), Koonzime (Latn, 40,000 speakers), Han (Latn, 6 speakers), Navajo (Latn, 166,319 speakers), Mango (Latn, 77,000 speakers), Southern Kisi (Latn, 360,000 speakers), Ekpeye (Latn, 226,000 speakers), Cicipu (Latn, 44,000 speakers), Mfumte (Latn, 79,000 speakers), Mundani (Latn, 34,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Teke-Ebo (Latn, 260,000 speakers), Bafut (Latn, 158,146 speakers), Sar (Latn, 500,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Ejagham (Latn, 120,000 speakers), Dii (Latn, 71,000 speakers), Nateni (Latn, 100,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* u106C7 (U+106C7): L&lt;&lt;127.0,374.0&gt;--&lt;32.0,513.0&gt;&gt; -&gt; L&lt;&lt;32.0,513.0&gt;--&lt;20.0,528.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* u10649 (U+10649): B&lt;&lt;148.0,681.0&gt;-&lt;184.0,724.0&gt;-&lt;239.0,737.0&gt;&gt;/L&lt;&lt;239.0,737.0&gt;--&lt;50.0,737.0&gt;&gt; = 13.298570330494275

* u10649 (U+10649): L&lt;&lt;504.0,737.0&gt;--&lt;314.0,737.0&gt;&gt;/B&lt;&lt;314.0,737.0&gt;-&lt;369.0,724.0&gt;-&lt;405.5,681.0&gt;&gt; = 13.298570330494275

* u106DF (U+106DF): B&lt;&lt;518.0,681.0&gt;-&lt;554.0,724.0&gt;-&lt;609.0,737.0&gt;&gt;/L&lt;&lt;609.0,737.0&gt;--&lt;420.0,737.0&gt;&gt; = 13.298570330494275

* u106DF (U+106DF): L&lt;&lt;874.0,737.0&gt;--&lt;684.0,737.0&gt;&gt;/B&lt;&lt;684.0,737.0&gt;-&lt;739.0,724.0&gt;-&lt;775.5,681.0&gt;&gt; = 13.298570330494275

* u106EC (U+106EC): B&lt;&lt;148.0,681.0&gt;-&lt;184.0,724.0&gt;-&lt;239.0,737.0&gt;&gt;/L&lt;&lt;239.0,737.0&gt;--&lt;50.0,737.0&gt;&gt; = 13.298570330494275

* u106EC (U+106EC): L&lt;&lt;504.0,737.0&gt;--&lt;314.0,737.0&gt;&gt;/B&lt;&lt;314.0,737.0&gt;-&lt;369.0,724.0&gt;-&lt;405.5,681.0&gt;&gt; = 13.298570330494275

* u106ED (U+106ED): B&lt;&lt;148.0,681.0&gt;-&lt;184.0,724.0&gt;-&lt;239.0,737.0&gt;&gt;/L&lt;&lt;239.0,737.0&gt;--&lt;50.0,737.0&gt;&gt; = 13.298570330494275

* u106ED (U+106ED): L&lt;&lt;504.0,737.0&gt;--&lt;314.0,737.0&gt;&gt;/B&lt;&lt;314.0,737.0&gt;-&lt;369.0,724.0&gt;-&lt;405.5,681.0&gt;&gt; = 13.298570330494275

* u106EF (U+106EF): B&lt;&lt;148.0,681.0&gt;-&lt;184.0,724.0&gt;-&lt;239.0,737.0&gt;&gt;/L&lt;&lt;239.0,737.0&gt;--&lt;50.0,737.0&gt;&gt; = 13.298570330494275

* u106EF (U+106EF): L&lt;&lt;504.0,737.0&gt;--&lt;314.0,737.0&gt;&gt;/B&lt;&lt;314.0,737.0&gt;-&lt;369.0,724.0&gt;-&lt;405.5,681.0&gt;&gt; = 13.298570330494275

* u106F0 (U+106F0): B&lt;&lt;148.0,681.0&gt;-&lt;184.0,724.0&gt;-&lt;239.0,737.0&gt;&gt;/L&lt;&lt;239.0,737.0&gt;--&lt;50.0,737.0&gt;&gt; = 13.298570330494275

* u106F0 (U+106F0): L&lt;&lt;504.0,737.0&gt;--&lt;314.0,737.0&gt;&gt;/B&lt;&lt;314.0,737.0&gt;-&lt;369.0,724.0&gt;-&lt;405.5,681.0&gt;&gt; = 13.298570330494275

* u106F1 (U+106F1): B&lt;&lt;148.0,681.0&gt;-&lt;184.0,724.0&gt;-&lt;239.0,737.0&gt;&gt;/L&lt;&lt;239.0,737.0&gt;--&lt;50.0,737.0&gt;&gt; = 13.298570330494275

* u106F1 (U+106F1): L&lt;&lt;504.0,737.0&gt;--&lt;314.0,737.0&gt;&gt;/B&lt;&lt;314.0,737.0&gt;-&lt;369.0,724.0&gt;-&lt;405.5,681.0&gt;&gt; = 13.298570330494275

* u106F2 (U+106F2): B&lt;&lt;148.0,681.0&gt;-&lt;184.0,724.0&gt;-&lt;239.0,737.0&gt;&gt;/L&lt;&lt;239.0,737.0&gt;--&lt;50.0,737.0&gt;&gt; = 13.298570330494275

* u106F2 (U+106F2): L&lt;&lt;504.0,737.0&gt;--&lt;314.0,737.0&gt;&gt;/B&lt;&lt;314.0,737.0&gt;-&lt;369.0,724.0&gt;-&lt;405.5,681.0&gt;&gt; = 13.298570330494275

* u106F3 (U+106F3): B&lt;&lt;148.0,681.0&gt;-&lt;184.0,724.0&gt;-&lt;239.0,737.0&gt;&gt;/L&lt;&lt;239.0,737.0&gt;--&lt;50.0,737.0&gt;&gt; = 13.298570330494275

* u106F3 (U+106F3): L&lt;&lt;504.0,737.0&gt;--&lt;314.0,737.0&gt;&gt;/B&lt;&lt;314.0,737.0&gt;-&lt;369.0,724.0&gt;-&lt;405.5,681.0&gt;&gt; = 13.298570330494275

* u106F4 (U+106F4): B&lt;&lt;151.0,681.0&gt;-&lt;187.0,724.0&gt;-&lt;242.0,737.0&gt;&gt;/L&lt;&lt;242.0,737.0&gt;--&lt;53.0,737.0&gt;&gt; = 13.298570330494275

* u106F4 (U+106F4): L&lt;&lt;507.0,737.0&gt;--&lt;317.0,737.0&gt;&gt;/B&lt;&lt;317.0,737.0&gt;-&lt;372.0,724.0&gt;-&lt;408.5,681.0&gt;&gt; = 13.298570330494275

* u106F5 (U+106F5): B&lt;&lt;148.0,681.0&gt;-&lt;184.0,724.0&gt;-&lt;239.0,737.0&gt;&gt;/L&lt;&lt;239.0,737.0&gt;--&lt;50.0,737.0&gt;&gt; = 13.298570330494275

* u106F5 (U+106F5): L&lt;&lt;504.0,737.0&gt;--&lt;314.0,737.0&gt;&gt;/B&lt;&lt;314.0,737.0&gt;-&lt;369.0,724.0&gt;-&lt;405.5,681.0&gt;&gt; = 13.298570330494275

* u106F6 (U+106F6): B&lt;&lt;148.0,681.0&gt;-&lt;184.0,724.0&gt;-&lt;239.0,737.0&gt;&gt;/L&lt;&lt;239.0,737.0&gt;--&lt;50.0,737.0&gt;&gt; = 13.298570330494275

* u106F6 (U+106F6): L&lt;&lt;504.0,737.0&gt;--&lt;314.0,737.0&gt;&gt;/B&lt;&lt;314.0,737.0&gt;-&lt;369.0,724.0&gt;-&lt;405.5,681.0&gt;&gt; = 13.298570330494275

* u106F7 (U+106F7): B&lt;&lt;148.0,681.0&gt;-&lt;184.0,724.0&gt;-&lt;239.0,737.0&gt;&gt;/L&lt;&lt;239.0,737.0&gt;--&lt;50.0,737.0&gt;&gt; = 13.298570330494275

* u106F7 (U+106F7): L&lt;&lt;504.0,737.0&gt;--&lt;314.0,737.0&gt;&gt;/B&lt;&lt;314.0,737.0&gt;-&lt;369.0,724.0&gt;-&lt;405.5,681.0&gt;&gt; = 13.298570330494275

* u106F8 (U+106F8): B&lt;&lt;148.0,681.0&gt;-&lt;184.0,724.0&gt;-&lt;239.0,737.0&gt;&gt;/L&lt;&lt;239.0,737.0&gt;--&lt;50.0,737.0&gt;&gt; = 13.298570330494275

* u106F8 (U+106F8): L&lt;&lt;504.0,737.0&gt;--&lt;314.0,737.0&gt;&gt;/B&lt;&lt;314.0,737.0&gt;-&lt;369.0,724.0&gt;-&lt;405.5,681.0&gt;&gt; = 13.298570330494275

* u106F9 (U+106F9): B&lt;&lt;148.0,681.0&gt;-&lt;184.0,724.0&gt;-&lt;239.0,737.0&gt;&gt;/L&lt;&lt;239.0,737.0&gt;--&lt;50.0,737.0&gt;&gt; = 13.298570330494275

* u106F9 (U+106F9): L&lt;&lt;504.0,737.0&gt;--&lt;314.0,737.0&gt;&gt;/B&lt;&lt;314.0,737.0&gt;-&lt;369.0,724.0&gt;-&lt;405.5,681.0&gt;&gt; = 13.298570330494275
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 1 | 8 | 117 | 6 | 119 | 0 | 
| 0% | 0% | 0% | 3% | 47% | 2% | 47% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
