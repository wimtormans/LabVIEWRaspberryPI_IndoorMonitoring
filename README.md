# LabVIEWRaspberryPI_IndoorMonitoring
Hobby project. 

# Summary:
Indoor temperature and relative humidity monitoring with LabVIEW on a Raspberry PI and a LabVIEW NXG webvi to display the data.

# Why did I start this project?
At our offices we are always complaining about the temperature difference between the groundfloor and the first floor offices.

As an engineer, I decided to make a small setup with a few sensornodes that measure and log temperature and relative humidity.

If we measure, we have proof :-)

# Setup:
- sensor node: 

Raspberry PI 3 B with an SHT21 I2C sensor connected.

I followed the installation instructions from makerhub (https://www.labviewmakerhub.com/).

After installation I had a small linking issue on the raspberry PI when deploying the code: LMH-LINX.lvlib
A fix can be found in this topic: https://www.labviewmakerhub.com/forums/viewtopic.php?f=12&t=3018


Additionally, I did the 'chroot SSH trick' to be able to read the CPU temperature of the Raspberry PI (https://www.labviewmakerhub.com/doku.php?id=learn:libraries:linx:misc:chroot-ssh-trick)

- WebVI:

LabVIEW NXG is still new and people aren't adopting to it yet. NXG has a webmodule to create webvi's which can be hosted on a webserver.
Plan is to make a webvi that will be hosted on an internal systemlink server so that every colleague can access the data with this webvi.


