# Krokomierz

## @showdialog

W tym projekcie zamienisz swojego micro:bita w krokomierz.

## 
Nie potrzebujesz bloku ``||basic: na zawsze||``, więc przeciągnij go z powrotem do przybornika (środkowa część ekranu).

## 
Najpierw musimy utworzyć zmienną. Zmienna to pojemnik na dane, które chcemy wykorzystać później.

W kategorii Zmienne kliknij ``||variables: Utwórz zmienną||`` i nazwij ją „kroki”.

## 
Pojawiło się kilka nowych bloków. Znajdź blok ``||variables: ustaw kroki na 0||`` i umieść go wewnątrz bloku ``||basic: podczas uruchamiania||``.

Dzięki temu po uruchomieniu programu liczba zapisana w zmiennej „kroki” zostanie ustawiona na 0.

## 
Następnie znajdź blok ``||input: po potrząśnięciu||`` (w kategorii Wejście) i przeciągnij go do okna z kodem.

## 
Następnie znajdź blok ``||variables: zmień kroki o 1||`` (w kategorii Zmienne) i umieść go wewnątrz bloku ``||input: po potrząśnięciu||``.

Zwiększy to liczbę zapisaną w zmiennej „kroki” o 1 za każdym razem, gdy potrząśniesz micro:bitem lub nim poruszysz.

## 
Teraz pokażmy liczbę wykonanych kroków.

Znajdź blok ``||basic: pokaż liczbę||`` (w kategorii Podstawowe) i umieść go pod blokiem ``||variables: zmień kroki o 1||``.

## 
Musimy pokazać liczbę zapisaną w zmiennej „kroki”.

Znajdź zmienną ``||variables: kroki||`` (w kategorii Zmienne) i upuść ją na 0 w bloku ``||basic: pokaż liczbę||``.

## 
Przetestujmy Twój kod w symulatorze micro:bita na ekranie. W symulatorze pojawił się teraz przycisk potrząsania do testowania.

Naciśnij przycisk potrząsania, a liczba pokazana na micro:bicie powinna wzrosnąć.

## 
Teraz pobierz swój kod na micro:bita. Naciśnij przycisk pobierania i postępuj zgodnie z instrukcjami.

Gdy potrząśniesz micro:bitem, liczba pokazana na micro:bicie powinna wzrosnąć.

## @showdialog

Gratulacje – udało Ci się stworzyć krokomierz na micro:bicie!
