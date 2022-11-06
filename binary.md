# Binary Search Tree Projesi #

Proje 3

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

 dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

___

Dizinin ilk elemanı olan 7 yi root olarak alıyoruz.

                    7 (root)
                
Dizinin ikinci elamanı 5 olduğundan ve root olan 7 den küçük olduğundan 7 nin soluna birinci düğüm satırına yazıyoruz.

                    7                  root satırı
                    
                /

            5                          1. Düğüm satırı

Dizinin üçüncü elemanı 1 olduğundan ve 7 ve 5 den küçük olduğundan 5 in soluna ikinci düğüm satırına yazıyoruz.

                    7                  root satırı

                /

            5                          1. Düğüm satırı

        /

    1                                  2. Düğüm satırı


Dizinin dördüncü elamanı 8 olduğundan ve root olan 7 den büyük olduğundan 7 nin sağına birinci düğüm satırına yazıyoruz.

                    7                  root satırı

                /       \

            5               8          1. Düğüm satırı

        /                       

    1                                  2. Düğüm satırı

Dizinin beşinci elemanı 3 olduğundan ve 7 ve 5 den küçük olduğundan 1 den büyük olduğundan 1 in sağına üçüncü düğüm satırına yazıyoruz.


                        7              root satırı

                    /       \
                    
                5               8      1. Düğüm satırı

            /       

        1                              2. Düğüm satırı

            \

                3                      3. Düğüm satırı

Dizinin altıncı elemanı 6 olduğundan ve 7 den küçük 5 den büyük olduğundan 5 in sağına ikinci düğüm satırına yazıyoruz.

                        7              root satırı

                    /       \
                
                5               8      1. Düğüm satırı

            /       \

        1               6              2. Düğüm satırı

            \

                3                      3. Düğüm satırı

Dizinin yedinci elemanı 0 olduğundan ve 7 den 5 den ve 1 den küçük olduğundan 1 in soluna üçüncü düğüm satırına yazıyoruz.

                            7              root satırı

                        /       \

                    5               8      1. Düğüm satırı

                /       \

            1               6              2. Düğüm satırı

        /       \

    0               3                      3. Düğüm satırı

Dizinin sekizinci elemanı 9 olduğundan ve 7 den 8 den büyük olduğundan 8 in sağına üçüncü düğüm satırına yazıyoruz.

                            7                           root satırı

                        /       \

                    5               8                   1.Düğüm satırı

                /       \               \

            1               6               9           2.Düğüm satırı

        /       \

    0               3                                   3.Düğüm satırı

Dizinin dokuzuncu elamanı 4 olduğundan ve 7 ve 5 den küçük olduğundan 1 den ve 3 den büyük olduğundan 3 ün sağına dördüncü düğüm satırına yazıyoruz.

                            7                           root satırı

                        /       \

                    5               8                   1. Düğüm satırı

                /       \               \

            1               6               9           2. Düğüm satırı

        /       \

    0               3                                   3. Düğüm satırı


                        \

                            4                           4. Düğüm satırı

Dizinin onuncu elamanı 2 olduğundan ve 7 ve 5 den küçük olduğundan 1 den büyük olduğundan 3 den küçük olduğundan 3 ün soluna dördüncü düğüm satırına yazıyoruz.

                            7                        root satırı

                        /       \

                    5               8                1. Düğüm satırı

                /       \               \

            1               6               9        2. Düğüm satırı

        /       \

    0               3                                3. Düğüm satırı

                /       \

            2               4                        4. Düğüm satırı

___

[www.patika.dev](https://www.patika.dev/tr)




