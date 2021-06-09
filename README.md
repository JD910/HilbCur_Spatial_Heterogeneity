# HilbCur_Spatial_Heterogeneity
The source code for "Decoding Intra-tumoral Spatial Heterogeneity on Radiological Images Using the Hilbert Curve"

[![standard-readme compliant](https://img.shields.io/badge/Readme-standard-brightgreen.svg?style=flat-square)](https://github.com/JD910/ESLN/blob/main/README.md)
![](https://img.shields.io/badge/Nodejs-V14.16.0-brightgreen.svg?style=flat-square)

### 
**A Hilbert curve–based spatial correspondence mapping approach to decode and visualize three-dimensional intra-tumoral heterogeneity on radiological images into two-dimensional images while preserving the spatial locality between voxels.**<br />

* TumorDimReducebyHilbCurve.html is used to start the illustration of the dimensionality reduction using the Hilbert curve-based spatial correspondence mapping.<br />
* tumor_2D_Slice.json, tumor_3D_blocks.json, and tumor.json are the corresponding Hilbert volume data, consisting of axial plane images, 3D blocks, and the lung tumor, for this study.

<div align=center><img width="610" height="331" src="https://github.com/JD910/HilbCurv_Spatial_Heterogeneity/blob/main/Imgs/Figure 1.jpg"/></div>
<p align="center"> Figure 1. The Hilbert curve H(t) from level 1 to level 8.</p><br />

<div align=center><img width="610" height="428" src="https://github.com/JD910/HilbCurv_Spatial_Heterogeneity/blob/main/Imgs/Figure 3.jpg"/></div>
<p align="justify"> Figure 2. Two-dimensional Hilbert curves with level 1 (A) and level 2 (B) were respectively stretched into a straight line. Example of the dimensionality reduction of a three-dimensional mass with 16 voxels to a two-dimensional matrix with 4 × 4 pixels using a three-dimensional Hilbert curve (C).</p><br />

<div align=center><img width="610" height="176" src="https://github.com/JD910/HilbCurv_Spatial_Heterogeneity/blob/main/Imgs/Figure 5.jpg"/></div>
<p align="justify"> Figure 3. The lung tumor used for the illustration of three-dimensional (3D) Hilbert curve expansion (A). The Hilbert volume with level 6 defined in this study (B), and the lung tumor (in blue) was encapsulated in the Hilbert volume according to the 3D coordinates. The empty Hilbert matrix (C) to store the result of dimensionality reduction from (B).</p><br />

<div align=center><img width="610" height="167" src="https://github.com/JD910/HilbCurv_Spatial_Heterogeneity/blob/main/Imgs/Figure 6.jpg"/></div>
<p align="justify"> Figure 4. The Hilbert volume (A) consisted of only a single axial plane image. The result of the Hilbert matrix expanded from the Hilbert volume with the single images on the cross-sectional (B), coronal (C), and sagittal (D) axes, respectively.</p><br />

<div align=center><img width="610" height="179" src="https://github.com/JD910/HilbCurv_Spatial_Heterogeneity/blob/main/Imgs/Figure 7.jpg"/></div>
<p align="justify"> Figure 5. A Hilbert volume (A) consisting of four blocks of VA1, VA2, VA3, and VA4 was expanded into a Hilbert matrix (B). The corresponding expansions of the four blocks were MB1, MB2, MB3, and MB4 on the matrix, respectively. The Hilbert volume with the lung tumor inside (C) was expanded to a two-dimensional Hilbert matrix (D). The voxels of the lung tumor (C) in blue were expanded into the pixels of the matrix (D) in blue, accordingly.</p><br />
