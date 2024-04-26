# The Ploopy Adept Trackball

![The Ploopy Adept Trackball](adept.jpg)

By some stroke of luck, you've made your way here. The Ploopy Adept Trackball. Your life will never be the same.

This repository contains all of the design and production files necessary to make a Ploopy Adept Trackball. We've also included some kick-ass documentation in the Wiki on how to get it made, assemble it, and program it.

What are you waiting for? Your new life awaits.

## QMK?!

Kits bought from the [Ploopy store](https://ploopy.co/product-category/trackball/adept/) come with QMK and VIA preloaded. Check out the Wiki for instructions on how to load new firmware onto your device. (It's super easy!)

The firmware hex file that ships with all Adepts is included in this repository as well, as [`ploopyco_madromys_rev1_001_via_mom_semaphore_4.uf2`](https://github.com/ploopyco/adept-trackball/blob/master/firmwares/drag_scroll_click_and_hold/ploopyco_madromys_rev1_001_via_mom_semaphore_4.uf2). This firmware features a "click and hold" Drag Scroll with a medium sensitivity.

It defaults to a drag scroll of "click and hold," which means that if you click the Drag Scroll button and move the ball, the screen under the cursor will scroll in the direction you roll. The [sempaphore_X](), or "sensitivity" of the scroll is set to **4** in this firmware, which requires a _modest amount_ of movement to scroll. A lower sensitivity means you move the ball less to scroll; a higher one means you move it more.

By default, **Drag Scroll** is the third button on the top row, counting from the left).



## Under what license is this released?

As per QMK's licensing requirements, the firmware for the Ploopy Adept Trackball is released under GPLv3. Hardware design files, including electronics and mechanical files, are released under OHL CERN v2-S. Check the respective directories for full license text.
