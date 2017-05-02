# shrthnd.css
d-f = display:flex; you get the idea! :smile:

2.5kb when minified and gzipped

#### whats the general idea?

A lot of css is repeated, like `display: flex`

```html
<div class="hero-container" >
    <h1 class="hero-container__text">Some hero text</h1>
</div>    
```

The class `.hero-container` tells you nothing about what it does


```html
<div class="hero-container d-f ai-c " >
    <h1 class="m-0 fs-44 fw-700">Some hero text</h1>
</div>    
```


#### cheatsheet

class|attribute|value
-|-|-
.d-f|display|flex
.d-b|display|block
.d-if|display|inline-flex
.d-i|display|inline
.d-ib|display|inline-block
.d-n|display|none
 | | 
.fw-w|flex-wrap|wrap
.fw-n|flex-wrap|nowrap
.fw-wr|flex-wrap|wrap-reverse
