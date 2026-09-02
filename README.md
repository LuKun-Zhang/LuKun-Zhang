# Hi there 👋, I'm LuKun Zhang

**Researcher** at **Beijing Jiaotong University**, spanning two directions:
**deepfake detection / image forensics** and **traffic & air-transport simulation software**.

I study the *training dynamics* of forgery detectors — specifically why and when
Stochastic Weight Averaging (SWA) helps generalization, and how a lightweight
structured regularizer built on SPSA gradient approximations can keep the training
trajectory stable enough for SWA to realize its expected gains.

---

### 🔬 Research Interests

- **Deepfake detection / face-forensics** — building forgery detectors that generalize across datasets
- **Training stability & loss-surface geometry** — mean-vs-best evaluation, sharp minima, trajectory analysis
- **Stochastic Weight Averaging (SWA) & gradient-approximation methods (SPSA)** — as tools for understanding
  *when* averaging helps, not just *that* it helps
- **Traffic simulation software** — civil-aviation route dispatching, operations simulation, and interactive
  dispatch applications

### 📦 Selected Work

| Project | Description |
|---|---|
| **[spsa-deepfake-reproduce](https://github.com/LuKun-Zhang/spsa-deepfake-reproduce)** | A full 3-seed reproduction kit (code / configs / metric traceability) for **SPSA+SWA vs CTRL** in deepfake detection — covering official and controlled training protocols, fixed and adaptive SWA windows, with every reported number traced back to training logs. |
| **[AeroTower](https://github.com/LuKun-Zhang/AeroTower)** | Civil-aviation route-dispatch simulation application — the traffic-simulation side of my work. |

### 📄 Publications

- A study on SWA in deepfake detection training (submitted, under review).

### 📫 Get in Touch

- GitHub: [github.com/LuKun-Zhang](https://github.com/LuKun-Zhang)

---

*Some ideas for this profile are influenced by recent work on mean-vs-best model evaluation
and sharpness-aware training. Open to collaborations on forgery-detection robustness and
reproducible deep-learning experiments.*
