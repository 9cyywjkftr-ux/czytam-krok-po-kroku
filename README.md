# Czytam krok po kroku

Spokojna aplikacja React do nauki liter, sylab, słów i zdań. Zawiera polską syntezę mowy, punkty, odznaki, tryb spokojny, panel rodzica i lokalny zapis postępów.

## Uruchomienie lokalne
```bash
npm install
npm run dev
```

## Publikacja na GitHub Pages
1. Utwórz puste repozytorium na GitHubie.
2. Wgraj wszystkie pliki z tego projektu.
3. W terminalu uruchom `npm install` i `npm run build`.

## Publikacja w Cloudflare Pages
Połącz repozytorium z Cloudflare Pages i ustaw:
- Build command: `npm run build`
- Build output directory: `dist`

Postępy są przechowywane w `localStorage` przeglądarki. Brak kont użytkowników i zewnętrznej bazy danych.
