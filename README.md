# Flagg-A1 oppgave

### Github Projects


Da vi skulle opprette "Git Project"-siden, så brukte vi "board template" som mal. I denne malen var det 3 kolonner som var fordelt inn i "Todo", "In progress", og "Done". Dette var en lett metode for å holde oversikt over hva vi har gjort og hva som mangler. I tillegg til dette, så hadde vi flere undermål under hovedmålene - altså "metadata".

### Gruppens deltakelse i prosjektet
**Thea**: Kodet "Pflagg2.html", og møtte problemer med margin slik at det ble skille mellom elemntene. For å løse dette, så satt hun margin til 0. 
**Sultan**: Kodet "PFlagg.html" med hjelp av Sofia og Simon, og møtte på problemet rundt det å plassere flagget i sentrum. Problemet var kun en slurvefeil i koden, og ble løst relativt kjapt. 
**Simon**: Kodet "CanvasFlagg.html" og hjalp til med "PFlagg.html". Kodet "CSSFlagg.html" med Sofia.
**Sofia**: Ansvarlig for å skrive og oppdatere README.md jevnlig, og kodet "CSSFlagg.html" med Simon.


### Beskrivelse av "PFlagg.html"

I denne delen av oppgaven skal vi kode flagget til Østerrike. Vi brukte p-elementet og brukte style-elementet direkte i p-elementene for å kode flagget til Østerrike etter å ha funnet de riktige proposjonene osv. Man kan ikke kode alle type flagg fordi en del inneholder våpenskjold eller andre symboler, som krever mer avansert koding.  


### Beskrivelse av "PFlagg2.html"

Fulgte samme metode som flagget til Østerrike. 


### Beskrivelse av "CSSFlagg.html"

Vi ble enige om å kode flagget til Thailand i denne delen av oppgaven. Aller først lagde vi et HTML-dokument, og skrev inn *style*-taggen for designet av flagget. Under *style*-taggen skrev vi inn CSS-elementene som vil sin for eksempel RGB-kodene, proposjoner osv. Etter dette fikk vi  *style*-taggen til å samhandle med *body*-taggen i html-filen gjennom attributen *class*. Grunnen til at vi valgte å bruke *class*-attributen er fordi det er flere deler av flagget som har repterende farger, og derfor er dette mer effektivt enn å gi en personlig ID til hver av de 6 delene som deler flere av de samme fargene.

### Beskrivelse av "CanvasFlagg.html" 

For å lage Vietnam flagget begynte vi med å bestme bredden og høyden på canvaset for å passe til dimensjonene til Vietnam flagget som er 2:3.
Canvaset ble derfor 640:426px. Deretter farget vi hele canvaset med rgb rød fagre. For å lage stjernen i flagget fant i midten av flagget og gikk nesten helt til toppen.
For å lage hver av linjene på stjerne måtte vi prøve og feile og se hva som passet best til de ekte dimensjonene på flagget.
Hver linje på stjernen er 4 enheter lang, som vil si 21px med vårt bredde på canvaset.
Vi brukte tilStroke og filStyle for å farge stjernen gul.

Referanser:
    Vietnam flagg:
    
    Traversy Media. (2020, 7. Januar). _HTML5 Canvas API Crash Course_ YouTube. (https://www.youtube.com/watch?v=gm1QtePAYTM) 
    
    Mozilla development network. (2022, 21. September). _Drawing shapes with canvas_ MDN. (https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)
    
    Thomas Zimmermann (2022, 9. September). _ctx.strokeStyle works, but not ctx.fillStyle without error message_. Stackoverflow (https://stackoverflow.com/questions/73866758/ctx-strokestyle-works-but-not-ctx-fillstyle-without-error-message)


