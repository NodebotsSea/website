# Nodebots Seattle

[http://nodebotssea.github.io/website/](http://nodebotssea.github.io/website/)

Watch the site above or [https://twitter.com/nodebotssea](https://twitter.com/nodebotssea) for the next event.

### Developing the site

[![Build Status](https://travis-ci.org/NodebotsSea/website.svg?branch=master)](https://travis-ci.org/NodebotsSea/website)

It's a wintersmith website, so 

```
$ npm install -g wintersmith
$ npm install
$ wintersmith preview
```

### Deploying the site

```
$ wintersmith build
$ git checkout gh-pages
$ git add [files that changed]
$ git commit
```
