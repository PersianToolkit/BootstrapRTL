<p align="center">
  <a href="https://getbootstrap.com/">
    <img src="https://getbootstrap.com/docs/4.1/assets/brand/bootstrap-solid.svg" alt="Bootstrap logo" width=72 height=72>
    <img src="http://uupload.ir/files/mp0h_rtl.png" alt="Bootstrap logo" width=36 height=36>
  </a>
  
  <h3 align="center">Bootstrap<sub><b>RTL</b></sub></h3>
  <h6 align="center">PersianToolkit</h6>

  <p align="center">
    an Extension for sleek, intuitive, and powerful front-end framework for faster and easier web development and having both rtl and ltr direction in your page.
    <br>
    <br> 
    <a href="https://persiantoolkit.github.io/BootstrapRTL/"><strong>Explore Bootstrap-RTL docs »</strong></a>
    <br>
    <br>
    <a href="https://github.com/PersianToolkit/BootstrapRTL/issues/new?template=bug.md">Report bug</a>
    ·
    <a href="https://github.com/PersianToolkit/BootstrapRTL/issues/new?template=feature.md&labels=feature">Request feature</a>
    ·
    <a href="https://themes.getbootstrap.com/">Themes</a>
  </p>
</p>


## Table of contents

- [Quick start](#quick-start)
- [Status](#status)
- [What's included](#whats-included)
- [Bugs and feature requests](#bugs-and-feature-requests)
- [Documentation](#documentation)
- [Contributing](#contributing)
- [Community](#community)
- [Versioning](#versioning)
- [Creators](#creators)
- [Thanks](#thanks)
- [Copyright and license](#copyright-and-license)


## Quick start

Several quick start options are available:

- [Download the latest release.](https://github.com/PersianToolkit/BootstrapRTL/archive/v4.1.3.zip)
- Clone the repo: `git clone https://github.com/PersianToolkit/BootstrapRTL.git`
- Install with [npm](https://www.npmjs.com/): `npm install PersianToolkit`
- Install with [yarn](https://yarnpkg.com/): `yarn add PersianToolkit@4.1.3`
- Install with [Composer](https://getcomposer.org/): `composer require PersianToolkit/bootstrapRTL:4.1.3`
- Install with [NuGet](https://www.nuget.org/): CSS: `Install-Package PersianToolkit` Sass: `Install-Package PersianToolkit.sass`

Read the [Getting started page](https://getbootstrap.com/docs/4.1/getting-started/introduction/) for information on the framework contents, templates and examples, and more.


## Status

[![Slack](https://bootstrap-slack.herokuapp.com/badge.svg)](https://bootstrap-slack.herokuapp.com/)
[![Build Status](https://img.shields.io/travis/twbs/bootstrap/v4-dev.svg)](https://travis-ci.org/twbs/bootstrap)
[![npm version](https://img.shields.io/npm/v/bootstrap.svg)](https://www.npmjs.com/package/bootstrap)
[![Gem version](https://img.shields.io/gem/v/bootstrap.svg)](https://rubygems.org/gems/bootstrap)
[![Meteor Atmosphere](https://img.shields.io/badge/meteor-twbs%3Abootstrap-blue.svg)](https://atmospherejs.com/twbs/bootstrap)
[![Packagist Prerelease](https://img.shields.io/packagist/vpre/twbs/bootstrap.svg)](https://packagist.org/packages/twbs/bootstrap)
[![NuGet](https://img.shields.io/nuget/vpre/bootstrap.svg)](https://www.nuget.org/packages/bootstrap/absoluteLatest)
[![peerDependencies Status](https://img.shields.io/david/peer/twbs/bootstrap.svg)](https://david-dm.org/twbs/bootstrap?type=peer)
[![devDependency Status](https://img.shields.io/david/dev/twbs/bootstrap.svg)](https://david-dm.org/twbs/bootstrap?type=dev)
[![Coverage Status](https://img.shields.io/coveralls/github/twbs/bootstrap/v4-dev.svg)](https://coveralls.io/github/twbs/bootstrap?branch=v4-dev)
[![CSS gzip size](https://img.badgesize.io/twbs/bootstrap/v4-dev/dist/css/bootstrap.min.css?compression=gzip&label=CSS+gzip+size)](https://github.com/twbs/bootstrap/tree/v4-dev/dist/css/bootstrap.min.css)
[![JS gzip size](https://img.badgesize.io/twbs/bootstrap/v4-dev/dist/js/bootstrap.min.js?compression=gzip&label=JS+gzip+size)](https://github.com/twbs/bootstrap/tree/v4-dev/dist/js/bootstrap.min.js)
[![BrowserStack Status](https://www.browserstack.com/automate/badge.svg?badge_key=SkxZcStBeExEdVJqQ2hWYnlWckpkNmNEY213SFp6WHFETWk2bGFuY3pCbz0tLXhqbHJsVlZhQnRBdEpod3NLSDMzaHc9PQ==--3d0b75245708616eb93113221beece33e680b229)](https://www.browserstack.com/automate/public-build/SkxZcStBeExEdVJqQ2hWYnlWckpkNmNEY213SFp6WHFETWk2bGFuY3pCbz0tLXhqbHJsVlZhQnRBdEpod3NLSDMzaHc9PQ==--3d0b75245708616eb93113221beece33e680b229)
[![Backers on Open Collective](https://opencollective.com/bootstrap/backers/badge.svg)](#backers)
[![Sponsors on Open Collective](https://opencollective.com/bootstrap/sponsors/badge.svg)](#sponsors)


## What's included

Within the download you'll find the following directories and files, logically grouping common assets and providing both compiled and minified variations. You'll see something like this:

```text
bootstrap/
├── dist/
│   ├── css/
│   │   ├── bootstrap-grid.css
│   │   ├── bootstrap-grid.css.map
│   │   ├── bootstrap-grid.min.css
│   │   ├── bootstrap-grid.min.css.map
│   │   ├── bootstrap-reboot.css
│   │   ├── bootstrap-reboot.css.map
│   │   ├── bootstrap-reboot.min.css
│   │   ├── bootstrap-reboot.min.css.map
│   │   ├── bootstrap.css
│   │   ├── bootstrap.css.map
│   │   ├── bootstrap.min.css
│   │   └── bootstrap.min.css.map
│   └── js/
│       ├── bootstrap.bundle.js
│       ├── bootstrap.bundle.js.map
│       ├── bootstrap.bundle.min.js
│       ├── bootstrap.bundle.min.js.map
│       ├── bootstrap.js
│       ├── bootstrap.js.map
│       ├── bootstrap.min.js
│       └── bootstrap.min.js.map
│       
└── dist-rtl/  
    └──css/
       ├── bootstrap-grid-rtl.css
       ├── bootstrap-grid-rtl.css.map
       ├── bootstrap-grid-rtl.min.css
       ├── bootstrap-grid-rtl.min.css.map
       ├── bootstrap-reboot-rtl.css
       ├── bootstrap-reboot-rtl.css.map
       ├── bootstrap-reboot-rtl.min.css
       ├── bootstrap-reboot-rtl.min.css.map
       ├── bootstrap-rtl.css
       ├── bootstrap-rtl.css.map
       ├── bootstrap-rtl.min.css
       └── bootstrap-rtl.min.css.map
```

We provide compiled CSS and JS (`bootstrap.*`), as well as compiled and minified CSS and JS (`bootstrap.min.*`). [source maps](https://developers.google.com/web/tools/chrome-devtools/debug/readability/source-maps) (`bootstrap.*.map`) are available for use with certain browsers' developer tools. Bundled JS files (`bootstrap.bundle.js` and minified `bootstrap.bundle.min.js`) include [Popper](https://popper.js.org/), but not [jQuery](https://jquery.com/).


## Bugs and feature requests

Have a bug or a feature request? Please first read our latest [issue](https://github.com/PersianToolkit/BootstrapRTL/issues) and search for existing and closed issues. If your problem or idea is not addressed yet, [please open a new issue](https://github.com/PersianToolkit/BootstrapRTL/issues/new).


## Documentation

Bootstrap's documentation, included in this repo in the root directory, is built with [Jekyll](https://jekyllrb.com/) and publicly hosted on GitHub Pages at <https://persiantoolkit.github.io/BootstrapRTL/>. The docs may also be run locally.

### Documentation for previous releases

We will allocate it here.

[Previous releases](https://github.com/PersianToolkit/BootstrapRTL/releases) and their documentation are also available for download.


## Versioning

For transparency into our release cycle and in striving to maintain backward compatibility, Bootstrap is maintained under [the Semantic Versioning guidelines](https://semver.org/). Sometimes we screw up, but we adhere to those rules whenever possible.

See [the Releases section of our GitHub project](https://github.com/PersianToolkit/BootstrapRTLreleases) for changelogs for each release version of Bootstrap. 


## Creators

**Farhang Vafa**

- <https://github.com/Farhangv>

**Pouya Shakeri**

- <https://github.com/pouyapoosh>

**Hossein Golmohammadi**

- <https://github.com/Hosein201>

**Mohammadali Moadeli**

- <https://github.com/elder1360>

## Thanks

<a href="https://www.browserstack.com/">
  <img src="https://live.browserstack.com/images/opensource/browserstack-logo.svg" alt="BrowserStack Logo" width="490" height="106">
</a>

Thanks to [BrowserStack](https://www.browserstack.com/) for providing the infrastructure that allows us to test in real browsers!


## Sponsors

Support this project by becoming a sponsor. Your logo will show up here with a link to your website. [[Become a sponsor](https://opencollective.com/bootstrap#sponsor)]


## Copyright and license

Code and documentation copyright 2018 the [Bootstrap Authors](https://github.com/PersianToolkit/BootstrapRTL/graphs/contributors) and [Twitter, Inc.](https://twitter.com) Code released under the [MIT License](https://github.com/PersianToolkit/BootstrapRTL/blob/master/LICENSE). Docs released under [Creative Commons](https://github.com/PersianToolkit/BootstrapRTL/blob/master/docs/LICENSE).
