# Conversational AI Prompt Engineering Portfolio

This repository serves as a professional portfolio, demonstrating my expertise as a **Conversational AI Engineer** specializing in **Prompt Engineering** and **Voice Agent Design**. The documents contained here are high-fidelity prompt sets, accompanied by test recordings, showing an ability to transform complex business goals into reliable, human-like agent interactions.

---

## Key Skills & Results

This work directly validates the core outcomes achieved during my tenure at Hatzs Dimension:

* **Precision Logic Implementation:** Successfully designing prompts that diagnose and resolve complex conversational failures, such as correcting **time zone, pronunciation, and calendar conflicts** (as demonstrated in the MediLink and Skyline projects).
* **Operational Efficiency:** Showcasing the speed and quality required to achieve a **40% reduction in prompt development turnaround time**.
* **Performance Optimization:** Strategic prompt refinement that improved Prompt Generator accuracy from **80% to 90%** across voice and text agents.

---

## Portfolio Documents & Scenarios

| Project Name | Agent Type | Primary Objective | Prompt Document (PDF) | Test Recording Link |
| :--- | :--- | :--- | :--- | :--- |
| **MediLink Health Services** | Voice (Inbound Receptionist) | Qualify leads based on insurance and service needs, and either **transfer the call to a specialist** or schedule a same-day appointment. | [`Prompts/MediLink-Inbound-Rep.pdf`](./Prompts/MediLink-Inbound-Rep.pdf) | **[`Recordings/MediLink-Test-Call.mp3`]** |
| **Skyline Realtors** | Voice (Outbound Lead Qualifier) | Qualify real estate leads based on financial criteria (**minimum budget: PKR 10M**) and urgency, while handling IVR/Voicemail protocols. | [`Prompts/Sky-Realtor-Outbound.pdf`](./Prompts/Sky-Realtor-Outbound.pdf) | **[`Recordings/SkylineRealtors-Test-Call.mp3`]** |
| **ShopNexa** | Text (Website/SMS Support) | Qualify e-commerce support requests, resolve issues via **FAQ knowledge base**, and successfully handle customer objections to schedule callbacks. | [`Prompts/Shop-Nexa-Texting.pdf`](./Prompts/Shop-Nexa-Texting.pdf) | **[`Recordings/ShopNexa-Test-Chat.mp4`]** |

---

## Technical Details & Prompt Strategy

The structure of these documents highlights the implementation of technical constraints and advanced prompt strategies:

* **Voice Design Rules (TTS/STT):** Documents define rules for managing low-latency full-duplex conversation, including how the Text-to-Speech engine must handle **phonetic pronunciation**, **contact information**, and use of natural speech fillers (`um`, `uh`).
* **Logic & Triage Flow:** The scripts detail a rigorous, multi-step lead qualification and triage process, ensuring accurate data capture by enforcing the **one question at a time** rule.
* **Robust Error Handling:** Contains specific protocols for non-supported interactions, such as **IVR/Voicemail detection** and scripts for handling user objections (e.g., "I don't trust online stores," "Your delivery is always late").
* **Persona and Tone Management:** Explicit instructions set the conversational tone for each client (e.g., **"Warm, reassuring"** for healthcare, **"Human, friendly, and natural"** for e-commerce), maintaining high customer satisfaction.
