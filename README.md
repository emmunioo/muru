# Muru · Kajtek

Archiwum zdjęć i filmów kota Muru, zwanego Kajtkiem.

## Jak dodać zdjęcia i filmy

1. Wrzuć zdjęcia do folderu `zdjecia/`, a filmy (`.mp4`, `.webm`, `.mov`) do `filmy/`.
2. W pliku `index.html` znajdź listę `ARCHIWUM` i dopisz każdy plik, np.:

   ```js
   { plik: "zdjecia/parapet.jpg", opis: "Ulubione miejsce na parapecie", data: "wiosna 2018" },
   { plik: "filmy/zabawa.mp4", opis: "Polowanie na wędkę", data: "2020" },
   ```

3. Opcjonalnie uzupełnij `lata` (np. `"2010 – 2026"`) i `motto` w obiekcie `KOT`.
4. Otwórz `index.html` w przeglądarce.

Strona działa bez serwera i można ją opublikować np. przez GitHub Pages.
