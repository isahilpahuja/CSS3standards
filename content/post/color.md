+++
date = "2016-10-07T15:38:01+05:30"
description = ""
draft = false
tags = []
title = "Color"
topics = []

+++

<div>
<p>CSS uses color values to specify a color. Typically, these are used to set a color either for the foreground of an element (i.e., its text) or else for the background of the element. They can also be used to affect the color of borders and other decorative effects.</p>
</div>

<p>You can specify your color values in various formats. Following table lists all the possible formats −</p>

<table>
  <thead>
    <tr>
      <th>Format</th>
      <th>Syntax</th>
      <th>Example</th>
    </tr>
  </thead>
<tbody>
  <tr>
    <td>Hex Code</td>
    <td>#RRGGBB</td>
    <td>p{color:#FF0000;}</td>
  </tr>
  <tr>
    <td>Short Hex Code</td>
    <td>#RGB</td>
    <td>p{color:#6A7;}</td>
  </tr>
  <tr>
    <td>RGB %</td>
    <td>rgb(rrr%,ggg%,bbb%)</td>
    <td>p{color:rgb(50%,50%,50%);}</td>
  </tr>
  <tr>
    <td>RGB Absolute</td>
    <td>rgb(rrr,ggg,bbb)</td>
    <td>p{color:rgb(0,0,255);}</td>
  </tr>
  <tr>
    <td>Keyword</td>
    <td>aqua, black, etc</td>
    <td>p{color:teal;}</td>
  </tr>
</tbody>
</table>

<h3>CSS Colors - Hex Codes:</h3>
<h4>Need for this standard:</h4>
<div>
  <p>A hexadecimal is a 6 digit representation of a color. The first two digits(RR) represent a red value, the next two are a green value(GG), and the last are the blue value(BB)</p>
  <p>A hexadecimal value can be taken from any graphics software like Adobe Photoshop, Jasc Paintshop Pro, or even using Advanced Paint Brush.</p>
</div>
<h4>Positive Impact</h4>
<div>
  <ul>
    <li>1. Supported by all browsers</li>
    <li>2. There is a perceived performance increase by saving the browser the trouble of converting the rgb notation.</li>
  </ul>
</div>

<h3>CSS Colors - RGBA:</h3>
<h4>Need for this standard:</h4>
<div>
  <p>This color value is specified using the rgb( ) property. This property takes three values, one each for red, green, and blue. The value can be an integer between 0 and 255 or a percentage.</p>
  <h4>Negative Impact</h4>
  <div>
    <ul>
      <li>1. Not Supported by all browsers so it is recommended not to use it</li>
    </ul>
  </div>
</div>
