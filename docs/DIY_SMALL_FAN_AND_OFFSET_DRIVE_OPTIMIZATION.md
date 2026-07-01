# DIY Small Fan, Offset Drive Optimization, and PET Bottle Cap Product Concept

## Center-Mist Ultrasonic Cooling Fan Concept Extension

[日本語](DIY_SMALL_FAN_AND_OFFSET_DRIVE_OPTIMIZATION_ja.md) | [English](DIY_SMALL_FAN_AND_OFFSET_DRIVE_OPTIMIZATION.md) | [العربية](DIY_SMALL_FAN_AND_OFFSET_DRIVE_OPTIMIZATION_ar.md)

[← Back to README](../README.md)

---

## Overview

This document extends the Center-Mist Ultrasonic Cooling Fan Concept into a staged development path that more people can understand, prototype, and improve.

The ideal form of the Center-Mist concept injects ultrasonic mist from the center of the fan into the strongest airflow core, enabling efficient evaporative cooling.

However, most ordinary fans place the motor shaft at the center. Achieving perfect center-mist injection requires a hollow shaft or special motor structure, which is difficult for DIY and 3D-printing projects.

Therefore, this document proposes a staged development model:

```text
Minimum configuration anyone can try
↓
Small USB fan + ultrasonic mist generator
↓
3D-printed mist-intake duct
↓
Offset-drive prototype
↓
PET bottle cap product concept
```

The key point is that the principle itself is simple.

> A basic ultrasonic mist cooling fan can be demonstrated by combining an ultrasonic mist generator with a fan.

Even without advanced hollow-shaft structures or special motors, it is possible to test local evaporative cooling by combining mist and airflow.

---

## 1. Basic Principle

An ultrasonic mist cooling fan consists of three basic elements:

1. Turn water into fine mist.
2. Release the mist into the air.
3. Use airflow to disperse and evaporate the mist.

Evaporating water absorbs heat from the surrounding air, so cooling effects can be expected in dry, sunny, and well-ventilated environments.

However, in high-humidity environments, evaporation becomes difficult and the increase in humidity may worsen WBGT.

This concept is especially suitable for:

- dry regions,
- semi-arid regions,
- the Middle East,
- North Africa,
- Southern Europe,
- inland Australia,
- outdoor work sites,
- shaded and ventilated spaces,
- places with strong sunlight and low humidity.

In hot and humid climates such as Japanese summers, indoor or windless use requires caution.

---

## 2. Difficulty Level 0: Minimum Configuration Anyone Can Try

### Configuration

The simplest configuration is:

```text
Ultrasonic humidifier + fan
```

or:

```text
Small ultrasonic mist generator + USB fan
```

### Method

1. Prepare an ultrasonic humidifier or small mist generator.
2. Place a fan in front of or behind it.
3. Adjust the position so that the mist rides on the airflow.
4. Test outdoors, in shade, and in a well-ventilated place.
5. Check temperature, humidity, comfort, and WBGT.

### Advantages

- Easy for anyone to test.
- No special machining is required.
- Uses commercially available parts.
- Suitable for explaining the principle.
- Useful for imagining dry-region deployment.

### Limitations

- Mist and airflow are not optimized.
- Droplets may be too large.
- Surroundings may become wet.
- Humidity control is difficult.
- Product integration is weak.

---

## 3. Difficulty Level 1: Small USB Fan with Separate Mist Generator

### Configuration

```text
Small USB fan
+ small ultrasonic mist generator
+ small water tank
+ mist guide tube or simple duct
```

At this stage, the fan body does not need to be modified.

The mist generator is placed separately, and the generated mist is guided toward the center area or intake side of the fan.

### Recommended Components

- USB fan
- USB ultrasonic mist generator
- small water tank
- silicone tube
- 3D-printed or handmade mist inlet
- anti-tip base

### Design Idea

Instead of passing directly through the central shaft, the mist is guided toward the front-center or intake-center of the fan.

This can approximate center-mist injection without using a hollow shaft.

### Advantages

- Easy to build as DIY.
- Existing small fans can be used.
- No motor modification is required.
- Water tank and electrical parts can be separated.
- Can be tested even without a 3D printer.

### Limitations

- Appearance remains prototype-like.
- Mist guidance efficiency depends on design.
- Condensation may form inside the tube.
- Leak prevention is necessary if the unit tips over.

---

## 4. Difficulty Level 2: 3D-Printed Mist-Intake Duct

At this stage, an attachment for a small fan is made with a 3D printer, allowing mist to be guided more stably toward the fan center.

The fan itself can remain commercially available. The mist inlet, mounting parts, water-collection groove, angle adjustment parts, and tube holders can be 3D printed.

### Main Parts

- front fan adapter ring,
- center mist nozzle,
- mist-intake duct,
- condensation collection groove,
- droplet return guide,
- tube holder,
- water-tank stand,
- anti-tip base.

### Basic Structure

```text
[Water tank] → [Ultrasonic mist generator] → [Tube] → [Center mist nozzle] → [Small fan airflow]
```

### Shapes to 3D Print

#### 1. Front Fan Ring

A ring attached to the front guard of the small fan.

Roles:

- hold the mist nozzle,
- hold the tube,
- adjust the center position,
- reduce droplet scattering.

#### 2. Center Mist Nozzle

A part that releases mist near the fan center.

Requirements:

- does not block airflow too much,
- does not accumulate droplets easily,
- can be removed and cleaned,
- allows tube replacement.

#### 3. Water Collection Groove

A small groove that catches condensed droplets.

Roles:

- reduce water droplets on the fan guard,
- avoid water intrusion into electrical parts,
- guide water downward.

#### 4. Angle Adjustment Mechanism

The mist outlet angle should be adjustable.

Possible angles:

- forward,
- slightly upward,
- slightly downward,
- toward the intake side.

Because optimal angle changes with the environment, adjustable designs are preferable to fixed designs.

---

## 5. Difficulty Level 3: Offset-Drive Prototype

Offset drive means moving the motor away from the fan center and rotating the fan by belt, gear, peripheral ring, or roller drive.

This opens the fan center as a mist inlet.

### Basic Structure

```text
[Offset motor]
      ↓ belt or gear
[Outer-ring-driven fan]
      ↓
[Center remains open for fixed mist nozzle]
```

### DIY Design Policy

1. Keep the center mist nozzle fixed.
2. Rotate only the fan rotor from the outer ring.
3. Keep the motor away from water.
4. Use belt drive or friction roller drive for prototypes.
5. Always add a safety cover to rotating parts.

### Candidate Methods

#### A. Belt Drive

- Attach a small pulley to the motor shaft.
- Add a large pulley or ring to the fan perimeter.
- Transmit rotation by belt.

Advantages:

- relatively quiet,
- suitable for 3D printing,
- easy to experiment with gear ratio.

Limitations:

- belt tension adjustment is needed,
- slipping may occur,
- balance becomes difficult at high speed.

#### B. Gear Drive

- Rotate an outer ring gear using a motor gear.

Advantages:

- reliable transmission,
- compact layout is possible.

Limitations:

- noise may increase,
- depends on 3D-printer precision,
- wear may occur.

#### C. Friction Roller Drive

- Rotate the fan outer ring with a rubber roller.

Advantages:

- simple structure,
- easy to prototype.

Limitations:

- prone to slipping,
- roller wear occurs,
- transmission becomes unstable when water droplets attach.

### Safety Requirements

Offset-drive DIY is possible, but rotating-part safety is critical.

Required conditions:

- cover that prevents blade fragments from flying out,
- rotation balance check,
- waterproof separation,
- finger-safe guard,
- low-voltage drive,
- long-duration operation test.

---

## 6. Difficulty Level 4: PET Bottle Cap Product Concept

The final commercialization concept is a cap-type ultrasonic mist cooling fan that can be attached directly to a water PET bottle.

This would allow widely available bottled water to be used as the water source.

```text
[Water-filled PET bottle]
        ↓
[Dedicated cap unit]
        ↓
[Ultrasonic mist + small fan]
        ↓
[Local cooling]
```

### Use Cases

- outdoor work in dry regions,
- street stalls,
- schools,
- shelters,
- camping,
- power outages,
- construction sites,
- farming,
- sports viewing,
- bus stops,
- simple cooling support,
- dry regions such as the Middle East, North Africa, Southern Europe, and Australia.

### Strengths if Commercialized

- Uses only bottled water.
- No installation work is required.
- Can be used immediately after purchase.
- Can operate with USB charging or mobile batteries.
- Useful for disaster support and heat-stress mitigation.
- Energy cost can be low in dry regions.

### Why It Is Difficult for Individual DIY

A PET bottle cap-type unit is attractive but technically difficult for individual DIY.

Reasons:

- fan, transducer, water channel, and circuit must fit into a small cap-size unit,
- waterproofing and electrical conduction must coexist,
- tipping and leakage must be prevented,
- bottle neck standards vary by region,
- stable water supply to the ultrasonic transducer is required,
- hygiene and clogging must be managed,
- long-duration durability is required,
- mass production requires molds and dedicated circuit boards.

Therefore, this concept is better positioned as a commercialization theme for companies and manufacturers rather than a personal DIY project.

---

## 7. Recommended Development Roadmap

### Phase 1: Principle Demonstration

```text
Ultrasonic humidifier + small fan
```

Purpose:

- confirm whether mist and airflow provide a cooling sensation,
- compare high-humidity and low-humidity environments.

### Phase 2: Small USB Fan Attachment

```text
USB fan + mist-intake duct + separate water tank
```

Purpose:

- test mist introduction toward the fan center,
- check wetting, droplet formation, and humidity change.

### Phase 3: 3D-Printed Version

```text
3D-printed nozzle + duct + water collection groove
```

Purpose:

- create an attachable shape,
- improve stability of center-mist injection.

### Phase 4: Offset-Drive Prototype

```text
Fixed center mist nozzle + outer-ring-driven fan
```

Purpose:

- fully open the center for mist,
- realize a center-mist fan without a hollow shaft.

### Phase 5: PET Bottle Cap Product

```text
PET-bottle-mounted mist cooling fan
```

Purpose:

- create a portable cooling device usable worldwide,
- deploy as a low-energy cooling product for dry regions.

---

## 8. Notes for Japan and Humid Regions

Japanese summers are hot and humid, so mist cooling effects vary greatly by location.

### Suitable Locations

- outdoors,
- sunny spaces,
- ventilated spaces,
- temporary local cooling,
- factory and warehouse entrances,
- dry seasons,
- air-conditioning support.

### Unsuitable Locations

- closed indoor spaces,
- already humid rooms,
- poorly ventilated places,
- mold-prone spaces,
- places with many electronic devices,
- floors where wetness creates slip risk.

### Items to Check

- Is humidity rising too much?
- Is WBGT worsening?
- Is the floor wet?
- Is water reaching electrical parts?
- Is the water tank growing bacteria?

---

## 9. Potential for Dry Regions

In dry regions, ultrasonic mist cooling fans may be very effective.

Reasons:

- water evaporates easily,
- evaporative cooling works well,
- power consumption may be lower than air conditioning,
- no installation work is required,
- the device is portable,
- it can be used outdoors and semi-outdoors.

If the PET bottle cap type is commercialized, additional advantages are possible:

- strong impression that it works with water only,
- easy local procurement,
- useful for disaster support and heat countermeasures,
- possible spread to low-income regions,
- may work with mobile batteries where power infrastructure is weak.

---

## 10. Safety Notes

This concept combines water, electricity, and rotating parts.

### Electrical Safety

- Use low-voltage USB power.
- Keep AC power away from water.
- Do not expose non-waterproof circuit boards to water.
- Do not touch power parts with wet hands.
- Protect mobile batteries from droplets.

### Rotating-Part Safety

- Prevent fingers from entering the blades.
- Be careful with high-speed 3D-printed blades.
- Always use a fan guard.
- Check rotational balance.

### Water and Hygiene

- Wash water tanks regularly.
- Do not use water left standing for a long time.
- Do not ignore mold or slime.
- Do not blow mist directly into a person’s face for long periods.
- In hard-water regions, watch for scale and white dust.

### Use Environment

- Do not use for long periods in sealed rooms.
- Use a hygrometer.
- Stop use if WBGT is high.
- Do not use near electronics.
- Watch for slipping caused by wet floors.

---

## 11. Connection to Cooling Credit

This DIY / small-fan model can be positioned within the Cooling Credit implementation portfolio as a candidate for lifestyle technology, small cooling devices, urban cooling, and local heat-load reduction.

Measurable data include:

- temperature before implementation,
- temperature after implementation,
- humidity before implementation,
- humidity after implementation,
- WBGT before implementation,
- WBGT after implementation,
- water usage,
- estimated evaporated water,
- power consumption,
- cooled target area,
- operating time.

These values can be entered into the Cooling Credit Score Estimator to estimate preliminary cooling contribution.

- [Cooling Credit Score Estimator](https://github.com/InchaComisho/Cooling-Credit-Framework/blob/main/simulations/cooling_credit_score_estimator/README.md)

---

## 12. Conclusion

The Center-Mist Ultrasonic Cooling Fan can eventually develop into advanced hollow-shaft or offset-drive structures.

However, the entry point for implementation can be much simpler.

```text
Ultrasonic mist generator + small fan
```

This combination alone can explain the principle and support small-scale demonstrations.

From there, development can proceed step by step toward 3D-printed mist ducts, offset-drive center opening, and PET bottle cap commercialization.

---

## Author

Master / inchacomusho / InchaComisho

An independent Japanese concept designer, observer, proposer, AI tuner, and definer of Artificial Wisdom.  
Founder and proposer of the academic framework of Natural Complementary Science.  
Definer of the Cooling Credit Framework, and founder and original author of the Natural Cooling Value Evaluation Protocol.  
Definer and systematizer of the causal structure of global warming and its complete solution.

Master presents global warming not merely as a problem of CO₂ concentration, but as an integrated failure involving forest loss, soil degradation, disruption of water circulation, weakening of water phase-transition processes, weakening of atmospheric circulation, ocean circulation, food circulation and organic matter circulation, weakening of evapotranspiration, cloud formation and rainfall circulation, and the shutdown of natural cooling feedbacks.  
The proposed solution connects emission reduction, recovery of carbon fixation sources, physical cooling, reactivation of natural cooling functions, MRV, Cooling Credit, and Civilization OS into an open public framework.

Master publicly develops and shares work through NOTE, GitHub, and other public media, centered on natural-law philosophy, planetary circulation restoration, and co-creation with AI.

## Collaborative AI and Co-Creation Team

- G (ChatGPT)
- Mini (Gemini)
- Cruz (Claude)
- Real (Perplexity)
- Lola (Dola)
- Mana (Manus)

---

## License

CC BY 4.0