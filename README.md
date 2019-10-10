ClearSansAlternateGlyphs
========================

SVG files for glyphs intended to work with Intel Clear Sans.

Intel Clear Sans is my body copy font of choice for most things ePub but it is
lacking small-caps variant.

My intention is to create small-caps variants for the Regular and Bold weights
with both the Upright and Italic variants.

There also are some picture glyphs I often use with CSS and ::before with
hyperlinks to give a visual indication about the link. I will be adding those
too where the existing picture glyphs in Intel Sans do not suit my needs.

The asterik character will be lowered and possibly borrowed from Fira Sans so
that it is centered nicely between two lower-case small-caps letters.

Only the SVG files will be here, ready for import into FontForge. I will not
be hosting font files.

This will take a while to complete. Many glyphs need side-bearing and other
metric adjustments. Especially with Italic and BoldItalic.

Remember to auto-hint and kern if importing these into a font.

Descriptions of the glyphs I am creating are below. These are being created for
my own personal needs but they may be of benefit to others.


U+002A Alternate
----------------

This glyph is actually borrowed from Fira Sans but lowered so that it is
vertically centered in small-cap height.

It exists for typing the words Un*x or *nix in small-caps.


U+0061-007A Small-Caps
----------------------

Right now only 3 glyphs in this range have been created, 23 more to go (possibly
more if I ever need small-caps ligatures or variants like Ñ)

Small-Caps created from the Clear Sans upper case. Each glyph was redrawn,
it is not just a scale/resize. The small-caps height is just a tad taller than
the x-height. Strokes are proportionally a tad thicker and glyphs are
proportionally a tad wider than the upper case letters when scaled to the same
height.


U+2150-215F 'Vulgar Fractions'
------------------------------

Intel Clear Sans already has a few of these (in addition to the Latin 1 vulgar
fractions U+00BC-U+00BE) but it seems to only have the vulgar fractions that are
part of WGL4. I will be creating glyphs for the vulgar fractions that it is
missing as I use them (e.g. U+2153 and U+2154 for a third and two thirds
respectively).


U+23ED 'BLACK RIGHT-POINTING DOUBLE TRIANGLE WITH VERTICAL BAR' Alternate
-------------------------------------------------------------------------

In ePub I use this glyph as a visual indication to the user for hyperlinks the
use can use to skip past a block of content they may not immediately want to
consume. The glyph was drawn by me to small-caps height so that it looks good in
body copy, with most fonts it is designed for A/V interface control and it looks
out of place in body copy.


U+25CF 'BLACK CIRCLE' Alternate
-------------------------------

This is the Clear Sans glyph but centered to the Caps Height (actual caps, not
small caps). Italic variants may need horizontal adjustment.

In ePub when the user prefers bold over italics, I use this glyph with CSS and
h3::before to allow h3 headings to be visually distinguished from other bold
text of similar height.


U+267F 'WHEELCHAIR SYMBOL' Alternate
------------------------------------

This glyph really *needs* it's own Unicode codepoint.

The manual wheelchair glyph is frequently abused as a glyph in association with
accessibility (a11y) probably as a result of the appropriate use of the glyph
with handicapped parking and wheelchair accessible restrooms.

Accessibility goes beyond physical mobility issues and when addressing
accessible content I do not want to use a glyph that focuses on the disability
but I would rather use a glyph that focuses on the humanity of those who have
barriers to content access, whether they are physical disabilities or not.

The glyph is my own creation but is heavily based on a glyph that is widely used
with the accessibility community. I do not understand why it does not have its
own Unicode codepoint.

I use this glyph in ePub to indicate when a section deals with content
accessibility issues.

The same glyph is used for Regular, Italic, Bold, and BoldItalic. It is designed
to have same vertical metrics as an upper case O so that it aligns nicely with
both headings and body copy.


U+1F310 'GLOBE WITH MERIDIANS' Alternate
----------------------------------------

Clear Sans does not have this glyph. My version is much like the globe with
meridians you see in other fonts, but the center has a wifi symbol.

In ePub when a hyperlink requires an Internet connection and a browser, I use
this glyph the let the user know so that the user does not follow the link if
they do not have a current Internet connection or wish to have a browser launch.

The same glyph is used for Regular, Italic, Bold, and Bold Italic.


U+1F41A 'SPIRAL SHELL' Alternate
--------------------------------

Clear Sans does not have this glyph. My version will not be a 'spiral' shell but
will be heavily based on this shell:

    https://pixabay.com/vectors/seashell-shell-ocean-beach-sea-1531572/

In ePub when I have a link to shell utilities, I will use this glyph as a
visual indication to the user that the link is to shell utilities that I
maintain.


U+1F4D3 'NOTEBOOK' Alternate
----------------------------

Clear Sans does not have this glyph. My version uses a book with a question mark
on the cover. My use *probably* should have a different Unicode codepoint but
one does not exist (that I could find) for my use, so I used 1F4D3 so that those
reading my ePub books with publisher fonts disabled will still get a glyph that
is not too far off the mark.

In ePub when an acronym or term is used that is not central to understanding the
section but which the user may want defined, I will *sometimes* define it in the
glossary and link to it. I use this glyph as a visual indication with the link
so that the user knows it is a link within the document to the definition.

The book outline is my own but I have seen the same concept used elsewhere and I
liked it. The question mark is from Clear Sans Bold and Clear Sans Bold Italic.

I am planning to redraw this glyph to make the stroke for the book outline a tad
thicker, which will reduce the vertical space for the question mark so I will
probably remove the bottom dot.

The glyph height is from baseline to caps height so it looks good in body copy.


U+1F4D7 'GREEN BOOK' Alternate
------------------------------

Clear Sans does not have this glyph. My version (not yet created) will be much
like my version of U+1F4D3 but will have an ePub logo on it.

I will use it to indicate a link is to an ePub book.
