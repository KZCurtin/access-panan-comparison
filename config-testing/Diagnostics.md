# Diagnostics
This file outlines the diagnostics that we need to save in the new experiments.

### Surface fluxes
| Model         | Variable                | Description |
| ------------- |------------------------ | ----------- |
| PanAntarctic  | `salt_flux`             |             |
| PanAntarctic  | `salt_flux_added`       | Note - maybe included in `salt_flux` in the new update, depends on what version of PanAnt we use. |
| PanAntarctic  | `wfo`                   | P+E+R            |
| PanAntarctic  | `net_melt`              | In the sea-ice model. Gives net mass flux from ice and snow melt/freeze.    |
| PanAntarctic  | `fprec`                 | Is the snowfall_flux. Can be used to just isolate the mass flux from ice from `net_melt`.     |
| PanAntarctic  | `lrunoff`               | Liquid river runoff            |
| PanAntarctic  | `evap`                  | This is a maybe - could infer evap changes from difference between `wfo` and `net_melt - fprec`.  |
| PanAntarctic  | ADVECTION VARIABLE - TO FIND  |            |
| ACCESS-OM2-01 | `sfc_salt_flux_ice`     |             |
| ACCESS-OM2-01 | `sfc_salt_flux_restore` |             |
| ACCESS-OM2-01 | `pme_river`             |             |
| ACCESS-OM2-01 | `wfiform`               |             |
| ACCESS-OM2-01 | `wfimelt`               |             |
| ACCESS-OM2-01 | `runoff`                | Liquid river runoff            |
| ACCESS-OM2-01 | ADVECTION VARIABLE - TO FIND  |            |

### Heat budget
| Model         | Variable         |  Frequency    | Description |
| ------------- | ---------------- |-------------- | ----------- |
| PanAntarctic  | `thetao`         | Daily         | Potential temperature    |
| ACCESS-OM2-01 | `temp`           | Daily         | Conservative temperature        |
|               |                  |               |             |

### Restoring checks

Potentially unnecessary category - placeholder if we need to save anything extra to confirm that the forcing applied is the same as what is actually being input in the model. 
