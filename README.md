# MultimodalNLoSVehicleDetection
This repository accompanies our research on **Multimodal Non-Line-of-Sight Vehicle Detection: Dataset and Method**. It includes the AVGT dataset and the proposed detection method.

## Dataset
AVGT: A Multimodal Dataset Integrating **A**udio, **V**isual, and **G**eometric Information at **T**-junctions.

### Overview

AVGT is a multimodal dataset integrating **Audio, Visual, and Geometric information** collected at real-world T-junctions. It provides acoustic recordings, surround-view images, and LiDAR point clouds captured under naturalistic traffic conditions.

A key feature of AVGT is the integration of acoustic observations with temporally aligned scene structural information derived from surround-view images and LiDAR point clouds. Unlike existing datasets that primarily focus on audio recordings, AVGT enables researchers to investigate the relationship between vehicle-generated sounds and surrounding scene structures, particularly under non-line-of-sight (NLoS) conditions where sound propagation is influenced by environmental obstacles.

The dataset was collected at three real-world T-junctions in Beijing, China, covering two typical scene configurations with different structural conditions around the intersections.

### Dataset Statistics

The complete AVGT dataset contains:

- *3* real-world T-junctions
- *585 s* of multimodal recordings (*111.13 GB*)
- *73* labeled multimodal clips
- *45,718* multimodal sample triplets
- *6* vehicle-state classes

### Demo Data

This repository provides a subset of the AVGT dataset for demonstration, allowing researchers to inspect real-world multimodal recordings and their corresponding annotations.

A subset of the AVGT dataset is currently available for demonstration, **with the full dataset to be released once the paper is accepted.**

**Download:** [Google Drive](https://drive.google.com/drive/folders/1PNZXzOOLI3UsdlA_hG3CumOaeASM6P8o?usp=sharing)

#### Folder Structure

The demo dataset is organized as follows:

```text
AVGT_Demo/
├── Stage1-RawMultimodalRecordings/
│   ├── multi_camera_lidar_20251129-1006.bag (LiDAR & multi-view cameras)
│   └── scene1-11291006-1764382014.026008129-right-12.462991871-17.793991871.wav (16-channel audios)
├── Stage2-LabeledClips/
│   ├── scene1-11291006-1764382024.489000000-rightapproach.bag
│   ├── scene1-11291006-1764382024.489000000-rightapproach.wav
│   └── ...
├── Stage3-SampleTriplet/
│   ├── MULTI_CHANNEL_AUDIO/
│   │   ├── scene1-11291006-1764382024.739000000-rightapproach.wav
│   │   └── ...
│   ├── LIDAR_TOP/
│   │   ├── scene1-11291006-1764382024.739000000-rightapproach.bin
│   │   └── ...
│   ├── CAM_FRONT/
│   │   ├── scene1-11291006-1764382024.739000000-rightapproach.jpg
│   │   └── ...
│   └── ...
└── Stage4-NetworkInputImages/
    ├── BevImage
    ├── DoaImage
    └── StftImage


### Research Applications

AVGT can support research on:

- Non-line-of-sight vehicle detection
- Multimodal Scene Reconstruction
- Traffic behavior analysis
- Acoustic-spatial interaction modeling


## Method

We propose a multimodal NLoS vehicle detection method that integrates acoustic observations and surrounding scene structures to identify occluded vehicles.

**The source code will be made publicly available following the acceptance of our paper.**


