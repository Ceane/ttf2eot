ttf2eot
=======

This is node.js port of [ttf2eot](http://code.google.com/p/ttf2eot/). It
converts TTF fonts to EOT format.


Usage
-----

Install:

``` bash
npm install -g ttf2eot
```

Usage:

``` bash
ttf2eot -i fontello.ttf -o fontello.oet
```


Possible problems
-----------------

Due to bug in IE, font `FullName` __MUST__ begin with `FamilyName`. For example,
if `FamilyName` is `fontello`, then `FullName` should be `fontello regular` and
so on.

In this condition is not satisfyed, then font will not be shown in IE.


Authors
-------

* Victor Semykin <thesame.ml@gmail.com>


License
-------

Copyright (c) 2012 [Vitaly Puzrin](https://github.com/puzrin).
Released under the MIT license. See
[LICENSE](https://github.com/nodeca/ttf2eot/blob/master/LICENSE) for details.

