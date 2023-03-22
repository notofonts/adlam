## Fontbakery report

Fontbakery version: 0.8.11

<details><summary><b>[4] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoSansAdlamUnjoined/googlefonts/ttf', 'fonts/NotoSansAdlamUnjoined/googlefonts/variable-ttf'] [code: single-directory]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE proportion? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_proportion">com.google.fonts/check/family/panose_proportion</a>)</summary><div>


* 🔥 **FAIL** PANOSE proportion is not the same across this family. In order to fix this, please make sure that the panose.bProportion value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE family type? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_familytype">com.google.fonts/check/family/panose_familytype</a>)</summary><div>


* 🔥 **FAIL** PANOSE family type is not the same across this family. In order to fix this, please make sure that the panose.bFamilyType value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that OS/2.fsSelection bold & italic settings are unique for each NameID1 (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.adobe.fonts/check/family/bold_italic_unique_for_nameid1">com.adobe.fonts/check/family/bold_italic_unique_for_nameid1</a>)</summary><div>


* 🔥 **FAIL** Family 'Noto Sans Adlam Unjoined' has 2 fonts (should be no more than 1) with the same OS/2.fsSelection bold & italic settings: Bold=False, Italic=False [code: unique-fsselection]
</div></details><br></div></details><details><summary><b>[11] NotoSansAdlamUnjoined-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ ĭ i̇ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Adlam Unjoined' / SUBFAMILY_NAME = 'Bold'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- guillemotleft.1 

	- guillemotright.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* numbersign (U+0023): X=236.0,Y=713.0 (should be at cap-height 714?)

	* numbersign (U+0023): X=343.0,Y=713.0 (should be at cap-height 714?)

	* numbersign (U+0023): X=440.0,Y=713.0 (should be at cap-height 714?)

	* numbersign (U+0023): X=545.0,Y=713.0 (should be at cap-height 714?)

	* six (U+0036): X=489.0,Y=715.0 (should be at cap-height 714?)

	* C (U+0043): X=482.0,Y=-1.0 (should be at baseline 0?)

	* G (U+0047): X=527.5,Y=1.0 (should be at baseline 0?)

	* G (U+0047): X=543.0,Y=712.0 (should be at cap-height 714?)

	* b (U+0062): X=227.0,Y=583.0 (should be at x-height 585?)

	* c (U+0063): X=394.5,Y=-0.5 (should be at baseline 0?) 

	* 54 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
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

	* 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* u1E918 (U+1E918): L<<215.0,714.0>--<216.0,498.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[10] NotoSansAdlamUnjoined-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ ĭ i̇ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/issues.json: Expected and actual shaping not matching
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSansAdlamUnjoined/googlefonts/ttf/NotoSansAdlamUnjoined-Regular.ttf);}
    .tf { font-family: "TestFont"; }
    .shaping pre { font-size: 1.2rem; }
    .shaping li {
        font-size: 1.2rem;
        border-top: 1px solid #ddd;
        padding: 12px;
        margin-top: 12px;
    }
    .shaping-svg {
        height: 100px;
        margin: 10px;
        transform: matrix(1, 0, 0, -1, 0, 0);
    }
</style>

<h4>qa/shaping_tests/issues.json: Expected and actual shaping not matching</h4>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𞤉𞥅𞤉𞥊𞥅𞤉𞥊</span> (#3)</li>


<pre>Expected: u1E94A=5@242,196+0|u1E909=5+711|u1E945.case=2@285,177+0|u1E94A.below=2@271,-7+0|u1E909=2+711|u1E945.case=0@285,177+0|u1E909=0+711</pre>



<pre>Got     : u1E94A=5+0|u1E909=5+711|u1E945=2+0|u1E94A.below=2+0|u1E909=2+711|u1E945.case=0+0|u1E909=0+711</pre>



<pre>                  ++++++++                      +++++  ++++++++                 +++++++                             ++++++++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2133 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M176.0,670.0Q176.0,639.0 157.5,625.0Q139.0,611.0 111.0,611.0Q83.0,611.0 64.0,625.0Q45.0,639.0 45.0,670.0Q45.0,700.0 64.0,715.0Q83.0,730.0 111.0,730.0Q140.0,730.0 158.0,715.0Q176.0,700.0 176.0,670.0Z" transform="translate(0, 793)"/>
<path d="M473.0,0.0L357.0,0.0Q287.0,0.0 253.5,33.0Q220.0,66.0 220.0,109.0L215.0,109.0Q208.0,102.0 196.5,83.0Q185.0,64.0 180.0,38.0L180.0,0.0L90.0,0.0L90.0,483.0Q90.0,612.0 153.5,668.0Q217.0,724.0 363.0,724.0Q497.0,724.0 554.0,676.5Q611.0,629.0 611.0,545.0Q611.0,465.0 577.5,417.0Q544.0,369.0 490.0,330.0L491.0,326.0Q512.0,322.0 540.0,311.5Q568.0,301.0 594.5,281.0Q621.0,261.0 638.5,228.0Q656.0,195.0 656.0,147.0Q656.0,90.0 634.0,58.0Q612.0,26.0 571.0,13.0Q530.0,0.0 473.0,0.0ZM227.0,200.0Q235.0,222.0 249.5,243.0Q264.0,264.0 294.0,289.5Q324.0,315.0 376.0,350.0Q430.0,386.0 461.0,413.0Q492.0,440.0 505.0,467.5Q518.0,495.0 518.0,534.0Q518.0,566.0 504.5,591.0Q491.0,616.0 457.0,630.5Q423.0,645.0 363.0,645.0Q269.0,645.0 224.5,611.0Q180.0,577.0 180.0,483.0L180.0,151.0L183.0,151.0Q187.0,159.0 197.5,173.5Q208.0,188.0 227.0,200.0ZM473.0,79.0Q520.0,79.0 541.5,94.0Q563.0,109.0 563.0,146.0Q563.0,187.0 538.5,214.0Q514.0,241.0 479.0,254.0Q444.0,267.0 412.0,267.0Q393.0,267.0 385.0,264.0Q366.0,255.0 346.0,237.0Q326.0,219.0 312.0,195.5Q298.0,172.0 298.0,145.0Q298.0,109.0 319.0,94.0Q340.0,79.0 380.0,79.0L473.0,79.0Z" transform="translate(0, 793)"/>
<path d="M393.0,653.0L349.0,598.0Q345.0,603.0 339.0,608.0Q333.0,613.0 315.0,613.0L155.0,613.0Q104.0,613.0 72.0,632.0Q40.0,651.0 40.0,708.0Q40.0,765.0 74.0,800.0Q108.0,835.0 187.0,835.0L306.0,835.0L283.0,765.0L197.0,765.0Q154.0,765.0 135.0,752.5Q116.0,740.0 116.0,713.0Q116.0,696.0 127.5,689.5Q139.0,683.0 161.0,683.0L332.0,683.0Q364.0,683.0 375.5,672.5Q387.0,662.0 393.0,653.0Z" transform="translate(711, 793)"/>
<path d="M151.0,-141.0Q151.0,-172.0 132.5,-186.0Q114.0,-200.0 86.0,-200.0Q58.0,-200.0 39.0,-186.0Q20.0,-172.0 20.0,-141.0Q20.0,-110.0 39.0,-95.0Q58.0,-80.0 86.0,-80.0Q115.0,-80.0 133.0,-95.0Q151.0,-110.0 151.0,-141.0Z" transform="translate(711, 793)"/>
<path d="M473.0,0.0L357.0,0.0Q287.0,0.0 253.5,33.0Q220.0,66.0 220.0,109.0L215.0,109.0Q208.0,102.0 196.5,83.0Q185.0,64.0 180.0,38.0L180.0,0.0L90.0,0.0L90.0,483.0Q90.0,612.0 153.5,668.0Q217.0,724.0 363.0,724.0Q497.0,724.0 554.0,676.5Q611.0,629.0 611.0,545.0Q611.0,465.0 577.5,417.0Q544.0,369.0 490.0,330.0L491.0,326.0Q512.0,322.0 540.0,311.5Q568.0,301.0 594.5,281.0Q621.0,261.0 638.5,228.0Q656.0,195.0 656.0,147.0Q656.0,90.0 634.0,58.0Q612.0,26.0 571.0,13.0Q530.0,0.0 473.0,0.0ZM227.0,200.0Q235.0,222.0 249.5,243.0Q264.0,264.0 294.0,289.5Q324.0,315.0 376.0,350.0Q430.0,386.0 461.0,413.0Q492.0,440.0 505.0,467.5Q518.0,495.0 518.0,534.0Q518.0,566.0 504.5,591.0Q491.0,616.0 457.0,630.5Q423.0,645.0 363.0,645.0Q269.0,645.0 224.5,611.0Q180.0,577.0 180.0,483.0L180.0,151.0L183.0,151.0Q187.0,159.0 197.5,173.5Q208.0,188.0 227.0,200.0ZM473.0,79.0Q520.0,79.0 541.5,94.0Q563.0,109.0 563.0,146.0Q563.0,187.0 538.5,214.0Q514.0,241.0 479.0,254.0Q444.0,267.0 412.0,267.0Q393.0,267.0 385.0,264.0Q366.0,255.0 346.0,237.0Q326.0,219.0 312.0,195.5Q298.0,172.0 298.0,145.0Q298.0,109.0 319.0,94.0Q340.0,79.0 380.0,79.0L473.0,79.0Z" transform="translate(711, 793)"/>
<path d="M20.0,687.0Q46.0,704.0 69.5,737.5Q93.0,771.0 93.0,815.0Q93.0,840.0 88.0,856.5Q83.0,873.0 79.0,880.0L164.0,900.0Q169.0,894.0 174.0,877.5Q179.0,861.0 179.0,833.0Q179.0,785.0 157.0,747.0Q135.0,709.0 107.5,683.0Q80.0,657.0 62.0,645.0L20.0,687.0Z" transform="translate(1422, 793)"/>
<path d="M473.0,0.0L357.0,0.0Q287.0,0.0 253.5,33.0Q220.0,66.0 220.0,109.0L215.0,109.0Q208.0,102.0 196.5,83.0Q185.0,64.0 180.0,38.0L180.0,0.0L90.0,0.0L90.0,483.0Q90.0,612.0 153.5,668.0Q217.0,724.0 363.0,724.0Q497.0,724.0 554.0,676.5Q611.0,629.0 611.0,545.0Q611.0,465.0 577.5,417.0Q544.0,369.0 490.0,330.0L491.0,326.0Q512.0,322.0 540.0,311.5Q568.0,301.0 594.5,281.0Q621.0,261.0 638.5,228.0Q656.0,195.0 656.0,147.0Q656.0,90.0 634.0,58.0Q612.0,26.0 571.0,13.0Q530.0,0.0 473.0,0.0ZM227.0,200.0Q235.0,222.0 249.5,243.0Q264.0,264.0 294.0,289.5Q324.0,315.0 376.0,350.0Q430.0,386.0 461.0,413.0Q492.0,440.0 505.0,467.5Q518.0,495.0 518.0,534.0Q518.0,566.0 504.5,591.0Q491.0,616.0 457.0,630.5Q423.0,645.0 363.0,645.0Q269.0,645.0 224.5,611.0Q180.0,577.0 180.0,483.0L180.0,151.0L183.0,151.0Q187.0,159.0 197.5,173.5Q208.0,188.0 227.0,200.0ZM473.0,79.0Q520.0,79.0 541.5,94.0Q563.0,109.0 563.0,146.0Q563.0,187.0 538.5,214.0Q514.0,241.0 479.0,254.0Q444.0,267.0 412.0,267.0Q393.0,267.0 385.0,264.0Q366.0,255.0 346.0,237.0Q326.0,219.0 312.0,195.5Q298.0,172.0 298.0,145.0Q298.0,109.0 319.0,94.0Q340.0,79.0 380.0,79.0L473.0,79.0Z" transform="translate(1422, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2133 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M176.0,670.0Q176.0,639.0 157.5,625.0Q139.0,611.0 111.0,611.0Q83.0,611.0 64.0,625.0Q45.0,639.0 45.0,670.0Q45.0,700.0 64.0,715.0Q83.0,730.0 111.0,730.0Q140.0,730.0 158.0,715.0Q176.0,700.0 176.0,670.0Z" transform="translate(242, 989)"/>
<path d="M473.0,0.0L357.0,0.0Q287.0,0.0 253.5,33.0Q220.0,66.0 220.0,109.0L215.0,109.0Q208.0,102.0 196.5,83.0Q185.0,64.0 180.0,38.0L180.0,0.0L90.0,0.0L90.0,483.0Q90.0,612.0 153.5,668.0Q217.0,724.0 363.0,724.0Q497.0,724.0 554.0,676.5Q611.0,629.0 611.0,545.0Q611.0,465.0 577.5,417.0Q544.0,369.0 490.0,330.0L491.0,326.0Q512.0,322.0 540.0,311.5Q568.0,301.0 594.5,281.0Q621.0,261.0 638.5,228.0Q656.0,195.0 656.0,147.0Q656.0,90.0 634.0,58.0Q612.0,26.0 571.0,13.0Q530.0,0.0 473.0,0.0ZM227.0,200.0Q235.0,222.0 249.5,243.0Q264.0,264.0 294.0,289.5Q324.0,315.0 376.0,350.0Q430.0,386.0 461.0,413.0Q492.0,440.0 505.0,467.5Q518.0,495.0 518.0,534.0Q518.0,566.0 504.5,591.0Q491.0,616.0 457.0,630.5Q423.0,645.0 363.0,645.0Q269.0,645.0 224.5,611.0Q180.0,577.0 180.0,483.0L180.0,151.0L183.0,151.0Q187.0,159.0 197.5,173.5Q208.0,188.0 227.0,200.0ZM473.0,79.0Q520.0,79.0 541.5,94.0Q563.0,109.0 563.0,146.0Q563.0,187.0 538.5,214.0Q514.0,241.0 479.0,254.0Q444.0,267.0 412.0,267.0Q393.0,267.0 385.0,264.0Q366.0,255.0 346.0,237.0Q326.0,219.0 312.0,195.5Q298.0,172.0 298.0,145.0Q298.0,109.0 319.0,94.0Q340.0,79.0 380.0,79.0L473.0,79.0Z" transform="translate(0, 793)"/>
<path d="M20.0,687.0Q46.0,704.0 69.5,737.5Q93.0,771.0 93.0,815.0Q93.0,840.0 88.0,856.5Q83.0,873.0 79.0,880.0L164.0,900.0Q169.0,894.0 174.0,877.5Q179.0,861.0 179.0,833.0Q179.0,785.0 157.0,747.0Q135.0,709.0 107.5,683.0Q80.0,657.0 62.0,645.0L20.0,687.0Z" transform="translate(996, 970)"/>
<path d="M151.0,-141.0Q151.0,-172.0 132.5,-186.0Q114.0,-200.0 86.0,-200.0Q58.0,-200.0 39.0,-186.0Q20.0,-172.0 20.0,-141.0Q20.0,-110.0 39.0,-95.0Q58.0,-80.0 86.0,-80.0Q115.0,-80.0 133.0,-95.0Q151.0,-110.0 151.0,-141.0Z" transform="translate(982, 786)"/>
<path d="M473.0,0.0L357.0,0.0Q287.0,0.0 253.5,33.0Q220.0,66.0 220.0,109.0L215.0,109.0Q208.0,102.0 196.5,83.0Q185.0,64.0 180.0,38.0L180.0,0.0L90.0,0.0L90.0,483.0Q90.0,612.0 153.5,668.0Q217.0,724.0 363.0,724.0Q497.0,724.0 554.0,676.5Q611.0,629.0 611.0,545.0Q611.0,465.0 577.5,417.0Q544.0,369.0 490.0,330.0L491.0,326.0Q512.0,322.0 540.0,311.5Q568.0,301.0 594.5,281.0Q621.0,261.0 638.5,228.0Q656.0,195.0 656.0,147.0Q656.0,90.0 634.0,58.0Q612.0,26.0 571.0,13.0Q530.0,0.0 473.0,0.0ZM227.0,200.0Q235.0,222.0 249.5,243.0Q264.0,264.0 294.0,289.5Q324.0,315.0 376.0,350.0Q430.0,386.0 461.0,413.0Q492.0,440.0 505.0,467.5Q518.0,495.0 518.0,534.0Q518.0,566.0 504.5,591.0Q491.0,616.0 457.0,630.5Q423.0,645.0 363.0,645.0Q269.0,645.0 224.5,611.0Q180.0,577.0 180.0,483.0L180.0,151.0L183.0,151.0Q187.0,159.0 197.5,173.5Q208.0,188.0 227.0,200.0ZM473.0,79.0Q520.0,79.0 541.5,94.0Q563.0,109.0 563.0,146.0Q563.0,187.0 538.5,214.0Q514.0,241.0 479.0,254.0Q444.0,267.0 412.0,267.0Q393.0,267.0 385.0,264.0Q366.0,255.0 346.0,237.0Q326.0,219.0 312.0,195.5Q298.0,172.0 298.0,145.0Q298.0,109.0 319.0,94.0Q340.0,79.0 380.0,79.0L473.0,79.0Z" transform="translate(711, 793)"/>
<path d="M20.0,687.0Q46.0,704.0 69.5,737.5Q93.0,771.0 93.0,815.0Q93.0,840.0 88.0,856.5Q83.0,873.0 79.0,880.0L164.0,900.0Q169.0,894.0 174.0,877.5Q179.0,861.0 179.0,833.0Q179.0,785.0 157.0,747.0Q135.0,709.0 107.5,683.0Q80.0,657.0 62.0,645.0L20.0,687.0Z" transform="translate(1707, 970)"/>
<path d="M473.0,0.0L357.0,0.0Q287.0,0.0 253.5,33.0Q220.0,66.0 220.0,109.0L215.0,109.0Q208.0,102.0 196.5,83.0Q185.0,64.0 180.0,38.0L180.0,0.0L90.0,0.0L90.0,483.0Q90.0,612.0 153.5,668.0Q217.0,724.0 363.0,724.0Q497.0,724.0 554.0,676.5Q611.0,629.0 611.0,545.0Q611.0,465.0 577.5,417.0Q544.0,369.0 490.0,330.0L491.0,326.0Q512.0,322.0 540.0,311.5Q568.0,301.0 594.5,281.0Q621.0,261.0 638.5,228.0Q656.0,195.0 656.0,147.0Q656.0,90.0 634.0,58.0Q612.0,26.0 571.0,13.0Q530.0,0.0 473.0,0.0ZM227.0,200.0Q235.0,222.0 249.5,243.0Q264.0,264.0 294.0,289.5Q324.0,315.0 376.0,350.0Q430.0,386.0 461.0,413.0Q492.0,440.0 505.0,467.5Q518.0,495.0 518.0,534.0Q518.0,566.0 504.5,591.0Q491.0,616.0 457.0,630.5Q423.0,645.0 363.0,645.0Q269.0,645.0 224.5,611.0Q180.0,577.0 180.0,483.0L180.0,151.0L183.0,151.0Q187.0,159.0 197.5,173.5Q208.0,188.0 227.0,200.0ZM473.0,79.0Q520.0,79.0 541.5,94.0Q563.0,109.0 563.0,146.0Q563.0,187.0 538.5,214.0Q514.0,241.0 479.0,254.0Q444.0,267.0 412.0,267.0Q393.0,267.0 385.0,264.0Q366.0,255.0 346.0,237.0Q326.0,219.0 312.0,195.5Q298.0,172.0 298.0,145.0Q298.0,109.0 319.0,94.0Q340.0,79.0 380.0,79.0L473.0,79.0Z" transform="translate(1422, 793)"/>
</svg>


</div> [code: shaping-regression]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Adlam Unjoined' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- guillemotleft.1 

	- guillemotright.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 558 among a set of 2 math glyphs.
The following math glyphs have a different width, though:

Width = 557:
plus

Width = 545:
equal

Width = 572:
divide, multiply

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* u1E918 (U+1E918): L<<164.0,714.0>--<165.0,475.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[11] NotoSansAdlamUnjoined[wght].ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check a font's STAT table contains compulsory Axis Values. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/STAT">com.google.fonts/check/STAT</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check variable font instances (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fvar_instances">com.google.fonts/check/fvar_instances</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ ĭ i̇ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Adlam Unjoined' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure variable fonts include an avar table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/mandatory_avar_table">com.google.fonts/check/mandatory_avar_table</a>)</summary><div>


* ⚠ **WARN** This variable font does not have an avar table. [code: missing-avar]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- guillemotleft.1 

	- guillemotright.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 558 among a set of 2 math glyphs.
The following math glyphs have a different width, though:

Width = 557:
plus

Width = 545:
equal

Width = 572:
divide, multiply

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 3 | 11 | 22 | 326 | 20 | 312 | 0 |
| 0% | 2% | 3% | 47% | 3% | 45% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
