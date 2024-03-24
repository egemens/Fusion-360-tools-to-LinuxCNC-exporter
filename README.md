## Convert Fusion360 Tool Library to LinuxCNC Tool Table

Based on the work of Nathan Crapo
https://github.com/ntc490/fusion360

The script runs in Fusion 360, pointing to "CAMTools" directory, where both local and cloud libraries are found as json files. If the path to the directory changes in the future updates of the Fusion 360, just change it in the script.
   	
## Only tested on MacOS

### How to install and use

1. Go to "Utilities" and select "Scripts and Add-ins" from "Add-Ins" dropdown menu.
2. Create a new script under "My Scripts" section. Give it a name such as "exportToolsLinuxCNC"
3. Click edit to open your code editor.
4. Open "exportToolsLinuxCNC.py", copy and paste its contents to the script you created under Fusion.
5. If it is necessary, you can change default paths for input and output files and formatting of the output file (toolname, diameter, etc..)
7. Run the script inside Fusion 360. Select the json file of the library you like to convert and select the output folder.
