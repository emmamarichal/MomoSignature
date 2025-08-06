## FontSpector report

fontspector version: 1.3.0






## Check results




<details><summary>[19] MomoSignature-Regular.ttf</summary>
<div>


<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. (googlefonts/glyphsets/shape_languages)</summary>
    <div>








- 🔥 **FAIL** Failed language shaping:

| Message                                                     | Languages              |
|-------------------------------------------------------------|------------------------|
| Mandatory orthography codepoints:                           | * vi_Latn (Vietnamese) |
|   The following mark characters are missing from the font: ̣ |                        | [code: failed-language-shaping]
  
  


- ⚠️ **WARN** Warning language shaping:

| Message                                                              | Languages                    |
|----------------------------------------------------------------------|------------------------------|
| Auxiliary orthography codepoints:                                    | * de_Latn (German)           |
|   The following auxiliary characters are missing from the font: ſ    | * fr_Latn (French)           |
| Auxiliary orthography codepoints:                                    | * lt_Latn (Lithuanian)       |
|   Shaper didn't attach tildecomb to L.ss03 when shaping the text 'L̃' |                              |
|   Shaper didn't attach tildecomb to M.ss03 when shaping the text 'M̃' |                              |
|   Shaper didn't attach tildecomb to R.ss03 when shaping the text 'R̃' |                              |
|   Shaper didn't attach tildecomb to l.isol when shaping the text 'l̃' |                              |
|   Shaper didn't attach tildecomb to m.isol when shaping the text 'm̃' |                              |
|   Shaper didn't attach tildecomb to r.isol when shaping the text 'r̃' |                              |
| Auxiliary orthography codepoints:                                    | * ca_Latn (Catalan)          |
|   The following auxiliary characters are missing from the font: Ŀ    |                              |
|   The following auxiliary characters are missing from the font: ŀ    |                              |
| Auxiliary orthography codepoints:                                    | * nb_Latn (Norwegian Bokmål) |
|   The following auxiliary characters are missing from the font: Ŋ    |                              |
|   The following auxiliary characters are missing from the font: Ŧ    |                              |
|   The following auxiliary characters are missing from the font: ŋ    |                              |
|   The following auxiliary characters are missing from the font: ŧ    |                              |
| Auxiliary orthography codepoints:                                    | * fi_Latn (Finnish)          |
|   The following auxiliary characters are missing from the font: Ǥ    |                              |
|   The following auxiliary characters are missing from the font: Ŋ    |                              |
|   The following auxiliary characters are missing from the font: Ŧ    |                              |
|   The following auxiliary characters are missing from the font: Ʒ    |                              |
|   The following auxiliary characters are missing from the font: Ǯ    |                              |
|   The following auxiliary characters are missing from the font: ǥ    |                              |
|   The following auxiliary characters are missing from the font: ŋ    |                              |
|   The following auxiliary characters are missing from the font: ŧ    |                              |
|   The following auxiliary characters are missing from the font: ʒ    |                              |
|   The following auxiliary characters are missing from the font: ǯ    |                              | [code: warning-language-shaping]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Ensure dotted circle glyph is present and can attach marks. (dotted_circle)</summary>
    <div>








- 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

* uni0308
* uni0307
* gravecomb
* acutecomb
* uni030B
* uni0302
* uni030C
* uni0306
* uni030A
... and 8 others [code: unattached-dotted-circle-marks]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. (contour_count)</summary>
    <div>








- ⚠️ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are
     infered from the typical ammounts of contours observed in a
     large collection of reference font families. The divergences
     listed below may simply indicate a significantly different
     design on some of your glyphs. On the other hand, some of these
     may flag actual bugs in the font such as glyphs mapped to an
     incorrect codepoint. Please consider reviewing the design and
     codepoint assignment of these to make sure they are correct.


    The following glyphs do not have the recommended number of contours:
* uni1E20 (U+1E20): found 3, expected one of: {2}
* uni0136 (U+0136): found 1, expected one of: {3, 2, 4}
* uni013B.loclMAH (unencoded): found 4, expected one of: {2}
* G.ss01 (unencoded): found 2, expected one of: {1, 4}
* Ohorn.ss01 (unencoded): found 2, expected one of: {4, 3}
* uni1EDA.ss01 (unencoded): found 3, expected one of: {5, 4}
* uni1EE2.ss01 (unencoded): found 3, expected one of: {5, 4}
* uni1EDC.ss01 (unencoded): found 3, expected one of: {4, 5}
* uni1EDE.ss01 (unencoded): found 3, expected one of: {5, 4}
... and 54 others [code: contour-count]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? (ligature_carets)</summary>
    <div>








- ⚠️ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. (math_signs_width)</summary>
    <div>








- ⚠️ **WARN** The most common width is 602 among a set of 13  math glyphs.
The following math glyphs have a different width, though:
width=441: approxequal
width=601: greaterequal, lessequal
width=530: multiply
width=592: less, greater
width=548: logicalnot
width=534: notequal, equal
width=642: plusminus [code: width-outliers]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure indic fonts have the Indian Rupee Sign glyph. (rupee)</summary>
    <div>








- ⚠️ **WARN** Font is missing the Indian Rupee Sign glyph. Please add a glyph for Indian Rupee Sign (₹) at codepoint U+20B9. [code: missing-rupee]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking that the typoAscender exceeds the yMax of the /Agrave. (typoascender_exceeds_Agrave)</summary>
    <div>








- ⚠️ **WARN** OS/2.sTypoAscender value should be greater than 1147, but got 1100 instead [code: typoAscender]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Font has correct separator glyphs? (googlefonts/separator_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following separator glyphs are missing:
* U+2028
* U+2029 [code: missing-separator-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that
replace the dot. (soft_dotted)</summary>
    <div>








- ⚠️ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: * į̀
* į̄
* į́
* į̃
* į̂
* į̌The dot of soft dotted characters _should_ disappear in other cases, for example: * į̨̉
* į̨̀
* į̨̈
* į̨̄
* į̨́
* į̨̆
* į̨̃
* į̨̇
* į̨̂
... and 50 others [code: soft-dotted]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph (outline_direction)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have a counter-clockwise outer contour:

* b.init has a path with no bounds (probably a single point)
* b_r.liga.init has a path with no bounds (probably a single point)
* b_s.liga.init has a path with no bounds (probably a single point)
* b_r.liga.isol has a path with no bounds (probably a single point)
* b_s.liga.isol has a path with no bounds (probably a single point)
* b_r.liga.init.case has a path with no bounds (probably a single point)
* b_s.liga.init.case has a path with no bounds (probably a single point)
* b_r.liga.init.ss01 has a path with no bounds (probably a single point)
* b_s.liga.init.ss01 has a path with no bounds (probably a single point) [code: ccw-outer-contour]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? (outline_jaggy_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have jaggy segments:

* Acircumflex (U+00C2): Quad(QuadBez { p0: (941.0, 1128.0), p1: (942.0, 1127.0), p2: (941.0, 1128.0) })/Quad(QuadBez { p0: (941.0, 1128.0), p1: (942.0, 1127.0), p2: (943.0, 1126.0) }) = 0.0000012074182697257333
* uni1EA4 (U+1EA4): Quad(QuadBez { p0: (941.0, 1128.0), p1: (942.0, 1127.0), p2: (941.0, 1128.0) })/Quad(QuadBez { p0: (941.0, 1128.0), p1: (942.0, 1127.0), p2: (943.0, 1126.0) }) = 0.0000012074182697257333
* uni1EAC (U+1EAC): Quad(QuadBez { p0: (941.0, 1128.0), p1: (942.0, 1127.0), p2: (941.0, 1128.0) })/Quad(QuadBez { p0: (941.0, 1128.0), p1: (942.0, 1127.0), p2: (943.0, 1126.0) }) = 0.0000012074182697257333
* uni1EA6 (U+1EA6): Quad(QuadBez { p0: (941.0, 1128.0), p1: (942.0, 1127.0), p2: (941.0, 1128.0) })/Quad(QuadBez { p0: (941.0, 1128.0), p1: (942.0, 1127.0), p2: (943.0, 1126.0) }) = 0.0000012074182697257333
* uni1EA8 (U+1EA8): Quad(QuadBez { p0: (941.0, 1128.0), p1: (942.0, 1127.0), p2: (941.0, 1128.0) })/Quad(QuadBez { p0: (941.0, 1128.0), p1: (942.0, 1127.0), p2: (943.0, 1126.0) }) = 0.0000012074182697257333
* uni1EAA (U+1EAA): Quad(QuadBez { p0: (941.0, 1128.0), p1: (942.0, 1127.0), p2: (941.0, 1128.0) })/Quad(QuadBez { p0: (941.0, 1128.0), p1: (942.0, 1127.0), p2: (943.0, 1126.0) }) = 0.0000012074182697257333
* Ccaron (U+010C): Quad(QuadBez { p0: (450.0, 915.0), p1: (449.0, 916.0), p2: (450.0, 915.0) })/Quad(QuadBez { p0: (450.0, 915.0), p1: (449.0, 916.0), p2: (448.0, 917.0) }) = 0.0000012074182697257333
* Ccircumflex (U+0108): Quad(QuadBez { p0: (597.0, 1097.0), p1: (598.0, 1096.0), p2: (597.0, 1097.0) })/Quad(QuadBez { p0: (597.0, 1097.0), p1: (598.0, 1096.0), p2: (599.0, 1095.0) }) = 0.0000012074182697257333
* Dcaron (U+010E): Quad(QuadBez { p0: (486.0, 915.0), p1: (485.0, 916.0), p2: (486.0, 915.0) })/Quad(QuadBez { p0: (486.0, 915.0), p1: (485.0, 916.0), p2: (484.0, 917.0) }) = 0.0000012074182697257333
... and 883 others [code: found-jaggy-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments (overlapping_path_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlapping path segments:

* .notdef: Line(Line { p0: (124.0, -54.0), p1: (124.0, -54.0) }) has the same coordinates as a previous segment.
* .notdef: Line(Line { p0: (124.0, -54.0), p1: (124.0, -54.0) }) has the same coordinates as a previous segment.
* .notdef: Quad(QuadBez { p0: (124.0, -54.0), p1: (124.0, -54.0), p2: (124.0, -54.0) }) has the same coordinates as a previous segment.
* .notdef: Line(Line { p0: (52.0, 706.0), p1: (52.0, 706.0) }) has the same coordinates as a previous segment.
* .notdef: Line(Line { p0: (613.0, 710.0), p1: (613.0, 710.0) }) has the same coordinates as a previous segment.
* .notdef: Line(Line { p0: (510.0, -43.0), p1: (510.0, -43.0) }) has the same coordinates as a previous segment.
* A (U+0041): Line(Line { p0: (866.0, 120.0), p1: (866.0, 120.0) }) has the same coordinates as a previous segment.
* Aacute (U+00C1): Line(Line { p0: (866.0, 120.0), p1: (866.0, 120.0) }) has the same coordinates as a previous segment.
* Abreve (U+0102): Line(Line { p0: (866.0, 120.0), p1: (866.0, 120.0) }) has the same coordinates as a previous segment.
... and 5684 others [code: overlapping-path-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? (outline_semi_vertical)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

* r.case.ss01: Line(Line { p0: (358.0, 413.0), p1: (126.0, 414.0) })
* r.case.ss01: Line(Line { p0: (231.0, 508.0), p1: (438.0, 507.0) })
* A_r.liga: Line(Line { p0: (1343.0, 413.0), p1: (1111.0, 414.0) })
* A_r.liga: Line(Line { p0: (1216.0, 508.0), p1: (1423.0, 507.0) })
* C_r.liga: Line(Line { p0: (1052.0, 413.0), p1: (820.0, 414.0) })
* C_r.liga: Line(Line { p0: (925.0, 508.0), p1: (1132.0, 507.0) })
* E_r.liga: Line(Line { p0: (956.0, 413.0), p1: (724.0, 414.0) })
* E_r.liga: Line(Line { p0: (829.0, 508.0), p1: (1036.0, 507.0) })
* G_r.liga: Line(Line { p0: (1233.0, 413.0), p1: (1001.0, 414.0) })
... and 500 others [code: found-semi-vertical]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (googlefonts/meta/script_lang_tags)</summary>
    <div>








- ⚠️ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. (googlefonts/vendor_id)</summary>
    <div>








- ⚠️ **WARN** OS/2 VendorID value 'TA  ' is not yet recognized.
If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Show hinting filesize impact. (hinting_impact)</summary>
    <div>








- ℹ️ **INFO** Hinting filesize impact:

 |               | MomoSignature-Regular.ttf     |
 |:------------- | ---------------:|
 | Dehinted Size | 357256 |
 | Hinted Size   | 362060   |
 | Increase      | 4804      |
 | Change        | 1.3 %  | [code: size-impact]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Font contains all required tables? (required_tables)</summary>
    <div>








- ℹ️ **INFO** This font contains the following optional tables:

    cvt 
    fpgm
    loca
    prep
    GPOS
    GSUB
    gasp [code: optional-tables]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table
set to optimize rendering? (googlefonts/gasp)</summary>
    <div>








- ℹ️ **INFO** These are the ppm ranges declared on the gasp table:

| PPM <= 65535 | - Use grid-fitting                                    |
|              | 	- Use grayscale rendering                            |
|              | 	- Use gridfitting with ClearType symmetric smoothing |
|              | 	- Use smoothing along multiple axes with ClearType®  |
|--------------|-------------------------------------------------------|
 [code: ranges]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Font has old ttfautohint applied? (googlefonts/old_ttfautohint)</summary>
    <div>








- ℹ️ **INFO** Could not detect which version of ttfautohint was used in this font. It is typically specified as a comment in the font version entries of the 'name' table. Such font version strings are currently: Version 1.000; ttfautohint (v1.8.4.7-5d5b) [code: version-not-detected]
  
  

</div>
</details>


</div>
</details>


<details><summary>[3] </summary>
<div>


<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. (googlefonts/metadata/unreachable_subsetting)</summary>
    <div>








- ⚠️ **WARN** MomoSignature-Regular.ttf: The following codepoints supported by the font are not covered by any subsets defined in the font's metadata file, and will never be served. You can solve this by either manually adding additional subset declarations to METADATA.pb, or by editing the glyphset definitions.

* U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
* U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
* U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
* U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, cherokee, tifinagh, coptic
* U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
* U+0307 COMBINING DOT ABOVE: try adding one of: hebrew, canadian-aboriginal, coptic, todhri, syriac, math, old-permic, tifinagh, duployan, malayalam, tai-le
* U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac
* U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
* U+030C COMBINING CARON: try adding one of: cherokee, tai-le
... and 18 others

Or you can add the above codepoints to one of the subsets supported by the font: latin-ext, latin, vietnamese [code: unreachable-subsetting]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Check for presence of an ARTICLE.en_us.html file (googlefonts/description/has_article)</summary>
    <div>








- ℹ️ **INFO** This font doesn't have an ARTICLE.en_us.html file. [code: missing-article]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Check axis ordering on the STAT table. (googlefonts/STAT/axis_order)</summary>
    <div>








- ℹ️ **INFO** All of the fonts lack a STAT table. [code: summary]
  
  

  

</div>
</details>


</div>
</details>






### Summary

| 🔥 FAIL | ⚠️ WARN | ℹ️ INFO | ✅ PASS | ⏩ SKIP | 
| ---|---|---|---|---|
| 2 | 15 | 6 | 92 | 66 | 
| 1% | 8% | 3% | 51% | 37% | 



