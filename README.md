# Frontend Responsive Design
Eindopdracht voor het vak Frontend @CMD Amsterdam

https://henkwillem.github.io/frontend-responsive-design/

**Wat?**
Ik heb ervoor gekozen om (een poging te doen om) de website van HvanA na te maken.
Voor een ander vak wat ik momenteel ook aan het afronden ben (Vormgeving 2) was een van de opdrachten om een huisstijl analyse te maken van deze website. Ik raakte gecharmeerd van de stijl die ze op de website neergezet hadden en was gemotiveerd om aan de slag te gaan.

**Uitleg website**
Wanneer je naar www.hvana.nl gaat tref je een website die vrijwel volledig bestaat uit divjes, iets wat in het vak FED niet heel erg gewaardeerd kan worden. Toch heb ik deze website als uitgangspunt genomen en heb ik hem "from scratch" na proberen, ook al is het een vrij basale uitvoering.

In de website heb ik geprobeerd de criteria op een leuke en elegante manier te verwerken. Hieronder staan de criteria, en per criterium zal ik uitleggen hoe ik geprobeerd heb om hieraan te voldoen. 


## Criteria
### 1.) De HTML is gestructureerd en semantisch opgemaakt
In de HTML heb ik mijn best gedaan zo "schoon" mogelijk te werken. Dit heb ik zo goed mogelijk proberen te doen door alle elementen goed te nesten en de juiste tags te gebruiken. De pagina bestaat uit een *header, main* en een *footer*. Hierin staan verschillende sections met daarin articles met bijbehorende inhoud. Ook heb er ik een form in verwerkt. 

In de section boven de footer zul je in de code een div tegenkomen. Deze heb ik gebruikt om te voorkomen dat ik het stukje javascript onnodig moeilijk heb gemaakt. Ja, je zou kunnen stellen dat deze div overbodig is, maar het heeft wel voor een versimpeld stukje javascript gezorgd. Ook heb er ik een form in verwerkt. De button bij dit form had ook een input type="submit .. kunnen zijn, maar ook hier heb ik gekozen voor een andere oplossing vanuit het javascript oogpunt.

### 2.) De basis principes van CSS zijn begrepen en toegepast
Het stuk css code van mijn website is vrij fors, blijkbaar was het nodig om zoveel code te schrijven haha. CSS vond ik zelf dan ook het leukste om te doen. Ik heb geprobeerd het aantal classes zo beperkt mogelijk te houden, de nth-of-type selector heeft mij daar heel goed bij geholpen.

Ik heb diverse :hovers toegevoegd op buttons en iconen, waardoor de elementen veranderen. Check de h1, social media icoontjes, verzendknop en de tekst in de footer maar eens. Door te spelen met deze hovers kreeg ik echt plezier in het schrijven van de code. Voor de rest heb ik mijn best gedaan alle html mooi vorm te geven.

### 3.) De site is responsive
Yes, de site is responsive. Dat was best een karwei. Hij heeft 1 "major breakpoint", namelijk bij >1300px. Op dat moment gaan de articles namelijk in een grid van 3 kolommen staan. Verder heb ik nog andere breakpoints toegevoegd om het meeschalen van de website wat soepeler te laten gaan. Je zult zien dat niet alle elementen perfect meeschalen wanneer je de website vanaf mobile size groter gaat maken. Helaas ben ik hier niet aan toegekomen.

### 4.) Er is een werkende interactie met js gemaakt
Jazeker. Bij het drukken op de verzendknop wordt er een class toegevoegd aan de h2 die in de footer staat. Deze class wordt ingeladen met een leuke animatie, zodat het allemaal net wat meer fancy lijkt. De querySelector, event en classList.toggle komen erin terug. 

### 5.) Er is geëxperimenteerd met verschillende technieken
Omdat ik echt wel plezier had in het toevoegen van transities en animaties, ben ik hier verder in gegaan. Ik heb animaties en transities toegevoegd die niet terugkomen in de daadwerkelijke website. Vond ik leuk om te doen. Het experimenteren met keyframes is best tof.

Ik heb nog geprobeerd om een login knop toe te voegen en hier wat mee te experimenteren, maar daardoor ging m'n javascript stuk, dus dat heb ik maar achterwege gelaten.


Al met al heb ik flink wat uren in het maken van de website zitten en ben dan ook erg trots op het resultaat. Naar mijn idee heb ik echt stappen gezet en ben ik de code beter gaan doorgronden. Natuurlijk valt er nog genoeg winst te behalen, maar ik kijk met plezier terug op het vak. Ik hoop dat het geheel genoeg is voor een voldoende :)

Henk Willem
500730919
