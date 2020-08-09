# Fade Carousel

This builds on the [Slide Carousel](https://github.com/teochewthunder/slidecarousel). Instead of having content slide from left to right (or vice versa), now we want the content to fade in and out of view.

## Changes to code
- Now all mentions of "slide" are changed to "fade". This improves the naming convention since it's less confusing and puts us in the right mental state to tackle this problem.
- The content wrapper is now 100% width of the viewport instead of 200%.
- The content divs within are now 100% with of the parent instead of 50%.
- There is no sliding left and right. Instead, the transitions are carried  out on the content divs themselves, with the previous one fading out of view and the new one fading in.
