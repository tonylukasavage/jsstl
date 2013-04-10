jsstl
=====

Pure Javascript demo code for parsing and rendering STL (ascii and binary) files.

The code is currently tightly coupled between the STL parsing and three.js geometry creation for the sake of initial rendering speed. That said, it would be relatively trivial to make the `parseStl()` and `parseStlBinary()` functions be renderer-agnostic. Feel free to cannibalize the code as you see fit.

try it out
----------

Dump this repo on a web server and open up **index.html** in a browser. Voila, [octocat](http://www.thingiverse.com/thing:10367)!

thanks to
---------
* [three.js](https://github.com/mrdoob/three.js/) for the ability to render the 3D models in WebGL/Canvas via Javascript
* [Mozilla Devloper Network](https://developer.mozilla.org/en-US/) for the tremendously well-written docs on [Javascript typed arrays](https://developer.mozilla.org/en-US/docs/JavaScript/Typed_arrays)

license
-------

Do whatever you want with this code. I offer it without expectation or warranty. No need to credit me in your project or source code. A [digital high five](https://twitter.com/tonylukasavage) would be nice, but is not required.

me
-----

**[@tonylukasavage](https://twitter.com/tonylukasavage)**