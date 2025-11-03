# Crestron Construct MTR Camera Control
This project file contains pages for PTZ control and Preset Recall of commonly supported cameras on a Crestron Flex MTR system (Huddly, Jabra, Logitech, Poly) via Reserved Joins.

# Disclaimer
**Please note that this project is not created by or associated with Crestron Electronics and no support or warranty is provided.**

Inspired by https://github.com/avdoguctricks/crestroncameracontrols

# Installation Instructions
1) Load project solution (.csln) into Crestron Construct.
2) Double click on a page to view its contents. The pages are split into themes (Default Blue or Vivid Flag) and the type of camera to be used.
3) Click the pencil symbol next to the page and then select the option to make the page the default page (e.g. Huddly-Default Blue).
4) Observe the star icon next to the page indicating this is the landing page for the project.
5) Remove the star symbol from any other pages that may have that symbol (by default Huddly-Vivid Flag is the page set to be the landing page).
6) Compile the project.
7) The compiled file (.ch5z) will be located in the output folder within your project folder (by default C:\Users\{Your Username}\Documents\Crestron\Crestron Construct\Solutions
8) Upload the .ch5z file to the UC-ENGINE using Toolbox or by coping the file onto a USB stick and then using the Crestron Settings application on the UC-ENGINE to load the file.

# Limitations
The project has been designed with the idea that you will only use page flips (no control system needed). This provides convenience but does add some limitations.
1) The switch theme button is just a page flip- there is no memory. Each day, after the unit does its nightly reboot, you would need to press the change theme button again to get the theme you want. Instead, to make this persistent, you should compile the project with the correct theme set as the landing page (as per the installation instructions).
2) Camera support is limited to those supported by Crestron's reserved joins. Please contact Crestron True Blue Support for queries related to supported camera makes/models and Crestron Construct.

# Bugs & Support
Per the disclaimer, please note that this project is not created by or associated with Crestron Electronics - please do not contact them for support regarding this project.
Please feel free to report any issues with the project via the usual Github process.
