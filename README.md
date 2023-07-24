# ipip6 package feed

## Description

This is an ipip6 package feed containing community maintained package.

## Usage

To use these packages, add the following line to the feeds.conf
in the OpenWrt buildroot:

```
src-git ipip6 https://github.com/HiraokaHyperTools/openwrt-ipip6.git
```

This feed should be included and enabled by default in the OpenWrt buildroot. To install all its package definitions, run:

```
./scripts/feeds update ipip6
./scripts/feeds install ipip6
```

The ipip6 package should now appear in menuconfig.

This will make package `bin/packages/mipsel_24kc/ipip6/ipip6_0.1-4_all.ipk` or such.

```
make package/ipip6/compile
```

## Download

- [ipip6_0.1-5_all.ipk](https://github.com/HiraokaHyperTools/openwrt-ipip6/releases/download/v0.1-5/ipip6_0.1-5_all.ipk)
