## 👋 Hi, I’m Karol
<sub>
(Find my full profile at https://karol-gotkowski.pages.dev/)
</sub>

I’m a **Machine Learning Engineer and Researcher** at the Medical Image Computing group of the **Deutsches Krebsforschungszentrum (DKFZ)** in Heidelberg, Germany, specializing in **3D radiological image analysis**. Over the last two years, my work has strongly focused on **large-scale self-supervised representation learning** for medical imaging, alongside interactive and applied segmentation research. My work can be broadly grouped into the following areas:

* 🧠 **Large-Scale Self-Supervised Representation Learning (DINOv2 / DINOv3)**:
  My main research focus over the past two years has been 3D foundation models for radiology, culminating in [nnFoundation](https://arxiv.org/abs/2609.26924): a pair of complementary convolutional and transformer-based models **pretrained on 2.1 million CT, MRI and PET volumes from 125 datasets**, evaluated on 108 downstream tasks and released integrated into nnU-Net and nnDetection. I led the data infrastructure group, harmonizing over a petabyte of data and building the database, storage systems and data formats for training at that scale. On the pretraining side I developed a 3D DINOv2 and compared it against MAE under matched compute. I also co-led the hands-on fine-tuning for segmentation and classification. I currently work with DINOv3, focusing on parameter-efficient fine-tuning (PEFT) across medical and non-medical image domains.

* 🔧 **Methodological & Interactive Deep Learning**:
  Development of 3D medical image segmentation methods, with an emphasis on weak supervision, interactive and prompt-based segmentation, and usability-driven model design. This includes large-scale benchmarking, Napari-based interactive systems, and scalable training and inference pipelines.

* 🧠 **Applied & Clinical Projects**:
  Collaboration with clinical partners on applied radiological segmentation tasks, translating methodological advances into clinically meaningful and validated systems.

* 🛠️ **Tooling & Infrastructure**:
  Design and maintenance of open-source tools for patch-based processing, large-volume data handling, compressed storage, experiment configuration, and reproducible research workflows.

Co-lead of the [Human Radiome Project](https://human-radiome-project.de/), which aims to develop a radiological 3D vision foundation model trained on 4.8 million 3D images to improve diagnostics and support treatment decisions across diverse populations.

Frequent maintainer, contributor and daily user of [nnU-Net](https://github.com/MIC-DKFZ/nnUNet) [![Stars](https://img.shields.io/github/stars/MIC-DKFZ/nnUNet?style=social)](https://github.com/MIC-DKFZ/nnUNet), and many of my projects build upon its philosophy of strong, generalizable baselines extended toward interactive and foundation-model–based systems.


## 📌 Selection of my repositories

### 🔬 Research & Application
- [ScribbleBench](https://github.com/MIC-DKFZ/ScribbleBench) [![Stars](https://img.shields.io/github/stars/MIC-DKFZ/ScribbleBench?style=social)](https://github.com/MIC-DKFZ/ScribbleBench) – Benchmark for scribble-supervised 3D medical image segmentation  
- [ParticleSeg3D](https://github.com/MIC-DKFZ/ParticleSeg3D) [![Stars](https://img.shields.io/github/stars/MIC-DKFZ/ParticleSeg3D?style=social)](https://github.com/MIC-DKFZ/ParticleSeg3D) – Particle-based instance-aware 3D segmentation  
- [M3D-CAM](https://github.com/MECLabTUDA/M3d-Cam) [![Stars](https://img.shields.io/github/stars/MECLabTUDA/M3d-Cam?style=social)](https://github.com/MECLabTUDA/M3d-Cam) – Class activation mapping and interpretability for 2D/3D CNNs  
- [napari-sam](https://github.com/MIC-DKFZ/napari-sam) [![Stars](https://img.shields.io/github/stars/MIC-DKFZ/napari-sam?style=social)](https://github.com/MIC-DKFZ/napari-sam) – Interactive segmentation in Napari using Segment Anything 

### 🛠️ Tooling & Infrastructure  
- [patchly](https://github.com/MIC-DKFZ/patchly) [![Stars](https://img.shields.io/github/stars/MIC-DKFZ/patchly?style=social)](https://github.com/MIC-DKFZ/patchly) – Patch-based processing for very large images and volumes
- [mlarray](https://github.com/MIC-DKFZ/mlarray) [![Stars](https://img.shields.io/github/stars/MIC-DKFZ/mlarray?style=social)](https://github.com/MIC-DKFZ/mlarray) – Fast, compressed storage for large medical or science images using Blosc2 
- [MedVol](https://github.com/MIC-DKFZ/MedVol) [![Stars](https://img.shields.io/github/stars/MIC-DKFZ/MedVol?style=social)](https://github.com/MIC-DKFZ/MedVol) – Lightweight medical image volume reader/writer with simple usage 
- [confly](https://github.com/MIC-DKFZ/confly) [![Stars](https://img.shields.io/github/stars/MIC-DKFZ/confly?style=social)](https://github.com/MIC-DKFZ/confly) – Configuration management for ML projects, more intuitive than Hydra
- [napari-stream](https://github.com/MIC-DKFZ/napari-stream) [![Stars](https://img.shields.io/github/stars/MIC-DKFZ/napari-stream?style=social)](https://github.com/MIC-DKFZ/napari-stream) – Real-time streaming of image data over the network to Napari 
- [tqdmp](https://github.com/MIC-DKFZ/tqdmp) [![Stars](https://img.shields.io/github/stars/MIC-DKFZ/tqdmp?style=social)](https://github.com/MIC-DKFZ/tqdmp) – Multiprocessing-friendly progress bars  
- [human-readable-id](https://github.com/Karol-G/human-readable-id) [![Stars](https://img.shields.io/github/stars/Karol-G/human-readable-id?style=social)](https://github.com/Karol-G/human-readable-id) – Simple, readable, reproducible experiment identifiers  

