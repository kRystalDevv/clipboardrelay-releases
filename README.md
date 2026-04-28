# Clipboard Relay

**Clipboard Relay** is a local-network clipboard tool for Windows.

It lets you send text from a phone, tablet, or another device to Windows machines on the same local network. It is designed for places like gaming zones, computer labs, classrooms, offices, and other LAN setups where quick text transfer between devices is needed.

No cloud account is required. Devices communicate through your local network.

## What this repository is for

This repository is used for public release distribution.

It includes:

- Windows installer builds
- Release notes
- Update packages used by Clipboard Relay

The main development repository is maintained separately.

## How Clipboard Relay works

Clipboard Relay uses a simple Hub and Agent setup.

- **Hub**  
  Installed on the main machine. It hosts the web interface and manages connected devices.

- **Agent**  
  Installed on Windows machines that should receive clipboard text.

- **Helper**  
  Runs in the logged-in Windows session and writes received text to the clipboard.

- **Updater**  
  Handles update installation when new release packages are available.

## Basic installation

1. Open the **Releases** page of this repository.
2. Download the latest Clipboard Relay installer.
3. Run the installer as **Administrator**.
4. During setup, install the **Hub** only on the main/server machine.
5. Install the **Agent** on the Windows machines that should receive text.
6. Start the Hub.
7. Open the Hub web address from your phone or another device on the same network.
8. Select the target device and send text.

## Typical use cases

Clipboard Relay is useful for:

- Gaming zones
- Computer labs
- Classrooms
- Office LAN setups
- Multi-PC rooms
- Quickly sending links, commands, usernames, or text snippets to Windows machines

## Network requirement

All devices should be on the same local network.

Clipboard Relay is intended for trusted LAN environments.

## License

Clipboard Relay is distributed as compiled software.

Copyright (c) 2026 63xky.

See [LICENSE.md](LICENSE.md) for full license details.
