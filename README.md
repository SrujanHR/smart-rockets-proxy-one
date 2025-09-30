# Smart Rocket Proxy One 🚀

A lightweight prototype of the **Smart Rockets Genetic Algorithm project**, built in **Python with Pygame**. This version focuses on testing movement, angle exclusion, and basic fitness evaluation as a foundation for later evolutionary improvements.

---

## 📖 Overview

Smart Rocket Proxy One is an early trial project that simulates triangles ("rockets") navigating toward a target point.
Unlike the full GA version, this prototype primarily experiments with:

* Randomized movement and exclusion of poor-performing angles.
* Fitness measurement based on distance to the target.
* Visualization of motion in a Pygame window.

---

## ✨ Features

* **Random angle assignment**: Rockets are initialized with random headings.
* **Exclusion logic**: Identifies poorly performing directions and prevents re-use in later attempts.
* **Basic fitness evaluation**: Rockets are compared by distance to the goal.
* **Interactive visualization**: Real-time motion rendered with Pygame.

---

## 🛠️ Dependencies

* **Python 3.11** (recommended)
* **Pygame** (install with `pip install pygame`)

---

## ▶️ How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/smart-rocket-proxy-one.git
   cd smart-rocket-proxy-one
   ```
2. Install dependencies:

   ```bash
   pip install pygame
   ```
3. Run the simulation:

   ```bash
   python proxy_one.py
   ```

---

## 📌 Notes

* This is **not the full genetic algorithm version**, but a stepping stone toward **Smart Rockets v2**.
* Useful for experimenting with motion, randomization, and early exclusion strategies.

---

## 🏷️ GitHub Topics

```
genetic-algorithm
pygame
python
simulation
artificial-intelligence
evolutionary-computation
smart-rockets
prototype
visualization
```

---

## 🙌 Acknowledgments

Inspired by Daniel Shiffman’s "Smart Rockets" concept and implemented here as an exploratory learning project.
