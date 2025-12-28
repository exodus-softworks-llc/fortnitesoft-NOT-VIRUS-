*Lunar Neural Network Aimbot*

AI-powered aimbot that uses a neural network (YOLO-based detection) plus simulated mouse input to automatically aim at targets on screen in supported games.
This project is for educational and research purposes only.

    ⚠️ Using aimbots in online games can violate Terms of Service and may result in bans. Use at your own risk.

Features

    Real-time screen capture and object detection (players / humanoid targets).

    Optional CUDA acceleration when a compatible NVIDIA GPU and PyTorch CUDA build are available.

    Uses ddxoft style virtual input to move the mouse smoothly and mimic human aim behavior.

    Simple hotkeys:

        F1 – Toggle aimbot on/off while running.

        F2 – Quit the aimbot.

Requirements

    OS: Windows 10/11 64‑bit

    Python: 3.13.x (installed to C:\Users\ur username\AppData\Local\Programs\Python\Python313\)

    GPU (optional but recommended):

        NVIDIA RTX 50‑series card (e.g. RTX 5070 Ti) with updated drivers and CUDA 13.0 or later.

        PyTorch with CUDA support (e.g. torch 2.6.0+cu124 and torchvision 0.21.0+cu124).

    Python dependencies (installed via pip):

        torch, torchvision, torchaudio (CUDA build)

        ultralytics (YOLO models)

        opencv-python, numpy, Pillow, scipy, pandas, matplotlib, seaborn, tqdm, tensorboard, PyYAML

        mss (fast screen capture)



