# Project Wifi UIT: ESP32 Wi-Fi CSI for patient-motion research

Project Wifi UIT is exploring whether Wi-Fi channel-state information (CSI) captured by an ESP32 can provide useful signals about movement in a hospital-room research setting. The project combines embedded sensing, signal processing, and a small hospital-software context to support repeatable engineering experiments.

## Purpose

The prototype records CSI measurements, processes changes in those measurements, and presents the resulting experimental signals for inspection. The goal is to learn about sensing setups, data pipelines, and responsible software integration—not to make medical decisions.

This work is exploratory. It is not a clinical device, diagnostic system, alarm, or replacement for professional observation and judgment.

## Architecture overview

```text
ESP32 sensing setup
        |
        v
CSI capture and transport
        |
        v
Signal processing and visualization
        |
        v
Hospital-software workflow experiments
        |
        v
Knowledge, limitations, and reproducibility notes
```

- **Sensing:** an ESP32 captures Wi-Fi CSI from a controlled experimental setup.
- **Processing:** software receives, filters, transforms, and visualizes measurements.
- **Application context:** the hospital-software project explores how experimental outputs could fit beside ordinary workflows without presenting them as medical conclusions.
- **Documentation:** the knowledge repository records setup details, assumptions, observations, and limitations.

Interfaces, hardware choices, and data formats are still evolving. Refer to the repositories for current implementation details.

## Repositories

- [Hospital software with Wi-Fi CSI implementation through ESP32](https://github.com/Project-Wifi-UIT/Hospital-software-with-Wifi-CSI-implementation-through-esp32) — ESP32, application, and integration prototype.
- [Hospital CSI Knowledge](https://github.com/Project-Wifi-UIT/Hospital-CSI-Knowledge) — background, experiment notes, and project documentation.

## Current prototype status

The project is under active development. Hardware experiments, processing logic, interfaces, and documentation may change as the team improves repeatability and evaluates environmental limitations. Demonstrations and early observations should not be treated as evidence of clinical performance or production readiness.

## Basic API liveness

[Check API liveness](https://api.uitenglishclub.link/health) — a basic endpoint check, not a clinical or full infrastructure status dashboard.

## Safety and privacy boundaries

- Treat outputs as experimental signals, never as diagnoses, treatment recommendations, or emergency alerts.
- Use synthetic, simulated, or explicitly de-identified data in development and documentation.
- Do not commit patient information, credentials, access tokens, private keys, or other sensitive data.
- Record uncertainty, environmental conditions, and possible false positives or false negatives.
- Do not describe the prototype as clinically validated, regulatory-approved, or ready for unsupervised use.

## Roadmap

- Make ESP32 capture and experiment setup instructions easier to reproduce.
- Improve measurement processing, visualization, and test coverage.
- Document data formats and interfaces between sensing, processing, and application components.
- Expand controlled experiments and report limitations clearly.
- Improve examples and contributor documentation using safe, non-sensitive data.

## Contributing

Contributions to reproducibility, testing, documentation, accessibility, and responsible data handling are welcome. Start with the organization [contribution guide](../CONTRIBUTING.md), then review the [code of conduct](../CODE_OF_CONDUCT.md) before opening an issue or pull request. Use the issue templates for focused bug reports and feature ideas.
