+++
date = "2016-19-13T13:20:20+05:30"
description = ""
draft = false
tags = []
title = "CSS3 Text"
topics = []

+++


<p>CSS has various text properties that makes it easier to align, color, transform or format the displayed text content. CSS3 contains several new text features.</p>
<p>The below table shows the default values and the property values for each of the above properties.</p>
<table>
  <thead>
    <tr>
      <th>Properties</th>
      <th>Default value</th>
      <th>Property Values</th>
    </tr>
  </thead>
<tbody>
  <tr>
    <td>text-overflow</td>
    <td>clip</td>
    <td>clip | ellipsis | string | initial | inherit;</td>
  </tr>
  <tr>
    <td>word-wrap</td>
    <td>normal</td>
    <td>normal | break-word | initial | inherit;</td>
  </tr>
  <tr>
    <td>word-break</td>
    <td>normal</td>
    <td>normal | break-all | keep-all | initial | inherit;</td>
  </tr>
</tbody>
</table>

<ul>
  <li>text-overflow</li>
  <li>word-wrap</li>
  <li>word-break</li>
</ul>

<h2><u>text-overflow:</u></h2>
<p>This property in CSS deals with situations where text is clipped when it overflows the element's box. It can be clipped (i.e. cut off, hidden or clip) or display an ellipsis ('…').
Text overflow can only happen on block or inline-block level elements.</p>

<h3>Need for this standard:</h3>

<p>If the element (area/div) has a fixed defined width the text might overflow and appear out of the element, in-order to handle this the properties overflow and white-space are defined in CSS; but then we can further define whether the overflowed text should be cut-off or to display an ellipsis (where its default value is ‘clip’).</p>
<p>But it is preferable to use media-queries and percentage-based widths for creating columns and rows.</p>

<h3>Negative Impact:</h3>
<p>The drawback for this property is that it will work only when the following properties are defined:</p>
<ul>
  <li>Overflow property is defined (scroll, hidden, auto), and</li>
  <li>White-space is defined as ‘nowrap’.</li>
</ul>

<p>If the overflow and white-space is not defined it will take the default values, ‘visible’ and ‘normal’ respectively and hence the text-overflow property fails to work.</p>

<p>It is advisable not to use ’text-overflow: ellipsis’ property as the words could be truncated in a way that the original word will get another meaning.</p>

<p>Another methods of wrapping words are using word-break or word-wrap properties.</p>

<h3>Positive Impact:</h3>
<p>It is supported in all browsers.</p>

<h2><u>word-wrap:</u></h2>
<p>this property will either expand the word outside if it is too long to fit within an area (normal) or forcefully wraps the text even if it means splitting it in the middle of a word (break-word).</p>

<h4>and Hyphen:</h4>
<p>The hyphens CSS property tells the browser how to hyphenate words when line-wrapping.</p>

<h3>Need for this standard:</h3>
<p>the need for these standard is also to handle the overflow of text outside the area/element.</p>

<h3>Negative Impact:</h3>
<p>hyphens are not very well supported in some of the browsers like (Chrome, Opera, Android, etc). Furthermore, hyphens is language-sensitive.</p>
<p>In HTML, the language is determined by the ‘lang’ attribute, and browsers will hyphenate only if this attribute is present and if an appropriate hyphenation dictionary is available. You could also use a JavaScript library like Hyphenator.js which works with many languages and in lots of browsers.</p>

<h3>Positive Impact:</h3>
<p>Unlike text-overflow, they do not require any additional properties to be defined, they can be used directly.</p>
<p>Word-wrap is supported in all browsers.</p>

<h2><u>word-break:</u></h2>
<p>a CSS property to specify whether to break lines within words. </p>

<h3>Need for this standard:</h3>

<p>this property can break at words, hyphens or even between any two letters. This option is used mostly in a context where the text is predominantly using CJK characters with few non-CJK excerpts and it is desired that the text be better distributed on each line.</p>

<p>This property is very useful for CJK characters as ‘keep-all’ property sequences of CJK characters do not break.</p>

<h4>For example: </h4>
<p>Korean has two styles of line-breaking: between any two Korean syllables (‘word-break: normal’) or, like English, mainly at spaces (‘word-break: keep-all’).</p>

<p>Here's a mixed-script sample text:</p>

<div style="display: flex;">
  <div class="prop">
      <p><b>Text: </b>这是一些汉字, and some Latin, و کمی نوشتنن عربی, และตัวอย่างการเขียนภาษาไทย.</p>
      <p><i>The break-points are determined as follows (indicated by ‘·’):</i></p>
      <p><u>‘word-break: normal’</u></p>
      <p>这·是·一·些·汉·字,·and·some·Latin,·و·کمی·نوشتنن·عربی·และ·ตัวอย่าง·การเขียน·ภาษาไทย.</p>
      <p><u>‘word-break: break-all’</u></p>
      <p>这·是·一·些·汉·字,·a·n·d·s·o·m·e·L·a·t·i·n,·و·ﮐ·ﻤ·ﻰ·ﻧ·ﻮ·ﺷ·ﺘ·ﻦ·ﻋ·ﺮ·ﺑ·ﻰ,·แ·ล·ะ·ตั·ว·อ·ย่·า·ง·ก·า·ร·เ·ขี·ย·น·ภ·า·ษ·า·ไ·ท·ย.</p>
      <p><u>‘word-break: keep-all’</u></p>
      <p>这是一些汉字,·and·some·Latin,·و·کمی·نوشتنن·عربی,·และตัวอย่างการเขียนภาษาไทย.</p>
    </div>
</div>

<h4>Working Section:</h4>
<p>Check the working of Flex Properties here:</p>

<ul>
    <li><a href="https://jsbin.com/rudoy/2 ">Text-overflow</a></li>
    <li><a href="https://jsbin.com/ducosi/1">Word-break</a></li>
    <li><a href="https://jsbin.com/duzowa/5">Difference between text-overflow, word-break and word-wrap</a></li>
</ul>

<p><strong><i>Note:</i></strong>the difference between text-overflow and word-wrap is that, the text-overflow property cuts-off the part which does not fits into the element, while the word-wrap forcefully pushes the text inside the element. Word-break break the word/letter or at space as per required by the area.</p>

<h4>Reference:</h4>
<a href="https://www.w3.org/TR/css-text-3/">CSS Text Module Level 3</a><br>
<a href="https://justmarkup.com/log/2015/07/dealing-with-long-words-in-css/">Dealing with long words in CSS</a><br>
<a href="http://www.w3schools.com/css/css3_text_effects.asp">CSS3 Text</a>

<h4>Point of Contact:</h4>

<p>Minu Kumari</p>
<a href="mailto:minkumari@deloitte.com">minkumari@deloitte.com</a>
<style>
.prop
{
background-color:#B2DCDC;
color:#005747;
border: 1px solid;
padding: 25px;
margin: 25px;
text-align: left;
word-wrap: wrap;
font-size:14px;
}
</style>
