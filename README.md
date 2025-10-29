# Predykcja masy pingwina

## Opis projektu
Projekt pokazuje, jak przewidzieć masę ciała pingwina (w gramach) na podstawie jego cech, takich jak długość i szerokość dzioba, długość płetwy, płeć i gatunek. 

W kontekście biznesowym pokazuje, jak modele regresyjne mogą wspierać podejmowanie decyzji opartych na danych i prognozowanie wyników w różnych dziedzinach.

## Cel
Celem jest stworzenie modelu, który dobrze dopasowuje się do danych, ale jednocześnie potrafi przewidywać wyniki dla nowych obserwacji.
Model regresji, który:
- dobrze tłumaczy zmienność masy pingwina,
- unika przeuczenia,
- osiąga R^2  co najmniej 0.75 dla modelu konkurencyjnego (drzewa decyzyjnego).

## Etapy pracy

1. Wczytanie i przygotowanie danych - czyszczenie, konwersje typów, kodowanie kategorii.

2. Budowa modelu regresji liniowej z wszystkimi zmiennymi.

3. Ocena wyników: analiza współczynników beta, ich istotność, R^2 i p-value.

4. Analiza reszt – sprawdzenie założeń modelu, w tym stałośći wariancja błędów.

5. Predykcja dla wskazanego pingwina - gatunek maskowy, samiec, 46/21/210 mm.

6. Budowa modelu drzewa decyzyjnego - porównanie R^2 i interpretacja różnic w podejściach.
