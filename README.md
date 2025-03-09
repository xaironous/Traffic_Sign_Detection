# 🚦 Traffic Sign Detection using YOLOv8 & Faster R-CNN  

This project implements **traffic sign detection** using **YOLOv8** and **Faster R-CNN**. The models are trained on a dataset obtained from **Roboflow** and evaluated for object detection tasks. The project was developed in **Google Colab**, utilizing its cloud GPU for training.  

---

## 📌 Project Overview  
- ✅ **Goal**: Detect and classify traffic signs from images using deep learning models.  
- 📊 **Dataset**: Traffic sign dataset from **Roboflow**.  
- 🛠 **Models Used**:  
  - **YOLOv8** (Ultralytics)  
  - **Faster R-CNN** (Detectron2)  
- 📈 **Model Evaluation**:  
  - Used **training logs, validation results, and visual predictions**.  
  - Compared model performance on test images.  
- ⚠ **Note**: This project is designed for **Google Colab**, as it relies on **Colab-specific functions** such as `cv2_imshow()` and cloud-based model training.  

---

## 🛠️ Tools & Libraries Used  
- **Python**  
- **Google Colab (GPU)**  
- **Ultralytics YOLOv8** (for object detection)  
- **Detectron2** (for Faster R-CNN implementation)  
- **Roboflow API** (for dataset retrieval)  
- **OpenCV, Matplotlib** (for visualization)  

---

## 🔄 Workflow  
1️⃣ **Setup Environment**  
   - Installed necessary dependencies (`ultralytics`, `detectron2`, `roboflow`).  
   - Checked GPU availability (`nvidia-smi`).  

2️⃣ **Dataset Preparation**  
   - Downloaded traffic sign dataset using **Roboflow API**.  
   - Registered dataset using **COCO format** for Detectron2.  

3️⃣ **Model Training & Evaluation**  
   - Trained **YOLOv8** for 15 epochs.  
   - Trained **Faster R-CNN** using **Detectron2**.  
   - Compared results by visualizing detection outputs.  

4️⃣ **User Input for Model Selection**  
   - Allowed users to upload an image and choose between YOLO or Faster R-CNN.  
   - Displayed detected traffic signs on the input image.  
