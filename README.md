# urdf2webots

This tool converts URDF files to a Webots-readable format.

## Usage

`python urdf2webots.py someRobot.urdf [-o outputFile] [--box-collision]`

Outputs: someRobot_textures (folder), someRobot.proto.
Test in webots: put outputs in protos folder within webots project.

## notes
urdf file should in root folder. 
This has been tested with ur10 and pr2 using webots7.4.3 on Ubuntu16.04.
