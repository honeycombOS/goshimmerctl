GoShimmer is an implementation of IOTA Coordicide. It's the prototype node software for an IOTA network without the Coordinator."

This repository contains tools that help managing GoShimmer nodes.

It's designed to work with [nfpm](https://github.com/goreleaser/nfpm) CLI tool to create a `.deb.` package.

Instructions:
```
export GOSHIMMERCTL_VERSION=0.1
nfpm pkg -t goshimmerctl_0.1_all.deb
```
