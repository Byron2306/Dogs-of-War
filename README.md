# 🐾 Dogs of War (DoW) — Digital Edition

<p align="center">
  <img src="dow 3.png"  width="900" style="max-width: 92%; height: auto;">
</p>


> **"Power through ruthlessness. Freedom through liberty. Perfection through discipline."**

**Dogs of War (DoW)** is an educational, historically themed serious Trading Card Game (TCG) set during World War II. Directly inspired by the mechanical perfection and philosophical depth of *Magic: The Gathering (MtG)*, DoW translates complex historical behaviors into interactive, emergent gameplay strategies.

This repository contains the digital adaptation of the framework originally published in *Creative Education* (2022).

---

## 🧭 Core Philosophy & The Faction Wheel

At the heart of *Dogs of War* is a 6-faction alignment framework adapted from MtG’s iconic color pie. Each nation’s historical role, motivations, and interactions are hardcoded into their gameplay mechanics.

<p align="center">
  <img src="fig 7.png"  width="900" style="max-width: 92%; height: auto;">
</p>

### Faction Breakdowns & Mechanics

| Faction | Primary Goal | Core Mechanic / Keyword | Historical Parallel |
| :--- | :--- | :--- | :--- |
| **Grrmany** 🇩🇪 | Power through ruthlessness | **Ruthlessness**: Rewards cards based on high raw power ("bite"). | Tactical aggression, rapid elimination. |
| **Yelpan** 🇯🇵 | Perfection through discipline | **Discipline**: Multiplies strength if board matches unit types. | Samurai legacy, unwavering honor (Bushido). |
| **Ruffia** 🇷🇺 | Revolution through unity | **Unity**: Synergizes based on identical faction tags. | Mass mobilization, strength in solidarity. |
| **Arferica** 🇺🇸 | Freedom through liberty | **Liberty**: Buffs single blank spaces or positions. | Arsenal of democracy, liberating intervention. |
| **Barktain** 🇬🇧 | Peace through ingenuity | **Ingenuity**: Triggers tactical bonuses based on card count in hand. | Technological marvels (sonar, radar, decoding). |
| **Yipaly** 🇮🇹 | Dominion through persistence | **Persistence**: Activates when deploying a lone survivor on board. | Unification ambitions, relentless drive. |

---

## ⚔️ Gameplay Architecture

Gameplay shifts away from standard life-total grinding toward tactical arena positioning. To win, a player must bypass enemy defenses and **defeat the opposing player’s General**.

### The 3-Lane Battlefield

Battles are fought concurrently across three distinct operational zones:

1. **Lane 1: Home Turf** 🏰
   * Resource-focused framework.
   * Boosts defensive capabilities.
   * Amasses **Pupper Points (PP)** early game.
2. **Lane 2: Deployment** 📡
   * Event-focused design.
   * Limited to one card play per turn.
   * Radiates buffs/debuffs to adjacent combat lanes.
3. **Lane 3: Battlefield** 🪖
   * Expenditure-focused arena.
   * Highly offensive.
   * Best utilized late game.

---

## 🎴 Anatomy of a Unit Card

Stamina (health) loops are entirely removed to optimize for pure, fast-paced tactical calculations.

<p align="center">
  <img src="fig 8.png"  width="900" style="max-width: 92%; height: auto;">
</p>

* **Top Left**: Faction Flag
* **Top Right**: Rarity Paws
* **Center**: Character Artwork
* **Bottom Left**: Combat Resistance
* **Bottom Right**: Combat Weakness

### Balancing: The Combat Triangle
Combat features a built-in balancing matrix mimicking a rock-paper-scissors engine:
$$\text{Air Units} > \text{Sea Units} > \text{Land Units}$$

---

## 📊 Designing for Player Retention

*Dogs of War* integrates elements designed for the four core quadrants of the **Bartle Taxonomy of Player Types**:

* 💎 **Achievers**: Rarity scale milestones.
* ♠️ **Explorers**: Complex, deep tactical synergies.
* ♥️ **Socializers**: Collaborative match evaluations.
* ♣️ **Killers**: Zero-sum tactical dominance.

---

## 🛠️ Getting Started & Installation

### Prerequisites
* Configure required digital environment tools.

### Setup
```bash
# Clone the repository
git clone https://github.com/Dogs-of-War

# Navigate to project root
cd dogs-of-war

# Install dependencies
npm install

# Launch local testing server
npm start
```

---

## 📜 Citation & Academic Background

If you use this codebase, framework, or asset system in an academic or design context, please cite the original paper:

```bibtex
@article{bunt2022pie,
  title={Pie-Eyed: Adapting MtG Elements to Create a New Card Game Called Dogs of War},
  author={Bunt, Byron and Bunt, Lance},
  journal={Creative Education},
  volume={13},
  number={3},
  pages={1022--1044},
  year={2022},
  publisher={Scientific Research Publishing}
}
```
