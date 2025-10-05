# Oral Notes

---

## Written Test Incorrect Areas

### PA.I.A.K1 — Certification Requirements, Recent Flight Experience, and Record Keeping
**Regulation:** [14 CFR §61.57](https://www.ecfr.gov/current/title-14/chapter-I/subchapter-D/part-61/subpart-A/section-61.57)

| Requirement | Condition | Description |
|--------------|------------|-------------|
| 90 days | Passenger-carrying | At least 3 takeoffs and 3 landings (same category/class/type) |
| 90 days (night) | 1 hr after sunset → 1 hr before sunrise | 3 full-stop landings during that period |
| Flight Review | Every 24 months | 1 hr ground + 1 hr flight instruction |
| Medical | Varies by class | 3rd Class valid 60 mo (<40 yrs), 24 mo (≥40 yrs) |

---

### PA.I.D.K2 — Privileges and Limitations
**Regulation:** [14 CFR §61.113](https://www.ecfr.gov/current/title-14/chapter-I/subchapter-D/part-61/subpart-E/section-61.113)

| Privilege | Limitation |
|------------|-------------|
| Act as PIC for non-commercial flight | ❌ No compensation or hire (不得有偿飞行) |
| Share operating expenses | Only **pro rata share** of fuel, oil, airport, rental fees |
| Charitable / Nonprofit / Community event flights | Under §91.146, FAA approval required |
| BasicMed operations | ≤ 6 passengers + pilot, ≤ 12,500 lbs, ≤ 250 KIAS |

---

### PA.I.G.K1c — Powerplant and Propeller
**Ref:** [PHAK Ch. 7](https://www.faa.gov/regulationspolicies/handbooksmanuals/aviation/phak/chapter-7-aircraft-systems)

#### Engine
- **4-stroke cycle:** Intake → Compression → Ignition → Exhaust
- **Oil functions:** Lubricate, Cool/Heat, Seal, Clean, Actuate (驱动)

#### Left-Turning Tendencies (左转趋势)
| Effect | Description |
|--------|-------------|
| Torque | Prop rotates CW → aircraft rolls left |
| P-Factor | Descending blade produces more thrust at high AOA |
| Spiraling Slipstream | Air hits tail from left, yawing left |
| Gyroscopic Precession | Pitch-up force acts 90° later, yawing left |

---

### PA.IV.N.K3 — Wind Correction on Takeoff / Landing
**Ref:** [AFH Ch. 9](https://pilotinstitute.com/crosswind-landings)

| Phase | Correction |
|-------|-------------|
| Takeoff Roll | Aileron into wind |
| Climb-out | Rudder to maintain centerline |
| Approach | Crab into wind |
| Flare / Touchdown | Transition to sideslip (rudder + aileron) |

---

### PA.IX.D.K1 — Emergency Locator Transmitter (ELT)
**Ref:** [AIM 6-2](https://www.faa.gov/air_traffic/publications/atpubs/aim_html/chap6_section_2.html)

| Requirement | Description |
|--------------|-------------|
| Battery | Replace after 1 hr cumulative use or 50 % of life |
| Inspection | Every 12 months |
| Testing | Only within first 5 min after the hour |

---

### PA.VI.A.K5b — Wind Correction Angle
Compute drift to maintain ground track.
Use E6B — inputs: heading, TAS, wind direction, wind speed.


---

## ✈️ Airspace 🗺️

| Class | Altitude | Radius | Weather Min | Equipment | Notes |
|--------|-----------|---------|--------------|------------|--------|
| A | FL180–FL600 | — | IFR only | Mode C, IFR clearance | Use 29.92 |
| B | Up to 10,000 MSL | Tailored | 3 SM COC | Mode C, ADS-B, radio clearance | ≤ 250 KIAS (≤ 200 below 2500AGL) |
| C | 4,000 AGL | 10 NM | 3-152 | Mode C, ADS-B, 2-way radio | ≤ 200 KIAS |
| D | 2,500 AGL | 4 NM | 3-152 | 2-way radio | ≤ 200 KIAS |
| E < 10k | — | — | 3-152 | — | — |
| E > 10k | — | — | 5-111 | — | — |
| G Day | — | — | 1SM, coc<1200AGL, 152 1200AGL-10000MSL | — | Uncontrolled |
| G Night | — | — | 3-152 | — | Uncontrolled |

Different Class E Spaces:
* Surface: to 17999 MSL
* Extension: for IFR traffic
* Transition: Shadow / solid side
* Victor: Victor airways, 1200AGL-17999MSL, 4nm
* Offshore: 3nm
* Domestic
* Above: >60000 MSL


**Special Use Airspace (特殊空域):**
| Type           | Rule                                       |
| -------------- | ------------------------------------------ |
| **MOA**        | VFR allowed; IFR may be cleared through    |
| **Restricted** | Need permission from controlling agency    |
| **Prohibited** | No entry, no exceptions                    |
| **Warning**    | Offshore (3 NM+), advisory only            |
| **Alert**      | High training area; use caution            |
| **NSA**        | Dashed magenta; check NOTAMs               |
| **TFR**        | Temporary Flight Restriction               |
| **ADIZ**       | Border defense zone; need DVFR/IFR plan    |
| **TRSA**       | Radar service around some Class D airports |
| **SFRA**       | Special rules, e.g., Washington DC         |

---

## ☁️ Weather

### Pressure Systems
| Type | Airflow | Motion | Weather |
|-------|----------|--------|----------|
| High | Outward, Downward, Clockwise | Stable | Clear, good visibility |
| Low | Inward, Upward, Counterclockwise | Unstable | Clouds, precipitation |

### Atmospheric Layers
| Layer | Approx Altitude | Temp Trend | Notes |
|--------|-----------------|-------------|--------|
| Troposphere | To ~46,000 ft | ↓ with altitude | All weather here |
| Stratosphere | To ~160,000 ft | ↑ with altitude | Ozone layer |
| Mesosphere | Higher | ↓ | Coldest layer |
| Thermosphere | > 280,000 ft | ↑ | Aurora region |

### AIRMET / SIGMET / Convective SIGMET

| Type | Duration | Conditions |
|-------|-----------|-------------|
| AIRMET Sierra | 6 hrs | IFR / vis < 3 SM / mountain obsc. |
| AIRMET Tango | 6 hrs | Mod. turbulence / ≥ 30 KT winds |
| AIRMET Zulu | 6 hrs | Moderate icing |
| SIGMET (WS) | 4 hrs | Severe icing / turb / dust / ash |
| Convective (WST) | 2 hrs | Thunderstorms, hail > ¾", winds > 50 KT |

### Fog Types
- **Radiation Fog** – Nighttime surface cooling
- **Advection Fog** – Warm moist air over cold surface
- **Upslope Fog** – Air pushed uphill
- **Steam Fog** – Cold air over warm water
- **Freezing / Ice Fog** – Supercooled water freezes on contact
- **Frontal / Precipitation Fog** – Warm front rain into cold dry air

### Icing
| Type | Description |
|-------|-------------|
| Clear | Large drops, smooth, most dangerous |
| Rime | Small drops, rough, milky |
| Mixed | Combo of both |

### Thunderstorms & Microbursts
- **Stages:** Cumulus → Mature → Dissipating
- **Hazards:** Turbulence, Wind Shear, Lightning, Hail, Icing
- **Microburst:** Downdraft > 6,000 ft/min

---

## 🧠 Human Factors

### Spatial Disorientation
- Vestibular System: Semicircular Canals and Otolith Organs
- Somatogyral Disorientation / Somatogravic Disorientation / Visual Disorientation

### Visual Illusions in Spatial Disorientation — *ICEFLAGS*
| Illusion | Description |
|-----------|-------------|
| Inversion | Level-off feels nose-down |
| Coriolis | Head movement during turn causes tumbling |
| Elevator | Updrafts mimic pitch changes |
| False Horizon | Misjudged horizon at night or over ocean |
| Leans | Missed small gradual turn |
| Autokinesis | Stationary light appears to move |
| Graveyard Spiral | Undetected turn, losing altitude |
| Somatogravic | Acceleration feels pitch-up |

### Hypoxia
| Type | Cause |
|-------|-------|
| Hypoxic | High altitude, low O₂ pressure |
| Hypemic | Blood can’t carry O₂ (e.g. CO poisoning) |
| Stagnant | Poor circulation (G-forces) |
| Histotoxic | Cells can’t use O₂ (drugs/alcohol) |

### Hazardous Attitudes
| Attitude | Example Thought | Antidote |
|-----------|------------------|-----------|
| Anti-Authority | “Rules don’t apply to me” | “Follow the rules—they’re usually right.” |
| Impulsivity | “Do it quick” | “Not so fast—think first.” |
| Invulnerability | “It won’t happen to me” | “It could happen to me.” |
| Macho | “Watch what I can do” | “Taking chances is foolish.” |
| Resignation | “What’s the use” | “I can make a difference.” |

### CRM — *Crew Resource Management*
- Team-based concept: **communication, leadership, situational awareness, decision-making**.
- Aim: Reduce human-error accidents by effective use of *all available resources (people, equipment, information).*
- Originated from NASA research in the 1970s; now standard for all multi-crew operations.

### SRM — *Single-Pilot Resource Management*
- Application of CRM for single-pilot ops.
- Focus: how one pilot manages **self, aircraft, automation, ATC, passengers, environment.**
- Core components:
  - **ADM (Aeronautical Decision Making)**
  - **Risk Management**
  - **Task / Workload Management**
  - **Automation & System Management**
  - **CFIT Awareness**
  - **Situational Awareness**
- Common framework: **5P model — Plan / Plane / Pilot / Passengers / Programming**
Refs:
- FAA: [Single-Pilot CRM Guide (PDF)](https://www.faa.gov/sites/faa.gov/files/2022-01/Single%20Pilot%20Crew%20Resource%20Management.pdf)

---

## ⚠️ Risk Management — 5×5 Risk Matrix

| **Probability ↓ / Severity →** | Negligible (1) | Minor (2) | Moderate (3) | Major (4) | Catastrophic (5) |
|--------------------------------|----------------|-----------|--------------|-----------|------------------|
| **Frequent (5)** | 5 | 10 | 15 | 20 | **25** |
| **Likely (4)** | 4 | 8 | 12 | 16 | 20 |
| **Occasional (3)** | 3 | 6 | 9 | 12 | 15 |
| **Remote (2)** | 2 | 4 | 6 | 8 | 10 |
| **Improbable (1)** | 1 | 2 | 3 | 4 | 5 |

Ref: [Aviation SMS Risk Matrix Explanation](https://aviationsafetyblog.asms-pro.com/blog/how-to-customize-risk-matrix-probability-and-severity-in-aviation-sms)

---

## ⚙️ Emergency Procedures — “ABCD(E)”

| Step | Action |
|-------|--------|
| **A** | Airspeed – Establish best glide |
| **B** | Best place to land |
| **C** | Checklist – Attempt restart / troubleshoot |
| **D** | Declare – MAYDAY 121.5, Squawk 7700 |
| **E** | Execute / Evacuate |

---

## Random

- Preventive maintenance per [Part 43 Appendix A(c)](https://www.ecfr.gov/current/title-14/part-43#p-Appendix-A-to-Part-43(c))
- Sectional + Chart Supplement expire every **56 days**
- Avoid **Runway Incursions** Brief taxiway diagram, read back, write down
