# Awesome-Medical-Imaging-AI-Platform

## Top Medical Imaging AI Platforms Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Radiology AI, Diagnostic Imaging Analysis, Triage, Segmentation, Detection & Clinical Workflow Integration*  

**Last updated: August 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Medical Imaging AI**. These tools apply deep learning to CT, MRI, X-ray, and other modalities for detection, triage, segmentation, quantification, and decision support, helping radiologists and clinicians improve speed, accuracy, and prioritization of critical findings.



**Examples** include Aidoc, Arterys, Viz.ai, Subtle Medical, Qure.ai, Lunit, Nanox AI, Brainomix, Flywheel, Blackford Platform, Zebra Medical Vision, Gleamer, Oxipit, Rad AI, and Deepc (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for medical image AI frameworks, multi-organ segmentation, annotation tools, model deployment, and related open platforms — ideal for researchers, hospitals, and developers seeking transparent, standards-based alternatives or complementary components to commercial medical imaging AI solutions.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Aidoc](https://www.aidoc.com/)**  

  Leading radiology AI platform providing always-on triage and detection across multiple body regions and critical findings, widely deployed in hospitals.



- **[Arterys (Tempus Radiology)](https://www.arterys.com/)**  

  Cloud-native medical imaging AI platform with strong cardiac and multi-vendor algorithm marketplace capabilities.



- **[Viz.ai](https://www.viz.ai/)**  

  AI-powered care coordination platform specializing in stroke, neurovascular, and other time-sensitive imaging workflows with hospital-wide notifications.



- **[Subtle Medical](https://subtlemedical.com/)**  

  AI solutions focused on accelerating and enhancing MRI and PET image acquisition and reconstruction.



- **[Qure.ai](https://www.qure.ai/)**  

  AI-powered diagnostic imaging platform with broad global adoption, covering chest X-ray, CT, and other modalities for detection and triage.



- **[Lunit](https://www.lunit.io/)**  

  Medical AI company specializing in cancer detection and analysis on chest X-rays, mammography, and pathology images.



- **[Nanox AI](https://www.nanox.vision/)**  

  AI solutions for population health and opportunistic screening from medical imaging, often paired with advanced imaging hardware.



- **[Brainomix](https://www.brainomix.com/)**  

  AI platform focused on stroke imaging analysis and decision support for acute care pathways.



- **[Flywheel](https://flywheel.io/)**  

  Research and clinical imaging data platform that supports AI model development, management, and deployment workflows.



- **[Blackford Platform](https://www.blackfordanalysis.com/)**  

  AI orchestration and marketplace platform that integrates multiple third-party algorithms into existing radiology workflows.



- **[Zebra Medical Vision / Nanox AI lineage](https://www.nanox.vision/)**  

  Earlier and related AI imaging solutions covering a wide range of automated detection use cases.



- **[Gleamer](https://www.gleamer.ai/)**  

  AI suite for musculoskeletal and chest imaging that assists radiologists with detection and prioritization.



- **[Oxipit](https://oxipit.ai/)**  

  AI tools for chest X-ray analysis, including fully automated normal report generation in some cleared workflows.



- **[Rad AI](https://www.radai.com/)**  

  Generative AI platform focused on radiology reporting, impression generation, and workflow efficiency.



- **[Deepc](https://www.deepc.ai/)**  

  Radiology AI platform and orchestration layer that integrates multiple algorithms into clinical practice.



## Open-Source GitHub Projects



- **[Project MONAI](https://github.com/Project-MONAI)**  

  The leading open-source PyTorch-based framework for medical imaging AI, covering training (MONAI Core), intelligent annotation (MONAI Label), and deployment (MONAI Deploy).



- **[TotalSegmentator](https://github.com/wasserth/TotalSegmentator)**  

  Widely used open-source multi-organ segmentation model that segments 100+ anatomical structures from CT (and MRI variants) with high accuracy.



- **[3D Slicer](https://github.com/Slicer/Slicer)**  

  Powerful open-source platform for medical image visualization, analysis, and AI integration, extensively used in research and clinical prototyping.



- **[OHIF Viewer](https://github.com/OHIF/Viewers)**  

  Open-source, web-based DICOM viewer that supports AI overlays, segmentation, and integration with modern medical imaging workflows.



- **[MONAI Label](https://github.com/Project-MONAI/MONAILabel)**  

  Intelligent open-source annotation tool with active learning that integrates with 3D Slicer, OHIF, and other viewers for efficient dataset creation.



- **[nnU-Net](https://github.com/MIC-DKFZ/nnUNet)**  

  Self-configuring deep learning framework for biomedical image segmentation that remains a strong baseline and foundation for many medical AI models.



- **[MedSAM / MedSAM2 and related Segment-Anything adaptations](https://github.com/)**  

  Open-source adaptations of the Segment Anything Model family tailored for 2D and 3D medical image segmentation.



- **[MONAI Model Zoo](https://github.com/Project-MONAI/model-zoo)**  

  Collection of ready-to-use, community-contributed medical imaging models packaged in the MONAI Bundle format.



- **[ITK / SimpleITK](https://github.com/InsightSoftwareConsortium/ITK)**  

  Foundational open-source toolkit for medical image processing, registration, and analysis that underpins many higher-level AI pipelines.



- **[TorchIO](https://github.com/fepegar/torchio)**  

  Open-source library for loading, preprocessing, augmentation, and patch-based sampling of 3D medical images in PyTorch workflows.



- **[OHIF-AI and AI-enhanced Viewer Projects](https://github.com/CCI-Bonn/OHIF-AI)**  

  Extensions of the OHIF viewer that add interactive AI segmentation and report-generation capabilities.



- **[Research Segmentation & Detection Toolkits](https://github.com/)**  

  Numerous open-source implementations for brain tumor, lung nodule, vessel, and multi-organ segmentation used in academic and clinical research.



### Additional Strong Open-Source Options



- **End-to-end framework**: MONAI (Core + Label + Deploy) is the most comprehensive open ecosystem for medical imaging AI.

- **Ready-to-run models**: TotalSegmentator and the MONAI Model Zoo provide high-quality segmentation out of the box.

- **Visualization & annotation**: 3D Slicer and OHIF remain the standard open platforms for interactive work.

- **Foundational libraries**: nnU-Net, ITK, and TorchIO power countless research and production pipelines.

- Many specialized **radiology AI**, **pathology AI**, and **multi-modal** open-source projects continue to appear on GitHub.



**Frameworks for building custom systems**: Combine **MONAI** for training and deployment, **TotalSegmentator or MONAI Model Zoo** models for segmentation, **3D Slicer / OHIF** for visualization and annotation, and open DICOM infrastructure to create a complete research or prototype medical imaging AI platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Medical imaging AI systems are regulated medical devices in most jurisdictions; clinical use requires appropriate regulatory clearance (FDA, CE, etc.), validation, and integration with clinical workflows.

- Self-hosted open-source solutions are primarily suited for research, education, and development; production clinical deployment demands rigorous quality management, cybersecurity, and regulatory compliance.



---



**Made for radiologists, clinical AI teams, researchers, and healthcare technology developers.**  

Let's make medical imaging AI more open, reproducible, and collaborative.
