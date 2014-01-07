Crowbar circuit
===============

Purpose
-------
Spitzensparken und blowenfusen!

A crowbar is a circuit that in case of overvoltage on the supply rails will short the supply rails together to reduce the supply voltage close to 0, thereby blowing the fuse(s) and thus disabling the output.

All three outputs of this power supply (+5V, +15V, -15V) will be protected by crowbar circuits. These crowbar circuits will have an output to the microcontroller indicating whether they fired recently.

Operation
---------

BOM
---
==============================================  ======  ======= ================================================================================
What                                            Amount  Price € Link
==============================================  ======  ======= ================================================================================
TVS-Diode for good measure                      4       0.17    https://secure.reichelt.de/Ueberspannungs-schutzdioden/P6KE-6-8CA/3//index.html?ACTION=3&GROUPID=3000&ARTICLE=42018&SHOW=1&OFFSET=500&
MOSFET 162A IRF1404                             4       0.96    https://secure.reichelt.de/IRC-IRF-Transistoren/IRF-1404/3//index.html?ACTION=3&GROUPID=2891&ARTICLE=41598&SEARCH=mosfet&SHOW=1&OFFSET=500&
Bandgap-Spannungsreferenz 2.5V LT 1004          1       1.95    https://secure.reichelt.de/ICs-LT-LTC-/LT-1004-CZ-2-5/3//index.html?ACTION=3&GROUPID=2913&ARTICLE=10855&SEARCH=spannungsreferenz&SHOW=1&OFFSET=500&
2-fach Komparator LM293                         2       0.28    https://secure.reichelt.de/ICs-LM-10-LM-999/LM-293-DIP/3//index.html?ACTION=3&GROUPID=5464&ARTICLE=10439&SEARCH=komparator&SHOW=1&OFFSET=500&
----------------------------------------------  ------  ------- --------------------------------------------------------------------------------
Total                                           
==============================================  ======  ======= ================================================================================
