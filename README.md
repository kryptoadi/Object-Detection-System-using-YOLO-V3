# 🧠 Object Detection System using YOLOv3

An object detection system leveraging the **YOLOv3** (You Only Look Once) model to detect and classify objects in images in real-time. The system uses OpenCV and pre-trained weights to accurately identify multiple objects in a single frame.

---

## 📌 Features

- 🚀 Real-time object detection
- 📦 Detects multiple objects in one image
- 🖼️ Visualizes bounding boxes with labels and confidence scores
- 🔧 Easy to run and modify

---

## 🛠️ Technologies Used

- **Python**
- **OpenCV**
- **YOLOv3**
- **Pre-trained COCO dataset weights**

---

## 📁 Installation

### 🔧 Prerequisites
- Python 3.x
- `pip` package manager

### 📥 Clone the repository
```bash
git clone https://github.com/kryptoadi/Object-Detection-System-using-YOLO-V3.git
cd Object-Detection-System-using-YOLO-V3
```

### 📦 Install dependencies
```bash
pip install opencv-python
```

### 📥 Download YOLOv3 weights
Download the official YOLOv3 weights from:

```
https://pjreddie.com/media/files/yolov3.weights
```

Place the `yolov3.weights` file in the same directory as your Python script.

---

## ▶️ How to Use

### Run the detection script:
```bash
python yolo_opencv.py
```

### 📸 Input
The script uses `dog.jpg` by default. Replace this file with your own image or modify the script to choose a different one.

### 🖼️ Output
The output window will show:
- Detected objects
- Bounding boxes
- Class labels
- Confidence scores

---


## 🔄 Project Structure

```
├── coco.names               # Class labels
├── yolov3.cfg               # YOLOv3 configuration
├── yolov3.weights           # Pre-trained weights
├── yolo_opencv.py           # Main script
├── dog.jpg                  # Sample input image
```

---

## 🙌 Acknowledgments

- **YOLO** by Joseph Redmon & Ali Farhadi  
  Paper: [YOLOv3: An Incremental Improvement](https://arxiv.org/abs/1804.02767)
- **OpenCV** for real-time image processing

---


## 👤 Author

- **GitHub:** [@kryptoadi](https://github.com/kryptoadi)
- **Project Link:** [Object Detection System using YOLOv3](https://github.com/kryptoadi/Object-Detection-System-using-YOLO-V3)

---

> *This README was generated with ❤️ to enhance clarity and accessibility.*
