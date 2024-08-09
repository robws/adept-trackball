# The Ploopy Adept Trackball

![The Ploopy Adept Trackball](adept.jpg)

By some stroke of luck, you've made your way here. The Ploopy Adept Trackball. Your life will never be the same.

This repository contains all of the design and production files necessary to make a Ploopy Adept Trackball. We've also included some kick-ass documentation in the Wiki on how to get it made, assemble it, and program it.

What are you waiting for? Your new life awaits.

## Getting started

You can plug the Adept into your computer and start using it without doing anything else!

### Built in firmware has "click to hold" drag scroll

The Adept ships with [this firmware](https://github.com/ploopyco/adept-trackball/blob/master/firmwares/drag_scroll_click_and_hold/ploopyco_madromys_rev1_001_via_mom_semaphore_4.uf2), included in this repo. It features a "click and hold" Drag Scroll with a [sempaphore_X](), or "sensitivity" of 4, meaning that if you hold the Drag Scroll button and move the ball, the screen under the cursor will scroll in that direction, and it takes a _modest_ amount of ball movement to do so. A lower sensitivity means you move the ball less to scroll; a higher one means you move it more.

By default, **Drag Scroll** is the third button on the top row, counting from the left).



## QMK?!

Kits bought from the [Ploopy store](https://ploopy.co/product-category/trackball/adept/) come with QMK and VIA preloaded. [Check out the Wiki](https://github.com/ploopyco/adept-trackball/wiki) for instructions on how to load new firmware onto your device. (It's super easy!)




## Under what license is this released?

As per QMK's licensing requirements, the firmware for the Ploopy Adept Trackball is released under GPLv3. Hardware design files, including electronics and mechanical files, are released under OHL CERN v2-S. Check the respective directories for full license text.
