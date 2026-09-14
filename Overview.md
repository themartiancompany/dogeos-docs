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

### Overview

DogeOS is an application layer over an operating system base
(a platform), which may have or may have not been provided by
DogeOS itself.

Regardless, DogeOS will manage it.

An operating system DogeOS is able to run on is called a *base*.

As of 2026, DogeOS has three main working *bases*, which are

- GNU, (`gnu`),
- Android (`android`) and
- Windows (`windows`).

Release of MacOS (`macos`) base
[Gur](
  https://github.com/themartiancompany/gur)
binary packages is currently being postponed because
the `system-7` (*System 7*, also known as *MacOS 7*)
[Ur](
  https://github.com/themartiancompany/ur)
package already provides an easy way for developers
to develop and run MacOS applications natively on other
DogeOS bases with greater performance than on a MacOS
base itself.

The Martian Company's currenty policy before OS binary
releases is MacOS user or developer interested in DogeOS
should seek to run MacOS applications natively on the
existing DogeOS bases.

An operating system base is considered supported by DogeOS
when the Ur builds on the platform.

For an operating system base to be considered fully
supported by DogeOS software, the Ur and the Ethereum
stack should build on the Gur binary packages
for that platform.

Ur Gur support for a platform is obtained by appropriately
configuring the Github or the Gitlab continuous integration (CI)
configuration file in Ur
[Universal Recipe](
  https://github.com/themartiancompany/ur-ur).
