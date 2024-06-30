# cache speed tests

two experiments which show the effect of cache hits and misses in makeing your c++ run fast.

there is a detailed article on [my blog](https://www.seanbutler.net/2024/06/26/size-speed-and-caches.html) 

## accessing arrays 
in column first or row first order makes a differene in time taken
![](/cache-row-col-exp.png)

## size
accessing large arrays is slower overall
![](/cache-size-skip-image.png)
