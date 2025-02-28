[![Build Status](https://travis-ci.org/jgraph/drawio.svg?branch=master)](https://travis-ci.org/jgraph/drawio)

About
-----
[draw.io](https://www.draw.io) is an online diagramming web site that delivers the source in this project.

draw.io uses the [mxGraph library](https://github.com/jgraph/mxgraph) as the base of the stack, with the [GraphEditor example](https://github.com/jgraph/mxgraph/tree/master/javascript/examples/grapheditor) from mxGraph as the base of the application part. The mxGraph library build used is stored under /etc/mxgraph/mxClient.js.

License
-------
draw.io is licensed under the Apache v2.

Development
-----------

A development guide is being started on the GitHub project wiki. There is a [draw.io](http://stackoverflow.com/questions/tagged/draw.io) tag on Stack Overflow currently, please make sure any questions adhere to their guidelines for question.

The [mxGraph documentation](https://jgraph.github.io/mxgraph/) provides a lot of the docs for the bottom part of the stack. There is an [mxgraph tag on SO](http://stackoverflow.com/questions/tagged/mxgraph).

Running
-------
One way to run draw.io is to fork this project, [publish the master branch to GitHub pages](https://help.github.com/categories/github-pages-basics/) and the [pages sites](https://mhgharieb.github.io/drawio/src/main/webapp/index.html) will have the full editor functionality (sans the integrations).

Another way is to use [the recommended Docker project](https://github.com/fjudith/docker-draw.io) or to download [draw.io Desktop](https://get.draw.io).

The full packaged .war of the client and servlets is built when the project is tagged and available on the [releases page](https://github.com/jgraph/draw.io/releases).

Supported Browsers
------------------
draw.io supports IE 11, Chrome 32+, Firefox 38+, Safari 9.1.x, 10.1.x and 11.0.x, Opera 20+, Native Android browser 5.1.x+, the default browser in the current and previous major iOS versions (e.g. 11.2.x and 10.3.x) and Edge 23+.
