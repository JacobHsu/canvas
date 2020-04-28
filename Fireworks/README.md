

canvas-container 父類別 background 在後

```html
<div id="canvas-container">
    <div id="mountains2"></div>
    <div id="skyline"></div>
</div>
```

z-index 同層級 HTML在下者更上層 (skyline在mountains2前)

```html
<div id="mountains2"></div>
<div id="skyline"></div>
```

```css
#skyline {
    z-index: 1;	
#mountains2 {
    z-index: 1;	
```


[12 Incredible CodePen.IO Demos](https://davidwalsh.name/codepen-demos) Canvas Fireworks