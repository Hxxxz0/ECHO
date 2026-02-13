# ECHO: Edge-Cloud Humanoid Orchestration for Language-to-Motion Control

Browser-based demo for language-conditioned humanoid whole-body control. The app runs a MuJoCo WebAssembly scene driven by an ONNX tracking policy and connects to a text-to-motion backend for language-driven motion generation.

---

## Overview

This project implements a deployment-oriented **edge–cloud** setup: a diffusion-based text-to-motion generator produces **robot-native** motion references on the server, while a lightweight tracking controller runs in the browser (and on-robot) in closed loop. The motion representation is a compact **38D velocity-based** format (joint positions, root velocity, height, and rotation) that is retargeting-free and tracker-friendly.

**Contributions:** Edge–cloud language-to-humanoid control with streaming motion references; robot-native 38D motion interface; evaluations in simulation and on a real humanoid robot.

---

## TODOS

- ✓ **Demo** — [Live demo](https://hxxxz0.github.io/ECHO/) (released)
- **Paper** — Coming soon
- **Training code** — Coming soon
- **Dataset** — Coming soon

---

## License

See [LICENSE](LICENSE) for license terms.
