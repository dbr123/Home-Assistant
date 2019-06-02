# My Home Assistant setup:

This is my current Home Automation setup, based on Homeassistant.  This is my live system as it is running in my house at the moment.  I am currently tracking the beta channel of releases.  Below you will find links to how it is all organised, and I am in the process of adding a Wiki to this site that will explain how to create a system like mine from scratch...

## Information

| [![TravisCI](https://travis-ci.org/acesyde/Home-Assistant.svg?branch=master)](https://travis-ci.org/acesyde/Home-Assistant) | [![LastCommit](https://img.shields.io/github/last-commit/acesyde/Home-Assistant.svg?color=blue&style=plasticr)](https://github.com/acesyde/Home-Assistant/commits/master)|
|:---:|:---:|
| This shows whether the configuration in this repo is valid. [Version I'm running.](.HA_VERSION) | This shows how up to date this repo is |
| [![GitHub stars](https://img.shields.io/github/stars/acesyde/Home-Assistant.svg)](https://github.com/acesyde/Home-Assistant/stargazers) | [![GitHub issues](https://img.shields.io/github/issues/acesyde/Home-Assistant.svg)](https://github.com/acesyde/Home-Assistant/issues) |
| Please :star: this repo if you find it useful, like these people have. | This is like my TODO list |
|[![License: MIT](https://img.shields.io/badge/license-mit-blue.svg)](https://choosealicense.com/licenses/mit/)| [![contributions welcome](https://img.shields.io/badge/contributions-welcome-blue.svg?style=flat)](https://github.com/acesyde/Home-Assistant/pulls) |
| This tells you you can use anything you like from this repo for your project, gratis! | If you have any ideas, they're always welcome.  Either submit an issue or a PR, or drop me a message! |
| [![Uptime Robot status](https://img.shields.io/uptimerobot/status/m780352466-da3a90fa1da0e09f6f0ee745.svg)](https://uptimerobot.com/) |  |
|  |  |

## House:

- A living area (Living room and kitchen/diner)
- 3 bedrooms and bathroom
- 1 desk office

## Hardware:

### My controller
 - RPI 3
 - Zigate
 - USB Z-Wave+ - Everspring

## Integrated platforms:

### Networking
 - Netgear R7000 router - connecting everything together.
 - TP-Link TL-SG1016D 16 ports switch - allowing to have lots of wired connections for reliability.

### Xiaomi
 - Xiaomi Aqara Temperature Humidity Sensor x5

### Media
 - LG TV with Web OS 3

### Interfaces
 - 2 x Amazon Echo Dots - for voice control.
 - Telegram App (on mobiles) - for two-way conversations with Homeassistant.

## Configuration

Click [here](documentation/configuration.md) to see how I've configured it and how this repo is organised.

Click [here](packages/snapshots/README.md) to see how I keep everything running smoothly by monitoring my instances uptime, checking the validity of my config and managing backups.

## Inspirated By

* [mf-social](https://github.com/mf-social/Home-Assistant)
* [ntalekt](https://github.com/ntalekt/homeassistant)
* [stanvx](https://github.com/stanvx/Home-Assistant-Configuration)
* [JamesMcCarthy79](https://github.com/JamesMcCarthy79/Home-Assistant-Config)