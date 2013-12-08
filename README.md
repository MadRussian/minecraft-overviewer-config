minecraft-overviewer-config
===========================

Configuration that can be used with minecraft overviewer.

Requirements
============

1. You must have Minecraft Overviewer already installed
    http://overviewer.org/
2. You are running a Linux device
3. Your game saves are located in HOME/.minecraft/saves

How to use
==========

Change the do_worlds to the saves that you want to create the maps for.
The rest of the settings are set as defaults

    overviewer.py --config config

Settings
========

__do_worlds__: The worlds to create maps for

__render_dict__: The map types and overlays to create

__direction__: Which direction to draw the maps

__outputdir__: Where to store the result

