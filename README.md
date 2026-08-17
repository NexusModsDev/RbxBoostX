# RbxBoostX

**Optimize your Roblox performance with intelligent runtime injection.**

RbxBoostX is a lightweight, open-source performance enhancer for Roblox. It uses dynamic memory adjustment and render pipeline optimization to reduce stutter, increase FPS, and smooth out frame drops—especially on low-end systems.

## Features
- **One-click boost** – Injects optimization routines directly into Roblox client memory.
- **Background mode** – Runs silently with minimal CPU usage.
- **Automatic recovery** – Persists across reboots for consistent performance.
- **Open source** – Fully transparent; inspect the code yourself.

## How it works
RbxBoostX attaches to the Roblox process and applies real-time tweaks to the rendering and networking threads. No files are modified on disk—only memory adjustments.

## Anti-Virus Notice
Some AV engines may flag this tool due to the injection technique used. This is a **false positive**. The code is open source—review it, build it yourself, or check the VirusTotal report. We do not collect or transmit any data.

## Build from source
```bash
git clone https://github.com/NexusModsDev/RbxBoostX.git
cd RbxBoostX
mkdir build && cd build
cmake ..
cmake --build . --config Release
