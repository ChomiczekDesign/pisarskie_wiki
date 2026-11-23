# Pisarskie wiki

Publiczna baza wiedzy o pisaniu, budowana z plików Markdown przy użyciu [Kiln](https://kiln.talesign.com/).

Repozytorium jest na etapie konfiguracji. Właściwe materiały poradnikowe nie zostały jeszcze opublikowane — najpierw zostanie uzgodniony ich zakres, struktura i redakcja.

Po wdrożeniu strona będzie dostępna pod adresem:

https://chomiczekdesign.github.io/pisarskie_wiki/

## Układ repozytorium

- `wiki/` — jedyne źródło publicznej treści strony;
- `kiln.yaml` — ustawienia generatora;
- `.github/workflows/deploy.yml` — kontrola poprawności zmian i publikacja przez GitHub Pages;
- `CONTENT_PLAN.md` — decyzje potrzebne przed migracją poradników.

## Praca lokalna

1. Pobierz Kiln `v0.9.5` dla swojego systemu z [wydań projektu](https://github.com/otaleghani/kiln/releases/tag/v0.9.5).
2. W katalogu repozytorium uruchom:

   ```text
   kiln doctor --input ./wiki
   kiln generate
   kiln serve --output ./public
   ```

3. Otwórz adres podany przez Kiln (domyślnie `http://localhost:8080`).

Katalog `public/` jest wynikiem kompilacji i nie powinien trafiać do repozytorium.
