# css snippets
Re-usable CSS Snippets

#### Viewport Meta
**You need to make all yo pages responsive**
```html
<meta name="viewport" content="width=device-width, initial-scale=1">
```

#### Responsive Background Image
```css
.responsive-background {
    background: url(/path/to/your/image.png) no-repeat center center fixed;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
}
```

#### Side-by-side columns
```css
.column-container {
  position: relative;
  margin: auto;
}
.column-right {
  display: block;
  float: right;
}
.column-left {
  display: block;
  float: left;
}
```
**Usage**
```html
<div class="column-container">
    <section class="column-left"></section>
    <aside class="column-right"></aside>
</div>
```

#### Turn submit button into image
```css
/* add this class to your submit button to make it an image */
.submit-button-img {
  background: url(http://x3dgraphics.com/examples/X3dForAdvancedModeling/HelloWorldScenes/HelloWorld.tall.png);
    border: 0;
    display: block;
    height: 100px; /* change to your own needs */
    width: 100px; /* change to your own needs */
}
```

**Usage**

```html
<submit value="what" class="submit-button-img"></submit>
```
