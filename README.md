# COVID-19 Detection from Chest X-Rays (CNN)

This project implements a Convolutional Neural Network (CNN) to detect COVID-19 from chest X-ray images. Developed as part of a Kaggle exercise, the model achieves a high classification accuracy by distinguishing between positive and negative cases.

## 📊 Performance

* **Accuracy:** 98%
* **Model Type:** Convolutional Neural Network (CNN)

## 📁 Project Structure

* `nn.ipynb`: The main Jupyter Notebook containing data preprocessing, CNN architecture, and training logic.
* `datasets/datasets/`: Contains the split data (`train` and `test`). The 'test' folder is for validation. Images are ignored via `.gitignore` to keep the repo size manageable.
* `DLAI3_CXR_Validation_Set/`: These are the actual test pictures. The names are set like this from kaggle.
* `sub.csv`: The final submission/prediction output file.
* `.gitignore`: Configured to exclude image files (`.png`, `.jpg`, `.jpeg`) while preserving folder structure.

## 🛠️ Installation & Usage

1. **Clone the repository:**


2. **Download the Datasets:**
The image datasets are not included in this repository due to their size. You must download the data manually from Kaggle:
* **Dataset Link:** [COVID-19 Radiography Database](https://www.kaggle.com/competitions/csc532/overview)


3. **Setup Data:**
After downloading, place the X-ray images into the `datasets/datasets/train/` and `test/` folders under their respective `positive` and `negative` subdirectories to match the notebook's pathing.
4. **Dependencies:**
Ensure you have the following libraries installed:
* `TensorFlow` / `Keras`
* `NumPy`
* `Matplotlib`
* `Pandas`
