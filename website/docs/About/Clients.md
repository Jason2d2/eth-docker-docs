---
id: Clients
title:  Supported Clients.
sidebar_label: Clients
---

This project builds from client teams' official docker images or from official source repositories, pulled
directly from docker hub or github, respectively. In most cases, binary is the default.

Currently supported consensus clients:
- Teku
- Lighthouse
- Nimbus
- Lodestar
- Prysm

Currently supported execution clients:
- Geth
- Besu
- Nethermind
- Erigon - alpha release
- Akula - pre-alpha, source build only

> An Ethereum node has one consensus client and one execution client. eth-docker can be used to
> split this between two machines, but that distributed setup has not yet been tested.

Currently supported additional options:
- Sending stats to https://beaconcha.in
- Prysm Web UI
- Grafana dashboard
- slasher - running slasher is optional and requires additional resources

Please see [Prysm Web](../Usage/PrysmWeb.md) for Web UI support on Prysm.
