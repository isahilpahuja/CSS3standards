+++
date = "2016-10-06T13:20:20+05:30"
description = ""
draft = false
tags = []
title = "CSS3 Transforms"
topics = []

+++


<p>The transform property allows you to visually manipulate an element by skewing, rotating, translating, or scaling</p>
<p><strong>Values</strong><p>

<ul>
  <li>scale(): affects the size of the element. This also applies to the font-size, padding, height, and width of an element, too. It’s also a a shorthand function for the scaleX and scaleY functions.</li>
  <li>skewX() and skewY(): tilts an element to the left or right, like turning a triangle into a parallelogram. There is no shorthand skew property.</li>
  <li>translate(): moves an element sideways or up and down.</li>
  <li>rotate(): rotates the element clockwise from its current position.</li>
  <li>matrix(): a function that is probably not intended to be written by hand, but combines all transforms into one.</li>
  <li>perspective(): doesn’t affect the element itself, but affects the transforms of descendent elements' 3D transforms, allowing them all to have a consistent depth perspective.</li>
</ul>


<h3>Need for this standard:</h3>

<p><strong>Skew</strong><p>
<p>The skewX and skewY transform functions tilt an element one way or the other. </p>
<h4>Working Section:</h4>
<a href="https://jsbin.com/johariyina/edit?html,output"></a>

<p><strong>Rotate</strong><p>
<p>This rotates an element clockwise from its original position, whilst a negative value would rotate it in the opposite direction.</p>
<h4>Working Section:</h4>
<p><strong>2D rotate</strong><p>
<a href="https://jsbin.com/relepidife/edit?html,output"></a>
<p><strong>3D rotate</strong><p>
<a href="https://jsbin.com/bovazadono/edit?html,output"></a>

<p><strong>Translate</strong><p>
<p>This transform function moves an element sideways, or up and down.These values would be any length value, like 10px or 2.4em. One value will move the element to the right (negative values to the left). If a second value is provided, that second value will move it down (negative values up). Or, you can get specific:</p>
<p>transform will not cause other elements to flow around it.</p>
<h4>Working Section:</h4>
<a href="https://jsbin.com/zepafofulo/edit?html,output"></a>

<h4>Point of Contact:</h4>

<p>Meghna Khound</p>
<a href="mailto:mkhound@deloitte.com">mkhound@deloitte.com</a>
