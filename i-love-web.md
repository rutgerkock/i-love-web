<h1>Semester 3</h1>

<h2>Sprint 13</h2>

<b>Week 1</b>
<ul>
  <b>Maandag</b>
  <li> We hebben de introductie gehad en zijn verdeeld in groepjes voor onze squad page. </li>
  <li> Vervolgens afgesproken woensdag allemaal een lofi-design af te hebben. </li> 
  <br>
  <b>Dinsdag</b>
  <li> Lofi-design gemaakt in Figma. </li> <a href='https://github.com/rutgerkock/your-tribe-for-life-squad-page/issues/1'>Zie issue</a>
  <li> Svelte/Directus documentatie doorgelezen </li>
  <br>
  <b>Woensdag</b>
  <li> We hebben het gehad over onze designs en zijn samen tot een samenvoeging van onze designs gekomen waar we nu zelf verder aan kunnen werken. </li> <a 
  href='https://github.com/rutgerkock/your-tribe-for-life-squad-page/issues/1](https://github.com/users/rutgerkock/projects/7?pane=issue&itemId=78311249'>Zie issue</a>
  <li> Opzetten van de Github repo en het maken van een team-canvas. </li> <a href='https://github.com/users/rutgerkock/projects/7/views/1?pane=issue&itemId=78310746'>Zie issue</a>
  <li>
    <b>notes</b>
    <br>
> Client side rendering uitzetten:
> Export let car = false
> (+ page.js in de root van de route folder) 


> Mapjes svelte uitleg:
> Static is public map (client side) 
> - CSS >  global.css

> *SRC map meest belangrijkst > daar gebeurd het meeste in 


> Handig om te weten
> <body data-sveltekit-preload-data=“hover”>
>       %Sveltekit.body%
> </body>

> > gebruikservaring is beter en lazy loading staat aan

> Routes > daar staan alle pagina’s
> Lib > shorthand voor library, daar staan de componenten in, voor hergebruik van componenten.

> +page.svelte -> lijkt op ejs -> hier combineer je data met html
> In dit +page.svelte bestand krijg je html + css + js

> Npm run dev (server starten)

> Css definiëren per pagina


> Data ophalen:
> Export let data (in je +page.svelte) (haalt data op)

> +page.server.js -> fetchjson -> functie load -> await -> return { persons: persons}

> In je routes mapje bijv. [id] -> page.server.js + page.svelte -> filters zoals persons/id

> Routes aanmaken defineren
> Als je een map aanmaakt in het mapje routes met een page bestand maakt ie een route
> In je page.server.js kan je data sturen naar deze page bestanden


> Svelte installatie
> * npm create svelte@latest
> * Welcome to SvelteKit!
> * │
> * ◇  Where should we create your project?
> * │    (hit Enter to use current directory)
> * ◇  Directory not empty. Continue?
> * │  Yes
> * ◇  Which Svelte app template?
> * │  Skeleton project
> * ◇  Add type checking with TypeScript?
> * ◇  Select additional options (use arrow keys/space bar)
> * │  none
> * └  Your project is ready!

  </li>
  <br>
  <br>
  <b>Donderdag</b>
  <li> Ik heb vandaag gewerkt aan een animatie/loading state die we willen gebruiken voor de squad page, maar ik ook zelf wil gebruiken. </li> <a href='https://github.com/rutgerkock/your-tribe- 
  for-life-profile-card/commit/8c64582d2b32e64710412be7ff628fc1267759f8'>Zie commit</a>
  <li> Ik heb een design gemaakt in Figma voor mijn visitekaartje.</li>
  <br>
  <b>Vrijdag</b>
  <li> Ik heb deze ochtend voor m'n eigen profile-card een loading animation gemaakt. </li> <a href='https://github.com/rutgerkock/your-tribe-for-life-profile-card/commit/40ab1d1367e0e61907de709e8a4ff8e77d426ef2'>Zie commit</a>
  <li>Later deze ochtend heb ik vervoor gezorgd dat de basis van mijn eigen profile-card voldoet aan contrast eisen en een prettige dark mode heeft.</li>
</ul>

<b>Week 2</b>

<b>Week 3</b>
