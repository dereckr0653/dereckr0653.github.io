---
layout: post
title: "Game-Reflection "
date: 2019-03-08
---
Video Game Submission Sheet

Your name:Dereck Rampersad

Shared link to your game:https://www.wescheme.org/view?publicId=937oSfxCQA

Game Title: Gold digger
Describe your game, characters and setting: 
Their is the player as shovel knight and he is trying to get his gold but in the deep dark caves there's someone else trying to get his gold so he can have it.

Choose one of either the onscreen?, update-player, distance, or collide? functions. Copy and paste the entire function including contract, purpose statement, examples and definition. 

; safe-left? : Number -> Boolean
; Is the character visible on the left side of the screen?

; Write an EXAMPLE that makes this true, and one that makes this false:

(EXAMPLE (safe-left? 100) (> 100 -50))

(EXAMPLE (safe-left? -200) (> -200 -50))

(define (safe-left? x) (> x -50))


Describe every line in the pasted code above.
1)The first line is the contract of the function and these are the values in the code that we are going to use to make sure the character is still there on left side of screen.The contract is telling us how we need a number to then make a boolean to see if the position that the character is at is true or not giving the x coordinate to make sure that it is true.
2)This the question we are solving in the game.We do this to make sure we know what the function is for like making a simple question for a complex code that in large sums we can not understand.

3)This tells us to make a function that could be used and the examples we could use and we could not use to make sure we don’t use that one.

4 and 5)These are the values i could use in the game also making one that makes the safe-left? True or false.

6)This is what the game uses uses to know if we can still see the game character on the left side of the screen.
Describe the role of the function in the video game program.
This function is to make sure that we can still see the game objects and the code further is able to bring them back on screen we the object gets off the screen.This also helps us know where the eneime should spawn as also the target in the game
