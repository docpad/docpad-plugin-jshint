<!-- TITLE/ -->

<h1>docpad-plugin-jshint</h1>

<!-- /TITLE -->


<!-- BADGES/ -->

<span class="badge-travisci"><a href="http://travis-ci.com/docpad/docpad-plugin-jshint" title="Check this project's build status on TravisCI"><img src="https://img.shields.io/travis/com/docpad/docpad-plugin-jshint/master.svg" alt="Travis CI Build Status" /></a></span>
<span class="badge-npmversion"><a href="https://npmjs.org/package/docpad-plugin-jshint" title="View this project on NPM"><img src="https://img.shields.io/npm/v/docpad-plugin-jshint.svg" alt="NPM version" /></a></span>
<span class="badge-npmdownloads"><a href="https://npmjs.org/package/docpad-plugin-jshint" title="View this project on NPM"><img src="https://img.shields.io/npm/dm/docpad-plugin-jshint.svg" alt="NPM downloads" /></a></span>
<span class="badge-daviddm"><a href="https://david-dm.org/docpad/docpad-plugin-jshint" title="View the status of this project's dependencies on DavidDM"><img src="https://img.shields.io/david/docpad/docpad-plugin-jshint.svg" alt="Dependency Status" /></a></span>
<span class="badge-daviddmdev"><a href="https://david-dm.org/docpad/docpad-plugin-jshint#info=devDependencies" title="View the status of this project's development dependencies on DavidDM"><img src="https://img.shields.io/david/dev/docpad/docpad-plugin-jshint.svg" alt="Dev Dependency Status" /></a></span>
<br class="badge-separator" />
<span class="badge-githubsponsors"><a href="https://github.com/sponsors/balupton" title="Donate to this project using GitHub Sponsors"><img src="https://img.shields.io/badge/github-donate-yellow.svg" alt="GitHub Sponsors donate button" /></a></span>
<span class="badge-patreon"><a href="https://patreon.com/bevry" title="Donate to this project using Patreon"><img src="https://img.shields.io/badge/patreon-donate-yellow.svg" alt="Patreon donate button" /></a></span>
<span class="badge-flattr"><a href="https://flattr.com/profile/balupton" title="Donate to this project using Flattr"><img src="https://img.shields.io/badge/flattr-donate-yellow.svg" alt="Flattr donate button" /></a></span>
<span class="badge-liberapay"><a href="https://liberapay.com/bevry" title="Donate to this project using Liberapay"><img src="https://img.shields.io/badge/liberapay-donate-yellow.svg" alt="Liberapay donate button" /></a></span>
<span class="badge-buymeacoffee"><a href="https://buymeacoffee.com/balupton" title="Donate to this project using Buy Me A Coffee"><img src="https://img.shields.io/badge/buy%20me%20a%20coffee-donate-yellow.svg" alt="Buy Me A Coffee donate button" /></a></span>
<span class="badge-opencollective"><a href="https://opencollective.com/bevry" title="Donate to this project using Open Collective"><img src="https://img.shields.io/badge/open%20collective-donate-yellow.svg" alt="Open Collective donate button" /></a></span>
<span class="badge-crypto"><a href="https://bevry.me/crypto" title="Donate to this project using Cryptocurrency"><img src="https://img.shields.io/badge/crypto-donate-yellow.svg" alt="crypto donate button" /></a></span>
<span class="badge-paypal"><a href="https://bevry.me/paypal" title="Donate to this project using Paypal"><img src="https://img.shields.io/badge/paypal-donate-yellow.svg" alt="PayPal donate button" /></a></span>
<span class="badge-wishlist"><a href="https://bevry.me/wishlist" title="Buy an item on our wishlist for us"><img src="https://img.shields.io/badge/wishlist-donate-yellow.svg" alt="Wishlist browse button" /></a></span>

<!-- /BADGES -->


<!-- DESCRIPTION/ -->

JSHint plugin for docpad

<!-- /DESCRIPTION -->


## Configure

For information on customizing your plugin configuration you can refer to the [DocPad FAQ](https://github.com/bevry/docpad/wiki/FAQ)

### Ignore Files

```
ignoreFiles: ['path/file.js']
```

`ignoreFiles` accepts an array of file paths to ignore while hinting.

### Ignore Paths

```
ignorePaths: ['path/']
```

`ignorePaths` accepts an array of directory paths to ignore while hinting.

### Ignore Minified Files

```
ignoreMinified: boolean
```

`ignoreMinified` accepts a boolean which determines whether files ending in `.min.js` are ignored. The default is `true`.

### Globals

```
globals: {var: boolean}
```

`globals` is an object of global variables, with keys as names and a boolean value to determine if they are assignable.

It's recommended you define these in a `.jshintrc` file instead of config options to make your preferences more portable.

### JSHint options

`hintOptions` is an object where you can pass any of [JSHint's options](http://www.jshint.com/docs/options/)

It's recommended you define these in a `.jshintrc` file instead of config options to make your preferences more portable.









<!-- INSTALL/ -->

<h2>Install</h2>

Install this DocPad plugin by entering <code>docpad install jshint</code> into your terminal.

<!-- /INSTALL -->


<!-- HISTORY/ -->

<h2>History</h2>

<a href="https://github.com/docpad/docpad-plugin-jshint/blob/master/HISTORY.md#files">Discover the release history by heading on over to the <code>HISTORY.md</code> file.</a>

<!-- /HISTORY -->


<!-- CONTRIBUTE/ -->

<h2>Contribute</h2>

<a href="https://github.com/docpad/docpad-plugin-jshint/blob/master/Contributing.md#files">Discover how you can contribute by heading on over to the <code>Contributing.md</code> file.</a>

<!-- /CONTRIBUTE -->


<!-- BACKERS/ -->

<h2>Backers</h2>

<h3>Maintainers</h3>

These amazing people are maintaining this project:

<ul><li><a href="10x.la/croixdrinker">Jamie King</a> — <a href="https://github.com/docpad/docpad-plugin-jshint/commits?author=10xLaCroixDrinker" title="View the GitHub contributions of Jamie King on repository docpad/docpad-plugin-jshint">view contributions</a></li></ul>

<h3>Sponsors</h3>

No sponsors yet! Will you be the first?

<span class="badge-githubsponsors"><a href="https://github.com/sponsors/balupton" title="Donate to this project using GitHub Sponsors"><img src="https://img.shields.io/badge/github-donate-yellow.svg" alt="GitHub Sponsors donate button" /></a></span>
<span class="badge-patreon"><a href="https://patreon.com/bevry" title="Donate to this project using Patreon"><img src="https://img.shields.io/badge/patreon-donate-yellow.svg" alt="Patreon donate button" /></a></span>
<span class="badge-flattr"><a href="https://flattr.com/profile/balupton" title="Donate to this project using Flattr"><img src="https://img.shields.io/badge/flattr-donate-yellow.svg" alt="Flattr donate button" /></a></span>
<span class="badge-liberapay"><a href="https://liberapay.com/bevry" title="Donate to this project using Liberapay"><img src="https://img.shields.io/badge/liberapay-donate-yellow.svg" alt="Liberapay donate button" /></a></span>
<span class="badge-buymeacoffee"><a href="https://buymeacoffee.com/balupton" title="Donate to this project using Buy Me A Coffee"><img src="https://img.shields.io/badge/buy%20me%20a%20coffee-donate-yellow.svg" alt="Buy Me A Coffee donate button" /></a></span>
<span class="badge-opencollective"><a href="https://opencollective.com/bevry" title="Donate to this project using Open Collective"><img src="https://img.shields.io/badge/open%20collective-donate-yellow.svg" alt="Open Collective donate button" /></a></span>
<span class="badge-crypto"><a href="https://bevry.me/crypto" title="Donate to this project using Cryptocurrency"><img src="https://img.shields.io/badge/crypto-donate-yellow.svg" alt="crypto donate button" /></a></span>
<span class="badge-paypal"><a href="https://bevry.me/paypal" title="Donate to this project using Paypal"><img src="https://img.shields.io/badge/paypal-donate-yellow.svg" alt="PayPal donate button" /></a></span>
<span class="badge-wishlist"><a href="https://bevry.me/wishlist" title="Buy an item on our wishlist for us"><img src="https://img.shields.io/badge/wishlist-donate-yellow.svg" alt="Wishlist browse button" /></a></span>

<h3>Contributors</h3>

These amazing people have contributed code to this project:

<ul><li><a href="https://github.com/balupton">Benjamin Lupton</a> — <a href="https://github.com/docpad/docpad-plugin-jshint/commits?author=balupton" title="View the GitHub contributions of Benjamin Lupton on repository docpad/docpad-plugin-jshint">view contributions</a></li>
<li><a href="https://github.com/greenkeeperio-bot">Greenkeeper</a> — <a href="https://github.com/docpad/docpad-plugin-jshint/commits?author=greenkeeperio-bot" title="View the GitHub contributions of Greenkeeper on repository docpad/docpad-plugin-jshint">view contributions</a></li>
<li><a href="10x.la/croixdrinker">Jamie King</a> — <a href="https://github.com/docpad/docpad-plugin-jshint/commits?author=10xLaCroixDrinker" title="View the GitHub contributions of Jamie King on repository docpad/docpad-plugin-jshint">view contributions</a></li>
<li><a href="https://github.com/nfriedly">Nathan Friedly</a> — <a href="https://github.com/docpad/docpad-plugin-jshint/commits?author=nfriedly" title="View the GitHub contributions of Nathan Friedly on repository docpad/docpad-plugin-jshint">view contributions</a></li>
<li><a href="https://github.com/paleite">Patrick Eriksson</a> — <a href="https://github.com/docpad/docpad-plugin-jshint/commits?author=paleite" title="View the GitHub contributions of Patrick Eriksson on repository docpad/docpad-plugin-jshint">view contributions</a></li></ul>

<a href="https://github.com/docpad/docpad-plugin-jshint/blob/master/Contributing.md#files">Discover how you can contribute by heading on over to the <code>Contributing.md</code> file.</a>

<!-- /BACKERS -->


<!-- LICENSE/ -->

<h2>License</h2>

Unless stated otherwise all works are:

<ul><li>Copyright &copy; <a href="10x.la/croixdrinker">Jamie King</a></li></ul>

and licensed under:

<ul><li><a href="http://spdx.org/licenses/MIT.html">MIT License</a></li></ul>

<!-- /LICENSE -->
