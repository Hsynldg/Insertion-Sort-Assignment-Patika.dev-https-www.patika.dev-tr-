
[16,21,11,8,12,22] -> Merge Sort

1. Merge'e göre sıralama:

|Steps|Divided & Merged Schema|
|:--:|:--:|
| İlk ayırma                                             |[16,21,11,8,12,22]|
| İkinci ayırma                                          |[16,21,11] - [8,12,22]|
| Üçüncü ayırma                                          |[16] - [21,11] - [8] - [12,22]|
| Dördüncü ayırma                                        |[16] - [21] - [11] - [8] - [12] - [22]|
| ilk birleştirme                                        |[16] - [11,21] - [8] - [12,22]|
| İkinci birleştirme                                     |[11,16,21] - [8,12,22]|
| Üçüncü birleştirme                                     |[8,11,12,16,21,22]|

2. Big O notation:

> O(nlogn)