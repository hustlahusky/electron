# Weking

Weking is responsive, fast and easy toolkit for creating web interfaces.

## Features
* BEM
```
.block {}
.block__element {}
.block--modifier {}
```
* Mobile-first
* Without JavaScript & jQuery

## Quick Start

* Download latest version
* Copy **"dist"** folder to your project. Minimally you need `weking.min.css` file and `fonts` folder
* Create a simple HTML5 document with Weking stylesheet

```
    <!doctype html>
    <html>
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
        <meta name="description" content="">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">

        <title>Page Name</title>

        <!-- FAVICONS -->
        <!-- Default -->
        <link rel="icon" type="image/png" href="path/to/favicon.png" />

        <!-- Add to homescreen for Chrome on Android -->
        <meta name="mobile-web-app-capable" content="yes">
        <link rel="icon" sizes="192x192" href="path/to/chrome-touch-icon-192x192.png">

        <!-- Add to homescreen for Safari on iOS -->
        <meta name="apple-mobile-web-app-capable" content="yes">
        <meta name="apple-mobile-web-app-status-bar-style" content="black">
        <meta name="apple-mobile-web-app-title" content="Weking">
        <link rel="apple-touch-icon" href="path/to/apple-touch-icon.png">

        <!-- Tile icon for Win8 (144x144 + tile color) -->
        <meta name="msapplication-TileImage" content="path/to/ms-touch-icon-144x144-precomposed.png">
        <meta name="msapplication-TileColor" content="#3372DF">

        <!-- SEO: If your mobile URL is different from the desktop URL, add a canonical link to the desktop page https://developers.google.com/webmasters/smartphone-sites/feature-phones -->
        <!-- <link rel="canonical" href="http://www.example.com/"> -->

        <!-- Weking Stylesheet -->
        <link rel="stylesheet" href="dist/css/weking.min.css">

        <!-- HTML5 shim and Respond.js IE8 support of HTML5 elements and media queries -->
        <!--[if lt IE 9]>
            <script src="http://html5shim.googlecode.com/svn/trunk/html5.js"></script>
            <script src="http://css3-mediaqueries-js.googlecode.com/svn/trunk/css3-mediaqueries.js"></script>
        <![endif]-->
    </head>
    <body>

    </body>
    </html>
```

* See the code in the **"test"** folder & write your own code. Docs are in development
