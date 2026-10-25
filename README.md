# Autokulut

Autokulut-sivuston staattinen esikatselu. Sivusto ladataan `index.html`-tiedostosta ja puretaan selaimessa gzip-pakatuista `site-data-01.txt`–`site-data-11.txt`-tiedostoista. Varsinainen käyttöliittymä ja laskentalogiikka ovat pakatussa HTML:ssä.

## GitHub Pagesin käyttöönotto

1. Avaa repositorion **Settings → General → Danger Zone → Change visibility** ja valitse **Make public**. Julkisuus tarkoittaa, että lähdekoodi ja kaikki sivuston aineisto ovat kaikkien nähtävissä.
2. Avaa **Settings → Pages**.
3. Kohdassa **Build and deployment** valitse **Deploy from a branch**.
4. Branch: `main`; folder: `/ (root)`; valitse **Save**.
5. Odota, että GitHub Pages näyttää julkaistun URL-osoitteen. Tämän repositorion osoitteen oletusmuoto on `https://jonoppa.github.io/kulutusvertailu/`.

Jatkossa muutokset `index.html- ja `site-data-*.txt`-tiedostoihin `main`-haarassa päivittyvät Pages-sivulle automaattisesti. GitHub Pagesin julkaisu ja välimuistin päivitys voivat kestää hetken jokaisen commitin jälkeen.
