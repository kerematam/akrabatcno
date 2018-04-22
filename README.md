Akraba TC kimlik no algoritması 

Bilindiği üzere TC No toplamda 11 haneden oluşuyor. Fakat en sondaki iki hane kendisinden önce gelen dokuz haneden belli bir algoritmaya göre türetiliyor. Böylelikle rastgele uydurulan herhangi 11 haneli sayı TC kimlik no özelliğini taşımamış oluyor.

Kimlik numarasının 10'uncu hanesi; kimilk numarsanın 1'inci, 3'üncü, 5'inci, 7'inci ve 9'uncu hanelerindeki rakamların toplamının 7 ile çarpımından, kimlik nurasanın 2'inci, 4'üncü, 6'ıncı ve 8'inci hanlerindeki rakamların çıkarılmasından elde edilen sayının 10'a bölümünden kalan ile elde ediliyor.
10uncu= mod 10 [ 7x (1inci + 3üncü + 5inci + 7nci + 9uncu) - ( 2inci + 4üncü + 6ıncı + 8inci ) ]

Kimlik numarasının 11'uncu hanesi; kimlik numarasının kendisinden önce gelen 10 hanedeki rakamların toplamının 10'a bölümünden kalan ile elde ediliyor.
11inci= mod 10 [ 1inci + 2inci + 3üncü  + 4üncü + 5inci + 6ıncı + 7nci + 8inci + 9uncu  + 10uncu ]
Akraba kimlik numarası elde etmek için de, (sizinle aynı soyadını paylaşann başka birinin kimlik numarasına ulaşmak için); Kimlik numarasının anlamlı dokuz rakamı alınır ve baştan beş hane ve sonraki dört hane olmak üzere ikiye ayrılır.

Örnek(1) 11111 - 1111 - 10 gibi...

Ardından 5 basamaklaı kısma 3 ekleyip, 4 basamaklı kısımdan 1 çıkarıldığında elde edilen yeni dokuz haneli sayıydan yukarıda belirtildiği gibi 10'uncu ve 11'inci hanelerin hesaplanması ile yeni kimilk numarası elde edilmiş olur.

Örnek(2):  11114- 1110 - 56

Bu şekilde genelde sizden yaşça daha büyük bir akrabalarınızın kimlik numarasına ualşırısnız. Aynı şekilde 3 çıkartılıp, 1 eklediğiniz taktirde tam tersi gerçekleşir. Yukarı da bu hesaplamaları kolaylaştırma amacıyla JavaScript'te bu algoritmayı uygulamaya çalıştım. Program şuan dört dörtlük çalışmasa bile aşağı yukarı istenileni veriyor. Hataları düzeltmeye çalışıyorum henüz. Ben bu yolla en son 1903 doğumlu babamın halasının kimlik numarasına kadar yaklaşık 40 akrabamın kimlik numaralarına ulaştım. Çoktan vefat etmiş kişilerin bile kimlik numaralarının çıkarılması ilginç. Kişi hala yaşıyorsa ikamet ettiği adres bilgilerini http://www.ysk.gov.tr/ysk/index.html adresinden elde edebilirsiniz.

http://akrabatcno.com


## akrabatcno
