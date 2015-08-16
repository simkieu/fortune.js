Fortune.js
==========

## Introduction

This repository contains a tiny fortune quotes database (172) and 
a library that read the quotes and returns a random one.

## How to use

```html
<script type="text/javascript" src="fortune.js"></script>
```
```javascript
fortune.getQuote(function(quote) {
    console.log(quote); // i.e. Happy news is on its way to you.
});
```

* Optionally, you can pass a second parameter which represents another fortunes database (single quote per line):
```javascript
fortune.getQuote(function(quote) {
    console.log(quote); // i.e. My nice quote.
}, "myFortunes.txt");
```

## Files

* *quotes.txt* contains the fortunes (i.e. the quotes)
* *fortune.js* library which reads the quotes and picks a random one
* *demo.html* demo file which shows a quote every reload

---

Patricio Córdova, [patricio@cs.toronto.edu]