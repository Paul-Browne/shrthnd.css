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
.w-1-1   | width| 100% |:ballot_box_with_check:
.w-1-2   | width| 50% |:ballot_box_with_check:
.w-1-3   | width| 33.333% |:ballot_box_with_check:
.w-2-3   | width| 66.666% |:ballot_box_with_check:
.w-1-4   | width| 25% |:ballot_box_with_check:
.w-3-4   | width| 75% |:ballot_box_with_check:
.w-1-6   | width| 16.666% |:ballot_box_with_check:
.w-5-6   | width| 83.333% |:ballot_box_with_check:
.w-1-12  | width| 8.333% |:ballot_box_with_check:
.w-5-12  | width| 41.666% |:ballot_box_with_check:
.w-7-12  | width| 58.333% |:ballot_box_with_check:
.w-11-12 | width| 91.666% |:ballot_box_with_check:
 | | | 
.w-1     | width| 1rem |:ballot_box_with_check:
.w-15    | width| 1.5rem |:ballot_box_with_check:
.w-2     | width| 2rem |:ballot_box_with_check:
.w-3     | width| 3rem |:ballot_box_with_check:
.w-4     | width| 4rem |:ballot_box_with_check:
.w-5     | width| 5rem |:ballot_box_with_check:
.w-6     | width| 6rem |:ballot_box_with_check:
.w-7     | width| 7rem |:ballot_box_with_check:
.w-8     | width| 8rem |:ballot_box_with_check:
.w-9     | width| 9rem |:ballot_box_with_check:
 | | | 
.h-1-1   | height| 100% |:ballot_box_with_check:
.h-1-2   | height| 50% |:ballot_box_with_check:
.h-1-3   | height| 33.333% |:ballot_box_with_check:
.h-2-3   | height| 66.666% |:ballot_box_with_check:
.h-1-4   | height| 25% |:ballot_box_with_check:
.h-3-4   | height| 75% |:ballot_box_with_check:
.h-1-6   | height| 16.666% |:ballot_box_with_check:
.h-5-6   | height| 83.333% |:ballot_box_with_check:
.h-1-12  | height| 8.333% |:ballot_box_with_check:
.h-5-12  | height| 41.666% |:ballot_box_with_check:
.h-7-12  | height| 58.333% |:ballot_box_with_check:
.h-11-12 | height| 91.666% |:ballot_box_with_check:
 | | | 
.h-1     | height| 1rem |:ballot_box_with_check:
.h-15    | height| 1.5rem |:ballot_box_with_check:
.h-2     | height| 2rem |:ballot_box_with_check:
.h-3     | height| 3rem |:ballot_box_with_check:
.h-4     | height| 4rem |:ballot_box_with_check:
.h-5     | height| 5rem |:ballot_box_with_check:
.h-6     | height| 6rem |:ballot_box_with_check:
.h-7     | height| 7rem |:ballot_box_with_check:
.h-8     | height| 8rem |:ballot_box_with_check:
.h-9     | height| 9rem |:ballot_box_with_check:
 | | | 
.m-a     | margin-left | auto |:ballot_box_with_check:
&nbsp;     | margin-right | auto |:ballot_box_with_check:
 | | | 
.m-0     | margin| 0 |:ballot_box_with_check:
.m-05    | margin| 0.5rem |:ballot_box_with_check:
.m-1     | margin| 1rem |:ballot_box_with_check:
.m-15    | margin| 1.5rem |:ballot_box_with_check:
.m-2     | margin| 2rem |:ballot_box_with_check:
.m-3     | margin| 3rem |:ballot_box_with_check:
.m-4     | margin| 4rem |:ballot_box_with_check:
 | | | 
.mt-0    | margin-top| 0 |:ballot_box_with_check:
.mt-05   | margin-top| 0.5rem |:ballot_box_with_check:
.mt-1    | margin-top| 1rem |:ballot_box_with_check:
.mt-15   | margin-top| 1.5rem |:ballot_box_with_check:
.mt-2    | margin-top| 2rem |:ballot_box_with_check:
.mt-3    | margin-top| 3rem |:ballot_box_with_check:
.mt-4    | margin-top| 4rem |:ballot_box_with_check:
 | | | 
.mb-0    | margin-bottom| 0 |:ballot_box_with_check:
.mb-05   | margin-bottom| 0.5rem |:ballot_box_with_check:
.mb-1    | margin-bottom| 1rem |:ballot_box_with_check:
.mb-15   | margin-bottom| 1.5rem |:ballot_box_with_check:
.mb-2    | margin-bottom| 2rem |:ballot_box_with_check:
.mb-3    | margin-bottom| 3rem |:ballot_box_with_check:
.mb-4    | margin-bottom| 4rem |:ballot_box_with_check:
 | | | 
.ml-0    | margin-left| 0 |:ballot_box_with_check:
.ml-05   | margin-left| 0.5rem |:ballot_box_with_check:
.ml-1    | margin-left| 1rem |:ballot_box_with_check:
.ml-15   | margin-left| 1.5rem |:ballot_box_with_check:
.ml-2    | margin-left| 2rem |:ballot_box_with_check:
.ml-3    | margin-left| 3rem |:ballot_box_with_check:
.ml-4    | margin-left| 4rem |:ballot_box_with_check:
 | | | 
.mr-0    | margin-right| 0 |:ballot_box_with_check:
.mr-05   | margin-right| 0.5rem |:ballot_box_with_check:
.mr-1    | margin-right| 1rem |:ballot_box_with_check:
.mr-15   | margin-right| 1.5rem |:ballot_box_with_check:
.mr-2    | margin-right| 2rem |:ballot_box_with_check:
.mr-3    | margin-right| 3rem |:ballot_box_with_check:
.mr-4    | margin-right| 4rem |:ballot_box_with_check:
 | | | 
.p-0     | padding| 0 |:ballot_box_with_check:
.p-05    | padding| 0.5rem |:ballot_box_with_check:
.p-1     | padding| 1rem |:ballot_box_with_check:
.p-15    | padding| 1.5rem |:ballot_box_with_check:
.p-2     | padding| 2rem |:ballot_box_with_check:
.p-3     | padding| 3rem |:ballot_box_with_check:
.p-4     | padding| 4rem |:ballot_box_with_check:
 | | | 
.pt-0    | padding-top| 0 |:ballot_box_with_check:
.pt-05   | padding-top| 0.5rem |:ballot_box_with_check:
.pt-1    | padding-top| 1rem |:ballot_box_with_check:
.pt-15   | padding-top| 1.5rem |:ballot_box_with_check:
.pt-2    | padding-top| 2rem |:ballot_box_with_check:
.pt-3    | padding-top| 3rem |:ballot_box_with_check:
.pt-4    | padding-top| 4rem |:ballot_box_with_check:
 | | | 
.pb-0    | padding-bottom| 0 |:ballot_box_with_check:
.pb-05   | padding-bottom| 0.5rem |:ballot_box_with_check:
.pb-1    | padding-bottom| 1rem |:ballot_box_with_check:
.pb-15   | padding-bottom| 1.5rem |:ballot_box_with_check:
.pb-2    | padding-bottom| 2rem |:ballot_box_with_check:
.pb-3    | padding-bottom| 3rem |:ballot_box_with_check:
.pb-4    | padding-bottom| 4rem |:ballot_box_with_check:
 | | | 
.pl-0    | padding-left| 0 |:ballot_box_with_check:
.pl-05   | padding-left| 0.5rem |:ballot_box_with_check:
.pl-1    | padding-left| 1rem |:ballot_box_with_check:
.pl-15   | padding-left| 1.5rem |:ballot_box_with_check:
.pl-2    | padding-left| 2rem |:ballot_box_with_check:
.pl-3    | padding-left| 3rem |:ballot_box_with_check:
.pl-4    | padding-left| 4rem |:ballot_box_with_check:
 | | | 
.pr-0    | padding-right| 0 |:ballot_box_with_check:
.pr-05   | padding-right| 0.5rem |:ballot_box_with_check:
.pr-1    | padding-right| 1rem |:ballot_box_with_check:
.pr-15   | padding-right| 1.5rem |:ballot_box_with_check:
.pr-2    | padding-right| 2rem |:ballot_box_with_check:
.pr-3    | padding-right| 3rem |:ballot_box_with_check:
.pr-4    | padding-right| 4rem |:ballot_box_with_check:
 | | | 
