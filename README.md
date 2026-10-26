# Future Air Temperature Mapping for Greater London

This project supports a 100 m resolution air temperature dataset for Greater London, UK. The dataset provides projections for 2050 and 2080 under three Representative Concentration Pathways: RCP 2.6, RCP 4.5 and RCP 8.5.

Baseline temperature observations come from low-cost sensors in the Netatmo crowdsourced monitoring network. The workflow synthesises a typical meteorological year (TMY) from current meteorological records and applies weather morphing to generate future temperature scenarios. Spatial interpolation combines kriging with Local Climate Zone (LCZ) information to convert station-based temperature data into continuous spatial grids.

## Code availability

This repository currently contains a project overview only. The full source code will be made publicly available after the peer review and revision process has been completed.

## Planned contents

1. **Netatmo data retrieval and database preparation** — Methods for retrieving air temperature observations from the Netatmo crowdsourced monitoring network, transforming the records and organising them into a database.
2. **Typical meteorological year generation** — Algorithms for synthesising a TMY from current meteorological records.
3. **Future climate scenario generation** — Weather morphing algorithms for transforming baseline temperature data into future climate scenarios.
4. **Spatial temperature mapping** — Spatial interpolation algorithms that combine kriging with LCZ information to generate temperature grids at 100 m resolution.
5. **HTML query interface** — A web interface for quickly visualising temperature grids and querying temperature data for selected locations under different climate scenarios.
