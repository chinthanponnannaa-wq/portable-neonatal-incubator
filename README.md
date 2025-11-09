# Portable Neonatal Incubator with Sleep Apnea Monitoring 🍼💤

A low-cost, IoT-enabled neonatal incubator that monitors infant vitals such as
temperature, humidity, and sleep apnea in real-time.

---

## 🧠 Features
- Real-time monitoring using DHT22, MAX30100, and Load Cell  
- Sleep apnea detection via pulse oximetry  
- Cloud data storage using ESP8266 (IoT integration)  
- Compact and portable design for rural healthcare  

---

## 🛠️ Tech Stack
- **Arduino IDE** (C/C++)  
- **ESP8266** WiFi module  
- **Sensors:** DHT22, MAX30100, Load Cell  
- **Display:** OLED  
- **Cloud Platforms:** ThingSpeak / Blynk  

---

## 📊 System Overview

Below is a simplified diagram of the neonatal incubator system.

![System Diagram](images/methodology_diagram.png)

---

## 👨‍💻 Team

- **Chinthan A D**  
- **Kruthin H K**  
- **N Likitha**  
- **Sanjana B R**  

**Mentor:** *Prof. Shreeshayana R*  
**Institution:** *ATME College of Engineering*  
**Academic Year:** *2025–2026*  

---

## 🔗 Presentation
View the full project documentation [here](docs/slides.pdf).

---

## 📷 Prototype

Below is an image of the actual working prototype of the incubator developed during the project phase.

![Prototype](images/prototype.jpg)

---

## 📹 Prototype Demo

Below is a short demonstration of the working prototype 👇

<!--
  Primary (GitHub-friendly) approach: GIF.
  If you already have media/prototype.gif in your repo, GitHub will display it inline.
-->
![Prototype Demo](media/prototype.gif)

---

<!--
  Optional HTML <video> fallback. GitHub's README renderer will NOT play MP4 inline;
  it will typically show a download link instead. But other renderers (or local previews)
  may show an inline player.
-->
<details>
<summary>Video fallback / local preview (click to expand)</summary>

<video src="media/prototype.mp4" width="720" controls>
  Your browser does not support the video tag. You can download the video here:
  <a href="media/prototype.mp4">media/prototype.mp4</a>
</video>

</details>

---

<!--
  Optional: link to externally hosted playable video (YouTube / Google Drive / Vimeo).
  Replace the URL below with your actual hosted video URL and a thumbnail if available.
-->
**Watch the demo (playable):**  
[![Watch Prototype Demo](images/video-thumbnail.jpg)](https://youtu.be/REPLACE_WITH_YOUR_VIDEO_ID)

---

## 📂 Repository Structure
```plaintext
portable-neonatal-incubator/
├─ README.md
├─ LICENSE
├─ .gitignore
├─ B3_Major_Project_Phase_II.pptx
│
├─ docs/
│  ├─ poster.pdf
│  └─ slides.pdf
│
├─ hardware/
│  ├─ bill-of-materials.csv
│  └─ schematics/
│     └─ .gitkeep
│
├─ firmware/
│  └─ arduino/
│     └─ .gitkeep
│
├─ software/
│  └─ web-dashboard/
│     └─ .gitkeep
│
├─ media/
│  ├─ prototype.gif       <- demo GIF (recommended for GitHub README)
│  └─ prototype.mp4       <- optional video file (fallback)
│
└─ images/
   ├─ cover.png
   ├─ circuit_diagram.png
   └─ model_photo.jpg
