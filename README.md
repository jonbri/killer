# killnode
While developing NodeJS applications I often create stray processes by accident.

To fix this situation I usually use a combination of `px aux | grep node` and `kill -9 123`.

This script makes that action a little easier.

## Installation
This is a Perl script.

Put this on your `PATH` for easy invocation.

The checked-in version already has the executable bit set.

## Run
```
killnode
```

