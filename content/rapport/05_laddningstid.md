Laddningstid
=======================

I den här uppgiften så skall vi analysera laddningstid på olika hemsidor.

Urval
-----------------------
[FIGURE src="image/hemsida1.jpg" class="hemsida"]
[FIGURE src="image/hemsida2.jpg" class="hemsida"]
[FIGURE src="image/hemsida3.jpg" class="hemsida"]

Jag har valt att analysera samma hemsidor som i föregående analys då jag har redan blivit bekant med dem.

www.folkhogskolan.se
www.arbetsformedlingen.se
www.burleightourism.com.au

Metod
-----------------------

Jag använde mig utav google page speed insights, och google kalkylark för att notera ner mina mätningar och analyser. Sedan såklart använde jag mig utav bild taben under nätverk i devtools. Jobbade igenom en sida i taget och provdae nya tabs och tog bort historiken för den sidan.


Resultat
-----------------------

Här hittar ni mina laddnings resultat på
<a href="https://docs.google.com/spreadsheets/d/1d9R3fyMMC3QSWEZBI1hYZTAJ0g2FKBYybFjuNaQ96cE/edit?usp=sharing">Kalkylark</a>!

Alla hemsidor kan absolut förbättras. Samtliga hemsidor ligger i genomsnitt på google insights på dator skärmen. På mobila enheter så är samtliga hemsidor långsamma. Vilket inte förvånar mig på Burleigh Tourisms hemsida. Men på arbetsförmedlingen och folkhögskolan så trodde jag inte att det skulle bli så.

För att arbetsförmedlingens hemsida ska bli snabbare enligt google insights så behöver som ta bort resurser som blockerar rendering, minska svarstiderna ifrån servern och även skjuta upp CSS kod som inte används.

För att folkhögskolans hemsida ska laddas fortare så behöver även som minska svarstiderna ifrån servern. Dom behöver jobba lite med deras bilder också, skicka in bilder i ett modernare format, och använda dem med rätt storlek och även koda bilderna mer effektivt. Javascript kodningen behöver minifieras samt en aktivering av textkomprimeringen.

Burleigh Tourisms hemsida slutar aldrig att laddas. Det används en video istället för en bild som startsida, vilket inte är optimalt för laddningstiden. Bilder som inte visas på skärmen fortsätter även dom att laddas in. För att den här hemsidan skall bli snabbare så behöver dom jobba lite med deras bilder. Alltså skjuta upp bilder som inte används på skärmen, och även skicka in bilderna i ett modernare format. Även den här hemsidan behöver använda bilderna i rätt storlek, och koda bilderna mer effektivt. CSS kod som inte används bör även skjutas upp.

Analys
-----------------------

Samtliga hemsidor stöter på liknande problem. Klagar på att bilder behövs användas mer effektivt. Alltså i rätt storlek och i ett modernare format. Det klagas även på att det är för mycket kodning, och att all kodning inte behövs eller används. Både i Javascript och CSS. Arbetsförmedlingens hemsida är den ända som inte klagar på bilderna. Dock så blockeras renderingen av olika resurser (händer även på Burleigh Tourisms hemsida).

Efter andra omladdningen så sparas bilderna i cache. Så att andra omladdningen blir snabbare och bildstorlekarna blir mindre och laddningstiden dras även ner. Förutom på burleightourism. Låt datorn stå öppen och deras hemsida laddar fortfarande, 20.2 minuter nu. En snabb hemsida enligt mig skall såklart ligga så lågt som möjligt, men som ett max värde runt 3 sekunder. Sidorna hade laddats upp till en användbar stadie under 3 sekunder. Men ingen av dessa hemsidorna hade laddats klart under 3 sekunder. Arbetsförmedlingens hemsida var dock närmst på 3.89 sekunder.

Första plats: Arbetsförmedlingen

Andra plats: Folkhögskolan

Förlorare by far: Burleigh Tourism


Referenser
-----------------------

https://developers.google.com/speed/pagespeed/insights

Övrigt
-----------------------

Rapport utförd på egen hand.
