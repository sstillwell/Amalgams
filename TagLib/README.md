# TagLib Amalgamation Template

Source templates for building the [TagLib Amalgamation][1].

This contains the templates and script used to build the [TagLib Library][2] in
amalgamated form. This is useful if you want to create it yourself. For example,
if you have applied patches.

To build the amalgamation:

- Build the [Amalgamate][3] tool and place it in a directory where the system
  will find it (the PATH environment variable in Windows).

- Put a TagLib repository in the root of this local repository.

- Open your IDE-specific project file and build it.

- The amalgamated output  will be placed in TagLibAmalgam/ (which you must create).

The resulting amalgamation is platform independent, but projects for each
platform are provided to make it easy to build and also to detect errors in
specific IDEs.

## License

Copyright (C) 2012 [Vinnie Falco][4] <br>
TagLib Amalgamation Template is provided under the terms of the [MIT license][5].

[1]: https://github.com/vinniefalco/TagLibAmalgam "TagLibAmalgam"
[2]: http://developer.kde.org/~wheeler/taglib.html "TagLib"
[3]: https://github.com/vinniefalco/Amalgamate "Amalgamate Tool"
[4]: http://vinniefalco.com "Vinnie Falco's Home Page"
[5]: http://www.opensource.org/licenses/MIT "MIT License"