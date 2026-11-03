---
title: "AS Axial Fan- Guard-Ring — Axial Fan"
description: "AS Axial Fan- Guard-Ring series: 4 models with airflow, static pressure, voltage, power, speed, noise and control data."
layout: kb
---

# AS Axial Fan- Guard-Ring — Axial Fan

SUNXFAN AS Axial Fan- Guard-Ring series: 4 models. All figures below are manufacturer datasheet values.

## Model matrix

| Model | Airflow | Max static pressure | Voltage | Power | Speed | Noise | Speed control |
| --- | --- | --- | --- | --- | --- | --- | --- |
| AS760A-E137A3-01 | 16500 m³/h | 300 Pa | 380-480 V AC | 1100 W | 950 r/min | 69 dB(A) | 0-10V/PWM / Modbus RTU(RS485) |
| AS860A-E150A3-01 | 24000 m³/h | 300 Pa | 380-480 V AC | 1800 W | 920 r/min | 72 dB(A) | 0-10V/PWM / Modbus RTU(RS485) |
| AS910A-E150A3-01 | 25000 m³/h | 300 Pa | 380-480 V AC | 1800 W | 930 r/min | 73 dB(A) | 0-10V/PWM / Modbus RTU(RS485) |
| AS960A-E150B3-01 | 29000 m³/h | 300 Pa | 380-480 V AC | 3200 W | 915 r/min | 75 dB(A) | 0-10V/PWM / Modbus RTU(RS485) |

## AS760A-E137A3-01 — EC760 Axial Fan — 16500 m³/h

### Specifications

- **Category:** Axial Fan
- **Motor:** EC
- **Airflow:** 16500 m³/h
- **Max static pressure:** 300 Pa
- **Voltage:** 380-480 V AC
- **Current:** 2.4 A
- **Power:** 1100 W
- **Speed:** 950 r/min
- **Noise:** 69 dB(A)
- **Protection:** IP55
- **Temperature:** -40 °C ~ +65 °C
- **Impeller:** PA6+GF30%
- **Bearing:** ball bearing
- **Speed control:** 0-10V/PWM / Modbus RTU(RS485)
- **MOQ:** 70 PCS
- **FOB:** FOB Nansha Guangzhou
- **Lead time:** 25-30 days

## AS860A-E150A3-01 — EC860 Axial Fan — 24000 m³/h

### Specifications

- **Category:** Axial Fan
- **Motor:** EC
- **Airflow:** 24000 m³/h
- **Max static pressure:** 300 Pa
- **Voltage:** 380-480 V AC
- **Current:** 4.8 A
- **Power:** 1800 W
- **Speed:** 920 r/min
- **Noise:** 72 dB(A)
- **Protection:** IP55
- **Temperature:** -40 °C ~ +65 °C
- **Impeller:** PA6+GF30%
- **Bearing:** ball bearing
- **Speed control:** 0-10V/PWM / Modbus RTU(RS485)
- **MOQ:** 70 PCS
- **FOB:** FOB Nansha Guangzhou
- **Lead time:** 25-30 days

## AS910A-E150A3-01 — EC910 Axial Fan — 25000 m³/h

### Specifications

- **Category:** Axial Fan
- **Motor:** EC
- **Airflow:** 25000 m³/h
- **Max static pressure:** 300 Pa
- **Voltage:** 380-480 V AC
- **Current:** 4.5 A
- **Power:** 1800 W
- **Speed:** 930 r/min
- **Noise:** 73 dB(A)
- **Protection:** IP55
- **Temperature:** -40 °C ~ +65 °C
- **Impeller:** PA6+GF30%
- **Bearing:** ball bearing
- **Speed control:** 0-10V/PWM / Modbus RTU(RS485)
- **MOQ:** 70 PCS
- **FOB:** FOB Nansha Guangzhou
- **Lead time:** 25-30 days

### FAQ

**Q: What are the primary applications of EC axial fans with a wall ring and guard?**

A: For a massive EC axial fan with an operating voltage of 380–480V AC (three-phase industrial wide voltage), a maximum airflow of 31,000 m³/h, and equipped with a Wall Ring and Guard, this is an ultra-high-airflow, industrial-grade, high-efficiency heavy-duty fan (typically corresponding to a 760mm–1000mm large-diameter impeller class).

The combination of 380–480V three-phase power with the stepless speed control and high energy efficiency of an EC motor makes it highly suitable for heavy industrial and agricultural scenarios requiring 24-hour continuous operation, ultra-large-space air exchange, or high heat dissipation loads.

I. Specific Industries and Application Scenarios
1. Livestock & Agricultural Ventilation
Large modern poultry houses and dairy barns: The ultra-high airflow of 31,000 m³/h is extremely suitable as tunnel ventilation fans at the end of large-scale farms, used to rapidly remove ammonia, moisture, and heat from the barn to maintain livestock comfort.

Large multi-span greenhouses: Installed on the end wall of the greenhouse, working in conjunction with a Cooling Pad system for overall evaporative cooling and long-distance air circulation.

2. HVAC & Commercial Refrigeration
Dry Coolers & Closed Cooling Towers: Widely used as top-mounted exhaust fans for dry coolers, serving heat dissipation in the secondary loop for data centers, large commercial buildings, or industrial refrigeration.

Large Air-Cooled Condensers & Chillers: The design equipped with a Wall Ring and Guard allows direct bolt-fastening to the top or side of condenser frames, significantly improving heat exchange efficiency and reducing energy consumption.

3. Industrial Facilities & High-Bay Ventilation
Heavy Industrial Plant Exhaust: Suitable for high-temperature/high-dust workshops in steel, foundry, chemical, rubber, and glass industries, installed on exterior walls for centralized high-power exhaust.

Logistics Centers & Warehouses: Maintaining overall air movement within high-bay spaces to prevent hot air accumulation at the top (destratification).

4. Renewable Energy & Power Grid
MW-level Containerized ESS: In centralized heat exhaust systems for large energy storage containers, secured to the container end wall via the Wall Ring for high-airflow forced draft cooling to prevent battery thermal runaway.

Transformers & Wind Turbine Substation Cooling: Used for air-cooling systems of ultra-high-voltage transformer banks and heat dissipation of electrical equipment at the base of wind turbine towers.

**Q: One large fan or several smaller ones for the same duty?**

A: One AS910 moving 25,000 m³/h beats a bank of small fans on installed cost, wiring and maintenance — one motor, one set of bearings to watch. It also wins the acoustic sum: several equal sources together add about 10·log(N) dB, so five fans of the same total duty run roughly 7 dB(A) louder than one. Several smaller fans earn their place where redundancy matters — N+1 capacity so a single failure costs a fraction of the airflow — and where the opening cannot host one round fan.

**Q: How does Modbus RTU integration work on this fan?**

A: The EC electronics expose the fan as a Modbus RTU slave: the BMS writes the speed setpoint and reads back speed, current and status over the same two-wire RS-485 that already runs the site. That closes the thermal loop — airflow follows measured temperature instead of a fixed tap — and runtime logs enable condition-based maintenance instead of calendar-based. Address, baud and parity are configured once at commissioning; afterwards the fan behaves like any other Modbus device on the panel.


## AS960A-E150B3-01 — EC960 Axial Fan — 29000 m³/h

### Specifications

- **Category:** Axial Fan
- **Motor:** EC
- **Airflow:** 29000 m³/h
- **Max static pressure:** 300 Pa
- **Voltage:** 380-480 V AC
- **Current:** 8.0 A
- **Power:** 3200 W
- **Speed:** 915 r/min
- **Noise:** 75 dB(A)
- **Protection:** IP55
- **Temperature:** -40 °C ~ +65 °C
- **Impeller:** PA6+GF30%
- **Bearing:** ball bearing
- **Speed control:** 0-10V/PWM / Modbus RTU(RS485)
- **MOQ:** 70 PCS
- **FOB:** FOB Nansha Guangzhou
- **Lead time:** 25-30 days

---

_Last updated: 2026-11-03_
