# 🧠 Brain Tumor Segmentation using U-Net (BraTS 2021)

This project implements a U-Net-based convolutional neural network to segment brain tumors from MRI scans using the BraTS 2021 dataset. It is a mini-project developed for academic purposes in the field of medical image analysis.

---

## 📂 Project Structure

| File/Folder        | Description                                      |
|--------------------|--------------------------------------------------|
| `code.ipynb`       | Jupyter Notebook containing all training and evaluation code |
| `model.pth`        | Trained PyTorch model weights                    |
| `report.pdf`       | Project report documenting objectives, methods, and results |
| `screenshots/`     | Visualization of input MRI, ground truth mask, and model prediction |

---

## 📊 Dataset: BraTS 2021

- **Modality Used**: FLAIR (single modality)
- **Format**: 3D MRI `.nii.gz` files (only 2D slices were used for training)
- **Task**: Binary segmentation (tumor vs. non-tumor)

---

## 🧠 Model Architecture

- **Model**: U-Net
- **Encoder**: ResNet34 via `segmentation_models_pytorch`
- **Loss Function**: Combination of Binary Cross Entropy (BCE) and Dice Loss
- **Evaluation Metrics**:
  - Dice Coefficient
  - Intersection over Union (IoU)

---

## 🔧 How to Run

 Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd <your-repo-folder>

Sample Output
  Visual comparisons of:
Input MRI slice
Ground truth mask
Predicted segmentation mask
(Screenshots available in the screenshots/ folder.)

## 🙋‍♂️ Author
Sreekar  
   git clone <your-repo-url>
   cd <your-repo-folder>
