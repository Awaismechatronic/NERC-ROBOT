<h1 align="center">🤖 Autonomous Line-Following & Sorting Robot</h1>
<h3 align="center">National Engineering Robotics Contest (NERC) 2026 — Runner-Up 🏆</h3>

<p align="center">
  <b>Runner-Up</b> · <b>Best Design Award</b> · <b>Cash Prize Winner</b><br>
  Indigenous Category — May 2026 to June 2026
</p>

<p align="center">
  <img src="images/pose 1.jpeg" width="270">
  <img src="images/pose 2.jpeg" width="270">
  <img src="images/pose 3.jpeg" width="270">
</p>

---

## 📖 Overview

Built by a 5-member team for the indigenous category of NERC, this robot autonomously navigates to a designated point by following a black line, detects junctions, and turns toward a target **BOX marked with color stripes**. Each round placed the box in a different location, so the robot had to identify the correct color first, then **launch a domino into the box** using an onboard mechanism — entirely without manual control.

The robot's navigation, color detection, and sorting logic were handled through microcontrollers and onboard sensors, all integrated with a custom-designed mechanical system.

**Result:** 🥈 Runner-Up · 🏅 Best Design Award (selected as the best design among all competing teams) · 💰 Cash prize

---

## 🔧 My Role — Mechanical System Design

I was responsible for the robot's mechanical subsystem, including:

- **Domino-holding mechanism** — designed to securely hold dominoes and release them precisely into the target box on command
- **Solenoid-actuated launch system** — used to eject/throw the domino into the box once the correct target was confirmed
- **Stepper motor–driven rotating wheel** — controlled precise rotational positioning for aiming and mechanism timing
- Full **CAD modeling and design iteration** in Fusion 360, balancing weight, structural rigidity, and mounting compatibility with the electronics stack

### CAD / Fusion 360 Files

Full mechanical design files are included in [`/cad`](./cad):

| File | Description |
|---|---|
| `domino_holder.f3d` | Domino-holding mechanism assembly |
| `solenoid_mount.f3d` | Solenoid mounting bracket and launch assembly |
| `stepper_wheel_assembly.f3d` | Stepper motor-driven rotating wheel assembly |
| `full_robot_assembly.f3d` | Complete mechanical assembly |

> 💡 Open `.f3d` files directly in [Autodesk Fusion 360](https://www.autodesk.com/products/fusion-360) (free for students/hobbyists), or export to `.step`/`.stl` for viewing in other CAD tools.

---

## ⚙️ System Overview

| Subsystem | Description |
|---|---|
| **Navigation** | Line-following via IR/color sensors, junction detection logic |
| **Target Detection** | Color sensor identifies correct box among multiple color-striped targets |
| **Actuation** | Solenoid + stepper motor for aiming and domino launch |
| **Control** | Microcontroller-based control logic coordinating sensing and actuation |
| **Mechanical Design** | Domino holder, launch mechanism, rotating wheel assembly (Fusion 360) |

---

## 🛠️ Tools & Technologies

`Microcontrollers` `IR/Color Sensors` `Solenoid Actuator` `Stepper Motor` `Autodesk Fusion 360` `Embedded C/C++`

---

## 👥 Team

Built by a team of five as part of the National Engineering Robotics Contest (NERC) 2026, indigenous category.

---

## 📸 Gallery

<p align="center">
  <img src="images/nerc-robot-1.jpeg" width="400"><br>
  <em>Side view — showing domino-holding mechanism and drivetrain</em>
</p>

<p align="center">
  <img src="images/nerc-robot-2.jpeg" width="400"><br>
  <em>Front view — sensor array for line following and junction detection</em>
</p>

<p align="center">
  <img src="images/nerc-robot-3.jpeg" width="400"><br>
  <em>Rear-angle view — solenoid and stepper motor assembly</em>
</p>
