# VisionID Pro

**VisionID Pro** is a professional-grade desktop application for real-time face detection, recognition, and daily logging. It combines computer vision, intelligent recognition, and a user-friendly GUI to monitor and record facial appearances with high accuracy.

---

## 📸 Features

- ✅ **Real-Time Face Detection** using OpenCV
- 👤 **Face Recognition** using known images
- 📁 **Auto-Snapshot & Save** on detection
- 📊 **Daily Logs** saved as CSV reports
- 🎨 **GUI Theme Switcher** (Dark / Light)
---

## 🧩 Technologies Used

- Python 3.8+
- OpenCV
- face_recognition
- Pillow (PIL)
- Tkinter (GUI)
- CSV logging

---

## 🚀 How to Run

1. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

2. **Add known faces**:  
   Place known images (e.g., `john.jpg`, `alice.png`) in `known_faces/`.

3. **Run the app**:
   ```bash
   python autosnap_gui.py
   ```

4. **Controls**:
   - ▶ Auto-Start Detection
   - ⏹ Stop Detection
   - ❌ Exit Application
   - 🎨 Change Theme (Dark / Light)

---

## 📦 Export as Windows `.exe`

To create a standalone executable:

```bash
pyinstaller --noconfirm --onefile --windowed --icon=icon.ico VisionID_Pro.spec
```

> Optional:
> - Edit the `.spec` file to bundle folders (`known_faces`, `logs`, `detected_faces`)

---

## 📊 Logs & Reporting

- All detected faces are saved to `detected_faces/` with timestamps.
- Daily logs are saved as CSVs under `logs/`:
  ```
  logs/detection_20250729.csv
  ```

---

## 🔐 Use Cases

- Office Entry Logging
- Classroom Attendance
- Lightweight Surveillance
- Personalized Recognition Apps

---

## 📜 License

MIT License © 2025  
Developed by Akrash Noor Awan

---

## 🤖 Powered by Vision

> _“VisionID Pro sees, remembers, and logs – so you don’t have to.”_

---

## 📄 requirements.txt

```
opencv-python
face_recognition
Pillow
```
