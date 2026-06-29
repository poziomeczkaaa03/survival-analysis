# Analiza przeżycia odejść klientów w branży fitness

Repozytorium zawiera implementację semiparametrycznego modelu proporcjonalnych hazardów Coxa (zarówno w wersji bazowej, jak i z rozszerzeniami dynamicznymi) w celu identyfikacji czynników wpływających na czas do rezygnacji klientów z członkostwa w sieci fitness. Analiza została przeprowadzona na zbiorze danych obejmującym 5000 obserwacji, a kluczowym elementem było zweryfikowanie założenia o proporcjonalności hazardów za pomocą testu reszt Schoenfelda.

## Zawartość repozytorium

* `semiparametryczny.ipynb` – Jupyter Notebook zawierający pełen kod źródłowy, estymację modelu Coxa oraz testy diagnostyczne.
* `gym_membership_renewal.csv` – zbiór danych z profilami demograficznymi i historią aktywności klientów.
* `membership_renewal_presentation.pdf` – prezentacja podsumowująca wyniki analizy.
