---
title: "Semi-automatic intelligent labeling"
collection: projects
type: "SAM"
permalink: /projects/annotation
venue: "HKUST(GZ) Medical Data Inteligence Lab, "
date: 2023-11-01
location: "HKUST(GZ)"
---

MDI annotation platform SAM real-time recognition server ⚡ .
Current support:
- (1) 🌟 Real time annotation: multi-point annotation, single rectangle annotation
- (2) 🔥 Prompt with different positive and negative values
- (3) 🐬 the Whole Llide Image recognition

### WSI segmentation annotation
<img src="/images/wsi_segmentation.gif" width="75%"/>

### point & rectangle mode
<p float="left">
  <br>
  <img src="/images/demo_point1.jpg" width="37.25%" />
  <img src="/images/demo_point2.jpg" width="37.25%" />
  <br>
  <img src="/images/demo_rectangle1.jpg" width="37.25%" /> <img src="/images/demo_rectangle2.jpg" width="37.25%" />
</p>

### Supporting models:
  - 1.**[Meta SAM](https://github.com/facebookresearch/segment-anything)** (default service)
  - 2.**[mobile_sam](https://github.com/ChaoningZhang/MobileSAM)**
  - 3.**ONNX** mode
