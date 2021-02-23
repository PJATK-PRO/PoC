# hrprojekt

## instalacja
1. Pobierz projekt używając git clone.
2. Z poziomu rootu projektu wykonaj polecenie instalacji modułów node:
```shell
npm i
```

## uruchomienie
1. Z poziomu wykonaj polecenie uruchomienia serwera lokalnego:
```shell
npm start
```
2. W przeglądarce przejdź na stronę serwera (domyślnie http://localhost:3000/)

_numer portu widoczny jest w pliku bin/www:_
```javascript
var port = normalizePort(process.env.PORT || '3000');
```
