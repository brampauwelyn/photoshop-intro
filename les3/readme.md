# Photoshop Les 3

## 1. Curves

Curves worden vooral gebruikt bij het bewerken van foto's.
Met foto's kan je de kleuren en het contrast van een foto gaan aanpassen.

Open curves.jpg

De snelste manier en makkelijkste manier om de curves van een afbeelding te gaan aanpassen is via:
- Image > Adjustments > curves
- Uiteraard kan je dit menu ook oproepen via de shortcut (ctrl + m)

![Curves](https://cl.ly/3I2L09183g0c/Screen%20Recording%202017-01-22%20at%2004.00%20PM.gif "curves")

Als we werken met curves moeten we aantal zaken vermijden:
- Vermijd platte curves zoals voorbeeld hieronder:

![Curves](https://cl.ly/3s1e0R3q1g3n/Image%202017-01-22%20at%204.06.17%20PM.png "Curves")

- Vermijd "downhill curves"

![Curves](https://cl.ly/3X2l253D2q42/Image%202017-01-22%20at%204.09.24%20PM.png "Curves")

Stel nu dat je de heldere stukken nog meer wil verhelderen.
Dit doe je door de rechterbovenhoek naar links te verslepen.
Als je dit volledig naar links versleept dan krijg je een witte afbeelding. Dit komt eigenlijk omdat je al het zwart uit de afbeelding haalt.

![Curves](https://cl.ly/0y1Y1I3x133E/Screen%20Recording%202017-01-22%20at%2004.16%20PM.gif "Curves")

Omgekeerd stel nu dat je de donkere stukken wil verdonkeren.
Dan doe je dit door de linkeronderhoek naar rechts te verplaatsen.

![Curves](https://cl.ly/0P0w0F1F0G10/Screen%20Recording%202017-01-22%20at%2004.20%20PM.gif "Curves")

Om meer contrast in de afbeelding te brengen gaan we een S-curve maken.
Dit doen we op de volgende manier:

![S curve](https://cl.ly/1W0A1L3e0f06/Screen%20Recording%202017-01-22%20at%2004.33%20PM.gif "S Curve")

Nu hebben de curves aangepast voor alle kleuren (RGB). Je ziet dat de RGB optie geselecteerd staat bij channel. Het toffe aan curves is dat we nu ook de curves kunnen gaan aanpassen per kleur (rood, groen en blauw). Op deze manier kunnen we de foto een volledige andere look geven (bv. vintage look).

![RGB curves](https://cl.ly/0O2d2l463X1g/Screen%20Recording%202017-01-22%20at%2004.46%20PM.gif "RGB curves")

Het nadeel van deze manier van curves maken is dat eenmaal je de curves toepast je deze nadien niet meer kan aanpassen. Dit is dus niet echt handig. Gelukkig kunnen we ook de curves van een afbeelding aanpassen via een adjustment layer. Dit doe je op de volgende manier:

![Adjustment Layer](https://cl.ly/1e1x1r3v2w11/Screen%20Recording%202017-01-22%20at%2005.08%20PM.gif "Curves Adjustment Layer")

## 2 Carnovsky effect

- Open de afbeelding carnovsky.jpg
- Maak een selectie van de achtergrondkleur a.d.h.v. de toverstaf tool (magic wand tool)
- Vervolgens gaan we onze selectie uitbreiden via select > similar.
![Magic Wand Tool](https://cl.ly/1x0D031P173q/Screen%20Recording%202017-02-19%20at%2007.53%20PM.gif 'magic wand tool')
- Vervolgens gaan we onze selectie omkeren want we hebben nu de achtergrond geselecteerd maar we willen uiteindelijk de plant selecteren.
- Dit doen we via select > inverse of via de shortcut (ctrl + shift + i).

![Inverse selection](https://cl.ly/3c3R3f242s0Y/Screen%20Recording%202017-02-19%20at%2007.59%20PM.gif 'inverse selection')

- Vervolgens maken we een kopie van onze Layer (dit kunnen we doen via alt) of rechtermuisknop duplicate layer.
- Daarna selecteren we de bovenste laag en voegen we layer style toe (via fx langsonder in layer panel), we kiezen voor overlay color.
- Zet de blendingmode op vivid light
- Pas het kleur aan naar 00FFFF (blauw)

![](https://cl.ly/0X3h3g1t3R2a/Screen%20Recording%202017-02-19%20at%2008.50%20PM.gif 'blue')

- Groepeer beide lagen (ctrl + g)
- Geef de groep een gepaste naam (bv. blue).
- Kopieer de volledige groep

![](https://cl.ly/1S221H3y3s2d/Screen%20Recording%202017-02-19%20at%2009.15%20PM.gif)

- Pas de color-overlay aan van de 2e groep naar magenta #FF00FF
- Maak opnieuw een nieuwe kopie van deze groep en pas de color overlay van de derde groep aan naar geel #FFFF00

![](https://cl.ly/0j0o2r330K3W/Screen%20Recording%202017-02-19%20at%2009.20%20PM.gif)

- Selecteer alle lagen met de color overlays
- Rechtermuisknop en kies voor 'rasterize layer style'
- En zet de blendingmode voor deze layers op 'Screen'

![](https://cl.ly/2d47402J3q1J/Screen%20Recording%202017-02-19%20at%2009.31%20PM.gif)

- Zet de bovenste 2 lagen op multiply
- Vervolgens kunnen we de groepen 1 per 1 verplaatsen via free transform (ctrl + t)

![](https://cl.ly/1G1t0o3b3N2n/Screen%20Recording%202017-02-19%20at%2009.40%20PM.gif)

Eindresultaat:

![Eindresultaat](https://cl.ly/1r1o3J3Q0T0l/Image%202017-02-19%20at%209.44.09%20PM.png)
