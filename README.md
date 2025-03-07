# cinematic-mode
An ultra wide cinematic look for your websites 💕

## How to use
Save the following code as a bookmarklet:
```js
(javascript:(function(){["top:0;","bottom:0;"].forEach(p=>{let d=document.createElement("div");d.style.cssText=`position:fixed;left:0;display:block;z-index:9999;background:black;width:100%;height:40vh;${p}`,document.body.appendChild(d)})})();)
```

## Why?
Because some websites just don't know how to respect your eyeballs and instead pepper you with ginormous fucking banners.
