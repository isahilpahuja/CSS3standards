+++
date = "2016-19-13T13:20:20+05:30"
description = ""
draft = false
tags = []
title = "CSS3 User Interface"
topics = []

+++

<p>CSS3 brings some great new properties relating to resizing elements, cursors, outlining, box layout and more. Here we will be focusing on three of the most significant user interface enhancements:</p>
<ul>
<li>resize</li>
<li>box-sizing</li>
<li>outline-offset</li>
</ul>
<p>The following table shows the default values of the user interface properties:</p>


<h3>Need for this standard:</h3>

<p>For cleaner and faster code, one can use the animation shorthand, but it is always advisable to use the additional animation properties instead of the shorthand properties. This is because, not declaring few properties explicitly will set them to their default values which might take away the intention of the whole property. Also it becomes difficult to memorize the animation sequence for the shorthand, whereas it’s easier to remember them individually.</p>

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
    <td>resize</td>
    <td>none</td>
    <td>none|both|horizontal|vertical|initial|inherit;</td>
  </tr>
  <tr>
    <td>box-sizing</td>
    <td>content-box</td>
    <td>content-box|border-box|initial|inherit;</td>
  </tr>
    <tr>
    <td>outline-offset</td>
    <td>0</td>
    <td>length|initial|inherit;</td>
  </tr>
</tbody>
</table>

<h2><u>resize:</u></h2>
<p>The resize property specifies whether or not an element should be resizable by the user.</p>

<h3>Need for this standard:</h3>
<p>The purpose of the resize property is to also allow control over the appearance and function of the resizing mechanism on the element.</p>
<p><strong><i>Note:</i></strong> The resizing mechanism is NOT the same as the scrolling mechanism. The scrolling mechanism allows the user to determine which portion of the contents of an element is shown. The resizing mechanism allows the user to determine the size of the element.</p>
<p>The resize property applies to elements whose computed ‘overflow’ value is something other than ‘visible’.</p>

<h3>Negative Impact:</h3>
<p>The effect of the resize property on generated content is undefined. Implementations should not apply the resize property to generated content.</p>

<h4>Working Section:</h4>
<a href="https://jsbin.com/xovezey/1">Using resize</a><br>
<a href= "https://jsbin.com/cesijic/3">Effect of the resize property on generated content</a>

<h2><u>box-sizing:</u></h2>
<p>The box sizing aspect allows you to define certain elements to fit an area in a certain way. For example, if we want two bordered boxes side by side, it can be achieved by setting box-sizing to ‘border-box’. This forces the browser to render the box with the specified width and height, and place the border and padding inside the box.</p>

<h3>Need for this standard:</h3>
<p>By default, the width and height of an element is calculated like this:</p>
<p>width + padding + border = actual width of an element</p>
<p>height + padding + border = actual height of an element</p>
<p>This means that when we set width/height of an element it will appear bigger that the actual size we defined. The CSS3 box-sizing property allows us to include the padding and border in an element's total width and height.</p>
<p>We can include the padding and border in the width/height defined without increasing the required size of the element using <i>‘box-sizing: border-box’</i>.</p>

<h4>Working Section:</h4>
<a href="https://jsbin.com/dunafux/3">Box-Sizing</a>

<h2><u>Outline offset:</u></h2>
<p>CSS3 includes the facility to offset the outline away from the element – as the value is defined.</p>
<p>Outlines differs from a border in two ways:</p>
    <ul>
        <li>Outlines do not take up space</li>
        <li>Outlines may be non-rectangular</li>
    </ul>
<h3>Need for this standard:</h3>
<p>The outline-offset is such property of the CSS3 User Interface, which can be used to define the space between the element's border and its outline. By default, the outline is drawn starting just outside the border edge.</p>
<p>The space will be transparent (the parent will determine the background).</p>
<p>Negative values must cause the outline to shrink into the border box.</p>

<h4>Working Section:</h4>
<a href="https://jsbin.com/kisunay/1">Outline-offset</a>

<h4>Reference:</h4>
<a href="https://www.w3.org/TR/css-ui-3/#propdef-box-sizing">CSS Basic User Interface Module Level 3 (CSS3 UI)</a><br>
<a href="http://www.html5andcss3.org/css3userinterface.php">CSS3 User Interface Tutorial</a><br>
<a href="http://www.w3schools.com/css/css3_user_interface.asp">CSS3 User Interface</a><br>
<a href="https://drafts.csswg.org/css-ui-3/#outline-offset">Outline-Offset</a>

<h4>Point of Contact:</h4>

<p>Minu Kumari</p>
<a href="mailto:minkumari@deloitte.com">minkumari@deloitte.com</a>
