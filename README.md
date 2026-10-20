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

- Collection sites: **3** real-world T-junctions
- Raw recording duration: **585 s** of multimodal recordings （**111.13 GB**）
- Labeled multimodal clips: **73**
- Multimodal sample triplets: **45,718** (each sample triplet associates an audio segment with temporally corresponding surround-view image frames and a LiDAR point cloud frame.)
- Target vehicle states: **6** classes

### Demo Data

This repository provides a subset of the AVGT dataset for demonstration, allowing researchers to inspect real-world multimodal recordings and their corresponding annotations.

The complete AVGT dataset contains **45,718 multimodal sample triplets**. Currently, only selected samples are publicly available. **The complete dataset will be released upon acceptance of the accompanying paper.**

### Research Applications

AVGT is designed to support research on:

Non-line-of-sight vehicle detection

Audio-visual-geometric multimodal learning

Acoustic-spatial interaction modeling

Scene structure-aware acoustic perception

Traffic behavior analysis
