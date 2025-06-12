# 📚 Basit Kütüphane Otomasyonu (C)

Bu proje, C programlama diliyle geliştirilmiş basit bir **kütüphane otomasyon sistemidir**. Komut satırı arayüzüyle çalışan bu uygulama, kitap ve yazar kayıtlarını `.txt` dosyasında tutarak, temel CRUD (Create, Read, Update, Delete) işlemlerini gerçekleştirebilir.

## 🚀 Özellikler

- 📘 Kitap ekleme, listeleme, silme, güncelleme
- 👤 Yazar bilgileri ile eşleştirme
- 🔍 Kitap arama ve yazar bazlı filtreleme
- 🧾 Dosya tabanlı veri saklama (`KitapKayit.txt`)
- 📎 Basit kullanıcı arayüzü (konsol tabanlı)

## 🛠️ Derleme Talimatları

```bash
gcc kutuphane.c -o kutuphane.exe
```

▶️ Kullanım
Program çalıştırıldığında aşağıdaki menü gelir:
Kutuphane otomasyonuna Hosgeldiniz!
1- Kayit ekleme islemleri
2- Kayit silme islemleri
3- Kayit guncelleme islemleri
4- Kayit listeleme islemleri
5- Kayit arama islemleri
6- Yazar bilgileri arama
7- Cikis


İlgili işlemler klavyeden rakam girilerek yapılır.

📂 Veri Formatı
Veriler KitapKayit.txt dosyasında şu şekilde tutulur:
<kitap_kodu> <kitap_adi> <yazar_adi> <yazar_soyadi> <yazar_kodu> <sayfa_sayisi> <basim_yili> <uygun_kitap_durum>

uygun_kitap_durum: 1 = Mevcut, 0 = Silinmiş


