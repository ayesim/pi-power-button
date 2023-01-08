# pi power on off button
Pi power on off button function with control board

## Installation

Clone this repo: `git clone https://github.com/ayesim/pi-power-button.git`
Optional: Edit line 9/10 in listen-for-shutdown.py to your preferred pin
Run the setup script: `./pi-power-button/script/install`

## Uninstallation

If you need to uninstall the power button script in order to use GPIO6 for another project or something:

1. Run the uninstall script: `./pi-power-button/script/uninstall`

### Is it possible to use another pin other than Pin 31 (GPIO 6)?

There are two main features of the power button:

a. **Shutdown functionality:** Shut the Pi down safely when the button is pressed. The Pi now consumes zero power. Circuit will cut power
b. **Wake functionality:** Turn the Pi back on when the button is pressed again. Circuit handle power on function
