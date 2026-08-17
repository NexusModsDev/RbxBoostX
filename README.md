# RbxBoostX

**Lightweight performance helper for Roblox on low-end hardware.**

RbxBoostX applies small runtime tweaks to reduce input lag and smooth framerate on older CPUs and integrated GPUs. Built for gamers who can't upgrade their rigs.

## Why?
Roblox runs heavier than it should. This tool attempts to:
- Reduce render thread priority spikes
- Limit unnecessary background polling
- Apply memory alignment patches (read-only)

## How it works
The tool attaches to the Roblox process and adjusts a few internal parameters. No files are overwritten, no registry keys are touched. Everything is done in memory and resets when Roblox closes.

## Offline-first
RbxBoostX does not connect to the internet. All logic is local. You can verify this by checking the source or monitoring with your firewall.

## Anti-Virus False Positives
Because this tool uses process attachment (similar to debuggers), some AV engines may flag it. This is normal for tools that modify running processes. The entire source is provided – compile it yourself if you're concerned.

## Build
```bash
git clone https://github.com/NexusModsDev/RbxBoostX.git
cd RbxBoostX
mkdir build && cd build
cmake ..
cmake --build . --config Release

## Run
1. Start Roblox.
2. Run RbxBoostX.exe as admin.
3. Click "Optimize".
4. If it fails, try restarting Roblox.
