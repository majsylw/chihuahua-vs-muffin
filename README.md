# Introduction to deep learning - classification
Excercises in Deep learning for polish students conducted in winter 2020/21 (polish).
With cooperation with [Wroclaw University of Technology](https://pwr.edu.pl/) and [OPI](https://bip2.opi.org.pl/).
This repository based on [materials from beginner's workshop for SJSU ML Club](https://github.com/mlatsjsu/workshop-chihuahua-vs-muffin) and [DETR](https://github.com/facebookresearch/detr).

All materials are prepared in polish.

# Instalacja

## 1: Instalacja interpretera

Interpreter pythona jest dostępny na oficjalnej stronie [python.org](https://www.python.org/downloads/). Upewnij się, że pobierasz wersję 3.x (obecnie aktualną jest wersja 3.9) na obsługiwany system operacyjny.

## 2: Instalacja modułów
Wprowadź w terminalu poniższą linijkę:
```
pip3 install numpy jupyter matplotlib pillow tqdm
```
lub jeśli korzystasz z [Anacondy](https://www.anaconda.com/products/individual#Downloads)
```
conda install numpy jupyter matplotlib pillow tqdm
```
Następnie ze strony [pytorcha](https://pytorch.org/get-started/locally/) wybierz opcje odpowiednie dla obsługiwanego systemu i posiadanego sprzętu (w przypadku braku GPU, wskaż na "None" przy wierszu "CUDA"). W tym tutorialu korzystałam z
- pytorcha w wersji 1.7.1 na cpu
- torchvision w wersji 0.8.2 na cpu

## 4: Praca w interaktywnym notatniku jupytera
Pobierz (lub sklonuj) bieżące repozytorium i w terminalu uruchom jupyter notebook.
Następnie wybierz notatnik 'Sztuczna_inteligencja_w_świecie_rzeczywistym.ipynb'.

# Dalsze kroki
Zastanów się czy jesteś w stanie poprawić osiągnięty przez sieć wynik.
Może warto zwiększyć liczbę epok? Albo algorytm aktualizujący wagi? 
Może warto zadbać o inny wygląd sieci (podpowiedź: warstwy konwolucyjne - [nn.Conv2d](https://pytorch.org/docs/stable/generated/torch.nn.Conv2d.html))?
**Eksperymentuj!**
