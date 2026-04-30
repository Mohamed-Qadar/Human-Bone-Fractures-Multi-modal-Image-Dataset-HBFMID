# Human Bone Fracture Classification (HBFMID)

##  Overview

This project focuses on classifying human bone fractures using the **Human Bone Fractures Multi-modal Image Dataset (HBFMID)**.
A deep learning model (CNN-based) is used to detect and classify different types of fractures from medical images.

---

##  Dataset

* **Train:** 1344 images
* **Validation:** 128 images
* **Test:** 64 images

### Classes (10 total)

* FractureType2 (531)
* Fractured (297)
* Elbow (150)
* FractureType3 (90)
* Hand (75)
* FractureType1 (66)
* Shoulder (54)
* Intact (48)
* Femur (21)
* Another (12)

---


##  Model

* Architecture: Convolutional Neural Network (CNN) - ResNet50 based
* Task: Multi-class classification
* Approach: Transfer learning with ImageNet pre-trained weights
* Preprocessing: Image resizing, normalization, and data augmentation applied

---
 
