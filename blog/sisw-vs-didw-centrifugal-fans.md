---
title: "SISW vs DIDW Centrifugal Fans: What Is the Difference?"
description: "SISW vs DIDW centrifugal fans explained with real 230 VAC EC data: SF146C-E092B3-01 (705 Pa) vs DG200D-E092E3-01 (500 Pa) — inlets, static pressure and selection."
---

# SISW vs DIDW Centrifugal Fans: What Is the Difference?

In centrifugal fan datasheets and RFQs, two acronyms appear constantly:
**SISW** and **DIDW**. Buyers who confuse them often compare fans that were
never intended for the same duty. This guide defines both terms, then walks
through a real case comparison using two SUNXFAN<sup>®</sup> 230 VAC EC fans with almost
identical airflow — but a 205 Pa gap in static pressure that comes almost
entirely from the inlet configuration.

## Quick Answer: SISW vs DIDW in One Paragraph

**SISW (single inlet, single width)** centrifugal fans take air in through
**one side** and discharge at the top or side — compact, ideal for embedded
and space-limited cooling. **DIDW (double inlet, double width)** fans draw air
from **both sides** of the motor and discharge forward — with twice the inlet
area, the same diameter wheel moves more air against higher static pressure,
which is why DIDW dominates AHU and ducted HVAC duty.

## What SISW and DIDW Actually Mean

- **SISW — Single Inlet, Single Width.** The centrifugal fan has **one side
  inlet** and the outlet is on the **top side** of the scroll housing. Air
  enters through a single throat, and the impeller is as wide as that single
  inlet needs.
- **DIDW — Double Inlet, Double Width.** The centrifugal fan has **inlets on
  either side** (both sides of the motor) and the **outlets are on the front
  side** of the scroll. The impeller is effectively two wheels back to back —
  double the width, twice the inlet area.

Everything else — backward-curved blade geometry, EC motor technology, scroll
function — can be identical. The inlet count and wheel width change how much
air the fan can move and how much static pressure it can build.

## Case Study: Two 230 VAC EC Fans, Nearly Same Airflow

Both models below are EC external rotor motor fans running directly on
230 V AC mains — same voltage class, similar airflow. The difference is the
inlet architecture.

| Specification | SF146C-E092B3-01 (DIDW) | DG200D-E092E3-01 (SISW) |
| --- | --- | --- |
| Inlet / outlet | Double inlet / front discharge | Single inlet / top discharge |
| Motor type | EC, 230 V AC | EC, 230 V AC |
| Airflow (0 Pa) | 1250 m³/h | 1300 m³/h |
| Max static pressure | **705 Pa** | 500 Pa |
| Power input | 220 W | 190 W |
| Speed | 1650 r/min | 1200 r/min |
| Noise | 65±2 dB(A) | 64 dB(A) |
| Protection | IP44 | **IP54** |
| Impeller | Galvanised sheet steel | PP+GF (galvanised optional) |
| Bearings | NSK ball bearings | NSK ball bearings |
| Speed control | 0-10V/PWM, 0-5V, 0-6.5V, 4-speed | 0-10V/PWM, 0-6.5V, 4-speed |
| Temperature range | -25 °C ~ +60 °C | -25 °C ~ +50 °C |

View the full datasheets:
[SF146C-E092B3-01](/en/products/sf146c-e092b3-01/) ·
[DG200D-E092E3-01](/en/products/dg200d-e092e3-01/)

## Why the DIDW Fan Reaches 705 Pa

The double-inlet **SF146C-E092B3-01** effectively combines two single-inlet
wheels on one shaft. With twice the inlet area, air enters at a lower face
velocity, so the fan can sustain a much deeper vacuum in the scroll before
performance collapses. The result: at duct resistance above roughly
500 Pa — filters loaded with dust, dense coil stacks, long silencer runs —
the DIDW fan still delivers stable airflow while a comparable single-inlet
unit would fall off its curve.

That is why double-inlet double-width fans dominate **air handling units
(AHU), fan coil units, FFU cleanroom modules and data center CRAC systems**,
where the scroll's front discharge aligns naturally with rectangular duct
connections. If you compare the two intake layouts in more detail, our
[dual-inlet vs single-inlet guide](/en/blog/dual-inlet-vs-single-inlet-centrifugal-blowers/)
covers the trade-offs.

## Why the SISW Fan Is the Compact Workhorse

The single-inlet **DG200D-E092E3-01** gives up 205 Pa of maximum static
pressure but wins on integration:

- **Narrower frame depth** — air enters one side only, so the fan fits
  equipment where there is no space for a second inlet throat.
- **Top-side discharge** — easy vertical duct routing in compact cabinets.
- **IP54 protection and a PP+GF composite impeller** — glass-fibre reinforced
  polypropylene resists corrosion in humid, coastal or outdoor-air
  applications where galvanised steel would eventually degrade.
- **Lower speed (1200 r/min vs 1650 r/min)** for the same airflow class,
  which eases bearing load and broadband noise management (64 dB(A)).

These traits make SISW fans the default in **fresh-air ventilation units,
telecom and outdoor cabinets, marine HVAC, EV charging cabinets and medical
equipment**, where the fan is embedded inside the machine rather than
connected to a duct network.

## Selection Rules You Can Apply in 30 Seconds

1. **System resistance above ~500 Pa** (filters, coils, long ducts) → choose
   a DIDW fan like the SF146C family.
2. **Fan embedded inside equipment, single-sided space** → choose a SISW fan
   like the DG200 family.
3. **Corrosive or humid airstream** → SISW with PP+GF impeller (IP54).
4. **Rectangular AHU duct connection** → DIDW front discharge.
5. Both need **0-10V/PWM speed control on 230 V AC** → both models qualify.

## Key Takeaways

SISW and DIDW describe the **inlet and discharge geometry** of a centrifugal
fan — not its motor or efficiency class. For the same airflow and voltage,
the double-inlet design buys you static pressure headroom (705 Pa vs 500 Pa
in our case), while the single-inlet design buys you compactness, corrosion
resistance and easier top-outlet routing. Decide by measuring your system's
resistance and the space around the fan — not by the acronym alone.

Explore the full families: the
[SF146C series](/en/products/series/sf146c/) (double inlet) and the
[DG200 series](/en/products/series/dg200/) (single inlet), both available
across AC, DC and EC motor types. For the fundamentals behind inlet
configurations, start with our
[axial vs centrifugal comparison](/en/blog/axial-fan-vs-centrifugal-fan-difference/).
