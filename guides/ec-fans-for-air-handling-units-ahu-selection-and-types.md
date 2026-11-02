---
title: "EC Fans for Air Handling Units (AHU): Selection and Types"
description: "How fan sections in air handling units are arranged, why EC double-inlet centrifugal fans dominate modern AHUs, and the three parameters — airflow, external static pressure and mounting envelope — that settle the selection."
---

# EC Fans for Air Handling Units (AHU): Selection and Types

The fan section is the energy heart of an air handling unit. Everything else in the cabinet — filters, coils, attenuators, dampers — only adds resistance; the fans are the components that pay the electricity bill. This guide explains how fans are arranged inside an AHU, why EC double-inlet centrifugal fans have become the default choice, and how to size them with three parameters.

## How fans are arranged inside an AHU

There are two common layouts for the fan section:

- **Single plenum-mounted plug fan.** One double-inlet centrifugal impeller is mounted directly in the cabinet wall without a scroll housing, blowing into the plenum downstream of the coil. Fewer parts, one motor, simple wiring — the classic layout for smaller AHUs.
- **Fan array (fan wall).** Several smaller EC fans are installed in parallel in a panel. The array gives redundancy — a single failed fan only trims capacity instead of stopping the unit — lowers overall section height, and produces an even discharge profile across the filter and coil face.

Both layouts rely on the same component: a backward-curved double-inlet centrifugal blower with an EC motor.

## Why AHUs prefer EC double-inlet centrifugal fans

An AHU fan must push air through filters, coils, attenuators and the duct network — that is external static pressure, not just bulk airflow. Backward-curved double-inlet centrifugal impellers generate this pressure efficiently, and the double-inlet design splits the flow across two suction faces, so the same airflow is delivered by a wheel with a shorter axial length and balanced suction on both sides.

The EC part matters just as much. An EC (electronically commutated) motor is a permanent-magnet machine with integrated power electronics: no belts and pulleys to align, no separate variable-frequency drive cabinet, and precise speed control built into the fan itself. For a refresher on the motor economics, see the [EC vs AC comparison](/en/guides/ec-vs-ac-fans-which-saves-more-energy/).

## Partial load: why speed control pays off

Fan power follows roughly the **cube of speed**. An AHU that runs at 70% airflow needs only about a third of the power — but only if the fan actually slows down instead of being throttled by dampers. Because AHUs spend most of their operating hours well below design airflow, the fan that decelerates smoothly wins the energy argument. This is exactly where EC fans outperform fixed-speed AC units: the electronics adjust speed continuously, without the losses of throttling.

## Control integration with the building automation system

Modern EC fans plug straight into the building automation system:

- **0-10V** analog input for a simple speed setpoint from the controller.
- **Modbus RTU (RS-485)** digital control, which also reports speed, current and status back to the BAS.

That return channel is what makes demand-controlled ventilation practical: the unit ramps with CO₂, occupancy or schedule, and the BAS can see — not guess — what the fan is doing.

## The three selection parameters

1. **Airflow (m³/h).** The design supply airflow of the unit. Size the fan for the duty point, not for free-blowing capacity.
2. **External static pressure (ESP).** The total resistance downstream and upstream of the unit: filters (at loaded condition, not clean), coils, attenuators, dampers and ductwork. A fan selected on clean-filter ESP alone will fall short in its first season.
3. **Mounting envelope.** The width, depth and weight the fan section can accept, plus the electrical connection and any clearances for service. In a fan array, the individual module size decides how many fans fit the panel.

For a deeper walk-through of fan sizing in general, see the [centrifugal fan selection guide](/en/guides/how-to-choose-a-centrifugal-fan-cfm-static-pressure-voltage/).

## Serviceability: access doors, slide rails and swap-outs

Maintenance is designed into the fan section, not improvised later:

- An **access door** in front of the fan section sized for the impeller.
- **Slide rails** that let the complete motor-impeller module be pulled out of the cabinet without touching duct connections.
- In a fan array, **modular units** that can be unbolted and swapped during a single maintenance window, while the remaining fans keep running at higher speed.

This is one more reason arrays are popular in buildings that cannot tolerate downtime.

## Bottom Line

For most AHUs the choice is now straightforward: backward-curved EC double-inlet centrifugal fans, mounted either as a plug fan or as a redundant array, controlled over 0-10V or Modbus RTU. Get the three selection numbers right — airflow, ESP at loaded filters, and mounting envelope — and the fan section will run quietly for years. Browse the [centrifugal fan range](/en/products/centrifugal-fans/) or the [EC fan technology page](/en/technologies/ec-fans/), and tell us your unit's duty point for an exact model proposal.
