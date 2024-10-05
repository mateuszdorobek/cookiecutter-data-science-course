{{cookiecutter.project_name}}
==============================

{{cookiecutter.description}}

Project Organization
------------

    ├── README.md          <- Główny plik README dla osób korzystających z tego projektu.
    ├── data
    │   ├── external       <- Dane z zewnętrznych źródeł.
    │   ├── interim        <- Dane pośrednie, które zostały przekształcone.
    │   ├── processed      <- Ostateczne zestawy danych do modelowania.
    │   └── raw            <- Oryginalny, niezmienialny zrzut danych.
    │
    ├── models             <- Wytrenowane i zserjalizowane modele, predykcje modelu lub podsumowania modelu.
    │
    ├── notebooks          <- Notatniki Jupyter. Konwencja nazewnictwa to numer (do sortowania)
    │                         i krótki opis oddzielony myślnikami, np. `1.0-initial-data-exploration`.
    │
    ├── references         <- Treści zadań, opisy danych i wszelkie inne materiały.
    │
    ├── reports            <- Wygenerowane raporty, analizy w formie HTML, PDF, LaTeX itp.
    │    └── figures             <- Wygenerowane grafiki i figury do użycia w raportach.
    │
    ├── requirements.txt   <- Plik wymagań do odtworzenia środowiska analizy, np.
    │                         wygenerowany poleceniem `pip freeze > requirements.txt`
    │
    ├── results            <- Wyniki eksperymentów w formacie CSV.
    │
    └── src                <- Kod źródłowy do użycia w tym projekcie.
        ├── __init__.py    <- Czyni src modułem Pythona
        │
        ├── data           <- Skrypty do pobierania lub generowania danych
        │    └── make_dataset.py
        │
        ├── features       <- Skrypty do przekształcania surowych danych na cechy do modelowania
        │    └── build_features.py
        │
        ├── models         <- Skrypty do trenowania modeli, a następnie używania wytrenowanych modeli do predykcji
        │    │   
        │    ├── predict_model.py
        │    └── train_model.py
        │
        └── visualization  <- Skrypty do tworzenia eksploracyjnych i wynikowych wizualizacji
             └── visualize.py

--------