CommentGCode

Cura Postprocessing Script that adds comments to the G-Code

This Cura Postprocessing Script adds comments to the G-Code.
The user can select or deselect comments for M-Commands and G-Commands separately.

G0 and G1 commands are only commented if a retract is included.

Command, description and parameters are read from a CSV file. If a command is not contained, the required data is determined once via
http://marlinfw.org/docs/gcode/
and added to the CSV file.


Installation:

The two files CommentGCode.py and Cura_GCode.CSV are stored in the user script directory of the respective Cura version:
<user>\AppData\Roaming\cura\<version>\scripts

After the next start of Cura the script can be added via
Extension / Post-Processing / Modify G-Code
Add a script: Comment G Code
