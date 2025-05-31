Here's a **perfect and professional `README.md` file** tailored for your GitHub repository based on the provided files: `CNN.ipynb`, `resUnet(3).ipynb`, and `app.py`. This README presents a clear project overview, setup instructions, and usage guide suitable for showcasing on GitHub.

---

```markdown
# 🧠 Brain Tumor Detection and Classification with GUI

This project is a comprehensive deep learning application for brain tumor **segmentation** and **classification** using MRI scans. It includes a **ResUNet** model for segmentation, a custom **CNN** for tumor classification, and a **Tkinter GUI** that allows users to interact with the system seamlessly.

## 🚀 Features

- **Automatic Brain Tumor Segmentation** using ResUNet.
- **Tumor Classification** into four categories:  
  - Glioma Tumor  
  - Meningioma Tumor  
  - Pituitary Tumor  
  - No Tumor
- **Tumor Size Estimation** as a percentage of brain region.
- **Graphical User Interface** for uploading images and visualizing results.
- Built using **Keras**, **OpenCV**, **PIL**, and **Tkinter**.

---

## 🗂️ Project Structure

```

.
├── CNN.ipynb              # Jupyter notebook for CNN-based classification
├── resUnet(3).ipynb       # Jupyter notebook for ResUNet-based segmentation
├── app.py                 # GUI application script
├── brain\_tumor\_cnn.h5     # Trained CNN model (not included, user must provide)
├── ResUnet.keras          # Trained ResUNet model (not included, user must provide)
├── brain.png              # Icon used in GUI
├── brain.ico              # App icon
├── plus.png               # Upload icon
├── loading.png            # Loading animation icon
├── lens.png               # GUI decoration

````

---

## 🖼️ GUI Preview

The GUI enables users to:
- Upload an MRI brain scan.
- View:
  - Original Image
  - Binary (Grayscale) Image
  - Segmented Tumor Mask
  - Tumor Area Highlighted
- See the **predicted tumor type** and **tumor size** percentage.

---

## ⚙️ Requirements

Install the required dependencies:

```bash
pip install -r requirements.txt
````

### Main Libraries Used:

* `tensorflow` / `keras`
* `opencv-python`
* `numpy`
* `Pillow`
* `matplotlib`
* `tkinter` (comes pre-installed with Python on most systems)

---

## 🧪 Running the Application

1. Ensure that the trained models are available:

   * `ResUnet.keras` for segmentation
   * `brain_tumor_cnn.h5` for classification

2. Place the model files in the correct paths as specified in `app.py`.

3. Run the GUI:

```bash
python app.py
```

4. Upload a brain MRI image (e.g., `.jpg`, `.png`) and view the results.

---

## 📒 Notebooks

* `CNN.ipynb`: Includes training logic and evaluation for the CNN classifier.
* `resUnet(3).ipynb`: Contains the model architecture and training logic for the ResUNet-based segmentation.

---

## 📌 Notes

* The GUI and scripts are configured with **hardcoded paths** for model files and icons. You may need to adjust the paths in `app.py` accordingly.
* Input images must be MRI scans with appropriate preprocessing (grayscale recommended).
* Accuracy and results may vary based on the quality of training data and model tuning.

---

## 📷 Example Output

| Original                 | Binary                 | Segmented               | Highlighted               |
| ------------------------ | ---------------------- | ----------------------- | ------------------------- |
| ![](assets/original.png) | ![](assets/binary.png) | ![](assets/segment.png) | ![](assets/highlight.png) |

> *(Add sample outputs in an `/assets` folder for better visualization on GitHub.)*

---

## ✨ Author

Developed by **\[Your Name]**
For academic and demonstration purposes.

---

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).

```

---

### ✅ Next Steps:

- Create a `requirements.txt` file for dependencies.
- Add a few example images and model weights if sharing publicly.
- Add screenshots in an `assets/` directory if you want visual previews in your README.

Would you like me to create the `requirements.txt` file or help you refactor the hardcoded model paths in `app.py`?
```
