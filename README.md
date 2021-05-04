# M1 - SwipeyKey
Mini-Project 1: TinyType for ECE 188 Applied &amp; Interactive Machine Learning

## Project Specifications
Your task is to employ a user-centered design approach to create a keyboard design on a small input area that still allows you to type as fast as possible.

* You can design the keyboard for either desktop or mobile devices or both.

* Accordingly, you can only use pointing-based inputs, e.g., mouse, trackpad, touch screen. No keyboard. No speech recognition.

* The active input areas on the screen (i.e., the part of screen that responds to input) can be any shapes but should be no larger than 256 x 256 pixels

* The input should cover at least the English alphabet (lower or upper case), space, and delete

* For typing, you should use phrases from this standard [testing set](https://drive.google.com/file/d/1xzjQp5QPM7syozcr9GXpFLVU-ifTQECc/view)


## My Design: SwipeyKey
Using two 180x180 pixel squares, I've divided a normal QWERTY keyboard into two halves- a left and a right side. As 180x180 pixels is a small space, I decided to fit only 9 (3x3) keys into each square, along with a spacebar on the bottom. 

Clearly, one cannot access all 26 alphabetical keys in such a space. Thus, the main feature of SwipeyKey, as hinted by the name, is swiping! Swiping allows for the user to control both halves of the keyboard, shifting the "window" of 9, 3x3 keys that are being displayed.

Though the design works on desktop, SwipeyKey is mainly intended for mobile!

## Resources used
[Swiper.js](https://swiperjs.com/)

[Dcode's Virtual Keyboard Tutorial](https://www.youtube.com/watch?v=N3cq0BHDMOY&ab_channel=dcode)


# M2 - EmojiType
Mini-Project 2: EmojiType for ECE 188 Applied &amp; Interactive Machine Learning

## Project Specifications
Your task is to build on M1 and add emoji entry by gesture.

* All the input requirements remain the same as M0 (e.g., pointing only, limited input area—please refer back to the M0 doc);

* Design a suite of pointing-based gestures to input at least five emojis, e.g., drawing a smily-shaped arc will input "😊"; 

* Implement a gesture recognizer that works for your design and integrate it into M1 as a working prototype;

## My EmojiKey:
### Emojis Recognized:
* 🌊
* 💪
* 🔥
* 🍜
* 💙

## Resources used
[$1 Unistroke Recognizer](http://depts.washington.edu/acelab/proj/dollar/index.html)

[$1 Unistroke JS Wrapper Library](https://github.com/nok/onedollar-unistroke-coffee)