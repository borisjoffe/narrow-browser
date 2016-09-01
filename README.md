# Narrow Browser

### Install from [GreasyFork](https://greasyfork.org/en/scripts/17115-narrow-browser)

### NOT production ready - causes some pages to look bad or have page content hidden.

- Change maximum width of most page elements to be slightly less than the current browser width.
- Updates the max width when the browser window is resized.

Requires
--------
One of the following:
- [TamperMonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=en) with [Chrome](https://www.google.com/chrome/browser/)
- [GreaseMonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/) with [Firefox](https://www.mozilla.org/firefox)
- [ViolentMonkey](https://addons.opera.com/en/extensions/details/violent-monkey/) / [TamperMonkey](https://addons.opera.com/en/extensions/details/tampermonkey-beta/?display=en) with [Opera](http://www.opera.com/) - untested

## Add custom site exclude
If a site or specific web page looks bad, you can add a [custom exclusion rule](https://wiki.greasespot.net/Include_and_exclude_rules) to prevent this script from running on that page.

* Use `*` for wildcards
* Examples: `http://somesite.com/*`, `https://*.othersite.org/*`, `http://example.com/home/*.html`

#### In Firefox
* Go to `about:addons`
* Click _User Scripts_ (from the left sidebar) > _Narrow Browser_ > _Preferences_
* Under _Excluded Pages_, add the site URL(s) to exclude

#### In Chrome
* Click the TamperMonkey icon near the top right
* Click _Dashboard_ > _Narrow Browser_ > _Settings_ tab
* Go to _User excludes_ > _Add_ > add the site URL(s) to exclude


# LICENSE
MIT
