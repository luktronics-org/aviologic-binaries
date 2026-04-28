# ✈️ LukTronics Aviologic

Aviologic is a desktop application for configuring LukTronics hardware interface cards and connecting them to PC-based flight simulators. It handles the communication between real avionics hardware and the simulator, so you can focus on building and using your cockpit instead of dealing with low-level protocol details.

This repository hosts **pre-built binary releases only**. The source code is not included.

## Supported Hardware

| Card | Type | Channels |
|---|---|---|
| A429_8 | ARINC 429 | 8 |
| ARI_10 | ARINC 429 | 10 |
| SSD_10 | Synchro | 10 |
| SSD3_10 | Synchro (HW rev 3) | 10 |

Devices are discovered automatically over the local network — no manual IP configuration needed.

## Supported Simulators

- **X-Plane 11**
- **ProSim** (Windows only)
- **PSX**

## Key Features

- **ARINC 429 configurator** — configure RX/TX channels and labels per device
- **Synchro configurator** — set filter and voltage parameters
- **Equipment file editor** — create and edit ARINC equipment definition files
- **Logic scripting** — load custom Python scripts to implement your own data mapping and processing logic
- **Firmware update** — update connected hardware directly from the application
- **Debug console** — inspect live output from your logic scripts

## Downloads

Download the latest release from the **Releases** section of this repository.

**Supported platforms:**
- Windows (full support)
- Linux (X-Plane/PSX only; ProSim not supported)

No compilation required — just extract and run.

## Getting Started

1. Download the binary for your platform from the Releases page.
3. Connect your hardware interface card.
4. Launch Aviologic.
5. Select your simulator and configure your device mappings.

## Reporting Issues

Use the **Issues** tab to report bugs or request features.

Please include any relevant log files and describe the steps to reproduce the problem.

## License

See the `LICENSE` file.
