# Binaural-Rendering-of-Ambisonics-2D-Head-tracking-
READ ME

This file contains information on how to operate the two Max/MSP patches for 3rd and 5th order 2D Ambisonics. Please ensure that both the ICST ambisonics externals (https://www.zhdk.ch/index.php?id=icst_ambisonicsexternals) and the HISStools Impulse Response Toolbox (http://eprints.hud.ac.uk/14897/) are installed before use. 

** Note: Ensure the head tracker has had the correct firmware uploaded to it and that it is connected to the computer via USB before opening Max/MSP

Head Tracker:

1. Hit the print message to display the available serial ports in the Max window.

2. Select the Appropriate serial port (the usb one) from the drop down menu. 

3. Turn the head tracker on with the toggle.  

4. While wearing the head tracker, face the direction that you desire 0˚ azimuth to be. Hit the centering Bang button. This position will now be saved as 0˚ azimuth.  

 
Setting speaker placements and HRTFs:

1. Load in the folder containing the 2D HRTFs (48kHz) into the polybuffer~ object.

2. Click the bang button that selects speaker positions (this also sets the multiconvolve~ object).



