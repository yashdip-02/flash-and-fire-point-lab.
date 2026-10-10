# flash-and-fire-point-lab.
# Virtual Chemistry Lab: Flash Point & Fire Point Simulator

An interactive, PhET-style virtual laboratory simulation designed for first-year engineering and diploma students following the **Maharashtra State Board of Technical Education (MSBTE 'K Scheme')** curriculum for **Basic Science – Chemistry (Course Code: 311305)**.

---

## 📌 Practical Overview

* **Experiment:** Practical No. 13 – Determination of Flash Point and Fire Point by Cleveland's Open Cup Apparatus
* **Subject:** Basic Science – Chemistry (311305)
* **Standard Test Methods:** 
  * ASTM D92 / IS 1448 [P:69] (Cleveland Open Cup Apparatus)
  * ASTM D93 / IS 1448 [P:21] (Pensky-Martens Closed Cup Apparatus)
* **Course Outcome (CO):** CO6 – Use the appropriate engineering material and catalyst appropriately.

---

## 🚀 Key Features

* **PhET-Style Interactive Simulation:**
  * Dynamic heat transfer model with adjustable heater wattage (0–1000 W).
  * Natural convection, radiation, and ambient cooling simulation.
  * Interactive virtual test flame with realistic arc sweeps across the oil surface.
  * Distinct physical events: momentary vapor flash (flash point) vs. sustained burning $\ge 5\text{ s}$ (fire point).
* **Dual Standard Apparatus Support:**
  * **Cleveland Open Cup (ASTM D92):** Used for petroleum products and lubricating oils having open-cup flash points above 79°C.
  * **Pensky-Martens Closed Cup (ASTM D93):** Used for fuels, diesel, and volatile distillates with mechanical stirring and shutter dip mechanisms.
* **No Spoilers (Discovery-Based Learning):**
  * Does not give away exact flash/fire points upfront.
  * Displays subtle reference spectrum bands while requiring students to observe and record readings independently.
* **MSBTE-Aligned Observation Table:**
  * Manual reading logger matching the official laboratory manual format (Time, Temperature, Test Flame Applied, Observation).
  * Add, edit, delete, and CSV export capabilities.
* **Real-Time Data Plotting:**
  * Live temperature vs. time graph with event milestone pins.
* **Viva Voce & Practical Record:**
  * Integrated theory section, answers to manual questions, and an interactive 10-question viva quiz.

---

## 🧪 Scientific Datasets & References

Scientific reference ranges are separated from the simulation physics engine to prevent misleading assumptions about universal values:

| Material | Appropriate Method | Reference Flash Point | Reference Fire Point | Standard Source |
| :--- | :--- | :--- | :--- | :--- |
| **SAE 20W-50 Engine Oil** | Cleveland Open Cup | 215°C – 230°C | 240°C – 260°C | ASTM D92 / Technical Data Sheet |
| **Diesel Fuel (HSD)** | Pensky-Martens Closed Cup | 55°C – 66°C | N/A (Closed Cup) | ASTM D93 / IS 1460 |
| **Industrial Kerosene** | Pensky-Martens Closed Cup | 38°C – 48°C | N/A (Closed Cup) | ASTM D93 / IP 34 |
| **Gear Oil (ISO VG 220)** | Cleveland Open Cup | 240°C – 255°C | 275°C – 290°C | ASTM D92 / ISO 2592 |
| **Vegetable Oil (Canola)** | Cleveland Open Cup | 310°C – 330°C | 350°C – 368°C | ASTM D92 / USDA Literature |

> *Disclaimer: Reference values are typical ranges based on published technical data sheets and ASTM standards. Actual experimental values vary based on composition, shear history, and ambient pressure.*

---

## 🛠️ Project Structure

```text
├── index.html        # Complete standalone interactive virtual lab application
└── README.md         # Documentation, syllabus alignment, and lab manual details
