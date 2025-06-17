# Fine-Tuning EfficientNet-B1 for Breast Cancer Classification

In this notebook, I walk through the process of fine-tuning the EfficientNet-B1 model on the Breast Ultrasound Images Dataset (BUSI) to classify identified tumors in ultrasounds as benign or malignant.

Using AI models as a "second set of eyes" can help improve radiologist accuracy and ensure that less malignant tumors are misclassified as benign, allowing for more people to receive the treatment they need.

**Dataset:** Dataset of breast ultrasound images by Walid Al-Dhabyani, Mohammed Gomma, Hussien Khaled, and Aly Fahmy.

### Notebook Sections:
1. Check Version and Import Dependencies
2. Download, Preprocess, and Load Data
3. Initialize Training and Evaluation Device and Functions
4. Define Model Architecture and Prepare for Training
5. Cross-Validate Model
6. Final Model, Conclusions, and Bibliography

This model was developed on an M4 MacBook Pro, 16 GB Unified RAM, 10-core CPU 10-core GPU

### Bibliography
* Al-Dhabyani W, Gomaa M, Khaled H, Fahmy A. Dataset of breast ultrasound images. Data in Brief. 2020 Feb;28:104863. *DOI: 10.1016/j.dib.2019.104863.*
* Ma, H., et al. Fus2Net: A Novel Convolutional Neural Network for Classification of Benign and Malignant Breast Tumor in Ultrasound Images *ResearchGate preprint DOI:10.21203/rs.3.rs-853246/v1*
* Tan M, Le Quoc V. EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks.  *arXiv:1905.11946*