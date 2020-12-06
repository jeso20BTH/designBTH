---
Title: Laddtider
Description: Analysis page for loads
template: sidebar
menu:
    - url: 01_colors
      text: Färger
    - url: 02_load
      text: Laddtider
    - url: 03_design_principles
      text: Designprinciper
# hidden: true
---

Analys - Laddtider
==================

Syftet med denna uppgift är att dokumentera tre sidors laddningstider och samt jämföra och analysera data, för att utse en vinnare, samt hitta förbättringsförslag för dem olika sidorna.

Urval
-----------------------

Precis som för uppgift ett ville  jag välja en typ av sidor som intresserade mig personligen och valde då discgolfdisctillverkare. Jag tycker det kan vara intressant att använda samma sidor för att se om det finns samband mellan färger från förra analysen samt dagens analys. Jag upptäckte efter förra analysen att innova sidan jag använt var deras europabutik, så jag ändrade den för att kunna göra analys på liknande sidor för alla tre webbplatser. Mitt urval gjordes sedan efter dom tre företagen som har flest marknadsandelar.
Jag valde då följande:
* [Discraft](https://www.discraft.com/)
* [Dynamic discs](https://www.dynamicdiscs.com/)
* [Innova Discs](https://www.innovadiscs.com/)

Metod
-----------------------

Jag identifierar vilka sidor som finns på samtliga webbplatser för att kunna göra en rättvis jämförelse över laddningstider. Det slutade med att jag valde startsida, lagsida och produktsida. För varje sida så använder jag google page speed, som gör en analys och ger en poäng för mobil samt dator.Dessa poäng antecknas i ett google spreadsheet. Närta steg är att med hjälp av google chromes devtools mäta laddtid, skickade förfrågningar, överförd data samt sidans totala storlek. Resultatet av det förs även det in i google spreadsheet. Den mättningen görs tre gånger för att sedan räknas ut ett snitt. Då vissa sidor har en bläddrande bildmeny, så används lightshot för att ta en print av data för respektivesida efter initiala laddningen. För webbplatserna tas även en printscreen som tas med i resultatet.

Resultat
-----------------------

Nedan presenteras resultatet för samtliga sidor, i bilaga finns även rådata.


### Discraft
![Discraft](../assets/img/discraft2.jpg)

#### Sida 1 - Startsida
* Google page speed
    - Desktop: 62 poäng
    - Mobil: 34 poäng
* Snitt devtools
    - Laddtid: 12,26 s
    - Resurser: 54
    - Överförd storlek: 14,9 MB
    - Total Storlek: 16,9 MB

#### Sida 2 - Lagsida
* Google page speed
    - Desktop: 89 poäng
    - Mobil: 54 poäng
* Snitt devtools
    - Laddtid: 3,35 s
    - Resurser: 120
    - Överförd storlek: 1,1 MB
    - Total Storlek: 5,4 MB

#### Sida 3 - Produktsida
* Google page speed
    - Desktop: 64 poäng
    - Mobil: 23 poäng
* Snitt devtools
    - Laddtid: 4,81 s
    - Resurser: 70
    - Överförd storlek: 2,0 s
    - Total Storlek: 4,4 s

#### Förbättringsförslag:
Största förbättringsförslaget jag kan se är storleken på bilder och då framför allt på startsidan där dom laddar ner flertalet bilder som inte är anpassade efter var den ska sitta. Det finns inte heller någon anpassning för surfplatta utan den visas på samma sätt som dator och läser in samma bilder. Det positiva är att det finns en mobilverision som läser in mindre bilder.

### Dynamic discs
![Dynamic discs](../assets/img/dynamicdiscs.jpg)

#### Sida 1 - Startsida
* Google page speed
    - Desktop: 41 poäng
    - Mobil: 7 poäng
* Snitt devtools
    - Laddtid: 3,65 s
    - Resurser: 182
    - Överförd storlek: 5,13 MB
    - Total Storlek: 9,8 MB

#### Sida 2 - Lagsida
* Google page speed
    - Desktop:          52 poäng
    - Mobil:            13 poäng
* Snitt devtools
    - Laddtid:          3,99 s
    - Resurser:         246
    - Överförd storlek: 15,1 MB
    - Total Storlek:    19,1 MB

#### Sida 3 - Produktsida
* Google page speed
    - Desktop:          68 poäng
    - Mobil:            13 poäng
* Snitt devtools
    - Laddtid:          3,32 s
    - Resurser:         135
    - Överförd storlek: 1,8 MB
    - Total Storlek:    6,2 MB

#### Förbättringsförslag:
Använda sig av möjligheten att sidan laddas allt eftersom att man skrollar och tänker då jag främst på lagsidan där hela sidan läses in samtidigt, hade varit mindre resurskrävande om det lästes in allt eftersom.

### Innova
![Innova](../assets/img/innovadiscs2.jpg)

#### Sida 1 - Startsida
* Google page speed
    - Desktop:          36 poäng
    - Mobil:            4 poäng
* Snitt devtools
    - Laddtid:          4,85 s
    - Resurser:         208
    - Överförd storlek: 4,93 MB
    - Total Storlek:    11,43 MB    

#### Sida 2 - Lagsida
* Google page speed
    - Desktop:          19 poäng
    - Mobil:            10 poäng
* Snitt devtools
    - Laddtid:          8,61 s
    - Resurser:         586
    - Överförd storlek: 7,33 MB
    - Total Storlek:    16,07 MB

#### Sida 3 - Produktsida
* Google page speed
    - Desktop:          46 Poäng
    - Mobil:            9 Poäng
* Snitt devtools
    - Laddtid:          3,41 s
    - Resurser:         162
    - Överförd storlek: 3,03 MB
    - Total Storlek:    7,73 MB

#### Förbättringsförslag
Sidan ger ett intryck av att vara allmänt långsam, tar längre tid än övriga sidor från att man trycker på en länk tills dess att man blir omdirigerad. Mitt förslag till förbättring är att se över varför det är långa tider till första serveranropet utförs

Analys
-----------------------

### Vanligaste förbättringarna för sidorna.

Till min hjälp för att hitta de vanligaste förbättringarna för webbplatserna har jag använt informationen som finns på google page speed. Det jag ser som återkommande både för desktop och mobil är enligt nedan:
* Det finns oanvänd kod för javascript.
* Man använder fel format på bilder.
* Man använder fel storlek på bilder.
* Man hade kunnat ladda in visa resurser tidigare.

Jag tycker google page speed var väldigt behjälpligt då jag inte hade hittat vissa av dessa bristerna annars. Det jag själv kunde se var att det användes större bilder än behövligt. däremot hade jag inte själv hittat att det fanns oanvänd javascript kod.

### Bäst webbplats

Jag har valt att analysera dem olika mätvärdena jag har fått fram enligt tabellen nedan. Jag har för varje sida rangordnat dom från ett till tre där ett är bäst och tre är sämst. Jag lägger sedan ihop poängen från samtliga kategorier för att få ett resultat.

|           | Discraft       |    |Dynamic         |       |Innova    |       |
| :------------: | :------------: |:-------:|:---------:|:-----:|:--------:|:-----:|
| **Test**                | **Placering/sida**    | **Total**    | **Placering/sida**    | **Total**    | **Placering/ sida**    | **Total**    |
| GPS - Desktop       | 1-1-1    | 3    | 2-2-2    | 6    | 3-3-3    | 9    |
| GPS - Mobil         | 1-1-1    | 3    | 2-2-2    | 6    | 3-3-3    | 9    |
| Laddtid             | 3-1-3    | 7    | 1-2-1    | 4    | 2-3-2    | 7    |
| Resurser            | 1-1-1    | 3    | 2-2-2    | 6    | 3-3-3    | 9    |       
| Överförd storlek    | 3-1-2    | 6    | 2-3-1    | 6    | 1-2-3    | 6    |
| Total storlek       | 3-1-1    | 5    | 1-3-2    | 6    | 2-2-3    | 7    |
| **Totalt**          |          |**27**|          |**34**|          |**47**|   


Med hjälp den analysen ser vi följande rangordning av de olika webbplatserna:
1. Discraft med 27 poäng
2. Dynamic discs med 34 poäng
3. Innova discs med totalt 47 poäng
Jag tycker det är intressant att det jag upplevde när jag använde det olika webbplatserna återspeglar sig här, då jag upplevde innova som mycket långsammare. Det är även det testet visar. Sen skilljer det inte lika mycket mellan Discraft och Dynamic disc.

### Absolut laddtid
Jag skulle säga att en sida som är färdigladdad på under två sekunder är snabbt men att man vbehöver börja se saker snabbare än så. Skulle sidan däremot ta längre än fem sekunder upplever jag sidan som långsam. Allt däremellan upplever jag som acceptabelt. Ingen av sidorna jag valt ut klarade sig under två sekunder däremot gick flera sidor över fem sekunder varav ett par närmade sig tio sekunder. Som referens har jag använt min portfolio som laddar på under två sekunder. Sen beror det på ifall det är mycket bilder och då bilder som är befogade för då kan det vara okej att laddningstiden ökar en anning.

Referenser
-----------------------
[Cypresspointgolf](https://www.cypresspointgolf.com/best-disc-golf-brand/) har använts till urvalsprocessen.  
[Rådata](https://docs.google.com/spreadsheets/d/e/2PACX-1vQjBlNMOq_YqtP2qSHECWCEiKWtEZBY1FVZzWI961koXSzn8IE05IC-Chqa8t5lMj39QENfcNztPicH/pubhtml?gid=0&single=true)

### Hjälpmedel
* [Google page speed](https://developers.google.com/speed/pagespeed/insights/)
* [Google spreadsheet](https://www.google.se/intl/sv/sheets/about/)
* [lightshot](https://app.prntscr.com/en/)
* [Discraft sida 1](https://www.discraft.com/)

### Webbplatser
#### Discraft
* [Discraft sida 1](https://www.discraft.com/)
* [Discraft sida 2](https://www.team.discraft.com/team-discraft)
* [Discraft sida 3](https://www.discraft.com/star-wars-3-pack-disc-golf-set-starwars.3pk?returnurl=%2fsearch%3fq%3dstar%2bwars)

#### Dynamic discs
* [Dynamic discs sida 1](https://www.dynamicdiscs.com/)
* [Dynamic discs sida 2](https://www.dynamicdiscs.com/disc-golf-team_a/274.htm)
* [Dynamic discs sida 3](https://www.dynamicdiscs.com/latitude-64-stiletto_a/594.htm)

#### Innova discs
* [Innova discs sida 1](https://www.innovadiscs.com/)
* [Innova discs sida 2](https://www.innovadiscs.com/team-innova/)
* [Innova discs sida 3](https://www.innovadiscs.com/disc/destroyer/)

Övrigt
-----------------------

Denna rapport är författad av Jesper Stolt under kursen Teknisk webbdesign och användarbarhet vid Blekinge Tekniska Högskola.

Bilagor
----------------------
<div class="embed-container">
    <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQjBlNMOq_YqtP2qSHECWCEiKWtEZBY1FVZzWI961koXSzn8IE05IC-Chqa8t5lMj39QENfcNztPicH/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false"></iframe>
</div>
