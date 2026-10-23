### Hi, I'm Kai-Chun Chang 👋

I'm a **hardware engineer in training**: I design the mechanics, wire up the electronics and make the whole system work together.

- 🎓 M.S. in Biomedical Engineering at **National Taiwan University** (graduating June 2027). B.S. in Biomechatronic Engineering at NTU, plus an exchange semester at TU Berlin.
- 🔧 I take products from **SolidWorks CAD and prototyping** through **hardware bring-up and system integration** (Raspberry Pi, Jetson Nano, Arduino, PCB) to **data-driven validation** in Python.
- 🧪 Thesis: magneto-acoustic imaging simulation. I'm building a coupled acoustic, magnetic, electric and solid-mechanics FEM model in openCFS (in progress) to find the setup that maximizes the received signal for analog front-end design.
- 🤖 I use AI and automation to make engineering faster:
  - **Simulation automation**: Python pipelines that run 900+ parallel FEM cases; profiling cut per-case time from 31 to 1.5 min.
  - **Computer vision on edge devices**: trained a YOLOv8 calf detector and converted it to NCNN for real-time inference on a Raspberry Pi 4; trained a YOLOv7 fruit detector (mAP 98.3%) for a Jetson Nano robot.
  - **Deep learning for medical images and signals**: SAM2-based medical image segmentation, ECG/PPG signal processing and vibration-based motor fault classification.
- 🎯 Open to 2027 hardware roles in Taiwan: product design, test and validation, and system integration.

---

### 🛠️ Hardware projects

<table>
<tr>
<td width="33%" align="center">
<a href="https://github.com/handsomekk-ntu/smart-mirror-google-hps"><img src="https://github.com/handsomekk-ntu/smart-mirror-google-hps/raw/main/images/finished_mirror.jpg" alt="SuPi Mirror"></a><br>
<b><a href="https://github.com/handsomekk-ntu/smart-mirror-google-hps">SuPi Mirror</a></b><br>
<sub>Google Hardware Product Sprint 2023. Team leader and PM; enclosure CAD, laser-cut DXF and a photo-capture / QR-code module on a Raspberry Pi smart mirror.</sub>
</td>
<td width="33%" align="center">
<a href="https://github.com/handsomekk-ntu/vacuum-cleaning-robot-cad"><img src="https://github.com/handsomekk-ntu/vacuum-cleaning-robot-cad/raw/main/images/final_labeled.png" alt="Vacuum robot CAD"></a><br>
<b><a href="https://github.com/handsomekk-ntu/vacuum-cleaning-robot-cad">Vacuum-Cleaning Robot</a></b><br>
<sub>Project leader. 45-part SolidWorks model (IMU, display and ultrasonic mounts, 3D-printed and laser-cut parts); CFD nozzle iteration gave +23% suction.</sub>
</td>
<td width="33%" align="center">
<a href="https://github.com/handsomekk-ntu/wearable-ppg-sensor-board"><img src="https://github.com/handsomekk-ntu/wearable-ppg-sensor-board/raw/main/images/pcb_layout.png" alt="PPG sensor PCB layout"></a><br>
<b><a href="https://github.com/handsomekk-ntu/wearable-ppg-sensor-board">Wearable PPG Sensor Board</a></b><br>
<sub>52 mm round 2-layer PCB in Altium: MAX30102 over I2C to a Raspberry Pi Pico, with a full Gerber / ODB++ / STEP package.</sub>
</td>
</tr>
</table>

### 🤖 Embedded & edge AI

- **[calf-monitoring-iot-pipeline](https://github.com/handsomekk-ntu/calf-monitoring-iot-pipeline)**: edge-AI calf feeding monitor (YOLOv8 → NCNN on a Raspberry Pi) with an MQTT → InfluxDB → Grafana telemetry stack. Oral talk at BIOME 2023.
- **[smart-access-control](https://github.com/handsomekk-ntu/smart-access-control)**: a Raspberry Pi door system. A PIR trigger records a video clip, pushes it to LINE, and the owner approves entry remotely.

Also built (code not public): an autonomous field robot (team leader, Honorable Mention at the NTU Field Robot Competition) on a Jetson Nano and Arduino, with PID drive control and a YOLOv7 fruit detector.

---

### 🧰 Toolbox

**CAD & prototyping:** SolidWorks · Fusion 360 · Altium Designer · laser cutting · 3D printing<br>
**Simulation:** openCFS (FEM) · COMSOL · ANSYS Mechanical · SolidWorks Simulation / Flow Simulation<br>
**Hardware:** Raspberry Pi · NVIDIA Jetson Nano · Arduino · Raspberry Pi Pico · I2C / GPIO · oscilloscope · DC power supply<br>
**AI & automation:** PyTorch · YOLOv7 / YOLOv8 · NCNN (edge deployment) · OpenCV · SAM2 · batch FEM automation in Python<br>
**Software:** Python · C/C++ · MATLAB · Docker · Git · Linux

---

### 中文簡介

台大醫工所碩士生（2027 年 6 月畢業），大學念台大生機系。擅長從 SolidWorks 機構設計、原型製作，到 Raspberry Pi／Jetson 的硬體整合與 Python 數據驗證，把一個產品從頭做到能動。也會用 AI 與自動化加速工程工作：用 Python 自動化大量有限元素模擬、在 Raspberry Pi／Jetson 上部署 YOLO 電腦視覺模型，並做醫學影像分割與生理訊號分析。碩論做磁聲成像的多物理場有限元素模擬。正在尋找 2027 年台灣的硬體相關職缺（產品設計、測試驗證、系統整合，含研發替代役）。

📫 [LinkedIn](https://www.linkedin.com/in/kai-chun-kevin-chang-191527282) · kaichunchangwork@gmail.com
