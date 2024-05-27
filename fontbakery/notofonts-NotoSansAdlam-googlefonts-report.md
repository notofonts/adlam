## FontBakery report

fontbakery version: 0.12.6



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] NotoSansAdlam-Regular.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Validate location, size and resolution of article images. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansAdlam/googlefonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>
</div>
</details>

<details><summary>[1] NotoSansAdlam-Bold.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Validate location, size and resolution of article images. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansAdlam/googlefonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[9] NotoSansAdlam-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nl_Latn (Dutch)</td>
<td align="left">Shaper didn't attach acutecomb to J</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0237</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



</div>
</details>

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
    <summary>⚠️ <b>WARN</b> Check mark characters are in GDEF mark glyph class. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following mark characters could be in the GDEF mark glyph class:
acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C), uni0326 (U+0326), uni0327 (U+0327) and uni0328 (U+0328)</p>
 [code: mark-chars]



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
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 558 among a set of 2 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 557:
plus</p>
<p>Width = 545:
equal</p>
<p>Width = 572:
multiply, divide</p>
<p>Width = 322:
minus</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* u1E918 (U+1E918): L&lt;&lt;174.0,714.0&gt;--&lt;175.0,475.0&gt;&gt;

* u1E918.fina: L&lt;&lt;174.0,714.0&gt;--&lt;175.0,475.0&gt;&gt;

* u1E918.init: L&lt;&lt;174.0,714.0&gt;--&lt;175.0,475.0&gt;&gt;

* u1E918.medi: L&lt;&lt;174.0,714.0&gt;--&lt;175.0,475.0&gt;&gt;

* u1E91D (U+1E91D): L&lt;&lt;199.0,321.0&gt;--&lt;200.0,0.0&gt;&gt;

* u1E91D.fina: L&lt;&lt;199.0,321.0&gt;--&lt;200.0,0.0&gt;&gt;

* u1E91D.init: L&lt;&lt;199.0,321.0&gt;--&lt;200.0,118.0&gt;&gt;

* u1E91D.medi: L&lt;&lt;199.0,321.0&gt;--&lt;200.0,118.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ j̦̀ j̦́ ĵ̦ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Basaa (Latn, 332,940 speakers), Zapotec (Latn, 490,000 speakers), Aghem (Latn, 38,843 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Southern Kisi (Latn, 360,000 speakers), Koonzime (Latn, 40,000 speakers), Lugbara (Latn, 2,200,000 speakers), Gulay (Latn, 250,478 speakers), Dii (Latn, 71,000 speakers), Mango (Latn, 77,000 speakers), Igbo (Latn, 27,823,640 speakers), Navajo (Latn, 166,319 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ekpeye (Latn, 226,000 speakers), Nateni (Latn, 100,000 speakers), Nzakara (Latn, 50,000 speakers), Ebira (Latn, 2,200,000 speakers), Bafut (Latn, 158,146 speakers), Ngbaka (Latn, 1,020,000 speakers), Ma’di (Latn, 584,000 speakers), Mfumte (Latn, 79,000 speakers), Sar (Latn, 500,000 speakers), Vute (Latn, 21,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Makaa (Latn, 221,000 speakers), Yala (Latn, 200,000 speakers), Mundani (Latn, 34,000 speakers), Avokaya (Latn, 100,000 speakers), Kom (Latn, 360,685 speakers), Ukrainian (Cyrl, 29,273,587 speakers), South Central Banda (Latn, 244,000 speakers), Dan (Latn, 1,099,244 speakers), Cicipu (Latn, 44,000 speakers), Fur (Latn, 1,230,163 speakers), Dutch (Latn, 31,709,104 speakers), Ejagham (Latn, 120,000 speakers).</p>
 [code: soft-dotted]



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
<li>U+02C7 CARON: try adding one of: yi, tifinagh, canadian-aboriginal</li>
<li>U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition</li>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, cherokee, tifinagh, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: canadian-aboriginal, tai-le, tifinagh, math, syriac, malayalam, old-permic, coptic</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: not included in any glyphset definition</li>
<li>U+0327 COMBINING CEDILLA: not included in any glyphset definition</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>adlam</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



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

<details><summary>[10] NotoSansAdlam-Bold.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nl_Latn (Dutch)</td>
<td align="left">Shaper didn't attach acutecomb to J</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0237</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



</div>
</details>

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
    <summary>⚠️ <b>WARN</b> Check mark characters are in GDEF mark glyph class. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following mark characters could be in the GDEF mark glyph class:
acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C), uni0326 (U+0326), uni0327 (U+0327) and uni0328 (U+0328)</p>
 [code: mark-chars]



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
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 322:
minus</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* W (U+0057): B&lt;&lt;266.0,196.0&gt;-&lt;272.0,161.0&gt;-&lt;275.0,137.0&gt;&gt;/B&lt;&lt;275.0,137.0&gt;-&lt;278.0,162.0&gt;-&lt;284.0,196.5&gt;&gt; = 13.967789761532726

* W (U+0057): B&lt;&lt;489.0,505.5&gt;-&lt;485.0,529.0&gt;-&lt;483.0,542.0&gt;&gt;/B&lt;&lt;483.0,542.0&gt;-&lt;482.0,529.0&gt;-&lt;477.5,505.5&gt;&gt; = 13.144867617550734

* W (U+0057): B&lt;&lt;683.0,196.0&gt;-&lt;689.0,161.0&gt;-&lt;692.0,137.0&gt;&gt;/B&lt;&lt;692.0,137.0&gt;-&lt;695.0,162.0&gt;-&lt;701.0,196.5&gt;&gt; = 13.967789761532726

* Wacute (U+1E82): B&lt;&lt;266.0,196.0&gt;-&lt;272.0,161.0&gt;-&lt;275.0,137.0&gt;&gt;/B&lt;&lt;275.0,137.0&gt;-&lt;278.0,162.0&gt;-&lt;284.0,196.5&gt;&gt; = 13.967789761532726

* Wacute (U+1E82): B&lt;&lt;489.0,505.5&gt;-&lt;485.0,529.0&gt;-&lt;483.0,542.0&gt;&gt;/B&lt;&lt;483.0,542.0&gt;-&lt;482.0,529.0&gt;-&lt;477.5,505.5&gt;&gt; = 13.144867617550734

* Wacute (U+1E82): B&lt;&lt;683.0,196.0&gt;-&lt;689.0,161.0&gt;-&lt;692.0,137.0&gt;&gt;/B&lt;&lt;692.0,137.0&gt;-&lt;695.0,162.0&gt;-&lt;701.0,196.5&gt;&gt; = 13.967789761532726

* Wcircumflex (U+0174): B&lt;&lt;266.0,196.0&gt;-&lt;272.0,161.0&gt;-&lt;275.0,137.0&gt;&gt;/B&lt;&lt;275.0,137.0&gt;-&lt;278.0,162.0&gt;-&lt;284.0,196.5&gt;&gt; = 13.967789761532726

* Wcircumflex (U+0174): B&lt;&lt;489.0,505.5&gt;-&lt;485.0,529.0&gt;-&lt;483.0,542.0&gt;&gt;/B&lt;&lt;483.0,542.0&gt;-&lt;482.0,529.0&gt;-&lt;477.5,505.5&gt;&gt; = 13.144867617550734

* Wcircumflex (U+0174): B&lt;&lt;683.0,196.0&gt;-&lt;689.0,161.0&gt;-&lt;692.0,137.0&gt;&gt;/B&lt;&lt;692.0,137.0&gt;-&lt;695.0,162.0&gt;-&lt;701.0,196.5&gt;&gt; = 13.967789761532726

* Wdieresis (U+1E84): B&lt;&lt;266.0,196.0&gt;-&lt;272.0,161.0&gt;-&lt;275.0,137.0&gt;&gt;/B&lt;&lt;275.0,137.0&gt;-&lt;278.0,162.0&gt;-&lt;284.0,196.5&gt;&gt; = 13.967789761532726

* Wdieresis (U+1E84): B&lt;&lt;489.0,505.5&gt;-&lt;485.0,529.0&gt;-&lt;483.0,542.0&gt;&gt;/B&lt;&lt;483.0,542.0&gt;-&lt;482.0,529.0&gt;-&lt;477.5,505.5&gt;&gt; = 13.144867617550734

* Wdieresis (U+1E84): B&lt;&lt;683.0,196.0&gt;-&lt;689.0,161.0&gt;-&lt;692.0,137.0&gt;&gt;/B&lt;&lt;692.0,137.0&gt;-&lt;695.0,162.0&gt;-&lt;701.0,196.5&gt;&gt; = 13.967789761532726

* Wgrave (U+1E80): B&lt;&lt;266.0,196.0&gt;-&lt;272.0,161.0&gt;-&lt;275.0,137.0&gt;&gt;/B&lt;&lt;275.0,137.0&gt;-&lt;278.0,162.0&gt;-&lt;284.0,196.5&gt;&gt; = 13.967789761532726

* Wgrave (U+1E80): B&lt;&lt;489.0,505.5&gt;-&lt;485.0,529.0&gt;-&lt;483.0,542.0&gt;&gt;/B&lt;&lt;483.0,542.0&gt;-&lt;482.0,529.0&gt;-&lt;477.5,505.5&gt;&gt; = 13.144867617550734

* Wgrave (U+1E80): B&lt;&lt;683.0,196.0&gt;-&lt;689.0,161.0&gt;-&lt;692.0,137.0&gt;&gt;/B&lt;&lt;692.0,137.0&gt;-&lt;695.0,162.0&gt;-&lt;701.0,196.5&gt;&gt; = 13.967789761532726
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* u1E918 (U+1E918): L&lt;&lt;225.0,714.0&gt;--&lt;226.0,498.0&gt;&gt;

* u1E918.fina: L&lt;&lt;225.0,714.0&gt;--&lt;226.0,498.0&gt;&gt;

* u1E918.init: L&lt;&lt;225.0,714.0&gt;--&lt;226.0,498.0&gt;&gt;

* u1E918.medi: L&lt;&lt;225.0,714.0&gt;--&lt;226.0,498.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ j̦̀ j̦́ ĵ̦ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Basaa (Latn, 332,940 speakers), Zapotec (Latn, 490,000 speakers), Aghem (Latn, 38,843 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Southern Kisi (Latn, 360,000 speakers), Koonzime (Latn, 40,000 speakers), Lugbara (Latn, 2,200,000 speakers), Gulay (Latn, 250,478 speakers), Dii (Latn, 71,000 speakers), Mango (Latn, 77,000 speakers), Igbo (Latn, 27,823,640 speakers), Navajo (Latn, 166,319 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ekpeye (Latn, 226,000 speakers), Nateni (Latn, 100,000 speakers), Nzakara (Latn, 50,000 speakers), Ebira (Latn, 2,200,000 speakers), Bafut (Latn, 158,146 speakers), Ngbaka (Latn, 1,020,000 speakers), Ma’di (Latn, 584,000 speakers), Mfumte (Latn, 79,000 speakers), Sar (Latn, 500,000 speakers), Vute (Latn, 21,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Makaa (Latn, 221,000 speakers), Yala (Latn, 200,000 speakers), Mundani (Latn, 34,000 speakers), Avokaya (Latn, 100,000 speakers), Kom (Latn, 360,685 speakers), Ukrainian (Cyrl, 29,273,587 speakers), South Central Banda (Latn, 244,000 speakers), Dan (Latn, 1,099,244 speakers), Cicipu (Latn, 44,000 speakers), Fur (Latn, 1,230,163 speakers), Dutch (Latn, 31,709,104 speakers), Ejagham (Latn, 120,000 speakers).</p>
 [code: soft-dotted]



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
<li>U+02C7 CARON: try adding one of: yi, tifinagh, canadian-aboriginal</li>
<li>U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition</li>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, cherokee, tifinagh, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: canadian-aboriginal, tai-le, tifinagh, math, syriac, malayalam, old-permic, coptic</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: not included in any glyphset definition</li>
<li>U+0327 COMBINING CEDILLA: not included in any glyphset definition</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>adlam</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



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
| 0 | 0 | 4 | 17 | 230 | 11 | 222 | 0 | 
| 0% | 0% | 1% | 4% | 48% | 2% | 46% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
