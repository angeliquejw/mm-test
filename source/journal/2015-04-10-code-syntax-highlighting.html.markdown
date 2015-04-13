---
title: Code Syntax Highlighting
date: 2015-04-10
location: Baltimore
tags: scss, code
---

CodePen embed:

<p data-height="268" data-theme-id="0" data-slug-hash="BgrIs" data-default-tab="result" data-user="angeliquejw" class='codepen'>See the Pen <a href='http://codepen.io/angeliquejw/pen/BgrIs/'>Palette Viewer and Tint Generator</a> by Angelique (<a href='http://codepen.io/angeliquejw'>@angeliquejw</a>) on <a href='http://codepen.io'>CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

~~~scss
// Layout //
* {     @include box-sizing(border-box); }
.container {
    width:70%;
    margin:0 auto; }
.row div {
    float:left;
    &:last-child { float:right; }
  min-height:100px;
  padding:12px 0 0;
  width:12.5%;
  &.main { width:25%; } }
~~~