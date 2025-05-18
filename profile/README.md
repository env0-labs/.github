# env0.labs

Welcome to **env0.labs** — a systems-focused creative space building narrative engines, simulation platforms, and AI-enhanced learning tools.

This isn’t a product studio. It’s a lab.

Small, sharp systems that model trust, interaction, and degradation — all layered on a retrofuturist terminal core. Think: _terminal as interface, simulator, and story engine._

---

## 🧠 About env0.labs

This is a personal experiment — an open, transparent attempt to see how far a non-developer can go with AI-assisted tooling.

Project started around the 4th of April, 2025.

To be clear:
- My closest brush with web dev before this was editing HTML on Myspace in 2004  
- I’d never opened VS Code before this project  
- I’d never written JavaScript beyond a few tweaks in Adobe Captivate  
- I didn’t know what a commit was  
- I didn’t know `.md` files existed  
- I’d only used Git to clone repos — never contributed, never pushed  
- I could move around Linux a bit, but that was it

This isn’t a side project from someone brushing up on skills.  
It’s a system built from **zero working dev experience** — using AI as co-designer, debugger, and reflection partner.

---

## 🧭 Project Evolution

**env0.labs** began as a pure web project (HTML, CSS, JS, and a canvas-based terminal renderer). After weeks of renderer pain, performance issues, and tight coupling between display and logic, the project moved to Unity — aiming to offload visuals and focus on simulation.

**However, Unity as an all-in-one solution proved too heavy and complex for pure system simulation.**

**Current direction:**
- The pure C# logic engine is being built in [`env0.terminal.unity`](https://github.com/env0-labs/env0.terminal.unity). This is the backend: a platform-agnostic, testable, simulation core. No Unity dependencies.
- [`env0.core.unity`](https://github.com/env0-labs/env0.core.unity) is the Unity front end, focused on visuals, audio, and immersive effects. It consumes output from the pure C# logic engine and displays it via TextMeshPro, shaders, etc.
- The JS project is on pause while the pure C# engine is established as the “brain” of the terminal.  
- The long-term goal: Logic and simulation are platform-agnostic and testable (console, Unity, web, or other UI), while Unity (and potentially other frontends) handle display, effects, and user interaction.

Nothing here is finished. But the direction is deliberate.

---

## 🏗️ Active Projects

### ⚙️ [`env0.terminal.unity`](https://github.com/env0-labs/env0.terminal.unity)
**The pure logic engine.**  
A platform-agnostic, pure C# simulation core with modular commands, virtual filesystems, networking, and all stateful logic — ready to plug into Unity, console, or web UIs. The “brain” of all future env0.labs projects.

### 🖥️ [`env0.core.unity`](https://github.com/env0-labs/env0.core.unity)
**Unity as terminal display.**  
Handles visuals, audio, and immersive effects. Consumes output from the pure C# logic engine. No business logic — just rendering, FX, and user interaction.

### 📚 [`env0.explore`](https://github.com/env0-labs/env0.explore)
Essays, audit trails, and explorations into trust, entropy, learning theory, and simulation. Markdown-first, AI-assisted.

---

## ⏸️ Paused Projects

### 🗂️ [`env0.core`](https://github.com/env0-labs/env0.core)
**(Paused)**  
Original JavaScript/HTML/CSS implementation. Custom canvas terminal renderer. Project is on hold in favor of the modular C# approach.

### 🗂️ [`env0.terminal`](https://github.com/env0-labs/env0.terminal)  
**(Archived)**  
Legacy proof-of-concept for a JS-based logic core. Superseded by the C# version. Kept for reference.

### 🗂️ [`node.zero`](https://github.com/env0-labs/node.zero)  
**(Paused)**  
CLI-based exploration environment that teaches terminal thinking, basic networking, and safe failure. Will eventually be rebuilt on the new C# core.

### 🗂️ [`entropy.echo`](https://github.com/env0-labs/entropy.echo)  
**(Paused)**  
The horror layer. Terminal where nothing is broken — but something is wrong. Will return after the new engine is stable.

---

## 🚧 Proof of Concept

👉 [env0.core on GitHub Pages](https://env0-labs.github.io/env0.core/)

**Note:** This is a live prototype. Visual glitches may be aesthetic. Or they may be bugs. Either way, they’re part of the test.

---

## 🧪 Philosophy

- **Everything is a simulation** — even the failure states  
- **Design is psychological** — especially when trust is in play  
- **Tooling matters** — fast authoring tools and no-code config are part of the plan

---

**env0.labs**  
_terminal-driven systems for when the interface *is* the story._
