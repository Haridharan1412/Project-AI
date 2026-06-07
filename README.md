<div align="center">

<!-- ANIMATED BANNER - uses only SMIL animations, GitHub-safe -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 200" width="800" height="200">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0f0c29"/>
      <stop offset="50%" stop-color="#302b63"/>
      <stop offset="100%" stop-color="#1a1a2e"/>
    </linearGradient>
  </defs>

  <!-- Background -->
  <rect width="800" height="200" rx="16" fill="url(#bg)"/>

  <!-- Glow orbs -->
  <circle cx="680" cy="80" r="90" fill="rgba(130,100,255,0.07)"/>
  <circle cx="100" cy="160" r="60" fill="rgba(80,180,255,0.05)"/>

  <!-- Outer pulse ring -->
  <circle cx="120" cy="100" r="58" fill="none" stroke="rgba(160,130,255,0.35)" stroke-width="1.5">
    <animate attributeName="r" values="55;63;55" dur="2.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.5;1;0.5" dur="2.5s" repeatCount="indefinite"/>
  </circle>
  <!-- Inner ring -->
  <circle cx="120" cy="100" r="46" fill="rgba(100,70,200,0.22)" stroke="rgba(160,130,255,0.5)" stroke-width="1"/>

  <!-- Floating hand group -->
  <g>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,-7; 0,0" dur="3s" repeatCount="indefinite" calcMode="spline" keySplines="0.4 0 0.6 1; 0.4 0 0.6 1"/>
    <!-- Fingers -->
    <rect x="109" y="68" width="9" height="28" rx="4.5" fill="#ffdcb4"/>
    <rect x="120" y="72" width="9" height="25" rx="4.5" fill="#ffdcb4"/>
    <rect x="98" y="72" width="9" height="25" rx="4.5" fill="#ffdcb4"/>
    <rect x="87" y="78" width="8" height="20" rx="4" fill="#ffdcb4"/>
    <!-- Thumb -->
    <rect x="130" y="82" width="8" height="18" rx="4" fill="#ffdcb4" transform="rotate(20,134,91)"/>
    <!-- Palm -->
    <rect x="87" y="94" width="46" height="24" rx="8" fill="#ffdcb4"/>
    <!-- Annotation dot -->
    <circle cx="109" cy="68" r="4" fill="rgba(255,80,80,0.9)">
      <animate attributeName="r" values="3;5;3" dur="1.4s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="1;0.5;1" dur="1.4s" repeatCount="indefinite"/>
    </circle>
    <!-- Annotation path drawn with SMIL -->
    <path d="M109 68 Q120 50 135 62 Q148 74 132 84" fill="none" stroke="rgba(255,80,80,0.85)" stroke-width="2.5" stroke-linecap="round"
      stroke-dasharray="120" stroke-dashoffset="120">
      <animate attributeName="stroke-dashoffset" values="120;0;120" dur="2.5s" repeatCount="indefinite" calcMode="spline" keySplines="0.4 0 0.6 1; 0.4 0 0.6 1"/>
    </path>
  </g>

  <!-- Project title -->
  <text x="210" y="78" font-family="system-ui,sans-serif" font-size="26" font-weight="700" fill="white" opacity="0">
    Presentation Dynamics
    <animate attributeName="opacity" values="0;1" dur="0.8s" begin="0.1s" fill="freeze"/>
  </text>
  <text x="210" y="110" font-family="system-ui,sans-serif" font-size="20" font-weight="400" fill="rgba(200,185,255,0.88)" opacity="0">
    through Gesture Control
    <animate attributeName="opacity" values="0;1" dur="0.8s" begin="0.4s" fill="freeze"/>
  </text>
  <text x="212" y="138" font-family="system-ui,sans-serif" font-size="12" fill="rgba(180,165,255,0.6)" opacity="0">
    Control slides hands-free  ·  Computer Vision  ·  AI-Powered
    <animate attributeName="opacity" values="0;1" dur="0.8s" begin="0.7s" fill="freeze"/>
  </text>

  <!-- Tech pill badges -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;1" dur="0.6s" begin="0.9s" fill="freeze"/>
    <rect x="210" y="152" width="62" height="20" rx="10" fill="rgba(99,70,255,0.32)" stroke="rgba(130,100,255,0.55)" stroke-width="1"/>
    <text x="241" y="166" font-family="system-ui,sans-serif" font-size="10" fill="#c4b5fd" text-anchor="middle">Python</text>

    <rect x="280" y="152" width="64" height="20" rx="10" fill="rgba(20,160,100,0.25)" stroke="rgba(20,200,120,0.45)" stroke-width="1"/>
    <text x="312" y="166" font-family="system-ui,sans-serif" font-size="10" fill="#6ee7b7" text-anchor="middle">OpenCV</text>

    <rect x="352" y="152" width="74" height="20" rx="10" fill="rgba(30,120,220,0.25)" stroke="rgba(60,150,255,0.45)" stroke-width="1"/>
    <text x="389" y="166" font-family="system-ui,sans-serif" font-size="10" fill="#93c5fd" text-anchor="middle">MediaPipe</text>

    <rect x="434" y="152" width="64" height="20" rx="10" fill="rgba(220,80,80,0.22)" stroke="rgba(255,100,100,0.45)" stroke-width="1"/>
    <text x="466" y="166" font-family="system-ui,sans-serif" font-size="10" fill="#fca5a5" text-anchor="middle">CVZone</text>

    <rect x="506" y="152" width="70" height="20" rx="10" fill="rgba(34,197,94,0.2)" stroke="rgba(34,197,94,0.45)" stroke-width="1"/>
    <text x="541" y="166" font-family="system-ui,sans-serif" font-size="10" fill="#86efac" text-anchor="middle">Real-time</text>
  </g>
</svg>

# Gesture-Controlled Presentation

> Control your slides hands-free using real-time hand gesture recognition powered by computer vision and AI.

[![Python](https://img.shields.io/badge/Python-3.7+-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.x-5C3EE8?style=flat-square&logo=opencv&logoColor=white)](https://opencv.org/)
[![MediaPipe](https://img.shields.io/badge/MediaPipe-Google-4285F4?style=flat-square&logo=google&logoColor=white)](https://mediapipe.dev/)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

</div>

---

## About the Project

This system uses **OpenCV** and **CVZone's Hand Tracking Module** to detect and classify hand gestures in real time. Recognized gestures are mapped to presentation actions — such as navigating slides, drawing annotations, and more — enabling a seamless, interactive presentation experience.

**Team:** Haridharan K.S & Karthikeyan

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

## Project Structure

```
gesture-presentation/
├── main.py            # Core gesture-controlled presentation app
├── test.py            # Extended version with speech recognition & extra gestures
└── Presentation/      # Place your exported slide images here (PNG/JPG)
```

---

## Requirements

- Python 3.7+
- A working webcam

### Dependencies

```bash
pip install opencv-python cvzone mediapipe numpy speechrecognition
```

---

## Installation & Setup

**1. Clone the repository**
```bash
git clone https://github.com/your-username/gesture-presentation.git
cd gesture-presentation
```

**2. Install dependencies**
```bash
pip install opencv-python cvzone mediapipe numpy speechrecognition
```

**3. Add your presentation slides**
- Export your PowerPoint slides as images (PNG or JPG)
- Place them inside a folder named `Presentation/` in the project root
- Name them sequentially (e.g., `slide1.png`, `slide2.png`, ...)

**4. Run the application**
```bash
python main.py
```
Or for the extended version with speech recognition:
```bash
python test.py
```

**5. Quit** — Press `q` to exit

---

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
| SpeechRecognition | Voice command support | Latest |

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
  <sub>Built with ❤️ by Haridharan K.S &amp; Karthikeyan</sub>
</div>
