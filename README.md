# LabVIEWRaspberryPI_IndoorMonitoring
Hobby project. 

Indoor temperature and relative humidity monitoring with LabVIEW on a Raspberry PI and a LabVIEW NXG webvi to display the data

# Why did I start this project?
At our offices we are always complaining about the temperature difference between the groundfloor and the first floor offices.
As an engineer, I decided to make a small setup with a few sensornodes that measure and log temperature and relative humidity.

# Setup:
- sensor node: 

Raspberry PI 3 B with an SHT21 I2C sensor connected.

I followed the installation instructions from makerhub (https://www.labviewmakerhub.com/).

Additionally, I did the 'chroot SSH trick' to able to read the CPU temperature of the Raspberry PI (https://www.labviewmakerhub.com/doku.php?id=learn:libraries:linx:misc:chroot-ssh-trick)


