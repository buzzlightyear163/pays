# PAYS ($PAYS)

Sajten för PAYS – "Only holds coins that pay."

## Vad som finns här
- `index.html` – hela sajten i en fil, med typsnitt och kod inbakade. Den går också att öppna med dubbelklick.
- `og.png` – bilden som visas när länken delas på X och i chattar.
- `favicon.svg`, `favicon-180.png`, `favicon-32.png` – ikonerna i webbläsarfliken och på hemskärmen.

## Fylls i vid launch
Längst upp i sajtens skript i `index.html` finns `CONFIG` med `ca` (kontraktsadressen) och `x` (länken till X-profilen). Tomma värden syns inte på sidan. Be Claude fylla i dem.

## Exempeldata
Payout Board, Coin Check och "What did $100 earn?" visar exempeldata tills en datakälla kopplas in, till exempel en gratis Helius-nyckel. Allt sådant är märkt Sample på sidan, och motorn är märkt Simulated.

## Publicering
Repot är kopplat till Vercel. Varje push till `main` publiceras automatiskt.
