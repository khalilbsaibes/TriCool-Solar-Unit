# TriCool Solar Unit – Build Instructions

**Author:** Khalil Bsaibes  
**Version:** v0.1  
**License:** CERN-OHL-S (Hardware), CC BY 4.0 (Documentation)

---

## 🧰 Tools Required
- Soldering iron + solder
- Wire cutters and strippers
- Small screwdriver set
- Thermal paste or adhesive
- Epoxy or hot glue
- Utility knife / Dremel (for aerogel shaping)
- Multimeter (for voltage check)
- Optional: 3D printer or CNC cutter

---

## 📦 Components Needed
Refer to the [Bill of Materials](../BOM/BOM.md) for full specifications.

| Component            | Qty |
|----------------------|-----|
| Solar Panel (10W–20W) | 1   |
| Peltier Module (TEC1-12706) | 1 |
| 12V CPU Fan + Heatsink | 1 |
| 5V Brushless Internal Fan | 1 |
| Aerogel Insulation Sheet | 1 |
| Copper Rod / Heat Pipe (optional) | 1 |
| Step-down DC converter | 1 |
| Thermal Paste / Epoxy | — |

---

## 🧱 Assembly Steps

### 1. 🖼️ Prepare the Enclosure
- Cut or print your **triangular casing** (base ≈ 20 cm, height ≈ 5 cm).
- Mount brackets to hold the solar panel at ~45° angle.
- Designate one face for the external fan and one for the internal airflow outlet.

### 2. ☀️ Mount the Solar Panel
- Position on the slanted face.
- Drill small holes for wire pass-through (positive/negative).
- Connect to a **DC buck converter** to ensure 12V stable output.

### 3. ❄️ Mount the Peltier Module
- Place **vertically inside** the tile: one side facing internal air chamber, the other to heatsink.
- Apply **thermal paste** between the Peltier and each contact plate.
- Clamp or screw Peltier between the cold plate (facing inside) and hot side (heatsink).

### 4. 🔥 Attach the Heatsink + External Fan
- Mount the CPU heatsink to the hot side of the Peltier.
- Fix the **12V fan** directly onto the heatsink to expel heat.
- Ensure airflow is outward and unobstructed.

### 5. ❄️ Install the Internal Fan
- Place the **5V blower fan** near the cold side to direct cool air inside.
- Orient for max circulation; shield from direct sunlight.

### 6. 🧪 Insert Aerogel Insulation
- Cut to fit around components without compressing.
- Surround the internal volume, especially under the solar panel.
- Leave space for the copper rod or heat pipe to pass through (if used).

### 7. 🔌 Wiring
- Connect:
  - Solar Panel → DC Converter
  - Converter → Peltier (+ internal & external fans)
- Use proper gauge wire (18–20 AWG) and test with multimeter.
- Consider fusing for overcurrent protection.

### 8. 🧪 Final Checks
- Check solar panel output in sunlight: 12–14V expected
- Confirm Peltier cold side is facing the correct direction
- Ensure airflow is strong on both fans
- Optionally seal the unit with UV-safe resin or ABS/ASA cover

---

## 📎 Tips
- Don’t block airflow on the external side — overheating reduces Peltier efficiency.
- Use **high-quality thermal paste** (≥3W/m·K) for best results.
- Avoid operating in full shade — system is solar-dependent.

---

## 🧪 Optional Add-ons
- Add sensors (e.g. temperature, current monitor) for performance tracking
- Use a fan controller for variable speed based on sunlight
- Stack multiple tiles with shared wiring for larger cooling areas

---

_Last updated: June 2025_
