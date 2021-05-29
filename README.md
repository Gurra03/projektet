# Webbutckling 1 projektet

## Info
[Hemsida](https://gurra03.github.io/projektet/)

Namn: Gustav Norberg

Klass: TE19

Skola: Nyköpings Gymnasium Gripen

Datum: 24 Maj 2021

## Hemsida

Hemsidan är menad att vara en centralbank för information om konservatism och den konservativa ideologin. Sidan kommer med en info bank om konservtaismens historia, fyra av de större inriktningarna och lite info om några konservativa partier i världen. 

## Support

Det är inte säkert att support kan garanteras då det beror på version till version och operativsystem

| MacOS Safari     | Chrome    | Explorer    |  Firefox    |  Opera    | Yandex    | iPhone Safari   |
| ---------- |:---------:|:-----------:|:-----------:|:---------:|:---------:|:----------------|
| 14.1         | 90        | 11          | 88          | 76        | 14.12     | 14.0              |

## Förbättringar

En förbättring som jag skulle kunna göra är att göra sidan snyggare med CSSen, just nu tycker jag den ser relativt generisk ut och jag kunde ha gjort att den ser bättre ut. Jag kunde även ha spnderat lite till på att få till en bra bakgrund till sidan. Jag kunde även minska css koden lite då den är väldigt lång.

### Annan förbättring

En annan förbättring jag skulle kunna göra är att texten skulle kunna vara mindre, där den ibland känns för stort, det var större än nu men jag har fortfarande gjort texten lite väl stor. Jag skulle även kunnat ha använt platsen mer. Det fanns vissa områden på sidan som inte användes på sidan.

## Lånad kod

Den enda lånade koden som jag använde var för navbaren. Där lånade jag och modifierade koden från en tidigare uppgift som vi hade om javascript.

### Javascript kod
```js
let nav = document.getElementById('nav')
let x = document.getElementById('x')

x.addEventListener('click', function() {
    nav.classList.toggle('open')
})

document,addEventListener('keydown', function(event) {
    if(event.key === 'Escape' && nav.classList.contains('open')) {
        nav.classList.toggle('open')}
})
```

### CSS Kod
```css
.slide {
    background-color: #40cac5;
    width: 600px;
    height: 300px;
    position: relative;
    
    position: fixed;
    top: -300px;
    right: 0;
    
    transition: .3s ease-in-out;
}

.slide a {
    font-family: 'Source Serif Pro', serif;
    color: white;
    font-size: 350%;
    display: flex;
    justify-content: center;
}

.slide span {
    background-color: #40cac5;

    border-bottom-left-radius: 10px;
    border-bottom-right-radius: 10px;

    cursor: pointer;
    
    display: block;
    height: 150px;
    width: 150px;

    font-family: Arial, "Helvetica Nueue", sans-serif;
    font-size: 350%;

    position: absolute;
    right: 50px;
    top: 300px;

    display: flex;
    justify-content: center;
    align-items: center;
}

.open {
    top: 0;
}
```

### HTML Kod
```html
    <script src="nav.js"></script>
```

### Säkerhet kring lånad kod

Det finns alltid risker kring att ta eller låna någon annans kod till ens hemsida. Om man inte kollar igenom och vet vad man ska leta efter finns det en risk att primärt om det är en javascript kod att den kan innehålla någon form av skadlig kod. Vid längre kod blir risken större då det finns mer att kolla igenom och mer rum att gömma skadlig kod. Om man inte vet vart eller vem en kod kommer ifrån kan det finnas en risk att man får med sig en skadlig kod till sin hemsida. Den största risken finns med koder som t.ex. lightbox där man laddar ner en komprimerad fil som man måste extrahera ur där det finns tre fyra kod filer, alla med olika funktioner och flera hundra rader kod.

Det kan då vara bra att kolla igenom koden för att se om något suspekt finns med. Om man inte är riktigt säker på koden ska man nog inte använda den. Som med mycket annat på internet gäller det att använda sunt förnuft, ett exempel ska man inte ladda ner kod från vilken sida som helst utan använd t.ex. GitHub från etablerade och säkerställda kodare.

Men det kan inte vara skadlig kod utan användardata kan skickas till den som skapat koden, detta likt att kodskaparen har implanterat skadlig kod sätter en stor risk hos de som besöker hemsidan. Det kan även vara att de sätter in kod som spionerar på en själv men även andra på hemsidan.

Det finns risker som det gäller att vara uppmärksam kring och agera vid behov. Den som skapade sidan och använde tredjepartskoden är den som hålls ansvarig om något går snätt, och om det råkar vara så att tredje parts koden som används samlar in data utan vetskap eller att den kommer med skadlig kod är det sidoskaparens ansvar för han/hon bestämde sig för att använda koden.

## Upphovsrätt och bilder

Att tänka på upphovsrätten är viktig, särskilt när det kommer till offentliga sidor.

### Vad är upphovsrätten?

Upphovsrätten är en samling lagar och regleringar kring hur användandet och publicerandet av material, teckningar och videor får användas och publiceras. Material som är skyddat under upphovsrätten får inte publiceras utan upphovsmannens egna tillstånd. Reglerna kring när upphovsrätten upphör varierar frånl land till land men brukar vara fram till upphovsmannens död + 75-100 år.

### Material på denna hemsida.

Jag använde överväldigande gratis bilder från sidor som har upphovsrätt över bilder och tillsånd att använda bilderna. Det finns däremot vissa bilder som ska vara upphovsrättsskyddade men får användas gratis vid angivning av vart bilden är tagen eller att bilden faller under creative commons license.

> Creative Commons licenses give everyone from individual creators to large institutions a standardized way to grant the public permission to use their creative work under copyright law. From the reuser’s perspective, the presence of a Creative Commons license on a copyrighted work answers the question, “What can I do with this work?

[-Creative Commons hemsida](https://creativecommons.org/about/cclicenses/)

Citate förklarar hur en Creative Commons licens fungerar och vad den gör. Alla bilder som faller under upphovsrättslagen som används på sidan har en creative common license. Den orginella tanken vid artikeln om [partier](https://gurra03.github.io/projektet/partier.html) var att bredvid texten om partierna sätta deras logga, men på grund av problem med att få tillstånd att använda loggorna valde jag att sätta partifärgerna som bakgrund på rubrikerna istället som en plan B.

## Webbhotell

Ett webhotell är en sida där man kan lagra filer och gör det lätt för användare att kunna publicera sina hemsidor på World Wide Web. Det finns många webbhotell ute på World Wide Web som man kan använda. Men alla är inte seriösa och man ska vara försiktig med vilket man väljer. 

### GitHub

GitHub är ett gratis webbhotell som ägs av Microsoft. Hotellet fungerar som en lagringsplats där man kan lagra källkod såsom skript och markdown filer. Med hjälp av GitHub Pages kan man på ett enkelt sätt lansera och skicka ut hemsidor på internet. Det finns möjlighet att betala och få yttligare förmåner som kommer med sidan. Eftersom GithHub ägs av Microsoft kan den trots att hotellet är gratis kan den vara mer pålitligt då vi vet att servarna är säker och supporten är bra. Det blir en äelig spelare på spelplanen.

### Loopia

Loopia är ett webbhotell som ägs av Axcel. De erbjuder ett sätt förvara filer med sitt webbhotell och skapar både möjlighet att bygga en egen hemsida men även anförskaffa domännamn till ens hemsida. Till skillnad från GitHub kostar det att använda deras tjänster. Priset för webbhotellet är 89 kr/månad, men de erbjuder 39 kr/månaden under det första året. 2019 var de inblandande i en kontrovers där det ska ha sagts att de har skickat ut bluffakturor till sina kunder och användare. Det har även sagts att deras support ska vara bra men det är långa väntetider. Flera av deras tjänster ligger bakom betalningar, ett exempel är deras SSL/https paket. 

## Teckenkod

Teckenkodningen som är standard och alltid bör användas är UTF-8. Om UTF-8 inte anges korrekt kan det skapa problem med sidan att bokstäver och tecken inte visas på rätt sätt. Det som blir det stora problemet då är att alla kan inte läsa bokstäver som t.ex. åäö kan så inte se hemsidan på det sätet som det ska visas. Det enklaste sättet att fixa en felangiven teckenkodning är att ange den rätta kodningen som exempel UTF-8.

Anledningen till att UTF-8 ska användas i alla lägen är att den teckenkodningen täcker nästan alla bokstäver och därför blir det enklast att sättet att skriva innehållet på hemsidan. Exempel ska man skriva ut meningen "Jag älskar att äta och göra kakor" men anger fel teckenkod kan det se ut så här "Jag Ã¤lskar att Ã¤ta och gÃ¶ra kakor".

Med en hel hemsida där vissa bokstäver inte visas ovh görs väldigt svår att läsa kommer bidra till att sidan inte blir användbar. Inte nog med att den kan bli svårtydd så kan den även få problem med att bli indexerad i sökningar då de rätta tecknen inte visas upp.

## Etik och Intigritet

Etik och integritet är väldigt viktigt på internet. Särskilt delen med integritet. Precis som i den analoga världen ska alla ha tillgång och möjlighet till att bibehålla sin integritet. Insamlandet av användardata som företag gör nu är oetiskt, man får inget privatliv och man får inte reda på vart ens data hamnar. Begreppet integritet och etik är väldigt stort och allting kan inte tas upp här. 

Det kanske största inskränkingen på den personliga integriteten på nätet är företagen som samlar in massiva mängder data om användaren, det kan vara allt från personlig data som namn, ålder och land till data som sökhistorik och de sidor man varit inne på. Det många företag gör då är att skicka den datan vidare till tredje parts företag och annonsörer som då skickar personaliserade annonser och reklam till användaren. Det brukar därför oftast skämta att Google vet mer om dig än dina föräldrar. 

Denna intensiva spårning av användardata och det folk gör på internet kan visa sig vara en stor risk för användaren. Datan som samlas in skulle kunna användas av auktoritära regimer för att spåra deras medborgare och se till att motståndare till deras regim inte kan uttrycka sina åsikter. 

Ett stort exempel är om ett företag samlar in en mängd känslig data och de utsätts för ett intrång av hackers. Den datan kan då läckas ut och användas i bland annat utpressningssyfte. Det är därför väldigt viktigt att känslig och personlig datan hålls säker, det kan vara användandet av längre och komplicerade lösenord. Ettbra sätt att hantera lösenord är att sätta in dem i en krypterad lösenordshantera som t.ex. iPin som krypterar lösenorden och låses endast upp med en kod in till appen.

## Utvärdering

Sidan tycker jag generellt sett blev väldigt bra. Jag är stolt över att jag kunde få färdigt den, den är anpassad efter flera upplösningar som 4k, 1440p, 1080p och mobiler. Sidan fungerar bra på alla stora moderna webbläsare som Chrome, Edge, Safari, Firefox men även Internet Explorer. Jag förde en logg på vad jag gjorde vilket kunde leda till att jag bland annat kunde hålla koll på de nuvrande problem som fanns med hemsidan.

Ett av de största problemen som jag mötte var dock CSS koden som inte alltid ville fungera, den bliv tillslut så lång att jag hade svårt att rensa koden utan att veta vad som kommer förstöra och vad som kommer hjälpa. Det ledde till att jag var tvungen att skriva om hela CSS koden vilket drog värdefull tid som jag kunde ha användt till förbättringar och finputsning på koden för att få sidan att se bättre ut eller fungera bättre på tidigare versioner av Google Chrome som exempel.

Som sammanfattning, sidan fungerar som den ska. Hade några fel i valideringen som fixades till i både HTML koden och CSS koden. Sidan fungerar som den ska även om CSS koden kunde gjorts bättre för att sidan skulle vara snyggare att se på. Jag följde mig enligt upphovsrättsstandarder och lånade bara en kod som jag vet inte skulle komma med problem för sidan.  