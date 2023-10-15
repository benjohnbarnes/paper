# What is this?

A postscript file (.ps) to generate A4 dot-grid note paper. The postscript is hackable; you can change the parameters in it to somewhat tweak what you get for your needs.

The grid here is 2.5mm pitch with larger squares at 1cm and 6cm. Two pages are generated so that duplex printing has two side.

# The goals

* Note paper I can use in landscape or in portrait.
* A grid made of dots instead of squares, because dots can almost vanish away.
* Fully black and fairly fine dots. Easy to see, but also easy to ignore. The size here is just right for my current level of presbyopia. If you want to vary it for your eyes, there's a parameter in the file for that.
* Multiple levels of grid to make it easy to write in straight lines or draw aligned stuff, but also to flexibly break up the page such as in to main notes and side notes.
* I want the largest grid to be centred on the page.

# What's here?

* A hackable postscript file
* A pdf generated from the postscript using [ghostscript](https://www.ghostscript.com)'s `ps2pdf` tool.
