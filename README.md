# OVEX Prices Widget

A reusable prices widget that continuously scrolls horizontally, **showing the prices and 24-hour price changes** of all **cryptocurrencies** listed on the **OVEX Cryptocurrency Exchange**.

- Works on HTML pages.
- Can be included anywhere on a page.
- Customizable styles via CSS.

## Setup

- Insert the link tag below in your document:
```
<link rel="stylesheet" type="text/css" href="https://storage.googleapis.com/ovex-static-assets/ovex-prices-widget.min.css">
```
- Insert both of the script tags below in your document:
```
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.0/jquery.min.js"></script>
<script src="https://storage.googleapis.com/ovex-static-assets/ovex-prices-widget.min.js"></script>
```

## Usage

- Copy and paste the block of HTML below in your document where you would like the widget to appear:
```
<div class="ovex-prices-widget-container">
	<a class="ovex-link" rel="nofollow" target="_blank" href="https://www.ovex.io">
		<div class="ovex-logo">
			<picture>
		        <source type="image/webp" srcset="https://storage.googleapis.com/ovex-static-assets/ov-white.webp">
			    <source type="image/png" srcset="https://storage.googleapis.com/ovex-static-assets/ov-white.png">
			    <img src="https://storage.googleapis.com/ovex-static-assets/ov-white.png" alt="OVEX">
			</picture>
		</div>
	</a>
	<div class="ovex-play-pause">
		<img id="pause_icon" src="https://storage.googleapis.com/ovex-static-assets/pause.png" alt="Pause" onclick="togglePausePlay(0)">
		<img id="play_icon" class="hide" src="https://storage.googleapis.com/ovex-static-assets/play.png" alt="Play" onclick="togglePausePlay(1)">
	</div>
	<a class="ovex-link" rel="nofollow" target="_blank" href="https://www.ovex.io">
		<div id="ovex_prices_container" class="ovex-cryptocurrency-prices"><div id="ovex_prices_marquee"></div></div>
	</a>
</div>
```

If you have any problems implementing this widget, please contact us at info@ovex.io and we will be happy to assist you. If you have any suggestions please also contact info@ovex.io.

## FAQs

### Can I choose which cryptocurrencies are displayed?
Not yet, but this will be added soon. 

### Can I also display other data such as 24-hour volume?
Not yet, but this will be added soon.

### Which browsers does it work with?
It has been tested in Safari 10.0.3 and Chrome, but it should work in most browsers. If you have tested it in a different browser please let us know at info@ovex.io.


