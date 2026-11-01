# wallet2_api.h (but this time C compatible)

> Wrapper around wallet2_api.h that can be called using C api.

## Building

TL;DR: 

```bash
$ rm -rf monero wownero beldex release
$ git submodule update --init --recursive --force
$ ./build_single.sh beldex $(gcc -dumpmachine) -j$(nproc)
```

Broken? Not working? Need help? https://moneroc.mrcyjanek.net/
