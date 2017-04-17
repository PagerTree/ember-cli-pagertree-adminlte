ember-cli-pagertree-adminlte
====================

[![npm version](https://badge.fury.io/js/ember-cli-pagertree-adminlte.svg)](https://badge.fury.io/js/ember-cli-pagertree-adminlte)
[![Ember Observer Score](https://emberobserver.com/badges/ember-cli-pagertree-adminlte.svg)](https://emberobserver.com/addons/ember-cli-pagertree-adminlte)

An [ember-cli addon](http://www.emberaddons.com/) to import a [PagerTree AdminLTE](https://github.com/PagerTree/AdminLTE)
theme, including the fonts and JavaScript. This addon is only meant to import the
related bower files and does NOT contain [Ember Components](http://emberjs.com/guides/components/)
to use within your templates. Other addons provide those features,
[search emberaddons.com](http://www.emberaddons.com/?query=bootstrap) for
those.

## Installation

From within your [ember-cli](http://www.ember-cli.com/) project, run the
following to install the addon and bower dependencies for bootstrap and
bootswatch:

```bash
ember install ember-cli-pagertree-adminlte
```

Note: This addon _is_ compatible with ember-cli 2.x

## Usage with other Bootstrap addons

Other Bootstrap addons should be configured NOT to import Bootstrap files
(styles, themes, fonts, etc.) This way files imported by ember-cli-pagertree-adminlte
do not conflict with other files and versions. But at the same time, if another
addon requires their own version of a core file (such as JavaScript), then disable
the import from Bootswatch.
