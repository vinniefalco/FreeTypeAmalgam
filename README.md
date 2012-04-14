# FreeType Amalgamation

A distribution of the [FreeType][1] library in amalgamated source code form.

## What is FreeType?

FreeType 2 is a software font engine that is designed to be small,
efficient, highly customizable, and portable while capable of producing
high-quality output (glyph images). It can be used in graphics libraries,
display servers, font conversion tools, text image generation tools, and
many other products as well.

## How do I use it?

Add FreeTypeAmalgam.c to your existing project, include FreeTypeAmalgam.h
in the source files where you want to use FreeType, and go!

## What's an amalgamation?

An amalgamation is simply a collection of header and source files that have been
concatenated together to form one or more very large files. In this form, they
are easy to add to your existing project as source files (rather than linking
as a library). They are also easier to redistribute if you are making an open
source application and don't want to have any external dependencies.

The amalgamation is built using the [FreeType Amalgamation Template][3] and the
[Amalgamate][4] tool.

## License

Copyright 2003-2007, 2011 by David Turner, Robert Wilhelm, and Werner Lemberg.<br>
FreeType is distributed under a dual license, see the file LICENSE.txt for details.

[1]: http://www.freetype.org "The FreeType Library"
[2]: http://rawmaterialsoftware.com/jucelicense.php "JUCE Commercial Licensing"
[3]: https://github.com/vinniefalco/FreeTypeAmalgamTemplate/ "FreeType Amalgamation Template"
[4]: https://github.com/vinniefalco/Amalgamate/ "Amalgamate Tool"
