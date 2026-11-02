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

### Security

#### Root file system immutability and boot key

DogeOS
[Ur package](
  https://github.com/themartiancompany/dogeos-ur)
binary images, if
written on a read-only support such as
a CDROM produce an immutable system,
as in no further changes can be produced
on the part of the system loaded on the
read-only supports.

By default the
[archiso profile](
  https://github.com/dogeos/tree/master/dogeos/profiledef.sh)
is configured to generate a second image to be
put on a read-only support or
an USB drive to be used as boot key.

When the security key is used,
it is convenient to connect
to your computer some non-volatile read-write
memory of some kind using some
storage medium like an hard-drive
or a solid state drive in order to conveniently
save your session.

The documentation is released under the terms of the
GNU Affero General Public License version 3.
