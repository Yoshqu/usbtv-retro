# About

This is extension for linux kernel module usbtv for Fushicai USBTV007, enabling doulbe frame rate progressive video.
This format is popular on some older computers like Atari 8-bit.

## Features

1) Avaible on "S-Video Retro" input.
2) Every half frame is sent to user space - doubling frame rate.
3) Black lines are cloned from neighbours lines.
4) Vertical resolution stays the same, input can be switched during playback.

## Demo

[Side by side comparison](https://www.youtube.com/watch?v=yuwyNnCaOAk)

## TODO

* return proper v4l descriptor
