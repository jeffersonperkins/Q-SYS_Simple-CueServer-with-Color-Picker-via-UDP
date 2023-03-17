# Simple CueServer with Color Picker via UDP for Q-SYS
This is a script for controlling a CueServer via UDP with the color picker in Q-SYS.
In brief, the color picker sends the selected color as a string into the script. 
The script then parses the color picked into a correctly formatted command suitable to 
be sent to a CueServer Group.  For simplicity, it is sent via UDP to the CueServer.
