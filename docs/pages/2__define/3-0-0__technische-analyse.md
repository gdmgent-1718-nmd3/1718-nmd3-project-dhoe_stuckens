---
layout   : default
permalink: define/technische-analyse/
published: true
# Custom Page Variables
# ─────────────────────
title: Technische Analyse
---
<br>
Wij kiezen voor dit project voor de Apple producten: Apple Watch en Iphone. Deze producten zijn wijdverspreid en hebben door ApplePay een extra troef die we kunnen integreren.  
Verder zijn Apple producten zeer betrouwbaar en dankbaar om een app voor te ontwikkelen.

## [Smartwatch: Apple Watch](https://developer.apple.com/watchos/human-interface-guidelines/overview/themes/ "Apple Watch OS Design Sheets"){:target="_blank"}
<br>
### Kenmerken
---------

- **Lightweight Interactions**
- **Hollistic Design**
- **Personal Communication**
- **Glanceable**
- **Actionable**
- **Responsiveness**

### Technische mogelijkheden
---------
#### Operating system
- watchOS 4

#### Navigation
- Capacitive touch (tap, swipe)
- Force touch (press)
- Digital crown (scroll, zoom, home, time, accessibility, Siri)
- Button (Friends, Apple Pay, power)

#### Sensors
_Series 1_
- Ambient light
- Accelerometer
- Gyroscope
- Heart rate

_Series 3_
- Ambient light
- Accelerometer
- Gyroscope
- GPS
- GLONASS
- Heart rate
- Barometric altimeter

#### Connectivity
_Series 1_
- Bluetooth 4.0 Low Energy (LE)
- Wi-Fi 802.11b/g/n 2.4GHz (system use only)

_Series 3_
- Bluetooth 4.2
- Wi-Fi 802.11b/g/n 2.4 GHz
- Cellular (LTE and UMTS)
- Battery life
- 18 hours
- 3 hours talk time
- 6.5 hours audio playback
- 6.5 hours workout use
- 48 hours time check
- 72 hours power reserve (time only)

#### Inductive charging time
- 1.5 hours to 80%
- 2.5 hours to 100%

#### Water resistance
_Series 1_
- IPX7 under IEC standard 60529

_Series 3_
- 50 meters under ISO standard 22810:2010

#### Processors
_Series 1_
- Apple S1 computer-on-a-chip

_Series 3_
- W2 chip and faster dual-core processor

#### Storage
- 8 GB total
- 2 GB for music
- 75 MB for photos

#### Display sizes
- 38mm: 340 &times; 272 px
- 42mm: 390 &times; 312 px
<br>

### Systeembekwaamheid
---------
#### Apple Pay
Apple Pay is een veilig en makkelijke manier om betalingen af te ronden voor diensten en goederen binnen de iOS en de watchOS apps. Gebruikers authoriseren betalingen door de door hun gekozen beveilingsmodus te activeren.

_De betaalknop_<br>
De betaalknop begint het process om de goederen of diensten af te rekenen met Apple Pay. Het logo van Apple Pay kan worden vergroot of verkleint naar keuze, en geschikt voor de inhoud van jouw app.

Apple Pay mag niet worden aangekondigd als deze niet beschikbaar is op de app. Bijkomstig, als de gebruiker Apple Pay niet heeft geïnstalleerd mag er ook geen betaalknop worden weergegeven in de app.

voor specifieke ontwerprichtlijnen in verband met Apple Pay: [WKInterfacePaymentButton](https://developer.apple.com/documentation/watchkit/wkinterfacepaymentbutton "Ontwerprichtlijnen bij Apple Pay")


#### Handoff
Apple Watch helpt gebruikers om informatie snel te bekijken, maar meer dan niet, wil de gebruiker ook dieper in de content graven op andere Apple devices. De watchOS app gebruikt hierbij Handoff om informatie van de gebruiker zijn laatste handelingen op andere Apple devices over te brengen.

Handoff wordt opgestart door naar boven te swipen op het lock screen van het apparaat. Het gebruikt de informatie van de Apple Watch om de informatie op een andere device te openen.

#### Notificaties
Notificaties op een Apple watch communiceert met de gebruiker door snelle interacties. Deze interacties vinden plaats in twee stadia: de short look en de long look.

- **Short Look**
Short looks verschijnen heel kort op het scherm, dit geeft de gebruiker genoeg tijd om te zien welke notificatie hij heeft ontvangen en welke app deze verstuurd heeft.<br>De ruimte beschikbaar voor titels is vrij beperkt dus houdt ze kort en makkelijk verstaanbaar. Extra informatie kan in de body van de notificatie worden geplaatst.<br>Privacy is een belangrijk gegeven bij Short Looks. Ze zijn dan ook bedoeld om discreet basisinformatie over de notificatie weer te geven. De developer moet dus rekening houden dat er geen gevoelige informatie in de titel kan sluipen.

- **Long Look**
Long Looks geven meer informatie over de notificatie. Deze Long look wordt geactiveerd wanneer de gebruiker van de Apple Watch zijn pols omhoog houdt of wanneer de gebruiker het touchscreen gebruikt om de Short Look te activeren.<br>Bij het neerlaten van de arm wordt de Long Look onmiddellijk gedeactiveerd.<br>Een Long Look komt in twee versies: een statische en een dynamische.<br>De statische interface geeft naast het notificatiebericht ook text en beeld weer. Terwijl de dynamisch interface, en zijn naam doet het al vermoeden, de gebruiker toegang geeft tot de volledige inhoud van het bericht en zelf opties kan bieden om een bericht te beantwoorden of de look aan te passen.

Het gebied van zowel de statische en dynamische Long Look is volledig aanpasbaar, houd hierbij wel rekening dat de structuur van de interface niet aangepast kan worden. Bovenaan bevindt zich de sash, app icoon en naam. De kleur en uitzicht van de sash kan worden aangepast. Custom Knoppen, maximaal vier, voor op maat gemaakte acties komen onder het content gebied. Onder de eigen ontworpen knoppen plaats het OS altijd een _'Dismiss'_ knop.

Voorzie bij de Long Look altijd een statische en een optionele dynamische interface.

#### SpriteKit and SceneKit
Deze Kits zorgen ervoor dat je als developer zelfontworpen UI elementen in je app of notificatie interface kan plaatsen.
SpriteKit voorziet grafische rendering en animatie infrastructuur voor de opbouw van beelden.
SceneKit voorziet een gelijkaardige infrastructuur voor 3D content.
Hierdoor wordt het mogelijk om de ervaring voor de gebruikers te verijken.

### Ontwerprichtlijnen
---------
De Apple Watch is in alle uitvoeringen beschikbaar in twee verschillende maten: 38mm of 42mm.  
Deze groottes werden officieel door Apple bepaalt aan de lengte van het apparaat. Bij benadering heeft de kleinere Apple Watch een beeldscherm van 38mm bij 32mm breed. De grote Apple Watch heeft een beeldscherm van 42mm lang en 36mm breed.  
Beide formaten hebben een Retina-beeldscherm. Dit wil zeggen dat, op een normale kijkafstand, de gebruiker geen pixels kan waarnemen.  
De 38mm versie heeft een horizontale beeldresolutie van 272px en een verticale beeldresolutie van 340px.  
de 42mm versie heeft een horizontale beeldresolutie van 312px en een verticale beeldresolutie van 390px.  


### Conlusie Smartwatch
---------
Het belangrijkste dat de smartwatch voor ons kan betekenen is de Handoff. Hierdoor kan de gebruiker snel en efficiënt de notificaties en andere info bekijken zonder de smartphone uit zijn broekzak of haar handtas te halen. De gebruiker kan, na het lezen van de notificatie nog beslissen of hij hierop wil ingaan of niet.

De Digital Crown aan het device zullen wij in onze app niet gebruiken. De beweging doorheen de verschillende menu's zullen met swipen (capacitive touch) en drukken (force touch) gebeuren.

Zoals de meeste smartwatch applicaties zullen wij onze notificaties ook werken in functie van een short look en long look. De beweging van de arm van de gebruiker bepaalt of de short of long look wordt weergegeven. De long look geeft de mogelijkheid om op een notificatie te reageren. Deze optie bieden wij natuurlijk ook aan.

SpriteKit en SceneKit geven ons de mogelijkheid om op de smartwatchapp beeld en video te tonen. Hoewel we niet de bedoeling hebben om video af te spelen op de smartwatch, kan het tonen van een afbeelding in ons concept heel goed passen.

Voor mensen die Apple Pay op hun device hebben bevestigd bieden wij die functie aan bij het aankopen van hun goederen of diensten. Heeft de gebruiker geen Apple Pay account, dan wordt hij op de conventionele manier naar een beveiligde betaalsite gestuurd.

## [Smartphone: iPhone](https://developer.apple.com/ios/human-interface-guidelines/overview/themes/ "iPhone OS Design Sheets"){:target="_blank"}
<br>

### Kenmerken
---------

- **Clarity**
- **Deference**
- **Depth**

#### Design Principes
---------
<br>
Apple wijst ons erop dat bij het ontwerpen van een app voor hun iPhone de volgende principes in achting moeten worden gehouden om impact te maximaliseren:

- **Aesthetic Integrity**
- **Consistency**
- **Direct Manipulation**
- **Feedback**
- **Metaphors**
- **User Control**

#### Technische mogelijkheden
---------
<br>
Wij belichten hier de specificaties van de **Iphone8 plus**.

#### Operating system
- iOS 11

#### Navigation
- Capacitive touch (tap, swipe)
- Force touch (press)
- Button (Friends, Apple Pay, power)

#### Capacity
- 64GB
- 256GB

#### Size and Weight
- Height: 6.24 inches (158.4 mm)
- Width: 3.07 inches (78.1 mm)
- Depth: 0.30 inch (7.5 mm)
- Weight: 7.13 ounces (202 grams)

#### Display
- Retina HD display
- 5.5-inch (diagonal) widescreen LCD Multi-Touch display with IPS technology
- 1920-by-1080-pixel resolution at 401 ppi
- 1300:1 contrast ratio (typical)
- True Tone display
- Wide color display (P3)
- 3D Touch
- 625 cd/m2 max brightness (typical)
- Dual-domain pixels for wide viewing angles
- Fingerprint-resistant oleophobic coating
- Support for display of multiple languages and characters simultaneously
- Display Zoom
- Reachability

#### Splash, Water, and Dust Resistant3
- Rated IP67 under IEC standard 60529

#### Chip
- A11 Bionic chip with 64-bit architecture
- Neural engine
- Embedded M11 motion coprocessor

#### Camera
- 12MP wide-angle and telephoto cameras
- Wide-angle: ƒ/1.8 aperture
- Telephoto: ƒ/2.8 aperture
- Optical zoom; digital zoom up to 10x
- Portrait mode
- Portrait Lighting (beta)
- Optical image stabilization
- Six‑element lens
- Quad-LED True Tone flash with Slow Sync
- Panorama (up to 63MP)
- Sapphire crystal lens cover
- Backside illumination sensor
- Hybrid IR filter
- Autofocus with Focus Pixels
- Tap to focus with Focus Pixels
- Live Photos with stabilization
- Wide color capture for photos and Live Photos
- Improved local tone mapping
- Body and face detection
- Exposure control
- Noise reduction
- Auto HDR for photos
- Auto image stabilization
- Burst mode
- Timer mode
- Photo geotagging
- Image formats captured: HEIF and JPEG

#### Video Recording
- 4K video recording at 24 fps, 30 fps, or 60 fps
- 1080p HD video recording at 30 fps or 60 fps
- 720p HD video recording at 30 fps
- Optical image stabilization for video
- Optical zoom; 6x digital zoom (iPhone 8 Plus only)
- Quad-LED True Tone flash
- Slo‑mo video support for 1080p at 120 fps or 240 fps
- Time‑lapse video with stabilization
- Cinematic video stabilization (1080p and 720p)
- Continuous autofocus video
- Body and face detection
- Noise reduction
- Take 8MP still photos while recording 4K video
- Playback zoom
- Video geotagging
- Video formats recorded: HEVC and H.264

#### FaceTime HD Camera
- 7MP camera
- 1080p HD video recording
- Retina Flash
- ƒ/2.2 aperture
- Wide color capture for photos and Live Photos
- Auto HDR
- Backside illumination sensor
- Body and face detection
- Auto image stabilization
- Burst mode
- Exposure control
- Timer mode

#### Touch ID
- Fingerprint sensor built into the Home button

#### Apple Pay
- Pay with your iPhone using Touch ID in stores, within apps, and on the web
- Complete purchases made with Apple Pay on your Mac
- Receive and redeem rewards using rewards cards

#### Cellular and Wireless
- All models
- 802.11ac Wi‑Fi with MIMO
- Bluetooth 5.0 wireless technology
- NFC with reader mode

#### Location
- Assisted GPS, GLONASS, Galileo, and QZSS
- Digital compass
- Wi-Fi
- Cellular
- iBeacon microlocation

#### Video Calling
- FaceTime video calling over Wi‑Fi or cellular

#### Audio Calling
- FaceTime audio
- Voice over LTE (VoLTE)5
- Wi‑Fi calling5

#### Audio Playback
- Audio formats supported: AAC-LC, HE-AAC, HE-AAC v2, Protected AAC, MP3, Linear PCM, Apple - Lossless, FLAC, Dolby Digital (AC-3), Dolby Digital Plus (E-AC-3), and Audible (formats 2, 3, 4, Audible Enhanced Audio, AAX, and AAX+)
- User-configurable maximum volume limit

#### Video Playback
- Video formats supported: HEVC, H.264, MPEG-4 Part 2, and Motion JPEG
- Supports Dolby Vision and HDR10 content
- AirPlay Mirroring, photos, and video out to Apple TV (2nd generation or later)6
- Video mirroring and video out support: Up to 1080p through Lightning Digital AV Adapter and Lightning to VGA Adapter (adapters sold separately)6

#### Siri
- Use your voice to send messages, set reminders, and more
- Get intelligent suggestions in Messages, Mail, QuickType, and more
- Activate with only your voice using “Hey Siri”
- Listen and identify songs

#### External Buttons and Connectors
- Home/Touch ID sensor
- Volume up/down
- Ring/Silent switch
- Side button
- Built-in stereo speaker
- Lightning connector
- Built-in microphone

#### Sensors
- Touch ID fingerprint sensor
- Barometer
- Three-axis gyro
- Accelerometer
- Proximity sensor
- Ambient light sensor

#### Accessibility
- Accessibility features help people with disabilities get the most out of their new iPhone 8. With built-in support for vision, hearing, physical and motor skills, and learning and literacy, you can fully enjoy the world’s most personal device.

- _Features include:_
- Voiceover
- Zoom
- Magnifier
- Software TTY
- Siri and Dictation
- Type to Siri
- Switch Control
- Closed Captions
- AssistiveTouch
- Speak Screen

#### Headphones
- EarPods with Lightning Connector

#### Rating for Hearing Aids
- iPhone 8 Plus (Model A1864, A1897): M3, T4

### Afmetingen
---------
<br>
2880 &times; 1440 px
Beeldschermdiagonaal 5.7 inch
grootte schermen

### Conlusie SmartPhone
---------
In de app op de Smartphone zal vooral worden genavigeerd door swipen en drukken.  
De Iphone beschikt over een draadloze Bluetooth verbinding, NFC-tag reader mode alsook een iBeacon microlocatie.
Deze zullen wij alledrie integreren in ons project. De NFC-tag worden geïntegreed om de gebruiker een afbeelding, filmpje of tekstbestand te laten downloaden. De door bluetooth verbinding met de Apple Watch kan deze een notificatie uitzenden dat er een bestand te bekijken of te downloaden valt.  
De iBeacon microlocatie wordt gebruikt om ons concept om het museum uit te breiden naar een forum. Deze bepaalt de locatie van de gebruiker tegenover andere als ze een online gesprek willen aanknopen.


## Extra informatie Beacons en NFC
### Beacons
---------
<br>
BLE transmitters worden gebruikt om de locatie van de bezoeker in het museum te bepalen. De installatie van BLE transmitters is snel, gemakkelijk en vergt nagenoeg geen onderhoud. Dit is de nieuwste trend om indoor locaties te bepalen.


### NFC of Near-field communication
---------
<br>
Draadloze communicatie van dichtbij. Simpelgezegd vindt er een actie plaats wanneer een NFC chip bij een toestel met NFC gehouden wordt op korte afstand. Je hoort een piep wat inhoudt dat er een NFC tag gelezen wordt.
Het heeft doorgaans een bereik van ongeveer 10 centimeter en kan in twee verschillende standen werken waarbij het verder bouwt op RFID-systemen door ook tweerichtingscommunicatie toe te laten:

NFC kent twee modi:
- **Passive mode** (of tag-emulatie) waar de chip zich als een RFID-tag gedraagt.
- **Active mode** waar de chip zich gedraagt als een reader en peer-to-peermode waarbij het mogelijk is om te communiceren tussen twee toestellen.
Deze laatste modus is handig om niet enkel data te ontvangen, maar deze ook te versturen.


