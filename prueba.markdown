---
layout: page
permalink: /comprar
---
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>jQuery UI Tabs - Default functionality</title>
  <link rel="stylesheet" href="//code.jquery.com/ui/1.12.1/themes/base/jquery-ui.css">
  <link rel="stylesheet" href="/resources/demos/style.css">
  <script src="https://code.jquery.com/jquery-1.12.4.js"></script>
  <script src="https://code.jquery.com/ui/1.12.1/jquery-ui.js"></script>
  <script>
  $( function() {
    $( "#tabs" ).tabs();
  } );
  </script>
</head>
<body id="bs-over">
 
<div id="tabs">
  <ul>
    <li id="ventana-1"><a href="#tabs-1">Café Don Lucas</a></li>
    <li id="ventana-2"><a href="#tabs-2">Utopia Cacao Farms</a></li>
  </ul>
  <div id="tabs-1">
   <div class="product" id="page-product">
	<div class="container">
		<div class="row">
			<div class="col-md-6 col-xs-12">
				<p>Moccha Blend</p>
				<a href="/moccha-blend"><img class="img-responsive" id="product-image" src="/images/moccha-blend.jpg"/></a>
			</div>
			<div class="col-md-6 col-xs-12">
				<p>Regi&oacute;n San Marcos Gourmet Blend</p>
				<a href="/region-san-marcos"><img class="img-responsive" id="product-image" src="/images/sanmarcos.jpg"/></a>
			</div>
		</div>
		<div class="row">
			<div class="col-md-6 col-xs-12">
				<p>Regi&oacute;n Huehuetenango</p>
				<a href="/region-huehuetenango"><img class="img-responsive" src="/images/huehue.jpg"/></a>
			</div>
			<div class="col-md-6 col-xs-12">
				<p>Mezcla de Regiones</p>
				<a href="/region-mezcla"><img class="img-responsive" src="/images/mezcla.jpg"/></a>
			</div>
		</div>
	</div>
</div>
  </div>
  <div id="tabs-2">
    <div class="product" id="page-product">
	<div class="container">
		<div class="row">
			<div class="col-md-6 col-xs-12">
				<p>Moringa Powder</p>
				<a href="/moringa-powder"><img class="img-responsive" id="product-image" src="/images/moringa-powder.jpg"/></a>
			</div>
			<div class="col-md-6 col-xs-12">
				<p>Cacao Nibs</p>
				<a href="/cacao-nibs"><img class="img-responsive" id="product-image" src="/images/cacao-nibs.jpg"/></a>
			</div>
		</div>
		<div class="row">
			<div class="col-md-6 col-xs-12">
				<p>Cacao Crunch</p>
				<a href="/cacao-crunch"><img class="img-responsive" src="/images/cacao-crunch.jpg"/></a>
			</div>
			<div class="col-md-6 col-xs-12">
				<p>Moccha Crunch</p>
				<a href="/region-mezcla"><img class="img-responsive" src="/images/moccha-crunch.jpg"/></a>
			</div>
		</div>
	</div>
</div>
  </div>
</div>
 
 
</body>
</html>