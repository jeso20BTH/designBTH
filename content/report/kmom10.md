---
Title: Projekt
Description: Report kmom10 page
template: sidebar
menu:
    - url: kmom01
      text: Kursmoment 1
    - url: kmom02
      text: Kursmoment 2
    - url: kmom03
      text: Kursmoment 3
    - url: kmom04
      text: Kursmoment 4
    - url: kmom05
      text: Kursmoment 5
    - url: kmom06
      text: Kursmoment 6
    - url: kmom10
      text: Projekt
# hidden: true
---

Projekt
==================
Implementerade krav
-------------------
En genomgång av samtliga implementerade krav för projektet. Jag har valt att göra en webbplats åt artisten Art Ist.
### Krav ett - Webbplats
Jag började med att göra om allt från början, för att jag känner att repetition ökar inlärningen, plus att jag ´ville lägga upp mycket av min design på annat sätt än hur min portfolio såg ut. Det jag återanvända var för att sätta upp session och uppdatera CImage, där jag kopierade in den data jag behövde. I övrigt har jag gjort allt från grunden. Jag upplevde att jag hade större förståelse för dom olika stegen man gjorde för att sätta upp webbplatsen nu andra gången jag gjorde det mot första gången jag gjorde det. Alla ikoner som finns på sidan hämtas med hjälp av FontAwesome.

### Krav två - Tema
För mitt tema valde jag att utgå från hero-bilden som finns på samtliga för att välja färger. Sen valde jag ett monokromt tema utifrån det. Jag ville sedan skapa en sida där bilder och viktig text var framhävd. Det gjorde jag genom att använda olika bakgrundsfärger på olika områden på sidan. Nästa steg var att hitta teckensnitt som passade webbplatsens syfte. Jag gjorde det med hjälp av google fonts och bläddrade bland typsnitten tills jag hittade teckensnitt som passade sidan. Jag har valt att dela upp all min SASS-kod i flera moduler för att enkelt hitta den kod jag behöver uppdatera, den andra anledningen är för att jag visste att jag ville göra ett alternativt tema direkt från början och den skulle underlätta den delen, då jag bara behövde ändra vissa moduler. Hur jag har delat upp SASS-koden finns dokumenterat i den dolda sidan på about inom projektet.

### Krav tre - Responsivitet och tillgänglighet
Jag upplever att mina sidor uppfyller dom flesta för responsivitet, jag hittar inga delar som ser sämre ut på mobil jämfört med dator. Däremot kan sidan se lite konstig ut i devtools för små enheter, som att den inte riktigt fyller hela skärmen, Så är inte fallet i verkligheten, jag har själv testat det på min telefon.

#### Responsivitet
Hela min sida är uppbyggd av grid, förutom header och footer, dom är båda uppbyggda av flex-box. För header och footer så gör den uppbyggnaden att responsiviteten sker automatiskt, vid storleksändringar. För att göra sidan tydligare på små skärmar har jag dolt copyright-texten i footern samt att naviationen byter utseende på små skärmar till en rullist. För övriga del av webbplatsen ändras antalet kolumner beroende på skärmstorlekar, på små skärmar är antalet kolumner oftast bara en medan större skärmar har två till tre olika. Dm olika divar med innehåll är samtliga styrda av antingen flex-box eller grid eller en kombination av båda för att även där vara responsiva vid ändring av storlek.

#### Tillgänglighet
Med hjälp av lighthouse i Google chrome så fick jag vad som behövde förbättras för att öka responsiviteten, med hjälp av dessa tips var det bara att utföra ändringar. Det stora var att det var för dåliga kontrast mellan bakgrund och text, Det löste jag genom att göra samtliga bakgrundsfärger lite mörkare. Det andra var att det saknades lite tagar eller behövde ändras lite, som följde med från starten av sidan, där ibland språk-tag. När jag hade uppdaterat felen på första sidan så fanns det inga fel på någon av de andra sidorna heller utan alla fel löstes samtidigt. Jag kollade även min sida på TopTal för att se hur den klarade sig för färgblinda, jag upplevde att min sida var fullt fungerande med samtliga filter.

### Krav fyra - Alternativt tema
Jag ville att mitt alternativa tema även det skulle uppfylla krav för responsivitet och tillgänglighet. Jag valde därför att fortsätta använda mig av grid och flexbox på hela sidan. Det jag behövde lägga till i min SASS-kod var nya moduler för varje sida. Jag ville utmana mig och skapa en tråd som användaren kunde följa genom sidan både för startsidan men också om-sidan. Jag var först inne på att lösa det antingen med egenritade bilder eller bilder utan licens på någon hemsida. Jag kom däremot fram till att jag kunde lösa det med hjälp av divar som placerades på önskade platser i gridet, dessa divar, fyllde upp hela ytan av sin ruta. Jag kunde då inom dom divarna placera ytterligare en div som med hjälp av position absolute/relative kunna placera ut divarna som jag ville. För att sedan skapa tråden använde jag mig av border dashed. Färgerna kunde jag enkelt uppdatera med hjälp av variabler. Jag valde då olika nyanser av grått och svart för att ge ett mörkt tema. Jag ville även ha med knappar i footern likt kursmomentet där vi la till ett alternativt tema. Jag ville däremot inte ha dom i samma grupp som sociala länkar. Det jag då gjorde var att skapa en ny grupp i -meta som jag kunde loopa igenom på samma sätt som social för att få fram knappar för att förstöra sessionen och byta tema.

### Krav fem - Analys aktuell webbplatsdesign
Jag ville försöka göra analys på sidor som på något sätt kunde kopplas samman med projektet jag gjort. Därför valde jag att analysera fotografers sidor. Jag valde att analysera hur sidorna använde designprinciper och bilder. Det var för att jag tyckte det var dom mest intressanta områdena att undersöka. Jag tog sedan hjälp av sidan med designprinciper för att dokumentera vilka designelement som användes. För bilderna använde jag mitt eget intryck gällande storlek och färger på bilder. På så sätt kunde jag hitta mönster som var gemensamt för samtliga sidor.

### Krav sex - Analys valfri
Eftersom jag i den första analysen gick in på områdena designprinciper och bilder. Kändes det mest logiskt att för denna analys fokusera på färger och teckensnitt. Jag tänkte först att jag skulle utföra analysen på samtliga undersidor, men kom då fram till att det blev väldigt repetitivt då alla delar gällande färg och teckensnitt var den samma. Det jag då istället valde att göra var att analysera mina båda teman. För att få till en större analys.

Om projektet
------------
Jag tyckte projektet gick bra att genomföra. Mycket funkade utan större problem. Jag tror sammanlagt har jag lagt mellan tjugo och trettio timmar på projektet. Det jag hade problem med var först att hitta bilder då jag ville ha ett stort antal eftersom det var en fotograf som är min kund. Men med hjälp unsplash kunde jag hitta det jag det jag behövde. Det andra problemet jag hade var att jag fick den att hämta bilder från portfolio istället för kmom10, Det berodde på att jag hade missat att uppdatera den delen i htaccess, jag  hade uppdaterat från mos till jeso20. Jag upplevde delen som lite otydlig, då det inte fanns dokumenterat, Det löste sig med lite hjälp via discord. Jag tycker det är ett rimligt projekt för kursen utifrån min tid jag lagt projektet ligger den inom uppskattningen för hur lång tid man kommer lägga ner på projektet. Det var även ett bra projekt då den omfattade allt vi gått igenom under kursen.

Om kursen
---------
Jag tycker detta både har varit den svåraste och samtidigt mest lärorika kursen hittills. Jag vet inte hur kursen var innan den gjordes om. Däremot har jag bara gott att säga om hur den är uppbyggd nu. Det finns otroligt mycket material både från högskolans sida men även sidor, och böcker som dom olika kursmomenten länkar till. Jag upplever att det materialet dels var till storhjälp för denna kurs men att även många av sidorna kan komma bra till hands även efter avslutade studier. Jag ger kursen full pott främst på grund av hur lärorik jag upplevde den.
