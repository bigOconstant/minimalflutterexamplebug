# myapp

A minimal Flutter project demonstrating keyboard bugs on  arm64 linux.

Video demonstration here https://files.catbox.moe/zp05ef.mp4

## Description

I installed flutter on the PinePhone Pro and compiled a app with two text fields. The keyboard does not immediately pop up like other wayland apps when entering into a text field. Instead I have to click around a couple times. When the keyboard finally appears text is prepended rather than appended so if you type a word it comes out backwords.

For example typing `hello` will display `olleh`
