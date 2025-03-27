# HAM10000 Skin Cancer Ensemble Classifier

## Overview
This project implements an **ensemble-based deep learning classifier** for **skin cancer detection** using the **HAM10000** dataset. It leverages multiple pre-trained CNN architectures to enhance classification accuracy.

## Features
✅ Uses **ResNet50, VGG16, and DenseNet121** for feature extraction.  
✅ Implements **ensemble learning** to combine model predictions.  
✅ Supports **data augmentation** for improved generalization.  
✅ Evaluates performance using **accuracy, precision, and recall**.  
 

## Dataset: HAM10000
The **HAM10000 dataset** consists of 10,015 labeled skin lesion images across(https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T),  **7 classes**:
- **akiec**: Actinic keratoses and intraepithelial carcinoma
- **bcc**: Basal cell carcinoma
- **bkl**: Benign keratosis-like lesions
- **df**: Dermatofibroma
- **mel**: Melanoma
- **nv**: Melanocytic nevi
- **vasc**: Vascular lesions

## Model Architecture
1. **Pre-trained Models:** ResNet50, VGG16, and DenseNet121.
2. **Feature Extraction:** Removes top layers and uses global average pooling.
3. **Fully Connected Layer:** Merges extracted features.
4. **Softmax Classifier:** Outputs final class probabilities.

## Installation

### Prerequisites
- Python 3.11+
- Google Colab (recommended) or local environment with GPU support
- TensorFlow 2.x
- Dependencies: numpy, pandas, scikit-learn, matplotlib, pydot, graphviz

### Setup
 **Clone the repository**
   ```sh
   git clone https://github.com/anandafc/ham10000-skin-cancer-ensemble-classifier.git
   cd ham10000-skin-cancer-ensemble-classifier
   ```


## Results & Performance
The ensemble model achieved an accuracy of **71.42%**. Performance metrics include:
- **Accuracy:** 71.42%
- **Precision & Recall:** Detailed per-class breakdown.



## Contribution
🚀 Contributions are welcome! Feel free to **fork**, create a new branch, and submit a **pull request**.  

## License
This project is released under the **MIT License**. See `LICENSE` for details.

## Contact
For any inquiries, reach out to `farhanacaa@gmail.com` or open an issue on GitHub.

