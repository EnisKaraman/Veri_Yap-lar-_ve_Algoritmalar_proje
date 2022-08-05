Birleştirme Sıralama Projesi

Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.


|    |    |    |  16  |  21  |  11  |  8  |  12  |  22  |    |    |    |
|--- |--- |--- |--- |--- |--- |--- |--- |--- |--- |--- |--- |
|    |    |  16  |  21  |  11  |    |    |  8  |  12  |  22  |    |    |
|    |    |    |    |    |    |    |    |    |    |    |    |
|    |  16  |  21  |    |  11  |    |    |  8  |    |  12  |  22  |    |
|    |    |    |    |    |    |    |    |    |    |    |    |
|  16  |    |  21  |    |  11  |    |    |  8  |    |  12  |    |  22  |
|    |    |    |    |    |    |    |    |    |    |    |    |
|    |  16  |  21  |    |  11  |    |    |  8  |    |  12  |  22  |    |
|    |    |    |    |    |    |    |    |    |    |    |    |
|    |    |  11  |  16  |  21  |    |    |  8  |  12  |  22  |    |    |
|    |    |    |    |    |    |    |    |    |    |    |    |
|    |    |    |  8  |  11  |  12  |  16  |  21  |  22  |    |    |    |


            
Zaman karmaşıklığı O(nlogn).Liste 6 elemanlı olduğundan O(6log6) olacaktır.
