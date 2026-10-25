# AI-DCGs

Author: Xin Yang

Documentation and source-image inventory for AI-DCGs, a multimodal AI-ready dataset for glacier semantic segmentation in High Mountain Asia.

AI-DCGs combines Sentinel-2 optical reflectance, Sentinel-1 radar backscatter, Landsat land surface temperature, Copernicus DEM terrain variables, and pixel-level reference labels for background, bare ice, and debris-covered ice.

## Documents

| File | Contents |
| --- | --- |
| [Dataset description](AI-DCGs_Dataset_Description_English.pdf) | Data coverage, patch releases, file organization, label codes, feature channels, numeric encoding, preprocessing, and training and evaluation guidance. |
| [Source-image summary](AI_DCGs_source_data_summary.pdf) | Table S1: satellite products, acquisition-date ranges, spatial identifiers, and scene counts for the source imagery. |

## Dataset overview

- Region: High Mountain Asia, with 42 source windows across 13 glacier subdivisions.
- Reference-label years: 2016-2025.
- Patch sizes: 256 x 256, 512 x 512, and 1024 x 1024 pixels.
- Inputs: four feature GeoTIFFs containing 15 predictor channels per sample.
- Labels: 0 = background, 1 = bare ice, 2 = debris-covered ice.

This repository contains the two PDF documents. The GeoTIFF datasets and original satellite scenes are distributed separately. See the dataset description for details on data access, citation, and the formal dataset record governing licensing and access conditions.
