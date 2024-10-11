# ExitOS Add-on Repository for Home Assistant

This repository contains a custom Home Assistant add-on, **ExitOS**, designed for managing smart energy networks. The add-on enables the configuration, simulation, and management of various energy assets, such as buildings, consumers, generators, and energy sources.

## Add-on Documentation

For more details about Home Assistant add-ons, refer to the [official documentation](https://developers.home-assistant.io/docs/add-ons).

[![Open your Home Assistant instance and show the add add-on repository dialog with a specific repository URL pre-filled.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https://github.com/NarcisPlan16/HA_Scheduler)

## Add-ons

This repository contains the following add-ons:

### [ExitOS](./exit_os)

![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]
![Supports armhf Architecture][armhf-shield]
![Supports armv7 Architecture][armv7-shield]
![Supports i386 Architecture][i386-shield]

_ExitOS manages a smart energy network by integrating various energy assets, such as buildings, consumers, and generators. It allows users to simulate energy production and consumption, making it ideal for energy communities._

### Features

- **Asset Configuration**: Allows you to configure various energy assets using `.toml` files.
- **Asset Simulation**: Provides the ability to simulate the performance of energy assets, including energy generation and consumption.
- **Dynamic Asset Management**: Easily manage buildings, generators, consumers, and energy sources.
- **Controllable Assets**: Supports integration of controllable energy sources.
- **Supports Multiple Architectures**: Compatible with a variety of hardware platforms.

### Usage Instructions

1. Add this repository to Home Assistant.
2. Configure your energy assets using the provided `.toml` configuration files.
3. Run simulations to manage and monitor energy production and consumption.
4. Manage the system through the provided web interface.

For further information on how to configure assets or contribute to the development of this add-on, check the code and documentation in this repository.

---

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
