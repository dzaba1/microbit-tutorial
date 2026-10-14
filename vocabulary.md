# Polish block vocabulary

Polish labels of MakeCode (micro:bit) toolbox categories and blocks, as they appear in the Polish editor (`?lang=pl`).
Use these exact labels in tutorials, e.g. ``` ``||basic: pokaż ikonę||`` ```; the text after `category:` must match the toolbox label or MakeCode will not highlight the block correctly.

Source: screenshots of the Polish editor provided by the repo owner. Entries marked **(?)** were not visible in any screenshot and are best guesses; verify them in the editor and remove the mark.

## Editor UI

| English | Polish |
| --- | --- |
| Toolbox | Zestaw narzędzi |
| Search... | Szukaj... |
| Advanced | Zaawansowane |
| Extensions | Rozszerzenia |
| Make a Variable... | Utwórz zmienną... |

## Categories

Tag prefix is the category id used in ``` ``||category: ...||`` ```.

| Tag prefix | English | Polish |
| --- | --- | --- |
| `basic` | Basic | Podstawowe |
| `input` | Input | Wejście (more: więcej) |
| `music` | Music | Muzyka |
| `led` | LED | LED (more: więcej) |
| `radio` | Radio | Radio |
| `loops` | Loops | Pętle |
| `logic` | Logic | Logika |
| `variables` | Variables | Zmienne |
| `math` | Math | Matematyka |

## Blocks used in the lessons

English labels are taken from the English originals in [microbit-foundation/makecode-tutorials `first-lessons`](https://github.com/microbit-foundation/makecode-tutorials/tree/main/first-lessons).

| English | Polish | Notes |
| --- | --- | --- |
| `basic: on start` | `basic: podczas uruchamiania` | |
| `basic: forever` | `basic: na zawsze` | |
| `basic: show icon` | `basic: pokaż ikonę` | |
| `basic: show string` | `basic: pokaż łańcuch` | default text is „Witaj!” (English: "Hello") |
| `basic: show number` | `basic: pokaż liczbę` | |
| `basic: show leds` | `basic: pokaż LED` | |
| `basic: clear screen` | `basic: wyczyść ekran` | |
| `basic: pause (ms)` | `basic: pauza (ms)` | |
| `input: on button A pressed` | `input: gdy przycisk A naciśnięty` | A/B is a dropdown |
| `input: on button B pressed` | `input: gdy przycisk B naciśnięty` | same block, dropdown set to B |
| `input: on shake` | `input: na potrząśnij` | event is a dropdown, default „potrząśnij” |
| `input: light level` | `input: poziom światła` | |
| `logic: if true then else` | `logic: jeśli prawda to w przeciwnym razie` | toolbox has two blocks: `jeśli prawda to` (with a plus) and `jeśli prawda to … w przeciwnym razie` |
| `logic: if... then` | `logic: jeśli... to` | |
| `logic: if` | `logic: jeśli` | |
| `logic: else if` | `logic: w przeciwnym razie jeśli` **(?)** | appears after pressing the plus; the label was not visible |
| `logic: else` | `logic: w przeciwnym razie` | |
| `logic: true` | `logic: prawda` | |
| `logic: 0 = 0` | `logic: 0 = 0` | comparison block, same in both languages |
| `logic: 0 < 0` | `logic: 0 < 0` | same block as `0 = 0` with the operator changed |
| `math: pick random 0 to 10` | `math: wybierz losowo 0 do 10` | |
| `variables: make a variable` | `variables: Utwórz zmienną` | the button is „Utwórz zmienną...” |
| `variables: set steps to 0` | `variables: ustaw kroki na 0` **(?)** | |
| `variables: change steps by 1` | `variables: zmień kroki o 1` **(?)** | |
| `variables: steps` | `variables: kroki` | variable reporter, named by the author |

## Other blocks seen in the Polish editor

Not used in the lessons yet; useful when writing new ones. English names are my own mapping, not verified.

### Podstawowe (basic)

- pokaż liczbę, pokaż LED, pokaż ikonę, pokaż łańcuch, wyczyść ekran, na zawsze, pauza (ms), podczas uruchamiania, pokaż strzałkę (Północ …)

### Wejście (input)

- gdy przycisk A naciśnięty, na potrząśnij, gdy pin P0 naciśnięty
- przycisk A jest wciśnięty, pin P0 jest wciśnięty, przyspieszenie (mg) x, poziom światła, pozycja kompasu (°), temperatura (°C), jest potrząśnij gestem
- gdy dźwięk głośny, na logo naciśnięty, przycisk logo jest wciśnięty, poziom dźwięku
- więcej: kalibruj kompas, siła magnetyczna (µT) x, rotacja (°) kąt, czas pracy (ms), czas pracy (µs), gdy pin P0 zwolniony, ustaw zakres akcelerometru 1g, ustaw dźwięk głośny na poziom 128

### Muzyka (music)

- zagraj melodię … w tempie 120 (bpm), zagraj ton Średnie C przez 1 takt, dźwięk dzwonka (Hz), odpocznij przez 1 takt, ustaw głośność, głośność, zatrzymaj wszystkie dźwięki, zmień tempo o (bpm), ustaw tempo na (bpm), tempo (bpm)
- zagraj melody dadadum w tle, włącz melodię dadadum powtarzaną raz, muzyka gdy nuta melodii zagrana, zatrzymaj melodię wszystkie
- zagraj dźwięk … aż do zakończenia, odtwarzaj do końca dźwięk, odtwórz dźwięk, ustaw wbudowany głośnik wył., dźwięk jest odtwarzany

### LED

- rysuj x y, wyczyść x y, przełącz x y, punkt x y, narysuj wykres słupkowy wartości … aż do …
- więcej: rysunek x y jasność, punkt x y o jasności, jasność, ustaw jasność, przerwij animację, włącz LED, ustaw tryb wyświetlania (czarno-biały)

### Radio

- radio ustaw grupę 1, radio wyślij liczbę 0, radio wyślij wartość "imię" = 0, radio wyślij ciąg ""
- gdy otrzymano radio odebranyNumer (also with the parameters imię wartość, and receivedString), odebrany pakiet siła sygnału
- radio odbierz liczbę, radio odbierz łańcuch znaków, radio zapisz wartość do szeregowego
- więcej: radio ustaw moc przesyłu 7, radio ustaw pasmo częstotliwości na 0, radia ustaw przesył numeru seryjnego prawda, radio zapisz otrzymany pakiet do szeregowego, aktywuj przez radio zdarzenie od źródła MICROBIT_ID_BUTTON_A o wartości MICROBIT_EVT_ANY
- Note: some labels are inconsistent or partly untranslated in the editor ("radia ustaw przesył…" with "radia", parameter names `receivedNumber`, `receivedString`, `name`, `value`, and several "gdy otrzymano radio" blocks whose parameters are hidden in the toolbox). Check the actual block in the editor before quoting it in a lesson.

### Pętle (loops)

- powtórz 4 razy wykonaj, dopóki fałsz wykonaj, dla indeks od 0 do 4 wykonaj, dla elementu wartość z lista wykonaj, co 500 ms, przerwij, kontynuuj, wstrzymaj do prawda

### Logika (logic)

- jeśli prawda to, jeśli prawda to … w przeciwnym razie, 0 = 0, 0 < 0, "" = "", i, lub, nie, prawda, fałsz

### Matematyka (math)

- 0 + 0, 0 - 0, 0 × 0, 0 / 0, reszta z 0 / 1, min z 0 i 0, maks z 0 i 0, bezwzględna 0, pierwiastek kwadratowy 0, zaokrąglenie 0, wybierz losowo 0 do 10, ogranicz 0 między 0 i 0, przelicz 0 z zakresu od 0 do 1023 na zakres od 0 do 4, wybierz losowo prawdę lub fałsz, π
