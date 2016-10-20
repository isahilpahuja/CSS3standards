+++
date = "2016-13-13T13:20:20+05:30"
description = ""
draft = false
tags = []
title = "Flexible Box Layouts"
topics = []

+++


<p>The Flexbox Layout officially called CSS Flexible Box Layout Module is new layout module in CSS3 made to improve the items align, directions and order in the container even when they are with dynamic or even unknown size. Using flexible widths and heights, elements can be aligned to fill a space or distribute space between elements.</p>

<p>It is a layout mode providing for the arrangement of elements on a page such that the elements behave predictably when the page layout must accommodate different screen sizes and different display devices.</p>
<p>It lacks many of the more complex text- or document-centric properties that can be used in block layout, such as floats and columns. In return it gains simple and powerful tools for distributing space and aligning content in ways that web apps often needs.</p>

<p>The flex layout is constituted of parent container referred as <strong>flex container</strong> and its immediate children which are called <strong>flex items</strong>.</p>

<p>In-order to use flexbox layout, we just need to set the ‘display’ property on the parent container and all its immediate children will become automatically flex items.</p>

<p>The following are the properties distributed for flexbox container:</p>
    <ul>
        <li>flex-direction</li>
        <li>flex-wrap</li>
        <li>justify-content</li>
        <li>align-items</li>
        <li>align-content</li>
        <li>flex-flow (shorthand for flex-direction and flex-wrap)</li>
    </ul>

<p>and flexbox items:</p>
    <ul>
        <li>order</li>
        <li>align-self</li>
        <li>flex-grow</li>
        <li>flex-shrink</li>
        <li>flex-basis</li>
        <li>flex (shorthand for flex-grow, flex-shrink, flex-basis)</li>
    </ul>

<p>The below table shows the default values and the property values for each of the above properties.</p>

<table>
  <thead>
    <tr>
      <th>Flex-Container Properties</th>
      <th>Default value</th>
      <th>Property Values</th>
    </tr>
  </thead>
<tbody>
  <tr>
    <td>flex-direction</td>
    <td>row</td>
    <td>row | row-reverse | column | column-reverse | initial | inherit;</td>
  </tr>
  <tr>
    <td>flex-wrap</td>
    <td>nowrap</td>
    <td>nowrap | wrap | wrap-reverse | initial | inherit;</td>
  </tr>
  <tr>
    <td>justify-content</td>
    <td>flex-start</td>
    <td>flex-start | flex-end | center | space-between | space-around | initial | inherit;</td>
  </tr>
  <tr>
    <td>align-items</td>
    <td>stretch</td>
    <td>stretch | center | flex-start | flex-end | baseline | initial | inherit;</td>
  </tr>
  <tr>
    <td>align-content</td>
    <td>stretch</td>
    <td>stretch | center | flex-start | flex-end | space-between | space-around | initial | inherit;</td>
  </tr>
</tbody>
</table>

<table>
  <thead>
    <tr>
      <th>Flex-Items Properties</th>
      <th>Default value</th>
      <th>Property Values</th>
    </tr>
  </thead>
<tbody>
  <tr>
    <td>order</td>
    <td>0</td>
    <td>number | initial | inherit;</td>
  </tr>
  <tr>
    <td>align-self</td>
    <td>auto</td>
    <td>auto|stretch|center|flex-start|flex-end|baseline|initial|inherit;</td>
  </tr>
  <tr>
    <td>flex-grow</td>
    <td>0</td>
    <td>number | initial | inherit;</td>
  </tr>
  <tr>
    <td>flex-shrink</td>
    <td>1</td>
    <td>number | initial | inherit;</td>
  </tr>
  <tr>
    <td>flex-basis</td>
    <td>auto</td>
    <td>number | auto | initial | inherit;</td>
  </tr>
</tbody>
</table>

<h3>Need for this standard:</h3>

<p>Particularly flexbox is used for scaling, vertically and horizontally aligning, and re-ordering elements within a container, distributing space and changing the direction of a column or row.
We no longer need to rely on solutions like, stretching content with position: absolute, fighting whitespace with inline-block, hacks involving floats and clearfixed, negative margins, or display: table-cell, as flexbox adds a level of control to our layouts.
</p>
<p>But it is preferable to use media-queries and percentage-based widths for creating columns and rows.</p>

<h3>Positive Impact:</h3>
<ul>
    <li>You only need to know a handful of CSS properties to use flexbox.</li>
    <li>Once an element is set as a flex container its children follow the flexbox rules for layout instead of the standard block, inline and inline-block rules</li>
    <li>Besides the support for flexbox, a reason to use it is the ease in which we can center elements, both horizontally and vertically</li>
    <li>It becomes easier to have space distributed evenly on both sides of the items/between only the middle items, without dealing with “:first-child” or  “:last-child”.</li>
    <li>It’s supported in all major browsers.</li>
</ul>

<h3>Negative Impact:</h3>
<p>Don't use flexbox for overall page layout.</p>
<p>If one uses the shorthand properties (flex shorthand property and the flex-flow shorthand property) and fails to declare any property in the sequence, those properties will fall back to their default values as defined in the above table. Using a flex value of something like 1 0 0px can still be a problem because many CSS minifiers will convert 0px to 0. To avoid this, make sure to use 0% instead of 0px since most minifiers won't touch percentage values for other reasons</p>

<p>Of all the benefits and ease, there are still some bugs in using Flexbox. You can check the list and description of known bugs at:</p>
<ul>
<li><a href="https://github.com/philipwalton/flexbugs">Flexbugs</a></li>
<li><a href="https://philipwalton.com/articles/normalizing-cross-browser-flexbox-bugs/">Normalizing Cross-browser Flexbox Bugs.</a></li>
</ul>

<h4>Working Section:</h4>
<p>Check the working of Flex Properties here:</p>
<a href="https://jsbin.com/yugubu/1">FlexBox Use</a>


<h4>Reference:</h4>
<a href="https://www.w3.org/TR/2016/CR-css-flexbox-1-20160526/">CSS Flexible Box Layout Module Level 1</a><br>
<a href="https://chriswrightdesign.com/experiments/using-flexbox-today/">Using Flexbox today</a><br>
<a href="https://css-tricks.com/snippets/css/a-guide-to-flexbox/">A Complete Guide to Flexbox</a><br>
<a href="http://brolik.com/blog/when-to-use-flexbox/">When to use Flexbox</a>

<h4>Point of Contact:</h4>

<p>Minu Kumari</p>
<a href="mailto:minkumari@deloitte.com">minkumari@deloitte.com</a>
