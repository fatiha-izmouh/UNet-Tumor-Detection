# 🧠 UNet Tumor Detection
A deep learning project that uses a **UNet model** with **Convolutional Neural Networks (CNN)** for precise tumor detection and segmentation. The project leverages the **Focal Loss** function to address class imbalance, achieving robust results for medical image analysis. 🚑

## 🚀 Features
- **UNet Architecture**: Designed for pixel-wise segmentation of medical images.
- **Focal Loss**: Reduces false negatives by focusing on difficult-to-classify pixels.
- **Binary Mask Output**: Predicts tumor regions (0: background, 1: tumor).
- **Input Shape**: Accepts grayscale images of size (256, 256, 1).

## 🛠️ Technologies Used
- **TensorFlow / Keras**: For building and training the deep learning model.
- **NumPy**: For numerical operations.
- **Matplotlib**: For plotting results and visualizations.
- **OpenCV**: For image processing tasks.
- **Python**: Programming language for the pipeline.

## 📝 How to Use

1️⃣ **Clone the Repository**  
  
   git clone https://github.com/yourusername/UNet-Tumor-Detection.git.
   
   cd UNet-Tumor-Detection
   
2️⃣  **Install Dependencies**   

   git clone https://github.com/yourusername/UNet-Tumor-Detection.git
   cd UNet-Tumor-Detection
   
3️⃣ **Prepare the Data**

Place your training images in the data/images/ directory.
Place your training masks in the data/masks/ directory.

## 📊 Results
-**Output:** The model outputs binary segmentation masks highlighting tumor regions.
-**Loss Function:** Focal Loss improves the model’s focus on minor tumor regions.
-**Visualization:** Overlays of predictions on original images can be viewed for evaluation.

   
