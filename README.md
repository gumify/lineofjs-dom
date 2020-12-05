## Quick start

Clone the github repo `git clone https://github.com/lineofapi/lineofjs-dom.git` and under the `dest` folder, you can find the minified version of the `lineofjs-dom`. Add it to your HTML as you would add any JavaScript files.

Or use CDN link

```html
<script src="https://cdn.jsdelivr.net/gh/lineofapi/lineofjs-dom@1.0.1/dest/lineof-dom.min.js"></script>
```

[![Build Status](https://travis-ci.org/lineofapi/lineofjs-dom.svg?branch=master)](https://travis-ci.org/lineofapi/lineofjs-dom)
[![License](https://img.shields.io/github/license/lineofapi/lineofjs-dom.svg)](https://github.com/lineofapi/lineofjs-dom/blob/master/LICENSE)
[![Version](https://img.shields.io/github/release/lineofapi/lineofjs-dom.svg)](https://github.com/lineofapi/lineofjs-dom/releases/latest)


## DOM methods

DOM methods makes DOM manipulation much easier.

```js
const lineof = new Lineof();
const $ = lineof.dom;
```

- [$([selector, function])](#dom-method-$)
- [.action(className)](#dom-method-action)
- [.addClass(className)](#dom-method-addClass)
- [.append(\[arugments\])](#dom-method-append)
- [.attr(key, \[value\])](#dom-method-attr)
- [.bind(event, callback)](#dom-method-bind)
- [.children(\[includeTextNodes=false\])](#dom-method-children)
- [.click(callback)](#dom-method-click)
- [.css(key, \[value\])](#dom-method-css)
- [.disable()](#dom-method-disable)
- [.enable()](#dom-method-enable)
- [.extend(\[arguments\])](#dom-method-extend)
- [.each(callback, \[context\])](#dom-method-each)
- [.filter(selector)](#dom-method-filter)
- [.first()](#dom-method-first)
- [.get(index)](#dom-method-get)
- [.hide()](#dom-method-hide)
- [.height(\[height\])](#dom-method-height)
- [.href()](#dom-method-href)
- [.html(\[html\])](#dom-method-html)
- [.isDisabled()](#dom-method-isDisabled)
- [.innerHeight()](#dom-method-innerHeight)
- [.innerWidth()](#dom-method-innerWidth)
- [.last()](#dom-method-last)
- [.offset()](#dom-method-offset)
- [.on(event, callback)](#dom-method-on)
- [.parent()](#dom-method-parent)
- [.parents()](#dom-method-parents)
- [.prepend(\[arugments\])](#dom-method-prepend)
- [.ready(function)](#dom-method-ready)
- [.removeClass(className)](#dom-method-removeClass)
- [.remove()](#dom-method-remove)
- [.removeAttr(key)](#dom-method-removeAttr)
- [.show()](#dom-method-show)
- [.siblings()](#dom-method-siblings)
- [.src()](#dom-method-src)
- [.toggleClass(className)](#dom-method-toggleClass)
- [.text(s)](#dom-method-text)
- [.unbind(event)](#dom-method-unbind)
- [.val(value)](#dom-method-val)
- [.width(\[width\])](#dom-method-width)