<div align="center">
<img width="775" height="459" alt="Witch Survivor Banner" src="https://github.com/user-attachments/assets/aecc2f91-7aad-42b5-87db-e4dfd3c11e22" />



# 🔮 Witch Survivor

**A magic-themed rogue-lite horde survival game.**

<p align="center">
  <a href="https://github.com/Linlang121/Witch-Survivor/stargazers">
    <img src="https://img.shields.io/github/stars/Linlang121/Witch-Survivor?style=for-the-badge&color=8A2BE2" alt="Stars">
  </a>
  <a href="https://github.com/Linlang121/Witch-Survivor/network/members">
    <img src="https://img.shields.io/github/forks/Linlang121/Witch-Survivor?style=for-the-badge&color=4B0082" alt="Forks">
  </a>
  <a href="https://github.com/Linlang121/Witch-Survivor/issues">
    <img src="https://img.shields.io/github/issues/Linlang121/Witch-Survivor?style=for-the-badge&color=FF69B4" alt="Issues">
  </a>
</p>

</div>

---

## 📖 About the Project

> The night falls, and the monsters surge like a tide. As the last witch, can you survive the endless darkness until dawn?

**Witch Survivor** is a C++ 2D action game in a Vampire Survivors–style roguelike, with player movement and combat, NPC AI and projectiles, tile-based world, camera follow, and save/load, built on a custom graphics framework.This project leverages the GamesEngineeringBase C++ framework to demonstrate core game development principles and technologies.


<br>

## 🎥 Demo Video


https://github.com/user-attachments/assets/1b68f0d7-8c6c-44d8-8c6d-c900d9faa469



<br>

### ✨ Core Features

* 🎥 **Custom 2D Virtual Camera System:** Implements robust world-to-screen coordinate transformations to ensure seamless entity tracking and fluid rendering.
* 👾 **Dynamic Spawning & Difficulty Scaling:** Features four distinct enemy archetypes (Melee, Tank, Ranged, and Elite). Utilizes optimized off-screen spawning algorithms coupled with adaptive difficulty progression.
* 💥 **High-Precision Collision Detection:** Employs a hybrid collision architecture, combining circular bounding boxes with multi-point tile collision queries for accurate spatial interactions.
* 🎯 **Advanced Targeting & Ballistics:** Implements linear projectile trajectories targeting the nearest entity, visually augmented by **Bresenham's Line Algorithm**. Features intelligent AOE mechanics that dynamically sort and target enemies based on HP thresholds.
* ⚡ **Dynamic Progression System:** Kill-triggered enhancement loop that programmatically modifies player DPS via real-time fire rate buffs and increased AOE target caps.
* 🗺️ **Optimized Rendering Pipeline:** Built on a data-driven tilemap architecture utilizing strict **Viewport Culling**, significantly reducing draw calls and rendering overhead for out-of-bounds sprites.
* 💾 **Lightweight Data Persistence:** Features a custom **Binary Serialization** system for rapid, low-overhead game state saving and loading (Hotkeyed to `K`/`L`).
* 📊 **Built-in Telemetry:** Integrated real-time FPS monitoring and basic performance profiling tools to track rendering and logic bottlenecks on the fly.
<br>


## 🖼️ Gallery

Explore the world and mechanics of *Witch Survivor*:

| <img src="https://via.placeholder.com/400x225/222222/FFFFFF?text=Screenshot+1" alt="Magic Swarm"> | <img src="https://via.placeholder.com/400x225/222222/FFFFFF?text=Screenshot+2" alt="Boss Fight"> |
| :---: | :---: |
| **Magic Swarm** | **Epic Boss Fights** |
| <img src="https://via.placeholder.com/400x225/222222/FFFFFF?text=Screenshot+3" alt="Upgrade Menu"> | <img src="https://via.placeholder.com/400x225/222222/FFFFFF?text=Screenshot+4" alt="Character Select"> |
| **Skill Upgrades & Evolutions** | **Character Selection** |

<br>

## 🚀 Getting Started

Follow these steps to get a copy of the project up and running on your local machine for development and testing.

### Prerequisites

* **Game Engine:** [Insert your engine here, e.g., Unity 2022.3 LTS / Godot 4.x]
* **OS:** Windows 10/11, macOS, or Linux
* **Git:** Make sure you have Git installed.

### Installation & Running

**1. Clone the repository**
```bash
git clone [https://github.com/Linlang121/Witch-Survivor.git](https://github.com/Linlang121/Witch-Survivor.git)
