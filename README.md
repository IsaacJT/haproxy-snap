# HAProxy Snap
[![haproxy](https://snapcraft.io/haproxy-dtp/badge.svg)](https://snapcraft.io/haproxy-dtp)

## Introduction

This is a community-developed [HAProxy](https://github.com/haproxy/haproxy) snap, made by repackaging the HAProxy binary from the Ubuntu package repository, with minor modifications to the `haproxy.cfg` file.

This is a fork of the [haproxy-dtp](https://github.com/DownThePark/haproxy-snap/tree/main/snap) snap.

## Features
- Strict confinement
- Support for multiple CPU architectures

## Installation
[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/itrue-haproxy)

This snap can be installed from the Snap Store using the following command:

    sudo snap install itrue-haproxy

>[!Note]
>The configuration file can be found at `/var/snap/itrue-haproxy/current/haproxy.cfg`
