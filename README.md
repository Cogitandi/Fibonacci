# Fibonacci

Aplikacja pozwalająca wyliczyć K-ty element ciągu Fibonacciego na podstawie podanej wartości

![Alt text](intro.png?raw=true "Aplikacja")
## Technologie
* Docker
* Vue.JS


## Domyślne ustawienia
* Aplikacja będzie dostępna pod adresem http://localhost:8080/

## Uruchomienie tylko aplikacji internetowej
```
docker build -t aplikacja .
docker run -dp 8080:8080 aplikacja
```

## Uruchomienie aplikacji równocześnie z testami
```
docker compose up
```