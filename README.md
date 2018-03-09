## Getting Started

These instructions will get you a copy of the Visualization Tool up and running on your Windows 10 machine for evaluation purposes.

### Prerequisites

The Visualization Tool was tested on both Windows 7 and Windows 10 platforms.  You will need Internet access to allow
the Windows Device Manager to download and install the Cypress FX3 USB driver.

### Installing

1. Download (or clone) the WindowsVisualizationTool repository to a convenient location on your PC.
2. Navigate to inside the "standalone" folder.
3. Attach the two USB cables of your DevKit2 and connect them to your PC.
4. Power on the DevKit2.
5. It will take approximately a minute for Windows to install a USB HID device along with the Cypress FX3 USB driver.
6. Verify that the FX3 driver has been installed by viewing the Windows Device Manager. The FX3 will
   present itself as an "Imaging device".

### Running

The Visualization Tool is now ready to be executed once the FX3 driver has been installed.  Run the tool by double-clicking 
on "pcl_phoenix_gui_sdk.exe". A console window will start up and display status messages.  The main application will be displayed
in a separate GUI window.

### Troubleshooting

* If the Visualization Tool does not start, verify that both USB cables have been plugged into the DevKit2. The tool will not
  start if either cable is unplugged.
* The FX3 driver installation may take longer to install on some machines.  Periodically check that the driver is being installed
  by viewing the Windows Device Manager.  The Device Manager will refresh its tree a few times during installation of the driver.
  The Visualization Tool will not function until the FX3 USB device has completed installation.