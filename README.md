# Insertion-Sort-Projesi
www.patika.dev
### [22,27,16,2,18,6] -> Insertion Sort
#### 1- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
İlk eleman olan 22'yi 27 ile kıyaslıyoruz. 22 sayısı 27'den küçük. Doğru sıralama!<br><br>
**[22] ,27,16,2,18,6** Artık 22 sayısını dizinin içine gönderebilirim.<br><br>
27 ve 16 kıyaslanıyor. 16 küçük 27 ile yer değiştiriyor.<br><br>
**[22],16,27,2,18,6**<br><br>
**[16,22],27,2,18,6**  Dizinin içerisine giren 16, 22 ile de karşılaştırılıyor.<br><br>
27 ve 2 kıyaslanıyor.<br><br>
**[16,22],2,27,18,6** Diziye alınıp dizinin içerisinde kıyaslama yapılıyor.<br><br>
**[2,16,22],27,18,6**<br><br>
27 ile 18 kıyaslanıyor.<br><br>
**[2,16,22],18,27,6**  Diziye alınıp dizinin içerisinde kıyaslama yapılıyor.<br><br>
**[2,16,18,22],27,6**<br><br>
27 ile 6 kıyaslanıyor.<br><br>
**[2,16,18,22],27,6**<br><br>
**[2,16,18,22],6,27** Diziye alınıp dizinin içerisinde kıyaslama yapılıyor.<br><br>
**[2,6,16,18,22],27**<br><br>
**[2,6,16,18,22,27]** İşte hazır!!!<br><br>
#### 2-Big-O gösterimini yazınız.
O(n^2)
#### 3-Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
#### 4- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
18 average case kapsamına girer.
#### 5- [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
**[3],7,5,8,2,9,4,15,6**<br>
**[3,5],7,8,2,9,4,15,6**<br>
**[3,5,7],8,2,9,4,15,6**<br>
**[3,5,7],2,8,9,4,15,6**<br>
**[2,3,5,7],8,9,4,15,6**<br>
