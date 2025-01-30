# 🎭 Real-Time Segmentation using MediaPipe & OpenCV  


## 🚀 Overview  
This project implements **real-time background segmentation** using **MediaPipe's Selfie Segmentation** and **OpenCV**.  
It allows users to dynamically switch between different background modes, such as:  

✅ **Blurred background**  
✅ **Custom image background**  
✅ **Original background**  

## 🛠️ Features  
- 🔥 **Real-time segmentation** using MediaPipe  
- 🎭 **Dynamic background switching** (Blurred, Image, Original)  
- 🖼️ **Custom image support** for background replacement  
- 🏎️ **Optimized for speed and smooth performance**  

## 🎮 Keyboard Controls  
| Key | Function |  
|-----|----------|  
| `b` | Blur background |  
| `i` | Use image background (if available) |  
| `o` | Keep original background |  
| `q` | Quit the program |  

## 🏗️ How It Works
- Captures video from webcam using OpenCV.
- Processes each frame with MediaPipe Selfie Segmentation.
- Applies a segmentation mask to separate the foreground (user) from the background.
- Blends the foreground with different backgrounds based on user input.

## 🔥 Future Enhancements
🎨 Add multiple image backgrounds & allow dynamic switching.
📹 Use real-time video as background.
🎛️ GUI controls for adjusting blur intensity.