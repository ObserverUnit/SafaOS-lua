# Lua

This is the repository of Lua development code, as seen by the Lua team. It contains the full history of all commits but is mirrored irregularly. For complete information about Lua, visit [Lua.org](https://www.lua.org/).

Please **do not** send pull requests. To report issues, post a message to the [Lua mailing list](https://www.lua.org/lua-l.html).

Download official Lua releases from [Lua.org](https://www.lua.org/download.html).

> NOTE: this is SafaOS's port and therefore might not work on other systems.

> NOTE: this is built for `kernel-snowball v0.2.1` and might be outdated If i didn't use lua in the project in the future because there would be no reason to maintain it, altough just bumping the `libc` commit should be enough.

## Building
run:
```
make safaos
```
then an `lua` binary would be built in the repo directory.
you can then copy it to `SafaOS/ramdisk-include/bin/lua` to bundle it with the initial ramdisk.
