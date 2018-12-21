---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## Flag of Prico Rico
by Dereck Rampersad

## Describe your program

-   I designed a flag for Prico Rico
-   I think i will receive a 2 or 3 on this assignment

<!--- Delete this comment and add your writing -->

## Current output



* * *
![Flag](/images/flag-final.png)
* * *

## Describe your process.

-   What questions, strategies, help from peers or teacher, or thinking got you to this point? 

I first looked at the height and width of the flag as these were the infomation that i needed to make it.I nade all the shapes before i put them all together because i wanted to make a defition for all of them so that you would not have to write the numbers and will know the tool that i was using as there were quite a few shapes to make and giving them names made it easyier for me to put them down.This also helped people understand my code because i gave them names so when i and other people read my code that people would not get confused.I think i got how to make neat code and tha is important becasue it is like hand writing and if you can not understand even your own hand writing how will people interpert and what it means.


## Explain your code.

-   Choose a significant part of your program (15 lines max) and paste it below. Do not insert your entire program here. _then delete this instruction_
-   Explain each argument in the code section. _then delete this instruction_
-   Tell us how it functions independently and within the whole program _then delete this instruction_


* * *

```
(define Width 300)
(define Height 200)
;I did these to tell me the height and width of the flag
(define tri(rotate 30(triangle 200 "solid""blue")))
tri
(define flag(rectangle Width Height "solid""white"))
flag
(define starPiece (star 40 "solid""white"))
starPiece
(define strip(rectangle Width 40 "solid""red"))
(define boss(star 50 "solid" "black"))
;I made the shapes 
(define one(put-image strip 150 180 flag))
one
(define two(put-image strip 150 100 one))
```

* * *

-   Explain the code you posted by telling us about each argument.
-   Then tell us how your code section fits into the whole.
 
<!--- Delete this comment and add your writing -->


## Program code

```
(define Width 300)
(define Height 200)
;I did these to tell me the height and width of the flag
(define tri(rotate 30(triangle 200 "solid""blue")))
tri
(define flag(rectangle Width Height "solid""white"))
flag
(define starPiece (star 40 "solid""white"))
starPiece
(define strip(rectangle Width 40 "solid""red"))
(define boss(star 50 "solid" "black"))
;I made the shapes 
(define one(put-image strip 150 180 flag))
one
(define two(put-image strip 150 100 one))
two
(define three(put-image strip 150 20 two))
three
(define combine(put-image starPiece 50 90 tri))
combine
(define four(put-image combine 85 100 three))
four


```
