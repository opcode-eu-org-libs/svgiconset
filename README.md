<!--
SPDX-FileCopyrightText: Robert Ryszard Paciorek <rrp@opcode.eu.org>
SPDX-License-Identifier: MIT
-->

About this repository
=====================

This repository contains:

1. custom icons for "special" folders - see [`folders`](folders) directory
2. custom icons for usage in html documents - see [`other`](other) directory
3. archived icons (from various projects) for supplementary use - see [`third-party-src`](third-party-src) directory
	* this also includes a few non-SVG icons - see [`third-party-src/png`](third-party-src/png) directory
4. icons and some other graphics used to created custom icons - see [`third-party-src`](third-party-src) directory


Usage
-----

To set directory icon you should create `.directory` file inside it:

```bash
echo '[Desktop Entry]' > .directory
echo 'Icon=./.directory.png' >> .directory
```

Next you should export your favorite icon as PNG and move it to location
specified in `.directory` file. In this example it's `.directory.png`
file in directory which should have an icon.


License
-------

Copyright (C) 2009-2019 Robert Ryszard Paciorek <rrp@opcode.eu.org>

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
