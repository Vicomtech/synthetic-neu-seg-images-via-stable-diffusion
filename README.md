# Synthetic NEU-Seg Images via Stable Diffusion

This dataset accompanies the paper "Latent Diffusion Models to Enhance the Performance of Visual Defect Segmentation Networks in Steel Surface Inspection".

The dataset will be made available upon the paper's acceptance and request for the data, filling the form at:

https://opendatasets.vicomtech.org/di11-synthetic-neu-seg-images-via-stable-diffusion/33e9a1ec

# Usage

The dataset is organized in the same way as the original NEU-seg dataset: the images folder contains the synthetic images of the defects, and the annotations folder contains the pixel-level annotations of each. The class values of the pixels in the masks are assigned as follows: 0. Background, 1. Patches, 2. Inclusion, 3. Scratches. Each image/annotation filename is self-descriptive, with regards to the class it belongs to.

# Authors
The following researchers have collaborated in the dataset creation and curation process:
- Jon Leiñena Otamendi
- Fátima Saiz Álvaro

# Contact

{jleinena, tech.transfer}@vicomtech.org

# License

[![CC BY-NC-ND 4.0][cc-by-nc-nd-image]][cc-by-nc-nd]

All datasets on this page are copyrigh by Vicomtech and published under the Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 License. This means that you must attribute the work in the manner specified by the authors, you may not use this work for commercial purposes and if you remix, transform, or build upon the material, you may not distribute the modified material.

[cc-by-nc-nd]: http://creativecommons.org/licenses/by-nc-nd/4.0/
[cc-by-nc-nd-image]: https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png

# Other relevant information

**Please cite ourwork as follows:**
```

@Article{s24186016,
AUTHOR = {Leiñena, Jon and Saiz, Fátima A. and Barandiaran, Iñigo},
TITLE = {Latent Diffusion Models to Enhance the Performance of Visual Defect Segmentation Networks in Steel Surface Inspection},
JOURNAL = {Sensors},
VOLUME = {24},
YEAR = {2024},
NUMBER = {18},
ARTICLE-NUMBER = {6016},
URL = {https://www.mdpi.com/1424-8220/24/18/6016},
ISSN = {1424-8220},
ABSTRACT = {This paper explores the use of state-of-the-art latent diffusion models, specifically stable diffusion, to generate synthetic images for improving the robustness of visual defect segmentation in manufacturing components. Given the scarcity and imbalance of real-world defect data, synthetic data generation offers a promising solution for training deep learning models. We fine-tuned stable diffusion using the LoRA technique on the NEU-seg dataset and evaluated the impact of different ratios of synthetic to real images on the training set of DeepLabV3+ and FPN segmentation models. Our results demonstrated a significant improvement in mean Intersection over Union (mIoU) when the training dataset was augmented with synthetic images. This study highlights the potential of diffusion models for enhancing the quality and diversity of training data in industrial defect detection, leading to more accurate and reliable segmentation results. The proposed approach achieved improvements of 5.95% and 6.85% in mIoU of defect segmentation on each model over the original dataset.},
DOI = {10.3390/s24186016}
}

```
