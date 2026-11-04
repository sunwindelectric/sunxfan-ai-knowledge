---
title: "SFP (Specific Fan Power): How to Calculate It and What Counts as Good"
description: "How to calculate specific fan power from airflow and fan input power, which SFP values count as efficient for an AHU, where the losses hide, and how EC control brings the annual figure down."
layout: kb
---

# SFP (Specific Fan Power): How to Calculate It and What Counts as Good

Two AHUs can deliver the same airflow with the same external static pressure and still differ by a factor of two in electricity use. Specific fan power is the number that exposes that difference, and it is the metric European ventilation specifications use to judge a fan package.

## What specific fan power measures

SFP compares the electrical power the fan absorbs with the air volume it moves:

**SFP = fan input power (W) ÷ airflow (l/s)**

The unit is W/(l/s), numerically the same as kW/(m³/s). A value of 1.0 W/(l/s) means one watt of electricity for every litre per second of air moved. Because the denominator is volume flow, not mass flow, SFP can be compared across a project without converting to standard conditions.

The formula uses **electrical input power at the fan terminals**, not shaft power and not air power. Whatever the motor, the drive and the control electronics consume counts against the result. That is deliberate: it reflects what the energy meter records.

Worked example: a plug fan moving 1,000 m³/h (278 l/s) and drawing 500 W at the duty point has an SFP of 500 / 278 = **1.8 W/(l/s)**. The same fan at 700 m³/h drawing 210 W reaches 210 / 194 = **1.08 W/(l/s)** — the airflow fell 30 % and the power fell 58 %, which is the cube law at work.

## What counts as a good SFP

There is no universal limit, because a filter-loaded cleanroom AHU cannot match a free-cooling unit. Project specifications and national energy codes set their own caps. Practical benchmarks used in tender documents:

| SFP (W/(l/s)) | Reading |
|---|---|
| ≤ 1.0 | Excellent — well-matched EC plug fan, low duct resistance |
| 1.0 – 1.5 | Good practice for a conventional AHU with filters and coils |
| 1.5 – 2.0 | Acceptable only where the duty is genuinely pressure-heavy |
| > 2.0 | Poor — check oversizing, damper throttling and duct losses |

The number alone is not a verdict. An AHU that must overcome 800 Pa of filters and coils will sit higher than one handling 200 Pa, and both can be correctly selected. Compare SFP between options that serve the same system resistance.

## Where the losses actually come from

SFP bundles three losses that are often discussed separately:

1. **Impeller and volute losses.** A backward-curved impeller holds efficiency over a wider flow range than a forward-curved drum; a double-inlet wheel spreads the same airflow across two inlets at lower tip speed.
2. **Motor and drive losses.** An AC motor at part load slips and its efficiency falls away; an EC external-rotor motor keeps a flatter efficiency curve and removes the separate VFD losses.
3. **Throttling.** A damper or a balancing valve turns pressure into heat. If the fan is oversized and throttled to reach design airflow, the absorbed power stays near full speed and SFP climbs.

System resistance belongs to the ductwork, not the fan, but it decides the operating point. A filter that loads up over its service life pushes the fan up its curve; selecting at the clean filter point guarantees a worse SFP for most of the year.

## Reducing SFP on a real project

**Select at the dirty-filter point.** Size for the resistance the system will have late in the filter cycle, not on day one. The fan then runs at a better efficiency point for the majority of operating hours.

**Match the impeller to the duty.** Plot the duty point on the curve: an oversized impeller running at 60 % speed wastes less than a throttled one, but a correctly sized impeller running near its best-efficiency point wastes least.

**Use EC control with a pressure setpoint.** Demand-controlled ventilation with a duct-pressure sensor lets speed follow the actual load. Because power follows roughly the cube of speed, a 20 % speed reduction cuts absorbed power by around half.

**Check the accessory cost.** Inlet guards, filters, silencers and long duct runs all add resistance. An accessory that raises system pressure by 50 Pa can cost more energy over a year than the fan it protects.

**Measure, do not assume.** Commissioning should record the actual airflow and input power at the installed duty point. A calculated SFP from a datasheet is a promise; a measured one is evidence.

## How SFP interacts with fan type

Axial fans post low SFP in free-blowing duties such as dry coolers, where system resistance stays under roughly 150 Pa. The moment filters or long ducts are added, the axial fan's low-pressure characteristic forces a larger diameter or higher speed, and SFP degrades quickly.

Centrifugal fans — backward-curved, single-inlet and double-inlet — hold their efficiency at higher pressures, which is why AHU and cleanroom duties sit in their range. The choice between them is usually made on envelope and noise rather than on SFP: a double-inlet wheel delivers a given airflow with a smaller diameter and lower tip speed, while a backward-curved impeller keeps efficiency stable as filters load.

Whichever type is chosen, the SFP figure quoted in a tender should be stated with the airflow, the external static pressure and the filter condition it was measured at. Without those three numbers it cannot be compared.

---

Source: [https://en.sunxfan.com/en/guides/sfp-specific-fan-power/](https://en.sunxfan.com/en/guides/sfp-specific-fan-power/)

_Last updated: 2026-11-04_
