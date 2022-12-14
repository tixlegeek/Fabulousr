# Fabulousr
Fabulousing all the things.

Some time ago, i made a code that make every web page fabulous. This code was made to be stuffed in a tweet, so i'ts kinda packed.

https://twitter.com/CaptnLarzuk/status/1039698850649464832

Now you can also make everything fabulous. Just put the script in the web console, or call the file in your webPages.

```javascript
t=0,p=[],T=document.querySelectorAll("*");function H(i,P){n=Math.sin(.08*i+P),I=(n*127<<0)+128,h=I.toString(16);return!h[1]?"0"+h:h;}for(i=0;i<64;i++){p[i]="#"+H(i,0)+H(i,2)+H(i,4);}setInterval(function(){t++;Object.keys(T).map(function(k,i){T[k].style.color=p[(i+t)%64];});},10);
```



hpphckng
