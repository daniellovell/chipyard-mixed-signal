![CHIPYARD](https://github.com/ucb-bar/chipyard/raw/master/docs/_static/images/chipyard-logo-full.png)

# Chipyard Framework [![Test](https://github.com/ucb-bar/chipyard/actions/workflows/chipyard-run-tests.yml/badge.svg)](https://github.com/ucb-bar/chipyard/actions)

## Quick Links

* **Stable Documentation**: https://chipyard.readthedocs.io/
* **User Question Forum**: https://groups.google.com/forum/#!forum/chipyard
* **Bugs and Feature Requests**: https://github.com/ucb-bar/chipyard/issues

## Chipyard - Mixed-Signal Fork
This fork is intended for use alongside the "Mixed-signal verification with Chisel" tutorial. It contains the latest Chipyard fork as of November 2022 as well as an additional generator for a PWM DAC peripheral.

The PWM DAC Peripheral can be found linked as a submodule in `generators/pwm-dac` and the corresponding repository is found on Github: https://github.com/daniellovell/pwm-dac-peripheral 

## Getting Started

Clone the repository:

`git clone https://github.com/daniellovell/chipyard-mixed-signal.git`

Initialize all submodules. This will handle downloading the PWM DAC peripheral

`git submodule update --init --recursive`

