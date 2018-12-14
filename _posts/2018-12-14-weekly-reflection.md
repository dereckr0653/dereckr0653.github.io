---
layout: post
title: "Dereck Rampersad,"
date: 2018-12-14
---
This week we have made our flags learning how even though it seems like a simle task 
![FlagImage](/images/flagv2.png)
``(define Width 300)
(define Height 200)
(define tri(rotate 30(triangle 200 "solid""blue")))
tri
(define flag(rectangle Width Height "solid""white"))
flag
(define Star (star 40 "solid""white"))
Star
(define strip(rectangle Width 40 "solid""red"))
(define stepone(put-image strip 150 180 flag))
stepone
(define steptwo(put-image strip 150 100 stepone))
steptwo
(define stepthree(put-image strip 150 20 steptwo))
stepthree
(define Boss(put-image Star 50 90 tri))
Boss
(define last-step(put-image Boss 85 100 stepthree))
last-step```
