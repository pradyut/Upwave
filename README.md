Upwave
======

Upwave Challenge
by Pradyut Pokuri


1. No Javascript was used to layout or to specify sizes of elements

2. The following CSS3 Attributes were used to center horizontally and vertically:
display, box-pack, box-align

3. AngularJS was used for the select box/glyph modification functionality.

4. Media queries were used to specify different styles for <768px widths

5. To keep a fixed aspect ratio, 
	a) A block level container element wrapped our content
	b) Then a pseudo element was placed in the container with a padding top set to 100% (1:1) or 56.25% (16:9)
	c) This pushed the container's height to 100% or 56.25% (9/16) of its width
	d) The content element was positioned absolutely with top, bottom, left, right all set to 0
		which caused to to fill the space taken by the parent

