
|                                                 |  |  |  |  |  |  |  |  |  |  |  |  |
|-----------------------------------------------  |- |- |- |- |- |- |- |- |- |- |- |- |
|Diziyi ikiye bölerek yeniden yazıyoruz           |  |  |  |16|21|11|8 |12|22|  |  |  |
|                                                 |  |  |  |  |  |  |  |  |  |  |  |  |
|Sol ve sağdaki dizileri tekrar ikiye böluyoruz.  |  |[16,21,11]  | |  |  | |[8,12,22]  |  |
|                                                 |  |  |  |  |  |  |  |  |  |  |  |  |
|Tek eleman kalana kadar bir kez daha bölüyoruz.  |[16,21]| |  |[11]|  |  |[8] |  |[12,22]|  |
|                                                 |  |  |  |  |  |  |  |  |  |  |  |  |
|                                                 |[16]|[21]  |  |[11]|  |  |[8] |  |[12]|  |[22]|
|                                                |  |  |  |  |  |  |  |  |  |  |  |  |
|----------------------------------------------- |- |- |- |- |- |- |- |- |- |- |- |- |
|tek elemanları birleştirirken sıralıyoruz       |[16,21]|  | |[11]|  | |[8] |  |[12,22]|
|                                                |  |  |  |  |  |  |  |  |  |  |  |  |
|1. ve 2. diziyi kendi arasında, 3. ve 4.diziyide kendi arasında sıralayarak birleştiririz          |  |[11,16,21]|  | |  |  |[8,12,22]|  |
|                                                |  |  |  |  |  |  |  |  |  |  |  |  |
|Son birleştirmede dizimizi elde ediyoruz.       |  |  |  |[8,11,12,16,21,22]|  |  |  |

big-O gösterimi : O(nlogn)dir.
