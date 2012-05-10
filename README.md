<h1> pxl paintr </h1> 

.it is small program for creating 2d [pixel art](http://en.wikipedia.org/wiki/Pixel_art)

.it is obviously NOT a fully fledged graphics program so don't expect much

.to see the final output(slightly scaled) in realtime, toggle the preview by pressing 'p', toggle the assistive grid with 'h'

.the status of anything in use is shown in the window header/caption whatever.

.unsaved art is denoted with an asterisk (*) at the end of the filename, once saved it will be removed

.images are saved as .pngs so alpha channel is preserved and you can easily add backgrounds to them

.when u save an image, it saves it as a 256 * 256 image so as to preserve the retro look and make choice avatars

![pxlee](https://github.com/iKlsR/pxl-paintr/raw/master/screenshots/pxlee.png)

<h1> technical </h1>

.pxl painter is (NOT) ide friendly unless you know how to pass arguments to it (from) your ide of choice, run it from the command line

.i removed all arguments except the filename so to start pxl paintr pass in the name of the file at runtime ie. new.png

.to further learn my pygame knowledge this was rewritten from scratch with the original guide as referene of course

.if you are a beginner to pygame DO NOT cross reference this rewrite with the [original guideline](http://github.com/cheery/pygame_tutorial) as variable names may differ and 
the project layout varies too, the less confusion, the better

.this was not written with classes or modules so it can be easier dissected by a pygame beginner

.to fully understand this program even tho its still quite simple, checkout the official [pygame docs](http://pygame.org) and do some night reading
on [python](http://docs.python.org) too. knowing what tuples, slicing, functions, loops and dictionaries are might prove helpful ;)

.i have tested and used this but it is quite possible it breaks or it needs something else, i have tried to keep it
~as minimal as possible. please report any [issues to the issues page](https://github.com/iKlsR/pxl-paintr/issues) or fork your own branch and play with the code

![default](https://github.com/iKlsR/pxl-paintr/raw/master/screenshots/default.PNG "default")

<h1> installation </h1>

what?

.if u somehow don't know by now, pixel painter uses the python programming language and pygame the graphics library as its graphics engine and event handler

.compiled and tested on win7 x64 with x64 python2.6 and [x64 pygame 1.9.2](http://www.lfd.uci.edu/~gohlke/pythonlibs/#pygame)

![pxled](https://github.com/iKlsR/pxl-paintr/raw/master/screenshots/pxled.PNG "pxled")

how to use
.open a prompt or terminal, on Windows make sure python is in your path, type python to check, if it returns:
'python' is not recognized as an internal or external command,
operable program or batch file. 

~python is NOT in your path. to add type set Path=C:\"python version";%PATH% 
~python version being the version you have without the quotes "". pxl paintr was written in Python 2.6

.at the prompt >
~type python pp.py "filename"
.you do not need to add the extension as pxl paintr adds it for you

.run the program

![gridified](https://github.com/iKlsR/pxl-paintr/raw/master/screenshots/grid_on.PNG "gridified")

<h1> keys: </h1>

mouse1(left click) - click to add points, hold to draw

mouse2(middle clikc) - N/A

mouse3(right click) - click points to delete, hold to delete

h - to toggle the assist grid on/off

p - to toggle the small preview (perspective helps)

f -  to clear canvas completely

1 - 9: to select colors as they are shown at the bottom in the palette

esc - to quit

w - to save

![NYAN](https://github.com/iKlsR/pxl-paintr/raw/master/screenshots/nyan.PNG "NYAN")

</h1> todo </h1>

.implement more arguments such as canvas size, bits, grid size, brush size 
(some of these are in the guideline, i chose to leave them out as i don't quite understand them as yet) etc

.scale the grid in realtime with limits of course still constraining preview to its same size

.read file, possibly a custom writeto format or maybe not. -ω-

.dialogs?

.BETTER colors, improved palette, able to adjust alpha <- see changes in realtime.

.fill tool, layers (hrmm custom writeto format X|)

.brush sizes! instead of zooming canvas. sizes will be incremented and decremted by 8, erase brush too.

.what use is any program without a few undos? redos etc. ;)

.specify symmetry to faster create art that is identical on both sides

.ability to grab and move objects or easier on me. layers!! (custom writeto format decided then.)

.convert to portable executable for windows users with the lovely py2exe

![crap](https://github.com/iKlsR/pxl-paintr/raw/master/screenshots/prev_on.PNG "i did not draw this ;)")

<h1> misc </h1>
.i love creating pixel art (the 90's is so nostalgic) and my friends do too, they love pxl paintr, 
if you somehow use this program to do any work or art, i would be delighted to hear.

.if on irc (freenode.net) and need any help, the #python and #pygame channel are always up (don't ask to ask.. just ask)

.thanks to [Cheery](http://github.com/cheery) for a few hints, project inspiration and a solid project skeletion


