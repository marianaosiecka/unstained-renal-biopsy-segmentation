# Unstained renal brightfield microscopy images segmentation
This code is part of experimental research that applies state-of-the-art segmentation models and machine learning techniques to segment unstained renal biopsy samples.

There are two segmentation approaches in this repository, a **shallow approach** using machine learning techniques such as **K-NN** and **K-Means**, and a **deep-learning** approach using **SAM**, **SAM2**, and **U-Net**.

For further instructions on how to execute our code access the corresponding READMEs.
* [Shallow Approach README](https://github.com/marianaosiecka/unstained-renal-biopsy-segmentation/tree/main/shallow-techniques)
* [Deep Learning Approach README](https://github.com/marianaosiecka/unstained-renal-biopsy-segmentation/tree/main/deep-learning)

---

The shallow approach code was developed by **Enzo Lopes** and **Yunnie Zita**.

The deep learning approach code was developed by **Mariana Carvalho**.

---

The **data collection** in this repository comprises samples of Formalin-fixated paraffin-embedded (FFPE) mature kidney tissue with normal histomorphological appearance. These samples were recovered from nephrectomy specimens for renal cancer and kindly provided by the Department of Pathological Anatomy of Centro Hospitalar Universitário de São João (CHUSJ). 
The glass microscope slides were converted into high-resolution digital images by high-speed scanning using a Nanozoomer S60 Digital Slide Scanner (Hamamatsu Photonics; Hamamatsu, Japan) at 40x magnification. A total of 13 WSIs were produced, and tiles of 1024x1024 dimensions were extracted from them. The dataset contains both the original tiles and corresponding annotations, where **5 classes where considered: glomeruli (blue), tubules (magenta), interstitium (green), vessels (orange) and ignore/empty space (yellow)**.


This [file](https://github.com/marianaosiecka/unstained-renal-biopsy-segmentation/blob/main/dataset/Info%20Dataset.xlsx) summarises information regarding the dataset. 


