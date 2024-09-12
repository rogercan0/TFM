The current traces in the Traces folder are PGP encrypted and will be deleted shortly after the project's presentation due to company policies.
If you want to test the code ask for the public key at rogercano97@gmail.com

In the NVM_detection folder there are 2 files:
1) NVM_detection.ipynb: A step by step description of the developed algorithm. The default trace used as an example is 07_08.txt
2) Full_Sweep.ipynb: The automated algorithm that will generate a .png file for every current trace. The images consist on the plotted traces in blue and the detected starting point of the NVM operation in red. The output format of the names are "preDelay_postDelay_startSample". The code should be run until an error is reached, which will indicate that all of the traces have been swept. The images will be generated within the NVM_Detection folder.

Note that in order for the code to work, the Traces folder must be decrypted and unzipped.

The Hardware folder contains the KiCad project and library dependencies of the custom Sol PCB, but requires having KiCad installed in the PC to run it. The schematics and Gerber files can be visualized without the need of additional software.