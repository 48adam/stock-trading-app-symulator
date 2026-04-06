
# Stock Trading App Symulator

**Stock Trading App Symulator** to desktopowa aplikacja edukacyjna napisana w **C++**, która pozwala ćwiczyć inwestowanie przy użyciu **wirtualnego kapitału**, ale w oparciu o **rzeczywiste ceny akcji**. Projekt powstał jako połączenie nauki rynku finansowego i rozwijania umiejętności programowania w C++.

## O projekcie

Celem aplikacji jest umożliwienie użytkownikowi bezpiecznego testowania podstaw inwestowania bez ryzyka utraty prawdziwych środków. Program oferuje prosty interfejs graficzny, system użytkowników oraz obsługę portfela inwestycyjnego.

Aplikacja pozwala logować się, przeglądać akcje, kupować i sprzedawać je oraz śledzić łączną wartość posiadanego portfolio.

## Najważniejsze funkcje

- rejestracja i logowanie użytkownika
- symulacja inwestowania przy użyciu wirtualnej gotówki
- przeglądanie rynku akcji
- kupno i sprzedaż akcji
- zapis średniej ceny zakupu
- obliczanie wartości portfela
- aktualizacja cen akcji w określonych odstępach czasu
- graficzny interfejs użytkownika oparty o SFML

## Technologie

- **C++**
- **SFML**
- **nlohmann/json**
- **Python** (`plot.py`)
- integracja z danymi cenowymi z Yahoo

## Struktura projektu

- `main.cpp` — uruchomienie aplikacji i główna pętla programu
- `okno.cpp`, `okno.h` — interfejs aplikacji oraz logika widoków
- `UserManager.*` — obsługa użytkowników i logowania
- `Stock.*` — model danych akcji
- `StockMarket.*` — pobieranie i aktualizacja danych rynkowych
- `PortfolioManager.*` — zarządzanie portfolio użytkownika
- `plot.py` — pomocnicza wizualizacja danych

## Jak uruchomić

1. Sklonuj repozytorium
2. Skonfiguruj środowisko C++ z biblioteką SFML
3. Dodaj zależność `nlohmann/json`
4. Skompiluj pliki źródłowe
5. Uruchom aplikację

## Założenia projektu

Aplikacja została zaprojektowana jako narzędzie edukacyjne, które:

- uczy podstaw kupna i sprzedaży akcji,
- pozwala obserwować zmiany wartości portfela,
- pokazuje, jak zorganizować większy projekt C++ z podziałem na klasy i moduły,
- łączy logikę biznesową z prostym GUI.

## Status

Projekt jest prototypem aplikacji do nauki inwestowania i rozwijania umiejętności programistycznych w C++.

## Autor

Repozytorium zostało opublikowane przez **48adam**.
