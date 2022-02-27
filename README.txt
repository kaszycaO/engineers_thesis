Archiwum składa się z następujących zasobów:

 - notatniki ipynb:
   * NST.ipynb - notatnik z zaimplementowanym transferem stylu
   * conv_training.ipynb - notatnik z modułem treningu sieci konwolucyjnej
   
 - foldery:
   * test_data - zbiór testwoych zdjęć do NST
   * models - w folderze znajduje się jeden wytenowany model, którego można użyć w NST (**)
   
 - pliki txt:
   * README.txt - krótki opis zasobów
   * requirements.txt - wymagane biblioteki do uruchomienia obu notatników ipynb.


Wymagania:

 - python3 (testowano na wersji 3.8.5)
 - anaconda (testowano na wersji 4.9.2)
 - sterowniki CUDA do obsługi GPU (https://developer.nvidia.com/cuda-zone)
 - biblioteki wylistowane w pliku requirements.txt
   
   Aby je zainstalować: pip3 install requirements.txt
   lub pip install requirements.txt
