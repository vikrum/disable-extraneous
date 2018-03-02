# Disable Extraneous

Disable Extraneous is a Chrome extension that disables the extraneous APIs. It has no configuration
settings, and is suitable for force-installing via Chrome Enterprise management.

## Why?

Extraneous APIs provide access to devices that may not be designed with an adversarial
threat model in mind, protected only by a permissions dialog that does not make
the risks clear.

Given the lack of widely-deployed uses of these extraneous APIS, disabling them is a prudent
defense-in-depth measure.

## Verification

Verify Bluetooth is disabled here: https://googlechrome.github.io/samples/web-bluetooth/device-info.html
