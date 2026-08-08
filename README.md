# CUWT-WHT-ViT: Trait-guided wheat cultivar classification

## Authors

Ziyang He, Gang Sun, Yumeng Wan, Feng Tu, Greg Deakin, Zhenjie Wen, Robert Jackson, Ji Zhou and Lei Ju

Ziyang He: heziyang@stu.njau.edu.cn | ORCID: 0009-0001-6862-8449  
Gang Sun: gang.sun@njau.edu.cn | ORCID: 0000-0002-6548-5980  
Yumeng Wan: Yumeng.Wan@stu.njau.edu.cn | ORCID: 0009-0004-3896-2341  
Feng Tu: fengtu@stu.njau.edu.cn | ORCID: 0009-0008-7453-6699  
Greg Deakin: Greg.Deakin@niab.com | ORCID: 0000-0002-7817-345X  
Zhenjie Wen: WenZhenjie@njau.edu.cn | ORCID: 0000-0002-8191-1070  
Robert Jackson: Robert.Jackson@niab.com | ORCID: 0000-0002-8364-1633  

**Corresponding authors:**  
Ji Zhou: Ji.Zhou@njau.edu.cn; JZhou@CEMPS.ac.cn | ORCID: 0000-0002-5752-5524  
Lei Ju: Lei.Ju@niab.com | ORCID: 0000-0002-0048-7440  

Ziyang He and Gang Sun contributed equally to this work.

## Overview

This repository accompanies the study *From Traits to IDs: Multi-trait Learning with Knowledge Distillation for Varietal Classification*.

It provides released materials for the China-UK Wheat Traits (CUWT) dataset and the Wheat Trait-guided Vision Transformer (WHT-ViT). WHT-ViT is a trait-guided deep learning framework for field-based wheat cultivar classification from cultivar-matched canopy and lateral smartphone images collected from China and the United Kingdom.

The framework integrates cultivar classification with supervision from six spike traits: awn presence, projected spike length-to-width ratio, compactness, density, texture and yellowness.

## Data access

The complete CUWT image dataset is publicly available from Zenodo:

https://doi.org/10.5281/zenodo.20056636

The CUWT dataset is distributed under the Creative Commons Attribution 4.0 International license (CC BY 4.0).

## Repository contents

- `trait_extraction.py`: trait-extraction workflow for wheat spike images.
- `README.md`: project documentation and resource overview.
- `LICENSE`: license for repository source code and release materials.

## Archived model packages

Archived trained-model packages are available from the [v1.0 release](https://github.com/The-Zhou-Lab/CUWT-WHT-ViT/releases/tag/v1.0).

The release currently includes:

- `Distillation.zip`
- `pretrain_weights.zip`
- `teacher_weights.zip`

## Data and code availability

The complete CUWT image dataset is available through Zenodo at https://doi.org/10.5281/zenodo.20056636.

Released source materials are provided in this repository. Archived trained-model packages are available from the v1.0 release.

## License

The source code and other repository and release materials are distributed under the Apache License 2.0; see the [LICENSE](LICENSE) file.

The CUWT image dataset deposited on Zenodo is licensed separately under CC BY 4.0.

## Citation

If you use the CUWT dataset, code or released model packages, please cite the associated manuscript and the Zenodo dataset record:

China-UK Wheat Traits (CUWT): a dual-view field image dataset for trait-guided wheat cultivar classification. Zenodo. https://doi.org/10.5281/zenodo.20056636
