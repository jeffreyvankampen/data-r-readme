---
description: De oplevering van het prototype en een video over hoe de app werkt
---

# 📱 Hi-Fi Prototype oplossing

### **Oplossing**

Uit de gesprekken blijkt dat het prototype succesvol is en dat de gebruiker dit graag zou willen gebruiken. Voor het milieu en een betere ervaring. De werking is nu functioneel en duidelijk geworden. Gebruikers willen meer om een app dagelijks te gebruiken, zoals kosten delen aan de hand van de kassabon. Mijn focus tijdens dit project lag op de automatische werking en het gebruiksgemak en daarom ben ik er zeer tevreden over. Ook vind ik de feedback die ik heb opgedaan handig door de gesprekken die ik met de doelgroep en de winkel heb gehouden. Alleen voor een implementatie met de winkel moet de API verder worden ontwikkeld. De uitdaging is beantwoord met mijn concept.

<figure><img src="../.gitbook/assets/Flow.jpg" alt=""><figcaption><p>De flow van het product<br></p></figcaption></figure>

**Link naar het prototype:** [**https://xd.adobe.com/view/425bf939-6c03-4214-ba25-aa3690b077ea-1708/**](https://xd.adobe.com/view/425bf939-6c03-4214-ba25-aa3690b077ea-1708/)

**Memo UX Prototype Video:**

{% file src="../.gitbook/assets/Memo UX Prototype.mp4" %}
Video over hoe de app werkt
{% endfile %}

### **API**&#x20;

Een API staat voor 'Application Programming Interface'. Om het volledige prototype te ontwikkelen moet ik een API ontwikkelen om data te sturen en ontvangen naar de gebruiker (input/ouput) of een GET data request, dit valt buiten de scope van dit project. Om kassabonnen digitaal op te slaan met behulp van een bankpas, moet de winkel de API integreren in hun kassasysteem ofwel POS (Point of Sale). Dit betekent "de plek waar een klant de betaling voor goederen en/of services voldoet, wat zich bij de kassa bevindt". Tijdens het afrekenen in de winkel betaalt de klant met zijn of haar bankpas en verwerkt de winkel de kassabon in hun systeem en stuurt deze door.&#x20;

1. De winkel moet een API integreren in hun kassasysteem, de API kan communiceren met de app waarin de klant de kassabon wil ontvangen.
2. Wanneer een klant met een bankpas betaalt, kan het kassasysteem de productgegevens naar de API sturen (dataopslag van de gebruiker). Dit is informatie zoals de productgegevens en de IBAN en de datum en tijd op de kassabon.
3. De API kan deze informatie dan gebruiken om een digitale kassabon te maken.
4. De API kan vervolgens de digitale kassabon doorsturen naar de app. Dit wordt gedaan door de kassabon automatisch te synchroniseren met de app. Dit kan alleen als zij aangemeld staan.&#x20;
5. De klant bewaart automatisch de kassabon in de app en kan het gebruiken. Dit kan handig zijn omdat ze de kassabon niet fysiek hoeven te bewaren en deze op elk gewenst moment kunnen bekijken op hun telefoon.

<figure><img src="../.gitbook/assets/20230417_153919.jpg" alt=""><figcaption><p>Test van het product met de doelgroep</p></figcaption></figure>

<figure><img src="../.gitbook/assets/WhatsApp Image 2023-03-17 at 13.28.25.jpeg" alt=""><figcaption><p>Test van het product met een peer</p></figcaption></figure>

<figure><img src="../.gitbook/assets/WhatsApp Image 2023-03-17 at 13.28.18.jpeg" alt=""><figcaption><p>Test van het product met een peer</p></figcaption></figure>

<figure><img src="../.gitbook/assets/8 kopie.jpeg" alt=""><figcaption><p>Test van het product met mijn belanghebbende</p></figcaption></figure>
