Proje-3
1.[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

Dizinin ilk elemanı olan sayı root olarak seçilir. Bizim root değerimiz '7' olacaktır.

1. Aşama: Root değeri olarak 7 yazdıktan sonra dizinin ikinci elemanına bakıyoruz. '5' sayısı root olan '7' sayısından küçük olduğu için sol tarafına yazılır.

2. Aşama: Sonra üçüncü eleman incelenir. '1' sayısı root olan '7' sayısından küçük olduğu için sol tarafa eklenmesi gerekir. Daha önceden sol tarafa eklenmiş '5' sayısından da küçük olduğu için '1' sayısı '5' sayısının sol tarafına eklenir.

3. Aşama: Dördüncü eleman '8' sayısı root olan '7' sayısından büyük olduğu için root değerinin sağ taraına eklenir.

4. Aşama: Beşinci eleman '3' sayısı root değerinden küçük olduğu için sol tarafa eklenmelidir. Önceki aşamalarda sol tarafa eklenmiş değerlere göre değerlendirilmesi yapılır. Sol tarafta bulunan '5' sayısından küçük olduğu için onun da sol tarafına eklenmelidir. '5' sayısının solunda bulunan '1' sayısına göre değerlendirildiğinde '1' sayısından büyük olduğundan dolayı '1' sayısının sağ tarafına yazılır.

5. Aşama: Altıncı eleman '0' sayısı root değerimizden küçük olduğu için sol tarafa yazılması gerekir. Diğer aşamlarda olduğu gibi '0' sayısı sol tarafta bulunan sayılarla kıyaslama apılmaya başlar. Yapılan değerlendirme sonucunda '1' sayısından küçük olduğu için sol tarafa eklenir.

6. Aşama: Yedinci eleman '9' sayısı root sayısından büyük olduğu için sağ tarafa yazılacaktır. Üçüncü aşamada sağ tarafa yazılan '8' sayısından da büyük olduğu için '8' sayısının da sağına yazılacaktır.

7. Aşama: Sekizinci eleman '4' sayısı root değerinden küçük olduğu için sol tarafa yazılacaktır. Gerekli takip yapıldığında '1'sayısından büyük olduğu için bu sayının sağ tarafında bulunması gerekmektedir. Daha önceden '1' sayısının sağ tarafına eklenen '3' sayısı ile kıyaslama yapılır. Bu sayıdan da büyük olduğu için '3' sayısının sağ tarafına eklenir.

8. Aşama: Son eleman '2' sayısı root değerimizden küçük olduğu için ağacımızın sol tarafında bulunacaktır. İncelemeler yapıldığında '1' sayısından büyük olduğu için bu sayının sağ tarafında olması gerekir. Yalnız bir sayısının sağ tarafına dördüncü aşamada eklenen '3' sayısından küçük olduğu için bu sayının sol tarafında eklenir.

Son olarak aşağıdaki görüntü elde edilir:

				    7
			      /   \
			    5       8
			  /   \       \
			1       6       9
		  /   \
	    0       3
			  /   \
			2       4


