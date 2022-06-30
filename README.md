# RSC-Project2
Project created for Recommender-System-Class

Celem projektu było stworzenie systemu rekomendacyjnego, który dla danych dotyczących rezerwacji hotelowych byłby skuteczniejszy od rekomendera Amazona, tzn. lepiej przewidywałby prawdopodobieństwo interakcji pomiędzy użytkownikiem a przedmiotem (usługą hotelową). Pierwszym zadaniem było wykonanie wstępnej obróbki danych. Zasadniczo udało się je wykonać już w ramach pierwszego projektu. W ramach aktualnego projektu udało się poprawić problemy z agregacją grupowych rezerwacji.

W zasadniczej części zadania udało się stworzyć działający rekomender porównywany pod względem skuteczności z rekomenderem Amazona (HR@10 na poziomie 0.25). W pliku głównym "project_2_recommender_and_evaluation" wykonano przewidziane zadania oraz dodatkowo rozwiązano problemy z brakami danych w przygotowaniu cech użytkowników.

Zasadnicze składowe projektu: Dwa pliki typu Jupyter Notebook:

project_1_data_preparation.ipynb,
project_2_recommender_and_evaluation.ipynb,
Pliki do wstępnego przetworzenia danych:

data_preprocessing/data_preprocessing_toolkit.py,
data_preprocessing/dataset_specification.py.py,
data_preprocessing/people_identifier.py.py,
Plik z danymi: data/hotel_data/hotel_data_original.csv.

Dodatkowo załączone są również pliki zapożyczone z repozytorium zajęć z systemów rekomendacyjnych oraz wersje HTML obydwu notebooków.

Wymagane pakiety (instalowane poprzez wpisanie w wierszu poleceń "pip install <nazwa_pakietu>"):
- numpy
- pandas
- matplotlib.pyplot
- seaborn
- notebook

Aby uruchomić projekt, w wierszu poleceń, w folderze, w którym znajduje się projekt, wpisujemy komendę "jupyter notebook". Jupyter uruchomi się w przeglądarce i będziemy mieli możliwość otwarcia interesującego nas pliku.
