# Sprint 13 
## 2-09 
### Eerste dag van sprint 13. 
- Begin met het leren van Sveltekit.
- Team bekend voor squadpage -> ik zit samen met Daan, Christopher, Annelinde, Tristan en Jason
- Leervragen opgesteld:
    - Hoe werken frameworks? 
    - Hoe begin ik met het leren van SvelteKit?
    - Wat is Svelte? 
    - Hoe werkt Sweltekit?
    - Hoe kan je een logisch stappenplan maken om een opdracht uit te voeren? 
    - Hoe plan ik mijn tijd beter in? 
    - Hoe lever ik mijn bewijslast op de juiste manier op? 
    - Hoe blijf ik constant de dlc gebruiken? 
    - Hoe zorg ik dat ik mijn i love web bijhoud?

## 3-09
- tutorial svelte 
- team afspraak 

## 4-09 
Team meeting 
- ontwerpen 
- taken verdeeld 

## 5-09
- gewerkt aan eigen taak (squadpage) 
Code gebruikt om component te laten werken op homepagina 
+page.svelte (begin pagina):

```
<script>
    import Card from '$lib/Card.svelte';

    /** @type {import('./$types').PageData} */
    export let data;

    // Check if the data has been received and is an array
    console.log('Received data in +page.svelte:', data);
</script>

<nav>
    <a href="/">home</a>
    <a href="/squadpage">squadpage</a>
</nav>

<h1>home</h1>
<p>this is the home page.</p>

<!-- Only render if we have people in the data -->
{#if data.people}
    {#each data.people as person}
        <Card {person}></Card>
    {/each}
{:else}
    <!-- This will show if no people are available -->
    <p>No data available</p>
{/if}

Staat in de lib 
Card.svelte 
<script>
    export let person;
</script>

<article>
    <h2>{person.name}</h2>
    <p>{person.bio}</p>
</article>

<style>
</style>
```


## 6-09
- visitekaartjes eerstejaars feedback gegeven 

Formuleer drie vragen over wat je heb geleerd (markdown bestand) 

Attomic design -> components 
Issues maken voor component 


## 9–09 
Workshop kill your darlings en workshop hoe ontwerp je in Figma (cyd) 
Figma workshop van cyd 
- auto layout en componenten 
- shortcut r: maak een vierkant 
- shortcut o: maak een cirkel 
- shortcut cmd+g: groeperen van objecten 
- 

Kan een grid toepassen om zo items netjes uit te lijnen 
375 px voor mobiel 

Goede website voor ideeën: https://www.awwwards.com/

Kan website live zetten met
vercel



## 13-09 
We love web eerste 
Code/design review 

## 16-09 
Pokerplanning 
Moscow 
Mark twain 
To change your life you need to change your priorities 

Van epic, langs (user)stories, naar taken 
Handige manier om werk op te organiseren en een hiërarchie te creëren. Het idee is om werk op te splitsen in opleverbare stukken. 

Voorbeelden van epic:
Een nieuwe e-commerce website lanceren voor …
De website van … verbeteren 
Een nieuwe website lanceren voor … 
De website van … optimaliseren voor zoekmachines 

Voorbeelden van stories:
Een nieuwe e-commerce website lanceren voor …
- winkelmandje toevoegen 
- betalingsmogelijkheden toevoegen 
- een klantenserviceportal toevoegen 

De website van … verbeteren 
- de website sneller maken 
- de website gebruiksvriendelijker maken 
- de website toegankelijker maken 

Voorbeelden van user-stories:
Een nieuwe e-commerce website lanceren voor …
- winkelmandje toevoegen 
Als bezoeker wil ik producten in mijn winkelmandje kunnen doen om overzicht te houden wat ik aanschaf 
- betalingsmogelijkheden toevoegen 
Als bezoeker wil ik producten kunnen verwijderen uit mijn winkelmandje al sik iets gevonden heb wat beter past bij wat ik nodig heb
- een klantenserviceportal toevoegen 
Als bezoeker wil ik overzicht houden op het uit te geven bedrag zodat ik het gevoel heb in controle te zijn 

Voorbeelden van taken:
Als bezoeker wil ik producten in mijn winkelmandje kunnen doen om overzicht te houden wat ik aanschaf 
- Database voor winkelmandje 
- Overzicht winkelmandje tonen in HTML/CSS
- Producten verwijderen uit de database 
- Interface ontwerpen voor verwijderen producten 
- Interface ontwerpen voor aantal aanpassen 
- Verder shoppen interface (button) / doorgaan naar betaling 
- Ontwerpen van icoon winkelmandje 
- Implementatie icoon winkelmandje 
- Optelsom alle prijzen 
- Verzendkosten 

Planning poker
Fibonatischn reeks 
? - 0 - 1 - 2 - 3 - 5 - 8 - 13 - 21 - oneindig 

Techniek voor het schatten, vooral gebruikt voor timeboxing in agile principes. 
Leden van de groep geven schatting door genummerde kaarten op tafel te leggen of een getal op te schrijven in plaats van dit hardop te zeggen. De kaarten worden omgedraaid en de schattingen worden vervolgens besproken. Door de cijfers te verbergen, kan cognitieve bias van verankering vermeden worden, waarbij het eerste hardop gesproken cijfer ene precedent schept voor volgende schattingen. 

Moscow 
Must haves: 
Moet af op de deadline -> niet af is het project gefaald 
Should haves: 
Best wel af moeten -> project is jammer als het niet af is 
Could haves: 
Dit kan -> als er tijd over is 
Want to have but will not have this time around: 
Dit zijn goede ideeën en nuttig om te noteren maar we komen er nu niet aantoe 



## 17-09 
Verder werken aan groepsopdracht 
Op school cards gemaakt 

## 18-09 
Hoe lever ik een project op ?
Readme 
In readme cms uitleggen -> hoe vragen aan opdrachtgever 
Code conventies 
Live zetten / publiceren 
Huisstijl -> in readme (pdf) 
Gestructureerde code / 
Refactoring 

Refactored code: 
Gestructureerde code (conventies), semantiek, geen commented code, geen console.log, goede tabs

Readme:
kenmerken
Live link 
Screenshots 
Instructies (uitleg over het gebruik) 
Installatiehandleiding 
Cms uitleg
Huisstijl (of waar die te vinden is) 
Bijdragen? (Hints voor volgende developers teams) 
Gebruikte bronnen 
Badges met gebruikte technologie 

Live zetten:
GitHub pages, 


## Vrijdag 20 sep 
Niveaumatrix bespreken 
Kampvuursessie 
Bewijslast in portflow zetten 

Wat betekend de indicator 
Waarom is dit goede bewijslast 
Heb je nog leervragen met betrekking op deze indicator 

