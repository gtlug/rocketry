# GTLUG Model Rocketry Project
## Introduction
At [GTLUG's](https://gtlug.github.io/) July 2024 monthly meeting, we started work on a model rocketry group project.

We've set out to solve a simple problem: How do we launch a model rocket without losing it?

We've since met several times to discuss various aspects of the project.

As a GTLUG project, it covers a wide variety of common intersecting subjects that we regularly discuss in our meetings in general:
* Physics
* Radio Engineering
* Open Source Software
* Electronics
* 3D Printing

## Objective
The purpose of this project is to research, design, and build a telemetry package capable of launching on a model rocket.

## Plan
The current plan is to integrate discrete telemetry hardware into a 3D-printed nose-cone.

The chosen telemetry hardware hypothetically should be capable of high acceleration, and high altitude flights.

In this first iteration, we are targeting off-the-shelf entry-level [Estes®-style model rockets](https://estesrockets.com/), 
using standard solid chemical propellant engines with modest thrust.

## Parts
For this project, we've acquired the following resouces:
| Part                                      | Links | Description                  |
|-------------------------------------------|-------|------------------------------|
| Quest Egg Lofter Courier Model Rocket Kit | [Store](https://bellevillehobby.com/product/quest-egg-lofter-courier-model-rocket-kit/)  [Specifications](https://www.apogeerockets.com/Rocket-Kits/Skill-Level-2-Model-Rocket-Kits/Courier#rocksim) | A base model rocket kit designed to loft loads in its nose-cone (an egg) |
| LILYGO® T-Beam SUPREME (UBLOX, 915MHz) | [Store](https://lilygo.cc/products/t-beam-supreme?variant=44907412193461) [Firmware](https://github.com/lyusupov/SoftRF/wiki/Prime-Edition-MkIII) | A telemetry module featuring multiple radio protocols, a GPS module capable of high acceleration, a wifi adapter and web interface for management |
