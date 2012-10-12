Crafty Typewriter
=================

Typewriter plugin for the Crafty JavaScript game library.

Writes out a string of text one character at a time in the style of a typewriter.

Particularly suited for use alongside fonts such as GNUTypewriter: http://openfontlibrary.org/en/font/gnutypewriter


Example
-------

	Crafty.audio.add("typekey", [
		"audio/effects/typewriter_key.ogg"
	]);
	
	Crafty.e("2D, DOM, Typewriter").attr({w: 100, h: 20, x: 200, y: 280})
		.write("Hello World!", "typekey", 200, 100);


License
-------

Dual licensed under MIT and GPL.
