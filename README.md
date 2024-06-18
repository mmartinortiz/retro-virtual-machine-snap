# Retro Virtual Machine - Snap

This repository contains the `snapcraft.yaml` for the generation of the Retro Virtual Machine Snap. The author of this snap **does not** offer support for **RetroVirtualMachine**, you have to contact the original author for getting support. If you want to contribute to the Snap, this is your place, feel free to open an issue or a merge request with improvements.

The original website of Retro Virtual Machine is <https://www.retrovirtualmachine.org/en/>. There you can find details to contact the original author.

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/mmartinortiz-retro-virtual-machine)

## Development

```bash
# Building
snapcraft build

# Pack
snapcraft pack

# Install locally
snap install --devmode mmartinortiz-retro-virtual-machine_2.1.0_amd64.snap

# Test locally. Last time I used this sequence
snapcraft try
snap try prime 
./prime/usr/bin/RetroVirtualMachine

# pushing
snapcraft login
snapcraft push mmartinortiz-retro-virtual-machine_2.1.0_amd64.snap
```
