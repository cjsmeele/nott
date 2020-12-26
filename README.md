# nott

An unofficial terminal-based NOS Teletekst browser.

usage:

    nott                        → interactive mode
    nott <pagenr> [subpagenr]   → render one page

![screenshots](scr.png)

Likely you will want to have a font in your terminal that can render Teletext
mosaic characters. I strongly recommend getting the amazing and free
[unscii](http://pelulamu.net/unscii/) raster font by Viznut.

The big thing that makes nott different from other existing NOS TT browsers
(including the web-based one) is that we parse actual teletext data (i.e. all
the glorious stuff like control characters), instead of using the buggy
JSON/HTML API that other clients use.

Interactive mode keybindings:

    q      quit
    <C-o>  go back in history
    <C-i>  go forward in history
    k      go to previous page
    j      go to next page
    h      go to previous subpage
    l      go to next subpage
    !      go to the red thingy
    @      go to the green thingy
    #      go to the yellow thingy
    $      go to the cyan thingy
    0-9    enter a 3-digit page number
    H      go home (100)
