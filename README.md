# HorseCatcherAI 🐴

As part of the **CowCatcherAI** open-source ecosystem, **HorseCatcherAI** is the newest member of the family. This repository is specifically tailored for horse breeders and equestrian owners, focusing exclusively on automated **foaling (birth) detection**.

By combining computer vision and local AI agents, HorseCatcherAI provides real-time insights and instant notifications to help breeders protect their mares and foals during crucial moments.

while we don't have an official foaling model for horses just yet, our standard Calving model does a solid job picking up the key signs (waterbag, hooves, head, and body). Just be sure to drop your confidence threshold to around 0.60 in config.json.

We’re currently running trials with a small horse farm to train a dedicated model from the ground up, and we'd love more partners. If you'd like to test it out or collaborate with us to make the model better, drop us a line at Cowcatcherai@gmail.com!

---

## 🔄 How it Works

📷 Foaling Stall Camera  ──→ 🤖 AI Computer Vision (YOLO) ──→ ⚡ Event Detection (Foaling) ──→ 💽 Save Event Image ──→  📲 Telegram Notification with Image & AI Reasoning

---

## 🚀 Features & Technology

We combine multiple cutting-edge, open-source technologies to create a reliable monitoring system that runs on the core [AI Detector](https://github.com/ESchouten/ai-detector) software:

* **Computer Vision:** Powered by **Ultralytics YOLO** for real-time tracking and behavior detection (restlessness, labor positioning, and the birthing process).
* **Thermal Imaging Support:** Optimized for IP cameras with thermal lenses. This allows the system to accurately detect the heat signatures of the mare and the newborn foal, identify the exact moment of birth, and perform a final check to confirm the newborn is alive and moving.
* **Local AI Agents:** Integrates with lightweight, locally hosted vision-language models like **Qwen 2.5-VL / Qwen 3.0** and **Moondream AI** (fine-tuned with foaling context) to analyze images. Alternatively, it can connect to cloud-based LLM APIs.
* **Smart Alerts:** Instant Telegram notifications including the captured image and the AI agent's expert reasoning.

---

## 🤝 Join the Movement: Looking for Beta Testers! 📢

HorseCatcherAI is currently in **active development**, and we need your help to make it perfect! 

Are you a **horse breeder**, equestrian owner, researcher, or tech enthusiast? We are actively looking for interested partners to:
* Test the software in real-world foaling stalls.
* Help collect and annotate data to train an ultra-accurate model for horses.

📩 **Interested?** Reach out to us at: **cowcatcherai@gmail.com** and help us bring smart farming to the equine community!

---

## 🌿 The CowCatcherAI Family

HorseCatcherAI runs on top of the shared family codebase. Check out the other repositories:

* **[Main CowCatcherAI Repo](https://github.com/CowCatcherAI/CowCatcherAI):** The origin of the project (focused on cattle).
* **[AI Detector](https://github.com/ESchouten/ai-detector):** The main software base and core detection engine used by HorseCatcherAI.
* **[Annotation Helper](https://github.com/JacobsFarm/annotation_helper_cowcatcherai):** Tooling to help annotate images for training our models.

---

## 📄 License

This project uses the **GNU Affero General Public License v3.0 (AGPL-3.0)**. It is based on Ultralytics YOLO and is fully open source.

> ⚠️ **IMPORTANT NOTICE:** This software and its trained models are **NOT authorized for commercial use or distribution** without explicit permission.

---

## 🙏 Acknowledgments

This project is made possible by the amazing [Ultralytics YOLO](https://github.com/ultralytics/ultralytics) library. Their state-of-the-art computer vision technology forms the basis of our behavior detection. 

**Thank you, Ultralytics team!** 🚀 For making cutting-edge AI technology available to help breeders worldwide.

---

## ⚠️ Disclaimer

This software is provided "as is" without warranty of any kind. It is an assistive tool — **not a substitute for professional veterinary advice**. Always confirm detections and consult a veterinarian for animal health decisions. The authors accept no liability for missed detections, false alarms, or decisions made based on this software.

## HorseCatcher AI logo

<img width="2048" height="2048" alt="Gemini_Generated_Image_il9oztil9oztil9o" src="https://github.com/user-attachments/assets/e3e8b1a2-5ae9-4326-87b1-58e693542850" />

