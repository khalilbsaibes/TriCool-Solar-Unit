# TriCool Solar Unit – Design Overview

**Author:** Khalil Bsaibes  
**Version:** v0.1  
**License:** CERN-OHL-S (Hardware), CC BY 4.0 (Documentation)

---

## 📌 Concept

The **TriCool Solar Unit** is a modular, battery-free cooling tile designed to provide active thermal regulation using only solar energy. Inspired by the need for efficient, compact cooling in mobile and off-grid environments, each tile integrates:

- A photovoltaic solar panel
- A thermoelectric cooling element (Peltier module)
- Dual fan system (internal circulation and external exhaust)
- Aerogel insulation
- An optional heat transfer conduit (copper rod or vapor chamber)

Its **triangular form** supports modular tiling across vehicle roofs, caravan panels, or standalone surfaces.

---

## 🧠 Design Philosophy

The system was designed to:
- **Operate only during peak sunlight** without energy storage
- Maximize **cooling efficiency per square cm**
- **Isolate interior and exterior heat transfer** using aerogel
- Be open-source, reproducible, and adaptable
- Keep component count and wiring to a minimum

---

## 🔺 Geometry & Layout

Each unit is a **triangular prism**, mounted with:
- **One face angled outward (solar panel)**
- **One face shaded with exhaust fan and heat sink**
- **One face facing down or inward for air cooling**

Internally:
- The **Peltier module** is mounted vertically between the hot and cold zones
- Aerogel lines the interior for passive thermal isolation
- Airflow is controlled by a **5V blower** (internal) and a **12V CPU fan** (external)

---

## 🔁 Energy Flow

[Sunlight] → [Solar Panel] → [Peltier + Fans]
↓ ↓
Electricity Hot side → Fan → Outside
Cold side → Fan → Interior


---

## 🧊 Why No Battery?

Batteries add cost, complexity, and degrade over time — but the TriCool unit **only needs to cool when the sun is out** (when it’s hottest).  
This makes it ideal for:
- Rooftop cooling in hot climates
- Ventilated mobile units
- Passive solar-aligned control

---

## 🧪 Materials Rationale

| Component     | Why It Was Chosen                          |
|---------------|---------------------------------------------|
| **Aerogel**   | Extremely low thermal conductivity, ultralight |
| **Peltier TEC1-12706** | Readily available, 12 V compatible, well-documented |
| **Copper Rod / Heat Pipe** | Transfers heat through aerogel without compromising insulation |
| **Modular triangle shape** | Stackable, water-shedding, minimal shading between tiles |

---

## 🛠️ Intended Use Cases

- Off-grid cooling panels for caravans and mobile homes
- Solar-powered exhaust tiles for tents and emergency shelters
- Scalable climate control tiles for container houses
- Educational kits on thermoelectric cooling

---

## 🔓 Open-Source Commitment

TriCool is released as an **open hardware and open documentation project** under:
- [CERN-OHL-S v2.0](https://ohwr.org/project/cernohl/wikis/Documents/CERN-OHL-version-2)
- [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

Collaborators are encouraged to fork, improve, and redistribute — with attribution.

---

_Last updated: June 2025_
