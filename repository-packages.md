# Repository packages gebruiken

## Voordat je begint!
- Om een web part package te gebruiken in de SharePoint omgeving, moet je *__Tenant Administrator__* zijn. Ben je geen *__Tenant Administrator__*...
    - Voer dan *Stap 1 - Downloaden van een package* uit
    - Zoek een *__Tenant Administrator__*! Zij kan stap 2 uitvoeren met de gedownloade package
    - Stappen 3 en 4 kan je zelf weer doen
- De web parts moeten in het *App Center* of *App Catalogue* toegevoegd worden. Dit is een SharePoint site collectie aangemaakt vanuit de admin portal. Is er nog geen App Center in je omgeving aanwezig, dan moet deze eerst aangemaakt worden. [Kijk hier voor meer informatie.](https://docs.microsoft.com/en-us/sharepoint/use-app-catalog)

## Stap 1 - Downloaden van een package

Om een web part package te gebruiken, moet je deze eerst downloaden uit GitHub:
1. Open de repository
2. Open de folder `sharepoint/solution`, neem altijd het laatste versie nummer in de folder naam
3. Klik op het `.sppkg` bestand en kies vervolgens in GitHub de knop **Download**
4. Bewaar het bestand op de lokale harde schijf 

## Stap 2 - Installeren van de package

1. Open je tenant en ga naar het App Center
2. Upload het lokale `.sppkg` bestand in het App Center
3. Is het bestand al aanwezig, kies dan **Vervangen**
4. SharePoint vraagt of dit bestand *uitgerold mag worden*, kies *Ja*

Na deze laatste stap is het `.sppkg` bestand geinstalleerd en kan het gebruikt worden in de sites op de tenant.

## Stap 3 - Toevoegen in een site

1. Open de site waar je de package wil gebruiken
2. Op de homepage van de site kies je *Nieuw > App*
3. De *Site Contents > Apps* pagina wordt geopend, klik op het icoon van de app die je wilt toevoegen
4. De app wordt toegevoegd aan de site

## Stap 4 - Toevoegen op een pagina

1. Open op de site waar de app is toegevoegd en maak een nieuwe pagina aan
2. In een web part zone, klik op het `+` icoon en kies het web part dat je hebt toegevoegd
3. Pas eventueel de configuratie van het web part aan

