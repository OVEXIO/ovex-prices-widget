# OVEX Prices Widget

A reusable prices widget that continuously scrolls horizontally, **showing the prices and 24-hour price changes** of all **cryptocurrencies** listed on the **OVEX Cryptocurrency Exchange**.

- Works on HTML pages.
- Can be included anywhere on a page.
- Customizable styles via CSS.

## Setup

- Insert the link tag below in your document:
```
<link rel="stylesheet" type="text/css" href="https://github.com/OVEXIO/ovex-prices-widget/blob/master/src/css/ovex-prices-widget.min.css">
```
- Insert both of the script tags below in your document:
```
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.0/jquery.min.js"></script>
<script src="https://github.com/OVEXIO/ovex-prices-widget/blob/master/src/javascript/ovex-prices-widget.min.js"></script>
```

## Usage

- Copy and paste the block of HTML below in your document where you would like the widget to appear:
```
<a class="ovex-link" target="_blank" href="https://www.ovex.io">
	<div class="ovex-prices-widget-container">
		<div class="ovex-logo">
			<img src="https://www.ovex.io/assets/ov-white-06b4578b5fcb02e219519d18bcfd2c7f57acec4b6528d32c9a34bd3aa8a884bb.png">
		</div>
		<div class="ovex-cryptocurrency-prices"><div id="ovex_prices_marquee"></div></div>
	</div>
</a>
```

If you have any problems implementing this widget, please contact us at info@ovex.io and we will be happy to assist you. If you have any suggestions please also contact info@ovex.io.

## FAQs

### Can I choose which cryptocurrencies are displayed?
Not yet, but this will be added soon. 

### Can I also display other data such as 24-hour volume?
Not yet, but this will be added soon.

### Which browsers does it work with?
It has been tested in Safari 10.0.3 and Chrome, but it should work in most browsers. If you have tested it in a different browser please let us know at info@ovex.io.


