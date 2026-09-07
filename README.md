# 🎭 Face Expression Detection Suite

An end-to-end computer vision project for real-time and multi-format facial expression detection. Powered by a custom-trained **YOLOv8** model and built with a unified, interactive **Gradio** web application interface.

---

## 📌 Features

* **Multi-Format Input Support:**
  * **🖼️ Image Upload:** Analyze uploaded images for individual or multiple face expressions.
  * **🎥 Live Webcam Feed:** Real-time facial expression tracking via live streaming camera feed.
  * **🎞️ Video File Processing:** Frame-by-frame expression detection and automated output video generation.
* **7 Facial Expression Classes:**
  * 😠 `Angry`
  * 🤢 `Disgust`
  * 😨 `Fear`
  * 😄 `Happiness`
  * 😐 `Neutral`
  * 😢 `Sadness`
  * 😲 `Surprised`
* **Real-time Visualization:** Displays annotated bounding boxes and mapped expression labels for detected faces.

---

## 🛠️ Project Architecture & Tech Stack

* **Deep Learning Model:** [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics) (Custom trained weights)
* **Computer Vision:** OpenCV (`cv2`), NumPy
* **Web Interface & UI:** [Gradio](https://www.gradio.app/) (`gr.Blocks`, `gr.Tabs`)
* **Programming Language:** Python 3.9+

---

## 📂 Repository Structure

```text
├── app.py              # Main Gradio application code
├── best (1).pt         # Trained YOLOv8 model weights
├── requirements.txt    # Project dependencies
└── README.md           # Project documentation
