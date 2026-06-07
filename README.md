# Gesture-Controlled Presentation

> Control your slides hands-free using real-time hand gesture recognition powered by computer vision and AI.

[![Python](https://img.shields.io/badge/Python-3.7+-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.x-5C3EE8?style=flat-square&logo=opencv&logoColor=white)](https://opencv.org/)

</div>

---

## About the Project

This system uses **OpenCV** and **CVZone's Hand Tracking Module** to detect and classify hand gestures in real time. Recognized gestures are mapped to presentation actions — such as navigating slides, drawing annotations, and more — enabling a seamless, interactive presentation experience.

---

## Features

| | Feature | Description |
|---|---|---|
| 👈 | **Slide Navigation** | Swipe left/right using thumb or pinky to go back or advance slides |
| ✍️ | **Freehand Annotation** | Draw on slides in real time using your index finger |
| 🗑️ | **Undo Annotation** | Remove the last drawn annotation with a 3-finger gesture |
| 🖱️ | **Pointer Mode** | Use two fingers to show a cursor on the slide |
| 🖥️ | **Live Camera Preview** | Small webcam feed overlaid on the slide for presenter awareness |
| 🎙️ | **Speech Recognition** | Voice command support *(test.py only)* |
| 🖊️ | **Pen & Slider Indicators** | On-screen indicators for active modes *(test.py only)* |

---

## Requirements

- Python 3.7+
- A working webcam

## Gesture Controls

<div align="center">

| Gesture | Fingers | Action |
|:---:|---|---|
| ☝️ | Index finger only | **Draw** annotation on slide |
| 👍 | Thumb only | **Previous** slide |
| 🤙 | Pinky only | **Next** slide |
| ✌️ | Index + Middle | **Pointer** cursor |
| 🤟 | Index + Middle + Ring | **Undo** last annotation |
| 🖐️ | All five fingers *(test.py)* | **Slider** indicator |
| 🤘 | Middle + Ring + Pinky *(test.py)* | **Pen** indicator |

</div>

> **Note:** Gestures are only registered when your hand is raised **above** the green threshold line (upper portion of the camera frame).

---

## Tech Stack

<div align="center">

| Technology | Role | Version |
|---|---|---|
| ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) | Core programming language | 3.7+ |
| ![OpenCV](https://img.shields.io/badge/-OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) | Video capture & image processing | 4.x |
| ![MediaPipe](https://img.shields.io/badge/-MediaPipe-4285F4?style=flat-square&logo=google&logoColor=white) | Hand landmark detection | Latest |
| CVZone | Hand tracking & finger detection | Latest |
| NumPy | Coordinate interpolation | Latest |

</div>

---

## References

1. [Gesture Recognition in Presentations](https://www.eurchembull.com/uploads/paper/e1872b82f7272d54308f653ddd1fc741.pdf)
2. [Hand Gesture-Based Control Systems](https://www.itm-conferences.org/articles/itmconf/pdf/2022/04/itmconf_icacc2022_03031.pdf)
3. [Computer Vision for HCI](https://ijsetr.com/uploads/251346IJSETR16450-43.pdf)
4. [Gesture-Based Slide Navigation](https://www.irjet.net/archives/V9/i7/IRJET-V9I7482.pdf)
5. [Real-time Hand Tracking](http://data.conferenceworld.in/BVCOE18/65.pdf)
6. [AI-Based Gesture Interfaces](https://airccse.org/journal/acij/papers/0512acij04.pdf)
7. [OpenCV Hand Detection](https://www.ijsr.net/archive/v4i1/SUB15298.pdf)
8. [Contactless Presentation Control](https://ijirt.org/master/publishedpaper/IJIRT156612_PAPER.pdf)

---

<div align="center">
  <sub>Built with ❤️ by Haridharan K.S </sub>
</div>
