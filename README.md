# John Berglund – verkko-CV

Staattinen verkko-CV GitHub Pagesissa: https://samppafin.github.io/JohnBergundCV/

Rakenne:

- `index.html` – suomenkielinen sivu
- `en/`, `sv/`, `no/` – englannin-, ruotsin- ja norjankieliset versiot
- `assets/` – fontit (Barlow, Barlow Condensed, JetBrains Mono, SIL OFL) ja favicon
- `liitteet/` – ladattavat tiedostot: CV (PDF ja Word); todistukset lisätään myöhemmin
- `.github/workflows/pages.yml` – julkaisee sivun automaattisesti jokaisesta `main`-haaran pushista

Sivu ei käytä build-vaihetta eikä ulkoisia palveluita: fontit ladataan omasta repostä.
Liitteisiin ei lisätä henkilötunnusta, katuosoitetta tai muita arkaluontoisia tietoja.
