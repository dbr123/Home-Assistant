# My configuration:

See in the repo for all of my non-sensitive configuration files.  I've been playing with HA for a while now and have made a fair few changes, and have now decided to organise my files in a package-based system.

I have put a comment block at the top of each file that hopefully will explain what each one is for, should anyone want to use this repo as a learning tool, or for anyone that wants to copy any of the packages.

## How it works:

All your Homeassistant files are contained within your `/path/to/.homeassistant/` directory.  Inside this directory are some files that can't be moved such as `secrets.yaml` , `known_devices.yaml` and (most importantly) `configuration.yaml` .

There are various ways to split the configuration.yaml in to smaller chunks with !include statements, this is detailed here > https://home-assistant.io/docs/configuration/splitting_configuration/

I've chosen to split the configuration in to packages (detailed here > https://home-assistant.io/docs/configuration/packages/ ), and create devices or utilities by grouping components and sensors together.  These are placed in a folder called `packages/` .  Where a config item is really long (like the list of ir codes to control my AV devices) I have used includes to keep things neat.

The end result looks like this:

```
.homeassistant/
    |
    |- configuration.yaml
    |- secrets.yaml
    |- travis.yml
    |- [other unmovable configuration files and directories]
    |
    |-----/config/
    |      |
    |      |- [General configuration]
    |
    |
    |-----/packages/
    |      |
    |      |[file per package]
```