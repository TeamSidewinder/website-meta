# Website Meta
Collection of meta tags and image assets to ease implementation of meta data on Live Nation websites. 

This repo includes two sets of icons. One utilizes the version of the Live Nation logo that has [no Fanman](/no-fanman/), the other does have the [Fanman](/fanman/).

## Meta Tags
```
<title>Live Nation website title</title>
<meta name="description" content="Live Nation web page description." />

<meta property="og:locale" content="en_US" />
<meta property="og:type" content="website" />
<meta property="og:site_name" content="Live Nation Website" />
<meta property="og:title" content="Live Nation web page title" />
<meta property="og:description" content="Live Nation web page description." />
<meta property="og:url" content="https://www.livenation.com" />
<meta property="og:image" content="open-graph-logo-1200x1200.png" />
<meta property="og:image:alt" content="Image description" />

<meta name="twitter:card" content="summary" />
<meta name="twitter:site" content="@livenation" />
<meta name="twitter:title" content="Live Nation web page title" />
<meta name="twitter:description" content="Live Nation web page description." />
<meta name="twitter:image" content="twitter-card-logo-1024x512.png" />
<meta name="twitter:image:alt" content="Image description" />

<meta name="msapplication-TileColor" content="#e21836" />
<meta name="msapplication-TileImage" content="ms-icon-144x144.png" />
<meta name="theme-color" content="#ffffff" />
<link rel="mask-icon" href="safari-pinned-tab.svg" color="#e21836" />
<link rel="apple-touch-icon" sizes="180x180" href="apple-icon-180x180.png" />
<link rel="apple-touch-icon" sizes="152x152" href="apple-icon-152x152.png" />
<link rel="apple-touch-icon" sizes="144x144" href="apple-icon-144x144.png" />
<link rel="apple-touch-icon" sizes="120x120" href="apple-icon-120x120.png" />
<link rel="apple-touch-icon" sizes="114x114" href="apple-icon-114x114.png" />
<link rel="apple-touch-icon" sizes="76x76" href="apple-icon-76x76.png" />
<link rel="apple-touch-icon" sizes="72x72" href="apple-icon-72x72.png" />
<link rel="apple-touch-icon" sizes="60x60" href="apple-icon-60x60.png" />
<link rel="apple-touch-icon" sizes="57x57" href="apple-icon-57x57.png" />
<link rel="icon" type="image/png" sizes="192x192"  href="android-icon-192x192.png" />
<link rel="icon" type="image/png" sizes="96x96" href="favicon-96x96.png" />
<link rel="icon" type="image/png" sizes="32x32" href="favicon-32x32.png" />
<link rel="icon" type="image/png" sizes="16x16" href="favicon-16x16.png" />
<link rel="shortcut icon" href="favicon.ico" />	
```

## Icon Exporter
These icons are produced using a modified version of this [Sketch Favicon Exporter](https://github.com/frederik-jacques/sketch-favicon-exporter-template).

## File Size Optimization
If you need to generate new icons, make sure to run the `PNG`s through [ImageOptim](https://imageoptim.com) to reduce their file size, and minimize the `SVG` file with [SVGOMG](https://jakearchibald.github.io/svgomg/).

## ICO Generation
The one file that Sketch is not able to export is the `favicon.ico`. To create that, upload the `32x32` `PNG` to [Favicon.cc](https://www.favicon.cc).