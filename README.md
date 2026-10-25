# Autokulut

Autokulut-sivuston staattinen selainversio. Käynnistyssivu on `index.html`, joka lataa ja purkaa selaimessa gzip-pakatuista `site-data-01.txt`–`site-data-11.txt`-tiedostoista varsinaisen käyttöliittymän ja laskentalogiikan.

## Julkaise GitHub Pagesissa

**Tärkeää:** julkisen repositorion koodi, aineisto ja sivusto ovat kaikkien nähtävissä. Älä lisää tähän repositorioon salasanoja, API-avaimia tai muuta luottamuksellista tietoa.

1. Avaa [repository settings](https://github.com/Jonoppa/kulutusvertailu/settings).
2. Kohdassa **General → Danger Zone → Change repository visibility** valitse **Make public** ja vahvista GitHubin pyytämät tarkistukset.
3. Avaa [Pages-asetukset](https://github.com/Jonoppa/kulutusvertailu/settings/pages).
4. Valitse **Build and deployment → Deploy from a branch**.
5. Valitse branchiksi `main` ja kansioksi `/ (root)`, ja paina **Save**.

Kun GitHub Pages on julkaissut sivun, sen osoite on tavallisesti [https://jonoppa.github.io/kulutusvertailu/](https://jonoppa.github.io/kulutusvertailu/). Jos sivu ei vielä aukea, tarkista Pages-asetusten julkaisutila ja odota hetki.

Jatkossa `index.html`- ja `site-data-*.txt`-tiedostojen muutokset `main`-haarassa tulevat mukaan seuraavaan Pages-julkaisuun automaattisesti. Julkaisu voi kestää muutaman minuutin.
