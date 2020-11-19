---
Title: Kmom02
Description: Report kmom02 page
template: kmom
# hidden: true
---

Kmom02
==================
Det är första gången jag arbetar med SASS, jag gillar det skarpt såhär långt. Möjligheten att använda variabler var något jag saknade i htmlphp-kursen då jag hade samma färg på många ställen vilket gjorde det invecklat att uppdatera. Jag tycker även funktionerna för att ljusa upp och mörka är väldigt smidiga. Jag testade även att använda mixins för att importera lokala fonts, istället för att behöva skriva all kod för båda mina lokala fonts jag importerar. Att man har möjlighet att nästla kod tycker jag ytterligare ökar läsbarheten för koden.  
Jag valde att dela upp min SASS-kod i flera filer, just nu har jag en fil för header, en för footer, en för övriga layout, en som innehåller typografi, en för variabler, en för responsivitet den är dock tom i nuläget, all den koden ligger kvar i min gamla CSS kod, då jag inte hunnit sätta mig in i vad allt gör. Alla ovannämnda moduler importeras till style som är huvudfilen för min SASS-kod.  
Jag Har gjort några ändringar sen förra vecka som jag tycker lyft min sida, Jag har uppdaterat flash-bilden och flyttat den, till under och ovanför content för att ge intrycket av en ram. Jag har tagit bort min föregående logo och bytt den mot en fontAwesome icon. Jag har även lagt till en fontAwesome ikon för hem. Hur jag tänkte gällande min design var att jag gillar hårdrock och metal-musik, vilket jag försöker återspegla i designen, både gällande typsnitt och även färgerna.  
Jag har inte tidigare arbetat med node, npm eller deras skript men jag upplever det som ett smidigt verktyg. Att man kan skapa egna skript var en trevlig möjlighet. Det gjorde det enkelt då man med hjälp av watch automatiskt kunde uppdatera temat vid ändringar. Att kompilera SASS till CSS var inget jag reflekterade över då det gick så snabbt och ofta gjordes automatiskt med hjälp av watch skriptet.  
Mitt TIL för detta kmom skulle jag säga är allmänt hur mycket mer användarvänligt och flexibelt SASS känns jämfört CSS, med alla inbyggda möjligheter som saknas från CSS.  
Jag valde att importera mina fonts lokalt, det medförde att det uppstod två valideringsfel gällande '' dök upp när man körde nrm run lint, efter komunitation med Niklas via discord så var det okej att bortse från dom.
