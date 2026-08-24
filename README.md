# SuperCar Vault - The Ultimate Webshop (herexamen)

Webshop voor exclusieve auto's, gemaakt met enkel HTML en CSS voor het vak Static Web.

## Projectstructuur

index.html -> homepage met intro, productgrid en "waarom ons"
css/style.css -> alle styling van de publieke site
producten/ -> 6 productdetail-pagina's (1 per auto)
admin/ -> beheerdersgedeelte (apart, zakelijk design)
  login.html
  dashboard.html -> productinventaris in tabelvorm
  product-form.html -> formulier om een product toe te voegen/aan te passen
  admin.css
afbeeldingen/ -> productfoto's en logo

## Plan van aanpak

- Homepage stap voor stap opgebouwd: skelet, header, hero-sectie, productgrid met 6 producten, "waarom ons"-blok, footer.
- CSS geschreven (variabelen, reset, flexbox-layout voor header/hero/grid/footer, responsive breakpoint op 650px).
- De 6 productdetail-pagina's gemaakt (specs, reviews, gerelateerde producten).
- Admin-gedeelte gebouwd: login, dashboard met productinventaris-tabel, formulier met alle input-types.
- Alles getest in de browser (links, afbeeldingen, responsive), laatste bugs gefixt, README afgewerkt.

## Gebruikte technieken

- Layout: Flexbox voor alle positionering (header, hero, productgrid, footer, formulieren).
- Typografie: Google Fonts - "Bebas Neue" voor titels (h1/h2/h3), "Inter" voor gewone tekst.
- Responsive: 1 breakpoint op 650px (publieke site) / 600px (admin). Onder die breedte passen de flex-items niet meer netjes naast elkaar, dus worden ze gestapeld met flex-direction: column.
- Admin-gedeelte heeft bewust een ander, zakelijker kleurenschema (licht met blauwe accent) dan de publieke site (donker thema), zoals gevraagd in de opdracht.
- CSS-variabelen (:root) voor kleuren en randradius, zodat die op 1 plek aangepast kunnen worden.

## Bronnen
- w3schools
- canvas cursus
- Google Fonts: https://fonts.google.com/ (lettertypes Bebas Neue en Inter)
- ChatGPT gebruikt als hulpmiddel voor het geven van ideeën en feedback.
- ChatGPT gebruikt om de pagina's te verbeteren en fouten in de HTML/CSS op te sporen en op te lossen.
- ChatGPT gebruikt voor suggesties en verbeteringen aan de README.

