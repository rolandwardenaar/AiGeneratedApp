# AiGeneratedApp

Dit is een standaard .NET 8.0 Blazor WebAssembly-applicatie, gegenereerd voor automatische deployment naar GitHub Pages.

## Features
- Blazor WebAssembly (standalone)
- Voorbeeldcode in C#
- Automatische deployment naar GitHub Pages via GitHub Actions

## Deployment
Zie `.github/workflows/deploy-to-gh-pages.yml` voor de deployment workflow.

## Starten van de app lokaal
```powershell
dotnet run
```

## Publicatie
De gepubliceerde site is te vinden op de `gh-pages` branch van deze repository, onder de URL:
```
https://<jouw-gebruikersnaam>.github.io/AiGeneratedApp/
```

## Opmerkingen
- De base-tag in `index.html` wordt automatisch aangepast voor GitHub Pages.
- Een `.nojekyll`-bestand en `404.html` worden automatisch toegevoegd voor correcte SPA-routing.
