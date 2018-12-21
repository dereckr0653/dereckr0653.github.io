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
Lines one and two explain the outline of the flag as all of the details will go in bewteen these positions.In line 4 describes the triangle for the flag as we will need to then put it on the flag but i defined it so i can use it later with out writeing it.Line 8 and 9 were fot the star in the flag.The last shape i needed to make was the line and all i need to do then is combine them.Lines 15-13 are me combining the lines on to the flag and that is important because if you would have put the triangle and satr first the lines of the flag would have overlaped all the other shapes.You can also see that i define the putimage because put-image funcitions can only use two image data so that means you can not just keep adding shapes i had to define them to make that put-image an image data as one shape.The funcitions explain to the computerwhat data is needed like the defining in the code as it works independently but when you put them togeter able to make a flag out of all the data given to the computer.


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
(define boss(star 50 "solid" "white"))
;I made the shapes 
(define one(put-image strip 150 180 flag))
one
(define two(put-image strip 150 100 one))
```

* * *

-   Explain the code you posted by telling us about each argument.
Lines one and two explain the outline of the flag as all of the details will go in bewteen these positions.In line 4 describes the triangle for the flag as we will need to then put it on the flag but i defined it so i can use it later with out writeing it.Line 8 and 9 were fot the star in the flag.The last shape i needed to make was the line and all i need to do then is combine them.Lines 15-13 are me combining the lines on to the flag and that is important because if you would have put the triangle and satr first the lines of the flag would have overlaped all the other shapes.You can also see that i define the putimage because put-image funcitions can only use two image data so that means you can not just keep adding shapes i had to define them to make that put-image an image data as one shape.All the data given is able to make the flag i am making and the lables show how the program as a whole is all important as without one of those defines the flag would not be possiable as we use all of our defines to make the whole flag as even though they are different data still area whole.
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
