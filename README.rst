===========================================
Stellarium scripting binnen de sterrenwacht
===========================================

.. contents:: Overzicht
.. sectnum::

Dit is een eerste versie van Koen Geuken's Stellarium scripts.

Deze scripts laten toe om een presentatie in Stellarium op een eenvoudige manier te programmeren.


Gebruik
+++++++

#. desgewenst, volg de instructies om ENTER en/of PG UP te kunnen gebruiken om door de script te stappen
#. in Stellarium, druk F12 om de "script console" dialoog te openen
#. open het script "`Stellarium_V_20200102.ssc`" (icoontje linksboven)
#. klik op het start icoontje ("run script") rechtsboven

Bestanden
+++++++++

Momenteel vind je volgende bestanden die je kan gebruiken ter inspiratie.

`Documentatie_Functies.docx`:
-----------------------------

Legt uit hoe de functies moeten worden aangeroepen.

`Stellarium_Setup_ENTER to continue script.docx`:
-------------------------------------------------

Hoe ervoor te zorgen dat je ENTER of een muis-presenter kan gebruiken om vooruit te stappen in je script.

`Stellarium_V_20200102.ssc`:
----------------------------

Dit script bestaat uit twee grote blokken:

#. het eerste deel is een oneindige lus waarin een reeks verschijnselen op datum via de nieuwe functies worden aangeroepen, telkens met een pauze en uitleg. Illustreert het gebruik van de functies. Maakt onder meer gebruik van de huidige maanfase om afwisseling te brengen in het programma.
#. het tweede deel bevat 5 functies die je in je eigen scripts kan gebruiken:

   - `toonSterrenbeeld()` - inzoomen op een sterrenbeeld
   - `toonObject()` - inzoomen op een object
   - `startRotation()` - ga naar een punt in de tijd
   - `getMaanFase()` - hulpfuctie, berekent de fase van de Maan (NM=1/EK=2/VM=3/LK=4) ifv datum (2020, bevat mogelijk nog een bug)
   - `toonHelp()` - hulpfunctie, voornamelijk bedoeld voor full domes (bv. Urania) (tekst wordt in de linker bovenhoek getoond maar verschijnt niet op de full dome)

`Stellarium_Script_Full Dome_Settings.ssc`:
-------------------------------------------

Deze script is specifiek voor Urania en stelt Stellarium in op Fisheye mode e.d.

Zie ook
+++++++


- Stellarium User Guid (SUG) - Part III - 16. Scripting
- http://stellarium.org/en/docs.html
- http://stellarium.org/doc/head/scripting.html

