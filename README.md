# My Firefox recommendations
My Firefox recommendations

* [all Firefox Downloads](https://www.mozilla.org/en-US/firefox/all/)

## Upstream

* find an add blocking DNS service. I use NextDNS.io(https://nextdns.io) that allows user fiddling.  enable advanced mode
* configure DNS over HTTPS in firefox (options, network, check box, enter value)
* pick a VPN service with either native adblock  (TorGuard.net, nordvpn, windscribe) or user configurable DNS resolvers (ivpn) not spending more than 50 usd annually.  

## Addons

### Bare minimum

* uBlock Origin (see [uBlock Origin recommendations](https://github.com/theel0ja/ubo-recommendations/blob/master/README.md))
* Privacy Possum
* [HTTPS Everywhere](https://addons.mozilla.org/en-US/firefox/addon/https-everywhere/)
* [Redirect AMP to HTML](https://addons.mozilla.org/en-US/firefox/addon/amp2html/)
* [View Image](https://addons.mozilla.org/en-US/firefox/addon/view-image/)
* [Cookie AutoDelete](https://addons.mozilla.org/en-US/firefox/addon/cookie-autodelete/) (tweaks: enable autoclean)
* [Anti paywall](https://github.com/nextgens/anti-paywall/releases)
* WebRTC

### For advanced users

* [uMatrix](https://addons.mozilla.org/en-US/firefox/addon/umatrix/) (see [my startingpoint](https://github.com/theel0ja/uMatrix-rules))

### Conveniences

* stop using "free" google services
* security for convenience is no more acceptable than privacy for convenience


### Privacy
* Replace [Privacy Badger](https://addons.mozilla.org/en-US/firefox/addon/privacy-badger17/) with the fork Privacy Possum
* [Decentraleyes](https://addons.mozilla.org/en-US/firefox/addon/decentraleyes/)
* Stop using Facebook
* [uBO-Scope](https://addons.mozilla.org/en-US/firefox/addon/ubo-scope/)

### Miscellaneous

* [FoxyProxy Standard](https://addons.mozilla.org/en-US/firefox/addon/foxyproxy-standard/) (check out if your VPN provider has SOCKS proxies)  warning socks5 is not encrypted like you thing
* [Stylus](https://addons.mozilla.org/en-US/firefox/addon/styl-us/) ([Dark mode guide](https://github.com/theel0ja/dark-theme-on-web/blob/master/README.md), [Lists I use](https://github.com/theel0ja/Stylus-Lists))
* [Redirector](http://einaregilsson.com/redirector/) (see [Dandelion Sprout's Redirector Assistant List](https://github.com/DandelionSprout/adfilt/tree/master/Dandelion%20Sprout-s%20Redirector%20Assistant%20List))

## Settings

* Set Firefox as default browser
* learn how to create multiple firefox profiles.  Change your shortcut to use the profile manager switch to invoke selection on click.
* FIRST add the user.js(https://github.com/ghacksuserjs/ghacks-user.js/wiki/1.1-Overview) to your respective profile directory from the Ghacks user.js github
* Set search engine to [DuckDuckGo](https://duckduckgo.com/) (or [Startpage](https://www.startpage.com/))
* Block 3rd-party cookies



## about:config

<!-- needs expansion -->

- `browser.ctrlTab.recentlyUsedOrder` = false
- `view_source.wrap_long_lines` = true
- `extensions.pocket.enabled` = false
- `general.autoScroll` = true (useful on linux especially)
