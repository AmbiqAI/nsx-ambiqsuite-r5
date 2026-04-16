# Changelog

## [0.1.1](https://github.com/AmbiqAI/nsx-ambiqsuite-r5/compare/nsx-ambiqsuite-r5-v0.1.0...nsx-ambiqsuite-r5-v0.1.1) (2026-04-16)


### Features

* update SDK to AmbiqSuite 5.1.0 (release_sdk5p1p0) ([7990aa6](https://github.com/AmbiqAI/nsx-ambiqsuite-r5/commit/7990aa6dffe8e5af050d61e73bb60e1af8105447))


### Bug Fixes

* add missing am_mcu_apollo.h top-level include ([a263109](https://github.com/AmbiqAI/nsx-ambiqsuite-r5/commit/a263109dbca6a48277a959abd9b1e79212f7044b))
* add missing am_sdk_version.h (required by am_hal_global.h) ([d15bfc2](https://github.com/AmbiqAI/nsx-ambiqsuite-r5/commit/d15bfc21d8045ec4dc9b1545591660a347c29d8c))
* add missing cdcd_deinit to cdc_device_ns.c (required by usbd.c) ([11106eb](https://github.com/AmbiqAI/nsx-ambiqsuite-r5/commit/11106eb29242e68ed97d8293befda05fc2fbd937))
* add missing tusb_config.h for TinyUSB (required by nsx-usb) ([701a144](https://github.com/AmbiqAI/nsx-ambiqsuite-r5/commit/701a1445ee1ee67533ae37180f6cc7108fb65a3a))
* **ci:** handle unquoted version in nsx-module.yaml ([e76b959](https://github.com/AmbiqAI/nsx-ambiqsuite-r5/commit/e76b95909aec5d0e8fa9f6d5ce88df0df92af29c))
* enable TinyUSB vendor class (CFG_TUD_VENDOR=1) for nsx-usb ([8d9e66f](https://github.com/AmbiqAI/nsx-ambiqsuite-r5/commit/8d9e66ffce2a91b818beb58cfccd756282201a3f))
