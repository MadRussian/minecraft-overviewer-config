minecraft-overviewer-config
===========================

Configuration that can be used with minecraft overviewer.

Requirements
============

1. You must have Minecraft Overviewer already installed
..* http://overviewer.org/
2. You are running a Linux device

How to use
==========

Change the do_worlds to the saves that you want to create the maps for.
The rest of the settings are set as defaults

    overviewer.py --config config

Settings
========

do_worlds
: The worlds to create maps for
render_dict
: The map types and overlays to create
direction
: Which direction to draw the maps
outputdir
: Where to store the result

