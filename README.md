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

class|attribute|value|responsive
-|-|-|-
.d-f|display|flex|:ballot_box_with_check:
.d-b|display|block|:ballot_box_with_check:
.d-if|display|inline-flex|:ballot_box_with_check:
.d-i|display|inline|:ballot_box_with_check:
.d-ib|display|inline-block|:ballot_box_with_check:
.d-n|display|none|:ballot_box_with_check:
 | | | 
.fw-w|flex-wrap|wrap|:ballot_box_with_check:
.fw-n|flex-wrap|nowrap|:ballot_box_with_check:
.fw-wr|flex-wrap|wrap-reverse|:ballot_box_with_check:
 | | | 
.fd-r    | flex-direction|row |:ballot_box_with_check:
.fd-c    | flex-direction|column |:ballot_box_with_check:
.fd-rr   | flex-direction|row-reverse |:ballot_box_with_check:
.fd-cr   | flex-direction|column-reverse |:ballot_box_with_check:
 | | | 
.jc-c    | justify-content|center |:ballot_box_with_check:
.jc-fs   | justify-content|flex-start |:ballot_box_with_check:
.jc-fe   | justify-content|flex-end |:ballot_box_with_check:
.jc-sa   | justify-content|space-around |:ballot_box_with_check:
.jc-sb   | justify-content|space-between |:ballot_box_with_check:
 | | | 
.ai-c    | align-items|center |:ballot_box_with_check:
.ai-fs   | align-items|flex-start |:ballot_box_with_check:
.ai-fe   | align-items|flex-end |:ballot_box_with_check:
.ai-s    | align-items|stretch |:ballot_box_with_check:
.ai-b    | align-items|baseline |:ballot_box_with_check:
 | | | 
.ac-c    | align-content|center |:ballot_box_with_check:
.ac-fs   | align-content|flex-start |:ballot_box_with_check:
.ac-fe   | align-content|flex-end |:ballot_box_with_check:
.ac-sa   | align-content|space-around |:ballot_box_with_check:
.ac-sb   | align-content|space-between |:ballot_box_with_check:
.ac-s    | align-content|stretch |:ballot_box_with_check:
 | | | 
.as-c    | align-self|center |:ballot_box_with_check:
.as-fs   | align-self|flex-start |:ballot_box_with_check:
.as-fe   | align-self|flex-end |:ballot_box_with_check:
.as-s    | align-self|stretch |:ballot_box_with_check:
.as-b    | align-self|baseline |:ballot_box_with_check:
 | | | 
