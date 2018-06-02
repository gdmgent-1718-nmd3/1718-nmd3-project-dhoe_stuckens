---
layout   : default
permalink: design/smartphone-app/wireflow/
published: true
# Custom Page Variables
# ─────────────────────
title: Wireflow
---

<img src="{{ '/assets/img/Wireflow_App1.png' | relative_url }}" title="Wireflow Applicatie">

**legende/kleurcode**

<img id="kleurcode" src="{{ '/assets/img/Wireflow_kleurcode_01.png' | relative_url }}" title="Wireflow Applicatie">
Dropdown menu<br>
<img id="kleurcode" src="{{ '/assets/img/Wireflow_kleurcode_02.png' | relative_url }}" title="Wireflow Applicatie">
Hoofdnavigatie<br>
<img id="kleurcode" src="{{ '/assets/img/Wireflow_kleurcode_03.png' | relative_url }}" title="Wireflow Applicatie">
Navigatie tussen verschillende pagina's en detailpagina's<br>

### Detail 1
---------
<img src="{{ '/assets/img/Wireflow_App_detail1.png' | relative_url }}" title="Wireflow detail 1">
**0.0 Index**  
De gebruiker kan naar beneden scrollen waar alle hoofdpagina's staan afgebeeld. Bij het drukken op een afbeelding of tekst gaat de gebruiker naar de betreffende pagina.  
De bezoeker kan ook op elke pagina het dropdown menu openen en krijgt daar een verkorte versie van de navigatie. Bij het drukken op de tekst navigeert de gebruiker naar de betreffende pagina.  
De navigatie blijft bovenaan de pagina staan bij het scrollen.  
De gebruiker kan op de CTA 'Tickets Aankopen' klikken en wordt onmiddellijk doorverwezen naar __6.0 Cart__ waar al reeds één ticket in staat.  

**1.0Events**  
De CTA 'Koop je evenement ticket' leidt naar __6.0 Cart__ waar al één ticket bij aankopen staat aangeduidt.  
Als de bezoeker naar beneden scrolt vindt hij andere eventen die plaats vinden met bijkomende uitleg en een CTA om een ticket aan te kopen die leidt naar __6.0 Cart__.  

**2.0 De Hallen**  
De gebruiker kan naar de detailpagina van een bepaalde hall navigeren. Daarin wordt de inhoud van de betreffende hall meer uitgelegd, zowel visueel als met tekst.  

**2.x De hallen - detailpagina**  
De Scan QR-knop opent de camera applicatie van de iPhone om de code in te scannen. Na het inscannen keert het terug naar de detailpagina waar de QR-code thuis hoort.  
vb: je opent de detailpagina __2.1 de hallen - hall 1__ maar je bevindt je in hall 3 waar je een QR-code scant. Na het succesvol inscannen van die code word je naar de detailpagina van hall 3 genavigeerd.  
Als de gebruiker een account heeft aangemaakt worden hierin de opgeslagen data (beeld, audio, tekst) bewaard. Deze pagina's zijn dus ook te bereiken via __5.0 account__

### Detail 2
---------
<img src="{{ '/assets/img/Wireflow_App_detail2.png' | relative_url }}" title="Wireflow detail 2">

**3.0 Interactie**
De Scan QR-knop opent de camera applicatie van de iPhone om de code in te scannen. Na het inscannen keert het terug naar de detailpagina waar de QR-code thuis hoort.  
vb: je opent __3.0 Interactie__ maar je bevindt je in hall 3 waar je een QR-code scant. Na het succesvol inscannen van die code word je naar de detailpagina van hall 3 genavigeerd.  
Bij het naderen van een NFC-tag komt er een pop-up op het scherm - ook bij de smartwatch- dat er een NFC-tag in de buurt is waar je extra informatie kan vinden.  

**4.0 Boutique**
De CTA om een toegangsticket aan te kopen leidt naar __6.0 Cart__.  
In de Boutique zijn de mogelijk aankopen uit de museumshop onderverdeeld in verschillende categorieën (albums, t-shirts, ...). Deze hebben allemaal een detailpagina waar je een specifieke aankoop kan selecteren.  

### Detail 3
---------
<img src="{{ '/assets/img/Wireflow_App_detail3.png' | relative_url }}" title="Wireflow detail 3">

**5.0 Account**
Vanuit de account pagina is het mogelijk om je opgeslagen data te bekijken door te navigeren naar de betreffende detailpagina van de hallen.  
Hierin staan ook de persoonlijke gegevens van de gebruiker en heeft hij de mogelijkheid deze aan te passen.  
Deze pagina in de app wordt niet bereikt als de gebruiker niet ingelogd of als hij nog geen account heeft aangemaakt.  
Als de gebruiker nog geen account heeft leidt deze pagina naar __5.1 Sign Up__. Na het registeren komt de gebruiker op zijn accountpagina terecht.  
Als de gebruiker is uitgelogd leidt deze pagina naar __5.2 Sign In__. Na het inloggen komt de gebruiker op zijn accountpagina terecht.  


**6.0 Cart**
Bovenaan staat de CTA om een toegangsticket aan te kopen. Wordt deze CTA ingedrukt komt er, als er al reeds aankopen zijn, een ticket bij de bestelling.  
De betaal-knop leidt naar Apple Pay als de gebruiker Apple Pay heeft ingesteld op zijn Smartphone. Zoniet wordt de gebruiker geleidt naar een externe, beveiligde betaalpagina.  

**7.0 Contact & Informatie**
Op deze pagina zijn openingsuren, adres en google maps afbeelding te vinden.

**8.0 Settings**
Hier is het mogelijk om settings zoals mail ontvangen, bluetooth uitschakelen, notificaties uitschakelen, ... aan of uit te zetten. Deze settings pagina is enkel te vinden op de smartphone app en enkel te bereiken via de __0.0 Index__

### Gebruikerstest op Wireflow-niveau
---------
Onze gebruiker vond de app op vele vlakken goed, duidelijk en intiutief aanvoelen. De bij pagina __1.0 Events__ zou zij nog een detailpagina aanmaken om meer informatie aan te bieden bij de volgende evenemtenten.  
Na overleg keurden wij dit idee goed en zouden wij in de visuals een detailpagina aanmaken. Dit werd dan ook toegevoegd in de sitemap.  
Onze testgebruiker vond de aanwezigheid van de CTA's iets teveel. Niet elke pagina moet je 'dwingen' om een ticket aan te kopen op de app. Een logische redenering vonden wij, de gebruikers zouden inmiddels de app al gedownload hebben en waarschijnlijk interesse tonen in een bezoek. Wij zouden de CTA's om een toegangsticket aan te kopen beperken tot enkel de __0.0 Index__ en de __4.0 Boutique__
De gebruiker vond ook dat de speelsere layout van de knoppen op de papieren wireflows, waarbij de afbeelding en tekst elkaar zou afwisselen, veel beter dan de layout van tekst en knoppen op de digitale wireframes. Dit is een opmerking naar layout toe, maar wel één die we omarmen.