# nsx-ambiqsuite-r5

`nsx-ambiqsuite-r5` is the AmbiqSuite R5 SDK provider for NSX modules.

This repo packages the vendor SDK under `sdk/` and exposes a thin NSX
provider target through `CMakeLists.txt` and `nsx-module.yaml`.

## SDK Version

**AmbiqSuite SDK 5.1.0** (`release_sdk5p1p0-609aff2828`)

## Package Contents

| Directory | Contents |
|-----------|----------|
| `sdk/CMSIS/` | ARM CMSIS headers, DSP/NN libs, AmbiqMicro SoC headers |
| `sdk/boards/` | BSP headers only (no source) — apollo510_evb, apollo510b_evb |
| `sdk/devices/` | Device driver headers only (no source) |
| `sdk/lib/` | Prebuilt `libam_hal.a`, `libam_bsp.a` (GCC + armclang) |
| `sdk/mcu/` | HAL headers + register definitions (no source) |
| `sdk/pack/SVD/` | SVD debug descriptors |
| `sdk/src/` | Curated sources: utils, FreeRTOS kernel, USB, BLE, MSPI drivers |
| `sdk/third_party/` | FreeRTOS, Cordio BLE, TinyUSB, uECC (full source) |
| `sdk/utils/` | Utility headers only (no source) |

HAL and BSP are provided as prebuilt static libraries only — no HAL or BSP
source code is included. Third-party components include full source.

## Branch Model

- `main` — current default R5 line for NSX (SDK 5.1.0)

Licensing for the imported SDK content follows the upstream AmbiqSuite terms.
See [`UPSTREAM-LICENSE-NOTICE.md`](UPSTREAM-LICENSE-NOTICE.md) for the
provenance note for this repo.
