## Getting Started

These instructions will get you a copy of the Visualization Tool up and running on your Windows 10 machine for evaluation purposes.

### Prerequisites

The Visualization Tool was tested on both Windows 7 and Windows 10 platforms.  

### Installing

1. Download (or clone) the WindowsVisualizationTool repository to a convenient location on your PC.
2. Navigate to inside the "standalone" folder.
3. Attach the two USB cables of your DevKit2 and connect them to your PC.
4. Power on the DevKit2.
5. It will take approximately a minute for Windows to install and enumerate both an HID and UVC class drivers for the DevKit2.
6. Verify that an image driver has been installed by viewing the Windows Device Manager. Under the "Imaging Device"
   you should see "FX3".

### Running

The Visualization Tool is now ready to be executed once the UVC driver has been installed.  Run the tool by double-clicking 
on "pcl_phoenix_gui_sdk.exe". A console window will start up and display status messages.  The main application will be displayed
in a separate GUI window.


### Guide
To zoom in and out, mouse click on the image and use mouse to zoom in and out
To rotate, hold mouse click down on the image and use mouse to rotate image
To shift image, hold shift key down, hold mouse click down on the image and use mouse to shift image

Click on About to find version of firmware and SDK 
The 'reset' button resets the visualization tool
The 'Reset View' buttons resets the view control settings


### Troubleshooting

* If the Visualization Tool does not start, verify that both USB cables have been plugged into the DevKit2. The tool will not
  start if either cable is unplugged.
* The UVC driver installation may take longer to install on some machines.  Periodically check that the driver is being installed
  by viewing the Windows Device Manager.  The Device Manager will refresh its tree a few times during installation of the UVC class driver.
  The Visualization Tool will not function until an FX3 device shows up in the Imaging Device tree.