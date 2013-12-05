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
High current relay (5V)                         1       5       https://secure.reichelt.de/Miniaturrelais/FRC6BA-1-DC12V/3/index.html?ACTION=3&LA=2&ARTICLE=127021&GROUPID=3292&artnr=FRC6BA-1-DC12V
15V relays                                      2       4       https://secure.reichelt.de/Miniaturrelais/G6K-2P-5V/3/index.html?ACTION=3&LA=2&ARTICLE=28335&GROUPID=3292&artnr=G6K-2P+5V
Anschlussklemmen 5V 10/11p gegen Verwechselung  2       5       http://www.conrad.de/ce/de/product/731966/Steckbare-Schraubklemme-mit-Liftprinzip-AKZ1550-Gruen-PTR-51550100025D-Inhalt-1-St?ref=list http://www.conrad.de/ce/ProductDetail.html?ref=list&productcode=732165&productname=Vertikale-Stiftleiste-Serie-STLZ1550-V-Rastermass-381-mm-Polzahl-10-Gruen-PTR-51550105125D-Inhalt-1-St&categorycode=SHOP_AREA_88126
Anschlussklemmen 15V 4pol                       1       3
Dickes Kupferkabel (16mm²)                      2m      4/m     http://www.conrad.de/ce/de/product/607441/NYM-J-Installationskabel-1-x-16-mm-Grau-Meterware-LappKabel?ref=list
Litze 2.5mm² als Verbindung nach oben           25m     11      https://secure.reichelt.de/Fahrzeugleitung/FLK-2-5-SW-25/3/index.html?ACTION=3&LA=2&ARTICLE=31793&GROUPID=5349&artnr=FLK+2%2C5+SW-25
Gewebe-Kabelschlauch                            2m      3/m     http://www.conrad.de/ce/de/product/543042/Helagaine-Geflechtschlauch-HEGPV0X-Buendelbereich-6-19-mm-HEGPV0X12-PBT-BK-C4HellermannTyton-Inhalt-Meterware?ref=searchDetail
Einbau-Sicherungshalter                         1       5       http://www.conrad.de/ce/de/product/379701/SINUSLIVE-MINI-ANL-SICHERUNGSH-SH-150
Sicherungen 60A tendenziell eher träge          3       2       http://www.conrad.de/ce/de/product/379707/
Alternativ: Sicherungsautomat 3*20A             0       25      https://secure.reichelt.de/Sicherungstechnik/EL-LS3CO-C-20A/3/index.html?ACTION=3&LA=2&ARTICLE=52703&GROUPID=3388&artnr=EL+LS3CO+C+20A
Einbau-Schmelzsicherungshalter                  2       1.5     https://secure.reichelt.de/Sicherungshalter/PL-FPG2-40/3/index.html?ACTION=3&LA=446&ARTICLE=53021&GROUPID=3308&artnr=PL+FPG2-40&SEARCH=sicherung+halter+schraub
Schmelzsicherungen 500mA Mittelträge            10      1/10pcs https://secure.reichelt.de/5x20mm-Feinsicherungen/MTR-0-5A/3/index.html?ACTION=3&LA=446&ARTICLE=13234&GROUPID=3301&artnr=MTR.+0%2C5A&SEARCH=MITTELTR%C4GE+0%2C5A
Crowbar (siehe ``crowbar.rst``)                 2
Stellaris Launchpad
Klebe-Platinenhalter
----------------------------------------------  ------  ------- --------------------------------------------------------------------------------
**Gesamt**                                              200
==============================================  ======  ======= ================================================================================

.. _AfRA: http://afra-berlin.de
