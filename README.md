# hey, i'm Omka

self-hosted tools, game engines, discord bots & linux handheld ports.

i build things that run on your own machine, don't phone home, and try not to be complete garbage.

### Far Far Away Engine

---

**[Far Far Away Engine](https://github.com/omka-1337/FFA)** - the Rebirth of Unreal Engine 2.

The goal of the project is to create a native engine for ARM that can run games built with Unreal Engine 2. Simply put, it’s a reverse-engineering project of Unreal Engine 2. I was inspired to do this by my desire to play Shrek 2, a game from my childhood, on my RG40XX H. I never found a way to run the game at a decent FPS, so I said "screw it" and decided to build it myself.

The tools for unpacking UE2 packages are ready. Right now, I'm working on the engine itself and recreating its functionality based on Shrek 2.

`C++` · `OpenGL` / `GLES` · `CMake`


### HPL1-Fledged

---

**[HPL1-Fledged](https://github.com/omka-1337/HPL1-Fledged)** — bringing the original HPL1 engine (Penumbra: Overture) back to life.

The upstream work by zenmumbler got it compiling again after years of bitrot. This fork finishes what was left incomplete: a proper multi-pass renderer with lighting, shadows, normal mapping, sky and post-processing, plus **OpenGL ES 3.0** support so it runs on ARM Linux and handhelds — not just desktops.

Built for real hardware. Currently powering the Penumbra: Overture PortMaster port.

`C++` · `OpenGL` / `GLES` · `CMake`

---

### 🔥 other projects

| Project | What it is | Stack |
|---------|------------|-------|
| **[Doppler](https://github.com/omka-1337/doppler)** | Self-hosted Discord bot that ships empty. Features are plugins installed from GitHub. Plugin code never sees your API keys. | Python · Docker · Web Dashboard |
| **[Possum](https://github.com/omka-1337/possum)** | Self-hosted panel for game servers (Minecraft → CS 1.6) running in Docker. Panel + agent architecture. | Python · Go · React · Docker |
| **[Hermit](https://github.com/omka-1337/hermit)** | BepInEx mod manager made for Linux & Steam Deck. Profiles, Thunderstore, controller layout. | Go · React · Wails |

---

### 🎮 PortMaster ports

I own an **Anbernic RG40XX H** and actively work on ports for PortMaster / ROCKNIX.

| Port | Engine | Notes |
|------|--------|-------|
| **[Fear & Hunger](https://github.com/omka-1337/FearAndHunger-PortMaster)** | NW.js (RPG Maker MV) | Playable on RG40XX. Needs ROCKNIX (DRM/KMS). Audio optimization + performance tweaks included. |
| **[Penumbra: Overture](https://github.com/omka-1337/PenumbraOverture-PortMaster)** | HPL1-Fledged | To create this port, I had to modify the Frictional Games engine and adapt it for ARM and GLES. Thanks to zenmumbler for his work on HPL1-Rehatched, on which HPL1-Fledged is based. |
| **[BLACK SOULS](https://github.com/omka-1337/BlackSouls-PortMaster)** | mkxp-z (RPG Maker VX Ace) | Full support for translations via `patches/`. Tested with Russian translations. |
| **[BLACK SOULS II](https://github.com/omka-1337/BlackSouls2-PortMaster)** | mkxp-z (RPG Maker VX Ace) | Same translation system. Handles both reduced Steam build and full data. |

---

### 🛠 tech i like

`C++` `OpenGL` `GLES` `Python` `Go` `TypeScript` `React` `Docker` `Linux` `Steam Deck` `PortMaster` `Anbernic`

---

### 📌 currently

- deep in **HPL1-Fledged** — getting Penumbra running properly on handhelds
- refining **Doppler** & **Possum**
- more PortMaster ports for the RG40XX
- keeping things self-hosted and relatively sane

---

*I use Arch btw*
