Hier vind je de uitleg rond de scripts.

.. contents :: Overzicht
.. sectnum ::

`Sterrenwacht_programma.ssc`:
----------------------------

Dit script bestaat uit twee grote blokken:

#. het eerste deel is een oneindige lus waarin een reeks verschijnselen op datum via de nieuwe functies worden aangeroepen, telkens met een pauze en uitleg. Illustreert het gebruik van de functies. Maakt onder meer gebruik van de huidige maanfase om afwisseling te brengen in het programma.
#. het tweede deel bevat 5 functies die je in je eigen scripts kan gebruiken:

   - `toonSterrenbeeld()` - inzoomen op een sterrenbeeld
   - `toonObject()` - inzoomen op een object
   - `startRotation()` - ga naar een punt in de tijd
   - `getMaanFase()` - hulpfuctie, berekent de fase van de Maan (NM=1/EK=2/VM=3/LK=4) ifv datum (2020, bevat mogelijk nog een bug)
   - `toonHelp()` - hulpfunctie, voornamelijk bedoeld voor full domes (bv. Urania) (tekst wordt in de linker bovenhoek getoond maar verschijnt niet op de full dome)

`Full_Dome_Settings.ssc`:
-------------------------------------------

Deze script is specifiek voor Urania en stelt Stellarium in op Fisheye mode e.d.


Zie ook
-------

- Stellarium User Guide (SUG) - Part III - 16. Scripting
- http://stellarium.org/en/docs.html
- http://stellarium.org/doc/head/scripting.html

