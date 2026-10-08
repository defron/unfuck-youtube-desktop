# unfuck-youtube-desktop
Various hacks from me trying to unfuck youtube's UI

A lot of stuff very much so WIP please help and make better if you can!

Structure:

* css: holds fixes for use with Stylus
* js: holds fixes for use with tampermonkey/violentmonkey
* ubo: holds fixes for use with Ublock Origin
* screenshots: holds screenshots of some of the changes (duh)

Usage:

css overrides: install [Stylus](https://github.com/openstyles/stylus) ([Firefox](https://addons.mozilla.org/en-US/firefox/addon/styl-us/), [Chrome](https://chromewebstore.google.com/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne?pli=1)) and put the userCSS rules in it for youtube. You can also install it from [userstyles.world](https://userstyles.world/style/30654)


![stylus changes](screenshots/desktop-youtube.webp)


TODO:

 * make things more responsive (anyone with 4k screen that can help out would be appreciated!)
 * make a style that works for non-theater mode (theater mode is my preferred viewing method)
 * ~~make theater mode video bigger~~
 * make video descriptions work better (right now: toggle-on good. toggle-off kills comments)
 * move UBO rules to css.