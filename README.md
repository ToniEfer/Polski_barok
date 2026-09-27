# Barok — materiały do sprawdzianu

Streszczenie działu, gra z fiszkami i quizem, sprawdzian próbny oraz słownik pojęć.
Opracowane na podstawie podręcznika *Oblicza epok 1.2* (WSiP), rozdział 3.

---

## Publikacja na GitHub Pages

Repozytorium: **`Polski_barok`**. Wszystko robisz w przeglądarce, nic nie instalujesz.

### 1. Wgranie plików

Wejdź na swoje repozytorium `Polski_barok` i kliknij **uploading an existing file**
(jeśli repozytorium jest puste) albo **Add file** → **Upload files**.

Otwórz folder `barok-ipad`, zaznacz **wszystkie pliki z jego wnętrza** (Cmd + A)
i przeciągnij je do okna przeglądarki. Nie przeciągaj samego folderu — tylko zawartość.

Na dole strony kliknij zielony **Commit changes**.

### 2. Włączenie Pages

**Settings** (zakładka u góry repozytorium) → w menu po lewej **Pages**.

- **Source**: `Deploy from a branch`
- **Branch**: `main`, folder: `/ (root)` → **Save**

### 3. Adres strony

Odczekaj 1–2 minuty i odśwież stronę Settings → Pages. Na górze pojawi się adres:

```
https://TWOJA-NAZWA-UZYTKOWNIKA.github.io/Polski_barok/
```

Jeśli zamiast strony widzisz 404 — odczekaj jeszcze chwilę. Pierwsza publikacja
potrafi trwać do 5 minut.

### 4. Ikona na iPadzie

Otwórz ten adres w **Safari** na iPadzie → ikona **udostępniania** (kwadrat ze strzałką
w górę) → **Dodaj do ekranu początkowego** → **Dodaj**.

Na ekranie pojawi się ikona z klepsydrą. Strona otwiera się na pełnym ekranie, bez
paska adresu, i **zapamiętuje wyniki quizów** między sesjami.

---

## Co jest w środku

| Plik | Co to jest |
|---|---|
| `index.html` | menu główne — punkt startowy, pokazuje postęp w quizie |
| `streszczenie_barok.html` | streszczenie w 15 rozdziałach, ułożone według listy od nauczyciela |
| `barok_quest.html` | gra: 59 fiszek + quiz (20 pytań, 3 życia, timer) |
| `sprawdzian_barok.html` | sprawdzian próbny: 10 zadań, 39 pkt, 30 liczy się automatycznie |
| `slownik_barok.html` | słownik 53 pojęć z wyszukiwarką |
| `slownik_barok.md` | źródło słownika w zwykłym tekście (nie jest potrzebne stronie) |
| `manifest.webmanifest`, `icon-*.png` | nazwa i ikona na ekranie początkowym |

## Warto wiedzieć

- **Wyniki zapisują się osobno na każdym urządzeniu** — postęp z iPada nie pojawi się
  na komputerze i odwrotnie.
- **Aktualizacja materiałów**: w repozytorium **Add file** → **Upload files**,
  przeciągnij nowe wersje, **Commit changes**. Strona odświeży się sama po minucie.
- Wyszukiwarka w słowniku **działa bez polskich znaków** — wpisz `sep szarzynski`,
  a znajdzie „Mikołaj Sęp-Szarzyński".
- Jeśli po aktualizacji iPad pokazuje starą wersję: w Safari przytrzymaj przycisk
  odświeżania i wybierz przeładowanie bez pamięci podręcznej.
