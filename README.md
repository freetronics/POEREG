Power-over-Ethernet 802.3af Regulator
=====================================

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


More information at:

  http://www.freetronics.com.au/poereg


Hardware
--------
The "Hardware" directory contains the PCB design as an EAGLE project.
EAGLE PCB design software is available from Autodesk free for
non-commercial use.


Credits
-------
  * Jonathan Oxer <jon@oxer.com.au>


License
-------
Copyright 2010-2021 Freetronics Pty Ltd www.freetronics.com

The hardware portion of this project is licensed under the TAPR Open
Hardware License (www.tapr.org/OHL). The "license" folder within this
repository also contains a copy of this license in plain text format.

The software portion of this project is licensed under the Simplified
BSD License. The "licence" folder within this project contains a
copy of this license in plain text format.
