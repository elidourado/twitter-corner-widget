# Animated Twitter corner widget

This is the animated corner widget I use on [elidourado.com](https://elidourado.com) to link to my Twitter account. On hover it displays a pleasing flapping motion.

![](example.png)

## Usage

Usage is simple. Put a script tag in your HTML body wherever you want the added elements to go. Include a data attribute indicating your username.

Example:

`<script src="twitter-corner-widget.js" data-username="elidourado"></script>`

You can add a `data-gtag` attribute if you would like to include Google Analytics tracking for hover and click events on the widget.

`<script src="twitter-corner-widget.js" data-username="elidourado" data-gtag></script>`

By default, the widget uses `#1da1f2`, Twitter-brand blue, as its color. You can change it to match your brand using the `data-color` attribute.

`<script src="twitter-corner-widget.js" data-username="elidourado" data-color="orange"></script>`
