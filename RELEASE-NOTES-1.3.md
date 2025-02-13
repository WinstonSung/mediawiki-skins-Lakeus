# mediawiki-skins-Lakeus 1.3

## mediawiki-skins-Lakeus 1.3.1+REL1.39

This is a security release of the mediawiki-skins-Lakeus 1.3 version with MediaWiki 1.39.x.

This release contains a security fix, all websites using Lakeus skin should apply this update!

### Bug fixes

* (#55, GHSA-mq77-3q68-v64v) SECURITY: Fixed stored XSS via system messages.

### Languages updated

Lakeus skin now supports 27 languages. Many localisations are updated regularly.

## mediawiki-skins-Lakeus 1.3.0

This is the first release of the mediawiki-skins-Lakeus 1.3 version.

This will be the last release support non-latest-stable MediaWiki version
1.39.x, 1.41.x, 1.42.x in the master branch.
Please switch to MediaWiki-version-specific branches and versions instead.

### Bug fixes in 1.3.0

* Removed duplicate `<h1>` from `#logo-text`.
* Updated logic and fixed styles of `.mw-portlet-dropdown`.
* Removed unnecessary slash from `<input>`.
* Removed unnecessary `role` attribute from `<footer>`.
* Added `aria-pressed` attribute for `#sidebar-input`.

### Languages updated in 1.3.0

Lakeus skin now supports 27 languages. Many localisations are updated regularly.

### Breaking changes in 1.3.0

* This will be the last release support non-latest-stable MediaWiki version
  1.39.x, 1.41.x, 1.42.x in the master branch.
  Please switch to MediaWiki-version-specific branches and versions instead.
