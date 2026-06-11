# VR Multiplayer Template

A Unity starter template for building **multiplayer virtual-reality** applications. It
provides a ready-made interaction rig and networked multiplayer so multiple headset users
can share and interact in the same VR space.

## Overview

The template wires together **Photon Fusion** for networking and the **Oculus/Meta VR
SDK** for headset interaction, giving you a working base to extend instead of starting
from scratch.

## Features

- **Networked multiplayer:** Powered by **Photon Fusion** (`Fusion.Unity` assemblies,
  `Assets/Photon` + `Assets/Photon Scripts`) for synchronized player state across clients.
- **VR interaction rig:** `InteractionRigOVR` prefab built on the **Oculus Integration /
  Meta XR** SDK (`Assets/Oculus`, `Assets/XR`) for grabbing and interacting with objects.
- **Reusable prefabs, scenes and resources** under `Assets/` to bootstrap a project.
- **Customizable & extensible** starting point for collaborative VR experiences.

## Requirements

- **Unity** 2021.3.0f1 or later
- **Photon Fusion** (a free Photon account + App ID — set it in the Photon AppSettings)
- **Oculus/Meta XR SDK** (included under `Assets/Oculus`)
- A Meta Quest / Oculus headset for testing

## Installation

```bash
git clone https://github.com/Rathesh0709/VR-Multiplayer-Template
```

1. Open the project in Unity (matching version above).
2. Add your **Photon Fusion App ID** in the Photon app settings.
3. See [INSTALLATION.md](INSTALLATION.md) for detailed setup steps.

## Usage

- Put on your headset and navigate using the VR controllers.
- Interact with objects in the scene via the interaction rig.
- Join or host a session to connect with other players in the shared VR space.

## License

MIT License — see [LICENSE](LICENSE).

## Contact

- **Rathesh Kumar** — rathesh0709@gmail.com — https://rathesh07.github.io/portfolio/
