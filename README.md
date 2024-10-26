# Zindi_2
GeoAI Ground-level NO2 Estimation Challenge by ITU

Plik know_data.ipynb zawiera operacje w celu przekształcenia danych
Plik lightgbm.ipynb zawiera model lgb i proces nauki, walidacji i zapisu predykcji na zbiorze testowym
Plik see_differences.ipynb miał na celu wskazanie różnic między zbiorzem testowym, a treningowym

Folder /data składa się z:
Test.csv i Train.csv jako bazowe pliki z strony konkursu
test_elevation.csv i train_elevation.csv posiada unikalne wartości LAT, LON i ich Elevation. 
Czasami API do Elevation nie działało.

Folder /prepared składa się z plików po przygotowaniu z know_data.ipynb
