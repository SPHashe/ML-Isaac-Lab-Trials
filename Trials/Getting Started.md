The hardest part of learning anything is getting started, so here's a jump-start on what to do for a quick start

# Download the Needed Folder
https://docs.isaacsim.omniverse.nvidia.com/latest/installation/download.html#isaac-sim-download
Go to the Isaac Sim website by NVIDIA and download the folder depending on your device.

# Next Step
Open up CMD with admin permissions, copy the following code and run it:

mkdir C:\isaacsim
cd %USERPROFILE%/Downloads
tar -xvzf "isaac-sim-standalone@4.5.0-rc.36+release.19112.f59b3005.gl.windows-x86_64.release.zip" -C C:\isaacsim
cd C:\isaacsim
post_install.bat
isaac-sim.selector.bat

# Long Wait and Open Program
After a whole bunch of code runs on your screen, the Isaac Sim full app  will open. Select the options you need (and if you don't know, then just run with the defaults; it worked for me)

# Debugging
I didn't run into any problems after that. This will probably be updated over time as I run into problems. Good luck in your endeavours, fellow coders.
