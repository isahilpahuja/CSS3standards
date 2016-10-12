+++
date = "2016-10-07T10:17:56+05:30"
description = ""
draft = false
tags = []
title = "Border"
topics = []

+++

<p>The CSS border properties allow you to specify the style, width, and color of an element's border. In CSS3 we have some new properties like CSS3 rounded corners, CSS3 Border Images.</p>

<h4>CSS3 Rounded Corners: </h4>

<p>With the CSS3 border-radius property, you can give any element "rounded corners".</p>

<p>
<strong>
#someDiv {
    border-radius: 25px;
    width: 100px;
    height: 100px;
}
</strong>
</p>

<p>If you specify only one value for the border-radius property, this radius will be applied to all 4 corners.</p>

<h3>Need for this standard:</h3>
<div>
You can specify each corner separately if you wish. Here are the rules:
<p>
Four values: first value applies to top-left, second value applies to top-right, third value applies to bottom-right, and fourth value applies to bottom-left corner.
<strong>Example :</strong> border-radius: 15px 50px 30px 5px
</p>
<p>
Three values: first value applies to top-left, second value applies to top-right and bottom-left, and third value applies to bottom-right.
<strong>Example :</strong> border-radius: 15px 50px 30px
</p>
<p>
Two values: first value applies to top-left and bottom-right corner, and the second value applies to top-right and bottom-left corner.
<strong>Example :</strong> border-radius: 15px 50px
</p>
<p>
One value: all four corners are rounded equally.
<strong>Example :</strong> border-radius: 15px
</p>
</div>

<h4>CSS3 Rounded Corners Properties:</h4>
<div>
<ul>
<li>border-radius : A shorthand property for setting all the four border-radius properties</li>
<li>border-top-left-radius : Defines the shape of the border of the top-left corner</li>
<li>border-top-right-radius : Defines the shape of the border of the top-right corner</li>
<li>border-bottom-right-radius : Defines the shape of the border of the bottom-right corner</li>
<li>border-bottom-left-radius : Defines the shape of the border of the bottom-left corner</li>
</ul>
</div>

<h4>CSS3 Border-Images: </h4>
<p>With the CSS3 border-image property, you can set an image to be used as the border around an element.</p>

<h3>Working Section:</h3>

<a href="https://jsbin.com/leqawakeji/2/edit?html,output">Border</a>

<h3>Point of Contact:</h3>
<p>Meghna Khound</p>
<a href="mailto:mkhound@deloitte.com">mkhound@deloitte.com</a>
