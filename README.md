# Autokulut – yksityinen esikatselu

Tämä repositorio on yksityinen. Sivustoa ei julkaista GitHub Pagesiin.

## Avaa sivusto omassa selaimessa yksityisesti GitHub Codespacesilla

1. Avaa tämä repositorio GitHubissa ja valitse **Code → Codespaces → Create codespace on main**.
2. Kun selainpohjainen VS Code on avautunut, avaa terminaali (**Terminal → New Terminal**).
3. Käynnistä esikatselupalvelin komennolla:

```bash
python3 -m http.server 8000
```

4. Avaa **Ports**-välilehti. Portin 8000 pitäisi näkyä; valitse sen näkyvyydeksi **Private**.
5. Avaa portin tarjoama URL. Se vaatii GitHub-kirjautumisen ja on tarkoitettu vain sinulle. Sivusto toimii niin kauan kuin Codespace ja palvelin ovat käynnissä.

Jos portti ei ilmesty automaattisesti, valitse Ports-välilehdeltä **Add Port** ja syötä `8000`.

## Tietosuoja

Älä vaihda repositorion näkyvyyttä julkiseksi äläkä määritä porttia Public-tilaan. GitHubin yksityisen portin näkyvyys on oletuksena vain omistajalle. Codespacesin saatavuus ja käyttökiintiöt riippuvat tilistäsi.
