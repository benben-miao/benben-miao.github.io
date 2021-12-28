---
title: Tech Flower
coverWidth: 1920
coverHeight: 1080
date: 2021-12-28
tags: Animation
cover: https://benben-miao.gitee.io/image-cloud/Codepen/tech-flower.png
---

<!-- <div style="background-color: #eeeeee; width: 120px; padding:5px 20px; border-radius: 3px;">Read More</div> -->
<!-- more -->

<div class="card">
  <a href="https://benben-miao.github.io" style="text-shadow: 1px 1px 3px #888;">https://benben-miao.github.io</a>
</div>

## Tech Flower

<div class="frame">
  <iframe frameborder="0" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" allow="fullscreen; autoplay; vr" 
  style="width: 100%; height: 520px; border-radius: 10px;" 
  src="https://benben-miao.gitee.io/beautiful-code/tech-flower/dist/index.html">
  </iframe>
</div>

## Code

``` css
#btn--yp {
  box-sizing: content-box;
  position: fixed;
  z-index: 9;
  bottom: 1em;
  right: 1em;
  border: solid 1em transparent;
  width: 4.625em;
  height: 3.25em;
  background: url(https://s3-us-west-2.amazonaws.com/s.cdpn.io/2017/icon-yp.svg) 50%/cover content-box;
  font: 16px/1.25 trebuchet ms, sans-serif;
  text-indent: 200vw;
  text-shadow: none;
  filter: grayscale(1) drop-shadow(0 0 1px #e8e0e0);
  transition: 0.5s;
  white-space: nowrap;
}
#btn--yp:before {
  box-sizing: inherit;
  position: absolute;
  left: 0;
  bottom: 100%;
  margin: 1em -0.5em;
  padding: 0.5em;
  width: 100%;
  border-radius: 5px;
  background: #e8e0e0;
  color: #000;
  text-align: center;
  text-decoration: none;
  text-indent: 0vw;
  white-space: normal;
  animation: float 1s ease-in-out infinite alternate;
  content: attr(data-txt);
}
#btn--yp:hover, #btn--yp:focus {
  outline: none;
  filter: grayscale(0) drop-shadow(0 0 1px crimson);
}

@keyframes float {
  to {
    transform: translateY(0.75em);
  }
}
body {
  display: grid;
  overflow: hidden;
  margin: 0;
  height: 100vh;
  background: #262626;
}

.dot {
  --f: calc(var(--i)/var(--n-lyrs));
  --p: calc(var(--n-reps)*var(--n-dots));
  --d: calc(1.5em + var(--k)*.3125em);
  --r: calc(.65*var(--d)*var(--tan));
  grid-area: 1/1;
  place-self: center;
  padding: var(--r);
  border-radius: 50%;
  --pos:
  	rotate(calc(var(--j)/var(--p)*1turn))
  	translate(var(--d));
  transform: scale(0.5) var(--pos);
  background: hsl(calc(var(--f)*360 - 35), 85%, 65%);
  mix-blend-mode: screen;
  animation: a 1.5s ease-in-out calc((6*var(--f) + 2*var(--j)/var(--n-dots) - 19)*1.5s) infinite alternate;
}

@keyframes a {
  to {
    transform: var(--pos);
  }
}
```