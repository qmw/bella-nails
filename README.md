# Bella Nails — Studio Paznokci

Strona-wizytówka dla fikcyjnego studia paznokci **Bella Nails** w Warszawie (Mokotów).
Projekt stworzony jako element portfolio [stronainternetowa.biz](https://stronainternetowa.biz).

## Styl wizualny

- **Paleta**: złamana biel #fdf7fa, magenta/róż #d6336c, brzoskwinia #f7b2c4, liliowy #b794d4, ciemny #2e1f29
- **Fonty**: Unbounded (display/nagłówki) + Mulish (body)
- **Klimat**: glamour, nowoczesny, kobiecy — różowe gradienty, mikro-animacje, reveal przy scrollu

## Sekcje

1. Pasek demo (promo-bar)
2. Nawigacja (fixed, z menu mobilnym)
3. Hero — hasło, CTA, statystyki, floating badges
4. O studiu — zdjęcia, zespół, certyfikaty
5. Usługi — 4 karty (hybryd, żel, pedicure, zdobienia)
6. Cennik — 3 kolumny (manicure, pedicure, zdobienia)
7. Galeria stylizacji — masonry grid
8. Opinie klientek — 4 recenzje na ciemnym tle
9. Rezerwacja — formularz + alternatywny kontakt
10. Kontakt — godziny, adres, mapa OpenStreetMap
11. Stopka z creditem

## Stack

- **Astro 5** + **Tailwind CSS 4** (via `@tailwindcss/vite`)
- Zero zewnętrznych zależności JS

## Komendy

```bash
npm install
npm run dev      # serwer deweloperski na http://localhost:4321
npm run build    # build produkcyjny do ./dist
npm run preview  # podgląd buildu
```

## Hosting

Gotowe do deploymentu na **Vercel** (Astro wykrywane automatycznie, output: `dist/`).
