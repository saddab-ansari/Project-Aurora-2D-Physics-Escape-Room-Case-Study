# 🌌 Project Aurora: 2D Physics Escape Room (Case Study)

![Event](https://img.shields.io/badge/Event-Zensar%20Game--a--thon-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Web%20Browser-lightgrey.svg)
![Tech Stack](https://img.shields.io/badge/Tech-HTML%20%7C%20CSS%20%7C%20JS-yellow.svg)
![Status](https://img.shields.io/badge/Status-Closed%20Source%20(Acquired)-red.svg)

## ⚠️ Repository Notice

This repository contains **no source code**.

The full game — including all assets, gameplay logic, and storyline — is protected under an **IP agreement signed with Zensar Technology** following the hackathon hosted at MMCOE. Out of respect for that agreement, nothing proprietary is published here.

What this repo *is*, is a transparent case study: how we built it, what we used, what worked, what didn't, and what we learned in 24 hours.

---

## 🎮 What We Built

**PhysX Escape** is a **2D escape room-style physics puzzler** that runs entirely in the browser — no download, no install, just a link.

Visually inspired by **Pokémon FireRed** (the aesthetic, the character sprite style, the top-down pixel feel), the game places you in a **Principal Hall** that connects to **5 distinct physics-themed rooms**. To escape each room, you solve a physics quiz. Clear all five, and the game concludes.

### Core Loop
```
Enter Room → Face Physics Challenge → Answer Correctly → Escape → Repeat × 5 → Victory
```

The storyline — which we're genuinely proud of — tied all of this together thematically. We're keeping that close to our chest.

---

## 🧑‍💻 The Team (A trio)

| Person | Role (in theory) | Role (in reality) |
|--------|-----------------|-------------------|
| **Saddab** | Lead Dev | Everything that needed to be done |
| **Ankit** | Dev | Everything that needed to be done |
| **Ishan** | Assets | Sound effects & background music |

Honest note: this wasn't a clean division of labor. Ankit and I were both heads-down across design, logic, integration, and bug-fixing simultaneously. ID sourced the audio, which mattered more than we expected — sound design added a lot to the atmosphere.

---

## 🛠️ The Stack (No Engine. Just AI + Code.)

We went into the hackathon knowing none of us had hands-on experience with any game engine. We briefly discussed **Godot** early on, but after a quick reality check on the learning curve vs. time available, we dropped it fast. A bad Godot build in 24 hours would've been worse than no build at all.

Instead, the stack looked like this:

### 🎨 Visual Generation
- **Google Gemini Pro** → Room backgrounds and environment visuals. As well as Sprite for our main character.
- **ChatGPT** → Additional background generation and iteration
- Character design was hand-crafted in the **Pokémon FireRed** sprite style

### 🌐 Frontend & Game Interface
- **Lovable AI** → Used to prototype and scaffold the web frontend; gave us TypeScript
- **Gemini Pro** → Converted the TypeScript output to HTML, CSS, and vanilla JavaScript (browser-native, no framework dependencies)

### ⚙️ Feature Development & Debugging
- **Claude (Anthropic)** → Primary tool for adding new features, fixing broken logic, and iterating on gameplay mechanics
- **GitHub Copilot / Codex in VS Code** → Inline autocomplete and code suggestions during crunch

### 🔊 Audio
- Sound effects and background music sourced by ID — fit the retro aesthetic well

### Deployment
- Web-based. Browser playable via a single link. No backend. No install.

---

## 🏆 The Hackathon — MMCOE, Pune

- **Event Format:** 2-round competition
  - Round 1: Idea submission (virtual)
  - Round 2: 24-hour offline build hackathon
- **Venue:** MMCOE (our own college)
- **Our Standing:** Qualified from idea submission to the offline round, competing against **60–70 teams** who had also cleared Round 1 out of **150+ total teams**
- **Semester:** 2nd semester — one of our first serious technical builds
- **IP Outcome:** Game IP acquired by **Zensar Technology**

---

## 🧑‍⚖️ The Verdict

The judges rejected the project citing a lack of **"X-factor"** — the hook that keeps players coming back.

We weren't blindsided by this. Physics puzzler is an inherently low-engagement genre. The issue wasn't execution, it was genre ceiling — and the genre was **fixed by the organizers**. Within the constraints, we built something complete, functional, and visually coherent in 24 hours. That's still something.

The IP still got picked up. So there's that.

---

## 💡 Honest Retrospective

**What actually worked:**
- Skipping the engine entirely. A clean HTML/CSS/JS build was shippable; a half-baked Godot build wouldn't have been.
- Using Lovable for rapid UI scaffolding saved us hours of boilerplate.
- Claude was the most useful tool for mid-build feature changes — fast, contextual, and it understood our existing code.
- Codex in VS Code made long coding sessions less exhausting.

**What we'd do differently:**
- Genre selection matters even when you don't control it — we should've thought harder about how to inject replayability into a constrained genre.
- Better division of non-code work earlier (audio, copy, QA) so Ankit and I weren't stretched thin.
- Storyline deserved more surface area in the actual gameplay. It was good. Players didn't see enough of it.

**What this proved:**
- You don't need a game engine to ship a game in a hackathon.
- Three people with good coordination and the right AI tools can build something polished in 24 hours.
- 2nd semester is not too early to compete.

---

## 📌 Status

`CLOSED — IP transferred to Zensar Technology`

No further development planned. This repo exists solely as documentation.

---

<div align="center">

*Built in 24 hours · MMCOE Hackathon · 2nd Semester*

</div>
