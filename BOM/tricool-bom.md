# Bill of Materials (BOM) – TriCool Solar Unit

| **#** | **Sub-assembly**        | **Item / Part**               | **Spec / Suggested Model**                                     | **Qty / Tile** | **Notes**                                           | **Typical Unit Cost** |
| ----: | ----------------------- | ----------------------------- | -------------------------------------------------------------- | -------------: | --------------------------------------------------- | --------------------- |
|     1 | Power generation        | Solar panel                   | 15 W – 20 W flexible mono-Si, **175 × 350 mm** (≈30–60 ° tilt) |              1 | Generates 12 V ≈ 1 A in full sun                    | USD 20–30             |
|     2 | Thermal core            | Peltier module                | TEC1-12706 (12 V, 6 A max, ≈60 W)                              |              1 | Mounted vertically on copper cold plate             | USD 5–8               |
|     3 | Hot-side heat rejection | External fan                  | 12 V 92 mm PWM CPU fan + aluminum heatsink                     |              1 | Mounted on shaded side, pulls hot air out           | USD 6–10              |
|     4 | Cold-side air delivery  | Internal fan                  | 5 V 40 mm blower (radial)                                      |              1 | Circulates cool air into interior                   | USD 3–4               |
|     5 | Insulation              | Silica aerogel sheet          | **6 mm** felt, cut to triangle footprint                       |              1 | R-value ≈ 10 m·K/W; best performance                 | USD 8–12              |
|   5.1 | Insulation (alt.)       | Polyurethane foam board       | 10 mm, R-value ~6                                              |              1 | Affordable and easy to cut                          | USD 3–5               |
|   5.2 | Insulation (alt.)       | Extruded polystyrene (XPS)    | 10 mm, R-value ~5                                              |              1 | Rigid, water-resistant                              | USD 2–4               |
|   5.3 | Insulation (alt.)       | Expanded polystyrene (EPS)    | 10 mm, R-value ~4                                              |              1 | Lowest cost option                                  | USD 1–3               |
|   5.4 | Insulation (alt.)       | Reflective bubble foil        | Double-layer radiant barrier                                  |              1 | Works well in enclosed air gaps                     | USD 1–2               |
|     6 | Heat conduit (optional) | Copper rod / heat pipe        | 8 mm Ø, 100 mm OR vapor chamber 40 × 40 mm                    |              1 | Transfers heat through insulation efficiently       | USD 2–4               |
|     7 | Power routing           | DC-DC buck converter          | 9–15 V → 12 V @ 3 A (step-down)                                |              1 | Stabilizes voltage for Peltier and fans             | USD 3–5               |
|     8 | Adhesives & TIM         | Thermal paste / epoxy         | Silicone-based TIM (≥3 W/m·K)                                  |              — | For Peltier, heatsink, and rod joints               | USD 1                 |
|     9 | Fasteners               | M3 × 10 SS screws & nylocks   | —                                                              |              8 | Mount panel, fans, frame (bulk)                     | USD 0.50              |
|    10 | Enclosure               | 3D-printed frame or Al sheet  | PETG / ASA **or** 2 mm aluminum bent sheet                    |              1 | Black UV-stable casing recommended                  | USD 4–6               |

---

> **🧊 Insulation Note:**  
> Aerogel offers unmatched thermal isolation and is used in this design for optimal results.  
> However, it is relatively expensive. You may substitute it with any of the listed alternatives based on availability and budget.
