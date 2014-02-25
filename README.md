[![build status](https://secure.travis-ci.org/codeparty/derby.png)](http://travis-ci.org/codeparty/derby)

# Derby

The Derby MVC framework makes it easy to write realtime, collaborative applications that run in both Node.js and browsers.

Derby includes a powerful data synchronization engine called Racer that automatically syncs data among browsers, servers, and a database. Models subscribe to changes on specific objects, enabling granular control of data propagation without defining channels. Racer supports offline usage and conflict resolution out of the box, which greatly simplifies writing multi-user applications.

Derby applications load immediately and can be indexed by search engines, because the same templates render on both server and client. In addition, templates define bindings, which instantly update the view when the model changes and vice versa. Derby makes it simple to write applications that load as fast as a search engine, are as interactive as a document editor, and work offline.

See docs here: **http://derbyjs.com/**

Examples here: **https://github.com/codeparty/derby-examples**

## Major updates coming soon!

The current version of Derby is really buggy. We know this, and the next version (0.6) is going to be the first beta quality release.

0.6 is a complete rewrite that will funadamentally change a lot of things internally. 0.6 will increase performance, reduce memory leaks, and improve stability. There will be a number of API changes, but they will be straightforward for current Derby apps. Most of the changes are simplifications that will clean up awkward limitiations of the current version. This next release is where all of our current efforts are, and we aren't planning on fixing any issues with the current version of Derby.

Racer, on the other hand, will not be changed substantially. Racer is much more stable, and any issues with Racer should be submitted (especially if you write a failing test! :-).

If you have feedback, ideas, or suggestions, please message the [Google Group](http://groups.google.com/group/derbyjs) or create an Issue. If you are interested in contributing, please reach out to [Nate](https://github.com/nateps).

## MIT License
Copyright (c) 2011-2014 by Nate Smith and Brian Noguchi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
