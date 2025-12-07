# Diagnostics
This file outlines the diagnostics that we need to save in the new experiments.

### Surface fluxes
| Model         | Variable                | Description |
| ------------- |------------------------ | ----------- |
| PanAntarctic  | `salt_flux`             |             |
| PanAntarctic  | `salt_flux_added`       | Note - maybe included in `salt_flux` in the new update, depends on what version of PanAnt we use. |
| PanAntarctic  | `wfo`                   |             |
| PanAntarctic  | `lrunoff`               |             |
| ACCESS-OM2-01 | `sfc_salt_flux_ice`     |             |
| ACCESS-OM2-01 | `sfc_salt_flux_restore` |             |
| ACCESS-OM2-01 | `pme_river`             |             |
| ACCESS-OM2-01 | `wfiform`               |             |
| ACCESS-OM2-01 | `wfimelt`               |             |
| ACCESS-OM2-01 | `runoff`                |             |

### Heat budget
| Model         | Variable                | Description |
| ------------- |------------------------ | ----------- |
| PanAntarctic  |                         |             |
| ACCESS-OM2-01 |                         |             |

### Restoring checks

Potentially unnecessary category - placeholder if we need to save anything extra to confirm that the forcing applied is the same as what is actually being input in the model. 
