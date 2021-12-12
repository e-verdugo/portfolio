Inladdninstidsanalys
=======================

Urval
-----------------------
Jag har valt tre sidor som innehåller mycket information. Dessa sidor är [DBWebb](https://dbwebb.se/), [Wikipedia](https://en.wikipedia.org/wiki/Main_Page), och [Encyclopedia](https://www.encyclopedia.com/). Jag valde dessa då jag ville se hur tre sidor ur samma kategori men med olika storlek och syfte jämförs med varandra. DBWebb och Wikipedia var mina förstahandsval då jag använder båda mycket, men Encyclopedia var jag tvungen att kolla runt lite för att hitta.

Metod
-----------------------
För den här rapporten så använde jag både Google Pagespeeds och själva devtoolsfliken för att mäta hur fort sidorna laddades. Jag mätte hastigheten för både mobil och desktop tre gånger, och antecknade resultaten i ett kalkylark. Att mäta flera gånger och ta ut medelvärdet gör att man få ett mer riktigt resultat, då värden som kanske hamnat utanför det normala balanseras ut. När jag skulle mäta Wikipedias sidor så fick jag vara försiktig så att jag inte nuddade några länkar, då den laddar in en sammanfattning av den länkade artikeln.

Resultat
-----------------------
### DBWebb
![Startsidan för DBWebb](portfolio/../../assets/img/dbwebb.PNG "Startsidan för DBWebb")

För DBWebb har jag valt att mäta dessa sidor:
<br> [https://dbwebb.se/kurser/design-v3/kmom05](https://dbwebb.se/kurser/design-v3/kmom05)
<br> [https://dbwebb.se/kurser/design-v3/kmom04](https://dbwebb.se/kurser/design-v3/kmom04)
<br> [https://dbwebb.se/kurser/design-v3/kmom03](https://dbwebb.se/kurser/design-v3/kmom03)

### Wikipedia
![Startsidan för engelskspråkiga Wikipedia](portfolio/../../assets/img/wikipedia.PNG "Startsidan för engelskspråkiga Wikipedia")

För Wikipedia har jag valt att mäta dessa sidor:
<br> [https://en.wikipedia.org/wiki/Python_(programming_language)](https://en.wikipedia.org/wiki/Python_(programming_language))
<br> [https://en.wikipedia.org/wiki/JavaScript](https://en.wikipedia.org/wiki/JavaScript)
<br> [https://en.wikipedia.org/wiki/Blekinge_Institute_of_Technology](https://en.wikipedia.org/wiki/Blekinge_Institute_of_Technology)

### Encyclopedia
![Startsidan för encyclopedia.com](portfolio/../../assets/img/encyclopedia.PNG "Startsidan för encyclopedia.com")

För Encyclopedia har jag valt att mäta dessa sidor:
<br> [https://www.encyclopedia.com/environment/encyclopedias-almanacs-transcripts-and-maps/passenger-pigeon)](https://www.encyclopedia.com/environment/encyclopedias-almanacs-transcripts-and-maps/passenger-pigeon)
<br> [https://www.encyclopedia.com/plants-and-animals/animals/vertebrate-zoology/thylacine](https://www.encyclopedia.com/plants-and-animals/animals/vertebrate-zoology/thylacine)
<br> [https://www.encyclopedia.com/science/encyclopedias-almanacs-transcripts-and-maps/rhinoceroses-rhinocerotidae](https://www.encyclopedia.com/science/encyclopedias-almanacs-transcripts-and-maps/rhinoceroses-rhinocerotidae)

Analys
-----------------------
Här är rådatan från min undersökning av sidornas tider och betyg:
<iframe class="calcdoc" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSszQFA2mGBlblWFumqPY5dEmYe3k83uQNlrOwXGmZEcRQ9O2VbBgMR5Uq6zH2Mg3okIbZWAqR_GRtV/pubhtml?widget=true&amp;headers=false" title="embedded calc doc"></iframe>

Av alla sidor, så använde DBWebb minst resurser som behövde hämtas, vilket drog ner på laddningstiderna. Sidorna var också de minsta. Tvåa kom Encyclopedia med 16 resurser på alla sidor, vilka alla också hade ungefär samma storlek. Wikipedia var störst, vilket var någolunda väntat då artiklarna var störst och hade flest bilder/resurser.

Alla sidorna fick högst betyg om man kollade via desktop, då flera fick 100 av 100 och ingen hamnade under 97. Det såg däremot lite annorlunda ut för den mobila kollen. Där var det högsta resultatet 99, och lägsta 78, med ett medeltal på ca 93. Det verkar tyda på att de mobila sidorna inte får samma prioritet, alternativt är svårare att bygga bra sidor för.

Den åtgärd som mest dök upp via PageSpeed för mobila sidor var att ta bort sånt som inte används, mestadels javascript och css. PageSpeeds uppmuntrade även användningen av "Lazy loading", där sidan laddar in element vart efter de behövs. När det gäller desktop sidor så var det mycket mindre som krånglade, vilket även ledde till mindre fel som dök upp på majoriteten av sidorna, och istället så var det lite blandat. Det var några påpekanden om vilka format man borde använda för media, att vissa element saknade vissa bra-att-ha egenskaper så som width och height, och samma som med de mobila sidorna, att det gick att spara in lite av laddningstiden genom att ta bort oanvända delar av sidans kod.

Slutsats
-----------------------
Enligt min åsikt så vinner DBWebb när det gäller laddningstid, men så är sidorna också mindre än de andra. Då DBWebb var den ända som kom under en sekunds laddningstid så vinner den i min bok. Därefter hamnar Encyclopedia på andraplats, och Wikipedia kommer trea. Av alla dessa sidor så tycker jag däremot att Wikipedia är enklast att använda, då sökfunktionen fungerar riktigt bra. I Encyclopedia så var det svårt att hitta det man ville då sökmotorn verkar fungera väldigt annorlunda från vad jag är van med. Jag ville hitta en artikel om lejon, och jag var tvungen att bläddra flera sidor för att hitta ett resultat som handlade om det fysiska djuret, och inte dess egenskaper och historik inom mänsklig kultur. DBWebb har ingen sökfunktion, utan man måste bläddra runt och hoppas att man lyckas hitta det man letar efter, vilket tyvärr inte är det mest användarvänliga.

Min gräns för vad som är en rimlig laddningstid ligger nog på ca 3 sekunder. Där efter så börjar man märka att det tar längre tid än vanligt. Jag skulle nog stå ut med upp till 5 sekunder, men efter det så skulle det vara lite för lång tid för att jag skulle kunna använda sidan ofta utan att bli irriterad.

Alla testade sidor klarar av att hålla sig inom den gränsen, och hittills har jag inte haft något problem med nån av dem (så länge internet fungerar som det ska från min ända).

Övrigt
-----------------------
Jag som har skrivit den här rapporten heter Emelie Verdugo. Min acronym här på BTH är ~emve21.
