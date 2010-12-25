SubtleLocationProxy
===================

Proxy the location of one frame to the hash of another and vice-versa.

It's handy for sites that simply wrap a fancy UI around simple HTML pages.


Usage
-----

1. Include the `SubtleLocationProxy.js` script[src] in your page (on the bottom, like normal).
2. Add the `data-history=proxy` attribute to an `IFRAME` element.
3. Enjoy the awesomenesses.

Note: If your browser doesn't support `document.querySelector` then you'll need to have either `window.$$` (e.g. MooTools) or `window.$` (e.g. jQuery) to get the single `[data-history~=proxy]` CSS selector working. Alternatively you can set `window.SubtleLocationProxy_element` to your element-to-proxy before loading SubtleLocationProxy.

Browser Support
---------------

Tested in...

* Safari 5
* Chrome 9
* IE8
* Firefox 3.6
* IE6
	* IE6 creates double history. You need to hit back twice in a row to go back.

It'll probly work in tons of other browsers too, it's not doing anything magical.
