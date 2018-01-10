Freetronics Power-over-Ethernet 802.3af Regulator
=================================================
Copyright 2010-2013 Freetronics Pty Ltd www.freetronics.com  
Copyright 2018 SuperHouse Automation Pty Ltd www.superhouse.tv--

Module to regulate power supplied on Power-over-Ethernet connection
down to 10Vdc for supply to the on-board voltage regulator in an
Arduino Uno or other compatible board using the Freetronics Ethernet
Shield, or boards with onboard Ethernet such as the Freetronics
EtherTen, EtherMega, and EtherDue.

The output can optionally be switched to 12V which can be useful for
supplying power to external loads such as 12V relays.

Features:

 * Adds 802.3af-compliant Power-over-Ethernet "PD" (powered device)
   support to the Freetronics Ethernet shield and other Freetronics
   boards.
 * Input voltage range 36-57Vdc (nominal 48Vdc for 802.3af PoE)
 * Output voltage regulated to 10V and fed to Arduino on-board voltage
   regulator via Ethernet shield for further regulation down to 5V.
 * Plugs directly onto Freetronics Ethernet Shield and other
   Freetronics boards.
 * "Power on" LED.


More information is available at:

  http://www.superhouse.tv/poereg


INSTALLATION
------------
The design is saved as an EAGLE project. EAGLE PCB design software is
available from www.cadsoftusa.com free for non-commercial use. To use
this project download it and place the directory containing these files
into the "eagle" directory on your computer. Then open EAGLE and
navigate to the project.


DISTRIBUTION
------------
The specific terms of distribution of this project are governed by the
license referenced below.


LICENSE
-------
Licensed under the TAPR Open Hardware License (www.tapr.org/OHL).
The "license" folder within this repository also contains a copy of
this license in plain text format.
