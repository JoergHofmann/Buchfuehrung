$(startbilanz("01." .. Monat[StartMonat].MM .. "." .. Jahr, "2.414.721,00"))
$(AV()) $(TC()) $(EK())
$(aktiva("0027 EDV-Software", "6.400,00")) $(TC()) $(passiva("0870 Einlage " .. GesA , "657.442,00"))
$(aktiva("0085 Grundstücke", "610.000,00")) $(TC()) $(passiva("0871 Einlage " .. GesB, "821.269,00"))
$(aktiva("0090 Gebäude", "1.545.000,00")) $(TC()) $(PHleer())
$(aktiva("0210 TA/Maschinen", "10.620,00")) $(TC()) $(FK())
$(aktiva("0440 Werkzeuge", "8.500,00")) $(TC()) $(passiva("0650 Hypothek CoBa", "830.960,00"))
$(aktiva("0320 Fuhrpark", "96.801,00")) $(TC()) $(passiva("0640 Darlehen Volksbank", "65.000,00"))
$(aktiva("0425 IT-Technik", "26.670,00")) $(TC()) $(passiva("1600 Verbindlichkeiten LuL", "40.050,00"))
$(aktiva("0490 Sonstige BGA", "61.660,00")) $(TC()) $(PHbnase())
$(PHleer())$(ASleer()) $(TC()) $(PHleer())
$(UV()) $(TC()) $(PHleer())
$(aktiva("3970 Bestand Rohstoffe", "11.030,00")) $(TC()) $(PHleer())
$(aktiva("3971 Bestand Hilfsstoffe", "7.840,00")) $(TC()) $(PHleer())
$(aktiva("1000 Kasse", "1.150,00")) $(TC()) $(PHleer())
$(aktiva("1210 Giro Volksbank 1161", "21.500,00")) $(TC()) $(PHleer())
$(aktiva("1220 Giro Commerzbank 100", "7.550,00")) $(TC()) $(PHleer())
$(stopbilanz())

## Offene Posten am 01. $(Monat[StartMonat].MMMM) $(Jahr)

Die Verbindlichkeiten teilen sich wie folgt auf:$(br)$(br)

------------------------------------------------------   ----------------------------   --------------------
Frau Rauscher IT-Technik GmbH                            ReNr 884753                               34.670,00

F. Stoltze e.K.                                          ReNr 647890                                5.380,00

 \

                                                                                                 **40.050,00**
------------------------------------------------------   ----------------------------   --------------------


## Bankkonten

-------   --------------------------------   -----------------------------------   -------------------------
0640      Darlehen Volksbank                 #234 198 417                                         65.000,00H
0650      Hypothek Commerzbank               #876 345 222                                        830.960,00H
1210      Giro Volksbank                     #654 332 1161                                        21.500,00S
1220      Giro Commerzbank                   #445 332 100                                          7.550,00S
-------   --------------------------------   -----------------------------------   -------------------------

