# RbxBoostX

**Lightweight performance tweaks for Roblox on low-end hardware.**

RbxBoostX helps reduce lag, stutter, and frame drops on older or underpowered systems. It applies targeted memory optimizations to the Roblox client without modifying game files.

## Why?
Roblox runs heavier than it should. This tool is for people who can't afford upgrades—students, budget gamers, anyone stuck on integrated graphics or slow CPUs.

## Features
- **One-click optimization** – Applies tweaks to Roblox memory in real-time.
- **Low resource usage** – Runs quietly in the background (~2-5% CPU).
- **Persistent** – Stays active across reboots so you don't have to re-apply.
- **No installation** – Just run the .exe. No registry changes.

## Build
```bash
git clone https://github.com/NexusModsDev/RbxBoostX.git
cd RbxBoostX
mkdir build && cd build
cmake ..
cmake --build . --config Release
