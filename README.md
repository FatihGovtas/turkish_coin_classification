# turkish_coin_classification
**-->** Türk madeni paralarının tanınması (5, 10, 25, 50 kuruş ve 1 tl) için YOLOV5 ağı kullanıldı.
### Proje Aşamaları	
1)	Veri seti oluşturulması: Çeşitli açılardan para fotoğrafları çekildi(1147). 
2)	Etiketleme: Etiketleme için labelImg programı kullanılarak veriler etiketlendi.
3)	Eğitim: Verilerin %80 eğitim (917) %20 test(230) olacak şekilde ayrıldı. Colab üzerinden ağ eğitimini gerçekleştirildi. Eğitim 30 epoch olarak gerçekleştirildi.
### Model Sonuçları
<img src="https://user-images.githubusercontent.com/74897177/181749841-b2f463a3-5533-4cf5-ba12-7703f7cd0087.png" width=300 height=400>                                <img src="https://user-images.githubusercontent.com/74897177/181750751-b34bd613-bc96-47e8-808a-4f70e9da2dc2.png" width=300 height=400>
