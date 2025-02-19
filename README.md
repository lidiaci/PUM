# PUM
Zadania wykonane w ramach przedmiotu PUM

## Regresja liniowa
W ramach zadania stworzono klasę pozwalającą stworzyć model regresji liniowej wyliczonej numerycznie, analitycznie oraz analitycznie z regularyzacją Tichonowa. Warianty zostały porównane między sobą oraz z regresją liniową z sklearn.

## Klasyfikacja liniowa
W pliku został zaimplementowany klasyfikator liniowy oparty o regresję liniową z regularyzacją Tichonowa. Został on porównany z implementacją z sklearn. W pliku znajduje się również wstępna analiza danych zbioru danych o chorobach z Cleveland oraz wybór cech.

## Regresja logistyczna
W pliku znajduje się własna implementacja regresji logistycznej oraz jej porównanie z regresją liniową z biblioteki sklearn. Zostały one porównane na syntetycznych zbiorach oraz na zbiorze Rain in Australia.

## SVM
W pliku znajduje się własna implementacja klasyfikatora SVM z trzema wariantami kerneli: linear, radial oraz polynomial. Został on porównany z odpowiednikiem z biblioteki sklearn i porównany na syntetycznych zbiorach oraz zbiorze SDSS17.

## Drzewa decyzyjne
W pliku znajduje się implementacja drzewa decyzyjnego i jej porównanie z odpowiednikiem z sklearn. Porównanie zostało dokonane na trzech zbiorach syntetycznych - make_moons, zbiorze jednomodowym oraz wielomodowym - oraz zbiorze HTRU2.

## Las losowy
W pliku został zaimplementowany klasyfikator lasu losowego. Został on porównany z lasem losowym dostępnym z bibliotece sklearn na trzech zbiorach syntetycznych oraz zbiorze NASA JPL Asteroid.

## Neuron
W pliku został zaimplementowany pojedynczy neuron z różnymi funkcjami aktywacji z możliwością zastosowania wyżarzania cosinusowego. Porównane zostały różne funkcje aktywacji.

## Sieć neuronowa
W pliku została zaimplementowana prosta klasa umożliwiająca stworzenie sieci neuronowej z aktywacją funkcją logistyczną oraz ReLU. Działanie zostało zaprezentowane na syntetycznym zbiorze oraz na zbiorze MNIST.
