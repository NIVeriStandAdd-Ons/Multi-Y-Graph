## Multi-Y Graph ##

**Multi-Y Graph** is a workspace object which enables the user to plot multiple Y channels verses a single X channel.

### LabVIEW Version ###

LabVIEW 2013.

### Built Availability ###

Builds of this IP not available.

### Quality, Limitations ###

This IP has been in use since 2013.

### Dependencies ###

Structured Error Handler

### Instructions for Use ###

1. Select which channel you would like to use for your X.
2. Select which channels you would like to plot against X for your Y list.
3. Set the Decimation, UDP Buffer Size, History Length (seconds), and Update Rate.
4. Format using the Format & Precision tab.

**Note** When you configure the Multi-Y Graph a memory buffer will be created according to the following equation: ((History Length (seconds) X PCL Rate (Hz))/(Decimation X Data Processing Loop Decimation)) X # of Channels X 64 bits. Verify that you have the available memory and increase Decimation if you do not.

### License ###

*This repository and any materials provided by NI therein are provided AS IS. NI DISCLAIMS ANY AND ALL LIABILITIES FOR AND MAKES NO WARRANTIES, EITHER EXPRESS OR IMPLIED, INCLUDING WITHOUT LIMITATION ANY WARRANTIES OF MERCHANTABILITY, FITNESS FOR  PARTICULAR PURPOSE, OR NON-INFRINGEMENT OF INTELLECTUAL PROPERTY. NI shall have no liability for any direct, indirect, incidental, punitive, special, or consequential damages for your use of the repository or any materials contained therein.*