// ==UserScript==
// @name          GitHub Code Wrap
// @namespace     http://userstyles.org
// @description	  Wrap long lines of code everywhere on GitHub.
// @author        StylishThemes
// @homepage      https://userstyles.org/styles/124860
// @include       http://github.com/*
// @include       https://github.com/*
// @include       http://*.github.com/*
// @include       https://*.github.com/*
// @include       http://gist.github.com/*
// @include       https://gist.github.com/*
// @include       http://*.gist.github.com/*
// @include       https://*.gist.github.com/*
// @run-at        document-start
// @version       0.20160603180549
// ==/UserScript==
(function() {var css = [
	".blob-code-inner,",
	"  .markdown-body pre > code,",
	"  .markdown-body .highlight > pre {",
	"    white-space: pre-wrap !important;",
	"    word-break: break-all !important;",
	"    overflow-wrap: break-word !important;",
	"    display: block !important;",
	"  }",
	"  td.blob-code-inner {",
	"    display: table-cell !important;",
	"  }"
].join("\n");
if (typeof GM_addStyle != "undefined") {
	GM_addStyle(css);
} else if (typeof PRO_addStyle != "undefined") {
	PRO_addStyle(css);
} else if (typeof addStyle != "undefined") {
	addStyle(css);
} else {
	var node = document.createElement("style");
	node.type = "text/css";
	node.appendChild(document.createTextNode(css));
	var heads = document.getElementsByTagName("head");
	if (heads.length > 0) {
		heads[0].appendChild(node);
	} else {
		// no head yet, stick it whereever
		document.documentElement.appendChild(node);
	}
}
})();


## HTML5 and CSS

### Comment out HTML

```
<!--
<h1>Hello World</h1>
-->
<h2>CatPhotoApp</h2>
<!--
<p>Hello Paragraph</p>
-->
```

### Change the Colour of Text

```
<h2 style="color: red">CatPhotoApp</h2>

<p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
```

### Use CSS Selectors to Style Elements

```
<style>
  h2 {color: blue;}
</style>

<h2>CatPhotoApp</h2>

<p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretc
```

### Use a CSS Class to Style an Element

```
<style>
  .red-text {
    color: red;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>

<p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
```

### Style Multiple Elements with a CSS Class

```
<style>
  .red-text {
    color: red;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>

<p class="red-text">Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
```

### Change the font size of an Element

```
<style>
  .red-text {
    color: red;}
 p {font-size: 16px;}
</style>

<h2 class="red-text">CatPhotoApp</h2>

<p class="red-text">Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
<p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
```

### Set the font-family of an Element

```
<style>
  .red-text {
    color: red;
  }

  p {
    font-size: 16px;
    font-family: Monospace;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>

<p class="red-text">Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
<p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p
```
