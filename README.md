# MultimodalNLoSVehicleDetection
This repository accompanies our research on **Multimodal Non-Line-of-Sight Vehicle Detection: Dataset and Method**. It includes the AVGT dataset and the proposed detection method.

## DATASET 
AVGT: A Multimodal Dataset Integrating **A**udio, **V**isual, and **G**eometric Information at **T**-junctions.

### Overview

AVGT is a multimodal dataset designed for **non-line-of-sight (NLoS) vehicle detection** at real-world T-junctions. It integrates **Audio, Visual, and Geometric data** to investigate how acoustic observations and surrounding scene structures can be jointly exploited to detect vehicles occluded by roadside obstacles.

Unlike audio-only datasets, AVGT provides temporally aligned acoustic observations, surround-view images, and LiDAR point clouds. These complementary modalities enable researchers to investigate the relationship between vehicle-generated sounds and the environmental structures that influence sound propagation under NLoS conditions.

The dataset was collected at three real-world T-junctions in Beijing, China, covering two typical scene configurations with different structural conditions around the intersections.

### Dataset Statistics

The complete AVGT dataset contains:

- **3** real-world T-junctions
- **585 s** of multimodal recordings
- **73** annotated multimodal clips
- **45,718** multimodal sample triplets
- **6** vehicle-state categories

