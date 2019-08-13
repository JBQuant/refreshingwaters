---
layout: page
title: Test
permalink: /test/
---

This is just a test page. 



<html>

<head>

<title></title>

<style type="text/css">

/* Container needed to position the button. Adjust the width as needed */

.container {

position: relative;

width: 50%;

}

?
/* centering the image */
.center {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 50%;
}

/* Make the image responsive */

.container img {

width: 100%;

height: auto;

}

/* Style the button and place it in the middle of the container/image */

.container .btn {

position: absolute;

top: 50%;

left: 50%;

transform: translate(-50%, -50%);

-ms-transform: translate(-50%, -50%);

background-color: #555;

color: white;

font-size: 16px;

padding: 12px 24px;

border: none;

cursor: pointer;

border-radius: 5px;

}

.container .btn:hover {

background-color: black;

}

</style>

</head>

<body>

<div class="container">

<img src="https://live.staticflickr.com/65535/48523950947_b8890faffb_b.jpg" alt="Snow">

<a href = "https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=MACURCQMRVLAS&source=url">
<button class="btn">Donate Now</button>
</a>


<html>
</div>

</body>

<div class="paypal-button" >
<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top" >
<input type="hidden" name="cmd" value="_s-xclick" />
<input type="hidden" name="hosted_button_id" value="MACURCQMRVLAS" />
<input type="image" src="https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif" border="0" name="submit" title="PayPal - The safer, easier way to pay online!" alt="Donate with PayPal button" style="width:175px;height:75px;" class="center" />
<img alt="" border="0" src="https://www.paypal.com/en_US/i/scr/pixel.gif" width="1" height="1" />
</form>
</div>

</html>


