# *LANE TRACKİNG SYSTEM*

## 📌 Description

This project implements a **Lane Tracking System** using OpenCV. The system detects and tracks lane markings on the road, guiding the vehicle to stay within the correct lane. It works by analyzing the road's edges, detecting lane lines, and determining whether the vehicle needs to turn left or right, or go straight.

![Lane Tracking GIF](images/Lane-Tracking-System.gif)

---

## 🚀 Features:
- 🛣 **Lane detection** using Hough Transform  
- 🚗 **Dynamic lane following** logic based on the vehicle's position  
- 🔄 **Handles sharp turns** while maintaining lane stability 
- 🎥 **Real-time video processing** for vehicle guidance

---

## 🛠 How to Use:
1️⃣ **Clone** or download the repository to your local machine.  
2️⃣ **Ensure you have the required dependencies installed** (see below).  
3️⃣ **Run** `Lane_Tracking_System.py` to begin lane tracking.  
4️⃣ The system will process the video and display the detected lane and the vehicle's current direction (e.g., "Turn left", "Go straight", or "Turn right").  

---

## 📦 Dependencies:
- 🖼 **OpenCV** (for image processing and video manipulation)  
- 🔢 **Numpy** (for numerical operations) 

You can install the required libraries using pip:

`pip install opencv-python numpy`

---

## 🎥 Example Video:
- You can watch the result video of the lane tracking system here: https://drive.google.com/file/d/1e_MF0u9tM_CmEbJQJ3imbosI0Lmuh-b8/view?usp=sharing
- Additionally, if you'd like to experiment with the same video used in the project, you can download it here: https://drive.google.com/file/d/1tD4gUrlxqKey6m29MjTTZt9fQ11-sq8O/view?usp=sharing

---

## ⚠️ Notes:
- The project uses a sample video for lane tracking, but you can replace it with any road video to test the system's effectiveness.
- You might want to adjust parameters depending on the specific video or road conditions.

---
  

## 🔧 Improvements: 

Some inaccuracies may occur due to road conditions, but this project is open for further improvements. Contributions are welcome!

---
