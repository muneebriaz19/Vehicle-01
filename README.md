# Vehicle 1 – Sensor-Driven Motion Simulation

This project is a simulation of **Vehicle 1**, inspired by *Braitenberg's Vehicles*. It's built in **Unreal Engine** and explores fundamental concepts in perception, motion, and artificial behavior using the simplest possible robot: one sensor, one motor, and a world with gradients (like temperature).

## 📘 Concept

**Vehicle 1** is a theoretical construct from Valentino Braitenberg’s book, *Vehicles: Experiments in Synthetic Psychology*. It consists of:
- One **sensor** that detects an environmental variable (e.g., temperature).
- One **motor** that drives the vehicle forward, with speed **proportional** to the sensor input.

The vehicle moves faster in warmer regions and slows down in colder areas. Since the sensor is unidirectional, it blindly follows whatever direction it was initially facing—creating the illusion of purpose or preference, even though its behavior is purely reactive.

## 🎮 Project Features

- Accurate simulation of **sensor-motor coupling**
- A dynamic environment with **temperature gradients**
- Realistic **friction modeling** (e.g., motion decay in cold zones)
- Custom **vehicle behavior** scripting mimicking Aristotelian physics
- Simplified visuals and physics ideal for educational/demo use

## 🌡 Behavior Summary

| Condition         | Outcome                                        |
|------------------|------------------------------------------------|
| Warmer area      | Higher motor force, faster movement            |
| Colder area      | Lower motor force, potential rest              |
| No friction (outer space) | Continuous motion with variation       |
| With friction (Earth) | Irregular, Brownian-like motion at low force |

## 🧰 Requirements

- Unreal Engine 5.x
- Windows or MacOS
- (Optional) Visual Studio for C++ compilation

## 🚀 Running the Simulation

1. Clone or download the project files.
2. Open `vehicle1.uproject` using Unreal Engine.
3. Press **Play** to run the simulation.
4. Observe how the vehicle responds to different temperature zones.

## 📷 Preview

![Vehicle Diagram](./image.png)

> *Figure 1: Vehicle 1. The speed of the motor (tail) is controlled by a front-facing sensor. Motion is forward, affected only by environment and friction.*

## 🧠 Philosophical Context

> "It is alive," you might say, seeing it roam aimlessly—yet consistently—toward warmer zones, much like primitive life forms that exhibit tropisms. Braitenberg uses such vehicles to challenge our assumptions about intelligence and behavior.

## 🤝 Contributions

This project is open for experimentation and extension. Want to simulate Vehicle 2 or add neural-style behavior? Fork it, mod it, and share your insights.

## 📄 License

[MIT License] or your preferred open-source license.

---

> Inspired by *Braitenberg's Vehicles* — simple components, complex behavior.
