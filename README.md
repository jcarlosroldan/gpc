# Global Privacy Control (GPC) enabler

This is the source code of the Chrome extension [GPC enabler](https://chromewebstore.google.com/detail/gpc-enabler/ilknagnpcicckgohjailfooamibaolnj), the most popular extension to enable GPC with over 3,000 downloads.

It's the minimal amount of code required to be fully compliant with [Global Privacy Control](https://en.wikipedia.org/wiki/Global_Privacy_Control), a set of technologies that allows websites to passively detect your cookie and tracking preferences. If this became a default (or even enforced!) practice, we could get rid of all those terrible cookie popups, and the web would be a nicer place again.

## How does it work?

At the HTTP level, the header `Sec-GPC` determines your default cookie preferences. For instance, sending a HTTP request with header `Sec-GPC: 1` signals that you want Global Privacy Control to be enabled, hence opting out of all non-necessary data collection methods.

At the browser's level, the property `navigator.globalPrivacyControl: true` being enabled has the same effect.
