# 🎯 Object Detection using OpenCV & Python

This project demonstrates how to perform **real-time object detection** using OpenCV in Python. It includes functionality to detect objects through video frames or images using contour detection, color filtering, and more.

## 📌 Project Features

- Real-time object detection using webcam
- Adjustable color thresholds using trackbars
- Contour detection and bounding boxes
- HSV color space filtering
- Clean and modular code structure

## 🛠️ Tech Stack

- **Language**: Python 3.x  
- **Library**: OpenCV

## 📷 Sample Output

> Real-time video output with bounding boxes drawn around detected objects based on color thresholds.

## 🧠 How It Works

1. The webcam captures frames.
2. The frame is converted to HSV.
3. A mask is created using lower and upper HSV bounds.
4. Contours are detected and drawn on the original frame.

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/HafsaNoorMuhammad26/Object-Detection-using-OpenCV-Python.git
   cd Object-Detection-using-OpenCV-Python
````

2. **Install requirements**

   ```bash
   pip install opencv-python
   ```

3. **Run the object detection script**

   ```bash
   python object_detection.py
   ```

   *(Replace `object_detection.py` with your script filename if different)*

## 🎚️ Customize Detection

You can fine-tune the detection by adjusting HSV trackbars to isolate the color range you want to detect.

## 📁 File Structure

```
Object-Detection-using-OpenCV-Python/
│
├── object_detection.py       # Main object detection script
├── README.md                 # Project documentation
├── Images/                   # Sample images (if any)
└── ...
```

---

## 🙋‍♀️ Author

**Hafsa Noor Muhammad**
🎓 Final Year Software Engineering Student, UIT University
 
Feel free to reach out via 
🔗 [LinkedIn](https://www.linkedin.com/in/hafsa-noor-muhammad-67b96331a/) 
                    OR 
🔗 [GitHub](https://github.com/HafsaNoorMuhammad26)
---

⭐ *If you found this project helpful, don’t forget to star the repo and share with your peers!*
```
