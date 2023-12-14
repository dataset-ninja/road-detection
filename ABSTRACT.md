In the pursuit of accurate road detection and centerline extraction from very high-resolution (VHR) remote sensing imagery, the authors of the **Road Detection and Centerline Extraction Dataset** address the challenges posed by complex backgrounds and occlusions of trees and cars. Traditional road detection methods often introduce heterogeneous segments, while existing centerline extraction approaches struggle to produce a smooth, complete, and single-pixel width road network. To overcome these complexities, the authors propose a novel deep model, the Cascaded End-to-End Convolutional Neural Network (**CasNet**), designed to simultaneously handle road detection and centerline extraction tasks.

CasNet comprises two interconnected networks. The first network focuses on road detection, leveraging strong representation abilities to navigate complex backgrounds and occlusions. The second network is cascaded to the first, utilizing previously generated feature maps to achieve effective centerline extraction. To obtain a smooth, complete, and single-pixel width road centerline network, a thinning algorithm is introduced as a final step in the process.

In the realm of road extraction, two fundamental subtasks exist: road detection and road centerline extraction. The former involves extracting all road pixels, while the latter focuses solely on labeling the centerline pixels to provide directional information for applications such as vehicle navigation. Many road detection approaches are pixel-level, leading to heterogeneous results in VHR remote sensing images due to noise and occlusions. Object-level-based approaches offer some improvement but struggle to provide consistent results around road boundaries.

## Dataset Information

There is a scarcity of publicly available very high-resolution (VHR) urban road datasets. In response, the authors collected 224 VHR images from Google Earth and manually labeled corresponding road segmentation reference maps and centerline reference maps. This dataset is touted as the largest road dataset with accurate segmentation and centerline maps.*

<img src="https://github.com/dataset-ninja/road-detection/assets/78355358/ee6e8fca-27b8-4f96-bef4-92bf5c4a9fba" alt="image" width="800">

**Road Detection Annotations:**
- Original images have a spatial resolution of 1.2 m per pixel.
- Each image contains at least 600x600 pixels, and the road width ranges from 12 to 15 pixels.
- The dataset includes images with complex backgrounds and occlusions, presenting a challenging road detection task.

**Road Centerline Annotations:**
- Corresponds to the road centerline maps of the original images.
- The road centerline is single-pixel width, accurately positioned at the center of the road.
- Provides a visual overlay between road segmentation reference maps and road centerline reference maps for better understanding.
- Close-ups highlight the single-pixel width and central positioning of the road centerline in the dataset.