## 👋 Real-Time Hand Gesture Recognition for Mouse Control

This is a Python-based virtual mouse that uses your webcam to track your hand in real time. By recognizing specific gestures, it moves your cursor and even clicks-no physical mouse required. It’s built using OpenCV, MediaPipe, and Autopy, so you get fast, accurate hand tracking with minimal setup.

---

### **How does it work?**

- **HandTracking.py**: Detects your hand, pinpoints finger positions, and figures out which fingers are up.
- **Virtual_Mouse.py**: Maps your hand’s position to your screen. Move your index finger to move the cursor. Pinch your index and middle fingers together to click. All in real time!

**Gestures Supported:**

| Gesture                                 | Action              |
|------------------------------------------|---------------------|
| Index finger up, middle down             | Move cursor         |
| Index & middle fingers up, close together| Mouse click         |

---

### **Getting Started**

**1. Clone the repo**

```bash
git clone https://github.com/sruthivellore/Real-Time-Hand-Gesture-Recognition-for-Mouse-Control.git
cd Real-Time-Hand-Gesture-Recognition-for-Mouse-Control
```

**2. Install requirements**

```bash
pip install opencv-python mediapipe autopy numpy
```

**3. Run the virtual mouse**

```bash
python Virtual_Mouse.py
```

---

### **How to Use**

- Make sure your webcam is connected.
- Raise your index finger to move the cursor.
- Bring your index and middle fingers together to perform a click.
- Watch the magic happen on your screen!

---

### **Troubleshooting**

- If the cursor is jumpy, try adjusting the `smoothening` parameter in `Virtual_Mouse.py`.
- Make sure your hand is well-lit and visible to the camera.
- Only one hand at a time-no multitasking (yet).

---

> “Why click when you can wave?”

---

Happy coding-and happy waving!
