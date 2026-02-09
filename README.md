# clerk-duties-assistant-agent

# clerk-duties-assistant-agent

A professional-grade, **privacy-first** AI workstation designed for local government administration. This project documents how to build a hardware-accelerated "Assistant Agent" for a **Township Clerk** using an **eGPU (NVIDIA RTX 4000)** and **AnythingLLM**. 

This setup allows for high-speed document analysis, drafting, and summarization without ever sending sensitive municipal data to the cloud.

## 🏛️ The Mission
Township Clerks handle a mountain of public records, ordinances, and meeting minutes. This agent is designed to be a "Digital Paralegal" that lives entirely on the Clerk's desk, ensuring 100% data sovereignty and public trust.

## 🚀 Key Features
- **100% Local & Private:** No internet required for AI "thinking." Data stays on your hardware.
- **Hardware Accelerated:** Uses an eGPU (Thunderbolt) to provide "instant" AI responses.
- **Document Intelligence:** "Talk" to your ordinances, minutes, and state statutes.
- **Voice Enabled:** Supports dictation and text-to-speech for hands-free administrative work.

## 🛠️ Hardware Stack
- **Host:** Lenovo Yoga (Intel Core Ultra / 16GB RAM)
- **Accelerator:** Razer Core eGPU Enclosure (Thunderbolt 4)
- **Brain Power:** NVIDIA Quadro RTX 4000 (8GB GDDR6)
- **Portable Library:** Samsung T5 External SSD (Stores the AI Models)

## 🧠 The "Brains" (Models)
This agent uses GGUF-formatted models optimized for 8GB VRAM:
- **Llama 3.1 8B:** The "All-Rounder" for drafting correspondence and general help.
- **Mistral 7B v0.3:** The "Logic Specialist" for formal reasoning and checklists.
- **Phi-3 Mini 128k:** The "Deep Reader" for analyzing massive 100+ page documents.

## 📂 Project Structure
- `/docs`: Contains the printable User Guide and Cheat Sheets.
- `/prompts`: Recommended system prompts for "Clerk Mode."
- `/configs`: Hardware and driver configuration notes.

## 📖 Quick Start
1. **Connect Hardware:** Plug in the Razer Core and Samsung T5.
2. **Install Drivers:** Use NVIDIA Enterprise/Data Center drivers for maximum stability.
3. **Launch AnythingLLM:** Point the model storage to the Samsung T5.
4. **Import Models:** Use the `+ Import GGUF` button to load the brains.
5. **Create Workspace:** Upload your PDFs and start chatting.

## ⚖️ Disclaimer
This agent is a productivity tool designed to assist with administrative duties. It is **not** a substitute for legal counsel or official statutory interpretation. Always verify AI outputs against official township records.

## 🛡️ License
Distributed under the MIT License. See `LICENSE` for more information.

---
**Built by [Dave/1r1shEX1T0]**  
*Part of the Ghost Node Lab Project*
