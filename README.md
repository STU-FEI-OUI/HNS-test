# HNS - Hlboké neurónové siete

Predmet Hlboké neurónové siete je pokračovanie predmetov Umelá inteligencia 1 a 2 , kde riešime pokročilé architektúry hlbokých neurónových sietí, ich princípy a algoritmy učenia.
Cieľom predmetu je naučiť vytvárať a trénovať vlastné štruktúry hlbokých neurónových sietí a aplikovať ich na rôzne úlohy v oblasti robotiky, kybernetiky a medicíny. 

## Aplikačné oblasti:
- klasifikácia a rozpoznávanie hlbokými neurónovými sieťami 
- modelovanie a predikcia hlbokými neurónovými sieťami
- detekcia a segmentácia objektov hlbokým učením 
- generatívne neurónové siete
- attention mechanizmus a transformery, vizuálne transformery, hybridné systémy
- metódy detekcie defektov materiálov, porúch zariadení
- metódy rozpoznávania vybraných ochorení  
- rozpoznávanie gest, tváre a hlasových povelov konvolučnými neurónovými sieťami
- jednoduchých aplikácií LLM v oblasti robotiky

## Harmonogram prednášok a cvičení:
[Harmonogram prednášok a cvičení](Zadania/HarmonogramPredmetu_HNS2026.pdf)

## Podmienky na absolvovanie predmetu: 
V priebehu semestra majú študenti možnosť získať 60 bodov za vypracovanie projektových úloh. (2 jednoduchšie zadania úloh a 2 projekty). Maximálny bodový zisk zo skúšky je 40 bodov. 

## Zadania úloh a projektov:
### Zadania 1:
[Zadanie 1 - Klasifikácia terénu pomocou SVM, MLP, LSTM a CNN](Zadania/HNS_Zadanie1.pdf)

Dataset a Programy k Zadaniu 1: [GoogleDisk - HNS/Cvicenia/Zadanie1](https://drive.google.com/drive/folders/11j4FFFKerQn-D_06xCKMpK6MajYdHAc3?usp=drive_link)

Obsah Adresára:
| Súbor | Obsah |
|--------|--------|
| outdoor_terrain_classification_database.zip | Dataset meraných signálov z akceleromerta, gyroskopu a magnetometra pre účely klasifikácie terénu  |
| python_programy.zip | Demo ukážky pre príklady klasifikácie pomocou MLP, LSTM a CNN v Pythone |
| Priklad_FashionMNIST_Matlab.zip | Demo príklad v Matlabe pre FashionMNIST |
| Programy_Zadanie1_Matlab.zip | Demo príklad v Matlabe pre rozpoznávanie číslic - MLP a CNN |
| Demogesta_Matlab.zip | Demo príklad v Matlabe pre rozpoznávanie dynamických gest - LSTM |
| HNS_Zadanie1.pdf | Dokument zadania 1 |

Literatúra:

[Peter Sarcevic - Online Outdoor Terrain Classification Algorithm ...](https://www.mdpi.com/2079-9292/12/15/3238)

[Ersek, Kajan, Korosi - Vibration based terrain classification...](https://reference-global.com/article/10.2478/jee-2025-0044)

### Zadania 2:
[Zadanie 2 - Detekcia objektov](Zadania/HNS_Zadanie2.pdf)

Dataset a Programy k Zadaniu 2: [GoogleDisk - HNS/Cvicenia/Zadanie1](https://drive.google.com/drive/folders/11j4FFFKerQn-D_06xCKMpK6MajYdHAc3?usp=drive_link)

### Projekt 1:
[Projekt 1 - Porovnanie štruktúr neurónových modelov pri úlohe klasifikácie obrazov](Zadania/HNS_Projekt1.pdf)

[Datasety k Projektu 1](https://github.com/STU-FEI-OUI/HNS-Projekt1)


### Projekt 2:
[Projekt 2 - Aplikačné úlohy klasifikácie s realizáciou na kamere](Zadania/HNS_Projekt2.pdf)

[Datasety k Projektu 2](https://github.com/STU-FEI-OUI/HNS-Projekt1)


## Príklady programov:

Príklady rozpoznávania oblečenia - fashionMNIST Dataset, pomocou CNN
* Keras: [fashionMNIST_keras.ipynb](Programy/fashionMNIST_keras.ipynb)
* Pytorch: [fashionMNIST_pytorch.ipynb](Programy/fashionMNIST_pytorch.ipynb)


