---
title: "CAV vs VAV Fan Systems: Which Airflow Strategy Should You Specify?"
description: "Constant air volume (CAV) wins on stability, compliance and low maintenance; variable air volume (VAV) wins on demand-matched airflow and part-load energy. A field-level comparison of both strategies — including the series-stacking trap that unbalances CAV and VAV terminals, and how EC fans with central static-pressure control let both coexist."
layout: kb
---

# CAV vs VAV Fan Systems: Which Airflow Strategy Should You Specify?

CAV versus VAV is one of the most argued questions in ventilation design, and most of the argument comes from comparing the two systems on the wrong terms. Constant air volume is not an outdated version of variable air volume. One is built to guarantee a fixed air quantity; the other is built to track a moving demand. The engineering question is narrower: does this zone have a hard constant-airflow requirement, does occupancy or pollutant load swing widely, and can the controls actually aggregate terminal demand back to the fan?

## The One Difference That Drives Everything

A **CAV (constant air volume)** system fixes the airflow delivered to each room. When airflow changes elsewhere in the duct network and pressure shifts, the CAV damper repositions itself to bring the target airflow back. The system does not care how many people are in the room; it guarantees how many cubic metres per hour go in.

A **VAV (variable air volume)** system follows demand. CO₂ and TVOC sensors feed the terminal controller, which opens or closes the damper: poorer air quality, more airflow; acceptable air quality, less. The system delivers what the space needs at that moment.

Every cost, energy and maintenance conclusion below follows from that single design intent.

## Constant Air Volume: Strengths and Costs

### Where CAV earns its place

- **Simple, stable control.** No air-quality sensor in the loop means no sensor drift to chase. Duct pressure disturbances are absorbed at the terminal, so the system holds its setpoint for years once commissioned.
- **Low first cost and easy maintenance.** No CO₂/TVOC transmitters or intelligent controllers to buy, a single fixed-airflow setpoint to commission, and no periodic probe calibration afterwards.
- **Compliance without argument.** Where a standard mandates a constant ventilation rate, or where online air-quality monitoring is impractical — production halls, chemical laboratories, cleanrooms — a fixed airflow satisfies the clause directly, without the compliance risk of demand-based modulation.

### Where CAV costs you

- **Poor part-load efficiency.** A half-empty room still receives full design airflow. In winter that is heat carried out of the building; in summer it is extra cooling load on the coil.
- **No adaptability.** When a space changes function — an open office converted into a meeting room — the fixed airflow no longer matches the new occupancy and the damper has to be re-set by hand.
- **Instability when stacked with VAV.** A CAV damper needs a certain pre-pressure and minimum airflow to regulate. Put it downstream of a VAV box and, when that box closes, the pre-pressure collapses and the branch loses its setpoint.

## Variable Air Volume: Strengths and Costs

### Where VAV earns its place

- **Real energy savings.** Demand-based ventilation avoids over-supply, and the savings grow with occupancy swings and operating hours — which is why VAV is the default in green-building ratings.
- **Adaptable to mixed occupancy.** Open offices, meeting rooms and retail floors change load hour by hour; a VAV terminal tracks that, and it can take signals from third-party sensors and a BMS.
- **System-level integration.** With central static-pressure control, terminal demand is summed and passed to the fan, so the fan slows when the building does — extending the savings beyond the terminal.

### Where VAV costs you

- **Higher first cost and harder commissioning.** Sensors, controllers and actuators all cost money, and commissioning has to map sensor thresholds, damper position and airflow, then prove the link to the central static-pressure loop.
- **Dependence on sensor health.** Probe accuracy determines control quality. Without routine cleaning and calibration, readings drift, airflow control degrades and indoor air quality follows it down.
- **A minimum-airflow floor.** To keep the sensor sampling valid, terminals cannot close fully, so low-demand periods still draw baseline energy.

## Side-by-Side Comparison

| Dimension | CAV | VAV |
| --- | --- | --- |
| Control target | Fixed supply airflow | Demand-matched airflow |
| Terminal hardware | Constant-volume damper, optional constant-airflow fan | Sensor + controller + VAV damper |
| First cost | Low | High |
| Commissioning | Low — one fixed setpoint | High — calibration plus system-level proof |
| Part-load energy | Poor | Good |
| Maintenance | Low, no probe calibration | Higher, sensors need cleaning and calibration |
| Best-fit spaces | Production halls, chemical labs, cleanrooms | Offices, meeting rooms, retail, hotels |
| Main risk | Balanced branch lost when stacked with VAV | Sensor drift and minimum-airflow limits |

## The Workable Hybrid: Zone-by-Zone, Fan-Side Control

Most real buildings are neither pure CAV nor pure VAV; they contain both kinds of zone. The workable approach is not to thread the two damper types onto one branch, but to control them at different levels:

1. **Give constant-volume zones their own branch.** Cleanrooms, laboratories and process rooms keep a dedicated CAV branch with a constant-airflow EC blower holding its own setpoint, outside the building-wide modulation.
2. **Let swing zones run VAV.** Office, meeting and retail terminals modulate on sensor demand and report that demand upstream.
3. **Close the loop at the fan.** A central static-pressure controller sums terminal demand into a pressure setpoint and trims EC fan speed through 0-10V or PWM. When demand falls, the fan slows with it instead of running flat out against closing dampers.

At that point the fan stops being a fixed-speed air source and becomes the actuator that delivers the energy saving. The [SF146A-E092A3-CA constant-airflow EC double-inlet centrifugal blower](https://en.sunxfan.com/en/products/sf146a-e092a3-ca/) is built for exactly this duty: 600 m³/h, up to 480 Pa, 180 W input at 230 V AC, 1200 r/min, 52±1 dB(A), IP42, a PA6+GF25% impeller on NSK ball bearings, rated −25 °C to +50 °C. Its four measured duty curves correspond to PWM 100/65/40/20% (Vsp 10.0/6.5/4.0/2.0 V), giving four design airflows — 600, 450, 300 and 180 m³/h — and it holds that airflow as system resistance climbs from roughly 100 Pa to 300 Pa without re-trimming the ductwork.

For larger duties, the rest of the [SF146A series](https://en.sunxfan.com/en/products/series/sf146a/) and the higher-pressure [SF160 series](https://en.sunxfan.com/en/products/series/sf160/) — up to 705 Pa — offer the same 0-10V/PWM control for central static-pressure integration. For the efficiency argument behind EC motors at part load, see the [IE5 PMSM EC fan technology breakdown](https://en.sunxfan.com/en/blog/inside-ie5-pmsm-ec-fan-technology/); for inlet configuration trade-offs, see [dual-inlet vs single-inlet centrifugal blowers](https://en.sunxfan.com/en/blog/dual-inlet-vs-single-inlet-centrifugal-blowers/).

## Specification Checklist: Five Questions

1. **Does the zone have a mandatory constant airflow?** If yes, CAV first — do not trade compliance for an energy figure.
2. **Do occupancy and pollutant load swing widely?** Large swings plus long operating hours are what make VAV pay.
3. **Will the building actually maintain sensors and controls?** Without calibration capability, VAV accuracy decays quickly and CAV becomes the lower-risk choice.
4. **Is the terminal already downstream of another control damper?** Never stack CAV below a VAV box; imbalance is almost guaranteed.
5. **Can the fan follow the system?** If it can, savings reach the fan; if it cannot, closing terminals only pushes surplus air against the ductwork.

Answer those five and the CAV-versus-VAV argument turns into an engineering calculation rather than a preference. If you need a constant-airflow EC blower for a CAV branch, or a fan-side scheme that follows a central static-pressure setpoint, send your airflow, static pressure, control signal and available space to our engineering team for a selection review.

---

Source: [https://en.sunxfan.com/en/blog/cav-vav-fan-systems/](https://en.sunxfan.com/en/blog/cav-vav-fan-systems/)

_Last updated: 2026-11-03_
