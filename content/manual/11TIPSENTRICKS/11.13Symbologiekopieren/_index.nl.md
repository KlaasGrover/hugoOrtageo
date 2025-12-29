---

title: "NIEUW 11.13 Symbologie kopiëren"

date: 2025-12-29

draft: false 

weight: 130      

---





Wanneer je b.v. een nieuwe boorpuntenlaag aanmaakt of een boorpuntenlaag in QGIS inlaadt, kun je de symbologie van een bestaande boorpuntenlaag overzetten. Dit bespaart tijd, vooral als er veel verschillende symbologieën zijn ingesteld.



**Belangrijk:** QGIS kent symbolen toe op basis van attribuutwaarden. Bij het overbrengen van symbologie moeten de attributen die voor de weergave worden gebruikt ook in de nieuwe laag aanwezig zijn en dezelfde veldnaam en hetzelfde gegevenstype hebben. De overige attributen zijn daarvoor niet relevant.



Stappen in QGIS 3.2:



<div style="margin-left: 1em;">

* Rechtsklik op de laag met de gewenste stijl > Stijl > Kopieer stijl > Alle stijlcategorieën
* Rechtsklik op de nieuwe laag > Stijl > Plak stijl > Alle stijlcategorieën

</div>

&nbsp;

**Tip:** Als je regelmatig nieuwe boorpuntenlagen toevoegt met dezelfde stijl, kan het handig zijn om de stijl van de originele laag op te slaan als .qml bestand: 



<div style="margin-left: 1em;">



* Rechtsklik op de laag met de gewenste stijl >  Laageigenschappen > Symbologie > Stijl (linksonder) > Stijl opslaan > Opslaan als: QML bestand; voer een bestandsnaam in > OK

</div>



Dit bestand kan later opnieuw worden geladen in QGIS, zelfs in andere projecten: 



<div style="margin-left: 1em;">



* Rechtsklik op de nieuwe laag > Laageigenschappen > Symbologie > Stijl (linksonder) > Stijl laden > kies QML-bestand > Stijl laden

</div>



