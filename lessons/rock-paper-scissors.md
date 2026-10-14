# Kamień, papier, nożyce

## @showdialog
W tym projekcie zamienisz swojego micro:bita w grę w kamień, papier, nożyce.

## 
Nie potrzebujesz bloków ``||basic: podczas uruchamiania||`` ani ``||basic: na zawsze||``, więc przeciągnij je z powrotem do zestawu narzędzi (środkowa część ekranu).

## 
W kategorii Wejście znajdź blok ``||input: na potrząśnij||`` i przeciągnij go do okna z kodem.

## 
W kategorii Zmienne kliknij ``||variables: Utwórz zmienną||`` i nazwij ją „losowa-liczba”.

## 
Znajdź blok ``||variables: ustaw losowa-liczba na 0||`` (w kategorii Zmienne) i umieść go wewnątrz bloku ``||input: na potrząśnij||``.

## 
Aby gra była uczciwa, znajdź blok ``||math: wybierz losowo 0 do 10||`` (w kategorii Matematyka).

Upuść go na 0 w bloku ``||variables: ustaw losowa-liczba na 0||``.

## 
W bloku ``||math: wybierz losowo 0 do 10||`` zmień 0 na 1, a 10 na 3.
Teraz micro:bit będzie losował liczbę od 1 do 3, ponieważ mamy 3 możliwości: kamień, papier lub nożyce.

## 
Teraz sprawdźmy zmienną „losowa-liczba”. Znajdź blok ``||logic: jeśli prawda to w przeciwnym razie||`` (w kategorii Logika) i umieść go pod blokiem ``||variables: ustaw losowa-liczba||``.

Znajdź blok porównania ``||logic: 0 = 0||`` (w kategorii Logika) i upuść go na słowo „prawda”.

## 
Znajdź blok ``||variables: losowa-liczba||`` (w kategorii Zmienne) i upuść go na pierwsze 0.

Następnie zmień drugie 0 na 1.

## 
Znajdź blok ``||basic: pokaż ikonę||`` (w kategorii Podstawowe) i umieść go pod ``||logic: jeśli||``.

Zmień serce na małą kwadratową ikonę (oznacza kamień).

## 
Kliknij znak plus „+”, aby rozszerzyć blok ``||logic: jeśli prawda to w przeciwnym razie||``.

Kod rozszerzy się o ``||logic: w przeciwnym razie jeśli||``.

## 
Tak jak poprzednio, znajdź blok ``||logic: 0 = 0||`` (w kategorii Logika) i upuść go w puste miejsce po ``||logic: w przeciwnym razie jeśli||``.
Znajdź blok ``||variables: losowa-liczba||`` (w kategorii Zmienne) i upuść go na pierwsze 0.

Następnie zmień drugie 0 na 2.

## 
Znajdź blok ``||basic: pokaż ikonę||`` (w kategorii Podstawowe) i umieść go pod ``||logic: w przeciwnym razie jeśli||``.

Zmień serce na dużą kwadratową ikonę (oznacza papier).

## 
Użyjmy logicznego myślenia, aby kod był krótszy. Jeśli zmienna losowa-liczba jest z przedziału od 1 do 3 i nie jest ani 1, ani 2, to musi być 3.

Dlatego dodaj blok ``||basic: pokaż ikonę||`` z ikoną nożyc pod ``||logic: w przeciwnym razie||``.

## 
Przetestuj swój kod w symulatorze, naciskając przycisk potrząsania.

Czy ikony kamienia, papieru i nożyc pojawiają się losowo?

## 
Teraz pobierz swój kod na micro:bita. Naciśnij przycisk pobierania i postępuj zgodnie z instrukcjami.

Spróbuj zagrać w kamień, papier, nożyce przeciwko innemu micro:bitowi lub człowiekowi!

## @showdialog
Gratulacje – udało Ci się stworzyć na micro:bicie grę w kamień, papier, nożyce!
