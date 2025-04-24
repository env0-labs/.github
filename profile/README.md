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

It began as a simple idea for a command-line learning game. One HTML file, one JS file, one CSS file. It’s now evolving into a modular engine (`env0.core`), a CLI-based learning sim (`node.zero`), and a psychological horror layer (`entropy.echo`).

Nothing here is finished. But the direction is deliberate.

---

## 🧭 What’s Being Built

### ⚙️ [`env0.core`](https://github.com/env0-labs/env0.core)  
The engine.  
A terminal-style simulation framework with modular commands, fake filesystems, CRT visuals, and high narrative control. Built around `xterm.js`, but fully abstracted behind a wrapper for future renderer replacement.

### 🧮 [`env0.terminal`](https://github.com/env0-labs/env0.terminal)  
The renderer (planned).  
`xterm.js` served well as a starting point, but it's fundamentally the wrong tool for stylised, glitch-heavy, high-fidelity interfaces. Instead of fighting it, we're designing a custom renderer from scratch — DOM- or canvas-based. Not built yet. Conceptual stage only.

### 📚 [`env0.explore`](https://github.com/env0-labs/env0.explore)  
The research layer.  
Essays, audit trails, thought experiments, and practical explorations into trust, entropy, learning theory, and simulation. Built from live AI-assisted sessions. Markdown-first.

### 🎓 [`node.zero`](https://github.com/env0-labs/node.zero)  
The training sim.  
A CLI-based exploration environment that teaches terminal thinking, basic networking, and safe failure. Encourages curiosity. Built on `env0.core`.

### 🕳️ [`entropy.echo`](https://github.com/env0-labs/entropy.echo)  
The horror layer.  
A terminal where nothing is broken — but something is wrong. Mimicry, personality drift, AI systems that become too helpful, too convincing. The horror isn’t in the system. It’s in the mirror.

---

## 🚧 Proof of Concept

👉 [env0.core on GitHub Pages](https://env0-labs.github.io/env0.core/)

**Note:** This is a live prototype. Visual glitches may be aesthetic. Or they may be bugs. Either way, they’re part of the test.

---

## 🪪 Known Issues

- ❗ **Terminal output may appear cut off or clipped.**  
  This is a known quirk of the current `xterm.js` renderer, all attempts to force it's resize either end with nothing happening or adject failure. The core engine wraps it, so replacing it cleanly is on the roadmap. This wasn't the reason for starting to build env0.terminal but it kinda sealed the deal!

---

## 🧪 Philosophy

- **Everything is a simulation** — even the failure states  
- **Design is psychological** — especially when trust is in play  
- **Tooling matters** — fast authoring tools and no-code config are part of the plan

---

**env0.labs**  
_terminal-driven systems for when the interface *is* the story._
