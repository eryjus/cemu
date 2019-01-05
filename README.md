Century Emulator
---


The Century Emulator (cemu) is born out of the necessity of having a proper emulator for debugging.  This emulator is designed to emulate the Raspberry Pi 3B (rpi3b).

**Build System**

I typically use a mix of `make` and `tup` as my build system.  I use `tup` to actually perform the build and `make` to take care of all the additional (more complicated) things that I might want to execute.  By default, `make` will merely call `tup`.

You can get `tup` from http://gittup.org/tup/.  Once you have `tup` built and in the `$PATH`, you simply run `tup init` from the root of this project before you `make`.

**My Journal**

As with all my projects, I will be keeping a JOURNAL.md of my progress and my trials and to help document the problems and decisions I encounter.  There are a few reasons I keep this journal with each project (as opposed to one journal for everything or putting the comments in the code):
1. I sometimes need to revisit my own thinking and refer back to the journal.
1. If I put this level of documentation into the code, there would be more comments than code and the actual code would get lost.
1. I want to be able to keep track of times when I change my mind and the source needs to represent current state, but a bunch of bad decisions.
1. I want to be able to present this journal for others to learn from.

