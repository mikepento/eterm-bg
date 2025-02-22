# eterm-bg
Collection of scaled and tiled backgrounds for the Eterm terminal.

Eterm Background Images
=======================

The default themes for Eterm are designed to select a background image
at random.  In order for this to work, some sort of mechanism had to
be created for the creation and maintenance of a set of backgrounds,
both tileable and scaled.  This mechanism had to allow for easy
selection of the random image as well as easy alterations to the
collection.

So here's how it works.  Underneath this directory (bg/) you'll find
two subdirectories:  tile and scale.  These directories contain tiled
and scaled background images, respectively.  When "make install" is
run, these images are automatically installed in directories with the
same names underneath <prefix>/share/Eterm/pix/.  Once these images
have been copied into place, the Etbg_update_list utility is run to
create or update the pixmaps.list file, a text file containing the
master list of images and their geometries, from which Eterm will
choose an image at random.

If you wish to add or remove images from the collection, first cd into
<prefix>/share/Eterm/pix/.  Once there, remove any unwanted images
from the tile/ and/or scale/ directories.  Then copy any images you
want into either the tile/ or scale/ directory, depending on whether
you want Eterm to tile the image or scale it.  When you have finished
adding and/or removing images, run the Etbg_update_list script again
(it is found in <prefix>/bin/) to update the list.

You may have as many or as few images in your collection as you like;
just remember to re-run the Etbg_update_list script after completing
each set of changes.  Note that if you have fewer than 2 images in the
collection, you should edit the theme.cfg file for your theme to
deactivate the random image selection.  (If you neglect to do this,
you may receive error messages from Eterm, but it will continue to
function.)


Disclaimer
----------

Most images distributed with Eterm and its supplementary backgrounds
collection were contributed by their respective authors.  In fact,
most of these images are original work by me.  Two images have unknown
copyright but are believed to be in the public domain.

However, should any person who can provide proof of ownership of any
of these pictures object to their inclusion, they will be IMMEDIATELY
withdrawn.  No copyright infringement is intended.  Inclusion here
should be taken as a compliment. :-)


Contributors
------------

The following contributions have been made by their authors.  Thanks
to all who have contributed.  If one of your images is in this
collection, but it isn't reflected here, please e-mail me
(mej@eterm.org) so I can correct the omission.  Note that some of
these images are included with the supplemental backgrounds
collection, others with the Eterm distribution.

All images are copyright their respective authors and are included
here by permission.

Neopolis-horizon.jpg            Joe Colburn <joe@nodomain.com>
acid_chess.png                  Michael Jennings <mej@eterm.org>
a_distant_star.png              Michael Jennings <mej@eterm.org>
alpha_centauri.png              Michael Jennings <mej@eterm.org>
army_brat.png                   Michael Jennings <mej@eterm.org>
bubbly1.jpg                     Tal Danzig <tal@libranet.com>
bubbly2.jpg                     Tal Danzig <tal@libranet.com>
bubbly3.jpg                     Tal Danzig <tal@libranet.com>
bubbly4.jpg                     Tal Danzig <tal@libranet.com>
circuit.jpg                     Public Domain
cold_steel.png                  Michael Jennings <mej@eterm.org>
conch.png                       Michael Jennings <mej@eterm.org>
confusion.jpg                   Tal Danzig <tal@libranet.com>
connect_the_dots.png            Michael Jennings <mej@eterm.org>
cyber_bg.jpg                    Joe Colburn <joe@nodomain.com>
darkness.png                    Michael Jennings <mej@eterm.org>
day-night.jpg                   Ted Zlatanov <tzz@lifelogs.com>
falling.png                     Michael Jennings <mej@eterm.org>
fascination.png                 Michael Jennings <mej@eterm.org>
firestorm.png                   Michael Jennings <mej@eterm.org>
for_a_moment.png                Michael Jennings <mej@eterm.org>
graffiti.png                    Michael Jennings <mej@eterm.org>
gray_matter.png                 Michael Jennings <mej@eterm.org>
lightning_crashes.png           Michael Jennings <mej@eterm.org>
marbles.png                     Michael Jennings <mej@eterm.org>
midnight_sky.png                Michael Jennings <mej@eterm.org>
moody_blues.png                 Michael Jennings <mej@eterm.org>
murky_depths.png                Michael Jennings <mej@eterm.org>
oil_on_canvas.png               Michael Jennings <mej@eterm.org>
pebble_beach.png                Michael Jennings <mej@eterm.org>
ping-pong.png                   Michael Jennings <mej@eterm.org>
plasma.png                      Michael Jennings <mej@eterm.org>
pulse.png                       Michael Jennings <mej@eterm.org>
rolling_meadows.png             Michael Jennings <mej@eterm.org>
sailors_delight.png             Michael Jennings <mej@eterm.org>
shades_of_being.png             Michael Jennings <mej@eterm.org>
shale.jpg                       Public Domain
shattered_windows.png           Michael Jennings <mej@eterm.org>
shock_and_awe.png               Michael Jennings <mej@eterm.org>
sitting_in_acid.png             Michael Jennings <mej@eterm.org>
spring_rain.png                 Michael Jennings <mej@eterm.org>
stained_glass.png               Michael Jennings <mej@eterm.org>
tales_of_earthsea.png           Michael Jennings <mej@eterm.org>
tangled_web.png                 Michael Jennings <mej@eterm.org>
the_wall.png                    Michael Jennings <mej@eterm.org>
trees_are_leafy.png             Michael Jennings <mej@eterm.org>
veins_2.png                     Michael Jennings <mej@eterm.org>
veins.png                       Michael Jennings <mej@eterm.org>
violetta.png                    Michael Jennings <mej@eterm.org>
wasteland.jpg                   Brian McFee <keebler@sandwich.net>
water_into_wine.png             Michael Jennings <mej@eterm.org>
wintertree.jpg                  Ted Zlatanov <tzz@lifelogs.com>
wormhole.png                    Michael Jennings <mej@eterm.org>
woven_memories.png              Michael Jennings <mej@eterm.org>
