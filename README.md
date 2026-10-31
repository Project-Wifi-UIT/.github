# Project Wifi UIT

Project Wifi UIT explores Wi-Fi sensing and software engineering for hospital environments. Our main research prototype uses an ESP32 to collect Wi-Fi channel-state information (CSI) for patient-motion research and connects that signal-processing work to a basic hospital-software context.

This repository is the organization-level project hub. The implementation and research repositories are:

- [Hospital software with Wi-Fi CSI implementation through ESP32](https://github.com/Project-Wifi-UIT/Hospital-software-with-Wifi-CSI-implementation-through-esp32) — application and ESP32 prototype work.
- [Hospital CSI Knowledge](https://github.com/Project-Wifi-UIT/Hospital-CSI-Knowledge) — project notes, background, and research documentation.

## What this project is

The prototype investigates whether changes in Wi-Fi CSI can provide useful signals about movement in a room. An ESP32-based sensing setup captures measurements, software processes and presents those measurements, and the hospital-software repository provides a domain context for exploring responsible integration.

The project is exploratory and engineering-focused. It is not a clinical device, does not diagnose or monitor a medical condition, and does not replace professional observation, clinical judgment, or established hospital safety processes. No patient data should be committed to these repositories.

## Architecture at a glance

1. **Sensing:** ESP32 hardware collects Wi-Fi CSI measurements in a controlled environment.
2. **Processing:** software receives, filters, and visualizes measurements for experimentation.
3. **Application context:** hospital-software components provide a place to explore workflows and data boundaries.
4. **Documentation:** the knowledge repository records assumptions, experiments, and limitations.

The exact hardware, firmware, data formats, and application interfaces may change while the prototype evolves. Check each repository's current documentation before relying on an interface.

## Current status

This is an active research and prototyping effort. Results, interfaces, and documentation are subject to change; the repositories should be treated as experimental rather than production-ready. Claims about sensing performance require repeatable testing and should not be inferred from a demo alone.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening an issue or pull request. By participating, you agree to follow the [Code of Conduct](CODE_OF_CONDUCT.md). Security concerns should be reported according to [SECURITY.md](SECURITY.md).
