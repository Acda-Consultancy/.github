
# **GitHub Organisatie Richtlijnen**

Welkom bij de GitHub-organisatie van **Acda Consultancy**. Deze repository bevat de richtlijnen voor het gebruik van onze GitHub-organisatie. Volg deze regels om consistentie, overzicht en samenwerking te bevorderen.

---

## **Inhoudsopgave**
1. [Repository-namen en structuur](#repository-namen-en-structuur)
2. [Branch-structuur en -regels](#branch-structuur-en--regels)
3. [Commitberichten](#commitberichten)
4. [Pull Requests en Code Reviews](#pull-requests-en-code-reviews)
5. [Documentatie](#documentatie)
6. [Beveiliging en Toegang](#beveiliging-en-toegang)

---

## **Repository-namen en structuur**

Om consistentie te waarborgen, volgen we deze richtlijnen voor repository-namen:

- Gebruik korte, beschrijvende namen in het Engels.
- Gebruik koppeltekens (`-`) in plaats van spaties of underscores.
- Structuur:
  - **team-project**: Bijvoorbeeld: `frontend-dashboard`
  - **functie-feature**: Bijvoorbeeld: `api-authentication`
- Archiveer oude repositories als ze niet meer actief worden gebruikt.

**Voorbeelden:**
- `backend-auth-service`
- `mobile-user-interface`
- `data-analytics-pipeline`

---

## **Branch-structuur en -regels**

Voor een duidelijke workflow gebruiken we de volgende branch-structuur:

- **`main`**: Productiebranch; bevat alleen stabiele code.
- **`develop`**: Ontwikkelingbranch; nieuwe features worden hier samengevoegd.
- **Feature branches**: Gebruik `feature/omschrijving` voor nieuwe functionaliteiten.
- **Bugfix branches**: Gebruik `bugfix/omschrijving` voor bugfixes.

**Branch-regels:**
- Directe commits naar `main` zijn niet toegestaan.
- Pull requests zijn verplicht voor alle merges naar `main` of `develop`.
- Tests moeten slagen voordat een merge wordt goedgekeurd.

---

## **Commitberichten**

Gebruik duidelijke en beknopte commitberichten. Volg deze structuur:

```
[Type]: Korte samenvatting

Details (optioneel)
```

**Types:**
- `feat`: Nieuwe functionaliteit
- `fix`: Bugfix
- `docs`: Documentatie-updates
- `style`: Code-stijl (geen functionaliteit)
- `refactor`: Herstructurering zonder nieuwe functionaliteit
- `test`: Testen of teststructuur
- `chore`: Overige taken

**Voorbeeld:**
```
feat: voeg authenticatie toe

Implementeert login- en registratiefunctionaliteit met JWT.
```

---

## **Pull Requests en Code Reviews**

- Maak een pull request (PR) aan zodra een feature of bugfix klaar is.
- Voeg een beschrijving toe met:
  - Wat is veranderd
  - Waarom deze wijziging nodig is
  - Eventuele tests die zijn uitgevoerd
- **Code review regels:**
  - Minimaal 1 goedkeuring nodig voor merge.
  - Gebruik opmerkingen om feedback te geven.


---

## **Documentatie**

- Voeg een duidelijke `README.md` toe aan elke repository met:
  - Beschrijving van het project
  - Installatie-instructies
  - Hoe bij te dragen
- Gebruik een `docs`-map voor aanvullende documentatie.

---

## **Beveiliging en Toegang**

- **Two-factor authentication (2FA):** Verplicht voor alle leden.
- **Branch-beveiliging:** Alleen PR's mogen worden gemerged in `main` en `develop`.
- **Gevoelige gegevens:** Gebruik [GitHub Secrets](https://docs.github.com/en/actions/security-guides/encrypted-secrets) om API-sleutels en wachtwoorden te beheren.

---

## **Vragen of Problemen**

Bij vragen of problemen, neem contact op met **Jelle of Shkar** via **email**.

Samen maken we van onze GitHub-organisatie een efficiënte en prettige werkplek! 🎉
