<div align="center">

<!-- Animated Header Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Gesture%20Controlled%20Presentation&fontSize=40&fontColor=fff&animation=twinkling&fontAlignY=35&desc=Control%20your%20slides%20hands-free%20with%20AI-powered%20hand%20tracking&descAlignY=55&descSize=16" width="100%"/>

<!-- Animated Typing SVG -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=6E40C9&center=true&vCenter=true&multiline=true&width=600&height=80&lines=👋+Wave+to+Navigate+Slides;✍️+Draw+Annotations+Mid-Presentation;🤖+Powered+by+Computer+Vision+%26+AI" alt="Typing SVG" />
</a>

<br/>

<!-- Core Badges -->
<p>
  <img src="https://img.shields.io/badge/Python-3.7+-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/OpenCV-4.x-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV"/>
  <img src="https://img.shields.io/badge/MediaPipe-Latest-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="MediaPipe"/>
  <img src="https://img.shields.io/badge/CVZone-Hand%20Tracking-FF6B6B?style=for-the-badge&logo=hand&logoColor=white" alt="CVZone"/>
</p>

<p>
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge&logo=checkmarx&logoColor=white" alt="Status"/>
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge&logo=opensourceinitiative&logoColor=white" alt="License"/>
  <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20macOS-blue?style=for-the-badge&logo=github&logoColor=white" alt="Platform"/>
</p>

</div>

---

## 🧠 About the Project

<img align="right" width="320" src="https://user-images.githubusercontent.com/74038190/229223156-0cbdaba9-3128-4d8e-8719-b6b4cf741b67.gif" alt="AI Gesture Demo" />

This system uses **OpenCV** and **CVZone's Hand Tracking Module** to detect and classify hand gestures in real time via your webcam. Recognized gestures are mapped to intuitive presentation actions — navigating slides, drawing freehand annotations, pointing, and more — enabling a truly **seamless, touch-free** presentation experience.

> *No clicker. No keyboard. Just your hands.*

Built as an exploration of Human-Computer Interaction (HCI), this project bridges **computer vision**, **machine learning**, and **real-time UI interaction** into a single, elegant pipeline.

<br clear="right"/>

---

## ✨ Features

<div align="center">

| | Feature | Description |
|:---:|:---|:---|
| 👈 | **Slide Navigation** | Swipe left/right using thumb or pinky to go back or advance slides |
| ✍️ | **Freehand Annotation** | Draw on slides in real time using your index finger |
| 🗑️ | **Undo Annotation** | Remove the last drawn annotation with a 3-finger gesture |
| 🖱️ | **Pointer Mode** | Use two fingers to display a live cursor on the slide |
| 🖥️ | **Live Camera Overlay** | Small webcam feed overlaid on the slide for presenter awareness |
| 🎙️ | **Speech Recognition** | Voice command support *(test.py only)* |
| 🖊️ | **Mode Indicators** | On-screen pen & slider indicators *(test.py only)* |

</div>

---

## 🖐️ Gesture Reference

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=14&pause=2000&color=6E40C9&center=true&vCenter=true&width=500&lines=Raise+your+hand+above+the+green+line+to+activate+gestures!" alt="Gesture Hint"/>

| Gesture | Visual | Fingers | Action |
|:---:|:---:|:---|:---|
| Draw | ☝️ | Index finger only | **Annotate** on slide |
| Previous | 👍 | Thumb only | **Previous** slide |
| Next | 🤙 | Pinky only | **Next** slide |
| Pointer | ✌️ | Index + Middle | **Cursor** on slide |
| Undo | 🤟 | Index + Middle + Ring | **Undo** annotation |
| Slider | 🖐️ | All five fingers *(test.py)* | **Slider** indicator |
| Pen | 🤘 | Middle + Ring + Pinky *(test.py)* | **Pen** indicator |

> ⚠️ **Note:** Gestures activate only when your hand is raised **above** the green threshold line in the upper portion of the camera frame.

</div>

---

## ⚙️ Requirements

```bash
Python 3.7+    # Core language
OpenCV 4.x     # Video capture & processing
MediaPipe      # Hand landmark detection
CVZone         # High-level hand tracking
NumPy          # Array & coordinate math
SpeechRecognition  # Voice commands (test.py)
A working webcam   # Required hardware
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/gesture-presentation.git
cd gesture-presentation
```

### 2. Install dependencies

```bash
pip install opencv-python cvzone mediapipe numpy SpeechRecognition
```

### 3. Add your presentation slides

Place your slide images (e.g., `slide1.jpg`, `slide2.jpg`, ...) inside the `Presentation/` folder.

### 4. Run the application

```bash
# Standard gesture control
python main.py

# Extended mode (pen indicator, slider, voice commands)
python test.py
```

---

## 🛠️ Tech Stack

<div align="center">

<p>
  <img src="https://skillicons.dev/icons?i=python,opencv&theme=dark" alt="Tech Stack Icons"/>
</p>

| Technology | Role | Version |
|:---:|:---|:---:|
| <img src="https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white"/> | Core programming language | `3.7+` |
| <img src="https://img.shields.io/badge/-OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white"/> | Video capture & image processing | `4.x` |
| <img src="https://img.shields.io/badge/-MediaPipe-4285F4?style=flat-square&logo=google&logoColor=white"/> | Hand landmark detection | `Latest` |
| <img src="https://img.shields.io/badge/-CVZone-FF6B6B?style=flat-square&logoColor=white"/> | Hand tracking & finger detection | `Latest` |
| <img src="https://img.shields.io/badge/-NumPy-013243?style=flat-square&logo=numpy&logoColor=white"/> | Coordinate interpolation | `Latest` |

</div>

---

## 📐 How It Works

```
┌─────────────────────────────────────────────────────────────┐
│                   GESTURE PIPELINE                          │
│                                                             │
│  📷 Webcam Input                                            │
│       │                                                     │
│       ▼                                                     │
│  🧠 MediaPipe → Hand Landmarks (21 keypoints)               │
│       │                                                     │
│       ▼                                                     │
│  👁️ CVZone → Finger State Detection                         │
│       │                                                     │
│       ▼                                                     │
│  🗺️ Gesture Mapping → Action Dispatcher                     │
│       │                                                     │
│       ▼                                                     │
│  🖥️ OpenCV → Render Slide + Overlay + Annotations           │
└─────────────────────────────────────────────────────────────┘
```

---

## 📚 References

1. [Gesture Recognition in Presentations](https://www.eurchembull.com/uploads/paper/e1872b82f7272d54308f653ddd1fc741.pdf)
2. [Hand Gesture-Based Control Systems](https://www.itm-conferences.org/articles/itmconf/pdf/2022/04/itmconf_icacc2022_03031.pdf)
3. [Computer Vision for HCI](https://ijsetr.com/uploads/251346IJSETR16450-43.pdf)
4. [Gesture-Based Slide Navigation](https://www.irjet.net/archives/V9/i7/IRJET-V9I7482.pdf)
5. [Real-time Hand Tracking](http://data.conferenceworld.in/BVCOE18/65.pdf)
6. [AI-Based Gesture Interfaces](https://airccse.org/journal/acij/papers/0512acij04.pdf)
7. [OpenCV Hand Detection](https://www.ijsr.net/archive/v4i1/SUB15298.pdf)
8. [Contactless Presentation Control](https://ijirt.org/master/publishedpaper/IJIRT156612_PAPER.pdf)

---

<!-- Animated Footer -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer&animation=twinkling" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=14&pause=1500&color=6E40C9&center=true&vCenter=true&width=440&lines=Built+with+❤️+by+Haridharan+K.S;Star+⭐+the+repo+if+you+found+it+useful!" alt="Footer Typing"/>

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/your-username)

<sub>© 2024 Haridharan K.S — Gesture-Controlled Presentation</sub>

</div>
