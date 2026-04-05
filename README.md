# Przewidywanie Wyników Studentów

## O Projekcie
Niniejsze repozytorium zawiera projekt zaliczeniowy zrealizowany w ramach naszych pierwszych zajęć z przedmiotu Uczenie Maszynowe na studiach. Przeszliśmy w nim przez cały proces analizy danych oraz budowy modeli predykcyjnych od początku aż do wyciągnięcia biznesowych wniosków. Głównym celem było zbadanie, jakie czynniki mają największy wpływ na końcowe oceny studentów.

## Czego się nauczyliśmy?
Jako że były to nasze pierwsze kroki w tej dziedzinie, projekt pozwolił nam na praktyczne opanowanie wielu kluczowych koncepcji:

* **Eksploracja i czyszczenie danych:** Zrozumieliśmy, jak ważne jest przygotowanie informacji przed podaniem ich do modelu. Nauczyliśmy się obsługi braków, zamiany wartości tekstowych na liczbowe (LabelEncoder, OneHotEncoder) oraz standaryzacji (StandardScaler).
* **Balansowanie zbioru:** Poznaliśmy techniki radzenia sobie z nierównymi klasami za pomocą metod takich jak SMOTE oraz RandomUnderSampler.
* **Budowa modeli:** Zbudowaliśmy i porównaliśmy działanie kilku podstawowych algorytmów klasyfikacji i regresji (między innymi: Regresja Logistyczna, Algorytm Najbliższych Sąsiadów, Maszyny Wektorów Nośnych).
* **Ocena skuteczności:** Zamiast ślepo ufać wynikom, nauczyliśmy się korzystać z metryk takich jak dokładność (accuracy), precyzja, czułość oraz czytać macierz pomyłek.
* **Wizualizacja:** Wykorzystaliśmy biblioteki Matplotlib oraz Seaborn do tworzenia czytelnych wykresów ułatwiających zrozumienie relacji w danych.

## Zbiór Danych
Analizie poddano zestaw informacji o studentach zawierający 2392 wiersze i 13 kolumn. Przeanalizowaliśmy takie zmienne jak wiek, płeć, wykształcenie rodziców, czas spędzany na nauce w tygodniu, liczba nieobecności oraz zaangażowanie w zajęcia pozalekcyjne.

## Jak uruchomić projekt?
Aby odtworzyć nasze wyniki na własnym komputerze, wykonaj poniższe kroki.

1. Pobierz pliki z tego repozytorium na swój dysk.
2. Upewnij się, że masz zainstalowane wszystkie wymagane biblioteki. Możesz zainstalować je wewnątrz swojego środowiska za pomocą terminala:

```bash
pip install -r requirements.txt
```

3. Uruchom plik notatnika `UM_Wandzel_Walus_Adamiak_Szymczyk.ipynb` w swoim ulubionym edytorze kodu (na przykład Jupyter Notebook, VS Code lub PyCharm) i wykonuj komórki jedna po drugiej.