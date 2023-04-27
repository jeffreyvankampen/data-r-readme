---
description: Een concept van de applicatie, waar ik de ideeën toelicht
---

# Concept

**Afkortingen**

API = Application Programming Interface\
POS = Point of Sale systeem

**Wat heb ik gedaan** \
\
Dit zijn de ideeën van mijn app, ik heb nagedacht over hoe deze eruit zou kunnen zien. Het ontwerp omvat onder andere een weergave van de kassabonnen, een snelle zoekfunctie en de mogelijkheid om een deel van je bankkaart toe te voegen om kassabonnen automatisch te bewaren.

Om het succes van de app te vergroten, heb ik onderzocht dat snelheid, veiligheid en automatische verwachtingen belangrijk zijn. Daarnaast vind ik het interessant om extra functies aan te bieden, zoals het bijhouden van bonnen op verschillende apparaten.

**Wat neem ik mee** \
\
Het idee om een app te ontwikkelen is de beste keuze, omdat gebruikers hierop automatisch hun kassabonnen kunnen bewaren. Ik heb een concreet concept gemaakt met verschillende functies. Daarna heb ik een keuze gemaakt voor de belangrijkste functies, zoals het bewaren en zoeken van bonnen. Ik heb ook nagedacht over hoe ik de API kan implementeren om communicatie tussen de winkel, de consument en de bank mogelijk te maken. **De API is als het ware de software dat ervoor zorgt gegevens tussen de app en andere partijen kunnen worden uitgewisseld.**

<figure><img src="../.gitbook/assets/Scherm­afbeelding 2023-04-24 om 22.02.44.png" alt=""><figcaption><p>Een voorbeeld van hoe de app werkt</p></figcaption></figure>

<figure><img src="../.gitbook/assets/MicrosoftTeams-image kopie.png" alt=""><figcaption><p>Concept 1</p></figcaption></figure>





<figure><img src="../.gitbook/assets/20221113_154903.png" alt=""><figcaption><p>Concept 2</p></figcaption></figure>



<figure><img src="../.gitbook/assets/20221113_154914.png" alt=""><figcaption><p>Concept 3</p></figcaption></figure>

**Concept**\
\
Na de feedback frenzy heb ik het concept om bonnen automatisch te bewaren bedacht. Tijdens de onboarding krijgt de gebruiker een beknopte uitleg over de app en kan zich vervolgens aanmelden met hun social media-account of bankpas door op een knop te drukken.

Bij het tweede idee heb ik nagedacht over het uiterlijk van de app en de onboarding van de gebruiker. Tijdens een feedback frenzy is het beter dat de app eenvoudig moet blijven en niet te veel opties moet heeft, zoals kosten splitten, ondernemers, social login. Voor hun privacy willen gebruikers liever alleen het laatste deel van hun IBAN gebruiken, dat ook op hun kassabon staat.

Mijn derde idee was om de digitale kassabonnen in de app te laten zen op basis van de weergave van de datum. Hier worden digitale bonnen automatisch ontvangen en weergegeven. Met snelle zoekmogelijkheden om de app makkelijk te maken. De gebruiker wilt hun bonnen eenvoudig opslaan en snel kunnen zoeken.\


<figure><img src="../.gitbook/assets/Scherm­afbeelding 2023-04-24 om 22.02.20.png" alt=""><figcaption><p>Lijst van de functionaliteiten na het groenlicht</p></figcaption></figure>

**Interactie**\
\
Memo is een interactieve app om kassabonnen digitaal op te slaan, met als doel de bonnen duurzamer te maken. Het gebruiksvriendelijke product kan het milieu verbeteren. Met een betrouwbare werking wil ik de doelgroep motiveren om hun bonnen digitaal te bewaren. De nadruk ligt op het bieden van een betere ervaring voor de gebruikers. De branding heeft impact op het product en het is belangrijk dat het een professionele en betrouwbare uitstraling heeft. Memo betekent memory of een korte notitie. Het is een tool om de gebruiker hun bonnen te bewaren. Om de gebruiker bewust te maken van de app deel ik de slogan "Get the Memo”.

**Wat doet het**

Met Memo bewaar je bonnen automatisch in de app met behulp van een bankpas. In de app kun je een bon gebruiken voor je aankopen of om een steentje bij te dragen aan het milieu. Met de handigheid van de app ontvang je moeiteloos en digitaal van de winkel waar je iets koopt. Ten slotte is het veel beter voor het milieu.

**Werking**

De gebruiker kan zich aanmelden met hun bankpas. Wanneer zij iets betalen, ontvangen zij een digitale kassabonnen die de winkel genereert. Door de laatste vier cijfers van de bankpas in de app te gebruiken kan de gebruiker zich snel en veilig aanmelden. De gebruiker en de winkel worden verbonden met de API en de gebruiker kan de kassabon automatisch ontvangen in de app.

**API**&#x20;

Een API staat voor 'Application Programming Interface'. Om het volledige prototype te ontwikkelen moet ik een API ontwikkelen om data te sturen en ontvangen naar de gebruiker (input/ouput) of een GET data request, dit valt buiten de scope van dit project. Om kassabonnen digitaal op te slaan met behulp van een bankpas, moet de winkel de API integreren in hun kassasysteem ofwel POS (Point of Sale). Dit betekent "de plek waar een klant de betaling voor goederen en/of services voldoet, wat zich bij de kassa bevindt". Tijdens het afrekenen in de winkel betaalt de klant met zijn of haar bankpas en verwerkt de winkel de kassabon in hun systeem en stuurt deze door.&#x20;

1. De winkel moet een API integreren in hun kassasysteem, de API kan communiceren met de app waarin de klant de kassabon wil ontvangen.
2. Wanneer een klant met een bankpas betaalt, kan het kassasysteem de productgegevens naar de API sturen (dataopslag van de gebruiker). Dit is informatie zoals de productgegevens en de IBAN en de datum en tijd op de kassabon.
3. De API kan deze informatie dan gebruiken om een digitale kassabon te maken.
4. De API kan vervolgens de digitale kassabon doorsturen naar de app. Dit wordt gedaan door de kassabon automatisch te synchroniseren met de app. Dit kan alleen als zij aangemeld staan.&#x20;
5. De klant bewaart automatisch de kassabon in de app en kan het gebruiken. Dit kan handig zijn omdat ze de kassabon niet fysiek hoeven te bewaren en deze op elk gewenst moment kunnen bekijken op hun telefoon.

<figure><img src="../.gitbook/assets/Scherm­afbeelding 2023-04-24 om 22.06.12.png" alt=""><figcaption><p>Een interactieve uitleg over hoe de app werkt</p></figcaption></figure>
