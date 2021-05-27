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

Det finns risker som det gäller att vara uppmärksam kring och agera vid behov.

## Upphovsrätt

