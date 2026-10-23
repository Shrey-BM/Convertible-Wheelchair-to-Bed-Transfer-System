# Materials and Stress Analysis

**Convertible Wheelchair-to-Bed Transfer System**

## 1. Materials used

| Parts | Material | Why this material |
|---|---|---|
| **Base frame, scissor arms, lift top frame** | Mild steel tubes (IS 4923, grade YSt 310) | These carry the heaviest loads in the chair. Steel is stiff, cheap and easy to weld. Its weight sits low down, which makes the chair harder to tip. |
| **Seat, backrest and leg rest frames, side plates** | Aluminium (6061-T6) | These parts move every time the chair reclines. Aluminium weighs about a third as much as steel, so the gas spring and the caregiver do less work. The parts are bolted, so no aluminium welding is needed. |
| **Sliding boards** | Aluminium tubes under a thin aluminium sheet, with slippery PTFE tape on top | The boards must be thin, light and stiff. The slippery top lets the belt slide over the board easily. |
| **Pins, lead screw, roller axles** | EN8 steel | Stronger than mild steel and easy to machine on a lathe. Can be hardened later if the pins wear. |
| **Recline linkage** | Mild steel plate | The pins press hard on their holes. Steel holes keep their shape better than aluminium ones. |
| **Bed clamp** | Mild steel, powder coated; steel screws | The clamp has the highest local loads among the safety parts. Steel threads survive being tightened again and again. |
| **Lock posts, edge bars, stop blocks** | Aluminium, machined | The loads here are small, and these parts bolt onto aluminium frames. |
| **Locking pins (plungers)** | Stainless steel (SS304) or hardened steel | Bought as standard parts; stainless steel does not rust. |
| **Handles and armrests** | Mild steel tube, powder coated | Stiff, cheap, easy to bend and comfortable to hold. |
| **Rack and pinion** | Acetal (POM) plastic | The forces are small. Acetal is quiet, needs no grease near the patient, and does not rust. |
| **Belts** | Polyester covered with PU | The polyester barely stretches, so the belt keeps its tension. The PU surface is smooth and easy to wipe clean. |

## 2. Strength of the materials

The table gives the strength values used in every safety factor in this document. We used the **guaranteed minimum** values from the material standards, not the typical values. Real material is usually a little stronger, so the real safety factors are slightly higher than the ones shown.

| Material | Yield strength (bends permanently) | Tensile strength (breaks) | Shear yield strength (pins) | Stiffness E | Density |
|---|---|---|---|---|---|
| **Mild steel IS 4923 YSt 310** | 310 MPa | 450 MPa | 179 MPa | 200 GPa | 7.85 g/cm³ |
| **Aluminium 6061-T6** | 240 MPa (typical 276) | 260 MPa (typical 310) | 138 MPa | 69 GPa | 2.70 g/cm³ |
| **EN8 steel (080M40), normalised** | 280 MPa | 550 MPa | 162 MPa | 205 GPa | 7.85 g/cm³ |
| **Stainless steel SS304** | 205 MPa | 515 MPa | 118 MPa | 193 GPa | 8.0 g/cm³ |
| **Acetal (POM)** | about 65 MPa | about 65 MPa | - | 2.8 GPa | 1.41 g/cm³ |

- **Safety factor = material strength ÷ stress in the part.**
- For parts that are bent or stretched (tubes, plates, boards), the yield strength is used.
- For pins that could be cut through, the shear yield strength is used. It is about 0.58 times the yield strength.
- For the plastic gear teeth, a lower working limit of 35 MPa is used, because plastic weakens under repeated loading.
- For the long, thin tie-rod, the buckling load is used instead of the material strength.

<img width="1267" height="628" alt="material_strength" src="https://github.com/user-attachments/assets/f8a28afc-1fc9-4263-9aba-aebf0215a74c" />

## 3. Dimensions of the main load-carrying parts

**I** shows how stiff the cross-section is in bending, and **Z** shows how much bending it can take (bending stress = bending moment ÷ Z). Larger is stronger.

| Part | Material | Cross-section (mm) | Length (mm) | Area (mm²) | I (mm⁴) | Z (mm³) |
|---|---|---|---|---|---|---|
| **Scissor arms (×4)** | Mild steel | Tube 50 × 25 × 2.6 wall | 550 between pins | 363 | 112,056 | 4,482 |
| **Base frame** | Mild steel | Tube 40 × 40 × 2.6 wall | 1040 × 700 frame | 389 | 91,115 | 4,556 |
| **Lift top frame, seat side rails** | Mild steel / aluminium | Tube 40 × 20 × 2 wall | 630 / 517 | 224 | 44,459 | 2,223 |
| **Backrest side tubes (×2)** | Aluminium | Tube 40 × 20 × 3 wall | 818 | 324 | 60,812 | 3,041 |
| **Scissor cross shafts (×4)** | Mild steel | Round tube Ø25 × 3 wall | 424 | 207 | 12,778 | 1,022 |
| **Lead screw** | EN8 steel | Tr20 × 4 thread, core Ø15.5 | 780 | 189 | - | - |
| **Tie-rod** | Mild steel | Flat bar 25 × 8 | 482 between pins | 200 | 1,067 (thin way) | 267 |
| **Sliding board (back)** | Aluminium | 5 tubes 25 × 16.5 × 1.5 + 1.3 sheet, 17.8 deep | 760 | 1,207 | 48,180 | 3,738 |
| **Bed clamp arm (×2)** | Mild steel | Tube 25 × 24 × 2 wall | 90 | 180 | 14,800 | 1,233 |
| **Pins** | EN8 / SS304 | Centre pin Ø20, pivot pins Ø12, locking pins Ø8 | - | 314 / 113 / 50 | - | - |

## 4. Loads the chair can handle

### The patient

The chair is designed for a patient of up to **120 kg**. All checks use 1.5 times this load (about 180 kg). For the seat, where a patient may sit down hard, the load is increased by a further 1.3 times.

### How a lying patient's weight is shared

| Part of the chair | Body parts resting on it | Share of body weight | For a 120 kg patient |
|---|---|---|---|
| **Backrest** | Head, chest, arms and stomach | 49% | about 59 kg |
| **Seat** | Hips and thighs | 39% | about 46 kg |
| **Leg rest** | Lower legs and feet | 12% | about 15 kg |

### The chair itself and people leaning on it

The chair weighs about **89 kg**. The checks also include someone leaning on the head end of the flat chair with about 25 kg of force, and the patient leaning back hard against the backrest when sitting upright. Each part is checked in its **worst position**, for example the lift at its lowest height or the backrest fully flat. If a part is safe there, it is safe everywhere else.

## 5. Strength checks

### Main parts (FEA)

| Part | Worst case checked | Highest stress (FEA) | Material strength | Safety factor |
|---|---|---|---|---|
| **Scissor arms** | Lift at its lowest height, chair flat | 102 MPa (next to the centre pin hole) | 310 MPa | 3.0 |
| **Backrest side tubes** | Chair flat, someone leaning on the head end | 89 MPa at the hinge | 240 MPa | 2.7 |
| **Backrest sliding board** | Upper body on the board plus 250 N in the middle | 35.4 MPa | 240 MPa | 6.8 |
| **Bed clamp arm** | Holding the chair at the worst moment of a transfer | 34.5 MPa | 310 MPa | 9.0 |
| **Tie-rod (leg rest link)** | Pushed from both ends (buckling) | Buckles at 9.06 kN; carries 831 N | - | 10.9 |

| Deflection | FEA | Hand calculation |
|---|---|---|
| **Backrest side tube, bend at 500 mm from the hinge** | 5.42 mm | 5.38 mm |
| **Backrest sliding board, sag in the middle** | 2.27 mm | 2.23 mm |

### Other parts (hand calculation)

The smaller parts were checked by hand calculation using AI.

| Part | What could go wrong | Stress or load | Strength used | Safety factor |
|---|---|---|---|---|
| **Scissor centre pin** | Cut through | 18.3 MPa | 162 MPa (shear) | 8.8 |
| **Holes at the arm ends** | Pushed out of shape by the shafts | 44.0 MPa | 310 MPa | 7.1 |
| **Lead screw** | Snaps under the pull of the lift | 60.5 MPa | 280 MPa | 4.6 |
| **Backrest pivot pin** | Cut through | 20.2 MPa | 162 MPa (shear) | 8.0 |
| **Stop blocks (flat position)** | Crushed | 9.8 MPa | 240 MPa | 25 |
| **Backrest locking pin** | Cut through if the gas spring fails while the patient leans back hard | 36.9 MPa | 118 MPa (shear) | 3.2 |
| **Seat board** | Bends when the patient sits down hard | 50.8 MPa | 240 MPa | 4.7 |
| **Rack and pinion teeth** | A plastic tooth breaks (the belt stops; the patient stays put) | 15.3 MPa | 35 MPa | 2.3 |
| **Board lock pin** | Cut through by a knock while moving | 11.7 MPa | 118 MPa (shear) | 10.1 |
| **Bed clamp pivot pin** | Bends during a transfer | 54.9 MPa | 310 MPa | 5.6 |
| **Clamp mounting bolts (M6)** | Pull out | 719 N each | 12,000 N | 16.7 |

## 6. Effort for the caregiver

| Task | Force needed | Feels like lifting |
|---|---|---|
| **Turning the crank, lowest height** (120 kg patient) | 115 N | 12 kg |
| **Turning the crank at 55 cm** | 79 N | 8 kg |
| **Turning the crank at 65 cm** | 46 N | 5 kg |
| **Reclining the backrest** (empty or with a 120 kg patient) | at most 76 N | 8 kg |
| **Sliding a 70 kg patient onto the bed** | 80 N | 8 kg |
| **Sliding a 120 kg patient onto the bed** | 137 N | 14 kg |
| **Moving a seated patient onto a commode** | 114 N | 12 kg |

The lift cannot sink by itself: the screw thread is so shallow (4.0°) that friction (equal to 7.1°) holds it in place.

## 7. Stability and anchoring to the bed

| Position (120 kg patient on board) | Forward | Backward | Sideways |
|---|---|---|---|
| **Chair, lowest height (50 cm)** | 39° | 31° | 27° |
| **Chair, highest height (78 cm)** | 31° | 23° | 20° |
| **Flat, highest height (78 cm)** | 41° | 20° | 23° |

The table shows how far the chair could be tilted before it tips. Even in the worst case it is about 20°; a wheelchair ramp slopes only about 5°.

During a transfer, the patient is carried out over the bed, past the chair's own wheels. At the worst moment, the patient's weight tries to tip the chair with 294 N·m, while the chair's own weight resists with only 253 N·m. Each clamp needs to hold about 436 N (44 kg); a clamp screw tightened by hand gives about 3.3 kN, about 7.6 times more.

## 8. Assumptions and limits

- The chair is rated for a 120 kg patient. Heavier patients are outside the rating.
- Body weight sharing is based on standard data for a 1.75 m adult. Taller or shorter patients change the loads slightly, and the safety factors cover this.
- Material strengths are the guaranteed minimum values. Friction values are typical values for clean, dry parts and will be measured on the prototype.
- The FEA studies are linear and static: they assume the material stays below its yield strength (which the results confirm) and the load is applied slowly. Pins are modelled as rigid supports, which slightly over-estimates the stress right at the holes.
- Each FEA study models one part with simplified supports, not the whole chair at once. The supports were chosen to reproduce the worst load each part sees.
- Long-term wear from repeated use was not calculated in detail, but the everyday stresses are well below the limits for repeated loading.
- The chair weighs about 89 kg, above the 70 kg target. The parts with large safety factors show where weight can be removed in future versions of the chair.

> *AI was used in some places (to find angles, cross-check stress calculations, etc.).*
