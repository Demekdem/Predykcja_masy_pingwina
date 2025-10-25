# Predykcja masy pingwina

## Opis projektu
Projekt pokazuje, jak przewidzieć masę ciała pingwina (w gramach) na podstawie jego cech, takich jak długość i szerokość dzioba, długość płetwy, płeć i gatunek. Celem jest stworzenie modelu, który dobrze dopasowuje się do danych, ale jednocześnie potrafi przewidywać wyniki dla nowych obserwacji.

## Cel
Zbudowanie modelu regresji, który:
- dobrze tłumaczy zmienność masy pingwina,
- unika przeuczenia,
- osiąga R^2  co najmniej 0.75 dla modelu konkurencyjnego (drzewa decyzyjnego).

## Etapy pracy

Wczytanie i przygotowanie danych (czyszczenie, konwersje typów, kodowanie kategorii).

Budowa modelu regresji liniowej z wszystkimi zmiennymi.

Ocena wyników: współczynniki beta, ich istotność, R^2 i p-value modelu.

Analiza reszt – sprawdzenie, czy wariancja błędów jest stała.

Predykcja dla wskazanego pingwina (gatunek maskowy, samiec, 46/21/210 mm).

Utworzenie modelu drzewa decyzyjnego i porównanie R^2
