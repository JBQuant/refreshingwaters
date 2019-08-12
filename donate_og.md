---
layout: page
title: Donate
#permalink: /donate/
---

<h2>Example Button 1:</h2>

<form class="paypalform" action="https://www.paypal.com/cgi-bin/webscr" method="post">
  <input type="hidden" name="cmd" value="_s-xclick">
  <input type="hidden" name="hosted_button_id" value="A9KK2MTU7QSJU">
  <button class="paypalbutton" name="submit">
    <span>Buy me some coffee</span>
  </button>
  <img alt= "" border="0" src="/assets/donation2.png" width="200" height="100">
</form>


<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.container {
  position: relative;
  width: 100%;
  max-width: 400px;
}

.container img {
  width: 100%;
  height: auto;
}

.container .btn {
  position: absolute;
  top: 25%;
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
  text-align: center;
}

.container .btn:hover {
  background-color: black;
}
</style>
</head>
<body>

<h2>Example Button 2:</h2>

<div class="container">
  <img src="/assets/img/donation2.png" alt="Snow" style="width:100%">
  <button class="btn" action="https://www.paypal.com/cgi-bin/webscr" method="post">Donate with PayPal</button>
</div>

</body>
</html>








