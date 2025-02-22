# CSCI611_Spring25_Gaurav_Patil

This repository contains code and resources for **image filtering** and **Convolutional Neural Networks (CNNs) training** on the CIFAR-10 dataset. It includes Jupyter notebooks for applying various image filtering techniques and building CNN models using different optimizers on both CPU and GPU.

---

## 📂 Project Structure

### 🔹 `image_filtering`
Contains implementations of image filtering techniques using OpenCV and NumPy.

- 📷 `building2.jpg` → Sample image used for filtering.
- 📄 `image_filtering.ipynb` → Jupyter Notebook demonstrating various image filtering techniques. Put image in same path

**Requirements:**
Before running the notebook, install the required dependencies:
```bash
pip install numpy opencv-python matplotlib
```
> **Note:** Ensure `building2.jpg` is present in the same directory as `image_filtering.ipynb` for proper execution.

---

### 🔹 `build_cnn`
Contains CNN training scripts using different optimizers and hardware setups.

#### 📝 Jupyter Notebooks (CPU Training)
- `build_cnn_epoch10-SGD.ipynb` → CNN trained for 10 epochs using **SGD optimizer** on CPU.
- `build_cnn_epoch10-adam.ipynb` → CNN trained for 10 epochs using **Adam optimizer** on CPU.

**Requirements:**
Install the necessary dependencies:
```bash
pip install torch numpy matplotlib
```

#### 📄 PDF Reports (GPU Training)
- `ADAM_py.pdf` → Results of CNN training using **Adam optimizer** on GPU.
- `SGD_py.pdf` → Results of CNN training using **SGD optimizer** on GPU.

---
