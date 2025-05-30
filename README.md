
# ✋ Volume and Brightness Control Using Hand Gestures

This Python project enables **hands-free control** of system **volume** and **screen brightness** using simple hand gestures via your webcam.

- 🙌 Use your **left hand** to adjust **brightness**
- ✋ Use your **right hand** to control **volume**

It leverages:
- **MediaPipe** for real-time hand tracking
- **pycaw** for controlling audio volume
- **screen-brightness-control** for adjusting screen brightness
- **OpenCV** for webcam integration and feedback

---

## 📸 Demo

> Coming soon: Demo GIF showing both hands adjusting volume and brightness

---

## 🛠️ Features

- Real-time gesture recognition using webcam
- Adjust screen brightness with left-hand pinch gesture
- Adjust system volume with right-hand pinch gesture
- Visual interface with OpenCV drawing
- Lightweight and responsive on most Windows machines

---

## 📦 Requirements

Install using `requirements.txt`:

```bash
pip install -r requirements.txt



Or manually install:

bash
Copy
Edit
pip install opencv-python mediapipe numpy screen-brightness-control pycaw comtypes absl-py
✅ Windows OS is recommended for full pycaw and screen-brightness-control compatibility.






🚀 How to Run
Clone the repository

bash
Copy
Edit
git clone https://github.com/<your-username>/Volume_and_Brightness_Control_Using_Hand_Gestures.git
cd Volume_and_Brightness_Control_Using_Hand_Gestures
Set up a virtual environment

bash
Copy
Edit
pip install virtualenv
virtualenv venv
venv\Scripts\activate  # For Windows
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the script

bash
Copy
Edit
python brightness_and_volume_control.py
