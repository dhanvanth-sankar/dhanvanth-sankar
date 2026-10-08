# Dhanvanth Sankar

**Electrical & Computer Engineering @ Carnegie Mellon** · B.S. expected May 2029 · Additional major in Engineering Design, Innovation & Entrepreneurship · Dallas, TX

I build things that have to work outside a simulator — firmware on deployed hardware, services in production, and a few things made of aluminum and servos.

📱 **[Sustain](https://apps.apple.com/us/app/sustain-glp-1-companion/id6793802192)** — native iOS app, live on the App Store
📊 **[OpenGym](https://cmuopengym.com)** — occupancy platform deployed in CMU's Cohon University Center gym

---

## Software & Cloud

**ParseEngine** · OneEstateOS (real-estate SaaS startup) · *Jun 2026 – present*
Contributed to the design of and built a document-intelligence pipeline: LLM-backed classification, structured field extraction with per-field confidence scoring, and a custom document-splitting and address-based collation system. The prototype became the foundation for the company's production service, a domain-blind, event-driven architecture. I personally provisioned and configured its **AWS ECS Fargate, DynamoDB, SQS and Textract** resources, and I review pull requests on the team. Currently building the conversational backend for their visitor-facing AI agent — persona classification, LLM-driven response logic, and artifact retrieval against a locked product spec.

**Sustain** · *Jul 2026* · [App Store](https://apps.apple.com/us/app/sustain-glp-1-companion/id6793802192) · [hearthlyapps.com](https://hearthlyapps.com)
A native iOS GLP-1 companion app. I wrote roughly half the Swift/SwiftUI by hand and directed AI-assisted development for the rest. Real billing via RevenueCat/StoreKit, Google and Apple sign-in, HealthKit sync, and an AI photo-to-protein feature that calls the Anthropic API from behind a Supabase Edge Function instead of a key shipped in the client. Shipped through App Store review, then root-caused a launch-performance defect across a multi-round investigation.

`Swift` `SwiftUI` `SwiftData` `Supabase` `Python` `Java` `AWS` `REST` `Docker` `Kubernetes` `CI/CD`

---

## AI / ML

**Technology Intern** · Real AI Dynamics · *Jun 2024 – Jul 2025*
Cut hallucination rate, off-topic responses, and response variance on production models from **30% to 10%** by designing and iterating on prompt templates and parameter configurations. Wrote rigorous Python-based stress tests against production LLMs (GPT, Claude) and documented **100+ edge-case reliability gaps**, then analyzed failure modes and output anomalies into reports used to improve real-world accuracy. Owned the evaluation-to-deployment workflow end to end.

**Gray Swan AI Jailbreakathon** · CMU · *Mar 2026*
Engineered prompt-based jailbreaks against ChatGPT, Claude and Gemini to find where safety guardrails fail. **8th of 70 teams.**

`LLM Fine-Tuning` `Prompt Engineering` `RAG` `Model Evaluation` `LLM Red-Teaming` `AI Guardrail Design`

---

## Embedded & Hardware

**OpenGym Occupancy Telemetry** · CMU Business Technology Group · *Jan 2026 – present* · [live](https://cmuopengym.com)
ESP32 firmware reading a laser distance-sensor array, feeding a pipeline to AWS and a real-time dashboard deployed in a campus gym. Cut sensor data packet drop from **12% to 3%** during peak traffic by reworking how the I2C/SPI array was multiplexed — the dashboard looked broken, but the failure was in firmware.

**Autonomous Long-Range UAV** · *2024 – 2026*
7-inch long-range drone built for end-to-end mission testing: GPS navigation, flight telemetry, and a custom flight-controller PCB/PCBA I laid out. Built the hardware–software interfaces for obstacle avoidance and long-distance video, holding **sub-20 ms video latency and reliable telemetry over 25 km** using digital modulation fundamentals and encryption.

**EMG-Controlled Prosthetic Hand** · CMU EDIE Makeathon · *Mar 2026* · **5th of 25 teams**
A MyoWare muscle sensor into an ESP32 driving five servos, one per finger, plus a dashboard for sensor inputs and system performance. Built end to end inside a **12-hour sprint**.

**Analog & Power Electronics**
A six-foot RF-actuated lighting array with multi-stage power delivery mapped in Altium and RF-relay remote control; a bicycle converted into an electric vehicle with the battery–motor configuration tuned for power draw, torque and range under real load (three motors died of a voltage overload teaching me that).

`ESP32` `I2C/SPI` `PCB/PCBA Layout` `Altium` `Oscilloscope` `Soldering` `SystemVerilog` `FPGA` `Vivado` `C` `C++`

---

## Building & Leading

**SpotlessDesigns** — Founder & Operator · *Jun 2022 – present*
Started at fifteen with a 3D printer my dad bought on impulse. Now a highly automated multi-machine print farm fulfilling **~200 orders/month at 3.5× YoY growth** across four marketplaces. Cut per-unit shipping cost **15% YoY** by redesigning packaging, and streamlined production workflows to hold part accuracy and reduce machine downtime.

**CMU Raasta** — Production Manager · *2026 – present*
Lead the team that designs and builds our set's technical systems: structural framing, lighting and power distribution, motorized moving elements, and the control system driving them. Modeled in CAD, fabricated in-house on 3D printers and a laser cutter, electrical side in Altium.

**Carnegie Mellon Racing** — power storage and delivery subsystems for a formula-style car
**CMU RoboClub** — Robobuggy, an autonomous vehicle
**Teaching Assistant, First Year Seminar** — CMU College of Engineering, *Aug 2026 – present*
**NASA Aerospace Scholars** — integrations manager for a 12-student Mars mission design team, **3rd in Texas**

---

## Coursework

CS 15112 (Python, data structures, algorithms, OOP) · CS 15122 (C, pointers & memory management) · ECE 18100 (digital logic design) · ECE 18240 (SystemVerilog, Vivado, FPGA) · ECE 18220 (electronic devices & analog circuits) · STA 36225 (probability theory) · MEG 24101 (fluid mechanics, ANSYS)

---

📫 **dsankar@andrew.cmu.edu** · [LinkedIn](https://linkedin.com/in/dhanvanth-sankar)
