<div align="center">

# 🌊 Makon Software

**Building the tools for the next generation of underwater robotics simulation.**

[![Organization](https://img.shields.io/badge/GitHub-Makon--Software-24292e?style=flat-square&logo=github)](https://github.com/Makon-Software)
[![Engine](https://img.shields.io/badge/Engine-Stride-4A90D9?style=flat-square)](https://www.stride3d.net/)
[![Language](https://img.shields.io/badge/Language-C%23-239120?style=flat-square&logo=csharp)](https://dotnet.microsoft.com/)
[![Status](https://img.shields.io/badge/Status-MVP%20in%20Progress-orange?style=flat-square)]()

</div>

---

## 🚀 Who We Are

**Makon Software** is an early-stage startup developing open-source tools and simulation frameworks for underwater remotely operated vehicles (ROVs). We believe that the barrier to building, simulating, and testing ROVs should be as low as possible — for researchers, engineers, hobbyists, and students alike.

Our focus is on **real-time physics fidelity**, **modular architecture**, and **developer experience**. We build on top of the **Stride** game engine (C#) to deliver a production-quality simulation layer that just works.

---

## 🔧 What We're Building

### ROV Toolkit

> *A complete simulation and control framework for underwater vehicles, built as a first-class component library for the Stride game engine.*

The ROV Toolkit gives developers everything they need to simulate a functional underwater robot:

| Module | Description |
|---|---|
| **Physics** | Buoyancy, underwater drag, water currents, anti-gravity |
| **Propulsion** | Configurable thruster system with 4H and 4H+2V layouts |
| **Sensors** | Sonar (raycast fan + ASCII display), Camera, Depth + Telemetry HUD |
| **Autopilot** | ROVScript framework — abstract C# scripts for autonomous control |
| **Vehicle Builder** | Entity factory with typed mount points — build a full ROV in seconds |

Everything is **component-based**, **editor-friendly**, and designed to be extended without touching the core.

---

## 🏗️ Architecture at a Glance

```
ROVToolkit/
├── Physics/           # Buoyancy, Drag, Water, Anti-gravity, Thrusters
├── Sensors/           # Sonar, Camera, HUD, Telemetry
├── Scripts/           # ROVScript base, Autopilot, HoldDepth PD controller
├── Vehicle/           # ROVBase, MountPoint, VehicleBuilder
└── Control/           # ThrusterMixer (keyboard + autopilot)
```

A single entity. A handful of components. A fully simulated ROV.

---

## 🌍 Our Vision

Underwater robotics is critical for ocean exploration, infrastructure inspection, scientific research, and environmental monitoring. Yet the software tooling lags far behind what's available in the aerial drone space.

We're changing that — one module at a time.

**Our Goals:**
- 🔓 Open-source core toolkit
- 🧩 Plug-and-play component design
- 🎓 Education-first documentation
- 🌐 Multi-ROV simulation support
- 🤝 Community-driven extension ecosystem

---

## 📦 Repositories

| Repo | Description | Status |
|---|---|---|
| [**Makon**](https://github.com/Makon-Software/Makon) | Main ROV Toolkit — Stride C# component library | 🟢 Active |

---

## 🛠️ Tech Stack

- **Engine**: [Stride](https://www.stride3d.net/) (C# / .NET)
- **Language**: C# 12 / .NET 10
- **Physics**: Bullet Physics (via Stride)
- **Version Control**: Git / GitHub

---

## 🤝 Contributing

We're in early MVP. Contributions, issues, and ideas are welcome.

The best way to start is to open the project in [Stride Game Studio](https://www.stride3d.net/), build the solution, and explore the `ROVToolkit/` folder.

---

## � Team

| | Name | Role |
|---|---|---|
| 🧑‍💻 | **Cássio João** | Co-founder · Engine & Systems |
| 🧑‍💻 | **Renan GCV** | Co-founder · Simulation & Architecture |
| 🧪 | **João Victor Mesquita** | Co-founder · QA & Testing |

---

## �📬 Contact

Reach us through GitHub — open an issue or start a discussion.

---

<div align="center">

*Built with ❤️ and a healthy curiosity about what lives under the water.*

**Makon Software © 2026**

</div>
