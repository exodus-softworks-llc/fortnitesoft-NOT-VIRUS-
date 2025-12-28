# 🧠 YoloV12 AI Aimbot - Exodus LITE

It features an updated triggerbot, modernized packages, and YOLOv12 support.

<div align="center">

<img src="https://ucarecdn.com/97ff66ce-04db-424f-97ad-3f246ebabef6/lunar_downloads.svg" alt="downloads" /><br>
<a href="https://discord.gg/aiaimbot">
  <img src="https://ucarecdn.com/c6b01f6a-a399-46e7-b89b-3f39b198888e/lunar_discord.svg" alt="Join Discord" />
</a>

</div>

---

Lunar uses screen capture + YOLO object detection to locate enemies in real-time.

> It doesn’t touch memory or inject code — think of it as a robot that watches your screen and gives you precise X,Y coordinates of targets.

🎯 Preconfigured for **Fortnite** — some sensitivity tuning may be needed for other games.

---

## 🔧 YOLOv12 Support

Exodus LITE works with:
- [YOLOv8](https://github.com/ultralytics/ultralytics)
- [YOLOv10](https://github.com/ultralytics/ultralytics)
- [YOLOv12](https://github.com/ultralytics/ultralytics)

---

![Exodus LITE Banner](https://github.com/user-attachments/assets/05864acf-cdd1-484f-be79-fa4a9643e8c2)
![Thumbnail](https://github.com/user-attachments/assets/afa30dd2-8168-4c64-999e-bedb0bef4dec)

---

<details>
<summary>📦 <strong>Installation</strong></summary>

1. Install [Python 3.10.5](https://www.python.org/downloads/release/python-3105/)
2. Install **CUDA Toolkit** 11.8, 12.4, or 12.6 (**12.6 recommended**)
3. Navigate to the root folder and run:
    ```
    install_requirements.bat
    ```
4. Launch with:
    ```
    start.bat
    ```

</details>

---

<details>
<summary>⚙️ <strong>Usage / Troubleshooting</strong></summary>

### If you get `CUDA IS UNAVAILABLE` error:
1. Make sure your installed CUDA version matches.
2. Visit [pytorch.org](https://pytorch.org/get-started/locally/) and install the right build.

Command for CUDA 12.6:
```
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu126
```

---

### If the console closes instantly:
```
python exodus.py
```

---

### To configure sensitivity:
```
python exodus.py setup
```

---

### To collect training images:
```
python exodus.py collect_data
```

</details>

---
