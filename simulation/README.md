# Hardware Simulation – AlertAxis

## Overview

This directory contains the hardware simulation of AlertAxis, developed using the Wokwi online electronics simulator.

The prototype explores an ESP32-based sensor monitoring node designed to collect environmental data relevant to tunnel safety.

## Components Used

| Component | Purpose |
|---|---|
| ESP32 | Main microcontroller |
| DHT22 | Temperature and humidity sensing |
| MQ2 | Gas and smoke input |
| Water Level Sensor | Water accumulation detection |
| Vibration Sensor | Vibration monitoring |
| Rain Sensor | Rainfall detection |
| LED | Visual indication of system status |
| Buzzer | Audible alert indication |

## Simulation Objectives

- Explore multi-sensor interfacing with ESP32.
- Acquire environmental sensor readings.
- Investigate sensor-based hazard assessment.
- Experiment with risk-level classification.
- Test visual and audible alert mechanisms.

## Experimental Risk Assessment

An experimental weighted risk-scoring mechanism is included in the simulation code to explore three operational states:

- **NORMAL:** No significant risk detected.
- **WARNING:** Conditions indicate a potential hazard.
- **CRITICAL:** Conditions indicate a high-risk situation.

This mechanism is currently experimental and requires further calibration and validation.

## Simulation Platform

**Wokwi:** [Open AlertAxis Simulation](https://wokwi.com/projects/477487143821102081)

## Current Status

The ESP32 sensor interfacing and individual input testing are part of the current prototype development. Further integration and validation of the multi-hazard assessment logic are ongoing.
