---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## Flag of _United Kingdom_ by _Mouhamed Tounkara_

## Describe your program

-  I design a united kingdom flag  
-   I excpet a 3 becase i attemped the profisional level flag and I didn't finish.


## Current output

-   Insert an image that your program currently produces. _then delete this instruction_

* * *
![Flag](/images/flagv4.png)
* * *

## Describe your process.


The strategies that i did was is defining the shapes that for the flag and i can put the image into the base to create the United Kingdom flag. I had a little help from my peers when I have a question for them. like for example my question was how to put image because in the past It was not my strong suit but I over come it and is half done. when I looked back at my notes it all become clear and found a way to do my work. I thinking can be better than asking for helpl if you have your notebook aside of you.



## Explain your code.


The argument in the code are all shapes that I used to put thoese images to put into a United kingdom flag. The code that i did was mostly defining  all the shapes because i wanted to do part by part.
-   Tell us how it functions independently and within the whole program _then delete this instruction_

* * *

```
(define LINE(rectangle 650 68 "solid" "crimson"))
(define left (rotate 155 (rectangle 600 15 "solid" "crimson")))
(define right (rotate 25 ( rectangle 600 15 "solid" "crimson")))
(define down (rotate 291 (rectangle 15 580 "solid" "crimson" )))
(define dl (rotate 65 (rectangle 15 600 "solid" "crimson")))
(define ball(rectangle 530 15 "solid" "white"))
(define all(rotate 90(rectangle 230 15 "solid" "white")))
(define dell(rotate 90(rectangle 230 15 "solid" "white")))

(define JAY (put-image LINE 300 150 BASE))
(define MAY (put-image UP 300 150 JAY))
(define LAYS (put-image left 0 300 MAY))
 (define BAY (put-image right 600 300 LAYS))
(define AY(put-image down 0 20 BAY))
(define EN (put-image dl 600 0 AY))
(define tall(put-image ball 0 108 EN ))
(define lal(put-image all 258 0 tall))
(define gall(put-image dell 344 0 lal))
(define hall(put-image laugh 500 108 gall))
```

* * *

-   Explain the code you posted by telling us about each argument.
-   Then tell us how your code section fits into the whole.
 
<!--- Delete this comment and add your writing -->


## Program code

```
Insert entire program here _then delete this instruction_
```
