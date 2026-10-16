# 🏜️ RANN MAHAL

### Luxury Heritage Desert Sanctuary

*A cinematic digital experience inspired by the timeless beauty of Rajasthan's desert palaces.*

RANN MAHAL is a premium, immersive website designed to capture the elegance of a luxury heritage sanctuary through cinematic scroll animations, golden visual accents, interactive navigation, and atmospheric sound design.

Inspired by the visual storytelling of `ff.mp4`, the experience takes visitors on a journey through five cinematic chapters, revealing the palace, its grand entrance, serene water court, elegant colonnade, and sunset terrace.

**Where the desert keeps its gold.**

---

## ✨ Features

### 🎬 1. Cinematic Scroll Animation Engine

* High-fidelity animation powered by **143 preloaded WebP frames**.
* Scroll-linked frame rendering for a seamless cinematic experience.
* Canvas-based rendering for smooth transitions between scenes.
* Scroll position dynamically controls animation progress.
* Designed for responsive, immersive visual storytelling.

### 🏛️ 2. Five Cinematic Chapters

Experience the architectural beauty of RANN MAHAL through five carefully designed chapters.

| Chapter               | Experience                                  | Tagline                                  |
| --------------------- | ------------------------------------------- | ---------------------------------------- |
| I — The Palace        | The majestic desert palace                  | *Where the desert keeps its gold.*       |
| II — The Gate         | The monumental teak entrance                | *Nine feet of teak, opened once a day.*  |
| III — The Water Court | The tranquil palace courtyard               | *A courtyard built to hold the evening.* |
| IV — The Colonnade    | The architectural elegance of sixty columns | *Sixty columns. One view.*               |
| V — The Terrace       | The sunset-facing sanctuary terrace         | *Stay until the sun clears the fields.*  |

Each chapter introduces a new visual moment as visitors scroll through the experience.

### 🏆 3. Interactive Roman Numeral Navigation

* Elegant right-side navigation rail featuring Roman numerals I–V.
* Dynamic golden progress indicator.
* Traditional *jharokha*-inspired active chapter indicator.
* Clickable navigation for direct access to individual chapters.
* Smooth transitions between cinematic sections.

### 🪞 4. Premium Fixed Header

The website features a persistent header designed around a refined heritage aesthetic.

**Header elements include:**

* Quick navigation to The Palace, The Gate, and The Court.
* Signature brand identity: `— R A N N  M A H A L —`
* Elegant gold divider lines.
* Interactive reservation button.
* Ambient sound toggle.

### 🎵 5. Generative Ambient Sound

An immersive sound experience powered by the **Web Audio API**.

* Generative sitar-inspired tones.
* Atmospheric desert-breeze resonance.
* User-controlled ambient audio.
* Sound interaction designed to complement the cinematic experience.

*Audio should remain user-controlled and must not start unexpectedly.*

### 🗝️ 6. Private Estate Reservation Drawer

A slide-out reservation interface designed to feel like a private luxury hospitality experience.

**Reservation features include:**

* Date selection.
* Sanctuary suite selection.
* Bespoke dining requests.
* Desert safari requests.
* Glassmorphic interface styling.
* Convenient access through the Reserve button.

### 📱 7. Keyboard and Touch Interaction

Designed for intuitive navigation across different input methods.

* Up and Down arrow key navigation.
* Page Up and Page Down support.
* Smooth touch-based scrolling.
* Custom golden aura cursor.
* Interactive navigation controls.

### 🌅 8. Luxury Visual Design

The overall interface combines traditional Rajasthani heritage with modern digital craftsmanship.

* Warm desert-inspired visual atmosphere.
* Elegant gold accents.
* Cinematic transitions.
* Refined typography and spacing.
* Immersive architectural storytelling.
* Premium hospitality-inspired interface.

---

## 🛠️ Technology Stack

The project uses browser-based technologies to create its immersive visual experience.

| Technology              | Purpose                                         |
| ----------------------- | ----------------------------------------------- |
| HTML5                   | Website structure and content                   |
| CSS3                    | Layout, styling, animations, and visual effects |
| JavaScript              | Interactive behavior and application logic      |
| HTML5 Canvas            | Rendering cinematic animation frames            |
| WebP                    | Optimized animation frame assets                |
| Web Audio API           | Generative ambient sound                        |
| Browser Keyboard Events | Keyboard-based interaction                      |
| CSS Backdrop Filters    | Glassmorphic reservation interface              |

*The exact implementation depends on the source code and libraries included in the project.*

---

## 🚀 Getting Started

Follow these steps to run RANN MAHAL locally.

### Prerequisites

You will need:

* A modern web browser such as Chrome, Edge, or Firefox.
* Python 3, if you want to use a local development server.
* The complete project files, including the animation assets.

### 1. Clone the Repository

If the project is hosted on GitHub, clone it using:

```bash
git clone <your-repository-url>
```

Navigate into the project directory:

```bash
cd rann-mahal
```

Replace the repository URL and directory name with your actual project details.

### 2. Check the Project Files

Ensure the main HTML file and required animation assets are present.

```text
rann-mahal/
├── index.html
├── assets/
│   └── frames/
│       ├── frame-001.webp
│       ├── frame-002.webp
│       ├── frame-003.webp
│       └── ...
└── README.md
```

*This is an illustrative structure. Your actual folder and frame names may differ.*

### 3. Run the Website

**Option A — Open Directly**

Open `index.html` in a modern web browser.

**Option B — Use a Local Server**

Open a terminal in the project directory and run:

```bash
python -m http.server 3000
```

Then open the following address in your browser:

http://localhost:3000

The website should load with its cinematic sections and interactive features.

> **Note:** If the animation does not work when opening `index.html` directly, use the local server. Make sure the frame paths in the JavaScript match the actual asset locations.

---

## 🎮 How to Explore

1. Open the website in your browser.
2. Scroll down to experience the cinematic animation.
3. Use the Roman numeral navigation rail to jump between chapters.
4. Explore the palace, entrance, courtyard, colonnade, and terrace.
5. Toggle the ambient sound to experience the audio atmosphere.
6. Open the reservation drawer using the Reserve button.
7. Try the keyboard controls and touch scrolling.

---

## 🎨 Design Philosophy

RANN MAHAL is built around a simple design principle:

**Transform a website visit into a cinematic journey.**

Instead of presenting a conventional hospitality landing page, the experience uses scroll-driven storytelling to gradually reveal the architecture and atmosphere of a fictional luxury desert sanctuary.

Every chapter contributes to the narrative, while the golden navigation elements, ambient audio, and interactive reservation drawer help establish a cohesive luxury identity.

The result is a digital experience that combines heritage-inspired aesthetics with modern web animation.

---

## ⚡ Performance Considerations

The cinematic experience relies on loading and rendering multiple image frames.

Performance can be improved by:

* Optimizing WebP frame dimensions and compression.
* Preloading essential frames strategically.
* Using responsive image resolutions where appropriate.
* Avoiding unnecessary layout recalculations during scrolling.
* Throttling or scheduling animation updates efficiently.
* Providing a fallback experience for devices with limited resources.

**Important:** Preloading 143 frames does not automatically guarantee zero latency or consistent 60–120 FPS on every device. Actual performance depends on the device, browser, frame dimensions, memory usage, and rendering implementation.

---

## 📁 Project Highlights

* **Immersive storytelling:** Five connected cinematic chapters.
* **Scroll-driven visuals:** Animation progress linked to scrolling.
* **Heritage-inspired design:** A modern interpretation of Rajasthani palace aesthetics.
* **Interactive navigation:** Roman numerals and golden progress indicators.
* **Atmospheric audio:** User-controlled generative sound.
* **Hospitality experience:** A dedicated reservation drawer.
* **Responsive interaction:** Keyboard and touch navigation.

---

## 🔮 Future Enhancements

Potential improvements for future versions include:

* Responsive animation assets for mobile devices.
* Adaptive frame loading for improved performance.
* Accessibility improvements and reduced-motion support.
* Enhanced reservation form validation.
* Backend integration for reservation management.
* Real-time availability and booking confirmation.
* Additional heritage-inspired transitions and soundscapes.

---

## 📜 License

Choose an appropriate license before making the project publicly available.

If you intend to use third-party images, audio, animation frames, or other assets, ensure that you have permission to redistribute them.

---

<div align="center">

### RANN MAHAL

**A sanctuary beyond the ordinary.**

*Where heritage meets cinematic storytelling.*

</div>
