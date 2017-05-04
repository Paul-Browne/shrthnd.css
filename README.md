# shrthnd.css
d-f = display:flex; you get the idea! :smile:

4kb when minified and gzipped

#### whats the general idea?

A lot of css is repeated, like `display: flex`, `margin-bottom:1rem`.

```html
<div class="some--container">
    <img class="some--image" src="https://placekitten.com/g/200/250">
    <h1 class="some--header-text">Some header text</h1>
    <p clas="some--copy-text">A whole bunch of copy text...</p>
</div>    
```

The classes `.some--container`, `.some--header-text` tell you nothing about 


```html
<div class="d-f">
    <img class="some--image" src="https://placekitten.com/g/200/250">
    <h1 class="some--header-text">Some header text</h1>
    <p clas="some--copy-text">A whole bunch of copy text...</p>
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
&nbsp; | &nbsp; | &nbsp;
.fw-w|flex-wrap|wrap
.fw-n|flex-wrap|nowrap
.fw-wr|flex-wrap|wrap-reverse
&nbsp; | &nbsp; | &nbsp;
.fd-r    | flex-direction|row 
.fd-c    | flex-direction|column 
.fd-rr   | flex-direction|row-reverse 
.fd-cr   | flex-direction|column-reverse 
&nbsp; | &nbsp; | &nbsp;
.jc-c    | justify-content|center 
.jc-fs   | justify-content|flex-start 
.jc-fe   | justify-content|flex-end 
.jc-sa   | justify-content|space-around 
.jc-sb   | justify-content|space-between 
&nbsp; | &nbsp; | &nbsp;
.ai-c    | align-items|center 
.ai-fs   | align-items|flex-start 
.ai-fe   | align-items|flex-end 
.ai-s    | align-items|stretch 
.ai-b    | align-items|baseline 
&nbsp; | &nbsp; | &nbsp;
.ac-c    | align-content|center 
.ac-fs   | align-content|flex-start 
.ac-fe   | align-content|flex-end 
.ac-sa   | align-content|space-around 
.ac-sb   | align-content|space-between 
.ac-s    | align-content|stretch 
&nbsp; | &nbsp; | &nbsp;
.as-c    | align-self|center 
.as-fs   | align-self|flex-start 
.as-fe   | align-self|flex-end 
.as-s    | align-self|stretch 
.as-b    | align-self|baseline 
&nbsp; | &nbsp; | &nbsp;
.fb-1-1   | flex-basis | 100% 
.fb-1-2   | flex-basis | 50% 
.fb-1-3   | flex-basis | 33.333% 
.fb-2-3   | flex-basis | 66.666% 
.fb-1-4   | flex-basis | 25% 
.fb-3-4   | flex-basis | 75% 
.fb-1-6   | flex-basis | 16.666% 
.fb-5-6   | flex-basis | 83.333% 
.fb-1-12  | flex-basis | 8.333% 
.fb-5-12  | flex-basis | 41.666% 
.fb-7-12  | flex-basis | 58.333% 
.fb-11-12 | flex-basis | 91.666% 
&nbsp; | &nbsp; | &nbsp;
.fb-1     | flex-basis | 1rem 
.fb-15    | flex-basis | 1.5rem 
.fb-2     | flex-basis | 2rem 
.fb-3     | flex-basis | 3rem 
.fb-4     | flex-basis | 4rem 
.fb-5     | flex-basis | 5rem 
.fb-6     | flex-basis | 6rem 
.fb-7     | flex-basis | 7rem 
.fb-8     | flex-basis | 8rem 
.fb-9     | flex-basis | 9rem 
&nbsp; | &nbsp; | &nbsp;
.fs-0     | flex-shrink | 0
.fs-1     | flex-shrink | 1
.fs-2     | flex-shrink | 2
.fs-3     | flex-shrink | 3
.fs-4     | flex-shrink | 4
.fs-5     | flex-shrink | 5
&nbsp; | &nbsp; | &nbsp;
.fg-0     | flex-grow | 0
.fg-1     | flex-grow | 1
.fg-2     | flex-grow | 2
.fg-3     | flex-grow | 3
.fg-4     | flex-grow | 4
.fg-5     | flex-grow | 5
&nbsp; | &nbsp; | &nbsp;
.f-01a     | flex | 0 1 auto
&nbsp; | &nbsp; | &nbsp;
.mw-n    | max-width | none
.mw-60   | max-width | 60rem
.mw-65   | max-width | 65rem
.mw-70   | max-width | 70rem
.mw-75   | max-width | 75rem
.mw-80   | max-width | 80rem
.mw-100  | max-width | 100%
&nbsp; | &nbsp; | &nbsp;
.w-1-1   | width| 100% 
.w-1-2   | width| 50% 
.w-1-3   | width| 33.333% 
.w-2-3   | width| 66.666% 
.w-1-4   | width| 25% 
.w-3-4   | width| 75% 
.w-1-6   | width| 16.666% 
.w-5-6   | width| 83.333% 
.w-1-12  | width| 8.333% 
.w-5-12  | width| 41.666% 
.w-7-12  | width| 58.333% 
.w-11-12 | width| 91.666% 
&nbsp; | &nbsp; | &nbsp;
.w-a     | width| auto 
.w-1     | width| 1rem 
.w-15    | width| 1.5rem 
.w-2     | width| 2rem 
.w-3     | width| 3rem 
.w-4     | width| 4rem 
.w-5     | width| 5rem 
.w-6     | width| 6rem 
.w-7     | width| 7rem 
.w-8     | width| 8rem 
.w-9     | width| 9rem 
&nbsp; | &nbsp; | &nbsp;
.h-1-1   | height| 100% 
.h-1-2   | height| 50% 
.h-1-3   | height| 33.333% 
.h-2-3   | height| 66.666% 
.h-1-4   | height| 25% 
.h-3-4   | height| 75% 
.h-1-6   | height| 16.666% 
.h-5-6   | height| 83.333% 
.h-1-12  | height| 8.333% 
.h-5-12  | height| 41.666% 
.h-7-12  | height| 58.333% 
.h-11-12 | height| 91.666% 
&nbsp; | &nbsp; | &nbsp;
.h-a     | height| auto 
.h-1     | height| 1rem 
.h-15    | height| 1.5rem 
.h-2     | height| 2rem 
.h-3     | height| 3rem 
.h-4     | height| 4rem 
.h-5     | height| 5rem 
.h-6     | height| 6rem 
.h-7     | height| 7rem 
.h-8     | height| 8rem 
.h-9     | height| 9rem 
.h-25    | height| 25vh
.h-50    | height| 50vh
.h-75    | height| 75vh 
.h-100   | height| 100vh 
&nbsp; | &nbsp; | &nbsp;
.m-a     | margin-left | auto 
&nbsp; | margin-right | auto 
&nbsp; | &nbsp; | &nbsp;
.m-0     | margin| 0 
.m-05    | margin| 0.5rem 
.m-1     | margin| 1rem 
.m-15    | margin| 1.5rem 
.m-2     | margin| 2rem 
.m-3     | margin| 3rem 
.m-4     | margin| 4rem 
&nbsp; | &nbsp; | &nbsp;
.mt-0    | margin-top| 0 
.mt-05   | margin-top| 0.5rem 
.mt-1    | margin-top| 1rem 
.mt-15   | margin-top| 1.5rem 
.mt-2    | margin-top| 2rem 
.mt-3    | margin-top| 3rem 
.mt-4    | margin-top| 4rem 
&nbsp; | &nbsp; | &nbsp;
.mb-0    | margin-bottom| 0 
.mb-05   | margin-bottom| 0.5rem 
.mb-1    | margin-bottom| 1rem 
.mb-15   | margin-bottom| 1.5rem 
.mb-2    | margin-bottom| 2rem 
.mb-3    | margin-bottom| 3rem 
.mb-4    | margin-bottom| 4rem 
&nbsp; | &nbsp; | &nbsp;
.ml-0    | margin-left| 0 
.ml-05   | margin-left| 0.5rem 
.ml-1    | margin-left| 1rem 
.ml-15   | margin-left| 1.5rem 
.ml-2    | margin-left| 2rem 
.ml-3    | margin-left| 3rem 
.ml-4    | margin-left| 4rem 
&nbsp; | &nbsp; | &nbsp;
.mr-0    | margin-right| 0 
.mr-05   | margin-right| 0.5rem 
.mr-1    | margin-right| 1rem 
.mr-15   | margin-right| 1.5rem 
.mr-2    | margin-right| 2rem 
.mr-3    | margin-right| 3rem 
.mr-4    | margin-right| 4rem 
&nbsp; | &nbsp; | &nbsp;
.p-0     | padding| 0 
.p-05    | padding| 0.5rem 
.p-1     | padding| 1rem 
.p-15    | padding| 1.5rem 
.p-2     | padding| 2rem 
.p-3     | padding| 3rem 
.p-4     | padding| 4rem 
&nbsp; | &nbsp; | &nbsp;
.pt-0    | padding-top| 0 
.pt-05   | padding-top| 0.5rem 
.pt-1    | padding-top| 1rem 
.pt-15   | padding-top| 1.5rem 
.pt-2    | padding-top| 2rem 
.pt-3    | padding-top| 3rem 
.pt-4    | padding-top| 4rem 
&nbsp; | &nbsp; | &nbsp;
.pb-0    | padding-bottom| 0 
.pb-05   | padding-bottom| 0.5rem 
.pb-1    | padding-bottom| 1rem 
.pb-15   | padding-bottom| 1.5rem 
.pb-2    | padding-bottom| 2rem 
.pb-3    | padding-bottom| 3rem 
.pb-4    | padding-bottom| 4rem 
&nbsp; | &nbsp; | &nbsp;
.pl-0    | padding-left| 0 
.pl-05   | padding-left| 0.5rem 
.pl-1    | padding-left| 1rem 
.pl-15   | padding-left| 1.5rem 
.pl-2    | padding-left| 2rem 
.pl-3    | padding-left| 3rem 
.pl-4    | padding-left| 4rem 
&nbsp; | &nbsp; | &nbsp;
.pr-0    | padding-right| 0 
.pr-05   | padding-right| 0.5rem 
.pr-1    | padding-right| 1rem 
.pr-15   | padding-right| 1.5rem 
.pr-2    | padding-right| 2rem 
.pr-3    | padding-right| 3rem 
.pr-4    | padding-right| 4rem 
&nbsp; | &nbsp; | &nbsp;
.p-a    | position| absolute
.p-r    | position| relative
.p-s    | position| static
.p-f    | position| fixed
&nbsp; | &nbsp; | &nbsp;
.tt-u   | text-transform| uppercase 
.tt-l   | text-transform| lowercase 
.tt-n   | text-transform| none 
&nbsp; | &nbsp; | &nbsp;
.td-u   | text-decoration| underline 
.td-n   | text-decoration| none 
&nbsp; | &nbsp; | &nbsp;
.ta-c   | text-align| center 
.ta-l   | text-align| left 
.ta-r   | text-align| right 
&nbsp; | &nbsp; | &nbsp;
.ff-custom | font-family| "custom" 
&nbsp; | &nbsp; | &nbsp;
.fs-12  | font-size| 0.75rem 
.fs-14  | font-size| 0.875rem 
.fs-16  | font-size| 1rem 
.fs-18  | font-size| 1.125rem 
.fs-20  | font-size| 1.25rem 
.fs-24  | font-size| 1.5rem 
.fs-28  | font-size| 1.75rem 
.fs-32  | font-size| 2rem 
.fs-36  | font-size| 2.25rem 
.fs-40  | font-size| 2.5rem 
.fs-44  | font-size| 2.75rem 
.fs-48  | font-size| 3rem 
&nbsp; | &nbsp; | &nbsp;
.fw-100 | font-weight| 100 
.fw-200 | font-weight| 200 
.fw-300 | font-weight| 300 
.fw-400 | font-weight| 400 
.fw-500 | font-weight| 500 
.fw-600 | font-weight| 600 
.fw-700 | font-weight| 700 
.fw-800 | font-weight| 800 
.fw-900 | font-weight| 900 
&nbsp; | &nbsp; | &nbsp;
.lh-1   | line-height| 1 
.lh-11  | line-height| 1.1 
.lh-115 | line-height| 1.15 
.lh-12  | line-height| 1.2 
.lh-125 | line-height| 1.25 
.lh-13  | line-height| 1.3 
.lh-135 | line-height| 1.35 
.lh-14  | line-height| 1.4 
.lh-145 | line-height| 1.45 
.lh-15  | line-height| 1.5 
&nbsp; | &nbsp; | &nbsp;
.va-m | vertical-align| middle 
&nbsp; | &nbsp; | &nbsp;
.bs-c  | background-size| cover 
&nbsp; | &nbsp; | &nbsp;
.br-nr | background-repeat| no-repeat 
&nbsp; | &nbsp; | &nbsp;
.ba-f  | background-attachment| fixed 
.ba-s  | background-attachment| scroll 
&nbsp; | &nbsp; | &nbsp;
.bp-c     | background-position-x | center 
&nbsp; | background-position-y | center | 
&nbsp; | &nbsp; | &nbsp;
.bpx-c | background-position-x| center 
.bpx-l | background-position-x| left 
.bpx-r | background-position-x| right 
.bpy-c | background-position-y| center 
.bpy-t | background-position-y| top 
.bpy-b | background-position-y| bottom 
&nbsp; | &nbsp; | &nbsp;
.o-h | overflow | hidden 
&nbsp; | &nbsp; | &nbsp;
.v-h | visibility | hidden 
.v-v | visibility | visible 
