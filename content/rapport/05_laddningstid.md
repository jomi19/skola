Laddningstid
=============

Undersökning om trender och likheter mellan några teknik ehands sidor.

Urval
--------------
Jag har valt tre stycken speltillverkare/spelbutikers hemsida både blizzards och eas hemsida är rätt lika hur dom är uppbygd med mycket bilder och efekter medans steams hemsida är lite mer enkel så jag tror steam kommer ha det bästa resultatet.  

[Blizzard](https://www.blizzard.com/en-us)  
  
[Ea](https://www.ea.com/sv-se)  
  
[Steam](https://steampowered.com)  


Metod
---------------

Jag har använt mig av firefoxswebbläsare för att läsa av nätverksstatistiken till varje sida, för att läsa av poängen har jag använt mig av [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/).

Resultat
---------------

Steam3


    
[FIGURE src=image/rapport/steam.png alt="Steam" caption="Steam" class="center"]  

| Försök   | Laddtid (s)   | Storlek(MB) |Requests  | Desktop Poäng  | Mobil Poäng  |
|----------|:-------------:|:-----------:|:--------:|:--------------:|-------------:|
| 1        | 5,85          | 6,95        | 94       | 92             | 67           |
| 2        | 4,63          | 5,56        | 94       | 94             | 69           |
| 3        | 4,09          | 5,56        | 94       | 73             | 52           |
| Snitt    | 4,85          | 6,02        | 94       | 86,3           | 62,6         |

Steams hemsida är lite enklare bygd med inte fullt lika stora bilder och designelement som rör sig.
Dom har inget bild spel eller nåtgot sådant. Laddtiden på 4,85sec var den överlägset kortaste av dom tre sidorna jag testade.
Request och storlken på sidan var mindre än dom andra två. Den fick även bäst i både desktop och mobil poäng.


Blizzard

   
[FIGURE src=image/rapport/blizzard.jpg alt="Blizzard" caption="Blizzard" class="center"]

| Försök   | Laddtid (s)   | Storlek(MB) |Requests  | Desktop Poäng  | Mobil Poäng  |
|----------|:-------------:|:-----------:|:--------:|:--------------:|-------------:|
| 1        | 10,02         | 12,18        | 130      | 72            | 17           |
| 2        | 7,98          | 12,18        | 130      | 72            | 13           |
| 3        | 7,9           | 12,18        | 130      | 74            | 10           |
| Snitt    | 8,63          | 12,18        | 130      | 72,6          | 13,3         |

Blizzard sida inhåller många stora bilder som rör sig och olika effekter på den sidan i sig är roligare och väcker mer intresse än steams men det kom till en stor kostnad på laddtiden som i snitt är ca 4sekunder längre än steams. Blizzards laddtid ligger i snitt på
8,63 sekunder vilket jag tycker känns lite långt men sidan går använda innan den har laddat det är bara bilderna som inte kommit upp.
Storleken på sidan var 12,18mb varje gång jag laddade sidan requests var också lika många varje gång (130st). Men sidan fick okej resultat på desktop poängen men väldigt dåligt på dom mobila poängen.


Ea

[FIGURE src=image/rapport/ea.png alt="Ea" caption="EA" class="center"]

| Försök   | Laddtid (s)   | Storlek(MB) |Requests  | Desktop Poäng  | Mobil Poäng  |
|----------|:-------------:|:-----------:|:--------:|:--------------:|-------------:|
| 1        | 49,86         | 16,17       | 202      | 69             | 37           |
| 2        | 53,35         | 15,53       | 206      | 75             | 29           |
| 3        | 48,04         | 16,17       | 204      | 75             | 35           |
| Snitt    | 50,41         | 15,95       | 204      | 73             | 33,6         |

Ea hemsida var inte rolig att ladda då det tar hela 50,41sekunder på min lapotop i snitt för mig är det väldigt frustrerande att vara inne på sånna sidor. Det tog runt 15sekunder innan menyn kom fram och man kunde börja bläddra igenom hemsidan. Sidan var i snitt 15,95mb stor och har 204 requests i snitt. Desktop poängen var dock min höga laddtid helt okej där den snittar 73 och mobila poängen med ett snitt på 33,6 är bättre än blizzards men fortfarande ligger den i rött enligt [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/).


Analys
----------------

Testets vinnare är steam på alla punkter, jag trodde den skulle vinna innan jag satt igång mina tester men med en så pass stor marginal som den gjorde. Steam var även den ända sidan som hade ett godkännt resultat i mobila poäng trots att den bara låg i gul zon på [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/). Fast då jag använder min mobil och surfar på dom olika sidorna märker jag ingen jätte skilnad mellan dom det trots att jag tömmer all webbplatsdata innan jag surfar in på dom. Ea hemsida upplever jag bättre på telefonen än vad jag gör på min laptop men då har jag full 4g täckning blizzards hemsida tycker jag inte heller är några problem att använda. Det som tar tid att få upp där är bildspelet dom kör med längst upp på sin hemsida så jag kan tänka mig att den drar ner deras score rätt mycket.

Då jag använder hemsidorna på datorn är det bara EA hemsida jag får en sämre upplevelse av då det faktiskt tar 15sekunder innan jag kan börja bläddra igenom den riktigt och efter det upplever jag sidan som lite hackig. Blizzards sida går börja scrolla i nästan direkt men menyn kommer upp förnst efter 3 sekunder men samma som på deras sida på mobilen så tar det ett tag innan deras stora bildspel längst upp på sidan kommer upp så även här är den klar sist. På steams hemsida kommer mycket upp nästan direkt jag laddar om hemsidan är lite bilder som laddas in eftersom dom sista sekundrarna.


Så min slutsats är att vill ea och blizzard få bättre laddnings tider samt bättre score i testen måste dom kompromissa lite med sina bilder och inehåll. För mig hade jag en bra upplevelse på alla tre hemsidorna via mobilen och är endast EA hemsida via min laptop jag fick en dålig upplevelse av vilket även märktes på laddnings tiden dom hade. Jag tycker det är en kompromiss som blizzard lyckats bra med jag tror målgruppen dom har oftast har lite bättre datorer och en bra uppkoppling. Men dom hard mycket att spara på med tex bildformaten då dom endast använder jpg och png bilder istället för bilder i nyare format så där skulle dom kunna spara in på mycket dataanvänding.

Referenser
----------------

Övrigt
----------------

Joakim Mikaelsson