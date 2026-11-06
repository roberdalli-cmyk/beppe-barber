# Beppe Barber

Sito statico multilingua per beppebarber.com. HTML, CSS e JavaScript.

## Struttura
- `/`: italiano; `/en/`, `/de/`: inglese e tedesco
- `/prodotti/`, `/en/products/`, `/de/produkte/`: catalogo
- `/privacy-policy/`, `/cookie-policy/`: informative
- `/fonts/`: font locali
- `/images/`: 14 immagini WebP locali, senza dipendenze da WordPress

## Pubblicazione
Cloudflare Workers Builds segue il branch main. Wrangler esegue `sh build.sh` per copiare pagine, font e immagini in `dist/`.

## Da completare
- Collegare Google Calendar sostituendo `INSERISCI-ID-PRENOTAZIONE` nelle tre home.
- Verificare il dominio personalizzato prima di dismettere SiteGround.
