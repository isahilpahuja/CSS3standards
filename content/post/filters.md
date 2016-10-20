+++
categories = []
date = "2016-10-14T12:14:19+05:30"
description = ""
keywords = []
title = "CSS3 Filters"

+++

<p>CSS Filters are a powerful tool that authors can use to achieve varying visual effects (sort of like Photoshop filters for the browser). The CSS filter property provides access to effects like blur or color shifting on an element’s rendering before the element is displayed. Filters are commonly used to adjust the rendering of an image, a background, or a border.</p>


<h6>The different Filter Functions are :</h6>

<table>
<tr>
  <td>blur(px)</td>
  <td>Applies a blur effect to the image. A larger value will create more blur.</td>
  </tr>
  <tr>
  <td>brightness(%)</td>
  <td>Adjusts the brightness of the image.</td>
  </tr>
  <tr>
  <td>contrast(%)</td>
  <td>Adjusts the contrast of the image.</td>
  </tr>
  <tr>
  <td>drop-shadow(h-shadow v-shadow blur spread color)</td>
  <td>Applies a drop shadow effect to the image. </td>
  </tr>
  <tr>
  <td>grayscale(%)</td>
  <td>Converts the image to grayscale. </td>
  </tr>
  <tr>
  <td>hue-rotate(deg)</td>
  <td>Applies a hue rotation on the image.</td>
  </tr>
  <tr>
  <td>invert(%)</td>
  <td>Inverts the samples in the image.</td>
  </tr>
  <tr>
  <td>opacity(%)</td>
  <td>Sets the opacity level for the image.</td>
  </tr>
  <tr>
  <td>saturate(%)</td>
  <td>Saturates the image.</td>
  </tr>
  <tr>
  <td>sepia(%)</td>
  <td>Converts the image to sepia.</td>
  </tr>
  <tr>
  <td>url()</td>
  <td>The url() function takes the location of an XML file that specifies an SVG filter, and may include an anchor to a specific filter element.</td>
  </tr>
</table>

<h6>Syntax :</h6>
filter: none | blur() | brightness() | contrast() | drop-shadow() | grayscale() | hue-rotate() | invert() | opacity() | saturate() | sepia() | url();

<h3>Need for this standard:</h3>

<p>The filter property used for graphical effects like blurring, sharpening, or color shifting an element. Filters are commonly used to adjust the rendering of images, backgrounds, and borders</p>

<h3>Negative Impact:</h3>
You may combine any number of functions to manipulate the rendering, but order still matters (i.e., using grayscale() after sepia() will result in completely gray output).


<h4>Working Section:</h4>

<a href="https://jsbin.com/toquqin/edit?html,output">All Filters</a>

<h4>References:</h4>
<a href="http://www.w3schools.com/cssref/css3_pr_filter.asp">http://www.w3schools.com/cssref/css3_pr_filter.asp</a><br>
<a href="https://css-tricks.com/almanac/properties/f/filter/">https://css-tricks.com/almanac/properties/f/filter/</a>

<h4>Point of Contact:</h4>

<p>Sahil Kumar</p>
<a href="mailto:sahikumar@deloitte.com">sahikumar@deloitte.com</a>