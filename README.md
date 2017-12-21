
Robert:
Bra indentering i koden
Mkt flex = bra!
Samma måttyper över allt (% och rem) = bra!
Coolt med transparenta “boxar”
Hover-effekter gillar jag

Funderingar/förslag på ändringar:
Mainbox, varför inte ha den 100% istället för 70rem? Behövs den överhuvudtaget? 
- Ja, vill sätta en maxbredd så möjligheten till utrymme för reklam eller bilder på sidorna för framtiden.
Har ni gjort detta, reklam för julgranar och ändrat till %.

THEMES har du som div, kanske döpa den till article eller section(eller vad det kan vara), med tanke på semantisk html?
Detta är nu gjort. har sätt över hur jag namnget allt.

Sen har du tre headers, vet inte om det är ok (enligt semantisk html). fixat, en header nu.

Utseendemässigt så är delen vid “contact us…” lite skev. Rubriken h2 (med grön bakgrund) är bredare på höger sida om man jämför med form under och lirar inte riktigt om man jämför med footern. Småskavank bara.
- Detta är nu löst. tog bort detta.

Överlag bra jobbat Robert!!  Med vänlig hälsning,
Andreas




Egna ord:
En kul uppgift där man kan gå all in på flexbox. 

Nedan är kraven på uppgiften och några feedbackord på varje punkt.

Sidan använder sig av en fler-kolumns-layout. Done

Du använder dig av semantisk HTML för att strukturera upp ditt innehåll. <div> ska enbart användas för styling-syfte. Done
  
Du använder dig inte av id för att styla din sida. Styling ska ske med _class_ eller <tag>. Det ska heller inte förekomma inline styling med style-attributet i HTML. Done
  
Du använder dig huvudsakligen utav flexbox för att positionerna ditt innehåll men andra positioneringstekniker får även förekomma (såsom float). Done, inga "float" är använt

Du använder i majoritet relativa måttenheter: % och rem/em. Användandet av enheterna ska vara konsekvent, dina marginaler och padding ska inte ha massor av spridda px-värden (såkallade magic numbers). Done, rem och %

Sidan har en meny där man kan gå till de olika undersidorna. Sidan får vara en one page där det inte finns några undersidor (pricing, themes, about, contact t.ex.) men då ska menyn länka till de olika rubrikerna på sidan (scrolla till rubriken). Done, endast id för länkning i onepagelösningen

Sidan innehåller all information ovan om företaget, logotyp, slogan, pricing etc. Hur det är strukturerat är dock upp till dig. Tabellen behöver t.ex. inte se exakt ut som den ser ut i detta dokument utan det viktiga är att man tydligt ser innehållet och att det är väl grupperat så man ser vilken information som hör till vad. Tabellen behöver inte heller vara av typen table. Done, Table använt

Sidan innehåller ett korrekt formaterat kontaktformulär som ska vara en <form> där man kan fylla i namn, telefonnummer, email, företag och meddelande. Inputfälten ska vara av rätt type och ha labels. Done
  
Projektet ska ha en README.md i rootmappen som beskriver projeket och som du även ska använda för att skriva ner återkopplingen i. Done

Sidan får innehålla JavaScript men det ger inget extra, sidan examineras utifrån html och css. Ingen JS är använt

HTML och CSS är korrekt indenterad. Done

HTML och CSS är validerad via W3C HTML Validator/W3C CSS Validator och ska inte innehålla varken fel eller varningar. Du ska bifoga den output du får utav valideringen i din README.md.
Document (HTML checking completed. No errors or warnings to show.
165		Parsningsfel [: separate; border-spacing: 0.1rem; th] (vet ej vad detta är för fel eller hur jag löser det) fixaf 19 dec.



Del 2. @media
jag har valt att i mobilt läge med en upplösning under 50 rem kommer reklamen presenteras i en box efter themes.
Det kommer även att visas en mer passande presentation av prislistan där varje priskategori är en flexbox istället för i ett "table". 
Themes exotique kommer ta 100% plats och hamna nedanför de två andra thems.
Har valt och behålla menyn även i mobil för att underlätta för äldre webläsare.

I surfplatta över 50 rem kommer hela prislistan presenteras i en Table istället. (Kanske inte den snyggaste men lägger in det för att lära mig det)

I upplösning över 60 rem kommer reklam att visas på sidorna istället för under misson.

