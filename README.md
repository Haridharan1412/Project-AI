<div align="center">

<!-- ANIMATED LOGO BANNER -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 200" width="800" height="200">
  <defs>
    <style>
      @keyframes float { 0%,100%{transform:translateY(0)} 50%{transform:translateY(-8px)} }
      @keyframes pulse { 0%,100%{opacity:0.6;r:60} 50%{opacity:1;r:65} }
      @keyframes draw { from{stroke-dashoffset:200} to{stroke-dashoffset:0} }
      @keyframes fadeIn { from{opacity:0;transform:translateY(10px)} to{opacity:1;transform:translateY(0)} }
      .hand { animation: float 3s ease-in-out infinite; transform-origin: 120px 100px; }
      .ring1 { animation: pulse 2.5s ease-in-out infinite; }
      .draw-path { stroke-dasharray:200; animation: draw 2s ease-in-out infinite alternate; }
      .title { animation: fadeIn 1s ease both; }
      .sub { animation: fadeIn 1s 0.3s ease both; }
    </style>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0f0c29"/>
      <stop offset="50%" stop-color="#302b63"/>
      <stop offset="100%" stop-color="#1a1a2e"/>
    </linearGradient>
  </defs>

  <!-- Background -->
  <rect width="800" height="200" rx="16" fill="url(#bg)"/>

  <!-- Glow circles -->
  <circle cx="680" cy="80" r="80" fill="rgba(130,100,255,0.08)"/>
  <circle cx="100" cy="160" r="60" fill="rgba(80,180,255,0.06)"/>

  <!-- Animated hand group -->
  <g class="hand">
    <!-- Outer pulse ring -->
    <circle cx="120" cy="100" r="60" fill="none" stroke="rgba(160,130,255,0.3)" stroke-width="1.5" class="ring1"/>
    <circle cx="120" cy="100" r="48" fill="rgba(100,70,200,0.25)" stroke="rgba(160,130,255,0.5)" stroke-width="1"/>
    <!-- Hand fingers -->
    <rect x="109" y="68" width="9" height="28" rx="4.5" fill="rgba(255,220,180,0.95)"/>
    <rect x="120" y="72" width="9" height="25" rx="4.5" fill="rgba(255,220,180,0.95)"/>
    <rect x="98" y="72" width="9" height="25" rx="4.5" fill="rgba(255,220,180,0.95)"/>
    <rect x="87" y="78" width="8" height="20" rx="4" fill="rgba(255,220,180,0.95)"/>
    <rect x="87" y="96" width="44" height="22" rx="8" fill="rgba(255,220,180,0.95)"/>
    <!-- Annotation line -->
    <path d="M109 96 Q118 78 130 90 Q140 102 125 110" fill="none" stroke="rgba(255,80,80,0.9)" stroke-width="2.5" stroke-linecap="round" class="draw-path"/>
    <circle cx="109" cy="96" r="4" fill="rgba(255,80,80,0.9)"/>
  </g>

  <!-- Title text -->
  <text x="210" y="85" font-family="system-ui, sans-serif" font-size="28" font-weight="600" fill="white" class="title">Presentation Dynamics</text>
  <text x="210" y="118" font-family="system-ui, sans-serif" font-size="22" font-weight="400" fill="rgba(200,185,255,0.9)" class="sub">through Gesture Control</text>
  <text x="212" y="148" font-family="system-ui, sans-serif" font-size="13" fill="rgba(180,165,255,0.65)" class="sub">Control slides hands-free · Computer Vision · AI-Powered</text>

  <!-- Badges row -->
  <rect x="210" y="163" width="64" height="20" rx="10" fill="rgba(99,70,255,0.3)" stroke="rgba(130,100,255,0.5)" stroke-width="1"/>
  <text x="242" y="177" font-family="system-ui,sans-serif" font-size="10" fill="#c4b5fd" text-anchor="middle">Python</text>

  <rect x="282" y="163" width="64" height="20" rx="10" fill="rgba(20,160,100,0.25)" stroke="rgba(20,200,120,0.4)" stroke-width="1"/>
  <text x="314" y="177" font-family="system-ui,sans-serif" font-size="10" fill="#6ee7b7" text-anchor="middle">OpenCV</text>

  <rect x="354" y="163" width="68" height="20" rx="10" fill="rgba(30,120,220,0.25)" stroke="rgba(60,150,255,0.4)" stroke-width="1"/>
  <text x="388" y="177" font-family="system-ui,sans-serif" font-size="10" fill="#93c5fd" text-anchor="middle">MediaPipe</text>

  <rect x="430" y="163" width="64" height="20" rx="10" fill="rgba(220,80,80,0.2)" stroke="rgba(255,100,100,0.4)" stroke-width="1"/>
  <text x="462" y="177" font-family="system-ui,sans-serif" font-size="10" fill="#fca5a5" text-anchor="middle">CVZone</text>

  <rect x="502" y="163" width="72" height="20" rx="10" fill="rgba(34,197,94,0.2)" stroke="rgba(34,197,94,0.4)" stroke-width="1"/>
  <text x="538" y="177" font-family="system-ui,sans-serif" font-size="10" fill="#86efac" text-anchor="middle">Real-time</text>
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
