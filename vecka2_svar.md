
 1.Skillnaden mellan vattenfallsmodellen och agil metodik
 Vattenfallsmodellen är en metod där projektet görs i bestämda steg. Först planerar man, sedan designar man, utvecklar, testar och levererar. Man avslutar vanligtvis ett steg innan man börjar med nästa. Det kan därför vara svårt att ändra något senare. 

Agil metodik betyder att man delar upp arbetet i mindre delar. Teamet utvecklar och testar ofta. Efter varje del kan teamet få feedback och ändra planen. 

Vattenfallsmodellen passar när kraven är tydliga och inte kommer att ändras mycket. Den kan till exempel passa ett projekt med fasta regler och en tydlig plan. 

Agil metodik passar bättre när kraven kan ändras under projektet. Den används ofta i mjukvaruutveckling eftersom kunden kan testa produkten och ge feedback under arbetets gång. 

2. Ett Git-commit är en sparad version av ändringarna i ett projekt. Varje commit har vanligtvis ett meddelande som beskriver vad man har ändrat, till exempel: 

( Lägg till ett formulär för inloggning ) 

Ett verkligt scenario kan vara att jag ska lägga till ett inloggningsformulär. Innan jag börjar gör jag ett commit när programmet fungerar. Efter mina nya ändringar slutar programmet att fungera. Då kan jag använda Git för att jämföra versionerna, hitta felet eller gå tillbaka till den fungerande versionen. På det sättet förlorar jag inte mitt tidigare arbete 

Commits är viktiga eftersom Git sparar projektets historik. Man kan se vad som ändrades, vem som gjorde ändringen och när den gjordes. 

I ett gemensamt projekt kan man också se vilka ändringar varje person har gjort. Om ett problem uppstår kan teamet kontrollera tidigare commits och jämföra olika versioner. Då blir det lättare att förstå vilken ändring som orsakade problemet och om den behöver rättas. 

3. I min tidigare utbildning arbetade jag mycket med Git och GitHub. 

Git hanterar projektets historik lokalt på datorn. GitHub är däremot en plattform på internet där man kan lagra projekt och samarbeta med andra utvecklare. 

I grupprojekt är det viktigt att använda branches utifrån varje persons ansvarsområde. Om min uppgift till exempel är att skapa kontaktsidan, kan jag skapa en branch som heter contact-page och skriva min kod där. 
En branch är en separat gren av projektet. En utvecklare kan arbeta och göra ändringar i sin branch utan att påverka eller förstöra huvudversionen, som vanligtvis finns i main. 

En pull request, som ofta kallas PR, är en begäran om att lägga till ändringarna från en branch till huvudbranchen. Innan ändringarna läggs till kan de andra medlemmarna i teamet granska koden, skriva kommentarer och be om rättningar. Detta hjälper teamet att upptäcka problem innan koden blir en del av huvudversionen. 

Merge betyder att ändringarna från en branch slås ihop med en annan branch, vanligtvis main. För att minska risken för buggar, fel och konflikter bör man först testa och granska ändringarna. Sedan kan man göra en merge när uppgiften i branchen är klar. Det är bättre att göra detta regelbundet efter varje färdig uppgift än att vänta till slutet av hela projektet. 
