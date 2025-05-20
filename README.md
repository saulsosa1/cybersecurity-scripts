# Cybersecurity Scripts

A collection of practical PowerShell scripts for system hardening and secure configuration, focused on Windows environments. These scripts are designed for blue team use, incident response, and baseline security enforcement.

## Contents

### Hardening Scripts

- **Third-Party Software Removal**
  - Remove Wireshark if found (potential sensitive packet capture risk)

- **Windows OS Secure Configuration**
  - Disable insecure protocols
  - Remove/disable insecure cipher suites
  - Audit guest account membership in privileged groups

## Usage

Each script is written in PowerShell and designed to be run with administrative privileges. See `docs/usage_examples.md` for more details and flags/options.

## Disclaimer

Use at your own risk. Always test scripts in a non-production environment before deploying to live systems.
