+++
categories = []
date = "2016-10-14T12:14:19+05:30"
description = ""
keywords = []
title = "Filters"

+++

<p>CSS Filters are a powerful tool that authors can use to achieve varying visual effects (sort of like Photoshop filters for the browser). The CSS filter property provides access to effects like blur or color shifting on an element’s rendering before the element is displayed. Filters are commonly used to adjust the rendering of an image, a background, or a border.</p>


The different Filter Functions are:

<ul>
  <li>blur(px)</li>
  <li>brightness(%)</li>
  <li>contrast(%)</li>
  <li>drop-shadow(h-shadow v-shadow blur spread color)</li>
  <li>grayscale(%)</li>
  <li>hue-rotate(deg)</li>
  <li>invert(%)</li>
  <li>opacity(%)</li>
  <li>saturate(%)</li>
  <li>sepia(%)</li>
  <li>url()</li>
</ul>

<h3>Need for this standard:</h3>

<p>It is always advisable to use the above properties in specific instead of using the shorthand as not declaring few properties explicitly will set them to their default values which might take away the intention of the whole property.</p>

<h3>Negative Impact:</h3>
If you use the background shorthand and fail to declare any of the individual properties that make up the shorthand, those properties will revert to their default values listed below:

<ul>
<li>background-color: transparent</li>
<li>background-position: 0% 0%</li>
<li>background-size: auto auto</li>
<li>background-repeat: repeat repeat</li>
<li>background-clip: border-box</li>
<li>background-origin: padding-box</li>
<li>background-attachment: scroll</li>
<li>background-image: none</li>
</ul>


<h4>Working Section:</h4>

<a href="https://jsbin.com/johariyina/edit?html,output">Background Shorthand</a>

<a href= "https://jsbin.com/xaseyahade/edit?html,output">Background Properties</a>

<h4>Point of Contact:</h4>

<p>Sahil Kumar</p>
<a href="mailto:sahikumar@deloitte.com">sahikumar@deloitte.com</a>