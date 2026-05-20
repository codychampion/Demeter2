# Demeter2

![Status](https://img.shields.io/badge/status-under%20review-f59e0b)
![Historical](https://img.shields.io/badge/project-historical-64748b)
![Geospatial](https://img.shields.io/badge/domain-geospatial%20analysis-2563eb)
![TerraRef](https://img.shields.io/badge/data-TerraRef-059669)

Historical research code related to TerraRef / plant phenotyping workflows.

This public repo is currently under review as part of a broader GitHub portfolio cleanup. The main open question is whether this repository is the canonical public home for the Demeter work, whether it should be merged with the private `demeter` repo, or whether it should be archived and redirected.

## Current status

This repo is public, but the project context is incomplete. Until the Demeter/Demeter2 split is resolved, treat this as a historical project rather than an actively maintained package.

## Related work

The private `demeter` repo includes README notes describing TerraRef / hyperspectral extraction utilities, including:

- generating TerraRef download lists
- extracting and summarizing variables from `ind.nc` files
- maintaining ratio/index definitions
- extracting plant-associated spectra using chlorophyll-informed masking
- converting between wavelength and band/index terms

Those notes suggest the broader project sits at the intersection of plant phenotyping, hyperspectral data processing, and geospatial / remote-sensing analysis.

## Cleanup plan

Before this repo is promoted or linked from the main GitHub profile, the next steps are:

1. Inspect the file trees of both `Demeter2` and the private `demeter` repo.
2. Decide which repo is canonical.
3. Audit private material for secrets, local paths, credentials, unpublished data, and large data artifacts.
4. Either turn this into the public historical showcase README or archive it with a clear redirect.

See issue #1 for the consolidation plan.