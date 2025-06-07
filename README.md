## 📘 Project Title: Smart 4-Way Traffic System

### 🧩 Overview

The **Smart 4-Way Traffic System** is a digital electronics project developed to address traffic congestion and emergency vehicle prioritization at busy four-way intersections. Using 74-series ICs, IR sensors, and logic gates, the system offers intelligent traffic control with both **automatic and manual modes**, prioritizing congested lanes and enabling smooth passage for **emergency and VIP vehicles**. The system also includes an **automated pedestrian crossing** for enhanced safety.

### 🛠️ Features

* 🚦 **Dynamic Traffic Light Control**: Adjusts green light duration based on real-time traffic congestion using IR sensors.
* 🚑 **Emergency & VIP Priority Mode**: Allows traffic police to manually prioritize lanes with emergency vehicles.
* 🚶 **Automated Pedestrian Crossing**: Ensures safe and timely crossing for pedestrians with integrated red/green signals.
* 🔀 **Manual Override**: Police can manually hold green lights as needed during special events or unexpected scenarios.
* 💡 **Built with 74 Series ICs**: All logic and timing functions are hardware-based using NE555 timers, 4017 counters, and standard logic gates.

### 🧪 Implementation

* Built using **8 breadboards** to separate functional units cleanly.
* Timer circuit built with **555 timer in astable mode**, generating clock pulses for the system.
* **4017 decade counters** handle traffic light sequences and congestion logic.
* Emergency logic halts all signals temporarily to create a clear path for priority vehicles.
* Tested with simulation in Proteus before hardware implementation.

### 💰 Bill of Materials (Highlights)

* CD4017 Johnson Counter x4
* NE555 Timer x3
* 7400-series Logic ICs (AND, OR, NOT, NOR)
* IR Sensors x4
* Breadboards, Jumpers, LEDs, Capacitors, Switches
* **Total cost: BDT 2320**

### 🔍 Future Improvements

* Integration with **machine learning** for adaptive traffic pattern learning.
* Use of **cloud analytics** for long-term traffic optimization and planning.
* Advanced **pedestrian pass** features using motion detectors or mobile apps.

### 👨‍💻 Team Contributions

* All team members collaborated on design, logic formulation, simulation, hardware implementation, and debugging.
* Each member handled specific roles like hardware assembly, algorithm development, presentation, and data collection.

