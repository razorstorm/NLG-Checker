## Technicals:
***

It uses javascript (jQuery) to send a GET request to mangafox, then uses the jQuery() function to build a DOM element out of the returned html. With this DOM tree as the context, nlgchecker selects the top most chapter li element and grabs the date.

Afterwards, it grabs the current date, massage it into the same format, and compare the strings. If the two dates are different, output OLG.

I used https://github.com/padolsey/jQuery-Plugins/tree/master/cross-domain-ajax/ to enable cross domain GET requests via javascript.
