# ProvningProgrammering1

## Slutprojekt - Hänga Gubbe

Uppgiften går ut på att ni ska skapa ett egenskrivet spel i Java eller C#, som går ut på att användaren ska gissa ett ord. Spelet ska vara baserat på input från användaren och skriva ut ledtrådar och instruktioner så att användaren ska kunna lyckas gissa ordet. Vet man inte hur Hänga Gubbe spelas kan man kolla på [den här videon](https://www.youtube.com/watch?time_continue=112&v=j-pBzBvJVKc&feature=emb_title).

Innan ni får börja koda måste ni göra en **planering**. Planeringen ska godkännas av mig, och sedan får ni sätta igång med själva koden.

Uppgiften ska göras **enskilt** och man får vara beredd att i detalj förklara muntligt hur koden fungerar. Kod utan kommentarer och godkänd planering kommer **inte** att godkännas. Man får självklart diskutera uppgiften med varandra och fråga om hjälp om man fastnar men det är **INTE** tillåtet att kopiera varandras kod. Plagiat ger automatiskt underkänt i uppgiften, och all kod utan kommentarer räknas automatiskt som plagiat.

#### Följande basfunktionalitet måste varje spel innehålla för att du ska få godkänt:

* En godkänd planering enligt [dessa instruktioner](./Planering.md).
* Ett program som fungerar, med följande funktionalitet:
    * Tydliga instruktioner till användaren om hur spelet går till.
    * Att spelaren får gissa på en bokstav i taget, tills hen gissat rätt på alla bokstäver i det rätta ordet. (Spelet ska *inte* differentiera mellan stora och små bokstäver)
    * Att spelaren får någon typ av feedback efter varje gissning, med antal **kvarvarande gissningar** samt en **representation av ordet** (med bokstäver man gissat rätt på) på detta sätt: **_r__gr_mm_r_ng**
* En utvärdering enligt [dessa instruktioner](./Utvärdering.md).

*För bara godkänt krävs det alltså inte att du har någon visuell representation av en gubbe som hängs, utan det räcker med att du talar om hur många gissningar spelaren har kvar.*

#### För att nå högre betyg ska även allt eller vissa delar av följande uppfyllas:

* Att du i din kod använder dig av metoder. (Obligatoriskt för att nå högre betyg än E) Hur väl ni använder och motiverar er användning av metoder påverkar hur högt betyg ni får på uppgiften.

* Att spelet ska kunna köras utan att krascha. Hur du implementerar det är upp till dig.

* Förslag på extra funktionalitet: 
    * Att ordet som ska gissas på något sätt är slumpgenererat i start av varje runda.
    * Att spelet har en meny som låter spelaren välja svårighetsnivå (exempelvis hur långa/svåra ord man får gissa på).
    * Att spelet kan köras flera gånger utan att spelaren behöver starta om hela applikationen.
    * Att man kan vara flera spelare. (Som kanske gissar på olika ord? Där en person skriver in ett ord och den andra gissar? Hur ni vill göra är helt upp till er.)
    * Att man har något spelläge där man skriver in ett eget ord som man ska gissa på.
    * Att man kan gissa på hela meningar, där mellanslagen inte räknas med i "ordet".
    * *(Svårare)* Att man lägger in någon slags ljudeffekter, t.ex. när man gissar rätt/fel, gubben dör, etc.
    * *(Svårare)* Att man använder sig av externa filer på något sätt. (För att läsa in en lista på alla ord som kan slumpas fram? För att spara alla resultat i en scoreboard? Välj själva.)
    * *(Svårare)* Att ni använder er av *flera* klasser, kanske för att sätta upp en MVC-struktur i projektet. Hör av er till mig om ni vill försöka göra detta, så kan vi diskutera det och ha en genomgång på kodstugan.
    * Valfri annan extra funktionalitet (dubbelkolla med mig först).

* Att du har någon typ av visuell representation av spelförloppet, med en gubbe som hängs, genom något av dessa två förslag:
    * Att du har en textbaserad visuell representation av en gubbe som hängs, kanske som i [detta exempel](https://gist.github.com/chrishorton/8510732aa9a80a03c829b09f12e20d9c).       Detta skrivs då ut i konsolen.
    
#### Deadline

Inlämningsdeadline: Onsdag 28 oktober, 15:00. (Färdig planering, kod och utvärdering.)
