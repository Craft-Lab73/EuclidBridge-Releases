# Euclid Bridge Windows Installers

This repository contains the official, signed Windows installers for Euclid Bridge.
It does not contain Euclid source code, tenant data, or credentials.

## Download

Use the [latest Euclid Bridge release](https://github.com/Craft-Lab73/EuclidBridge-Releases/releases/latest):

- **Desktop Agent** — for a tenant administrator's Windows computer.
- **Network Agent** — for an approved Windows server on the tenant's internal network.

These installers run on Windows only. A Mac can download the files, but it cannot
install or run them.

## Publisher and verification

Both installers are signed by **Epoch UX LLC** and timestamped through Microsoft's
code-signing service. Every release lists the expected file size and SHA-256
fingerprint so the downloaded file can be checked before installation.

Each release is automatically tested on Windows before publication. The checks
confirm the file fingerprint, publisher signature, installation result, and
Euclid Bridge service startup.
Official signed Windows installers for Euclid Bridge.
