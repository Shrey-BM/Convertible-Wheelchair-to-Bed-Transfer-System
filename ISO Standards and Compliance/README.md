# ISO Standards and How the Chair Follows Them

**Convertible Wheelchair-to-Bed Transfer System**

The chair is a hand-operated wheelchair that is pushed by a caregiver. It also lies flat like a stretcher and moves the patient sideways onto a bed. The main standards for it are the **ISO 7176 series (Wheelchairs)**. Because it also lifts and moves a patient, a few general medical-device standards apply as well.

**Meaning of the status column:**

- **Met in design:** checked on the 3D model or by AI calculation.
- **Test on prototype:** can only be proven by testing the real chair.
- **Planned:** a choice or document that will be finalised with the prototype.

## 1. Wheelchair standards (ISO 7176 series)

| Standard | What it says | How the chair follows it | Status |
|---|---|---|---|
| **ISO 7176-1**<br>Static stability | Measures how far the loaded chair can be tilted forward, backward and sideways before it tips over. | Tipping angles were worked out with a 120 kg patient, as a chair and lying flat, at the lowest and highest seat height. The worst case is about 20° (flat, at full height, tipping backward). As a chair at its lowest height, it takes 39° forward, 31° backward and 27° sideways. A wheelchair ramp is only about 5°.<br><br>During a transfer the patient moves out past the wheels, so the chair is clamped to the bed frame first. | Met in design. Tilt test on prototype |
| **ISO 7176-3**<br>Brakes | Checks that the parking brakes keep the loaded chair from rolling on a slope. | All four 125 mm wheels have total-lock brakes: one pedal stops the wheel from rolling and from swivelling. Most wheelchairs brake only two wheels. The chair will be tested on a 7° ramp, the target commonly used for manual wheelchairs in Europe (EN 12183). | Test on prototype |
| **ISO 7176-5**<br>Size, mass and turning space | Sets how to measure and state the chair's outside size, its mass and the space it needs to turn around. | As a chair: 115 × 78 × 135 cm (length × width × height). Lying flat: about 181 cm long. Mass: about 79 kg. At 78 cm wide it passes through any door 80 cm or wider. The turning space will be measured on the prototype. | Met in design. Turning space on prototype |
| **ISO 7176-7**<br>Seat and wheel sizes | Sets how to measure seat height, depth and width, backrest angle and wheel sizes, for users up to 120 kg. | Seat 47 cm deep and 55 cm wide. Seat height 50 to 78 cm (hand crank). Backrest from upright to fully flat; the leg rest rises with it. Wheels: 125 mm casters. The chair is rated for 120 kg, the top of this standard's range. | Met in design |
| **ISO 7176-8**<br>Strength: static, impact and fatigue | Pushes and pulls hard on the armrests, footrest, handles and frame, knocks the chair, and runs it on a rolling drum (200,000 cycles) and a kerb-drop rig (6,666 drops) to show that nothing breaks. | Every load-carrying part was checked by AI hand calculation, and the main parts also by FEA, for 1.5 times a 120 kg patient. The lowest safety factor is 2.3 (plastic gear teeth, where a failure only stops the belt). The frames and lift arms are at 2.7 to 3.0 or more. Everyday stresses are well below the limits for repeated loading.<br><br>The impact, drum and kerb-drop tests need the real chair. | Static: met in design. Impact and fatigue: test on prototype |
| **ISO 7176-11**<br>Test dummies | Defines the dummies that stand in for a person during the tests above. | The prototype will be tested with dummy or sandbag loads up to the 120 kg maximum user mass, placed the way a patient's weight spreads over the back (49%), seat (39%) and legs (12%). | Test on prototype |
| **ISO 7176-15**<br>Manual, labels and information | Lists what the user manual and labels must tell the buyer: maximum user mass, sizes, warnings, use and care. | Label: maximum user 120 kg. The manual will cover:<br>• the beds it fits: mattress top 47 to 75 cm high, mattress 9.5 to 28 cm thick, bed frame edge 2 to 10.5 cm deep<br>• the safety steps in order: lock all four wheels, clamp to the bed, then transfer<br>• cleaning and regular checks. | Planned |
| **ISO 7176-16**<br>Fire resistance of padding | Checks that padding and upholstery do not catch fire easily from a match or a cigarette. | The parts with padding or covers are the PU belts, the armrest pads and the leg pad cover. Fire-retardant grades will be bought, with the supplier's test certificate. | Planned |
| **ISO 7176-22**<br>Set-up before testing | Says how to set the chair to a fixed reference position before any test, so results can be repeated. | Reference set-up for testing: seat at its lowest (50 cm), backrest upright, both boards home and pinned, armrests fitted. Any other setting used in a test will be written in the test report. | Planned |

## 2. Other standards for a patient-transfer device

| Standard | What it says | How the chair follows it | Status |
|---|---|---|---|
| **ISO 10535**<br>Hoists for moving people | Safety rules for devices that lift and move a patient: strength, stability, safe lowering and caregiver effort. | The chair is not a hoist, but it lifts and moves a patient, so this standard is used as a guide:<br>• The lift cannot drop: the screw is self-locking and holds wherever the crank stops.<br>• The seat goes down only when the crank is turned.<br>• The hardest crank turn feels like lifting about 12 kg.<br>• The patient is never lifted off the surface; the belt carries them across. | Used as a guide |
| **ISO 14971**<br>Risk management for medical devices | Find every hazard, judge how likely and how serious it is, reduce it, and check what risk is left. | Done as the design FMEA. Main examples:<br>• tipping during transfer: bed clamp<br>• backrest falling: gas spring lock, spring pin and stop blocks<br>• boards sliding out: transit-lock pins<br>• chair rolling: four total-lock wheels<br>• seat sinking: self-locking screw. | Met in design. Update after testing |
| **ISO 10993-1**<br>Safety of materials touching the skin | Materials in contact with the skin must not cause irritation or allergy. | Skin-contact parts: PU belt, PU armrest pads, leg pad cover and powder-coated handles. Medical- or food-grade materials will be chosen, backed by supplier data. All surfaces are smooth and can be wiped clean with hospital disinfectant. | Planned |
| **ISO 13485**<br>Quality system for medical devices | How a maker must control design, purchasing and production of medical devices. | Applies when the chair goes into production. For the prototype, the parts list has revision control, every part has a drawing, and test results will be recorded. | Later (production) |

## 3. Standards that do not apply

These parts of ISO 7176 are for electric wheelchairs. The chair has no motor, battery or electronics, so they do not apply:

- **ISO 7176-2** dynamic stability, **-4** battery range, **-6** speed, **-9** climate tests, **-10** obstacle climbing: all for electric wheelchairs.
- **ISO 7176-14** power and control systems, **-21** electromagnetic compatibility, **-25** batteries and chargers.

**ISO 7176-19** (wheelchairs used as seats in vehicles) also does not apply. The chair is not meant to carry a patient in a car or ambulance, and the manual will say so.

## 4. Tests planned on the prototype

- Tilt test with 120 kg of load, as a chair and lying flat (ISO 7176-1).
- Parking brakes on a 7° ramp, fully loaded (ISO 7176-3).
- Measuring the size, mass and turning space (ISO 7176-5 and -7).
- Static loads on the armrests, footrest, handles and backrest (ISO 7176-8).
- Repeated cycles of lifting, reclining and transferring, to check for wear and loosening.

> *ISO standards are paid documents. The one-line summaries above are taken from the standards' public scope descriptions. We will try to get the full ISO standard documents while building the model.*
