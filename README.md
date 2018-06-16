# shrthnd.css
* `.d-f { display:flex }` you get the idea! :smile:
* ~8kb when minified and gzipped (~2kb without breakpoints)
* responsive (6 breakpoints)

**shrthnd.css** is a utility css or atomic css framework. Basically every class has **one job and one job only**

#### whats the general idea?

read :point_down:

* [css-tricks - growing popularity of atomic css](https://css-tricks.com/growing-popularity-atomic-css/)
* [css-tricks - so you need a css library?](https://css-tricks.com/need-css-utility-library/)
* [css-tricks - lets define exactly atomic css](https://css-tricks.com/lets-define-exactly-atomic-css/)
* [David Clark - the role of utility classes in scalable css](http://davidtheclark.com/on-utility-classes/)
* [Made by many - takeaways from trying out tachyons css after ages using bem](https://madebymany.com/stories/takeaways-from-trying-out-tachyons-css-after-ages-using-bem)
* [Smashing magazine - challenging css best practices atomic approach](https://www.smashingmagazine.com/2013/10/challenging-css-best-practices-atomic-approach/)
* [Adam Wathan - css utility classes and separation of concerns](https://adamwathan.me/css-utility-classes-and-separation-of-concerns/)

other similar frameworks

* [Tachyons](http://tachyons.io/)
* [Basscss](http://basscss.com/)
* [Tailwind](https://tailwindcss.com/)
* [Shed](http://tedconf.github.io/shed-css/index.html)
* [Expressive css](http://johnpolacek.github.io/expressive-css/)


#### cheatsheet

prefix|size|example
--|--|--
&nbsp;|all screen sizes|.w-1-3 { width: 33.333% }
l_|max-width: 95em (1480px)|.l_w-1-3 { width: 33.333% }
t_|max-width: 82.5em (1320px)|.t_w-1-3 { width: 33.333% }
tp_|max-width: 62.5em (1000px)|.tp_w-1-3 { width: 33.333% }
m_|max-width: 45em (720px)|.m_w-1-3 { width: 33.333% }
mp_|max-width: 25em (400px)|.mp_w-1-3 { width: 33.333% }



class|property|value
--|--|--
.ac-c|align-content|center
.ac-fe|align-content|flex-end
.ac-fs|align-content|flex-start
.ac-s|align-content|stretch
.ac-sa|align-content|space-around
.ac-sb|align-content|space-between
.ai-b|align-items|baseline
.ai-c|align-items|center
.ai-fe|align-items|flex-end
.ai-fs|align-items|flex-start
.ai-s|align-items|stretch
.as-b|align-self|baseline
.as-c|align-self|center
.as-fe|align-self|flex-end
.as-fs|align-self|flex-start
.as-s|align-self|stretch
.ba-f|background-attachment|fixed
.ba-s|background-attachment|scroll
.bpx-c|background-position-x|center
.bpx-l|background-position-x|left
.bpx-r|background-position-x|right
.bpy-c|background-position-y|center
.bpy-t|background-position-y|top
.bpy-b|background-position-y|bottom
.br-nr|background-repeat|no-repeat
.br-r|background-repeat|repeat
.br-rx|background-repeat|repeat-x
.br-ry|background-repeat|repeat-y
.bs-a|background-size|auto
.bs-cvr|background-size|cover
.bs-cnt|background-size|contain
.bs-bb|box-sizing|border-box
.bs-cb|box-sizing|content-box
.c-b|clear|both
.d-b|display|block
.d-f|display|flex
.d-i|display|inline
.d-ib|display|inline-block
.d-if|display|inline-flex
.d-n|display|none
.f-l|float|left
.f-r|float|right
.f-n|float|none
.fd-c|flex-direction|column
.fd-cr|flex-direction|column-reverse
.fd-r|flex-direction|row
.fd-rr|flex-direction|row-reverse
.fs-12|font-size|0.75rem
.fs-14|font-size|0.875rem
.fs-16|font-size|1rem
.fs-18|font-size|1.125rem
.fs-20|font-size|1.25rem
.fs-22|font-size|1.375rem
.fs-24|font-size|1.5rem
.fs-26|font-size|1.625rem
.fs-28|font-size|1.75rem
.fs-30|font-size|1.875rem
.fs-32|font-size|2rem
.fs-34|font-size|2.125rem
.fs-36|font-size|2.25rem
.fs-38|font-size|2.375rem
.fs-40|font-size|2.5rem
.fs-42|font-size|2.625rem
.fs-44|font-size|2.75rem
.fs-46|font-size|2.875rem
.fs-48|font-size|3rem
.fs-50|font-size|3.125rem
.fs-52|font-size|3.25rem
.fs-54|font-size|3.375rem
.fs-56|font-size|3.5rem
.fs-58|font-size|3.625rem
.fs-60|font-size|3.75rem
.fs-62|font-size|3.875rem
.fs-64|font-size|4rem
.fs-i|font-style|italic
.fs-n|font-style|normal
.fw-100|font-weight|100
.fw-200|font-weight|200
.fw-300|font-weight|300
.fw-400|font-weight|400
.fw-500|font-weight|500
.fw-600|font-weight|600
.fw-700|font-weight|700
.fw-800|font-weight|800
.fw-900|font-weight|900
.fw-n|flex-wrap|nowrap
.fw-w|flex-wrap|wrap
.fw-wr|flex-wrap|wrap-reverse
.h-1|height|1rem
.h-2|height|2rem
.h-3|height|3rem
.h-4|height|4rem
.h-5|height|5rem
.h-6|height|6rem
.h-7|height|7rem
.h-8|height|8rem
.h-9|height|9rem
.h-10|height|10rem
.h-11|height|11rem
.h-12|height|12rem
.h-13|height|13rem
.h-14|height|14rem
.h-15|height|15rem
.h-16|height|16rem
.h-17|height|17rem
.h-18|height|18rem
.h-19|height|19rem
.h-20|height|20rem
.h-a|height|auto
.jc-c|justify-content|center
.jc-fe|justify-content|flex-end
.jc-fs|justify-content|flex-start
.jc-sa|justify-content|space-around
.jc-sb|justify-content|space-between
.lh-10|line-height|1
.lh-105|line-height|1.05
.lh-11|line-height|1.1
.lh-115|line-height|1.15
.lh-12|line-height|1.2
.lh-125|line-height|1.25
.lh-13|line-height|1.3
.lh-135|line-height|1.35
.lh-14|line-height|1.4
.lh-145|line-height|1.45
.lh-15|line-height|1.5
.lh-155|line-height|1.55
.lh-16|line-height|1.6
.lh-165|line-height|1.65
.lh-17|line-height|1.7
.lst-n|list-style-type|none
.lst-c|list-style-type|circle
.lst-d|list-style-type|disc
.lst-s|list-style-type|square
.lst-ll|list-style-type|lower-latin
.lst-lr|list-style-type|lower-roman
.lst-1|list-style-type|decimal
.m-0|margin|0
.m-05|margin|0.5rem
.m-1|margin|1rem
.m-15|margin|1.5rem
.m-2|margin|2rem
.m-25|margin|2.5rem
.m-3|margin|3rem
.m-35|margin|3.5rem
.m-4|margin|4rem
.m-45|margin|4.5rem
.m-5|margin|5rem
.m-a|margin|auto
.m-b-0|margin-bottom|0
.m-b-05|margin-bottom|0.5rem
.m-b-1|margin-bottom|1rem
.m-b-15|margin-bottom|1.5rem
.m-b-2|margin-bottom|2rem
.m-b-25|margin-bottom|2.5rem
.m-b-3|margin-bottom|3rem
.m-b-35|margin-bottom|3.5rem
.m-b-4|margin-bottom|4rem
.m-b-45|margin-bottom|4.5rem
.m-b-5|margin-bottom|5rem
.m-b-a|margin-bottom|auto
.m-l-0|margin-left|0
.m-l-05|margin-left|0.5rem
.m-l-1|margin-left|1rem
.m-l-15|margin-left|1.5rem
.m-l-2|margin-left|2rem
.m-l-25|margin-left|2.5rem
.m-l-3|margin-left|3rem
.m-l-35|margin-left|3.5rem
.m-l-4|margin-left|4rem
.m-l-45|margin-left|4.5rem
.m-l-5|margin-left|5rem
.m-l-a|margin-left|auto
.m-r-0|margin-right|0
.m-r-05|margin-right|0.5rem
.m-r-1|margin-right|1rem
.m-r-15|margin-right|1.5rem
.m-r-2|margin-right|2rem
.m-r-25|margin-right|2.5rem
.m-r-3|margin-right|3rem
.m-r-35|margin-right|3.5rem
.m-r-4|margin-right|4rem
.m-r-45|margin-right|4.5rem
.m-r-5|margin-right|5rem
.m-r-a|margin-right|auto
.m-t-0|margin-top|0
.m-t-05|margin-top|0.5rem
.m-t-1|margin-top|1rem
.m-t-15|margin-top|1.5rem
.m-t-2|margin-top|2rem
.m-t-25|margin-top|2.5rem
.m-t-3|margin-top|3rem
.m-t-35|margin-top|3.5rem
.m-t-4|margin-top|4rem
.m-t-45|margin-top|4.5rem
.m-t-5|margin-top|5rem
.m-t-a|margin-top|auto
.mw-45|max-width|45em
.mw-50|max-width|50em
.mw-55|max-width|55em
.mw-60|max-width|60em
.mw-65|max-width|65em
.mw-70|max-width|70em
.mw-75|max-width|75em
.mw-80|max-width|80em
.mw-85|max-width|85em
.mw-90|max-width|90em
.o-0|opacity|0
.o-01|opacity|0.1
.o-02|opacity|0.2
.o-03|opacity|0.3
.o-04|opacity|0.4
.o-05|opacity|0.5
.o-06|opacity|0.6
.o-07|opacity|0.7
.o-08|opacity|0.8
.o-09|opacity|0.9
.o-1|opacity|1
.o-a|overflow|auto
.o-h|overflow|hidden
.o-s|overflow|scroll
.o-v|overflow|visible
.p-0|padding|0
.p-05|padding|0.5rem
.p-1|padding|1rem
.p-15|padding|1.5rem
.p-2|padding|2rem
.p-25|padding|2.5rem
.p-3|padding|3rem
.p-35|padding|3.5rem
.p-4|padding|4rem
.p-45|padding|4.5rem
.p-5|padding|5rem
.p-b-0|padding-bottom|0
.p-b-05|padding-bottom|0.5rem
.p-b-1|padding-bottom|1rem
.p-b-15|padding-bottom|1.5rem
.p-b-2|padding-bottom|2rem
.p-b-25|padding-bottom|2.5rem
.p-b-3|padding-bottom|3rem
.p-b-35|padding-bottom|3.5rem
.p-b-4|padding-bottom|4rem
.p-b-45|padding-bottom|4.5rem
.p-b-5|padding-bottom|5rem
.p-l-0|padding-left|0
.p-l-05|padding-left|0.5rem
.p-l-1|padding-left|1rem
.p-l-15|padding-left|1.5rem
.p-l-2|padding-left|2rem
.p-l-25|padding-left|2.5rem
.p-l-3|padding-left|3rem
.p-l-35|padding-left|3.5rem
.p-l-4|padding-left|4rem
.p-l-45|padding-left|4.5rem
.p-l-5|padding-left|5rem
.p-r-0|padding-right|0
.p-r-05|padding-right|0.5rem
.p-r-1|padding-right|1rem
.p-r-15|padding-right|1.5rem
.p-r-2|padding-right|2rem
.p-r-25|padding-right|2.5rem
.p-r-3|padding-right|3rem
.p-r-35|padding-right|3.5rem
.p-r-4|padding-right|4rem
.p-r-45|padding-right|4.5rem
.p-r-5|padding-right|5rem
.p-t-0|padding-top|0
.p-t-05|padding-top|0.5rem
.p-t-1|padding-top|1rem
.p-t-15|padding-top|1.5rem
.p-t-2|padding-top|2rem
.p-t-25|padding-top|2.5rem
.p-t-3|padding-top|3rem
.p-t-35|padding-top|3.5rem
.p-t-4|padding-top|4rem
.p-t-45|padding-top|4.5rem
.p-t-5|padding-top|5rem
.p-r|position|relative
.p-a|position|absolute
.p-s|position|static
.ta-c|text-align|center
.ta-j|text-align|justify
.ta-l|text-align|left
.ta-r|text-align|right
.td-n|text-decoration|none
.td-u|text-decoration|underline
.tt-c|text-transform|capitalize
.tt-l|text-transform|lowercase
.tt-n|text-transform|none
.tt-u|text-transform|uppercase
.v-h|visibility|hidden
.v-v|visibility|visible
.va-bl|vertical-align|baseline
.va-b|vertical-align|bottom
.va-m|vertical-align|middle
.va-sub|vertical-align|sub
.va-sup|vertical-align|super
.va-t|vertical-align|top
.w-1-12|width|8.3333%
.w-1-6|width|16.6667%
.w-1-5|width|20%
.w-1-4|width|25%
.w-1-3|width|33.3333%
.w-2-5|width|40%
.w-5-12|width|41.6667%
.w-1-2|width|50%
.w-7-12|width|58.3333%
.w-3-5|width|60%
.w-2-3|width|66.6667%
.w-3-4|width|75%
.w-4-5|width|80%
.w-5-6|width|83.3333%
.w-11-12|width|91.6667%
.w-1-1|width|100%
.w-1|width|1rem
.w-2|width|2rem
.w-3|width|3rem
.w-4|width|4rem
.w-5|width|5rem
.w-6|width|6rem
.w-7|width|7rem
.w-8|width|8rem
.w-9|width|9rem
.w-10|width|10rem
.w-11|width|11rem
.w-12|width|12rem
.w-13|width|13rem
.w-14|width|14rem
.w-15|width|15rem
.w-16|width|16rem
.w-17|width|17rem
.w-18|width|18rem
.w-19|width|19rem
.w-20|width|20rem
.w-a|width|auto
.wb-ba|word-break|break-all
.wb-ka|word-break|keep-all
.wb-n|word-break|normal
.ws-n|white-space|normal
.ws-nw|white-space|nowrap
.ws-p|white-space|pre
.ww-bw|word-wrap|break-word
.ww-n|word-wrap|normal
