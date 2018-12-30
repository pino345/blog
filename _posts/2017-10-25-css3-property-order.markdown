---
layout: post
title:  "CSS3"
crawlertitle: "감감묨소식"
summary: "CSS 속성 작성 순서"
date:   2017-10-25 17:09:47 +0700
categories: posts
tags: 'CSS3'
author: 명아
---
css 속성 선언 순서

기준     |순서  |속성        | 관련 속성 
--------|-----|-----------|------------
layout  |1    | display  | +visibility
        |2    | overflow | 
        |3    | float    | +clear
        |4    | position | +z-index
        |5    | width & height   | 
        |6    | margin & padding |
테두리    |7    | border   |
배경     |8    | background|
폰트     |9    | font     | +color/ letter-spacing/ text-align/ vertical-align/ white-space...
동작     |10   | animation| +transfrom/ transition/ marquee...
기타     |11   | etc      |  나머지는 순서 무관
 
