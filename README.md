# 🎙️ Research Task 6: Deep Fake Interview

## 📌 Project Title
**Task_06_Deep_Fake**

---

##  Objective

The goal of this research task was to explore the creative and technical boundaries of large language models (LLMs) by generating a **deep fake sports interview** using real performance statistics. This builds upon Research Task 5, which involved descriptive statistics of the 2025 Syracuse University Women’s Lacrosse team.

---

##  Scope

This task focused on:
- Converting sports performance metrics into human-readable narratives
- Simulating a realistic **post-season interview**
- Exploring **audio or video deep fake generation**
- Applying **prompt engineering** to structure narrative tone, dialogue flow, and role-specific responses
- Documenting the **process** and **challenges**, even if the media generation was only partially successful

---

## 💡 Process Overview

1. **Data Ingestion & Stats Summary**  
   Extracted player-level stats from PDF → structured into a CSV → LLM-verified summaries.

2. **Narrative Prompting**  
   Used prompt engineering to:
   - Simulate quotes from top-performing players (e.g., Emma Ward)
   - Generate reflective coaching statements
   - Create a full ESPN-style interview script

3. **Script Finalization**  
   Script is saved in `script.md` and formatted for either voice-over or avatar-based delivery.

4. **Optional Tools for Deep Fake**  
   Suggested tools (used or explored):
   - 🎤 [ElevenLabs](https://elevenlabs.io/) – Voice cloning
   - 📹 [D-ID](https://www.d-id.com/) – Talking head avatars
   - 📼 [Synthesia](https://www.synthesia.io/) – AI presenter videos
   - 🧠 [Play.ht](https://play.ht/) – Natural-sounding narration

5. **Prompt Logging**  
   The full list of prompts, iterations, and logic is provided in [`prompts.md`]

---

## 📁 Repository Structure

```bash
Task_06_Deep_Fake/
├── README.md            ← This file
├── prompts.md           ← Prompt engineering log and reasoning
├── script.md            ← Final deep fake interview script
└── LICENSE              ← Open license (if any used tools/scripts)
