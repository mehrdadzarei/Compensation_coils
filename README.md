# Compensation_coils

All required schemes, software, and fabrication files for PCB design and manufacturing of a compensation coils current controller (3x03A).
|
Project is in another repos (`here`_)

.. _here: https://repod.icm.edu.pl/dataset.xhtml?persistentId=doi:10.18150/YHSPTP
|
The presented device can be programmed by the Ethernet connection over Telnet protocol. Programming allows presetting in memory 32 values of the current on each of the currents. Fast addressing and setting the output values is made by TTL signals (five addressing bits and one clock/set bit). The output in the range of -3 A to 3 A is provided by 16 bits analog-digital converter. The stability of the output is provided by the ultralow noise internal voltage reference. Additionally, an arbitrary length linear ramp can be programmed, triggered by a clock/set TTL.
