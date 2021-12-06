<img src="https://assets.website-files.com/602eda09fc78afc76e9706b6/60917840ebdae99bf420b0a3_dcs.svg" width="140"/>

# Awesome Storj [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of projects, tools, and resources for the Storj platform. 

Note: this list contains only projects which are compatible with the current (v3) version of Storj network. Earlier projects and integrations were removed.

# Core links

- **[Start here](https://www.storj.io/) - Register on satellites operated by Storj Labs**
- [Documentation](https://docs.storj.io/dcs/) - Entrypoint to the official documentation
- [Community support / forum](forum.storj.io/) - Community and support forum
- [Storj Status](https://status.storj.io/) - Status of the Storj network
- [Usage statistic dashboard](https://storjstats.info/) - Statistics about the full Storj network ([raw data](https://stats.storjshare.io/))
- [Whitepaper v3](https://storj.io/storj.pdf) - Actual version of Storj white-paper 
- [FAQ](https://docs.storj.io/dcs/support/faqs) - Frequently Asked questions and answers 

 ## Clients with Storj support and integrations 

* **[uplink](https://github.com/storj/storj/releases) - Uplink is the official CLI for Storj. Can be downloaded from the release page** 
* [Storj Mobile](https://play.google.com/store/apps/details?id=com.storj_mobile) (beta) - Android application to access Storj ([forum post](https://forum.storj.io/t/storj-mobile-beta-for-android/15578))
* [rclone](https://rclone.org/tardigrade/) - Tool to sync your files to cloud storage including Storj 
* [restic]() - Restic is a modern backup program. Supports Storj via the rclone . [howto](https://docs.storj.io/dcs/how-tos/backup-with-restic), [docs](https://restic.readthedocs.io/en/stable/030_preparing_a_new_repo.html#other-services-via-rclone)

* [FileZilla](https://docs.storj.io/dcs/how-tos/set-up-filezilla-for-decentralized-file-transfer) - New protocol for Storj is being added to FileZilla. 
* [NextCloud](https://apps.nextcloud.com/apps/storj) - Adds Storj external storage to NextCloud 
* [Duplicati](https://www.duplicati.com/) - Free backup software to store encrypted backups online ([howto](https://docs.storj.io/dcs/how-tos/backup-with-duplicati))

# Client Libraries & language bindings

Storj can be used via the native interface (uplink CLI and uplink libraries) or as an S3 compatible backend with any S3 compatible tool. The following list focuses on the native protocol.

- [uplink](https://github.com/storj/uplink) - Go library to use Storj (documentation)[https://pkg.go.dev/storj.io/uplink]
- [uplink-c](https://github.com/storj/uplink-c) - C library of the Uplink

* [uplink-python](https://github.com/storj-thirdparty/uplink-python) - Python bindings for libuplink
* [uplink-php](https://github.com/storj-thirdparty/uplink-php/pull/20#pullrequestreview-818737763) - PHP binding for libuplink
* [uplink-rust](https://github.com/storj-thirdparty/uplink-rust) - Storj Uplink Rust bindings for the Rust programming language.

# Storage node operation (SNO/Farming)

Farmers store data on the Storj network in exchange for STORJ tokens based on contracts with any Storj Bridge.

- [Getting started with hosting Storagenode](https://www.storj.io/host-a-node/)
- [SNO Payment FAQ](https://forum.storj.io/t/sno-payment-mega-faq/16228) - Huge list of questions answered on the forum
- [Node FAQ](https://docs.storj.io/node/resources/faq) - FAQ about operating Storage Nodes
- [Grafana dashboard](https://gist.github.com/littleskunk/b16567743626d9dd33454463a2e8a5d4) - Grafana dashboard for the internal Prometheus endpoint of storagenodes ([forum post](https://forum.storj.io/t/tech-preview-email-alerts-with-grafana-and-prometheus/16156/8))

## Services based on / with support of Storj 

* [Fastly](https://fastly.com) - Content delivery network with Storj support ([docs](https://docs.fastly.com/en/guides/storj-dcs-object-storage))
* [Filebase](https://filebase.com/) - S3 compatible Object Storage. One of the supported storage backend is Storj ([docs](https://docs.filebase.com/what-is-filebase/our-ecosystem/storage-networks/storj#how-do-i-store-data-on-storj-through-filebase))
* [Opensea](https://opensea.io/) -- NFT marketplace. Supports hosting NFT resources on Storj ([howto](https://docs.storj.io/dcs/how-tos/nft-storage))
* [Pixelexperience](https://download.pixelexperience.org/) - Android ROMS are [distributed with the help of Storj](https://www.storj.io/blog/pixelexperience-scales-up-software-distribution-with-storj-dcs)

## Tokeneconomics

STORJ is an ERC-20 utility token for the Storj network.

* [STORJ on Coinmarketcap](https://coinmarketcap.com/currencies/storj/)
* Latest STORJ Token Balance & Flows Report: [Q3 2021](https://storj.io/blog/storj-token-balances-flows-report-q3-2021) 
* Supported on biggest centralized exchanges like [Binance](https://www.binance.com/en), [Kraken](https://www.kraken.com/) and DEX like  [Uniswap](https://app.uniswap.org/#/swap)
* Supported L2: [ZkSync](https://storj-labs.gitbook.io/node/dependencies/storage-node-operator-payout-information/zk-sync-opt-in-for-snos)

# Contribution

- [Contribution guideline](https://github.com/storj/storj/blob/main/CONTRIBUTING.md) - How to contribute to Storj
- [Give Feedback](https://forum.storj.io/c/ideas-and-suggestions/5) - Suggest new product ideas in the the community forum
- [Ideas and suggestions](https://forum.storj.io/c/ideas-and-suggestions/5) on Storj forum
- [Storj illustrated](https://github.com/storj/illustrated) - diagrams to explain internals of Storj architecture
- [storj-up](https://github.com/storj/up) - docker-compose based helper utility to startup full network (satellite + storage nodes) locally
- [Storj on Github](https://github.com/storj) - All Storj repositories in one place.
