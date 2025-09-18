# 🎛️ Slidex – Multi-Screen Kinetic LED System

Slidex is a **complex, multi-structure kinetic LED display system** designed and built for a large-scale corporate event at **Grand Hyatt Dubai**.  
It brings together **custom electronics, real-time wireless communication, and a dynamic control application** to control multiple rotating LED screens with synchronized visuals.

---

## 📖 Overview

- **Structures:** Up to 5 vertical totems  
- **Screens:** 4 LED screens per structure  
- **Motion Control:** Each screen can rotate 360° and move vertically with precise distance control  
- **Communication:** Low-latency wireless control using ESP-NOW  
- **Software:** Fully dynamic Python + Qt application with scenario and video playback support  

![System Overview](media/system_overview.png) <!-- Replace with actual image -->

---

## 🛠️ My Role

I was responsible for the **complete electronic and software design** of Slidex:

### 1️⃣ Custom PCB Design
- Designed a robust ESP32-based control board using **EasyEDA**
- Selected components rated for high temperature and harsh environments
- Integrated **Ethernet** and **RS485** support
- Prototyped, validated, and tested every feature (power, comms, I/O)

![PCB Design](media/pcb_design.png) <!-- Replace with your PCB render -->

---

### 2️⃣ Firmware Development
- Developed ESP32 firmware using the Arduino framework
- Implemented **ESP-NOW protocol** for fast, reliable wireless communication
- Added **OTA updates** to simplify field maintenance (no manual reflashing required)
- Created a modular and reusable codebase for multiple structures

![Firmware Flow](media/firmware_architecture.png) <!-- Optional diagram -->

---

### 3️⃣ Control Software (PySide6 GUI)
- Built a **Qt-based desktop application** (Python + PySide6)
- Provided **dynamic configuration** for different Slidex setups
- Added **scenario playback** and **video triggering** with **Resolume**
- Designed the UI for easy operator control during live events

![Control App Screenshot](media/software_ui.png) <!-- Replace with actual screenshot -->

---

### 4️⃣ Testing & Deployment
- Performed full system integration tests
- Managed on-site installation, calibration, and live operation during the Grand Hyatt Dubai event

![Live Event](media/live_event.jpg) <!-- Replace with event picture -->

---

## 🧰 Tech Stack

| Area        | Tools & Tech |
|------------|-------------|
| **Hardware Design** | EasyEDA |
| **Microcontroller** | ESP32 |
| **Communication** | ESP-NOW, RS485, Ethernet |
| **Firmware** | Arduino Framework |
| **Software** | Python, PySide6 (Qt for Python), Socket Programming |
| **Testing** | SocketTest, Oscilloscope |

---

## 🚀 Highlights

✅ **Full-Cycle Development** – From concept to final deployment  
✅ **Scalable System** – Easily adapts to different numbers of structures/screens  
✅ **Real-Time Wireless Control** – Ultra-low latency screen rotation and movement  
✅ **Robust Design** – Withstands heat and environmental stress during events  

---

## 🎥 Media

| Type | Link |
|------|------|
| PCB Render | ![PCB Render](media/pcb_render.png) |
| Firmware Demo | [Watch on YouTube](https://youtube.com/your-demo-link) |
| Control App | ![UI Screenshot](media/ui_screenshot.png) |
| Live Event Video | [Watch Deployment Video](https://youtube.com/your-event-link) |

---

## 📂 Repository Structure

```plaintext
Slidex/
├── firmware/         # ESP32 source code
├── pcb/              # EasyEDA project files, Gerbers (if shareable)
├── software/         # Python Qt control application
├── docs/             # Architecture diagrams, wiring schematics
├── media/            # Images, videos, screenshots
└── README.md
