<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=250&section=header&text=Sahayak&fontSize=80&fontAlignY=35&desc=AI-Powered%20Assistive%20Navigation&descAlignY=55&descAlign=50" alt="Sahayak Header" />
</p>

<p align="center">
    <a>
      <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=F39C12&center=true&vCenter=true&width=600&lines=Winner:+Best+Innovation+Award;Empowering+The+Visually+Impaired;Smart+Voice-Guided+Navigation;Real-Time+Emergency+SOS" alt="Features Overview" />
    </a>
</p>

<!-- Live Application Demo Walkthrough -->
<div align="center">
  <h2>👀 See It In Action (Demo Preview)</h2>
  <img src="demo.webp" width="700" alt="Sahayak Demo Application Walkthrough" style="border-radius:15px; box-shadow: 0px 4px 10px rgba(0,0,0,0.5);" />
</div>

<div align="center">
  <a href="#about">About</a> •
  <a href="#features">Features</a> •
  <a href="#tech-stack">Tech Stack</a> •
  <a href="#notice">Disclaimer</a>
</div>

<br/>

<div align="center">
  <img src="https://img.shields.io/badge/Status-Under%20Active%20Commercial%20Development-red?style=for-the-badge&logo=shield" alt="Status" />
</div>

<br/>

## 🛑 Proprietary & Closed Source Notice <a name="notice"></a>

> **Important**: This repository solely serves as a **portfolio and presentation showcase** for our award-winning hackathon submission. 
>
> 🔒 **The complete and working source code is NOT publicly available in this repository.** As this project is under intensive development for commercial deployment, access to the proprietary files is locked to prevent unauthorized copying, replication, or distribution. What is featured here represents the concept, user interface flow, and technical capabilities of Sahayak.

---

## 📖 About The Project <a name="about"></a>

**Sahayak** (meaning "Helper" in Hindi) is a next-generation mobility and navigation assistant designed exclusively for the visually impaired. Relying securely on real-time computer vision and voice commands, Sahayak acts as a "virtual eye"—solving the very real danger of navigating unpredictable urban Indian environments.

By fusing **Edge Computing (AI)** with **High-Precision Maps**, it promotes true independence.

---

## ✨ Dynamic Features <a name="features"></a>

| | Feature Insight | Technical Glimpse |
| :---: | :--- | :--- |
| <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Microphone.png" width="80" /> | **Zero-Touch Voice Commands**<br/>The entire app is controllable hands-free. A specialized wake-word ("Hey Sahayak") triggers intelligent system actions that speak back to the user. | Web Speech API,<br/>Audio Routing Contexts |
| <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Eye.png" width="80" /> | **Real-Time Scene Recognition**<br/>The device’s camera continuously scans the surroundings to actively detect hazards, people, and objects at an astonishingly low latency. | TensorFlow.js, `@tensorflow-models/coco-ssd` running securely on the edge browser. |
| <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/World%20Map.png" width="80" /> | **Hyper-Local Routing**<br/>Tailored pedestrian instructions mapping the physical complexities of streets, junctions, and narrow pathways. | MapmyIndia (Mappls API), Leaflet |
| <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Police%20Car%20Light.png" width="80" /> | **Protective SOS Dispatch**<br/>One reliable action triggers an instant SMS+Call sequence with precise live-location telemetry to pre-configured guardians. | Supabase Edge Functions, Twilio Backend (Simulated) |

---

## 🛠️ Proprietary Technology Stack <a name="tech-stack"></a>

While the complete proprietary repository isn't published, the architecture implements standard enterprise stacks configured for exceptional low-latency AI capability on mobile data:

- 🎨 **Frontend**: React 18, Vite, TypeScript, TailwindCSS
- 🧠 **AI / Inference**: TensorFlow.js (In-Browser Vision Pipelines)
- 🗺️ **Geospatial**: `mappls-web-maps`, `<MapContainer>` (Leaflet)
- ☁️ **Backend / Database**: Supabase (PostgreSQL, Realtime DB)

---

## 📋 System Access Requirements 

> *For evaluating engineers or authorized partners interacting with the full build:*

1. **Environment:** Node `v18+`
2. **Hardware:** Modern Smartphone or WebRTC-enabled tablet with a high-quality rear-facing camera.
3. **API Keys (Required in `.env`):**
   - `VITE_MAPPLS_API_KEY`
   - `VITE_SUPABASE_URL`
   - `VITE_SUPABASE_ANON_KEY`

---

<p align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Sparkling%20Heart.png" width="30"/>
  <br/>
  <b>Built with passion for a more accessible world.</b>
</p>
