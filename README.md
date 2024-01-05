# VanPi Automation API

Please note that this is currently in the proof of concept stage for automation tasks based on the [VanPi platform](https://github.com/coconup/vanpi-core-api). The primary goal is to centralize all automation tasks, such as timers, IoT-triggered flows, and thermostat-based heater control, within this repository instead of the core API.

## Project Overview

This repository is expected to feature standardized functionality, particularly in areas like heater control. However, its main purpose will be to serve as a collection of examples and provide inspiration for others to develop their own flows tailored to their specific needs.

## Modes Feature

One notable implemented pattern, both in functionality and the user interface, is the concept of "Modes." This feature allows users to create buttons through the UI that can toggle a specific "mode" on and off. These modes can serve as the foundation for automating various actions based on user-defined scenarios.

### Example Mode: "Winter Travel"

As an illustrative example, a "Winter Travel" mode has been included. When activated, this mode automatically initiates a loop of hot water as soon as the tank temperature drops below two degrees. The loop is designed to cease when the temperature rises again to at least six degrees.
