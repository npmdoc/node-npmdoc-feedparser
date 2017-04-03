# api documentation for  [feedparser (v2.1.0)](http://github.com/danmactough/node-feedparser)  [![npm package](https://img.shields.io/npm/v/npmdoc-feedparser.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-feedparser) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-feedparser.svg)](https://travis-ci.org/npmdoc/node-npmdoc-feedparser)
#### Robust RSS Atom and RDF feed parsing using sax js

[![NPM](https://nodei.co/npm/feedparser.png?downloads=true)](https://www.npmjs.com/package/feedparser)

[![apidoc](https://npmdoc.github.io/node-npmdoc-feedparser/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-feedparser_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-feedparser/build..beta..travis-ci.org/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-feedparser/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-feedparser/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dan MacTough",
        "email": "danmactough@gmail.com"
    },
    "bin": {
        "feedparser": "./bin/feedparser.js"
    },
    "bugs": {
        "url": "http://github.com/danmactough/node-feedparser/issues"
    },
    "dependencies": {
        "addressparser": "^1.0.1",
        "array-indexofobject": "~0.0.1",
        "lodash.assign": "^4.2.0",
        "lodash.get": "^4.4.2",
        "lodash.has": "^4.5.2",
        "lodash.uniq": "^4.5.0",
        "readable-stream": "^2.2.2",
        "sax": "^1.2.1"
    },
    "description": "Robust RSS Atom and RDF feed parsing using sax js",
    "devDependencies": {
        "eslint": "^2.11.1",
        "iconv": "2.2.1",
        "mocha": "^3.2.0",
        "request": "~2.79.0"
    },
    "directories": {},
    "dist": {
        "shasum": "4cd98bf04e18db5b8644f91e98da89dd179f1fe7",
        "tarball": "https://registry.npmjs.org/feedparser/-/feedparser-2.1.0.tgz"
    },
    "engines": {
        "node": ">= 4.2.0"
    },
    "gitHead": "beeba05294ee57650310dacec5291391f6083cf4",
    "homepage": "http://github.com/danmactough/node-feedparser",
    "keywords": [
        "rss",
        "feed",
        "atom",
        "rdf",
        "xml",
        "syndication",
        "rsscloud",
        "pubsubhubbub"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "danmactough",
            "email": "danmactough@gmail.com"
        }
    ],
    "name": "feedparser",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/danmactough/node-feedparser.git"
    },
    "scripts": {
        "lint": "eslint .",
        "pretest": "npm run lint",
        "test": "mocha"
    },
    "version": "2.1.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module feedparser](#apidoc.module.feedparser)
1.  [function <span class="apidocSignatureSpan">feedparser.</span>super_ (options)](#apidoc.element.feedparser.super_)
1.  [function <span class="apidocSignatureSpan">feedparser.</span>super_.super_ (options)](#apidoc.element.feedparser.super_.super_)
1.  object <span class="apidocSignatureSpan">feedparser.</span>super_.prototype
1.  object <span class="apidocSignatureSpan">feedparser.</span>super_.super_.prototype
1.  object <span class="apidocSignatureSpan">feedparser.</span>super_.super_.super_.prototype
1.  object <span class="apidocSignatureSpan">feedparser.</span>utils

#### [module feedparser.super_](#apidoc.module.feedparser.super_)
1.  [function <span class="apidocSignatureSpan">feedparser.</span>super_ (options)](#apidoc.element.feedparser.super_.super_)

#### [module feedparser.super_.prototype](#apidoc.module.feedparser.super_.prototype)
1.  [function <span class="apidocSignatureSpan">feedparser.super_.prototype.</span>_read (n)](#apidoc.element.feedparser.super_.prototype._read)
1.  [function <span class="apidocSignatureSpan">feedparser.super_.prototype.</span>_transform (chunk, encoding, cb)](#apidoc.element.feedparser.super_.prototype._transform)
1.  [function <span class="apidocSignatureSpan">feedparser.super_.prototype.</span>_write (chunk, encoding, cb)](#apidoc.element.feedparser.super_.prototype._write)
1.  [function <span class="apidocSignatureSpan">feedparser.super_.prototype.</span>push (chunk, encoding)](#apidoc.element.feedparser.super_.prototype.push)

#### [module feedparser.super_.super_](#apidoc.module.feedparser.super_.super_)
1.  [function <span class="apidocSignatureSpan">feedparser.super_.</span>super_ (options)](#apidoc.element.feedparser.super_.super_.super_)

#### [module feedparser.super_.super_.prototype](#apidoc.module.feedparser.super_.super_.prototype)
1.  [function <span class="apidocSignatureSpan">feedparser.super_.super_.prototype.</span>_write (chunk, encoding, cb)](#apidoc.element.feedparser.super_.super_.prototype._write)
1.  [function <span class="apidocSignatureSpan">feedparser.super_.super_.prototype.</span>cork ()](#apidoc.element.feedparser.super_.super_.prototype.cork)
1.  [function <span class="apidocSignatureSpan">feedparser.super_.super_.prototype.</span>end (chunk, encoding, cb)](#apidoc.element.feedparser.super_.super_.prototype.end)
1.  [function <span class="apidocSignatureSpan">feedparser.super_.super_.prototype.</span>setDefaultEncoding (encoding)](#apidoc.element.feedparser.super_.super_.prototype.setDefaultEncoding)
1.  [function <span class="apidocSignatureSpan">feedparser.super_.super_.prototype.</span>uncork ()](#apidoc.element.feedparser.super_.super_.prototype.uncork)
1.  [function <span class="apidocSignatureSpan">feedparser.super_.super_.prototype.</span>write (chunk, encoding, cb)](#apidoc.element.feedparser.super_.super_.prototype.write)
1.  object <span class="apidocSignatureSpan">feedparser.super_.super_.prototype.</span>_writev

#### [module feedparser.super_.super_.super_.prototype](#apidoc.module.feedparser.super_.super_.super_.prototype)
1.  [function <span class="apidocSignatureSpan">feedparser.super_.super_.super_.prototype.</span>_read (n)](#apidoc.element.feedparser.super_.super_.super_.prototype._read)
1.  [function <span class="apidocSignatureSpan">feedparser.super_.super_.super_.prototype.</span>addListener (ev, fn)](#apidoc.element.feedparser.super_.super_.super_.prototype.addListener)
1.  [function <span class="apidocSignatureSpan">feedparser.super_.super_.super_.prototype.</span>isPaused ()](#apidoc.element.feedparser.super_.super_.super_.prototype.isPaused)
1.  [function <span class="apidocSignatureSpan">feedparser.super_.super_.super_.prototype.</span>on (ev, fn)](#apidoc.element.feedparser.super_.super_.super_.prototype.on)
1.  [function <span class="apidocSignatureSpan">feedparser.super_.super_.super_.prototype.</span>pause ()](#apidoc.element.feedparser.super_.super_.super_.prototype.pause)
1.  [function <span class="apidocSignatureSpan">feedparser.super_.super_.super_.prototype.</span>pipe (dest, pipeOpts)](#apidoc.element.feedparser.super_.super_.super_.prototype.pipe)
1.  [function <span class="apidocSignatureSpan">feedparser.super_.super_.super_.prototype.</span>push (chunk, encoding)](#apidoc.element.feedparser.super_.super_.super_.prototype.push)
1.  [function <span class="apidocSignatureSpan">feedparser.super_.super_.super_.prototype.</span>read (n)](#apidoc.element.feedparser.super_.super_.super_.prototype.read)
1.  [function <span class="apidocSignatureSpan">feedparser.super_.super_.super_.prototype.</span>resume ()](#apidoc.element.feedparser.super_.super_.super_.prototype.resume)
1.  [function <span class="apidocSignatureSpan">feedparser.super_.super_.super_.prototype.</span>setEncoding (enc)](#apidoc.element.feedparser.super_.super_.super_.prototype.setEncoding)
1.  [function <span class="apidocSignatureSpan">feedparser.super_.super_.super_.prototype.</span>unpipe (dest)](#apidoc.element.feedparser.super_.super_.super_.prototype.unpipe)
1.  [function <span class="apidocSignatureSpan">feedparser.super_.super_.super_.prototype.</span>unshift (chunk)](#apidoc.element.feedparser.super_.super_.super_.prototype.unshift)
1.  [function <span class="apidocSignatureSpan">feedparser.super_.super_.super_.prototype.</span>wrap (stream)](#apidoc.element.feedparser.super_.super_.super_.prototype.wrap)

#### [module feedparser.utils](#apidoc.module.feedparser.utils)
1.  [function <span class="apidocSignatureSpan">feedparser.utils.</span>assign ()](#apidoc.element.feedparser.utils.assign)
1.  [function <span class="apidocSignatureSpan">feedparser.utils.</span>get (obj, subkey, defaultValue)](#apidoc.element.feedparser.utils.get)
1.  [function <span class="apidocSignatureSpan">feedparser.utils.</span>has (object, path)](#apidoc.element.feedparser.utils.has)
1.  [function <span class="apidocSignatureSpan">feedparser.utils.</span>nslookup (uri, def)](#apidoc.element.feedparser.utils.nslookup)
1.  [function <span class="apidocSignatureSpan">feedparser.utils.</span>nsprefix (uri)](#apidoc.element.feedparser.utils.nsprefix)
1.  [function <span class="apidocSignatureSpan">feedparser.utils.</span>reresolve (node, baseurl)](#apidoc.element.feedparser.utils.reresolve)
1.  [function <span class="apidocSignatureSpan">feedparser.utils.</span>resolve (baseUrl, pathUrl)](#apidoc.element.feedparser.utils.resolve)
1.  [function <span class="apidocSignatureSpan">feedparser.utils.</span>safeTrim (val)](#apidoc.element.feedparser.utils.safeTrim)
1.  [function <span class="apidocSignatureSpan">feedparser.utils.</span>stripHtml (str)](#apidoc.element.feedparser.utils.stripHtml)
1.  [function <span class="apidocSignatureSpan">feedparser.utils.</span>uniq (array)](#apidoc.element.feedparser.utils.uniq)



# <a name="apidoc.module.feedparser"></a>[module feedparser](#apidoc.module.feedparser)

#### <a name="apidoc.element.feedparser.super_"></a>[function <span class="apidocSignatureSpan">feedparser.</span>super_ (options)](#apidoc.element.feedparser.super_)
- description and source-code
```javascript
function Transform(options) {
  if (!(this instanceof Transform)) return new Transform(options);

  Duplex.call(this, options);

  this._transformState = new TransformState(this);

  var stream = this;

  // start out asking for a readable event once data is transformed.
  this._readableState.needReadable = true;

  // we have implemented the _read method, and done the other things
  // that Readable wants before the first _read call, so unset the
  // sync guard flag.
  this._readableState.sync = false;

  if (options) {
    if (typeof options.transform === 'function') this._transform = options.transform;

    if (typeof options.flush === 'function') this._flush = options.flush;
  }

  // When the writable side finishes, then flush out anything remaining.
  this.once('prefinish', function () {
    if (typeof this._flush === 'function') this._flush(function (er, data) {
      done(stream, er, data);
    });else done(stream);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.feedparser.super_.super_"></a>[function <span class="apidocSignatureSpan">feedparser.</span>super_.super_ (options)](#apidoc.element.feedparser.super_.super_)
- description and source-code
```javascript
function Duplex(options) {
  if (!(this instanceof Duplex)) return new Duplex(options);

  Readable.call(this, options);
  Writable.call(this, options);

  if (options && options.readable === false) this.readable = false;

  if (options && options.writable === false) this.writable = false;

  this.allowHalfOpen = true;
  if (options && options.allowHalfOpen === false) this.allowHalfOpen = false;

  this.once('end', onend);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.feedparser.super_"></a>[module feedparser.super_](#apidoc.module.feedparser.super_)

#### <a name="apidoc.element.feedparser.super_.super_"></a>[function <span class="apidocSignatureSpan">feedparser.</span>super_ (options)](#apidoc.element.feedparser.super_.super_)
- description and source-code
```javascript
function Duplex(options) {
  if (!(this instanceof Duplex)) return new Duplex(options);

  Readable.call(this, options);
  Writable.call(this, options);

  if (options && options.readable === false) this.readable = false;

  if (options && options.writable === false) this.writable = false;

  this.allowHalfOpen = true;
  if (options && options.allowHalfOpen === false) this.allowHalfOpen = false;

  this.once('end', onend);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.feedparser.super_.prototype"></a>[module feedparser.super_.prototype](#apidoc.module.feedparser.super_.prototype)

#### <a name="apidoc.element.feedparser.super_.prototype._read"></a>[function <span class="apidocSignatureSpan">feedparser.super_.prototype.</span>_read (n)](#apidoc.element.feedparser.super_.prototype._read)
- description and source-code
```javascript
_read = function (n) {
  var ts = this._transformState;

  if (ts.writechunk !== null && ts.writecb && !ts.transforming) {
    ts.transforming = true;
    this._transform(ts.writechunk, ts.writeencoding, ts.afterTransform);
  } else {
    // mark that we need a transform, so that any data that comes in
    // will get processed, now that we've asked for it.
    ts.needTransform = true;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.feedparser.super_.prototype._transform"></a>[function <span class="apidocSignatureSpan">feedparser.super_.prototype.</span>_transform (chunk, encoding, cb)](#apidoc.element.feedparser.super_.prototype._transform)
- description and source-code
```javascript
_transform = function (chunk, encoding, cb) {
  throw new Error('_transform() is not implemented');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.feedparser.super_.prototype._write"></a>[function <span class="apidocSignatureSpan">feedparser.super_.prototype.</span>_write (chunk, encoding, cb)](#apidoc.element.feedparser.super_.prototype._write)
- description and source-code
```javascript
_write = function (chunk, encoding, cb) {
  var ts = this._transformState;
  ts.writecb = cb;
  ts.writechunk = chunk;
  ts.writeencoding = encoding;
  if (!ts.transforming) {
    var rs = this._readableState;
    if (ts.needTransform || rs.needReadable || rs.length < rs.highWaterMark) this._read(rs.highWaterMark);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.feedparser.super_.prototype.push"></a>[function <span class="apidocSignatureSpan">feedparser.super_.prototype.</span>push (chunk, encoding)](#apidoc.element.feedparser.super_.prototype.push)
- description and source-code
```javascript
push = function (chunk, encoding) {
  this._transformState.needTransform = false;
  return Duplex.prototype.push.call(this, chunk, encoding);
}
```
- example usage
```shell
...
        res.pipe(feed)
    }
});

var articles = [];
feed.on('data', function (item)
{
   articles.push(item); //my item handling
});
feed.on('error', function (error)
{
    console.log(error);
    callback(500, error);
})
feed.on('end', function ()
...
```



# <a name="apidoc.module.feedparser.super_.super_"></a>[module feedparser.super_.super_](#apidoc.module.feedparser.super_.super_)

#### <a name="apidoc.element.feedparser.super_.super_.super_"></a>[function <span class="apidocSignatureSpan">feedparser.super_.</span>super_ (options)](#apidoc.element.feedparser.super_.super_.super_)
- description and source-code
```javascript
function Readable(options) {
  Duplex = Duplex || require('./_stream_duplex');

  if (!(this instanceof Readable)) return new Readable(options);

  this._readableState = new ReadableState(options, this);

  // legacy
  this.readable = true;

  if (options && typeof options.read === 'function') this._read = options.read;

  Stream.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.feedparser.super_.super_.prototype"></a>[module feedparser.super_.super_.prototype](#apidoc.module.feedparser.super_.super_.prototype)

#### <a name="apidoc.element.feedparser.super_.super_.prototype._write"></a>[function <span class="apidocSignatureSpan">feedparser.super_.super_.prototype.</span>_write (chunk, encoding, cb)](#apidoc.element.feedparser.super_.super_.prototype._write)
- description and source-code
```javascript
_write = function (chunk, encoding, cb) {
  cb(new Error('_write() is not implemented'));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.feedparser.super_.super_.prototype.cork"></a>[function <span class="apidocSignatureSpan">feedparser.super_.super_.prototype.</span>cork ()](#apidoc.element.feedparser.super_.super_.prototype.cork)
- description and source-code
```javascript
cork = function () {
  var state = this._writableState;

  state.corked++;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.feedparser.super_.super_.prototype.end"></a>[function <span class="apidocSignatureSpan">feedparser.super_.super_.prototype.</span>end (chunk, encoding, cb)](#apidoc.element.feedparser.super_.super_.prototype.end)
- description and source-code
```javascript
end = function (chunk, encoding, cb) {
  var state = this._writableState;

  if (typeof chunk === 'function') {
    cb = chunk;
    chunk = null;
    encoding = null;
  } else if (typeof encoding === 'function') {
    cb = encoding;
    encoding = null;
  }

  if (chunk !== null && chunk !== undefined) this.write(chunk, encoding);

  // .end() fully uncorks
  if (state.corked) {
    state.corked = 1;
    this.uncork();
  }

  // ignore unnecessary end() calls.
  if (!state.ending && !state.finished) endWritable(this, state, cb);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.feedparser.super_.super_.prototype.setDefaultEncoding"></a>[function <span class="apidocSignatureSpan">feedparser.super_.super_.prototype.</span>setDefaultEncoding (encoding)](#apidoc.element.feedparser.super_.super_.prototype.setDefaultEncoding)
- description and source-code
```javascript
function setDefaultEncoding(encoding) {
  // node::ParseEncoding() requires lower case.
  if (typeof encoding === 'string') encoding = encoding.toLowerCase();
  if (!(['hex', 'utf8', 'utf-8', 'ascii', 'binary', 'base64', 'ucs2', 'ucs-2', 'utf16le', 'utf-16le', 'raw'].indexOf((encoding + '').
toLowerCase()) > -1)) throw new TypeError('Unknown encoding: ' + encoding);
  this._writableState.defaultEncoding = encoding;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.feedparser.super_.super_.prototype.uncork"></a>[function <span class="apidocSignatureSpan">feedparser.super_.super_.prototype.</span>uncork ()](#apidoc.element.feedparser.super_.super_.prototype.uncork)
- description and source-code
```javascript
uncork = function () {
  var state = this._writableState;

  if (state.corked) {
    state.corked--;

    if (!state.writing && !state.corked && !state.finished && !state.bufferProcessing && state.bufferedRequest) clearBuffer(this
, state);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.feedparser.super_.super_.prototype.write"></a>[function <span class="apidocSignatureSpan">feedparser.super_.super_.prototype.</span>write (chunk, encoding, cb)](#apidoc.element.feedparser.super_.super_.prototype.write)
- description and source-code
```javascript
write = function (chunk, encoding, cb) {
  var state = this._writableState;
  var ret = false;
  var isBuf = Buffer.isBuffer(chunk);

  if (typeof encoding === 'function') {
    cb = encoding;
    encoding = null;
  }

  if (isBuf) encoding = 'buffer';else if (!encoding) encoding = state.defaultEncoding;

  if (typeof cb !== 'function') cb = nop;

  if (state.ended) writeAfterEnd(this, cb);else if (isBuf || validChunk(this, state, chunk, cb)) {
    state.pendingcb++;
    ret = writeOrBuffer(this, state, isBuf, chunk, encoding, cb);
  }

  return ret;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.feedparser.super_.super_.super_.prototype"></a>[module feedparser.super_.super_.super_.prototype](#apidoc.module.feedparser.super_.super_.super_.prototype)

#### <a name="apidoc.element.feedparser.super_.super_.super_.prototype._read"></a>[function <span class="apidocSignatureSpan">feedparser.super_.super_.super_.prototype.</span>_read (n)](#apidoc.element.feedparser.super_.super_.super_.prototype._read)
- description and source-code
```javascript
_read = function (n) {
  this.emit('error', new Error('_read() is not implemented'));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.feedparser.super_.super_.super_.prototype.addListener"></a>[function <span class="apidocSignatureSpan">feedparser.super_.super_.super_.prototype.</span>addListener (ev, fn)](#apidoc.element.feedparser.super_.super_.super_.prototype.addListener)
- description and source-code
```javascript
addListener = function (ev, fn) {
  var res = Stream.prototype.on.call(this, ev, fn);

  if (ev === 'data') {
    // Start flowing on next tick if stream isn't explicitly paused
    if (this._readableState.flowing !== false) this.resume();
  } else if (ev === 'readable') {
    var state = this._readableState;
    if (!state.endEmitted && !state.readableListening) {
      state.readableListening = state.needReadable = true;
      state.emittedReadable = false;
      if (!state.reading) {
        processNextTick(nReadingNextTick, this);
      } else if (state.length) {
        emitReadable(this, state);
      }
    }
  }

  return res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.feedparser.super_.super_.super_.prototype.isPaused"></a>[function <span class="apidocSignatureSpan">feedparser.super_.super_.super_.prototype.</span>isPaused ()](#apidoc.element.feedparser.super_.super_.super_.prototype.isPaused)
- description and source-code
```javascript
isPaused = function () {
  return this._readableState.flowing === false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.feedparser.super_.super_.super_.prototype.on"></a>[function <span class="apidocSignatureSpan">feedparser.super_.super_.super_.prototype.</span>on (ev, fn)](#apidoc.element.feedparser.super_.super_.super_.prototype.on)
- description and source-code
```javascript
on = function (ev, fn) {
  var res = Stream.prototype.on.call(this, ev, fn);

  if (ev === 'data') {
    // Start flowing on next tick if stream isn't explicitly paused
    if (this._readableState.flowing !== false) this.resume();
  } else if (ev === 'readable') {
    var state = this._readableState;
    if (!state.endEmitted && !state.readableListening) {
      state.readableListening = state.needReadable = true;
      state.emittedReadable = false;
      if (!state.reading) {
        processNextTick(nReadingNextTick, this);
      } else if (state.length) {
        emitReadable(this, state);
      }
    }
  }

  return res;
}
```
- example usage
```shell
...

var FeedParser = require('feedparser');
var request = require('request'); // for fetching the feed

var req = request('http://somefeedurl.xml')
var feedparser = new FeedParser([options]);

req.on('error', function (error) {
// handle any request errors
});

req.on('response', function (res) {
var stream = this; // 'this' is 'req', which is a stream

if (res.statusCode !== 200) {
...
```

#### <a name="apidoc.element.feedparser.super_.super_.super_.prototype.pause"></a>[function <span class="apidocSignatureSpan">feedparser.super_.super_.super_.prototype.</span>pause ()](#apidoc.element.feedparser.super_.super_.super_.prototype.pause)
- description and source-code
```javascript
pause = function () {
  debug('call pause flowing=%j', this._readableState.flowing);
  if (false !== this._readableState.flowing) {
    debug('pause');
    this._readableState.flowing = false;
    this.emit('pause');
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.feedparser.super_.super_.super_.prototype.pipe"></a>[function <span class="apidocSignatureSpan">feedparser.super_.super_.super_.prototype.</span>pipe (dest, pipeOpts)](#apidoc.element.feedparser.super_.super_.super_.prototype.pipe)
- description and source-code
```javascript
pipe = function (dest, pipeOpts) {
  var src = this;
  var state = this._readableState;

  switch (state.pipesCount) {
    case 0:
      state.pipes = dest;
      break;
    case 1:
      state.pipes = [state.pipes, dest];
      break;
    default:
      state.pipes.push(dest);
      break;
  }
  state.pipesCount += 1;
  debug('pipe count=%d opts=%j', state.pipesCount, pipeOpts);

  var doEnd = (!pipeOpts || pipeOpts.end !== false) && dest !== process.stdout && dest !== process.stderr;

  var endFn = doEnd ? onend : cleanup;
  if (state.endEmitted) processNextTick(endFn);else src.once('end', endFn);

  dest.on('unpipe', onunpipe);
  function onunpipe(readable) {
    debug('onunpipe');
    if (readable === src) {
      cleanup();
    }
  }

  function onend() {
    debug('onend');
    dest.end();
  }

  // when the dest drains, it reduces the awaitDrain counter
  // on the source.  This would be more elegant with a .once()
  // handler in flow(), but adding and removing repeatedly is
  // too slow.
  var ondrain = pipeOnDrain(src);
  dest.on('drain', ondrain);

  var cleanedUp = false;
  function cleanup() {
    debug('cleanup');
    // cleanup event handlers once the pipe is broken
    dest.removeListener('close', onclose);
    dest.removeListener('finish', onfinish);
    dest.removeListener('drain', ondrain);
    dest.removeListener('error', onerror);
    dest.removeListener('unpipe', onunpipe);
    src.removeListener('end', onend);
    src.removeListener('end', cleanup);
    src.removeListener('data', ondata);

    cleanedUp = true;

    // if the reader is waiting for a drain event from this
    // specific writer, then it would cause it to never start
    // flowing again.
    // So, if this is awaiting a drain, then we just call it now.
    // If we don't know, then assume that we are waiting for one.
    if (state.awaitDrain && (!dest._writableState || dest._writableState.needDrain)) ondrain();
  }

  // If the user pushes more data while we're writing to dest then we'll end up
  // in ondata again. However, we only want to increase awaitDrain once because
  // dest will only emit one 'drain' event for the multiple writes.
  // => Introduce a guard on increasing awaitDrain.
  var increasedAwaitDrain = false;
  src.on('data', ondata);
  function ondata(chunk) {
    debug('ondata');
    increasedAwaitDrain = false;
    var ret = dest.write(chunk);
    if (false === ret && !increasedAwaitDrain) {
      // If the user unpiped during 'dest.write()', it is possible
      // to get stuck in a permanently paused state if that write
      // also returned false.
      // => Check whether 'dest' is still a piping destination.
      if ((state.pipesCount === 1 && state.pipes === dest || state.pipesCount > 1 && indexOf(state.pipes, dest) !== -1) && !cleanedUp
) {
        debug('false write response, pause', src._readableState.awaitDrain);
        src._readableState.awaitDrain++;
        increasedAwaitDrain = true;
      }
      src.pause();
    }
  }

  // if the dest has an error, then stop piping into it.
  // however, don't suppress the throwing behavior for this.
  function onerror(er) {
    debug('onerror', er);
    unpipe();
    dest.removeListener('error', onerror);
    if (EElistenerCount(dest, 'error') === 0) dest.emit('error', er);
  }

  // Make sure our error handler is attached before userland ones.
  prependListener(dest, 'error', onerror);

  // Both close and finish should trigger unpipe, but only once.
  function onclose() {
    dest.removeListener('finish', onfinish);
    unpipe();
  }
  dest.once('close', onclose);
  function onfinish() {
    debug('onfinish');
    dest.removeListener('close', onclose);
    unpipe();
  }
  dest.once('finish', onfinish);

  function unpipe() {
    debug('unpipe');
    src.unpipe(dest);
  }

  // tell the dest that it's being piped to
  dest.emit('pipe', src);

  // start the flow if it hasn't been started already.
  if (!state.flowing) {
    debug('pipe resume');
    src.resume();
  }

  return dest;
}
```
- example usage
```shell
...
req.on('response', function (res) {
  var stream = this; // 'this' is 'req', which is a stream

  if (res.statusCode !== 200) {
    this.emit('error', new Error('Bad status code'));
  }
  else {
    stream.pipe(feedparser);
  }
});

feedparser.on('error', function (error) {
  // always handle errors
});
...
```

#### <a name="apidoc.element.feedparser.super_.super_.super_.prototype.push"></a>[function <span class="apidocSignatureSpan">feedparser.super_.super_.super_.prototype.</span>push (chunk, encoding)](#apidoc.element.feedparser.super_.super_.super_.prototype.push)
- description and source-code
```javascript
push = function (chunk, encoding) {
  var state = this._readableState;

  if (!state.objectMode && typeof chunk === 'string') {
    encoding = encoding || state.defaultEncoding;
    if (encoding !== state.encoding) {
      chunk = bufferShim.from(chunk, encoding);
      encoding = '';
    }
  }

  return readableAddChunk(this, state, chunk, encoding, false);
}
```
- example usage
```shell
...
        res.pipe(feed)
    }
});

var articles = [];
feed.on('data', function (item)
{
   articles.push(item); //my item handling
});
feed.on('error', function (error)
{
    console.log(error);
    callback(500, error);
})
feed.on('end', function ()
...
```

#### <a name="apidoc.element.feedparser.super_.super_.super_.prototype.read"></a>[function <span class="apidocSignatureSpan">feedparser.super_.super_.super_.prototype.</span>read (n)](#apidoc.element.feedparser.super_.super_.super_.prototype.read)
- description and source-code
```javascript
read = function (n) {
  debug('read', n);
  n = parseInt(n, 10);
  var state = this._readableState;
  var nOrig = n;

  if (n !== 0) state.emittedReadable = false;

  // if we're doing read(0) to trigger a readable event, but we
  // already have a bunch of data in the buffer, then just trigger
  // the 'readable' event and move on.
  if (n === 0 && state.needReadable && (state.length >= state.highWaterMark || state.ended)) {
    debug('read: emitReadable', state.length, state.ended);
    if (state.length === 0 && state.ended) endReadable(this);else emitReadable(this);
    return null;
  }

  n = howMuchToRead(n, state);

  // if we've ended, and we're now clear, then finish it up.
  if (n === 0 && state.ended) {
    if (state.length === 0) endReadable(this);
    return null;
  }

  // All the actual chunk generation logic needs to be
  // *below* the call to _read.  The reason is that in certain
  // synthetic stream cases, such as passthrough streams, _read
  // may be a completely synchronous operation which may change
  // the state of the read buffer, providing enough data when
  // before there was *not* enough.
  //
  // So, the steps are:
  // 1. Figure out what the state of things will be after we do
  // a read from the buffer.
  //
  // 2. If that resulting state will trigger a _read, then call _read.
  // Note that this may be asynchronous, or synchronous.  Yes, it is
  // deeply ugly to write APIs this way, but that still doesn't mean
  // that the Readable class should behave improperly, as streams are
  // designed to be sync/async agnostic.
  // Take note if the _read call is sync or async (ie, if the read call
  // has returned yet), so that we know whether or not it's safe to emit
  // 'readable' etc.
  //
  // 3. Actually pull the requested chunks out of the buffer and return.

  // if we need a readable event, then we need to do some reading.
  var doRead = state.needReadable;
  debug('need readable', doRead);

  // if we currently have less than the highWaterMark, then also read some
  if (state.length === 0 || state.length - n < state.highWaterMark) {
    doRead = true;
    debug('length less than watermark', doRead);
  }

  // however, if we've ended, then there's no point, and if we're already
  // reading, then it's unnecessary.
  if (state.ended || state.reading) {
    doRead = false;
    debug('reading or ended', doRead);
  } else if (doRead) {
    debug('do read');
    state.reading = true;
    state.sync = true;
    // if the length is currently zero, then we *need* a readable event.
    if (state.length === 0) state.needReadable = true;
    // call internal read method
    this._read(state.highWaterMark);
    state.sync = false;
    // If _read pushed data synchronously, then 'reading' will be false,
    // and we need to re-evaluate how much data we can return to the user.
    if (!state.reading) n = howMuchToRead(nOrig, state);
  }

  var ret;
  if (n > 0) ret = fromList(n, state);else ret = null;

  if (ret === null) {
    state.needReadable = true;
    n = 0;
  } else {
    state.length -= n;
  }

  if (state.length === 0) {
    // If we have nothing in the buffer, then we want to know
    // as soon as we *do* get something into the buffer.
    if (!state.ended) state.needReadable = true;

    // If we tried to read() past the EOF, then emit end on the next tick.
    if (nOrig !== n && state.ended) endReadable(this);
  }

  if (ret !== null) this.emit('data', ret);

  return ret;
}
```
- example usage
```shell
...

feedparser.on('readable', function () {
  // This is where the action is!
  var stream = this; // 'this' is 'feedparser', which is a stream
  var meta = this.meta; // **NOTE** the "meta" is always available in the context of the feedparser instance
  var item;

  while (item = stream.read()) {
    console.log(item);
  }
});

'''

### options
...
```

#### <a name="apidoc.element.feedparser.super_.super_.super_.prototype.resume"></a>[function <span class="apidocSignatureSpan">feedparser.super_.super_.super_.prototype.</span>resume ()](#apidoc.element.feedparser.super_.super_.super_.prototype.resume)
- description and source-code
```javascript
resume = function () {
  var state = this._readableState;
  if (!state.flowing) {
    debug('resume');
    state.flowing = true;
    resume(this, state);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.feedparser.super_.super_.super_.prototype.setEncoding"></a>[function <span class="apidocSignatureSpan">feedparser.super_.super_.super_.prototype.</span>setEncoding (enc)](#apidoc.element.feedparser.super_.super_.super_.prototype.setEncoding)
- description and source-code
```javascript
setEncoding = function (enc) {
  if (!StringDecoder) StringDecoder = require('string_decoder/').StringDecoder;
  this._readableState.decoder = new StringDecoder(enc);
  this._readableState.encoding = enc;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.feedparser.super_.super_.super_.prototype.unpipe"></a>[function <span class="apidocSignatureSpan">feedparser.super_.super_.super_.prototype.</span>unpipe (dest)](#apidoc.element.feedparser.super_.super_.super_.prototype.unpipe)
- description and source-code
```javascript
unpipe = function (dest) {
  var state = this._readableState;

  // if we're not piping anywhere, then do nothing.
  if (state.pipesCount === 0) return this;

  // just one destination.  most common case.
  if (state.pipesCount === 1) {
    // passed in one, but it's not the right one.
    if (dest && dest !== state.pipes) return this;

    if (!dest) dest = state.pipes;

    // got a match.
    state.pipes = null;
    state.pipesCount = 0;
    state.flowing = false;
    if (dest) dest.emit('unpipe', this);
    return this;
  }

  // slow case. multiple pipe destinations.

  if (!dest) {
    // remove all.
    var dests = state.pipes;
    var len = state.pipesCount;
    state.pipes = null;
    state.pipesCount = 0;
    state.flowing = false;

    for (var i = 0; i < len; i++) {
      dests[i].emit('unpipe', this);
    }return this;
  }

  // try to find the right one.
  var index = indexOf(state.pipes, dest);
  if (index === -1) return this;

  state.pipes.splice(index, 1);
  state.pipesCount -= 1;
  if (state.pipesCount === 1) state.pipes = state.pipes[0];

  dest.emit('unpipe', this);

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.feedparser.super_.super_.super_.prototype.unshift"></a>[function <span class="apidocSignatureSpan">feedparser.super_.super_.super_.prototype.</span>unshift (chunk)](#apidoc.element.feedparser.super_.super_.super_.prototype.unshift)
- description and source-code
```javascript
unshift = function (chunk) {
  var state = this._readableState;
  return readableAddChunk(this, state, chunk, '', true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.feedparser.super_.super_.super_.prototype.wrap"></a>[function <span class="apidocSignatureSpan">feedparser.super_.super_.super_.prototype.</span>wrap (stream)](#apidoc.element.feedparser.super_.super_.super_.prototype.wrap)
- description and source-code
```javascript
wrap = function (stream) {
  var state = this._readableState;
  var paused = false;

  var self = this;
  stream.on('end', function () {
    debug('wrapped end');
    if (state.decoder && !state.ended) {
      var chunk = state.decoder.end();
      if (chunk && chunk.length) self.push(chunk);
    }

    self.push(null);
  });

  stream.on('data', function (chunk) {
    debug('wrapped data');
    if (state.decoder) chunk = state.decoder.write(chunk);

    // don't skip over falsy values in objectMode
    if (state.objectMode && (chunk === null || chunk === undefined)) return;else if (!state.objectMode && (!chunk || !chunk.length
)) return;

    var ret = self.push(chunk);
    if (!ret) {
      paused = true;
      stream.pause();
    }
  });

  // proxy all the other methods.
  // important when wrapping filters and duplexes.
  for (var i in stream) {
    if (this[i] === undefined && typeof stream[i] === 'function') {
      this[i] = function (method) {
        return function () {
          return stream[method].apply(stream, arguments);
        };
      }(i);
    }
  }

  // proxy certain important events.
  var events = ['error', 'close', 'destroy', 'pause', 'resume'];
  forEach(events, function (ev) {
    stream.on(ev, self.emit.bind(self, ev));
  });

  // when we try to consume some more bytes, simply unpause the
  // underlying stream.
  self._read = function (n) {
    debug('wrapped _read', n);
    if (paused) {
      paused = false;
      stream.resume();
    }
  };

  return self;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.feedparser.utils"></a>[module feedparser.utils](#apidoc.module.feedparser.utils)

#### <a name="apidoc.element.feedparser.utils.assign"></a>[function <span class="apidocSignatureSpan">feedparser.utils.</span>assign ()](#apidoc.element.feedparser.utils.assign)
- description and source-code
```javascript
assign = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      array = Array(length);

  while (++index < length) {
    array[index] = args[start + index];
  }
  index = -1;
  var otherArgs = Array(start + 1);
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = array;
  return apply(func, this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.feedparser.utils.get"></a>[function <span class="apidocSignatureSpan">feedparser.utils.</span>get (obj, subkey, defaultValue)](#apidoc.element.feedparser.utils.get)
- description and source-code
```javascript
function get(obj, subkey, defaultValue) {
  if (!subkey) {
    subkey = '#';
  }

  if (!defaultValue) {
    defaultValue = null;
  }

  if (Array.isArray(obj)) {
    return _get(obj[0], subkey, defaultValue);
  }
  else {
    return _get(obj, subkey, defaultValue);
  }
}
```
- example usage
```shell
...

var url = "https://www.raspberrypi.org/feed/";
var callback = console.log;
var feed = new rss({ resume_saxerror: false });

var request;
if (urlUtil.parse(url).protocol == 'https:')
    request = https.get(url);
else
    request = http.get(url);

request.on('response', function (res)
{
    var encoding = res.headers['content-encoding']
    console.log(encoding);
...
```

#### <a name="apidoc.element.feedparser.utils.has"></a>[function <span class="apidocSignatureSpan">feedparser.utils.</span>has (object, path)](#apidoc.element.feedparser.utils.has)
- description and source-code
```javascript
function has(object, path) {
  return object != null && hasPath(object, path, baseHas);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.feedparser.utils.nslookup"></a>[function <span class="apidocSignatureSpan">feedparser.utils.</span>nslookup (uri, def)](#apidoc.element.feedparser.utils.nslookup)
- description and source-code
```javascript
function nslookup(uri, def) {
  return namespaces[uri] === def;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.feedparser.utils.nsprefix"></a>[function <span class="apidocSignatureSpan">feedparser.utils.</span>nsprefix (uri)](#apidoc.element.feedparser.utils.nsprefix)
- description and source-code
```javascript
function nsprefix(uri) {
  return namespaces[uri];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.feedparser.utils.reresolve"></a>[function <span class="apidocSignatureSpan">feedparser.utils.</span>reresolve (node, baseurl)](#apidoc.element.feedparser.utils.reresolve)
- description and source-code
```javascript
function reresolve(node, baseurl) {
  if (!node || !baseurl) {
    return false; // Nothing to do.
  }

  function resolveLevel (level) {
    var els = Object.keys(level);
    els.forEach(function(el){
      if (Array.isArray(level[el])) {
        level[el].forEach(resolveLevel);
      } else {
        if (level[el].constructor.name === 'Object') {
          if (el == 'logo' || el == 'icon') {
            if ('#' in level[el]) {
              level[el]['#'] = URL.resolve(baseurl, level[el]['#']);
            }
          } else {
            var attrs = Object.keys(level[el]);
            attrs.forEach(function(name){
              if (name == 'href' || name == 'src' || name == 'uri') {
                if ('string' === typeof level[el][name]) {
                  level[el][name] = URL.resolve(baseurl, level[el][name]);
                }
                else if ('#' in level[el][name]) {
                  level[el][name]['#'] = URL.resolve(baseurl, level[el][name]['#']);
                }
              }
            });
          }
        }
      }
    });
    return level;
  }

  return resolveLevel(node);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.feedparser.utils.resolve"></a>[function <span class="apidocSignatureSpan">feedparser.utils.</span>resolve (baseUrl, pathUrl)](#apidoc.element.feedparser.utils.resolve)
- description and source-code
```javascript
function resolve(baseUrl, pathUrl) {
  return URL.resolve(baseUrl, pathUrl);
}
```
- example usage
```shell
...
exports.safeTrim = safeTrim;

/*
* Expose require('url').resolve
* @private
*/
function resolve (baseUrl, pathUrl) {
 return URL.resolve(baseUrl, pathUrl);
}
exports.resolve = resolve;

/*
* Check whether a given namespace URI matches the given default
*
* @param {String} URI
...
```

#### <a name="apidoc.element.feedparser.utils.safeTrim"></a>[function <span class="apidocSignatureSpan">feedparser.utils.</span>safeTrim (val)](#apidoc.element.feedparser.utils.safeTrim)
- description and source-code
```javascript
function safeTrim(val) {
  if (typeof val === 'string') {
    return val.trim();
  }
  return val;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.feedparser.utils.stripHtml"></a>[function <span class="apidocSignatureSpan">feedparser.utils.</span>stripHtml (str)](#apidoc.element.feedparser.utils.stripHtml)
- description and source-code
```javascript
function stripHtml(str) {
  return str.replace(/<.*?>/g, '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.feedparser.utils.uniq"></a>[function <span class="apidocSignatureSpan">feedparser.utils.</span>uniq (array)](#apidoc.element.feedparser.utils.uniq)
- description and source-code
```javascript
function uniq(array) {
  return (array && array.length)
    ? baseUniq(array)
    : [];
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
