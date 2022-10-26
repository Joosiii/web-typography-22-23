# Web Typography, 2022/2023
```
name: "Joost Verweijen";
student-id: 500858940;
date: "26th of October, 2022";
```

## Introductie
Voor het vak 'Webtypografie' staan wij voor een behoorlijke opgave. De bedoeling is dat wij de 'Bassline Test' scène van de film 'Blade Runner 2049' zo moeten vormgeven, dat een doof persoon deze net zo kan ervaren dan een goedhorend persoon kan. Hierbij ga ik gebruik maken van typografie, grafische vormgeving en animatie, en dit alle gecodeerd in html/css. Bij het vormgeven van de scène ga ik me proberen in te leven in de dove/slechthorende doelgroep, waardoor ik een zo goed mogelijk resultaat kan neerzetten. In deze `README.md` onderbouw ik mijn keuzes en leg ik mijn proces in het maken van deze keuzes vast.

## Typografie
Ik zal starten met het onderbouwen van mijn typografie-gebruik. De basis van de oplossing voor doven om een film te kijken is uiteraard het gebruik van ondertiteling. Door met ondertiteling aan te geven welke tekst er gesproken wordt, en in de reeds bestaande 'ondertiteling voor doven' welke geluiden er te horen zijn door deze geluiden bijvoorbeeld tussen vierkante haakjes te plaatsen (bijvoorbeeld [Pieptoon]), kan er aan de dove kijker meegegeven worden wat zich qua geluid afspeeld in een fragment. Ik heb er voor gekozen om enkel gebruik te maken van ondertitelde gesproken tekst, en niet van het tekstueel laten zien van geluiden. Deze keuze maak ik omdat ik de geluiden zo ga vormgeven, dat deze enkel door deze vormgeving te begrijpen zijn en een tekstuele toevoeging overbodig en verwarrend zal zijn.

#### Het lettertype
Ik kreeg de keuze om gebruik te gaan maken van het 'systeem-font', of van het font 'Brenner'. Het systeem-font is het font wat je apparaat standaard als font ingesteld heeft staan, en deze heeft vaak weinig opties qua tesktvormgeving en verschillende soorten binnen het lettertype. Enkel een boldvariant, een schuine variant en een onderstreepte variant zijn hiervoor beschikbaar, naast natuurlijk het variëren in tekstgroottes. Zit zou het vormgeven van de tekst wel een leuke uitdaging maken, maar aangezien de opdracht al een uitdaging op zichzelf is heb ik niet voor dit font gekozen.

Ik ben dan ook gegaan voor het 'Brenner' font, een font met vele variërende stijlen, van monospace tot script. Door de vele keuzes kan ik de perfect passende fontstijlen uitkiezen die naar mijn gevoel het meest matchen met de stemmen die in het filmfragment voorkomen.

#### Verschillende stemmen
`voice 1`<br>
Dit is de stem van de 'intercom', de persoon die de hoofdpersoon ondervraagt; een erg monotone, robot-achtige en strenge stem. Ik heb voor deze stem gekozen voor de monospace variant van het font. Monospace wordt veel gebruikt voor zogenaamde Command Line Interfaces, welke dan weer van toepassing zijn op de besturingssystemen van bijvoorbeeld computers en andere devices. Aangezien de stem aanvoelt alsof deze een soort van computer-gestuurd en erg routine-gericht is, vind ik dit een passend font.

`voice 2`<br>
De stem van de hoofdpersoon, eigenlijk een niet heel interessante stem. De man praat met een normale, duidelijk verstaanbare mannenstem, en hier past dan ook een regulier en goed leesbaar font bij. Ik heb daarom ook gekozen voor de normale sans variant van het font. Door de keuze van het font voor de robot-achtige stem onderscheidt dit font goed van het andere font, doordat de tekst van deze stem voor ons op het oog normaal is vormgegeven, is het duidelijk dat deze tekst gesproken wordt door het 'normale mens' die in het fragment te zien is.

`voice 3`<br>
Dan is er nog één extra stem, die eigenlijk maar één zin zegt in het fragment: "F*ck off, skinjob!". Een interessante quote die op een bijzondere manier uitgesproken wordt; het klinkt agressief, geïrriteeerd, maar toch wat zachter, bijna fluisterend en gehaast. Om dit gevoel over te proberen te brengen heb ik een aantal ontwerpkeuzes gemaakt. Ten eerste heb ik gekozen voor de condensed variant van het Brenner font. Dit font is voor mijn gevoel toch wat 'zachter' dan het regular, de letters zijn wat smaller waardoor deze wat minder overtuigend zijn dan de normale letterbreedte. Om het gehaaste gevoel te versterken heb ik de tekst italic gemaakt, schuingedrukt dus. Nu voelde de typografie alleen nog wat te 'lief' aan, dus heb ik de dikte van te tekst iets versterkt en de tekst bold gemaakt.

#### Plaatsing en kleur
Qua plaatsing wilde ik de tekst zo postioneren dat dit niet wegviel buiten het vlak van de video, en tekst en video dus één geheel werden. De tekst onder of boven de video plaatsen was dus geen optie. Daarnaast wilde ik het niet standaard midden en onderin de video plaatsen, aangezien ik de verschillende stemmen op verschillende plekken wilde plaatsen, zo is er nog duidelijker te zien dat het om verschillende stemmen gaat. Ik heb er uiteindelijk voor gekozen om de tekst iets buiten het vlak van de video te plaatsen, aan de zijkanten. Zo ontstaat er toch een soort van diepte, maar weet je ook dat de tekst hoort bij de video. Daarnaast heb ik ervoor gekozen om onderscheid te maken tussen vraag en antwoord. De robot-stem stelt telkens een soort vraag/doet een uitspraak aan de hoofdpersoon, wie vervolgens antwoord geeft/een deel herhaalt. Deze vraag-antwoord dynamiek heb ik versterkt door telkens de vraag links te plaatsen, en het antwoord vervolgens rechts. Aangezien men in de westerse cultuur van links naar rechts leest is dit de meest organische manier om dit vorm te geven. Aangezien de derde stem niks te maken heeft met het gesprek, heb ik deze wel gewoon midden-onderin het frame geplaatst, waardoor deze hier ook los van staat.

De kleur van mijn tekst is ten alle tijde wit. Ik vond het niet nodig om te variëren in kleur, aangezien dit na experimenteren hiermee alleen maar afleidend was en ten koste ging van de leesbaarheid van de tekst. Door gebruik te maken van andere effecten, zoals animaties, heb ik ervoor gezorgd dat het niet nodig was om meer spannende dingen met de tekst te doen, zodat het zo duidelijk mogelijk leesbaar is voor de kijker. Wel heb ik achter de teskt een aardig duidelijke zwarte drop shadow geplaatst, waardoor de witte tekst ook op de lichte achtergronden die voorkomen in het fragment goed leesbaar is.

## Vormgeven van geluiden
Naast het vormgeven van de spraak in het fragment door middel van typografie, moeten de geluiden vormgegeven worden. Dit doe ik door middel van animatie en kleurgebruik. Elk voorkomend geluid zal ik hieronder toelichten en de bijbehorende vormgevingskeuzes onbouwen.

#### Alarm
Het eerste significante geluid dat te horen is is het alarm. Bij een alarm denk je al gauw aan de kleur rood, dit komt doordat veel alarmen in de echte wereld rood zijn, denk bijvoorbeeld aan typisch luchtalarm. Ik maak bij het horen van het alarm dan ook gebruik van een felrode achtergrond kleur. Toch is dit niet passend genoeg, het alarm is erg hard en intens. Hierom laat ik ook de video heftig trillen, dit versterkt de impact van het geluid van het alarm, en hangt ook samen met bijvoorbeeld een wekker, wat een ander soort alarm is. Een wekker trilt wanneer deze afgaat, en zo correleert dit met mijn vormgeving. Dit alarm komt vaker voor, en in sommige gevallen bouwt deze zichzelf een soort van op. Wanneer dit gebeurt maak ik gebruik van een zoom van de video, waar omheen geleidelijk een rode shadow ontstaat. Bij het klinken van het alarm komt vervolgens de originele vormgeving van het alarm in beeld. Zit zoomen en het 'infaden' van de rode gloed zorgen voor het gevoel dat het alarm zich opbouwt.

#### Sirene
Ook is er een sirene te horen in de filmscène. Deze sirene heeft wat minder impact dan het alarm, en deze mag dus iets minder heftig zijn. Ik heb daarom gekozen om voor deze sirene enkel een shadow toe te voegen aan de video. Deze shadow veranderd snel van rood, naar blauw, en weer naar rood, zoals men gewend is van de standaard politie of ambulance sirene welke ik hiermee wilde nabootsen.

#### Pieptoon
Nu de pieptoon, eigenlijk het meest belangrijke en irritante geluid van de scène. Zonder deze pieptoon heeft het einde van deel 1 van het fragment vrij weinig betekenis, maar wanneer je met geluid aan het fragment bekijkt word je geconfronteerd met deze bloedirritante opbouwende pieptoon. Mijn missie was dan ook om een zo irritant mogelijke visualisatie te maken welke de pieptoon moest evenaren. Hierin ben ik naar mijn mening wel geslaagd, in plaats van een opbouwende pieptoon is het een opbouwende witte flits geworden. Deze flits begint erg langzaam en moeilijk zichtbaar, maar naarmate de piep versterkt, hoe feller en sneller de flitsen zich afspelen. Net voor de climax zijn de flitsen zo snel en fel dat je hele scherm ermee bedekt wordt en je amper meer kan focussen op het fragment. Tot de flitsen plotseling stoppen, net als de piep in de scène.

#### Sciencefiction muziek
Wanneer deel 2 van het fragment begint start er een sciencefiction muziekje op de achtergrond, dit deel heeft duidelijk een andere sfeer dan het eerste deel. Het is nu wat zweveriger en je hebt het gevoel alsof het zich afspeelt in de ruimte. Om deze rede heb ik een bewegende sterrenachtergrond toegevoegd aan dit deel. Om het 'zweverige' nog wat extra te versterken laat ik de video heel rustig heen en weer roteren.

#### Ringtone
De ringtone die in deel 2 voorkomt heb ik simpel vormgegeven met een kleine trilling van het scherm. Deze ringtone valt bij het beluisteren van het fragment niet echt op, dus deze moet ook subtiel zijn. De trilling is daarom ook korter en minder heftig dan bijvoorbeeld de trilling van het alarm.

## Exclusive Design Principles
De 'Exclusive Design Principles' zijn principes die je helpen bij het ontwerpen van een product of opdracht voor een exclusief persoon. Deze principes heb ik meegenomen en getoetst tijdens het maken van deze opdracht, en ik zal dan ook bespreken hoe deze hiermee samenhangen.

#### Study Situation
Het onderzoeken van de situatie van je doelgroep/persoon is erg belangrijk. In mijn geval was het dus belangrijk dat ik me zo goed mogelijk inleefde in een doof persoon. In mijn geval was er een hele simpele oplossing om dit te doen, namelijk de video bekijken zonder geluid. Door dit te doen heb ik de vele geluiden zo goed mogelijk na kunnen bootsen en daarmee het gevoel en de sfeer die de geluiden meegeven kunnen vormgeven. Vooral bij het deel met de pieptoon was dit erg belangrijk, zonder geluid gebeurt er helemaal niks in dit fragment, maar met is dit ineens heel anders en zelfs irritant. Door zonder geluid mijn ontwerp te testen heb ik dit zo irritant mogelijk kunnen maken.

#### Ignore Conventions
Soms is het belangrijk om de gebruikelijke dingen te negeren, zo ook in het ontwerpen van een filmfragment voor doven. Een goed voorbeeld in mijn proces is het weglaten van de gebruikelijke beschrijvingen van geluiden, zoals eerder besproken. In hedendaagse dovenondertitelingen worden deze vaak gebruikt, maar ik laat deze weg omdat de toegevoegde vormgeving sterk genoeg is op zichzelf.

#### Prioritise Identity
Een bepaalde indentiteit van de doelgroep kan ik in dit geval moeilijk meegeven, aangezien het ontwerp niet op een bepaald persoon of een bepaalde smaak gericht is. Wel kan ik de vormgeving zo 'film-achtig' mogelijk maken. De effecten mogen lekker uitvergroot een duidelijk, net alsof je in een filmzaal zit waar alle geluiden ook erg hard en overdreven klinken. Ook bijvoorbeeld de science-fiction identiteit komt naar voren door het gebruik van de sterren en het zweverige gevoel.

#### Add nonsense
In sommige gevallen is het leuk voor doven om zogehete 'nonsense' toe te voegen, onzin dus. Naar mijn mening is het in het geval van een filmfragment alleen maar afleidend als er nonsense wordt toegevoegd, zelfs als iets zonder geluid bekeken wordt. Een film moet je pakken als kijker, en dient dus de volledige aandacht op zich te hebben. Ik wilde dan ook alles in en rondom het frame van de video houden, en geen rare dingen eromheen zetten waardoor de ogen van de gebruiker van het fragment afgestuurd worden. Het fragment is al interessant genoeg op zichzelf en de gebruiker zal moeten opletten om deze te begrijpen, dus om hieraan 'nonsense' toe te voegen zou in dit geval geen toegevoegde waarde hebben.

## Experimenten & Feedbackverwerking
Binnen mijn proces in het uitvoeren van deze opdracht heb ik uiteraard ook geëxperimenteerd en geïtereerd. Ik zal dan ook omschrijven welke 'experimenten' ik uit overweging heb besloten niet in het uiteindelijke ontwerp te laten voorkomen. Daarnaast zal ik de punten van feedback noemen die ik wel dan te niet heb meegenomen in mijn ontwerp.

#### Experimenten
De volgende vormgevingselementen heb ik overwogen toe te voegen, door dit toe te voegen en voor mijzelf (en soms klasgenoten) te testen.

- Ik heb wat geëxperimenteerd met de tekstkleur, zoals eerder genoemd. Zo heb ik bijvoorbeeld geprobeerd om "F*ck off skinjob" een rode kleur te geven, om dit nog agressiever te laten overkomen, of om sommige woorden in bepaalde zinnen een andere kleur te geven om deze te benadrukken. Dit deed de leesbaarheid alleen niet ten goede en maakte het geheel iets te druk en onrustig, en dit wilde ik liever voorkomen tegenover de minimale toevoeging die ze hadden aan aan het overbrengen van het fragment.
- Het fragment start ook met een geluid, wat klinkt als een soort van ruimteschip. Ik heb gekeken of ik hiervoor een animatie kon toevoegen. Ik kwam hierbij op een zoom van het filmpje, waar het fragment dan dus mee start. Echter ontstond er hier een soort van dubbel effect door, aangezien in het fragment zelf er ook al wordt ingezoomd op het gebouw waar de scène zich afspeelt. Hierdoor vond ik het niet nodig om deze zoom toe te voegen; het fragment op zichzelf beeld dit geluid naar mijn mening al voldoende uit.
- Bij deel 2 van het fragment is er onder de muziek nog steeds een lichte piep te horen. Om consistentie te houden in het ontwerp vond ik dat ik hiervoor alleen weer het witte knipper licht kon gebruiken. Na dit toegevoegd te hebben op lage opacity en snelheid, vond ik het toch iets te opvallend en overrompelde het het ruimtebeeld een beetje. Na overweging heb ik besloten dat de piep in deel 2 niet belangrijk en significant genoeg is voor het fragment, en niks bijdraagd aan de vernieuwde sfeer van deel 2 ten opzichte van deel 1, en daarom is een vormgevingselement voor dit geluid weggelaten

#### Feedback
Ik heb op verschillende momenten feedback ontvangen, zoals tijdens het feedbackmoment in de les en door mijn ontwerp te laten zien aan klasgenoten. Feedbackmoment 2 heb ik helaas moeten missen door problemen met het OV, maar deze heb ik vervangen door met klasgenoot Coen een grondige feedbackronde te doen.

- In feedbackmoment 1 kreeg ik de tip om de witte flitsen meer geleidelijk te maken, aangezien ze nu om de zoveel tijd pas versnelden. Ten eerste heb ik onderzoek gedaan naar of het mogelijk is om met css een animatie vaker en exponentieel sneller af te spelen. Dit bleek lastig te zijn, hetgene wat het meest in de buurt kwam was gebruik maken van `cubic-bezier`, maar dit gaf niet het gewenste resultaat. Ik heb daarom maar handmatig de animatie een stuk vaker van snelheid laten veranderen, waardoor het nu als nog (een soort van) lijkt alsof de animatie geleidelijk van snelheid verandert.
- Ik kreeg ook feedback over de momenten dat ik de 'zoom' had ingesteld bij de 'opbouw' van het alarm. Dit voelde nog niet helemaal als een opbouw van een alarm, aangezien het alleen een zoom was op dit moment. Naar aanleiding hiervan heb ik besloten om hieraan een rode shadow toe te voegen.
- De ruimte sfeer die ik wilde creëren in deel 2 was nog een beetje saai en simpel, bleek uit feedback van klasgenoten. Sommige zagen deze op het eerste gezicht bijna niet. Naar aanleiding daarvan heb ik ervoor gezorgd dat deze achtergrond langzaam beweegt, en ook de video een lichte rotatie animatie meegegeven zodat het wat zweveriger wordt.
- Ik kreeg nog de tip om nog iets toe te voegen voor het piepgeluid in deel 2, maar zoals besproken bij het experimenten gedeelte hierboven heb ik besloten hier niks mee te doen
