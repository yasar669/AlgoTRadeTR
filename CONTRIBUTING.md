# Katkıda Bulunma Kuralları

Bu açık kaynaklı projeye katkı sağlamak (indikatör eklemek, hata düzeltmek, yeni özellik geliştirmek) isteyen herkesin aşağıdaki kurallara mutlaka uyması gerekmektedir:

## 1. Dil Kullanımı
Proje dizininde her şey Türkçe yazılmalıdır. Hem kod içi isimlendirmelerde hem de yazışmalarda Türkçe karakterler (ş, ç, ğ, ü, ö, ı) kullanılabilir ve desteklenir.

## 2. Görsel Kurallar
Repoda ve kodların içerisinde kesinlikle görsel semboller (emojiler) **kullanılmayacaktır**. Sadelik ve profesyonellik ön plandadır.

## 3. Python Kod Standartları
Bütün Python kodları `ruff` aracı ile hem lint (kontrol) edilecek hem de formatlanacaktır. 
- Kullanılmayan kütüphane eklemeleri (imports) veya değişken tabirleri barındırılamaz.
- Her satır en fazla 88 karakter uzunluğunda olmalıdır.
- İçe aktarmalar (imports) isort kurallarına göre sıralanmış olmalıdır.
- Açıklama metinleri (docstring) `google` formatında yazılmalıdır.
- Tip belirteçleri (type hints) mümkün olan her fonksiyon ve değişkende zorunludur.

## 4. Geliştirme Akışı
- Yeni bir özellik veya indikatör eklenmeden önce GitHub üzerinden Talep (Issue) açılmalıdır.
- Çalışmalar ayrı bir dal (branch) üzerinde yapılmalı, işlemler bitince Birleştirme İsteği (Pull Request) oluşturulmalıdır.

## 5. Planlama ve Dokümantasyon
Projenin ana bileşenleri için hazırlanan planlar, proje kök dizinindeki kural ve şablonlara uygun bir şekilde md formatında kaleme alınmalıdır.
