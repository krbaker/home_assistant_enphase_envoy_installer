# Enphase Envoy Installer

[![GitHub Release][releases-shield]][releases]
[![Maintainer][maintainer-shield]][maintainer]
[![HACS Custom][hacs-shield]][hacs-url]

This is a HACS custom integration for enphase envoys with firmware version 7.X.

▶ To be used with your installer or DIY account. (Most of the functionality won't be available when using a Home Owner account.)

Features:
- Individual device per inverter with all information available. 
- Individual device per Q-relay with relay status.
- "Production" switch to turn on/off solar power production.
- Firmware update sensor.
- 3 Phase CT readings.


<img width="775" alt="ha_envoy_inverters" src="https://github.com/vincentwolsink/home_assistant_enphase_envoy_installer/assets/1639734/a070ab6e-3207-412f-b712-6bd31cf8ac83">

Based on work from [@briancmpbll](https://github.com/briancmpbll/home_assistant_custom_envoy) and [@posixx](https://github.com/posixx/home_assistant_custom_envoy)


# Installation

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=vincentwolsink&repository=home_assistant_enphase_envoy_installer&category=integration)

Or follow these steps:
1. Install [HACS](https://hacs.xyz/) if you haven't already
2. Add this repository as a [custom integration repository](https://hacs.xyz/docs/faq/custom_repositories) in HACS
4. Restart home assistant
5. Add the integration through the home assistant configuration flow

[releases-shield]: https://img.shields.io/github/v/release/vincentwolsink/home_assistant_enphase_envoy_installer.svg?style=for-the-badge
[releases]: https://github.com/vincentwolsink/home_assistant_enphase_envoy_installer/releases
[maintainer-shield]: https://img.shields.io/badge/maintainer-vincentwolsink-blue.svg?style=for-the-badge
[maintainer]: https://github.com/vincentwolsink
[hacs-shield]: https://img.shields.io/badge/HACS-Custom-41BDF5.svg?style=for-the-badge
[hacs-url]: https://github.com/vincentwolsink/home_assistant_enphase_envoy_installer
