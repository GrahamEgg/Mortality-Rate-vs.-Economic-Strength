# Mortality-Rate-vs.-Economic-Strength

Omschrijving:
--
In bijgevoegd Dashboard met bovenstaande als titel, wordt doormiddel van het gebruik van Bruto Binnenlands Product per inwoner (weergegeven in Dashboard als GDP per capita) en het percentage van kans op overlijden, het verband tussen de kans op overlijdensrisico aan hart- en vaatziekten, kanker en de welvaart van een land weergegeven. Dit verband wordt onder andere weergeven door een *bar chart* en door een *shape map*. Doormiddel van een *slicer* is het mogelijkheid om te filteren tussen continenten, eveneens als de verschillende jaartallen. Ook wordt het verschil weergeven tussen het overlijdensrisico in de armste landen versus de rijkste landen.

Navigatiegids en Dashboardfunctie:
--
In het midden is een wereldkaart weergeven, hierin is het mogelijk om een specifiek land naar keuze aan te klikken. Deze leid vervolgens tot informatie over dat land. Beneden is een *slicer*, waarbij het mogelijk is om naar een specifiek jaartal te gaan en/of om bredere informatie te ontvangen van een geheel continent. Links in het Dashboard wordt vervolgens de GDP per capita van hoog naar laag getoont wanneer een continent en/of land is aangeklikt, ook is het mogelijk om direct gegevens van het hoogste en laagste land te kunnen inzien. Rechts wordt een inzicht gegeven van het percentage van beide geslachten en het gemiddelde van deze geslachten samen.
De home knop brengt je terug naar het begin overzicht. 


Datatransformatie:
--
Transformatie voor het aanmaken van de Percentage Column:
Deze transformatie is bedoeld om een nieuwe kolom toe te voegen die het percentage weergeeft. Deze aanpassing is essentieel om een correcte visualisatie te kunnen genereren.

Transformatie om de Data op te splitsen op basis van Mortality Rate:

Voer deze transformatie uit om de data te categoriseren in twee groepen: 
één groep met een mortaliteitspercentage boven de 25% en de andere groep met een percentage onder de 25%. Dit is van belang voor het identificeren van verschillen in mortaliteit en het leggen van verband met gdp per capita.

Data transformatie van GDP per Capita om de data in te delen in drie groepen:
deze transformatie om de GDP per Capita data te verdelen in drie categorieën:
Onder 20 duizend
Tussen 20 duizend en 40 duizend
Boven 40 duizend


Navigatie
--
Aan de bovenkant van de pagina's bevinden zich verschillende knoppen die je helpen bij het navigeren door de verschillende pagina's en slicers. Deze worden hieronder omschreven:

De home Button:
Deze knop brengt je direct terug naar de homepagina. Handig als je snel wilt navigeren naar het beginpunt.

De menu Button (pagina 2 - 3):
Door op deze knop te klikken, opent zich het slicer-menu. Hiermee kun je specifieke opties selecteren of jaartal of continent aanpassen.

Het slicer-menu zelf heeft ook een aantal knoppen(de 3 stripjes onder elkaar):

De kruis Button:
Gebruik deze knop om het slicer-menu te sluiten. Handig als je klaar bent met het aanpassen van instellingen.

De reset Button:
De resetknop zorgt ervoor dat alle slicers terugkeren naar hun oorspronkelijke standpunten, waardoor je een frisse start hebt met de instellingen.
Deze navigatie-elementen maken het gemakkelijk om door de pagina's te manoeuvreren en de slicers naar wens aan te passen.

Volgende en Vorige Button:
Met deze knoppen kun je eenvoudig naar de volgende of vorige pagina navigeren. 






Bronnen 
--
https://www.imf.org/external/datamapper/NGDP_RPCH@WEO/OEMDC/ADVEC/WEOWORLD

https://www.kaggle.com-datasets-utkarshxy-who

https://www.kaggle.com/datasets/andradaolteanu/country-mapping-iso-continent-region
