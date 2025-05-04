# Hello World Web

## Opis projektu
To prosty projekt webowy wyświetlający stronę z napisem "Hello, World!". Projekt stworzony do nauki podstaw HTML i uruchamiania lokalnego serwera. Zawiera tylko jeden plik `index.html`.

## Wymagania
Do uruchomienia projektu potrzebny jest tylko Python (wersja 3 lub nowsza) oraz dowolna przeglądarka internetowa.

## Instalacja
1. Najpierw klonuję repozytorium lub pobieram je jako archiwum ZIP:
```bash
git clone https://github.com/moj-login-github/hello-world-web.git
cd hello-world-web
```
2. Upewniam się, że w folderze znajduje się plik `index.html`.

## Przykład użycia – jak uruchomić serwer webowy
Aby wyświetlić stronę lokalnie, uruchamiam prosty serwer HTTP wbudowany w Pythona:
```bash
python -m http.server 8000
```
Następnie wchodzę w przeglądarce na adres:
```bash
http://localhost:8000
```
Powinna pojawić się strona z napisem "Hello, World!".