Fortune.js
==========

## Introduction

This repository contains a tiny fortune quotes database (172) and 
a library that read the quotes and picks a random one.

## How to use

```html
<script type="text/javascript" src="fortune.js"></script>

<script>
	fortune.getQuote(function(quote) {
	    console.log(quote);
	});
</script>
```

* Optionally, you can pass another fortunes file (single quote per line) as a second parameter:
```html
<script>
	fortune.getQuote(function(quote) {
	    console.log(quote);
	}, "myFortunes.txt");
</script>
```

## Files

* *quotes.txt* contains the fortunes (i.e. the quotes)
* *fortune.js* library
* *demo.html* demo file which shows a quote every reload

---

Patricio Córdova, [patricio@cs.toronto.edu]