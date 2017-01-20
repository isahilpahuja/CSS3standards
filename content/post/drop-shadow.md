---
title: CSS3 Drop Shadow
prev: /post/css3text
next: /post/filters
weight: 3
---

<p>CSS3 Background has about 8 properties which is all included in the shorthand ‘background’.
The Background shorthand takes the following property values in the same order:</p>

<p> background: background-image | background-position / background-size | background-repeat | background-attachment | background-origin | background-clip | background-color</p>

<p><strong>Ex:</strong>  <span class="prop">background: url(myImg.jpg) bottom 20px right 20px / 200px 100px no-repeat fixed red;</span><p>

The different CSS3 Background properties are:

<ul>
  <li>background-attachment</li>
  <li>background-color</li>
  <li>background-image</li>
  <li>background-position</li>
  <li>background-position-x</li>
  <li>background-position-y</li>
  <li>background-repeat</li>
  <li>background-clip</li>
  <li>background-origin</li>
  <li>background-size</li>
  <li>background-inline-policy</li>
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

<p>Meghana Raju</p>
<a href="mailto:meraju@deloitte.com">meraju@deloitte.com</a>