About this repository
=====================

This is set of icons for "special" folders.

Repository also contains (GNU GPL or public domain) objects used to create
them and some other potential useful icons in [third-party-src](third-party-src).


Usage
-----

To set directory icon you should create `.directory` file inside it:

```
echo '[Desktop Entry]' > .directory
echo 'Icon=./.directory.png' >> .directory
```

Next you should export as PNG your favorite icon and move it to location
specified in `.directory` file. In this example it's `.directory.png`
file in directory which should have an icon.


License
-------

Copyright (C) 2009-2019 Robert Paciorek <rrp@opcode.eu.org>

This work use GNU GPL licensed items from from various authors - see
[third-party-src/README.txt](third-party-src/README.txt) for more details.

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.
