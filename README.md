# atalay_karttasarimi

<br>

> **Teknofest Roket Yarışması 2022 Orta İrtifa**

<details>
  
- Kartların arka yüzünde STM32F103RB işlemci olup olup ön yüzünde ise kullanacağımız sensörler, gps, haberleşme, ateşleme devresi ve voltaj regülatörü bulunuyor. 
- Kartımız 7-12V ile beslenmekte ve üzerinde güç ledi bulunmaktadır. 
- Voltaj regülatörü 3.3V çıkış vermektedir.
- Ateşleme devresi için mosfet ile optoptokuplör kullanılmıştır.
- Sensör için BME280 basınç sensörü ile ADXL345 ivme sensörü, gps modülü olarak NEO-6M, haberleşme için LORA modülü kullanılmıştır. 
- Kart hakkında sorunuz için kart üzerinde emeği geçen [Cengizhan Topçu](https://www.linkedin.com/in/cengizhantopcu53/) ile [Ferdi Ayhan](https://www.linkedin.com/in/ferdiayhann/) arkadaşlarımızdan bilgi alabilirsiniz.

</details>

| Ana Sistem | Yedek Sistem | Haberleşme | Görev Yükü |
| ------------ | ------------- | ------------- | ------------- |
| <img src="https://user-images.githubusercontent.com/104703949/178975949-c73ea188-78ee-422f-ae1e-443e428f9f21.JPG" width="350"> | <img src="https://user-images.githubusercontent.com/104703949/178975971-cedd0c6c-6338-451e-ba90-f94a9db79941.JPG" width="350"> | <img src="https://user-images.githubusercontent.com/104703949/178976015-2aa9b74b-eeaf-49ca-b19e-2ab924a77f52.JPG" width="320"> | <img src="https://user-images.githubusercontent.com/104703949/178975987-bcb0d98b-03aa-4c32-86b0-55a938d579de.JPG" width="350">|

##
***Kompenentlerin şematik ve pcb kütüphanelerini bu alanda uğraşmak isteyen arkadaşlara yol göstermesi amacıyla paylaşıyoruz. Dosya içerisinde bu sene yapılan pcb kartlarımızda kullandığımız kompenentlerin dosylarına da ulaşabilir ayrıca paylaşım içerisinde step ve datasheet dosyalarını da bulabilirsiniz.***
##

<br><br>

> **Altium ile PCB Çizimi (Temel Seviye)**

Karabük Üniversitesi öğrencilerine yönelik [Karabük Teknoloji ve İnovasyon Derneği](https://www.instagram.com/kartekinder/) üzerinden takım arkadaşlarımız [Cengizhan Topçu](https://www.linkedin.com/in/cengizhantopcu53/) ile  [Ferdi Ayhan](https://www.linkedin.com/in/ferdiayhann/) tarafından 21-22 Mayıs tarihlerinde ücretsiz olarak iki gün boyunca temel seviye pcb eğitimi verilmiştir.

<details>
  <summary>Eğitim İçeriği</summary>
    
 1. Programın Kurulması
 2. Kütüphane Oluşturma
 3. Şematik Tasarım
 4. PCB Tasarımı
 5. Üretim Dosyalarını Oluşturma

</details>

<img src="https://user-images.githubusercontent.com/104703949/180171973-0adf0bc6-bcd4-4074-b656-5cc029cb3bbe.png">
