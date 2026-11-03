---
title: "800VDC Axial Fan — Axial Fan"
description: "800VDC Axial Fan series: 3 models with airflow, static pressure, voltage, power, speed, noise and control data."
layout: kb
---

# 800VDC Axial Fan — Axial Fan

SUNXFAN 800VDC Axial Fan series: 3 models. All figures below are manufacturer datasheet values.

## Product image

![SUNXFAN 800VDC Axial Fan axial fan product photo](https://en.sunxfan.com/images/products/800vdc-axial-fan-axial-fan-product-1200.webp)

## Model matrix

| Model | Airflow | Max static pressure | Voltage | Power | Speed | Noise | Speed control |
| --- | --- | --- | --- | --- | --- | --- | --- |
| AG200A-D092BA-01 | 1950 m³/h | 1550 Pa | 460-800 V DC | 800 W | 7500 r/min | 83dB(A) | 0-10V/PWM / CAN 2.0 / CAN FD |
| AG305A-D092BA-Y1 | 4000 m³/h | 750 Pa | 480-650 V DC | 1200 W |  |  | CAN 2.0 / CAN FD |
| AG400A-D092BA-02 | 9000 m³/h | 850 Pa | 420-750 V DC | 1500 W | 3500 r/min | 75 dB(A) | CAN 2.0 / CAN FD |

## AG200A-D092BA-01 — DC200 Axial Fan — 1950 m³/h

### Specifications

- **Category:** Axial Fan
- **Motor:** DC
- **Airflow:** 1950 m³/h
- **Max static pressure:** 1550 Pa
- **Voltage:** 460-800 V DC
- **Power:** 800 W
- **Speed:** 7500 r/min
- **Noise:** 83dB(A)
- **Protection:** IP68
- **Temperature:** -15 °C ~ +60 °C
- **Impeller:** PA66+GF
- **Bearing:** ball bearing
- **Speed control:** 0-10V/PWM / CAN 2.0 / CAN FD
- **MOQ:** 124 PCS
- **FOB:** FOB Nansha Guangzhou
- **Lead time:** 25-30 days

### FAQ

**Q: What are the primary applications of 800VDC brushless fans?**

A: A DC axial fan operating over a wide voltage range of 560–800 VDC with integrated CAN FD communication is a high-voltage DC direct-fed, ultra-high-speed bus-responsive, high-reliability cooling terminal for industrial and vehicle-grade applications.

Since it can be mounted directly on a high-voltage DC bus (DC Link)—eliminating the traditional AC-DC or DC-DC step-down stage, greatly improving overall system efficiency and reducing footprint—and since CAN FD provides data transmission rates and payload capacity several times higher than traditional CAN 2.0B or Modbus, it has exceptionally clear applications in the following major heavy-industry and new-energy sectors, in addition to solid-state transformers (SSTs) and 800V EV fast-charging piles:

I. Core Application Scenarios
1. Large Containerized Battery Energy Storage Systems (BESS) and Liquid-Cooling Terminals (CDUs & Dry Coolers)
Application Logic: The battery cluster DC bus voltage of modern 1000V/1500V energy storage stations typically ranges from 500V–800VDC. The fan is powered directly from the high-voltage battery bus or high-voltage DC bus, requiring no additional voltage conversion or rectification equipment.

CAN FD Advantages: Energy storage stations have an extremely large number of nodes. The CAN FD protocol supports higher bandwidth (up to 5–8 Mbps) and 64-byte data payload, enabling millisecond-level real-time reporting of diagnostic data—such as fan speed, bus voltage, over-temperature alarms, and fan life warnings—to the BMS/EMS system, meeting the safety, explosion-proof, and rapid fault disconnection requirements of large-scale energy storage systems.

2. Hydrogen Fuel Cell Systems
Application Logic: The output voltage of megawatt-class or high-power commercial vehicle fuel cell stacks typically falls within the 500V–800VDC range during operation. The fan, serving as the fuel cell radiator or auxiliary thermal management fan, draws high-voltage power directly from the stack output.

CAN FD Advantages: Fuel cells are extremely sensitive to load changes and require the fan to adjust airflow instantaneously based on output power. The ultra-low latency control of CAN FD enables millisecond-level thermal response in coordination with the fuel cell.

3. 800V Commercial Heavy Trucks, Construction Machinery, and Electric Marine Vessels (Heavy-Duty EV & Marine)
Application Logic: The power battery platforms of mining trucks, electric heavy trucks, port machinery, and electric marine vessels are comprehensively transitioning to 800VDC. This fan is used for motor and power electronics radiators, battery chillers, and forced engine-room heat exhaust on these high-voltage platforms.

CAN FD Advantages: Vehicle-mounted and marine environments demand extremely high automotive-grade functional safety (ISO 26262). CAN FD supports more sophisticated CRC verification and native integration with the vehicle network (VCN).

4. Rail Transit Traction Converters and Auxiliary Power Supply Systems (Rail Transit APU & Traction Inverters)
Application Logic: The intermediate DC link voltage of high-speed rail, EMUs, and urban rail transit typically ranges around 600V–750VDC. The fan is connected directly to the intermediate DC circuit for forced air cooling of traction inverters, auxiliary power units (APUs), and braking resistors.

CAN FD Advantages: Train bus systems (TCMS) are progressively upgrading to CAN FD high-speed buses, allowing seamless fan integration with strong resistance to intense electromagnetic interference.

5. Industrial DC Microgrids and Centralized PV Inverters
Application Logic: In industrial zero-carbon parks and integrated PV-storage-charging facilities, a 750VDC DC bus is the standard energy transmission bus. The fan is mounted directly on the 750V DC bus, providing high-voltage direct-fed cooling for centralized PV inverters, high-voltage VFD cabinets, and DC distribution cabinets.

CAN FD Advantages: Supports large-scale network node deployment, facilitating centralized remote monitoring and digital twin modeling of all fans in a plant via smart factory systems (MES/SCADA).

6. Next-Generation 800V HVDC Data Centers
Application Logic: To reduce copper cable losses within data centers (especially AI supercomputing facilities), next-generation data center architectures are upgrading from 240V/330V HVDC to 800V HVDC power supply. This fan is used for high-capacity exhaust in outdoor dry coolers and chillers of data centers.

**Q: Why connect a fan directly to a 460-800 V DC bus instead of going through an inverter?**

A: Because the bus already exists. Energy-storage cabinets, PV arrays, HVDC telecom plants and DC charging sites distribute 460-800 V DC natively; every conversion stage you remove takes heat, losses and a failure mode with it. This axial (1,950 m³/h, up to 1,550 Pa, 800 W) hangs straight on that bus and is governed electronically — no VFD cabinet, no sine filter, no motor starting stress. Sites that must ride through outages like it too: the fan keeps running from the batteries while the AC side is down.

**Q: What does CAN FD communication add on a cooling fan?**

A: It turns the fan from an anonymous load into a reporting device. Over CAN FD the controller reads actual speed, current and temperature, and writes the duty point — so thermal management closes the loop on true cabinet temperature instead of open-loop guesses. The higher bandwidth carries more frequent telemetry on the same bus hosting the other DC-side devices, and fault flags (stall, overtemperature) reach the site controller in milliseconds instead of surfacing later as a thermal event.


## AG305A-D092BA-Y1 — DC305 Axial Fan — 4000 m³/h

### Specifications

- **Category:** Axial Fan
- **Motor:** DC
- **Airflow:** 4000 m³/h
- **Max static pressure:** 750 Pa
- **Voltage:** 480-650 V DC
- **Current:** 2 A
- **Power:** 1200 W
- **Protection:** IP68
- **Temperature:** -40 °C ~ +85 °C
- **Impeller:** PA66+GF
- **Bearing:** ball bearing
- **Speed control:** CAN 2.0 / CAN FD
- **MOQ:** 165 PCS
- **FOB:** FOB Nansha Guangzhou
- **Lead time:** 25-30 days

## AG400A-D092BA-02 — DC400 Axial Fan — 9000 m³/h

### Specifications

- **Category:** Axial Fan
- **Motor:** DC
- **Airflow:** 9000 m³/h
- **Max static pressure:** 850 Pa
- **Voltage:** 420-750 V DC
- **Power:** 1500 W
- **Speed:** 3500 r/min
- **Noise:** 75 dB(A)
- **Protection:** IP68
- **Temperature:** -40 °C ~ +65 °C
- **Impeller:** PA6+GF30
- **Bearing:** ball bearing
- **Speed control:** CAN 2.0 / CAN FD
- **MOQ:** 144 PCS
- **FOB:** FOB Nansha Guangzhou
- **Lead time:** 25-30 days

---

Source: [https://en.sunxfan.com/en/products/series/800vdc-axial-fan/](https://en.sunxfan.com/en/products/series/800vdc-axial-fan/)

_Last updated: 2026-11-03_
