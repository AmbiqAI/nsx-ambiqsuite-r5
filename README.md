# nsx-ambiqsuite-r5

`nsx-ambiqsuite-r5` is the raw AmbiqSuite R5 SDK provider repo used by NSX.

This repo keeps the imported vendor SDK under `sdk/` and exposes a thin NSX
provider target through `CMakeLists.txt` and `nsx-module.yaml`.

Branch model:
- `main`: current default R5 line for NSX
- `r5.1`: Apollo510B-era lineage
- `r5.2`: Apollo5B-era lineage
- `r5.2-alpha`: Apollo330-era lineage
- `r5.3`: Apollo510 default lineage
