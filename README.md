-Adam Asmaca Oyunu (Java)-

Bu proje, Java programlama dili ve Swing kütüphanesi kullanılarak geliştirilmiş masaüstü tabanlı bir "Adam Asmaca" (Hangman) oyunudur.

-Özellikler-
Güvenli Giriş Sistemi: Oyun başlatılmadan önce txt tabanlı bir şifre kontrol mekanizması devreye girer. Başarılı ve başarısız tüm giriş denemeleri loglanır.

Sekmeli Arayüz (JTabbedPane): Oyun, Skorlar ve Loglar olmak üzere üç farklı sekme üzerinden yönetilir.

Dinamik Kelime Seçimi: kelimeler.txt dosyasından rastgele çekilen kelimeler ile oyun oynanır.

Görsel Geri Bildirim: Kullanıcının hatalı harf veya kelime tahminlerine göre 11 aşamalı adam asmaca görselleri dinamik olarak güncellenir.

Kayıt Sistemi: Oynanan oyunların süreleri ve sonuçları oyunlar.txt dosyasına, tüm sistem giriş-çıkış işlemleri ise log.txt dosyasına zaman damgalı olarak kaydedilir.

Şifreli Temizleme: Skor ve log geçmişini arayüzden temizlemek için sistem şifresi (yönetici izni) gereklidir.

Dinamik Veri Okuma: Tüm dosya yolları sınıf değişkeni olarak ayarlanmıştır. Projenin ana kodlarına müdahale etmeden TXTDosyalar klasöründeki veriler değiştirilebilir.

-Kurulum ve Dosya Yapısı-
Projenin sorunsuz çalışabilmesi için dosyaların C:\ dizini altında belirtilen yapıda olması gerekmektedir:

C:\P2Oyun klasörünü oluşturun.

İçerisine Resimler ve TXTDosyalar adında iki alt klasör ekleyin.

Resimler klasörüne 1.jpg ile 11.jpg arasındaki oyun görsellerini yerleştirin.

TXTDosyalar klasörünün içine, her satırda en az 6 harfli bir kelime olacak şekilde kelimeler.txt dosyasını ekleyin.

Yerel Disk (C:) > P2Oyun
├── Resimler
│   ├── 1.jpg
│   ├── ...
│   └── 11.jpg
└── TXTDosyalar
    ├── kelimeler.txt
    ├── log.txt (Program tarafından oluşturulur)
    ├── oyunlar.txt (Program tarafından oluşturulur)
    └── sifre.txt (Program tarafından oluşturulur)
-Kullanım-
1 IDE üzerinden projeyi çalıştırın.
2 Giriş ekranında belirlediğiniz şifreyi girin.
3 Sol üst köşedeki "Menü" > "Oyuna Başla" yolunu izleyerek oyunu başlatın.
4 "Harf Tahmin Et" veya "Kelime Tahmin Et" metin kutularını kullanarak oynamaya başlayın.
-Ekran Görüntüleri-
<img width="337" height="155" alt="Ekran görüntüsü 2026-05-28 120930" src="https://github.com/user-attachments/assets/1ac1c668-7383-4d73-bd2a-c801a95a2b38" />
<img width="976" height="738" alt="Ekran görüntüsü 2026-05-28 120944" 
  src="https://github.com/user-attachments/assets/d9f55085-3fd9-4297-8d96-0fbc854fd8a1" />
  <img width="979" height="740" alt="Ekran görüntüsü 2026-05-28 121002" src="https://github.com/user-attachments/assets/d2961517-1354-4552-b5e7-4163d19ef5ed" />
<img width="972" height="737" alt="Ekran görüntüsü 2026-05-28 121009" src="https://github.com/user-attachments/assets/e432240d-2831-43c3-9dca-323b6ca430da" />
<img width="979" height="745" alt="Ekran görüntüsü 2026-05-28 121015" src="https://github.com/user-attachments/assets/5c6190dc-bcbc-4644-9d7d-4ba9479efec2" />

Geliştirici: Bekir Tuna Karamsal
