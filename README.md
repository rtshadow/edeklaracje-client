# E-Deklaracje client

## How to
1) Znajdź interaktywny formularz PDF na [stronie ministerstwa](https://www.podatki.gov.pl/e-deklaracje/zloz-e-deklaracje-pit/) dla PITu, który chcesz złożyć.
2) Wypełnij formularz.
3) Przygotuj plik XML na podstawie [przykładu](examples/deklaracja_pit36.xml). Wpisz wartości z interaktywnego formularza, który właśnie wypełniłeś.
4) Zainstaluj klient edeklaracji: `pip3 install edeklaracje_client`
5) Wyślij deklarację z pliku XML: `edeklaracje send_document twoj_plik.xml`
