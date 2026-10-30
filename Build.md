[comment]: <> (SPDX-License-Identifier: AGPL-3.0)

[comment]: <> (----------------------------------------------------)
[comment]: <> (Copyright © 2024, 2025, 2026)
[comment]: <> (            Pellegrino Prevete)
[comment]: <> (All rights reserved)
[comment]: <> (----------------------------------------------------)

[comment]: <> (This program is free software: you can redistribute)
[comment]: <> (it and/or modify it under the terms of the)
[comment]: <> (GNU Affero General Public License as published)
[comment]: <> (by the Free Software Foundation, either version)
[comment]: <> (3 of the License.)

[comment]: <> (This program is distributed in the hope that it)
[comment]: <> (will be useful, but WITHOUT ANY WARRANTY;)
[comment]: <> (without even the implied warranty of)
[comment]: <> (MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.)
[comment]: <> (See the GNU Affero General Public License)
[comment]: <> (for more details.)

### Build instructions

Being an extension of Life, a minimal immutable binary image of
the DogeOS GNU/Linux base can be obtained by building the
[`life`](
  https://github.com/themartiancompany/life)
universal recipe and installing the corresponding package.

The `life` package will install an ISO file at the
`<usr>/share/life` location which can then be installed
onto a disk using `dd`, or any image writer you may like,
for example on GNU/Linux systems the
[GNOME multi-writer](
  https://gitlab.gnome.org/GNOME/gnome-multi-writer)
or the
[GNOME disk utility](
  https://gitlab.gnome.org/GNOME/gnome-disk-utility).

The ISO image does contain a writable partition,
so placing the ISO onto a writable storage drive
you will be able to use the system normally without
further operations.

The documentation is released under the terms of the
GNU Affero General Public License version 3.
