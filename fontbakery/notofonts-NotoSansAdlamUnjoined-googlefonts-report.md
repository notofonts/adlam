## FontBakery report

fontbakery version: 0.12.6



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] NotoSansAdlamUnjoined-Regular.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Validate location, size and resolution of article images. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansAdlamUnjoined/googlefonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>
</div>
</details>

<details><summary>[1] NotoSansAdlamUnjoined-Bold.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Validate location, size and resolution of article images. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansAdlamUnjoined/googlefonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[12] NotoSansAdlamUnjoined-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check that texts shape as per expectation <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>qa/shaping_tests/issues.json: Expected and actual shaping not matching</p>
<ul>
<li>
<p>Shaping did not match: 𞤉𞥅𞤉𞥊𞥅𞤉𞥊 (#3)</p>
<pre><code>Expected: u1E94A=5@242,196+0|u1E909=5+711|u1E945.case=2@285,177+0|u1E94A.below=2@271,-7+0|u1E909=2+711|u1E945.case=0@285,177+0|u1E909=0+711
Got     : u1E94A=5@242,196+0|u1E909=5+711|u1E945=2@132,206+0|u1E94A.below=2@271,-7+0|u1E909=2+711|u1E945.case=0@285,177+0|u1E909=0+711
                                                +++++   ++++ ^^
</code></pre>
<p>Got: <svg style="height:100px;margin:10px;" xmlns="http://www.w3.org/2000/svg" viewBox="0 -724 2223 1793" transform="matrix(1 0 0 -1 0 0)"> <defs> <path id="g128" d="M176.0,670.0Q176.0,639.0 157.5,625.0Q139.0,611.0 111.0,611.0Q83.0,611.0 64.0,625.0Q45.0,639.0 45.0,670.0Q45.0,700.0 64.0,715.0Q83.0,730.0 111.0,730.0Q140.0,730.0 158.0,715.0Q176.0,700.0 176.0,670.0Z"/> <path id="g13" d="M473.0,0.0L357.0,0.0Q287.0,0.0 253.5,33.0Q220.0,66.0 220.0,109.0L215.0,109.0Q208.0,102.0 196.5,83.0Q185.0,64.0 180.0,38.0L180.0,0.0L90.0,0.0L90.0,483.0Q90.0,612.0 153.5,668.0Q217.0,724.0 363.0,724.0Q497.0,724.0 554.0,676.5Q611.0,629.0 611.0,545.0Q611.0,465.0 577.5,417.0Q544.0,369.0 490.0,330.0L491.0,326.0Q512.0,322.0 540.0,311.5Q568.0,301.0 594.5,281.0Q621.0,261.0 638.5,228.0Q656.0,195.0 656.0,147.0Q656.0,90.0 634.0,58.0Q612.0,26.0 571.0,13.0Q530.0,0.0 473.0,0.0ZM227.0,200.0Q235.0,222.0 249.5,243.0Q264.0,264.0 294.0,289.5Q324.0,315.0 376.0,350.0Q430.0,386.0 461.0,413.0Q492.0,440.0 505.0,467.5Q518.0,495.0 518.0,534.0Q518.0,566.0 504.5,591.0Q491.0,616.0 457.0,630.5Q423.0,645.0 363.0,645.0Q269.0,645.0 224.5,611.0Q180.0,577.0 180.0,483.0L180.0,151.0L183.0,151.0Q187.0,159.0 197.5,173.5Q208.0,188.0 227.0,200.0ZM473.0,79.0Q520.0,79.0 541.5,94.0Q563.0,109.0 563.0,146.0Q563.0,187.0 538.5,214.0Q514.0,241.0 479.0,254.0Q444.0,267.0 412.0,267.0Q393.0,267.0 385.0,264.0Q366.0,255.0 346.0,237.0Q326.0,219.0 312.0,195.5Q298.0,172.0 298.0,145.0Q298.0,109.0 319.0,94.0Q340.0,79.0 380.0,79.0L473.0,79.0Z"/> <path id="g205" d="M393.0,653.0L349.0,598.0Q345.0,603.0 339.0,608.0Q333.0,613.0 315.0,613.0L155.0,613.0Q104.0,613.0 72.0,632.0Q40.0,651.0 40.0,708.0Q40.0,765.0 74.0,800.0Q108.0,835.0 187.0,835.0L306.0,835.0L283.0,765.0L197.0,765.0Q154.0,765.0 135.0,752.5Q116.0,740.0 116.0,713.0Q116.0,696.0 127.5,689.5Q139.0,683.0 161.0,683.0L332.0,683.0Q364.0,683.0 375.5,672.5Q387.0,662.0 393.0,653.0Z"/> <path id="g129" d="M151.0,-141.0Q151.0,-172.0 132.5,-186.0Q114.0,-200.0 86.0,-200.0Q58.0,-200.0 39.0,-186.0Q20.0,-172.0 20.0,-141.0Q20.0,-110.0 39.0,-95.0Q58.0,-80.0 86.0,-80.0Q115.0,-80.0 133.0,-95.0Q151.0,-110.0 151.0,-141.0Z"/> <path id="g206" d="M20.0,687.0Q46.0,704.0 69.5,737.5Q93.0,771.0 93.0,815.0Q93.0,840.0 88.0,856.5Q83.0,873.0 79.0,880.0L164.0,900.0Q169.0,894.0 174.0,877.5Q179.0,861.0 179.0,833.0Q179.0,785.0 157.0,747.0Q135.0,709.0 107.5,683.0Q80.0,657.0 62.0,645.0L20.0,687.0Z"/> </defs> <g transform="translate(242,196)"> <use href="#g128"/> </g> <g transform="translate(0,0)"> <use href="#g13"/> </g> <g transform="translate(843,206)"> <use href="#g205"/> </g> <g transform="translate(982,-7)"> <use href="#g129"/> </g> <g transform="translate(711,0)"> <use href="#g13"/> </g> <g transform="translate(1707,177)"> <use href="#g206"/> </g> <g transform="translate(1422,0)"> <use href="#g13"/> </g> </svg>  Expected: <svg style="height:100px;margin:10px;" xmlns="http://www.w3.org/2000/svg" viewBox="0 -724 2223 1793" transform="matrix(1 0 0 -1 0 0)"> <defs> <path id="g128" d="M176.0,670.0Q176.0,639.0 157.5,625.0Q139.0,611.0 111.0,611.0Q83.0,611.0 64.0,625.0Q45.0,639.0 45.0,670.0Q45.0,700.0 64.0,715.0Q83.0,730.0 111.0,730.0Q140.0,730.0 158.0,715.0Q176.0,700.0 176.0,670.0Z"/> <path id="g13" d="M473.0,0.0L357.0,0.0Q287.0,0.0 253.5,33.0Q220.0,66.0 220.0,109.0L215.0,109.0Q208.0,102.0 196.5,83.0Q185.0,64.0 180.0,38.0L180.0,0.0L90.0,0.0L90.0,483.0Q90.0,612.0 153.5,668.0Q217.0,724.0 363.0,724.0Q497.0,724.0 554.0,676.5Q611.0,629.0 611.0,545.0Q611.0,465.0 577.5,417.0Q544.0,369.0 490.0,330.0L491.0,326.0Q512.0,322.0 540.0,311.5Q568.0,301.0 594.5,281.0Q621.0,261.0 638.5,228.0Q656.0,195.0 656.0,147.0Q656.0,90.0 634.0,58.0Q612.0,26.0 571.0,13.0Q530.0,0.0 473.0,0.0ZM227.0,200.0Q235.0,222.0 249.5,243.0Q264.0,264.0 294.0,289.5Q324.0,315.0 376.0,350.0Q430.0,386.0 461.0,413.0Q492.0,440.0 505.0,467.5Q518.0,495.0 518.0,534.0Q518.0,566.0 504.5,591.0Q491.0,616.0 457.0,630.5Q423.0,645.0 363.0,645.0Q269.0,645.0 224.5,611.0Q180.0,577.0 180.0,483.0L180.0,151.0L183.0,151.0Q187.0,159.0 197.5,173.5Q208.0,188.0 227.0,200.0ZM473.0,79.0Q520.0,79.0 541.5,94.0Q563.0,109.0 563.0,146.0Q563.0,187.0 538.5,214.0Q514.0,241.0 479.0,254.0Q444.0,267.0 412.0,267.0Q393.0,267.0 385.0,264.0Q366.0,255.0 346.0,237.0Q326.0,219.0 312.0,195.5Q298.0,172.0 298.0,145.0Q298.0,109.0 319.0,94.0Q340.0,79.0 380.0,79.0L473.0,79.0Z"/> <path id="g206" d="M20.0,687.0Q46.0,704.0 69.5,737.5Q93.0,771.0 93.0,815.0Q93.0,840.0 88.0,856.5Q83.0,873.0 79.0,880.0L164.0,900.0Q169.0,894.0 174.0,877.5Q179.0,861.0 179.0,833.0Q179.0,785.0 157.0,747.0Q135.0,709.0 107.5,683.0Q80.0,657.0 62.0,645.0L20.0,687.0Z"/> <path id="g129" d="M151.0,-141.0Q151.0,-172.0 132.5,-186.0Q114.0,-200.0 86.0,-200.0Q58.0,-200.0 39.0,-186.0Q20.0,-172.0 20.0,-141.0Q20.0,-110.0 39.0,-95.0Q58.0,-80.0 86.0,-80.0Q115.0,-80.0 133.0,-95.0Q151.0,-110.0 151.0,-141.0Z"/> </defs> <g transform="translate(242,196)"> <use href="#g128"/> </g> <g transform="translate(0,0)"> <use href="#g13"/> </g> <g transform="translate(996,177)"> <use href="#g206"/> </g> <g transform="translate(982,-7)"> <use href="#g129"/> </g> <g transform="translate(711,0)"> <use href="#g13"/> </g> <g transform="translate(1707,177)"> <use href="#g206"/> </g> <g transform="translate(1422,0)"> <use href="#g13"/> </g> </svg></p>
</li>
</ul>
 [code: shaping-regression]



</div>
</details>

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
<td align="left">Shaper didn't attach acutecomb to uni0237</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to J</td>
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
    <summary>⚠️ <b>WARN</b> Are any segments inordinately short? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have segments which seem very short:</p>
<pre><code>* u1E900 (U+1E900) contains a short segment L&lt;&lt;523.0,639.0&gt;--&lt;520.0,635.0&gt;&gt;

* u1E907 (U+1E907) contains a short segment L&lt;&lt;461.0,242.0&gt;--&lt;456.0,244.0&gt;&gt;

* u1E90D (U+1E90D) contains a short segment L&lt;&lt;514.0,66.0&gt;--&lt;509.0,67.0&gt;&gt;

* u1E90D (U+1E90D) contains a short segment L&lt;&lt;170.0,440.0&gt;--&lt;174.0,439.0&gt;&gt;

* u1E909 (U+1E909) contains a short segment L&lt;&lt;180.0,151.0&gt;--&lt;183.0,151.0&gt;&gt;

* u1E90A (U+1E90A) contains a short segment L&lt;&lt;180.0,436.0&gt;--&lt;184.0,435.0&gt;&gt;

* u1E902 (U+1E902) contains a short segment L&lt;&lt;626.0,412.0&gt;--&lt;624.0,413.0&gt;&gt;

* u1E902 (U+1E902) contains a short segment L&lt;&lt;475.0,384.0&gt;--&lt;478.0,384.0&gt;&gt;

* M (U+004D) contains a short segment L&lt;&lt;177.0,626.0&gt;--&lt;173.0,626.0&gt;&gt;

* M (U+004D) contains a short segment L&lt;&lt;450.0,129.0&gt;--&lt;454.0,129.0&gt;&gt;

* N (U+004E) contains a short segment L&lt;&lt;176.0,593.0&gt;--&lt;172.0,593.0&gt;&gt;

* N (U+004E) contains a short segment L&lt;&lt;582.0,123.0&gt;--&lt;586.0,123.0&gt;&gt;

* Q (U+0051) contains a short segment B&lt;&lt;416.0,-9.0&gt;-&lt;410.0,-9.0&gt;-&lt;403.5,-9.5&gt;&gt;

* Q (U+0051) contains a short segment B&lt;&lt;403.5,-9.5&gt;-&lt;397.0,-10.0&gt;-&lt;391.0,-10.0&gt;&gt;

* u1E921 (U+1E921) contains a short segment B&lt;&lt;103.5,70.0&gt;-&lt;93.0,87.0&gt;-&lt;90.0,94.0&gt;&gt;

* u1E921 (U+1E921) contains a short segment B&lt;&lt;180.0,121.0&gt;-&lt;183.0,113.0&gt;-&lt;193.0,100.5&gt;&gt;

* u1E91A (U+1E91A) contains a short segment B&lt;&lt;503.0,117.0&gt;-&lt;503.0,97.0&gt;-&lt;511.0,88.0&gt;&gt;

* u1E91A (U+1E91A) contains a short segment B&lt;&lt;511.0,88.0&gt;-&lt;519.0,79.0&gt;-&lt;538.0,79.0&gt;&gt;

* u1E913 (U+1E913) contains a short segment B&lt;&lt;477.0,439.0&gt;-&lt;477.0,430.0&gt;-&lt;476.0,422.0&gt;&gt;

* u1E913 (U+1E913) contains a short segment L&lt;&lt;637.0,435.0&gt;--&lt;632.0,436.0&gt;&gt;

* W (U+0057) contains a short segment B&lt;&lt;468.0,577.5&gt;-&lt;463.0,600.0&gt;-&lt;461.0,609.0&gt;&gt;

* u1E90F (U+1E90F) contains a short segment B&lt;&lt;376.5,354.0&gt;-&lt;388.0,345.0&gt;-&lt;393.0,338.0&gt;&gt;

* u1E90E (U+1E90E) contains a short segment L&lt;&lt;440.0,528.0&gt;--&lt;442.0,533.0&gt;&gt;

* a (U+0061) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* at (U+0040) contains a short segment B&lt;&lt;605.0,293.0&gt;-&lt;604.0,275.0&gt;-&lt;604.0,267.5&gt;&gt;

* at (U+0040) contains a short segment B&lt;&lt;604.0,267.5&gt;-&lt;604.0,260.0&gt;-&lt;604.0,257.0&gt;&gt;

* u1E926 (U+1E926) contains a short segment B&lt;&lt;413.5,507.0&gt;-&lt;399.0,503.0&gt;-&lt;390.0,497.0&gt;&gt;

* u1E929 (U+1E929) contains a short segment L&lt;&lt;378.0,244.0&gt;--&lt;373.0,245.0&gt;&gt;

* u1E948 (U+1E948) contains a short segment L&lt;&lt;180.0,707.0&gt;--&lt;184.0,707.0&gt;&gt;

* d (U+0064) contains a short segment L&lt;&lt;446.0,72.0&gt;--&lt;442.0,72.0&gt;&gt;

* u1E92F (U+1E92F) contains a short segment L&lt;&lt;174.0,484.0&gt;--&lt;179.0,482.0&gt;&gt;

* u1E92C (U+1E92C) contains a short segment L&lt;&lt;173.0,330.0&gt;--&lt;178.0,329.0&gt;&gt;

* u1E949 (U+1E949) contains a short segment L&lt;&lt;165.0,707.0&gt;--&lt;169.0,707.0&gt;&gt;

* u1E942 (U+1E942) contains a short segment L&lt;&lt;173.0,510.0&gt;--&lt;178.0,508.0&gt;&gt;

* m (U+006D) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* n (U+006E) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* u1E93B (U+1E93B) contains a short segment B&lt;&lt;267.0,290.0&gt;-&lt;259.0,292.0&gt;-&lt;248.0,294.0&gt;&gt;

* p (U+0070) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;173.0,463.0&gt;&gt;

* u1E939 (U+1E939) contains a short segment L&lt;&lt;540.0,272.0&gt;--&lt;537.0,274.0&gt;&gt;

* u1E939 (U+1E939) contains a short segment B&lt;&lt;325.0,233.0&gt;-&lt;315.0,232.0&gt;-&lt;308.0,232.0&gt;&gt;

* u1E939 (U+1E939) contains a short segment B&lt;&lt;308.0,232.0&gt;-&lt;301.0,232.0&gt;-&lt;290.0,232.0&gt;&gt;

* u1E95F (U+1E95F) contains a short segment B&lt;&lt;417.0,418.0&gt;-&lt;431.0,409.0&gt;-&lt;437.0,403.0&gt;&gt;

* u1E95F (U+1E95F) contains a short segment L&lt;&lt;89.0,451.0&gt;--&lt;89.0,473.0&gt;&gt;

* r (U+0072) contains a short segment L&lt;&lt;167.0,438.0&gt;--&lt;171.0,438.0&gt;&gt;

* two (U+0032) contains a short segment L&lt;&lt;159.0,84.0&gt;--&lt;159.0,80.0&gt;&gt;

* u1E952 (U+1E952) contains a short segment B&lt;&lt;229.0,543.0&gt;-&lt;234.0,544.0&gt;-&lt;236.5,544.0&gt;&gt;

* u1E952 (U+1E952) contains a short segment B&lt;&lt;236.5,544.0&gt;-&lt;239.0,544.0&gt;-&lt;240.0,544.0&gt;&gt;

* u (U+0075) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* u1E935 (U+1E935) contains a short segment L&lt;&lt;534.0,357.0&gt;--&lt;531.0,358.0&gt;&gt;

* u1E941 (U+1E941) contains a short segment B&lt;&lt;388.5,27.0&gt;-&lt;380.0,38.0&gt;-&lt;376.0,45.0&gt;&gt;

* u1E941 (U+1E941) contains a short segment B&lt;&lt;371.0,45.0&gt;-&lt;366.0,37.0&gt;-&lt;357.0,26.5&gt;&gt;

* Nacute (U+0143) contains a short segment L&lt;&lt;176.0,593.0&gt;--&lt;172.0,593.0&gt;&gt;

* Nacute (U+0143) contains a short segment L&lt;&lt;582.0,123.0&gt;--&lt;586.0,123.0&gt;&gt;

* Ncaron (U+0147) contains a short segment L&lt;&lt;176.0,593.0&gt;--&lt;172.0,593.0&gt;&gt;

* Ncaron (U+0147) contains a short segment L&lt;&lt;582.0,123.0&gt;--&lt;586.0,123.0&gt;&gt;

* uni0145 (U+0145) contains a short segment L&lt;&lt;176.0,593.0&gt;--&lt;172.0,593.0&gt;&gt;

* uni0145 (U+0145) contains a short segment L&lt;&lt;582.0,123.0&gt;--&lt;586.0,123.0&gt;&gt;

* Ntilde (U+00D1) contains a short segment L&lt;&lt;176.0,593.0&gt;--&lt;172.0,593.0&gt;&gt;

* Ntilde (U+00D1) contains a short segment L&lt;&lt;582.0,123.0&gt;--&lt;586.0,123.0&gt;&gt;

* Uogonek (U+0172) contains a short segment B&lt;&lt;539.5,-158.5&gt;-&lt;551.0,-156.0&gt;-&lt;559.0,-155.0&gt;&gt;

* Wacute (U+1E82) contains a short segment B&lt;&lt;468.0,577.5&gt;-&lt;463.0,600.0&gt;-&lt;461.0,609.0&gt;&gt;

* Wcircumflex (U+0174) contains a short segment B&lt;&lt;468.0,577.5&gt;-&lt;463.0,600.0&gt;-&lt;461.0,609.0&gt;&gt;

* Wdieresis (U+1E84) contains a short segment B&lt;&lt;468.0,577.5&gt;-&lt;463.0,600.0&gt;-&lt;461.0,609.0&gt;&gt;

* Wgrave (U+1E80) contains a short segment B&lt;&lt;468.0,577.5&gt;-&lt;463.0,600.0&gt;-&lt;461.0,609.0&gt;&gt;

* aacute (U+00E1) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* abreve (U+0103) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* acircumflex (U+00E2) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* adieresis (U+00E4) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* agrave (U+00E0) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* amacron (U+0101) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* aogonek (U+0105) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* aring (U+00E5) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* atilde (U+00E3) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* dcaron (U+010F) contains a short segment L&lt;&lt;446.0,72.0&gt;--&lt;442.0,72.0&gt;&gt;

* dcroat (U+0111) contains a short segment L&lt;&lt;445.0,72.0&gt;--&lt;441.0,72.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;184.0,390.0&gt;-&lt;183.0,380.0&gt;-&lt;183.0,371.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;183.0,371.0&gt;-&lt;183.0,362.0&gt;-&lt;183.0,352.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;183.0,352.0&gt;-&lt;183.0,343.0&gt;-&lt;183.0,332.5&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;183.0,332.5&gt;-&lt;183.0,322.0&gt;-&lt;184.0,311.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;95.0,311.0&gt;-&lt;94.0,323.0&gt;-&lt;94.0,331.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;94.0,331.0&gt;-&lt;94.0,339.0&gt;-&lt;94.0,352.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;94.0,352.0&gt;-&lt;94.0,363.0&gt;-&lt;94.5,373.5&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;94.5,373.5&gt;-&lt;95.0,384.0&gt;-&lt;95.0,390.0&gt;&gt;

* germandbls (U+00DF) contains a short segment B&lt;&lt;382.0,412.0&gt;-&lt;382.0,399.0&gt;-&lt;388.5,388.0&gt;&gt;

* nacute (U+0144) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* ncaron (U+0148) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* uni0146 (U+0146) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* ntilde (U+00F1) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* racute (U+0155) contains a short segment L&lt;&lt;167.0,438.0&gt;--&lt;171.0,438.0&gt;&gt;

* rcaron (U+0159) contains a short segment L&lt;&lt;167.0,438.0&gt;--&lt;171.0,438.0&gt;&gt;

* trademark (U+2122) contains a short segment L&lt;&lt;386.0,633.0&gt;--&lt;382.0,633.0&gt;&gt;

* uacute (U+00FA) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* ucircumflex (U+00FB) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* udieresis (U+00FC) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* ugrave (U+00F9) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* uhungarumlaut (U+0171) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* umacron (U+016B) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* uogonek (U+0173) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* uring (U+016F) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;
</code></pre>
 [code: found-short-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* u1E918 (U+1E918): L&lt;&lt;164.0,714.0&gt;--&lt;165.0,475.0&gt;&gt;
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
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Fur (Latn, 1,230,163 speakers), Koonzime (Latn, 40,000 speakers), Cicipu (Latn, 44,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Vute (Latn, 21,000 speakers), Ebira (Latn, 2,200,000 speakers), Gulay (Latn, 250,478 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Igbo (Latn, 27,823,640 speakers), Navajo (Latn, 166,319 speakers), Makaa (Latn, 221,000 speakers), Mundani (Latn, 34,000 speakers), Dii (Latn, 71,000 speakers), Zapotec (Latn, 490,000 speakers), Bafut (Latn, 158,146 speakers), Basaa (Latn, 332,940 speakers), Sar (Latn, 500,000 speakers), Kom (Latn, 360,685 speakers), Bete-Bendi (Latn, 100,000 speakers), Ejagham (Latn, 120,000 speakers), Ekpeye (Latn, 226,000 speakers), Nzakara (Latn, 50,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Yala (Latn, 200,000 speakers), Nateni (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Southern Kisi (Latn, 360,000 speakers), Dutch (Latn, 31,709,104 speakers), Ma’di (Latn, 584,000 speakers), Dan (Latn, 1,099,244 speakers), South Central Banda (Latn, 244,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mfumte (Latn, 79,000 speakers), Avokaya (Latn, 100,000 speakers), Mango (Latn, 77,000 speakers), Lugbara (Latn, 2,200,000 speakers).</p>
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
<li>U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh</li>
<li>U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition</li>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, coptic, tifinagh, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, tifinagh, syriac, tai-le, canadian-aboriginal, malayalam, coptic, math</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: not included in any glyphset definition</li>
<li>U+0327 COMBINING CEDILLA: not included in any glyphset definition</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>adlam</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Combined length of family and style must not exceed 32 characters. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Name ID 6 'NotoSansAdlamUnjoined-Regular' exceeds 27 characters. This has been found to cause problems with PostScript printers, especially on Mac platforms.</p>
 [code: nameid6-too-long]



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

<details><summary>[11] NotoSansAdlamUnjoined-Bold.ttf</summary>
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
<td align="left">Shaper didn't attach acutecomb to uni0237</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to J</td>
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
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* u1E907 (U+1E907): X=280.0,Y=2.0 (should be at baseline 0?)

* C (U+0043): X=482.0,Y=-1.0 (should be at baseline 0?)

* G (U+0047): X=527.5,Y=1.0 (should be at baseline 0?)

* G (U+0047): X=543.0,Y=712.0 (should be at cap-height 714?)

* u1E91B (U+1E91B): X=152.0,Y=-2.0 (should be at baseline 0?)

* u1E921 (U+1E921): X=196.5,Y=1.0 (should be at baseline 0?)

* u1E91A (U+1E91A): X=374.0,Y=712.0 (should be at cap-height 714?)

* u1E91A (U+1E91A): X=562.0,Y=712.5 (should be at cap-height 714?)

* b (U+0062): X=227.0,Y=583.0 (should be at x-height 585?)

* c (U+0063): X=394.5,Y=-0.5 (should be at baseline 0?)

* e (U+0065): X=432.5,Y=-0.5 (should be at baseline 0?)

* f (U+0066): X=102.0,Y=586.0 (should be at x-height 585?)

* u1E955 (U+1E955): X=352.5,Y=715.5 (should be at cap-height 714?)

* g (U+0067): X=555.0,Y=-1.0 (should be at baseline 0?)

* uni2E28 (U+2E28): X=404.0,Y=712.0 (should be at cap-height 714?)

* uni2E28 (U+2E28): X=526.0,Y=712.0 (should be at cap-height 714?)

* numbersign (U+0023): X=236.0,Y=713.0 (should be at cap-height 714?)

* numbersign (U+0023): X=343.0,Y=713.0 (should be at cap-height 714?)

* numbersign (U+0023): X=440.0,Y=713.0 (should be at cap-height 714?)

* numbersign (U+0023): X=545.0,Y=713.0 (should be at cap-height 714?)

* u1E927 (U+1E927): X=518.0,Y=1.0 (should be at baseline 0?)

* six (U+0036): X=489.0,Y=715.0 (should be at cap-height 714?)

* u1E945 (U+1E945): X=426.5,Y=712.5 (should be at cap-height 714?)

* u1E950 (U+1E950): X=223.5,Y=0.5 (should be at baseline 0?)

* Cacute (U+0106): X=482.0,Y=-1.0 (should be at baseline 0?)

* Ccaron (U+010C): X=482.0,Y=-1.0 (should be at baseline 0?)

* Ccedilla (U+00C7): X=482.0,Y=-1.0 (should be at baseline 0?)

* Cdotaccent (U+010A): X=482.0,Y=-1.0 (should be at baseline 0?)

* Gbreve (U+011E): X=527.5,Y=1.0 (should be at baseline 0?)

* Gbreve (U+011E): X=543.0,Y=712.0 (should be at cap-height 714?)

* uni0122 (U+0122): X=527.5,Y=1.0 (should be at baseline 0?)

* uni0122 (U+0122): X=543.0,Y=712.0 (should be at cap-height 714?)

* Gdotaccent (U+0120): X=527.5,Y=1.0 (should be at baseline 0?)

* Gdotaccent (U+0120): X=543.0,Y=712.0 (should be at cap-height 714?)

* uni1E9E (U+1E9E): X=371.5,Y=-1.0 (should be at baseline 0?)

* abreve (U+0103): X=249.0,Y=713.5 (should be at cap-height 714?)

* abreve (U+0103): X=348.5,Y=714.5 (should be at cap-height 714?)

* ae (U+00E6): X=758.0,Y=-0.5 (should be at baseline 0?)

* ae (U+00E6): X=311.0,Y=0.5 (should be at baseline 0?)

* breve (U+02D8): X=179.0,Y=713.5 (should be at cap-height 714?)

* breve (U+02D8): X=278.5,Y=714.5 (should be at cap-height 714?)

* uni0306 (U+0306): X=-50.0,Y=713.5 (should be at cap-height 714?)

* uni0306 (U+0306): X=49.5,Y=714.5 (should be at cap-height 714?)

* cacute (U+0107): X=394.5,Y=-0.5 (should be at baseline 0?)

* ccaron (U+010D): X=394.5,Y=-0.5 (should be at baseline 0?)

* ccedilla (U+00E7): X=394.5,Y=-0.5 (should be at baseline 0?)

* cdotaccent (U+010B): X=394.5,Y=-0.5 (should be at baseline 0?)

* eacute (U+00E9): X=432.5,Y=-0.5 (should be at baseline 0?)

* ecaron (U+011B): X=432.5,Y=-0.5 (should be at baseline 0?)

* ecircumflex (U+00EA): X=432.5,Y=-0.5 (should be at baseline 0?)

* edieresis (U+00EB): X=432.5,Y=-0.5 (should be at baseline 0?)

* edotaccent (U+0117): X=432.5,Y=-0.5 (should be at baseline 0?)

* egrave (U+00E8): X=432.5,Y=-0.5 (should be at baseline 0?)

* emacron (U+0113): X=432.5,Y=-0.5 (should be at baseline 0?)

* gbreve (U+011F): X=555.0,Y=-1.0 (should be at baseline 0?)

* gbreve (U+011F): X=261.0,Y=713.5 (should be at cap-height 714?)

* gbreve (U+011F): X=360.5,Y=714.5 (should be at cap-height 714?)

* uni0123 (U+0123): X=555.0,Y=-1.0 (should be at baseline 0?)

* gdotaccent (U+0121): X=555.0,Y=-1.0 (should be at baseline 0?)

* oe (U+0153): X=816.5,Y=-0.5 (should be at baseline 0?)

* sterling (U+00A3): X=444.5,Y=712.5 (should be at cap-height 714?)
</code></pre>
 [code: found-misalignments]



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
<pre><code>* u1E918 (U+1E918): L&lt;&lt;215.0,714.0&gt;--&lt;216.0,498.0&gt;&gt;
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
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Fur (Latn, 1,230,163 speakers), Koonzime (Latn, 40,000 speakers), Cicipu (Latn, 44,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Vute (Latn, 21,000 speakers), Ebira (Latn, 2,200,000 speakers), Gulay (Latn, 250,478 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Igbo (Latn, 27,823,640 speakers), Navajo (Latn, 166,319 speakers), Makaa (Latn, 221,000 speakers), Mundani (Latn, 34,000 speakers), Dii (Latn, 71,000 speakers), Zapotec (Latn, 490,000 speakers), Bafut (Latn, 158,146 speakers), Basaa (Latn, 332,940 speakers), Sar (Latn, 500,000 speakers), Kom (Latn, 360,685 speakers), Bete-Bendi (Latn, 100,000 speakers), Ejagham (Latn, 120,000 speakers), Ekpeye (Latn, 226,000 speakers), Nzakara (Latn, 50,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Yala (Latn, 200,000 speakers), Nateni (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Southern Kisi (Latn, 360,000 speakers), Dutch (Latn, 31,709,104 speakers), Ma’di (Latn, 584,000 speakers), Dan (Latn, 1,099,244 speakers), South Central Banda (Latn, 244,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mfumte (Latn, 79,000 speakers), Avokaya (Latn, 100,000 speakers), Mango (Latn, 77,000 speakers), Lugbara (Latn, 2,200,000 speakers).</p>
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
<li>U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh</li>
<li>U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition</li>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, coptic, tifinagh, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, tifinagh, syriac, tai-le, canadian-aboriginal, malayalam, coptic, math</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
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
| 0 | 0 | 5 | 20 | 230 | 11 | 218 | 0 | 
| 0% | 0% | 1% | 4% | 48% | 2% | 45% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
