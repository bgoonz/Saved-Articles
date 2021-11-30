# Web-scraping Web Services

## Web-data Extracting Services

  * [Dataflow kit](https://dataflowkit.com) - Turn websites data into structured data with a simple point-and-click toolkit
  * [ProxyCrawl](https://proxycrawl.com) - Crawl and scrape any website without blocks, captchas or proxies
  * [ScraperAPI](https://www.scraperapi.com) - A service that manages proxies
    and headless browsers, exposing a single API endpoint to scrape any url.
  * [import.io](https://import.io/)
  * [ScraperWiki](https://scraperwiki.com/about)
  * [Mozenda](https://www.mozenda.com/)
  * [PhantomJs.Cloud](https://phantomjscloud.com/)
  * [CloudScrape](http://cloudscrape.com/)
  * [DiffBot](http://www.diffbot.com/)
  * [Apify](https://www.apify.com/) - A serverless web scraping, data extraction and web automation platform
  * [Portia](http://scrapinghub.com/portia/); also on GitHub: [scrapinghub/portia](https://github.com/scrapinghub/portia)
  * [Dexi](https://dexi.io)
  * [Morph.io](https://morph.io) free of charge, fully [open-source](https://github.com/openaustralia/morph) service
  * [Page.REST](https://page.rest/)
  * [ParseHub](https://www.parsehub.com/)
  * [WrapAPI](https://wrapapi.com/)
  * [Agenty](https://www.agenty.com/)
  * [ScrapingBee](https://www.scrapingbee.com/) - A web scraping API that handles rotating proxies and headless browsers.
  * [SerpApi](https://serpapi.com/) - Real-time API to access structured search results of search engines.
  * [ScrapingAnt](https://scrapingant.com/) - Web Scraping API with thousands of residential proxies and headless Chrome cluster.
  * [Zyte (formerly Scrapinghub)](https://www.zyte.com/) - Web data extraction services and platform, also lead maintainers of Scrapy.
  * [ProxiesAPI](https://proxiesapi.com/) - Rotating proxies API with automatic retries, CAPTCHA handling and javacript rendering.
  * [ZenRows](https://www.zenrows.com/) - Web Scraping API & proxy server that bypasses any anti-bot solution while offering javascript rendering, rotating proxies, and geotargeting.




* [JavaScript Web Scraping](#javascript-web-scraping)
   * [Network](#network)
   * [Web-scraping Frameworks](#web-scraping-frameworks)
   * [HTML/XML Parsing](#htmlxml-parsing)
   * [Text processing](#text-processing)
   * [Specific Formats Processing](#specific-formats-processing)
   * [Natural Language Processing](#natural-language-processing)
   * [Browser automation and emulation](#browser-automation-and-emulation)
   * [Multiprocessing](#multiprocessing)
   * [Queue](#queue)
   * [Email](#email)
   * [URL and Network Address Manipulation](#url-and-network-address-manipulation)
   * [Web Content Extracting](#web-content-extracting)
   * [Asynchronous](#asynchronous)
   * [WebSocket](#websocket)
   * [DNS Resolving](#dns-resolving)
   * [Computer Vision](#computer-vision)
   * [Proxy Server](#proxy-server)
   * [Other JavaScript Lists](#other-javascript-lists)
   * [Data Structure](#data-structure)

## Network
* [request](https://github.com/request/request) - Simplified HTTP request client.
* [socks5-http-client](https://github.com/mattcg/socks5-http-client) - SOCKS v5 HTTP client implementation in JavaScript for Node.js
* [rest](https://github.com/cujojs/rest) - RESTful HTTP client for JavaScript
* [wreck](https://github.com/hapijs/wreck) - HTTP Client Utilities
* [got](https://github.com/sindresorhus/got) - Simplified HTTP requests
* [node-fetch](https://github.com/bitinn/node-fetch) - A light-weight module that brings window.fetch to Node.js
* [bent](https://github.com/mikeal/bent) - Functional HTTP client for Node.js w/ async/await
* [axios](https://github.com/axios/axios) - Promise based HTTP client for the browser and node.js
* [superagent](https://github.com/visionmedia/superagent) - Ajax for Node.js and browsers (JS HTTP client)
* [urllib](https://github.com/node-modules/urllib) - Request HTTP(s) URLs in a complex world
* [needle](https://github.com/tomas/needle) - Nimble, streamable HTTP client for Node.js. With proxy, iconv, cookie, deflate & multipart support

## Web-Scraping Frameworks
* [webparsy](https://github.com/joseconstela/webparsy) - NodeJS lib and cli for scraping websites using Puppeteer and YAML
* [node-crawler](https://github.com/sylvinus/node-crawler) - Web Crawler/Spider for NodeJS + server-side jQuery
* [node-simplecrawler](https://github.com/cgiffard/node-simplecrawler) - Flexible event driven crawler for node
* [Apify SDK](https://github.com/apifytech/apify-js) - The scalable web crawling and scraping library for JavaScript. Enables development of data extraction and web automation jobs (not only) with headless Chrome and Puppeteer.
* [Ayakashi](https://github.com/ayakashi-io/ayakashi) - The next generation web scraping framework. Features all the necessary tools to create reliable and maintainable scraping and automation systems.
* [pjscrape](https://github.com/nrabinowitz/pjscrape) - A web-scraping framework written in Javascript, using PhantomJS and jQuery

## HTML/XML Parsing
* General
  * [parse5](https://github.com/inikulin/parse5) - WHATWG HTML5 specification-compliant, fast and ready for production HTML parsing/serialization toolset for Node and io.js
  * [htmlparser2](https://github.com/fb55/htmlparser2) - forgiving html and xml parser
  * [sax-js](https://github.com/isaacs/sax-js) - A sax style parser for JS
  * [cheerio](https://github.com/cheeriojs/cheerio) - Fast, flexible, and lean implementation of core jQuery designed specifically for the server
* Sanitizing
  * [js-xss](https://github.com/leizongmin/js-xss) - Sanitize untrusted HTML (to prevent XSS) with a configuration specified by a Whitelist.
  * [surgeon](https://github.com/gajus/surgeon) - Declarative DOM extraction expression evaluator

## Text Processing

*Libraries for parsing and manipulating plain texts.*

* General
  * [string.js](https://github.com/jprichardson/string.js) - Extra JavaScript string methods.
  * [accounting.js](https://github.com/openexchangerates/accounting.js) - A lightweight JavaScript library for number, money and currency formatting - fully localisable, zero dependencies.
  * [validator.js](https://github.com/chriso/validator.js) - String validation and sanitization.
* Date and time
  * [moment](https://github.com/moment/moment) - Parse, validate, manipulate, and display dates in javascript.
    * [moment-timezone](https://github.com/moment/moment-timezone) - Timezone support for moment.js.
  * [date](https://github.com/MatthewMueller/date) - Date() for humans.
  * [ms.js](https://github.com/guille/ms.js) - Tiny millisecond conversion utility.
* HTML entities
  * [he](https://github.com/mathiasbynens/he) - A robust HTML entity encoder/decoder written in JavaScript.
* Money
  * [money.js](https://github.com/openexchangerates/money.js) - Simple and tiny JavaScript library for realtime currency conversion and exchange rate calculation, from any currency, to any currency.
* Color
  * [chroma.js](https://github.com/gka/chroma.js) - JavaScript library for all kinds of color manipulations.
  * [color](https://github.com/harthur/color) - JavaScript color conversion and manipulation library.
  * [TinyColor](https://github.com/bgrins/TinyColor) - Fast, small color manipulation and conversion for JavaScript.
* User Agent
  * [UAParser.js](https://github.com/faisalman/ua-parser-js) - Lightweight JavaScript-based User-Agent string parser. Supports browser & node.js environment. 
* Semantic Version
  * [node-semver](https://github.com/npm/node-semver) - The semver parser for node

## Specific Formats Processing

*Libraries for parsing and manipulating specific text formats.*

* General
  * [jBinary](https://github.com/jDataView/jBinary) - High-level I/O (loading, parsing, manipulating, serializing, saving) for binary files with declarative syntax for describing file types and data structures.
* Office
  * [js-xlsx](https://github.com/SheetJS/js-xlsx) - XLSX / XLSM / XLSB / XLS / SpreadsheetML (Excel Spreadsheet) / ODS parser and writer
* CSV
  * [BabyParse](https://github.com/Rich-Harris/BabyParse) - Fast and reliable CSV parser based on Papa Parse. Papa Parse is for the browser, Baby Parse is for Node.js.
  * [CSV](https://github.com/knrz/CSV.js) - A simple, blazing-fast CSV parser and encoder. Full RFC 4180 compliance.
* JSON
  * [json3](https://github.com/bestiejs/json3) - A modern JSON implementation compatible with nearly all JavaScript platforms.
* EXIF
  * [exif-js](https://github.com/exif-js/exif-js) - JavaScript library for reading EXIF image metadata
* CSS
  * [parse-css](https://github.com/tabatkins/parse-css) - Standards-based CSS Parser
  * [parser-lib CSS parser](https://github.com/CSSLint/parser-lib) - The ParserLib CSS parser is a CSS3 SAX-inspired parser written in JavaScript. By default, the parser only deals with standard CSS syntax and doesn't do validation (checking of property names and values).
* Torrent
  * [parse-torrent](https://github.com/feross/parse-torrent) - Parse a torrent identifier (magnet uri, .torrent file, info hash)
* SQL
  * [SQL Parser](https://github.com/forward/sql-parser) - SQL Parser is a lexer, grammar and parser for SQL written in JS. Currently it is only capable of parsing fairly basic SELECT queries.
* YAML
  * [JS-YAML](https://github.com/nodeca/js-yaml) - JavaScript YAML parser and dumper. Very fast.
* Markdown
  * [markdown-it](https://github.com/markdown-it/markdown-it) - Markdown parser, done right. 100% CommonMark support, extensions, syntax plugins & high speed
* Atom/RSS
  * [node-feedparser](https://github.com/danmactough/node-feedparser) - Robust RSS, Atom, and RDF feed parsing in Node.js
* Netscape Bookmarks(Firefox, Google Chrome, ...)
  * [node-bookmarks-parser](https://github.com/calibr/node-bookmarks-parser) - Parses Firefox/Chrome HTML bookmarks files

## Natural Language Processing

*Libraries for working with human languages.*

* General
  * [natural](https://github.com/NaturalNode/natural) - general natural language facilities for node
  * [nlp_compromise](https://github.com/spencermountain/nlp_compromise) - natural language processing
  * [Hanzi](https://github.com/nieldlr/Hanzi) - HanziJS is a Chinese character and NLP module for Chinese language processing for Node.js
  * [salient](https://github.com/nyxtom/salient) - Machine Learning, Natural Language Processing and Sentiment Analysis Toolkit for Node.js
  * [node-summary](https://github.com/jbrooksuk/node-summary) - Node module that summarizes text using a naive summarization algorithm
* Stemmer
  * [snowball-js](https://github.com/fortnightlabs/snowball-js) - javascript implementation of the popular snowball word stemming nlp algorithm
  * [porter-stemmer](https://github.com/jedp/porter-stemmer) - Martin Porter's stemmer for node.js
  * [Porter-Stemmer](https://github.com/kristopolous/Porter-Stemmer) - A Javascript Implementation of the Porter Stemmer
  * [lunr-languages](https://github.com/MihaiValentin/lunr-languages) - a collection of languages stemmers and stopwords for Lunr Javascript library
* Language detection
  * [franc](https://github.com/wooorm/franc) - Natural language detection
  * [guessLanguage.js](https://github.com/richtr/guessLanguage.js) - A natural language detection library based on trigram statistical analysis for Node.js

## Browser automation and emulation
* [phantomjs](https://github.com/ariya/phantomjs) - Scriptable Headless WebKit.
* [slimerjs](https://github.com/laurentj/slimerjs) - A PhantomJS-like tool running Gecko.
* [casperjs](https://github.com/n1k0/casperjs) - Navigation scripting & testing utility for PhantomJS and SlimerJS.
* [zombie](https://github.com/assaf/zombie) - Insanely fast, full-stack, headless browser testing using node.js.
* [nightmare](https://github.com/segmentio/nightmare) - Nightmare is a high level wrapper for PhantomJS that lets you automate browser tasks
* [puppeteer](https://github.com/GoogleChrome/puppeteer) - Puppeteer is a Node library which provides a high-level API to control headless Chrome or Chromium over the DevTools Protocol. It can also be configured to use full (non-headless) Chrome or Chromium.
* [headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) - Distributed crawler powered by Headless Chrome
* [puppeteer-recorder](https://github.com/checkly/puppeteer-recorder) - Puppeteer recorder is a Chrome extension that records your browser interactions and generates a Puppeteer script.
* [wendigo](https://github.com/angrykoala/wendigo) - Test-oriented headless browser, built on top of Puppeteer.
* [Playwright](https://github.com/microsoft/playwright) - Node.js library to automate Chromium, Firefox and WebKit with a single API

## Multiprocessing
  * [nexpect](https://github.com/nodejitsu/nexpect) - spawn and control child processes in node.js with ease
  * [respawn](https://github.com/mafintosh/respawn) - Spawn a process and restart it if it crashes
  * [node-webworker](https://github.com/pgriess/node-webworker) - A WebWorkers implementation for NodeJS

## Asynchronous

*Libraries for asynchronous networking programming.*

  * [socket.io](https://github.com/socketio/socket.io) - Realtime application framework (Node.JS server)
  * [engine.io](https://github.com/socketio/engine.io) - Engine.IO is the implementation of transport-based cross-browser/cross-device bi-directional communication layer for Socket.IO
  * [async](https://github.com/caolan/async) - Async utilities for node and the browser

## Queue
  * [kue](https://github.com/Automattic/kue) - Kue is a priority job queue backed by redis, built for node.js
  * [bull](https://github.com/OptimalBits/bull) - A lightweight, robust and fast job processing queue. Carefully written for rock solid stability and atomicity.

## Email

*Libraries for parsing email.*

  * [mailparser](https://github.com/andris9/mailparser) - Decode mime formatted e-mails

## URL and Network Address Manipulation

*Libraries for parsing/modifying URLs and network addresses.*

* URL
  * [query-string](https://github.com/sindresorhus/query-string) - Parse and stringify URL query strings.
  * [URI.js](https://github.com/medialize/URI.js/) - Javascript URL mutation library.
  * [jsurl](https://github.com/Mikhus/jsurl) - Lightweight URL manipulation with JavaScript.
  * [arg.js](https://github.com/stretchr/arg.js) - Lightweight URL argument and parameter parser
* Network Address
  * [node-ip](https://github.com/indutny/node-ip) - IP address tools for node.js
  * [ip-address](https://github.com/beaugunderson/ip-address) - A library for parsing and manipulating IPv6 (and v4) addresses in JavaScript

## Web Content Extracting

*Libraries for extracting web contents.*

* [node-read](https://github.com/bndr/node-read) - Get Readable Content from any page. Based on Arc90's readability project using cheerio engine.
* [node-ytdl-core](https://github.com/fent/node-ytdl-core) - Youtube video downloader in javascript
* [ImageResolver](https://github.com/mauricesvay/ImageResolver) - Does its best to determine the main image on a URL without loading all images.

## WebSocket

*Libraries for working with WebSocket.*

  * [websocket.io](https://github.com/LearnBoost/websocket.io) - WebSocket.IO is an abstraction of the websocket server previously used by Socket.IO. It has the broadest support for websocket protocol/specifications and an API that allows for interoperability with higher-level frameworks such as Engine, Socket.IO's realtime core.
  * [WebScoket-Node](https://github.com/theturtle32/WebSocket-Node) - A WebSocket Implementation for Node.JS (Draft -08 through the final RFC 6455)

## DNS Resolving
  * [multicast-dns](https://github.com/mafintosh/multicast-dns) - Low level multicast-dns implementation in pure javascript
  * [node-dns](https://github.com/tjfontaine/node-dns) - Replacement dns module in pure javascript for node.js

## Computer Vision
* [tracking.js](https://github.com/eduardolundgren/tracking.js) - A modern approach for Computer Vision on the web.
* [ocrad.js](https://github.com/antimatter15/ocrad.js) - OCR in Javascript via Emscripten.

## Proxy Server
  * [toxy](https://github.com/h2non/toxy) - Hackable HTTP proxy to simulate server failure scenarios and unexpected network conditions
  * [proxy-chain](https://github.com/apifytech/proxy-chain) - Node.js implementation of a proxy server (think Squid) with support for SSL, authentication and upstream proxy chaining

## Data Structure
* [immutable](https://github.com/facebook/immutable-js) - Immutable persistent data collections for Javascript which increase efficiency and simplicity.
* [lodash](https://github.com/lodash/lodash) - More consistent cross-environment iteration support for arrays, strings, objects, and arguments objects


# Python Web Scraping

This list contains python libraries related to web scraping and data processing

## Contents

* [Network](#network)
* [Web Scraping](#web-scraping)
* [HTML/XML](#htmlxml)
* [Text processing](#text-processing)
* [Structured Formats](#structured-formats)
* [Serialization](#serialization)
* [Natural Language Processing](#natural-language-processing)
* [Browser automation](#browser-automation)
* [Multiprocessing](#multiprocessing)
* [Job Queue](#job-queue)
* [Message Queue](#message-queue)
* [Cloud Computing](#cloud-computing)
* [Email](#email)
* [URL and Network Address](#url-and-network-address)
* [Web Content Extraction](#web-content-extraction)
* [Asynchronous](#asynchronous)
* [WebSocket](#websocket)
* [DNS Resolving](#dns-resolving)
* [Computer Vision](#computer-vision)
* [Proxy Server](#proxy-server)
* [Whois](#whois)
* [Website Specific Scraper](#site-specific-scraper)
* [JavaScript Engine Bindings](#javascript-engine-bindings)
* [Other Python Lists](#other-python-lists)

## Network

### Network : General

* [urllib](https://docs.python.org/3.4/library/urllib.html?highlight=urllib#module-urllib) - network library (stdlib)
* [requests](https://github.com/kennethreitz/requests) - network library
* [grab](https://github.com/lorien/grab) - network library (pycurl based)
* [pycurl](https://github.com/pycurl/pycurl) - network library (binding to [libcurl](http://curl.haxx.se/libcurl/))
* [urllib3](https://github.com/shazow/urllib3) - Python HTTP library with thread-safe connection pooling, file post support, sanity friendly, and more.
* [httplib2](https://github.com/httplib2/httplib2) - Small, fast HTTP client library. Features persistent connections, cache, and Google App Engine support.
* [RoboBrowser](https://github.com/jmcarp/robobrowser) - A simple, Pythonic library for browsing the web without a standalone web browser.
* [MechanicalSoup](https://github.com/hickford/MechanicalSoup) - A Python library for automating interaction with websites.
* [mechanize](https://github.com/python-mechanize/mechanize) - Stateful programmatic web browsing.
* [socket](https://docs.python.org/3/library/socket.html) low-level networking interface (stdlib)
* [Unirest for Python](https://github.com/Mashape/unirest-python) - Unirest is a set of lightweight HTTP libraries available in multiple languages
* [hyper](https://github.com/Lukasa/hyper) - HTTP/2 Client for Python
* [PySocks](https://github.com/Anorov/PySocks) - Updated and actively maintained version of SocksiPy, with bug fixes and extra features. Acts as a drop-in replacement to the socket module.

### Network : Asynchronous

* [treq](https://github.com/dreid/treq) - requests like API (twisted based)
* [aiohttp](https://github.com/KeepSafe/aiohttp) - http client/server for asyncio (PEP-3156)

### Network : Low Level

* [dpkt](https://github.com/kbandla/dpkt) - fast, simple packet creation / parsing, with definitions for the basic TCP/IP protocols
* [pyOpenSSL](https://github.com/pyca/pyopenssl) - A Python wrapper around the OpenSSL library
* [tlslite-ng](https://github.com/tomato42/tlslite-ng) - TLS implementation in pure python
* [scapy](https://github.com/secdev/scapy) - powerful Python-based interactive packet manipulation program and library
* [impacket](https://github.com/SecureAuthCorp/impacket/) - low-level programmatic access to the packets of network protocols

## Web Scraping

### Web Scraping : Frameworks

* [grab](https://grablab.org/docs/) - web-scraping framework (pycurl/multicurl based)
* [scrapy](http://scrapy.org/) - web-scraping framework (twisted based).
* [pyspider](https://github.com/binux/pyspider) - A powerful spider system.
* [cola](https://github.com/chineking/cola) - A distributed crawling framework.
* [ruia](https://github.com/howie6879/ruia) - Async Python 3.6+ web scraping micro-framework based on asyncio
* [ioweb](https://github.com/lorien/ioweb) - Web scraping framework based on gevent and lxml
* [autoscraper](https://github.com/alirezamika/autoscraper) - A smart, automatic and lightweight web scraper
* [frontera](https://github.com/scrapinghub/frontera) - A scalable frontier for web crawlers


### Web Scraping : Tools

* [portia](https://github.com/scrapinghub/portia) - Visual scraping for Scrapy.
* [restkit](https://github.com/benoitc/restkit) - HTTP resource kit for Python. It allows you to easily access to HTTP resource and build objects around it.
* [requests-html](https://github.com/kennethreitz/requests-html) - Pythonic HTML Parsing for Humans.
* [ScrapydWeb](https://github.com/my8100/scrapydweb) - A full-featured web UI for Scrapyd cluster management, which supports Scrapy Log Analysis & Visualization, Auto Packaging, Timer Tasks, Email Notice and so on.
* [Starbelly](https://github.com/HyperionGray/starbelly) - Starbelly is a user-friendly and highly configurable web crawler front end.
* [Gerapy](https://github.com/Gerapy/Gerapy) - Distributed Crawler Management Framework Based on Scrapy, Scrapyd, Django and Vue.js

### Web Scraping : Bypass Protection

* [cloudscraper](https://github.com/venomous/cloudscraper) - A Python module to bypass Cloudflare's anti-bot page.

## HTML/XML

### HTML/XML : General

* [lxml](https://github.com/lxml/lxml/) - effective HTML/XML processing library. Supports XPATH. Written in C.
* [cssselect](https://github.com/scrapy/cssselect) - working with DOM tree with CSS selectors
* [pyquery](https://github.com/gawel/pyquery) - working with DOM tree with jQuery-like selectors
* [BeautifulSoup](http://www.crummy.com/software/BeautifulSoup/bs4/doc/) - slow HTML/XMl processing library, written in pure python
* [html5lib](https://github.com/html5lib/html5lib-python) - builds DOM of HTML/XML document according to [WHATWG spec](url=http://www.whatwg.org/). That spec is used in all modern browsers.
* [feedparser](https://github.com/kurtmckee/feedparser) - parsing of RSS/ATOM feeds.
* [MarkupSafe](https://github.com/mitsuhiko/markupsafe) - Implements a XML/HTML/XHTML Markup safe string for Python.
* [xmltodict](https://github.com/martinblech/xmltodict) - Working with XML feel like you are working with JSON.
* [xhtml2pdf](https://github.com/chrisglass/xhtml2pdf) - HTML/CSS to PDF converter.
* [untangle](https://github.com/stchris/untangle) - Converts XML documents to Python objects for easy access.
* [hodor](https://github.com/CompileInc/hodor) - Configuration driven wrapper around lxml and cssselect.
* [chopper](https://github.com/jurismarches/chopper) - Tool to extract a part from HTML page with corresponding CSS rules and preserving correct HTML.
* [selectolax](https://github.com/rushter/selectolax) - Python bindings to Modest engine (fast HTML5 parser with CSS selectors).
* [parsel](https://github.com/scrapy/parsel) - Lets you extract data from XML/HTML documents using XPath or CSS selectors.
* [html5-parser](https://github.com/kovidgoyal/html5-parser) - Fast C based HTML 5 parsing for python.
* [gazpacho](https://github.com/maxhumber/gazpacho/) - A simple, fast, and modern web scraping library. 

### HTML/XML : Sanitizing

* [Bleach](https://github.com/mozilla/bleach) - cleaning of HTML (requires html5lib)
* [sanitize](https://github.com/Alir3z4/sanitize) - Bringing sanity to world of messed-up data.

### HTML/XML : Metadata

* [extruct](https://github.com/scrapinghub/extruct) - A library for extracting embedded metadata from HTML markup.

## Text Processing

Libraries for parsing and manipulating plain texts.

### Text Processing : General

* [difflib](https://docs.python.org/3/library/difflib.html) - (Python standard library) Helpers for computing deltas.
* [Levenshtein](https://github.com/ztane/python-Levenshtein/) - Fast computation of Levenshtein distance and string similarity.
* [fuzzywuzzy](https://github.com/seatgeek/fuzzywuzzy) - Fuzzy String Matching.
* [esmre](https://code.google.com/p/esmre/) - Regular expression accelerator.
* [ftfy](https://github.com/LuminosoInsight/python-ftfy) - Makes Unicode text less broken and more consistent automagically.

### Text Processing : Transliteration

* [unidecode](https://pypi.python.org/pypi/Unidecode) - ASCII transliterations of Unicode text.

### Text Processing : Character Encoding

* [uniout](https://github.com/moskytw/uniout) - Print readable chars instead of the escaped string.
* [chardet](https://github.com/chardet/chardet) - Python 2/3 compatible character encoding detector.
* [xpinyin](https://github.com/lxneng/xpinyin) - A library to translate Chinese hanzi (漢字) to pinyin (拼音).
* [pangu.py](https://github.com/vinta/pangu.py) - Spacing texts for CJK and alphanumerics.
* [cchardet](https://github.com/PyYoshi/cChardet) - cChardet is high speed universal character encoding detector. - binding to uchardet.

### Text Processing : Slugify

* [awesome-slugify](https://github.com/dimka665/awesome-slugify) - A Python slugify library that can preserve unicode.
* [python-slugify](https://github.com/un33k/python-slugify) - A Python slugify library that translates unicode to ASCII.
* [unicode-slugify](https://github.com/mozilla/unicode-slugify) - A slugifier that generates unicode slugs.
* [pytils](https://github.com/j2a/pytils) - Simple tools for processing strings in russian (including pytils.translit.slugify)

### Text Processing : General Parser

* [PLY](http://www.dabeaz.com/ply/) - Implementation of lex and yacc parsing tools for Python
* [pyparsing](http://pyparsing.wikispaces.com/) - A general purpose framework for generating parsers.

### Text Processing : Human Names

* [python-nameparser](https://github.com/derek73/python-nameparser) - Parsing human names into their individual components.

### Text Processing : Phone Number

* [phonenumbers](https://github.com/daviddrysdale/python-phonenumbers) - Parsing, formatting, storing and validating international phone numbers.

### Text Processing :: User-Agent strings

* [HTTP Agent Parser](https://github.com/shon/httpagentparser) - Python HTTP Agent Parser
* [uap-python](https://github.com/ua-parser/uap-python) - Python implementation of ua-parser
* [python-user-agents](https://github.com/selwin/python-user-agents) - Browser user agent parser.
* [fake-useragent](https://github.com/hellysmile/fake-useragent) - Python user agent string faker, based on world statistic of browsers
* [user_agent](https://github.com/lorien/user_agent) - Generator of User-Agent data

### Text Processing : robots.txt

* [reppy](https://github.com/seomoz/reppy) - Modern robots.txt Parser for Python
    
### Text Processing :: Date and Time

* [dateutil](https://github.com/dateutil/dateutil) - Useful extensions to the standard Python datetime features
* [dateparser](https://github.com/scrapinghub/dateparser) - python parser for human readable dates
* [ciso8601](https://github.com/closeio/ciso8601) - converts ISO 8601 or RFC 3339 date time strings into Python datetime objects

### Text Processing :: Price and Currency

* [price-parser](https://github.com/scrapinghub/price-parser) - a small library for extracting price and currency from raw text strings.

## Structured Formats

Libraries for parsing and manipulating specific text formats.

### Structured Formats : General

* [tablib](https://github.com/kennethreitz/tablib) - A module for Tabular Datasets in XLS, CSV, JSON, YAML.
* [textract](https://github.com/deanmalmgren/textract) - Extract text from any document, Word, PowerPoint, PDFs, etc.
* [messytables](https://github.com/okfn/messytables) - Tools for parsing messy tabular data
* [rows](https://github.com/turicas/rows) - A common, beautiful interface to tabular data, no matter the format (currently CSV, HTML, XLS, TXT -- more coming!)

### Structured Formats : Office

* [python-docx](https://github.com/python-openxml/python-docx) - Reads, queries and modifies Microsoft Word 2007/2008 docx files.
* [xlwt](https://github.com/python-excel/xlwt) / [xlrd](https://github.com/python-excel/xlrd) - Writing and reading data and formatting information from Excel files.
* [XlsxWriter](https://xlsxwriter.readthedocs.org/) - A Python module for creating Excel .xlsx files.
* [xlwings](http://xlwings.org/) - A BSD-licensed library that makes it easy to call Python from Excel and vice versa.
* [openpyxl](https://openpyxl.readthedocs.org/en/latest/) - A library for reading and writing Excel 2010 xlsx/xlsm/xltx/xltm files.
* [Marmir](https://github.com/brianray/mm) - Takes Python data structures and turns them into spreadsheets.

### Structured Formats : PDF

* [PDFMiner](https://github.com/euske/pdfminer) - A tool for extracting information from PDF documents.
* [PyPDF2](https://github.com/mstamy2/PyPDF2) - A library capable of splitting, merging and transforming PDF pages.
* [ReportLab](http://www.reportlab.com/opensource/) - Allowing Rapid creation of rich PDF documents.
* [pdftables](https://pypi.python.org/pypi/pdftables) - Extract tables from PDF files directly

### Structured Formats : Markdown

* [Python-Markdown](https://github.com/waylan/Python-Markdown) - A Python implementation of John Gruber’s Markdown.
* [Mistune](https://github.com/lepture/mistune) - Fastest and full featured pure Python parsers of Markdown.
* [markdown2](https://pypi.python.org/pypi/markdown2) - A fast and complete Python implementation of Markdown
* [mistletoe](https://github.com/miyuchina/mistletoe) - A fast, extensible and spec-compliant Markdown parser in pure Python

### Structured Formats : YAML

* [PyYAML](https://github.com/yaml/pyyaml) - YAML implementations for Python.

### Structured Formats : CSS

* [cssutils](https://pypi.python.org/pypi/cssutils/) - A CSS library for Python.

### Structured Formats : ATOM/RSS

* [feedparser](http://pythonhosted.org/feedparser/) - Universal feed parser.

### Structured Formats : SQL

* [sqlparse](https://sqlparse.readthedocs.org/) - A non-validating SQL parser.

### Structured Formats : HTTP

* [http-parser](https://github.com/benoitc/http-parser) - HTTP request/response parser for python in C
* [httptools](https://github.com/MagicStack/httptools) - a Python binding for nodejs HTTP parser

### Structured Formats : Microformats

* [opengraph](https://github.com/erikriver/opengraph) - A Python module to parse the Open Graph Protocol tags

### Structured Formats :  Portable Executable

*  [pefile](https://github.com/erocarrera/pefile) - A multi-platform module to parse and work with Portable Executable (aka PE) files.

### Structured Formats : PSD

* [psd-tools](https://github.com/kmike/psd-tools) - reading Adobe Photoshop PSD files (as described in [specification](https://www.adobe.com/devnet-apps/photoshop/fileformatashtml/PhotoshopFileFormats.htm)) to Python data structures.

### Structured Formats : Bookmarks File

* [bookmarks-parser](https://github.com/bookmarks-tools/bookmarks-parser) - Parses Firefox/Chrome HTML bookmarks files

## Serialization

* [orjson](https://github.com/ijl/orjson) - Fast, correct Python JSON library supporting dataclasses and datetimes
* [ujson](https://github.com/esnme/ultrajson) - Ultra fast JSON decoder and encoder written in C with Python bindings

## Natural Language Processing

Libraries for working with human languages.

* [NLTK](http://www.nltk.org/) - A leading platform for building Python programs to work with human language data.
* [spacy](https://github.com/explosion/spaCy) - Enables using State-of-the-Art Deep Learning models for common NLP tasks.
* [fastai](https://github.com/fastai/fastai) - Deep Learning library with free video tutorials + active forum community, downside of lib: GPU needed
* [gensim](https://github.com/RaRe-Technologies/gensim) -  library for topic modeling, document indexing and similarity retrieval with large corpora
* [Pattern](http://www.clips.ua.ac.be/pattern) - A web mining module for the Python. It has tools for natural language processing, machine learning, among others.
* [TextBlob](http://textblob.readthedocs.org/) - Providing a consistent API for diving into common NLP tasks. Stands on the giant shoulders of NLTK and Pattern.
* [jieba](https://github.com/fxsjy/jieba) - Chinese Words Segmentation Utilities.
* [SnowNLP](https://github.com/isnowfy/snownlp) - A library for processing Chinese text.
* [loso](https://github.com/victorlin/loso) - Another Chinese segmentation library.
* [genius](https://github.com/duanhongyi/genius) - A Chinese segment base on Conditional Random Field.
* [langid.py](https://github.com/saffsd/langid.py) - Stand-alone language identification system.
* [Korean](https://korean.readthedocs.org/) - A library for [Korean](http://en.wikipedia.org/wiki/Korean_language) morphology.
* [pymorphy2](https://github.com/kmike/pymorphy2) - Morphological analyzer (POS tagger + inflection engine) for Russian language.
* [PyPLN](https://github.com/NAMD/pypln.backend) - A distributed pipeline for natural language processing, made in Python. he goal of the project is to create an easy way to use NLTK for processing big corpora, with a Web interface.
* [langdetect](https://github.com/Mimino666/langdetect) - Port of Google's language-detection library to Python

## Browser Automation

### Browser Automation : Browsers

* [selenium](http://selenium-python.readthedocs.io/) - automating real browsers (Chrome, Firefox, Opera, IE)
* [Ghost.py](http://carrerasrodrigo.github.io/Ghost.py/) - wrapper of QtWebKit (requires PyQT)
* [Spynner](https://github.com/makinacorpus/spynner) - wrapper of QtWebKit QtWebKit (requires PyQT)
* [Splinter](https://github.com/cobrateam/splinter) - universal API to browser emulators (selenium webdrivers, django client, zope)
* [Requestium](https://github.com/tryolabs/requestium) - Integration layer between Requests and Selenium for automation of web actions.
* [Splash](https://github.com/scrapinghub/splash) - Lightweight, scriptable browser as a service with an HTTP API.
* [pyppeteer](https://github.com/miyakogi/pyppeteer) - Headless chrome/chromium automation library (unofficial port of puppeteer)
* [Playwright](https://github.com/microsoft/playwright-python) - Playwright is a Python library to automate Chromium, Firefox and WebKit browsers with a single API
* [seleniumbase](https://github.com/seleniumbase/SeleniumBase) - Python framework for Web/UI testing + RPA. 🤖 🏰 Fast, easy, and reliable.

### Browser Automation : Tools

* [xvfbwrapper](https://github.com/cgoldberg/xvfbwrapper) - Python wrapper for running a display inside X virtual framebuffer (Xvfb)

## Multiprocessing

* [threading](http://docs.python.org/3/library/threading.html) - standard python library to run threads. Effective for I/O-bound tasks. Useless for CPU-bound tasks because of python GIL.
* [multiprocessing](http://docs.python.org/3/library/multiprocessing.html) - standard python library to run processes.
* [concurrent-futures](https://docs.python.org/3/library/concurrent.futures.html) - The concurrent.futures module provides a high-level interface for asynchronously executing callables.

## Asynchronous

Libraries for asynchronous networking programming.

* [asyncio](https://docs.python.org/3/library/asyncio.html) - (Python standard library in Python 3.4+) Asynchronous I/O, event loop, coroutines and tasks.
* [Twisted](https://twistedmatrix.com/trac/) - An event-driven networking engine.
* [Tornado](http://www.tornadoweb.org/) - A Web framework and asynchronous networking library.
* [pulsar](https://github.com/quantmind/pulsar) - Event-driven concurrent framework for Python.
* [diesel](https://github.com/jamwt/diesel) - Greenlet-based event I/O Framework for Python.
* [gevent](http://www.gevent.org/) - A coroutine-based Python networking library that uses [greenlet](https://github.com/python-greenlet/greenlet).
* [eventlet](http://eventlet.net/) - Asynchronous framework with WSGI support.
* [Tomorrow](https://github.com/madisonmay/Tomorrow) - Magic decorator syntax for asynchronous code.
* [grequests](https://github.com/kennethreitz/grequests) - Make asynchronous HTTP Requests easily.

## Job Queue

* [celery](http://www.celeryproject.org/) - An asynchronous task queue/job queue based on distributed message passing.
* [huey](https://github.com/coleifer/huey) - Little multi-threaded task queue.
* [mrq](https://github.com/pricingassistant/mrq) - Mr. Queue - A distributed worker task queue in Python using Redis & gevent.
* [RQ](https://github.com/rq/rq) - lightweight task queue manager based on redis
* [simpleq](https://github.com/rdegges/simpleq) - A simple, infinitely scalable, Amazon SQS based queue.
* [python-gearman](https://github.com/Yelp/python-gearman) - python API for Gearman

## Message Queue

* [kombu](https://github.com/celery/kombu) - Messaging library for Python

## Cloud Computing

* [picloud](http://docs.picloud.com/) - executing python-code in cloud
* [dominoup.com](http://www.dominoup.com/) - executing R, Python и matlab code in cloud
* [minigun-requests](https://github.com/umihico/minigun-requests) - Web scraping API to outsource tons of GET & xpath to cloud computing
* [pythonista-chromeless](https://github.com/umihico/pythonista-chromeless) - AWS lambda which execute given python code on selenium

## Email

Libraries for parsing email.

* [flanker](https://github.com/mailgun/flanker) - A email address and Mime parsing library.
* [Talon](https://github.com/mailgun/talon) - Mailgun library to extract message quotations and signatures.

## URL and Network Address

Libraries for parsing/modifying URLs, network addresses, domain names.

### URL and Network Address : URL

* [furl](https://github.com/gruns/furl) - A small Python library that makes manipulating URLs simple.
* [purl](https://github.com/codeinthehole/purl) - A simple, immutable URL class with a clean API for interrogation and manipulation.
* [urllib.parse](https://docs.python.org/3/library/urllib.parse.html) - interface to break Uniform Resource Locator (URL) strings up in components (addressing scheme, network location, path etc.), to combine the components back into a URL string, and to convert a “relative URL” to an absolute URL given a “base URL.” (stdlib)

### URL and Network Address : Network Address

* [netaddr](https://github.com/drkjam/netaddr) - A Python library for representing and manipulating network addresses.
* [micawber](https://github.com/coleifer/micawber) - A small library for extracting rich content from URLs.

### Domain Names

* [tldextract](https://github.com/john-kurkowski/tldextract) - Accurately separate the TLD from the registered domain and subdomains of a URL, using the Public Suffix List.
* [find_domains](https://github.com/lorien/find_domains) - a library to search for domain names in text data

## Web Content Extraction

Libraries for extracting web contents.

* [newspaper](https://github.com/codelucas/newspaper) - News extraction, article extraction and content curation in Python.
* [python-goose](https://github.com/grangier/python-goose) - HTML Content/Article Extractor.
* [scrapely](https://github.com/scrapy/scrapely) - Library for extracting structured data from HTML pages. Given some example web pages and the data to be extracted, scrapely constructs a parser for all similar pages.
* [htmldate](https://github.com/adbar/htmldate) - Find creation date using common structural patterns or text-based heuristics.
* [lassie](https://github.com/michaelhelmick/lassie) - Web Content Retrieval for Humans.
* [html2text](https://github.com/Alir3z4/html2text) - Convert HTML to Markdown-formatted text.
* [libextract](https://github.com/datalib/libextract) - Extract data from websites.
* [python-readability](https://github.com/buriy/python-readability) - Fast Python port of arc90's readability tool.
* [sumy](https://github.com/miso-belica/sumy) - A module for automatic summarization of text documents and HTML pages.
* [Haul](https://github.com/vinta/Haul) - An Extensible Image Crawler.
* [you-get](http://www.soimort.org/you-get/) - A YouTube/Youku/Niconico video downloader written in Python 3.
* [youtube-dl](http://rg3.github.io/youtube-dl/) - A small command-line program to download videos from YouTube.
* [WikiTeam](https://github.com/WikiTeam/wikiteam) - Tools for downloading and preserving wikis.
* [linkchecker](https://github.com/wummel/linkchecker) - check links in web documents or full websites
* [python-sitemap](https://github.com/c4software/python-sitemap) - Mini website crawler to make sitemap from a website.
* [trafilatura](https://github.com/adbar/trafilatura) - Fast extraction of main text and comments along with structure, conversion to TXT, CSV & XML.
* [advertools](https://github.com/eliasdabbas/advertools) - A customizable crawler to analyze SEO and content of pages and websites.
* [photon](https://github.com/s0md3v/Photon) - Incredibly fast crawler designed for OSINT
* [extractnet](https://github.com/currentsapi/extractnet) - Machine Learning based content and metadata extraction in Python 3

## WebSocket

Libraries for working with WebSocket.

* [Crossbar](https://github.com/crossbario/crossbar/) - Open-source Unified Application Router (Websocket & WAMP for Python on Autobahn).
* [AutobahnPython](https://github.com/tavendo/AutobahnPython) - WebSocket & WAMP for Python on Twisted and [asyncio](https://docs.python.org/3/library/asyncio.html).
* [WebSocket-for-Python](https://github.com/Lawouach/WebSocket-for-Python) - WebSocket client and server library for Python 2 and 3 as well as PyPy.

## DNS Resolving

* [dnspython](https://github.com/rthalley/dnspython) - a powerful DNS toolkit for python
* [dnsyo](https://github.com/samarudge/dnsyo) - Check your DNS against over 1500 global DNS servers.
* [pycares](https://github.com/saghul/pycares) -  interface to c-ares. c-ares is a C library that performs DNS requests and name resolutions asynchronously

## Computer Vision

* [OpenCV](https://github.com/Itseez/opencv) - Open Source Computer Vision Library.
* [SimpleCV](https://github.com/sightmachine/SimpleCV) - Concise, readable interface for cameras, image manipulation, feature extraction, and format conversion (based on OpenCV).
* [mahotas](https://github.com/luispedro/mahotas) - fast computer vision algorithms (all implemented in C++) operating over numpy arrays.

## Proxy Server

* [scylla](https://github.com/imWildCat/scylla) - Intelligent proxy pool for Humans
* [ProxyBroker](https://github.com/constverum/Proxybroker) - Proxy [Finder | Checker | Server]. HTTP(S) & SOCKS
* [shadowsocks](https://github.com/shadowsocks/shadowsocks) - A fast tunnel proxy that helps you bypass firewalls (TCP & UDP support, User management API, TCP Fast Open, Workers and graceful restart, Destination IP blacklist)
* [tproxy](https://github.com/benoitc/tproxy) - tproxy is a simple TCP routing proxy (layer 7) built on Gevent that lets you configure the routine logic in Python
  
## Whois

* [python-whois](https://github.com/joepie91/python-whois) - A python module for retrieving and parsing WHOIS data

## Website Specific Scraper
* [twitter-scraper](https://github.com/bisguzar/twitter-scraper) - Scrape the Twitter Frontend API without authentication
* [Ultimate-Facebook-Scraper](https://github.com/harismuneer/Ultimate-Facebook-Scraper) - A bot which scrapes almost everything about a Facebook user's profile
* [instagram-scraper](https://github.com/rarcega/instagram-scraper) - Scrapes an instagram user's photos and videos

## JavaScript Engine Bindings

* [Js2Py](https://github.com/PiotrDabkowski/Js2Py) - JavaScript to Python Translator & JavaScript interpreter written in 100% pure Python
* [v8eval](https://github.com/sony/v8eval/) - Multi-language bindings to JavaScript engine V8

## Other python lists

* [awesome-python](https://github.com/vinta/awesome-python)
* [pycrumbs](https://github.com/kirang89/pycrumbs)
* [python-github-projects](https://github.com/checkcheckzz/python-github-projects)
* [python_reference](https://github.com/rasbt/python_reference)
* [pythonidae](https://github.com/svaksha/pythonidae)

