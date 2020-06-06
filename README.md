# Android chroot

## Disclaimer

This script don't care about inital setup of linux system, so it's part up to you

## Setup

Edit variables on top of `init` script, to fitt you environment

## Usage

```
./init [mount. unmount, run, help] /bin/bash
```

If no argumets provide, help will be shown.
Can specifi shell as last argument to run in chroot

## Tips

### Default shell as chroot

You can put this as shell to any terminal to start directly from chroot

```
/path/to/init run /bin/bash
```
