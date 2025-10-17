## FontSpector report

fontspector version: 1.3.0






## Check results




<details><summary>[3] </summary>
<div>


<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. (googlefonts/metadata/unreachable_subsetting)</summary>
    <div>








- ⚠️ **WARN** Capriola[wght].ttf: The following codepoints supported by the font are not covered by any subsets defined in the font's metadata file, and will never be served. You can solve this by either manually adding additional subset declarations to METADATA.pb, or by editing the glyphset definitions.

* U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
* U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
* U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
* U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, math, tifinagh
* U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
* U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, coptic, math, old-permic, duployan, malayalam, syriac, tifinagh, hebrew, todhri, canadian-aboriginal
* U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac
* U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
* U+030C COMBINING CARON: try adding one of: cherokee, tai-le
... and 35 others

Or you can add the above codepoints to one of the subsets supported by the font: cyrillic-ext, latin-ext, latin, vietnamese [code: unreachable-subsetting]
  
  

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








- ℹ️ **INFO** None of the fonts lack a STAT table.

	And these are the most common STAT axis orderings:
	wght: 1 [code: summary]
  
  

</div>
</details>


</div>
</details>


<details><summary>[17] Capriola[wght].ttf</summary>
<div>


<details>
    <summary>⚠️ <b>WARN</b> Check GDEF mark glyph class doesn't have characters that are not marks. (opentype/GDEF_non_mark_chars)</summary>
    <div>








- ⚠️ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
* U+F6C3 (uni0326.1) [code: non-mark-chars]
  
  

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
* uni1EF8 (U+1EF8): found 1, expected one of: {2, 3}
* uni20B4 (U+20B4): found 5, expected one of: {2, 4, 3, 1} [code: contour-count]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure variable fonts include an avar table. (mandatory_avar_table)</summary>
    <div>








- ⚠️ **WARN** The font does not include an avar table. [code: missing-avar]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. (math_signs_width)</summary>
    <div>








- ⚠️ **WARN** The most common width is 1363 among a set of 13  math glyphs.
The following math glyphs have a different width, though:
width=1364: less, greater
width=1393: plusminus
width=1302: equal
width=1403: plus, divide
width=1308: logicalnot
width=1202: multiply
width=1524: approxequal
width=1278: minus
width=1323: lessequal [code: width-outliers]
  
  

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








- ⚠️ **WARN** OS/2.sTypoAscender value should be greater than 2122, but got 1992 instead [code: typoAscender]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. (googlefonts/glyphsets/shape_languages)</summary>
    <div>








- ⚠️ **WARN** Warning language shaping:

| Message                                                               | Languages              |
|-----------------------------------------------------------------------|------------------------|
| Auxiliary orthography codepoints:                                     | * lt_Latn (Lithuanian) |
|   Shaper didn't attach acutecomb to uogonek when shaping the text 'ų́' |                        |
|   Shaper didn't attach tildecomb to uogonek when shaping the text 'ų̃' |                        |
| Auxiliary orthography codepoints:                                     | * fi_Latn (Finnish)    |
|   The following auxiliary characters are missing from the font: Ǥ     |                        |
|   The following auxiliary characters are missing from the font: Ʒ     |                        |
|   The following auxiliary characters are missing from the font: Ǯ     |                        |
|   The following auxiliary characters are missing from the font: ǥ     |                        |
|   The following auxiliary characters are missing from the font: ʒ     |                        |
|   The following auxiliary characters are missing from the font: ǯ     |                        |
| Auxiliary orthography codepoints:                                     | * de_Latn (German)     |
|   The following auxiliary characters are missing from the font: ſ     | * fr_Latn (French)     |
| Auxiliary orthography codepoints:                                     | * en_Latn (English)    |
|   The following auxiliary characters are missing from the font: ʻ     |                        | [code: warning-language-shaping]
  
  

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
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. (dotted_circle)</summary>
    <div>








- ⚠️ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that
replace the dot. (soft_dotted)</summary>
    <div>








- ⚠️ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: * ị́
* ị̂
* ị̄
* ị̃
* ị̀
* į̌
* į́
* į̂
* į̄
... and 2 othersThe dot of soft dotted characters _should_ disappear in other cases, for example: * ị̦̉
* ị̦̌
* ị̦́
* ị̦̂
* ị̦̄
* ị̦̊
* ị̦̇
* ị̦̒
* ị̦̃
... and 75 others [code: soft-dotted]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Checking OS/2 fsSelection value. (opentype/xavgcharwidth)</summary>
    <div>








- ℹ️ **INFO** OS/2 xAvgCharWidth is 1260 but it should be 1259 which corresponds to the average of the widths of all glyphs in the font. These are similar values, which may be a symptom of the slightly different calculation of the xAvgCharWidth value in font editors. There's further discussion on this at https://github.com/fonttools/fontbakery/issues/1622 [code: xAvgCharWidth-close]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Familyname must be unique according to namecheck.fontdata.com (fontdata_namecheck)</summary>
    <div>








- ℹ️ **INFO** The family name "Capriola" seems to be already in use.
Please visit http://namecheck.fontdata.com/ for more info. [code: name-collision]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Show hinting filesize impact. (hinting_impact)</summary>
    <div>








- ℹ️ **INFO** Hinting filesize impact:

 |               | Capriola[wght].ttf     |
 |:------------- | ---------------:|
 | Dehinted Size | 507240 |
 | Hinted Size   | 507264   |
 | Increase      | 24      |
 | Change        | 0.0 %  | [code: size-impact]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Font contains all required tables? (required_tables)</summary>
    <div>








- ℹ️ **INFO** This font contains the following optional tables:

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
    <summary>ℹ️ <b>INFO</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (googlefonts/meta/script_lang_tags)</summary>
    <div>








- ℹ️ **INFO** "latn" [code: dlng-tag]
  
  


- ℹ️ **INFO** "latn" [code: slng-tag]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Font has old ttfautohint applied? (googlefonts/old_ttfautohint)</summary>
    <div>








- ℹ️ **INFO** Could not detect which version of ttfautohint was used in this font. It is typically specified as a comment in the font version entries of the 'name' table. Such font version strings are currently: Version 1.007 [code: version-not-detected]
  
  

</div>
</details>


</div>
</details>






### Summary

| ⚠️ WARN | ℹ️ INFO | ✅ PASS | ⏩ SKIP | 
| ---|---|---|---|
| 11 | 10 | 111 | 48 | 
| 6% | 6% | 62% | 27% | 



