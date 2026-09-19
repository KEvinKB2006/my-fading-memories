# My Fading Memories 🎮

A 3D psychological puzzle and atmospheric narrative prototype built with **Unity** and **C#**.

> ⚠️ **Project Status: Concept Archive & Reconstruction Stage**  
> The original production code and raw Unity assets were lost. This repository documents the original prototype's mechanics, level architecture (greybox phase), and design documents, serving as a blueprint for the planned reconstruction.

---

## 📸 Prototype Showcase (Greybox Stage)

*Early development capture showcasing player movement, spatial bounds, and camera setup.*

<img width="1485" height="842" alt="Screenshot 2025-12-02 143728" src="https://github.com/user-attachments/assets/53a6ccae-e9b3-44a3-825d-8724c87f4fdf" />

[![Watch Gameplay Demo](https://img.youtube.com/vi/Fy7Jd9ve5Yg/maxresdefault.jpg)](https://youtu.be/Fy7Jd9ve5Yg)

---

## 📖 Game Concept & Narrative
*My Fading Memories* is an atmospheric exploration game where the player reconstructs fragmented, lost memories through environmental cues and spatial puzzles. 

The player navigates through dreamlike, shifting environments where physical architecture reflects emotional and mental states. Solving perspective puzzles and interacting with personal artifacts triggers scene transitions and narrative sequences.

---

## 🕹️ Implemented Prototype Mechanics

### 1. Character Controller & Greybox Prototyping
- **Locomotion:** Responsive 3D third-person character movement using Unity's Character Controller and physics checks.
- **Camera Rig:** Dynamic camera tracking and rotation tailored for tight indoor environments and open puzzle stages.
- **Environment Testing (Greybox/Blockout):** Fast prototyping using primitive geometry to dial in player scale, jump heights, walking speeds, and field of view before asset creation.

### 2. Interaction & Narrative Triggers
- Proximity detection system (Raycasts & Triggers) for inspectable objects.
- Trigger zones tied to narrative thresholds that alter lighting, fog density, or audio cues.

### 3. Scene & Dimension Transition System
- Asynchronous scene management (`SceneManager.LoadSceneAsync`) allowing seamless transitions between the active world and memory sequences.
- Screen fade overlays and perspective shifts used to convey memory shifts and temporal jumps.

---

## 💻 Tech Stack & Architecture
- **Engine:** Unity
- **Language:** C#
- **Patterns:** State machines for character movement, event-driven interaction listeners, modular scene loaders.

---

## 🗺️ Rebuilding Roadmap
- [x] Initial design concept, greybox mechanics, and scene transition logic
- [ ] Set up clean Unity LTS project repository with standard Git LFS support
- [ ] Rebuild modular 3D character controller (C#)
- [ ] Re-implement scene loading and fade-in/fade-out transition managers
- [ ] Implement inspectable object and dialogue/text prompt interfaces
- [ ] Art pass & replacement of greybox test assets

---

## 👤 Author
- **Kevin Barbagallo** - [GitHub](https://github.com/IL_TUO_USERNAME) | [LinkedIn](https://www.linkedin.com/in/kevin-barbagallo-a8a4883b0/)
