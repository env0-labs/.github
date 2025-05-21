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

**env0.labs** started as a pure web project (HTML, CSS, JS, and a custom canvas terminal renderer). After weeks of renderer pain, performance issues, and tight coupling between display and logic, the project shifted direction:

- **Unity was chosen as a front end** to offload visuals and handle immersive effects. But Unity as an all-in-one solution was too heavy and restrictive for true system simulation.
- The project split: **C# became the logic core**, and Unity is now the orchestration/presentation layer.
- The original game, `node.zero`, is on hold—not abandoned, but parked after realizing that maintaining two major games and a backend was too much to take on solo.
- **Current direction:**  
  - **env0.terminal**: Pure C# DLL, simulation engine, zero UI. Handles all logic, filesystem, and network state. Testable and platform-agnostic.
  - **entropy.echo**: Unity front end and game orchestration. Handles all visuals, audio, FX, and story layering. Owns the world state and orchestrates play.
  - **env0.explore**: Ongoing essays, audits, and knowledge trails.

The JavaScript proof-of-concept remains for reference only. Everything is being rebuilt from the ground up, leveraging lessons learned.

Nothing here is finished. But the direction is deliberate.

---

## 🏗️ Active Projects

### ⚙️ [`env0.terminal`](https://github.com/env0-labs/env0.terminal)
**Pure C# logic engine.**  
A platform-agnostic simulation core for modular commands, virtual filesystems, and networking. Plug it into Unity, CLI, or web UIs. The “brain” of all future env0.labs projects.

### 🖥️ [`entropy.echo`](https://github.com/env0-labs/entropy.echo)
**Unity game + orchestration layer.**  
Owns world state, handles visuals, audio, and narrative. Talks to env0.terminal via a strict one-way interface—DLL accepts only input and broadcasts output; Unity never sends internal state back.

### 📚 [`env0.explore`](https://github.com/env0-labs/env0.explore)
Essays, audit trails, and explorations into trust, entropy, learning theory, and simulation. Markdown-first, AI-assisted.

---

## 🗂️ Archived & Paused Projects

### 🗂️ JavaScript projects (`env0.core`, `env0.terminal.archive`)
Legacy JS/HTML/CSS terminal renderers and early experiments. All are now deprecated in favor of the pure C# approach.

### 🗂️ [`node.zero`](https://github.com/env0-labs/node.zero)
CLI-based adventure environment — paused, not abandoned. Will return after core systems stabilize.

---

## 🚧 Proof of Concept

👉 [env0.core on GitHub Pages](https://env0-labs.github.io/env0.core/)

**Note:** This is a live, JavaScript-based prototype. Visual glitches may be intentional, or bugs. Either way, it’s proof the whole thing is getting rebuilt from scratch.

---

## 🧪 Philosophy

- **Everything is a simulation** — even the failure states  
- **Design is psychological** — especially when trust is in play  
- **Tooling matters** — fast authoring tools and no-code config are part of the plan

---

**env0.labs**  
_terminal-driven systems for when the interface *is* the story._