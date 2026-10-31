# Project Wifi UIT

Project Wifi UIT is building an exploratory ESP32 Wi-Fi channel-state information (CSI) prototype for hospital patient-motion research. The work connects low-cost sensing, signal processing, and a basic hospital-software context while keeping the limits of the prototype explicit.

## Project overview

The prototype studies whether changes in Wi-Fi CSI can help describe movement in a controlled environment. An ESP32 records measurements; software processes and visualizes those measurements; and the surrounding hospital-software project provides a context for experimenting with workflows, security boundaries, and responsible handling of data.

This is research and prototype work, not a clinical product. It does not diagnose, predict, or make care decisions; it does not replace clinical observation or professional judgment; and it must not be used as the sole basis for an intervention. Do not use real patient information in issues, pull requests, examples, tests, or commits.

## Architecture

- **ESP32 sensing layer:** captures Wi-Fi CSI measurements from the experimental setup.
- **Processing layer:** receives, filters, transforms, and visualizes measurements.
- **Hospital-software context:** explores how prototype outputs might fit alongside ordinary software workflows without presenting them as medical conclusions.
- **Knowledge and documentation:** records experiments, assumptions, limitations, and reproducibility notes.

The implementation details and interfaces are evolving. See the repositories for the current setup and scope:

- [Hospital software with Wi-Fi CSI implementation through ESP32](https://github.com/Project-Wifi-UIT/Hospital-software-with-Wifi-CSI-implementation-through-esp32)
- [Hospital CSI Knowledge](https://github.com/Project-Wifi-UIT/Hospital-CSI-Knowledge)

## Safety boundaries

- Treat outputs as experimental signals, not diagnoses, alarms, or treatment recommendations.
- Use synthetic, simulated, or explicitly de-identified data only.
- Do not add credentials, access tokens, private keys, patient records, or other sensitive information.
- Document uncertainty, environmental limitations, and false-positive or false-negative risks.
- Do not imply clinical validation, regulatory approval, or production readiness.

## Status and collaboration

The project is under active development. Hardware experiments, data formats, software interfaces, and documentation may change. Contributions that improve reproducibility, testing, security, accessibility, and clear documentation are especially welcome.

Start with [CONTRIBUTING.md](../CONTRIBUTING.md), review the [Code of Conduct](../CODE_OF_CONDUCT.md), and use [SECURITY.md](../SECURITY.md) for private vulnerability reports.
