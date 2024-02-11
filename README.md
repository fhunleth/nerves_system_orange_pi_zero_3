# Nerves System for the OrangePi Zero 3

[![CircleCI](https://circleci.com/gh/fhunleth/nerves_system_orange_pi_zero_3.svg?style=svg)](https://circleci.com/gh/fhunleth/nerves_system_orange_pi_zero_3)
[![Hex version](https://img.shields.io/hexpm/v/nerves_system_orange_pi_zero_3.svg "Hex version")](https://hex.pm/packages/nerves_system_orange_pi_zero_3)

This is the base Nerves System configuration for the [Orange Pi Zero 3](http://www.orangepi.org/html/hardWare/computerAndMicrocontrollers/details/Orange-Pi-Zero-3.html).

| Feature              | Description                      |
| -------------------- | -------------------------------- |
| CPU                  | ARM Cortex-A53 1.5 GHz           |
| Memory               | 1 GB, 1.5 GB, 2 GB, or 4 GB DRAM |
| Storage              | MicroSD card (SPI Flash unused)  |
| Linux kernel         | 6.1                              |
| IEx terminal         | ttyS0 via GPIO header            |
| UART                 |                                  |
| USB                  | Yes                              |
| I2C                  | i2c-0, i2c-1, i2c-2              |
| Ethernet             | Yes                              |
| LEDs                 | LED exposed via /sys/class/leds  |

## Using

The most common way of using this Nerves System is create a project with `mix
nerves.new` and to export `MIX_TARGET=orange_pi_zero_3`. See the [Getting started
guide](https://hexdocs.pm/nerves/getting-started.html#creating-a-new-nerves-app)
for more information.

If you need custom modifications to this system for your device, clone this
repository and update as described in [Making custom
systems](https://hexdocs.pm/nerves/customizing-systems.html).

## Supported WiFi devices

The base image includes drivers for the onboard Orange Pi Zero 3 wifi module.

