# agfc - AMD GPU Fan Controller

agfc is a fan controller for AMD graphics cards supported by the AMDGPU Linux driver. It has hard coded values for the moment and is probably unsafe to run.

## Installation

There is a script `agfc` and a systemd service file `agfc.service`. Place them in appropriate directories.

## Usage

Enable the systemd service file with `systemctl enable agfc.service`. I don't recommend running `agfc` directly, at least yet.
