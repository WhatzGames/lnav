---
layout: page
title: Downloads
permalink: /downloads
---

The latest release is [**v{{ site.version }}**](https://github.com/tstack/lnav/releases/latest).

The following options are available for installing **lnav**:

## Linux

Download a [statically linked 64-bit binary](https://github.com/tstack/lnav/releases/download/v{{site.version}}/lnav-{{site.version}}-musl-64bit.zip). 

Install from the [Snap Store](https://snapcraft.io/lnav):

```shell
% sudo snap install lnav
```

## MacOS

Install using [Homebrew](https://formulae.brew.sh/formula/lnav):

```shell
% brew install lnav
```

## Source

Download the [source](https://github.com/tstack/lnav/releases/download/v{{site.version}}/lnav-{{site.version}}.tar.gz)
and install any dependencies.  The following commands will unpack the source
tar ball, configure the build for your system, build, and then install:

```shell
% tar xvfz lnav-{{site.version}}.tar.gz
% cd lnav-{{site.version}}
% ./configure
% make
% make install
```

If you would like to contribute to the development of lnav, visit our page on
[GitHub](https://github.com/tstack/lnav).