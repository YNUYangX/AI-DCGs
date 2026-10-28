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

This repository contains the two PDF documents. The AI-DCGs GeoTIFF dataset is distributed separately through the National Cryosphere Desert Data Center (NCDC), under the licence and access conditions stated in its dataset record. Original satellite scenes are distributed by their respective providers.

## License

Copyright (c) 2026 Xin Yang.

Unless otherwise noted, the original documentation and source-image inventory in this repository, including this README and the two PDFs listed above, are licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). The full licence text is provided in [LICENSE](LICENSE).

When sharing or adapting these materials, provide appropriate credit to Xin Yang, link to the licence, and indicate whether changes were made, in accordance with CC BY 4.0. For attribution, use: Xin Yang, *AI-DCGs documentation and source-image inventory*, [project repository](https://github.com/YNUYangX/AI-DCGs).

This licence applies to the original materials published in this repository. It does not change the licences or terms of use of third-party satellite imagery, elevation products, or other source datasets described in the documents; those products remain subject to their respective providers' terms. The separately archived AI-DCGs GeoTIFF dataset is governed by the licence stated in its NCDC record.
