# What is this?

A postscript file (.ps) to generate A4 dot-grid note paper. 

The grid is 2.5mm pitch with larger squares at 1cm (4x4 dots) and 6cm (24x24 dots). The file has two identical pages and is designed for a duplex printer providing double sided output.

The postscript is hackable; you can change the parameters in it to somewhat tweak what you get for your needs. If you don't like the factors of 2 and 3, you can change the grid to have decimal factors instead.

# Goals.

* Note paper I can use in landscape or in portrait.
* A grid made of dots instead of squares. Dots are really easy to ignore, but you can also find them when you want to see them. They get out of your way but still allow very precise placement if you want that.
* Fully black and really fine dots. Visible but ignorable. The size here is just right for my current level of presbyopia. If you want to vary it for your eyes, there's a parameter in the file for that.
* Multiple levels of grid to make it easy to write in straight lines or draw aligned stuff, but also to flexibly break up the page such as in to an area for main notes and other side notes or diagrams.
* The largest grid is centred on the page.

# What's here?

* A hackable postscript file.
* A pdf generated from the postscript using [ghostscript](https://www.ghostscript.com)'s `ps2pdf` tool.
