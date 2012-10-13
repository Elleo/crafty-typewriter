Crafty Typewriter
=================

Typewriter plugin for the Crafty JavaScript game library.

Writes out a string of text one character at a time in the style of a typewriter.

Particularly suited for use alongside fonts such as GNUTypewriter: http://openfontlibrary.org/en/font/gnutypewriter


Example
-------

	Crafty.init(640, 480);

	Crafty.audio.add("typekey", [
		"http://github.com/Elleo/crafty-typewriter/raw/master/audio/typewriter_key.ogg"
	]);
	
	Crafty.e("2D, DOM, Typewriter")
		.attr({w: 200, x: 10, y: 10})
		.css({"font-family" : "Courier New"})
		.write("Hello World!", "typekey", 250, 150);


License
-------

Dual licensed under MIT and GPL.
