> _Fork_ deze leertaak en ga aan de slag. 
Onderstaande outline ga je gedurende deze taak in jouw eigen GitHub omgeving uitwerken. 
De instructie vind je in: [docs/INSTRUCTIONS.md](https://github.com/fdnd-task/choices-choices-the-tech-stack/blob/main/docs/INSTRUCTIONS.md)

# Tech Stack
Ik heb ervoor gekozen een techstack van Nuxt/Sanity te gebruiken.

## Inhoudsopgave

  * [Beschrijving](#beschrijving)
  * [Installatie](#installatie)
  * [Bronnen](#bronnen)
  * [Licentie](#licentie)

## Beschrijving
Ik heb een Visual Thinking website gemaakt met als Tech stack Nuxt/Sanity

<img src= "https://github.com/kosterm14/choices-choices-the-tech-stack/assets/61830362/a21091fb-9244-4e1b-a33b-7017b498e0ab" width= 50%>


## Installatie
Ik begon door Sanity op te stellen in mijn CLI en heb hierna Nuxt toegevoegd.

## [Sanity](https://www.sanity.io/)
Als eerst heb ik op de [Sanity website](https://www.sanity.io/) een nieuw project gestart. 

<img src= "https://github.com/kosterm14/choices-choices-the-tech-stack/assets/61830362/ed3a8ec5-f8f5-4150-80ea-0d50754775ea" width= 30%>

Ik heb onderstaande line in mijn terminal gezet in Visual Studio Code en hier de installatie stappen gevolgd.

```
npm -y create sanity@latest
```

## [Nuxt](https://www.sanity.io/docs/connect-your-content-to-nuxt3#f17f81ffb6f2)
Nadat ik een de Sanity boilerplate code had geinstalleerd begon ik met het toevoegen van Nuxt. Nuxt.js heeft een server nodig, ik heb dit gedaan door [een project](https://github.com/sanity-io/get-started-sanity-nuxt3), vooraf opgesteld door Sanity, lokaal te clonen vanuit GitHub. Dit project bevat een [CodeSandbox](https://codesandbox.io/) en deze wordt gebruikt als server. Ook bevat dit project al Nuxt dus het lokaal clonen van dit project voegt ook Nuxt toe aan mijn project.

<img src= "https://github.com/kosterm14/choices-choices-the-tech-stack/assets/61830362/f27a7591-087f-4e81-a675-0be574a7ae43" width= 35%>

Hierna heb ik de juiste dependencies geinstalleerd door `npm install` te doen in de geclonede map.

```
git clone https://github.com/sanity-io/get-started-sanity-nuxt3.git
npm install
```

## [@nuxt/sanity module](https://www.sanity.io/docs/connect-your-content-to-nuxt3#f17f81ffb6f2)
Ik heb hierna de `@nuxt/sanity` module in diezelfde map toegevoegd aan mijn `package.json` doormiddel van onderstaande code.

```
npm i @nuxtjs/sanity
```

## Bronnen
https://www.sanity.io/
https://www.sanity.io/docs/
https://codesandbox.io/
https://github.com/sanity-io/get-started-sanity-nuxt3

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
