# Repository zelf uitbreiden

Om de repository zelf verder te uit te breiden of aan te passen, moet de repository lokaal gecloned worden. De beschrijving hieronder gaat uit dat je hiervoor Visual Studio Code gebruikt.

## Clone in Visual Studio Code

1. Open de repository die je wilt clonen
2. Kies in de repository `Clone or Download`
3. Kopieer de Url in de dropdown die verschijnt 
4. Open Visual Studio Code en kies `Ctrl + Shift + P` en typ/zoek naar `git clone` en druk op `Enter`
5. Plak de gekopieerde Url uit GitHub in de command regel en druk `Enter`
6. Kies een lokale folder voor de opslag

De repository wordt nu lokaal gekopieerd. Uiteraard kun je deze niet meer terug zetten, maar je kan de repo wel aanpassen naar je eigen wensen.

## Build de repository

1. Ga in Visual Studio Code naar het command venster `Ctrl + '`
2. Build de repository m.b.v. `npm install`
3. Compile de repository met `gulp serve `, het beste is om dit in een apart Cmd Window te doen, hierdoor zie je altijd alle compile errors direct.

Na het `gulp serve` commando, start automatisch de browser in de *local workbench*.

## Referenties
- [SPFx Getting Started](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/web-parts/get-started/build-a-hello-world-web-part)
- [SharePoint Development](https://docs.microsoft.com/en-us/sharepoint/dev/)
- [SharePoint Framework Reference](https://docs.microsoft.com/en-us/javascript/api/overview/sharepoint?view=sp-typescript-latest)
- [Release Notes for SPFx Package Version 1.5.1](https://github.com/SharePoint/sp-dev-docs/wiki/Release-Notes-for-SPFx-Package-Version-1.5.1)
