+++
date = "2016-10-06T13:20:20+05:30"
description = ""
draft = false
tags = []
title = "CSS3 Multi-Column Layouts"
topics = []

+++


<p>CSS columns you can create a print-inspired layout  that can adapt to a responsive canvas</p>

<p> There are three different ways to declare columns:</p>

<ul>
  <li>Declare column-count</li>
  <li>Declare column-width</li>
  <li>Declare both (recommended)</li>
</ul>

<h3>Need for this standard:</h3>

<p>Though there is no as such specs provided for this property it is always recommended never to use both column-count and column-width together.</p>

<h3>Negative Impact:</h3>
Using both column-count and column-width together will behave different in different browsers which will impact the look and feel of the page being rendered.
Firefox creates  columns to fill the width of the parent div; WebKit creates columns of exactly the specified column width each, leaving a large blank area to the right of the element.



<h4>Working Section:</h4>

<p>Try the below link in both firefox and chrome to see the difference!!<p>
<a href="http://codepen.io/katydecorah/pen/39ea7b0f24b5806969dc4c275461c5b1">Multi column</a>



<h4>Point of Contact:</h4>

<p>Meghana Raju</p>
<a href="mailto:meraju@deloitte.com">meraju@deloitte.com</a>
