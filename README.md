# U9 Wisselplanner

Wisselschema voor U9 (5 tegen 5) in de stijl van het Home Assistant-dashboard:
"Wie is er?", keeper per kwart, extra bank, andere variant, 4 kwarten met ▼ eruit / ▲ erin,
controle en een wedstrijdklok. Werkt als app op de iPhone, ook zonder internet.
Alles wordt op het toestel zelf bewaard.

## Online zetten (GitHub Pages)
1. Maak op github.com een nieuwe **public** repository, bv. `u9`.
2. *Add file → Upload files*: sleep alle bestanden uit deze map erin en kies *Commit changes*.
3. *Settings → Pages*: Source *Deploy from a branch*, branch `main`, map `/ (root)` → *Save*.
4. Na een minuutje staat de app op `https://<gebruikersnaam>.github.io/u9/`.

## Op de iPhone
Open de link in **Safari** → deelknop → **Zet op beginscherm**.

## Ploeg inladen
De spelersnamen staan niet in deze (publieke) repository. Vul ze in bij
*Spelers (naam + voorkeur)* als `Naam 1e 2e` (bv. `Louis 7 11`), of open een
persoonlijke ploeglink (`…/u9/#ploeg=…`). Zet zo'n link niet in deze repository.
Onderaan de app staat een knop om je ploeg als link naar een ander toestel te sturen.

## Bijwerken
Verhoog na een wijziging `VERSION` bovenaan in `sw.js` (bv. `u9-v2`), zodat iPhones
de nieuwe versie ophalen.
