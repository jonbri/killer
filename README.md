# killer
While developing I often create stray processes by accident.

To fix this situation I usually use something like: `px aux | grep node` and `kill -9 123`.

This script makes that action a little easier.

## Installation
This is a Perl script.

Put this on your `PATH` for easy invocation.

The checked-in version already has the executable bit set.

## Run
```
killer help           # see help
killer node           # kill all node instances
killer "jonbri.*node" # (regex) kill all node instances by user
```

## License
[BSD-2-Clause](http://spdx.org/licenses/BSD-2-Clause)
