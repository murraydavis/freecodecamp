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

<p>Kitty ipsum dolor sit.</p>
```

### Use CSS Selectors to Style Elements

```
<style>
  h2 {color: blue;}
</style>

<h2>CatPhotoApp</h2>

<p>Kitty ipsum dolor.</p>
```

### Use a CSS Class to Style an Element

```
<style>
  .red-text {
    color: red;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>

<p>Kitty ipsum dolor.</p>
```

### Style Multiple Elements with a CSS Class

```
<style>
  .red-text {
    color: red;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>

<p class="red-text">Kitty ipsum dolor.</p>
```

### Change the font size of an Element

```
<style>
  .red-text {
    color: red;}
 p {font-size: 16px;}
</style>

<h2 class="red-text">CatPhotoApp</h2>

<p class="red-text">Kitty ipsum dolor.</p>
<p>Purr jump eat.</p>
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

<p class="red-text">Kitty ipsum dolor.</p>
<p>Purr jump eat.</p
```

### Import a Google font

```
<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">
<style>
  .red-text {
    color: red;
  }

  h2 {
    font-family: Lobster, Monospace;
  }

  p {
    font-size: 16px;
    font-family: Monospace;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>

<p class="red-text">Kitty ipsum dolor.</p>
<p class="red-text">Purr jump eat.</p>

### Specify How Fonts Should Degrade

```

### Specify How Fonts Should Degrade

```
<!--<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">-->

<style>
  .red-text {
    color: red;
  }

  h2 {
    font-family: Lobster, Monospace;
  }
  p {
    font-size: 16px;
    font-family: Monospace;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>

<p class="red-text">Kitty ipsum dolor.</p>
<p class="red-text">Purr jump eat.</p>
```

### Add Images to your website

```
<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">
<style>
  .red-text {
    color: red;
  }

  h2 {
    font-family: Lobster, Monospace;
  }

  p {
    font-size: 16px;
    font-family: Monospace;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>

<img src="https://bit.ly/fcc-relaxing-cat" alt="MyCat"

<p class="red-text">Kitty ipsum dolor.</p>
<p class="red-text">Purr jump eat.</p>
```

### Size your Images

```
<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">
<style>
  .red-text {
    color: red;
  }
  .smaller-image {
    width: 100px;
  }

  h2 {
    font-family: Lobster, Monospace;
  }

  p {
    font-size: 16px;
    font-family: Monospace;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>

<img class=smaller-image src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back. ">

<p class="red-text">Kitty ipsum dolor.</p>
<p class="red-text">Purr jump eat.</p>
```

### Add Borders Around your Elements (and multiple classes)

```
<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">
<style>
  .red-text {
    color: red;
  }

  h2 {
    font-family: Lobster, Monospace;
  }

  p {
    font-size: 16px;
    font-family: Monospace;
  }

  .smaller-image {
    width: 100px;
  }

  .thick-green-border {
    border-color: green;
    border-width: 10px;
    border-style: solid;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>

<img class="smaller-image thick-green-border" src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back. ">

<p class="red-text">Kitty ipsum dolor.</p>
<p class="red-text">Purr jump eat.</p>
```
