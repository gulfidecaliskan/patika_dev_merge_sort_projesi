# patika_dev_merge_sort_projesi
[Patika.dev'in](https://www.patika.dev/) Veri Yapıları ve Algoritmalar eğitiminin 2. projesidir.

### [16,21,11,8,12,22] -> Merge Sort
### Yukarıdaki dizinin sort türüne göre aşamaları yazınız.

| Dizinin Normal Hali                    |    |    |    | 16 | 21 | 11 | 8 | 12 | 22 |    |    |    |
|----------------------------------------|----|----|----|----|----|----|---|----|----|----|----|----|
| Diziyi ikiye bölüp yeniden yazıyoruz.  |    |    | 16 | 21 | 11 |    |   | 8  | 12 | 22 |    |    |
| Üçlüleri 2-1 şeklinde bölüyoruz.       |    | 16 | 21 |    | 11 |    |   | 8  | 12 |    | 22 |    |
| Her biri tek kalacak hale getiriyoruz. | 16 |    | 21 |    | 11 |    |   | 8  |    | 12 |    | 22 |

Bölme işlemimizi bitirdik. Şimdi ise her bir grubu tekrar sıralı bir şekilde birleştirmemiz gerekiyor.

|     İkili sıralayarak birleştirdik.     | 16 | 21 |    | 11 |    |    |  8 | 12 |    | 22 |   |   |
|:---------------------------------------:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:-:|:-:|
|   Üçlü grup haline getirip sıraladık.   |    |    | 11 | 16 | 21 |    |    |  8 | 12 | 22 |   |   |
| Son birleştirmeyle dizimizi elde ettik. |    |    |    |  8 | 11 | 12 | 16 | 21 | 22 |    |   |   |


### Big-O gösterimini yazınız.
- Merge Sort bir Böl ve Fethet (Divide and Conquer Algorithm) algoritmasıdır. Big-O gösterimi ise O(nlogn) dir. Sebebi ise dizinin tekrar tekrar ikiye bölünmesidir.

