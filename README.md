# libcopyfile

Library for copying files on FreeBSD, ported from an old version of [macOS' copyfile](https://opensource.apple.com/source/copyfile/copyfile-66).
It was modified to function correctly on FreeBSD, but because of differences between macOS & FreeBSD, not everything works as expected!

Previously, this port was found in [`aquabsd-pkg-repo`](https://github.com/inobulles/aquabsd-pkg-repo), but to work better as a singular dependency for use in other projects, I've temporarily split this out into a separate repo.
Temporary you say?
Yes, Temporary™! I'd like this to be reimplemented (still keeping with a similar API to copyfile and likely incorporating a lot of Apple's code) into a generic filesystem manipulation library, something along the lines of `libfsutils`, which includes other useful stuff, like recursive versions of a lot of the POSIX FS functions, and perhaps even some filesystem creation functionality.
But that's not for right now 😉

## Building

With [Bob the Builder](https://github.com/inobulles/bob) installed:

```console
bob install
```

## Copyright stuff

Copyright over the source is held by Apple, Inc. (previously Apple Computer, Inc.), and is licensed under the Apple Public Source License Version 2.0.
A copy of the license text may be found in the `LICENSE` file in the root directory.
