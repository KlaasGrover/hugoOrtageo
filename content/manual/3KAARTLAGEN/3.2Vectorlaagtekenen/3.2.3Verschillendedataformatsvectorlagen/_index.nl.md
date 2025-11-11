---



title: "3.2.3 Verschillende data formats vectorlagen"



date: 2025-11-10



draft: false    



---



Wanneer je een vectorlaag opslaat in QGIS, kun je kiezen uit verschillende bestandsformaten, waarvan de Shapefile en GeoPackage de meest voorkomende zijn. Het Shapefile-formaat is ontwikkeld door ESRI en is een van de oudste en meest gebruikte vectorformaten. Een Shapefile bestaat uit meerdere bestanden met dezelfde naam, maar verschillende extensies, zoals .shp, .shx, en .dbf, die samenwerken om de ruimtelijke en attributieve informatie op te slaan. Hoewel Shapefiles breed compatibel zijn met andere GIS-software, hebben ze ook enkele beperkingen. Ze ondersteunen bijvoorbeeld geen complexe gegevens zoals geavanceerde geometrieën of topologie, zijn beperkt tot maximaal 2 GB aan gegevens per bestand, en attributennamen zijn beperkt tot 10 tekens.



Aan de andere kant is GeoPackage een nieuwer open standaardformaat, ontwikkeld door de Open Geospatial Consortium (OGC). In tegenstelling tot een Shapefile bestaat een GeoPackage uit slechts één bestand met de extensie .gpkg. Dit formaat ondersteunt zowel vector- als rastergegevens in hetzelfde bestand en heeft geen limiet op de bestandsgrootte, behalve wat het bestandssysteem toestaat.



**Belangrijk!** Binnen Ortageo hebben we besloten om met shapefiles te werken om zo een eenduidige data structuur aan te houden. Daarnaast werken veel van onze opdrachtgevers / klanten ook met shapefiles. Probeer daarom zoveel mogelijk met shapefiles te werken.

&nbsp;

