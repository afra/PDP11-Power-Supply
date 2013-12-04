PDP-11 Power Supply 
===================

Objective
---------

At AfRA_, we have a PDP-11/34A in pretty good condition, but since we are missing its power supply, we are unable to power it up and have fun with it. This state of affairs ought to be changed, so we set out build a power supply.

Specs
-----
+5V @ 50A; ±15V @ 500mA

- Full digital supervision of output voltages and currents
- Digital control of outputs (on/off)
- Analog output current display on front panel for good measure
- Electronic *and* regular fuses on all outputs
- Crowbar circuits on all outputs

Bill of Materials
-----------------

==============================================  ======  ======= ================================================================================
What                                            Count   Price € Link
==============================================  ======  ======= ================================================================================
Anzeigelämpchen                                 2       2       http://www.conrad.biz/ce/de/product/703910/Meldeleuchte-230-VAC-Serie-1800-230-VAC-18071108-Meldeleuchte-Gruen
Anzeigelämpchen                                 2       2       http://www.conrad.biz/ce/de/product/703897/Meldeleuchte-230-VAC-Serie-1800-230-VAC-18071102-Meldeleuchte-Rot
Schaltnetzteil 5V/60A (300W)                    1       90      https://secure.reichelt.de/Schaltnetzteile-Case-geschlossen/SNT-HRPG-300-5/3/index.html?ACTION=3&LA=5&ARTICLE=108276&GROUPID=4959&artnr=SNT+HRPG+300+5
19"-Rackgehäuse                                 1       45      http://www.thomann.de/de/adam_hall_87408_gehaeuse_2he.htm
Stromwandler 60A                                1       14      http://www.digikey.com/product-detail/en/L18P060S05/MT7362-ND/3048507
Alternativer Stromwandler (50A)                 0       7       http://www.digikey.com/product-detail/en/ACS756KCA-050B-PFF-T/620-1239-ND/1829842
Boost converter (für 5V->15V)                   1       4       http://www.amazon.de/LM2577-Step-Up-3-5-30V-Converter-Regulator/dp/B00D8V4ATA/ref=sr_1_2?ie=UTF8&qid=1386155677&sr=8-2&keywords=step+up+converter
Buck converter (für 5V->-15V)                   1       13      http://www.amazon.de/MW-LM2596-Converter-Module-1-23V-30V/dp/B00CVP4WJ2/ref=sr_1_2?ie=UTF8&qid=1386156155&sr=8-2&keywords=buck+converter
Einbaudrehspulmesswerk für Stromanzeige         2       5       http://www.conrad.de/ce/de/product/108467/VOLTCRAFT-72x72-15V-Analog-Einbauinstrument-72-15-V-Drehspule?ref=searchDetail
High current solid state relay (5V)
Low current solid state relay (15V)
Lüsterklemmen
Dickes Kupferkabel
Einbau-Flachsicherungshalter
Flachsicherungen 60A Träge
Einbau-Schmelzsicherungshalter
Schmelzsicherungen 500mA Träge
Crowbar (siehe ``crowbar.rst``)                 2
Anschlussklemmen                                2
XLR-Stecker, Buchse für ±15V
Stellaris Launchpad
Klebe-Platinenhalter
----------------------------------------------  ------  ------- --------------------------------------------------------------------------------
**Gesamt**                                              200
==============================================  ======  ======= ================================================================================

.. _AfRA: http://afra-berlin.de
