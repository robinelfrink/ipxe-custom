# Custom [iPXE](https://ipxe.org/) binary builder.

Configuration to build a custom iPXE binary for my personal use.

Usage:

```shell
$ git clone https://github.com/robinelfrink/ipxe-custom.git
$ cd ipxe-custom
$ git submodule update --init
$ cd ipxe/src
$ cp ../../general.h config/local/
$ make bin/ipxe.lkrn
```

Automated building is done using
[GitHub Actions](https://github.com/features/actions).
