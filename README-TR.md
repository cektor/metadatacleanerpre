# 🔒 Metadata Temizleyici Premium Edition

[![Android](https://img.shields.io/badge/Platform-Android-green.svg)](https://android.com)
[![API](https://img.shields.io/badge/API-24%2B-brightgreen.svg)](https://android-arsenal.com/api?level=24)
[![Kotlin](https://img.shields.io/badge/Kotlin-1.9.10-blue.svg)](https://kotlinlang.org)
[![License](https://img.shields.io/badge/License-Proprietary-red.svg)](LICENSE)

🇹🇷 Türkçe | [🇬🇧 English](README.md)

---

## 📱 Genel Bakış

**Metadata Temizleyici Premium Edition**, fotoğraflarınızdan, videolarınızdan ve PDF belgelerinizden gizli metadata bilgilerini kaldıran güçlü, gizlilik odaklı bir Android uygulamasıdır. Dosyalarınızı paylaşmadan önce GPS konumu, kamera bilgileri, zaman damgaları ve diğer hassas verileri kaldırarak gizliliğinizi koruyun.

### ✨ Temel Özellikler

- 🖼️ **Görsel Metadata Temizleme** - JPEG, PNG ve WebP görsellerden EXIF verilerini kaldırma
- 🎥 **Video Metadata Temizleme** - MP4, MKV ve AVI videolardan metadata silme
- 📄 **PDF Metadata Temizleme** - Yazar, oluşturma tarihi ve belge özelliklerini temizleme
- 🔒 **%100 Çevrimdışı** - İnternet bağlantısı gerektirmez, tüm işlemler yerel
- ⚡ **Toplu İşlem** - Birden fazla dosyayı aynı anda temizleme
- 📊 **Önce/Sonra Karşılaştırma** - Hangi metadata'nın kaldırıldığını görme
- 🚀 **Tek Dokunuşla Paylaşım** - Temizlenmiş dosyaları anında paylaşma
- ⚙️ **Gelişmiş Ayarlar** - Detaylı kontrol ile seçici metadata temizleme
- 🎨 **Modern Arayüz** - Material Design 3 ile güzel karanlık tema
- 🌐 **Türkçe Dil** - Tam Türkçe yerelleştirme

---

## 🎯 Neden Metadata Temizleyici?

### Problem

Çektiğiniz her fotoğraf gizli bilgiler içerir:
- 📍 **GPS Koordinatları** - Fotoğrafın çekildiği tam konum
- 📷 **Kamera Detayları** - Cihaz modeli, lens bilgisi, kamera ayarları
- 📅 **Zaman Damgaları** - Fotoğrafın oluşturulma ve değiştirilme zamanı
- 👤 **Yazar Bilgisi** - Kullanıcı adları ve yazılım detayları

Bu metadata, dosyaları çevrimiçi paylaştığınızda gizliliğinizi tehlikeye atabilir.

### Çözüm

Metadata Temizleyici, dosyalarınızın kalitesini korurken tüm bu hassas bilgileri kaldırır. Fotoğrafları, videoları ve belgeleri gizliliğinizin korunduğunu bilerek güvenle paylaşın.

---

## 🚀 Detaylı Özellikler

### 1. 📊 Metadata Karşılaştırma

Hangi metadata'nın kaldırıldığını gösteren detaylı önce/sonra karşılaştırması:

- Yan yana karşılaştırma görünümü
- Vurgulanan kaldırılmış öğeler
- Temizlenen şeyler hakkında tam şeffaflık
- Anlaşılması kolay arayüz

### 2. 🚀 Toplu Paylaşım

Dosyalarınızı temizledikten sonra anında paylaşın:

- Herhangi bir uygulamaya tek dokunuşla paylaşım
- Aynı anda birden fazla dosya
- Yerel Android paylaşım entegrasyonu
- Hızlı ve kullanışlı

### 3. ⚙️ Gelişmiş Ayarlar

Neyin kaldırılacağı üzerinde tam kontrol:

- **GPS Konumu** - Tüm konum verilerini kaldırma
- **Kamera Bilgisi** - Kamera modeli ve ayarlarını silme
- **Tarih/Saat** - Zaman damgalarını kaldırma
- **Yazar Bilgisi** - Yazar ve yazılım detaylarını temizleme
- **Orijinali Otomatik Sil** - İsteğe bağlı olarak orijinal dosyaları kaldırma
- **Özel Kayıt Konumu** - Temizlenmiş dosyaların nereye kaydedileceğini seçme

### 4. 🎨 Güzel Arayüz

Modern, sezgisel tasarım:

- Karanlık gradyan tema
- Akıcı animasyonlar
- Cyan vurgu rengi (#00D9FF)
- Material Design 3 bileşenleri
- Profesyonel açılış ekranı
- Duyarlı düzen

---

## 📸 Ekran Görüntüleri

### Ana Ekran
- Sürükle & bırak desteği ile dosya seçimi
- Tür göstergeleri ile gerçek zamanlı dosya listesi
- Temizleme sırasında ilerleme takibi
- Başarı bildirimleri

### Metadata Görüntüleyici
- Detaylı metadata gösterimi
- Kategorilere göre düzenlenmiş
- Okunması kolay format
- Metadata'sını görmek için herhangi bir dosyaya dokunun

### Ayarlar Paneli
- Bireysel metadata türlerini açma/kapama
- Her seçenek için görsel anahtarlar
- Tercihleri kaydetme
- Anında uygulama

### Karşılaştırma Görünümü
- Önce/sonra yan yana
- Değişiklikleri gösteren ok göstergeleri
- Kaldırılan öğeler için kırmızı vurgulama
- Tam denetim izi

---

## 🛠️ Teknik Detaylar

### Yapım Teknolojileri

- **Dil:** Kotlin 1.9.10
- **UI Framework:** Jetpack Compose
- **Mimari:** MVVM (Model-View-ViewModel)
- **Min SDK:** 24 (Android 7.0)
- **Target SDK:** 34 (Android 14)
- **Gradle:** 8.5

### Kütüphaneler & Bağımlılıklar

| Kütüphane | Versiyon | Amaç |
|-----------|----------|------|
| Jetpack Compose | 2023.10.01 | Modern UI araç seti |
| ExifInterface | 1.3.6 | Görsel metadata işleme |
| PdfBox-Android | 2.0.27.0 | PDF işleme |
| Kotlin Coroutines | 1.7.3 | Asenkron işlemler |
| Material 3 | 1.1.2 | Material Design bileşenleri |
| Core SplashScreen | 1.0.1 | Açılış ekranı API |

### Mimari

```
app/
├── data/
│   ├── model/          # Veri sınıfları
│   └── repository/     # Veri katmanı
├── domain/
│   ├── cleaner/        # Metadata kaldırma mantığı
│   └── reader/         # Metadata okuma mantığı
├── ui/
│   ├── screens/        # Compose UI ekranları
│   └── theme/          # Uygulama teması
└── viewmodel/          # ViewModels
```

### Desteklenen Dosya Türleri

#### Görseller
- JPEG (.jpg, .jpeg)
- PNG (.png)
- WebP (.webp)

#### Videolar
- MP4 (.mp4)
- MKV (.mkv)
- AVI (.avi)

#### Belgeler
- PDF (.pdf)

---

## 🔐 Gizlilik & Güvenlik

### Taahhüdümüz

- ✅ **Veri Toplama Yok** - Hiçbir kişisel bilgi toplamıyoruz
- ✅ **İnternet Gerektirmez** - %100 çevrimdışı çalışır
- ✅ **Analitik Yok** - Takip veya kullanım istatistiği yok
- ✅ **Reklam Yok** - Tamamen reklamsız deneyim
- ✅ **Üçüncü Taraf Hizmet Yok** - Harici entegrasyon yok
- ✅ **Yerel İşleme** - Tüm işlemler cihazınızda gerçekleşir
- ✅ **Açık Kaynak Kütüphaneler** - Güvenilir, denetlenmiş kütüphaneler kullanımı

### İzinler

Uygulama minimum izin gerektirir:

- **READ_MEDIA_IMAGES** - Seçtiğiniz görselleri okumak için
- **READ_MEDIA_VIDEO** - Seçtiğiniz videoları okumak için

Bu izinler yalnızca SİZİN açıkça seçtiğiniz dosyalara erişmek için kullanılır. Arka plan erişimi yok, otomatik tarama yok.

---

## 📦 Kurulum

### Gereksinimler

- Android 7.0 (API 24) veya üzeri
- ~20 MB depolama alanı
- İnternet bağlantısı gerektirmez

### İndirme

Yakında Google Play Store'da!

---

## 🎓 Nasıl Kullanılır

### Temel Kullanım

1. **Dosya Seçin** - "Dosyalara Gözat"a dokunun ve görseller, videolar veya PDF'ler seçin
2. **Seçimi İnceleyin** - Listede seçilen tüm dosyaları görün
3. **Metadata Temizleyin** - "Metadata Temizle" butonuna dokunun
4. **Sonuçları Görün** - Önce/sonra karşılaştırmasını görün
5. **Paylaşın** - Temizlenmiş dosyaları göndermek için "Paylaş"a dokunun

### Gelişmiş Kullanım

1. **Ayarları Açın** - Üst çubukta ayarlar simgesine dokunun
2. **Seçenekleri Özelleştirin** - Hangi metadata'nın kaldırılacağını seçin
3. **Tercihleri Kaydedin** - Ayarlarınız hatırlanır
4. **Dosyaları Temizleyin** - Özel ayarlarınızla dosyaları işleyin

### İpuçları

- 💡 Metadata'sını görmek için listedeki herhangi bir dosyaya dokunun
- 💡 Neyin kaldırıldığını doğrulamak için karşılaştırma görünümünü kullanın
- 💡 Depolama alanı tasarrufu için "Orijinali Otomatik Sil"i etkinleştirin
- 💡 Verimlilik için aynı anda birden fazla dosya işleyin

---

## 🏗️ Kaynak Koddan Derleme

### Ön Gereksinimler

- Android Studio Hedgehog veya daha yeni
- JDK 21
- Android SDK 34
- Gradle 8.5+

### Klonlama & Derleme

```bash
# Depoyu klonlayın
git clone https://github.com/yourusername/metadata-cleaner.git
cd metadata-cleaner

# Debug APK derleyin
./gradlew assembleDebug

# Release APK derleyin
./gradlew assembleRelease

# Bağlı cihaza yükleyin
./gradlew installDebug
```

### Proje Yapısı

```
MetaData/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/algyazilim/metadatacleaner/
│   │   │   ├── res/
│   │   │   └── AndroidManifest.xml
│   │   └── test/
│   └── build.gradle.kts
├── gradle/
├── build.gradle.kts
└── settings.gradle.kts
```

---

## 🤝 Katkıda Bulunma

Katkılarınızı bekliyoruz! Nasıl yardımcı olabilirsiniz:

### Katkı Yolları

- 🐛 Hata bildirin
- 💡 Yeni özellikler önerin
- 📝 Dokümantasyonu geliştirin
- 🌐 Çeviri ekleyin
- 🔧 Pull request gönderin

### Geliştirme Kuralları

1. Depoyu fork edin
2. Özellik dalı oluşturun (`git checkout -b feature/HarikaBirOzellik`)
3. Değişikliklerinizi commit edin (`git commit -m 'Harika bir özellik ekle'`)
4. Dalı push edin (`git push origin feature/HarikaBirOzellik`)
5. Pull Request açın

---

## 📄 Lisans

Bu proje, ALG Yazılım & Elektronik Inc. tarafından geliştirilen özel yazılımdır.

**Telif Hakkı © 2026 ALG Yazılım & Elektronik Inc. Tüm hakları saklıdır.**

---

## 👨💻 Geliştirici

**Fatih ÖNDER (CekToR)**

### Şirket

**ALG Yazılım & Elektronik Inc.**
- 🌐 Web Sitesi: [https://algyazilim.com](https://algyazilim.com)
- 📧 E-posta: info@algyazilim.com
- 📍 Konum: Türkiye

---

## 🙏 Teşekkürler

### Açık Kaynak Kütüphaneler

Aşağıdaki açık kaynak projelere özel teşekkürler:

- [ExifInterface](https://developer.android.com/jetpack/androidx/releases/exifinterface) - Apache License 2.0
- [PdfBox-Android](https://github.com/TomRoush/PdfBox-Android) - Apache License 2.0
- [Jetpack Compose](https://developer.android.com/jetpack/compose) - Apache License 2.0
- [Kotlin](https://kotlinlang.org/) - Apache License 2.0

---

## 📞 Destek

### Yardıma mı İhtiyacınız Var?

- 📧 E-posta: info@algyazilim.com
- 🌐 Web Sitesi: [https://algyazilim.com](https://algyazilim.com)
- 📖 Dokümantasyon: [Wiki](https://github.com/yourusername/metadata-cleaner/wiki)

### SSS

**S: Uygulama internet gerektirir mi?**  
C: Hayır, uygulama %100 çevrimdışı çalışır.

**S: Verilerim güvende mi?**  
C: Evet, tüm işlemler cihazınızda yerel olarak gerçekleşir. Hiçbir veri toplamıyor veya iletmiyoruz.

**S: Hangi dosya formatları destekleniyor?**  
C: Görseller (JPEG, PNG, WebP), Videolar (MP4, MKV, AVI) ve PDF belgeleri.

**S: Hangi metadata'nın kaldırılacağını seçebilir miyim?**  
C: Evet, neyin kaldırılacağını özelleştirmek için Gelişmiş Ayarları kullanın.

**S: Temizleme dosya kalitesini düşürür mü?**  
C: Hayır, yalnızca metadata kaldırılır. Gerçek görsel/video kalitesi değişmeden kalır.

---

## 🗺️ Yol Haritası

### Yaklaşan Özellikler

- [ ] Daha fazla görsel formatı desteği (HEIC, TIFF)
- [ ] Ses dosyası metadata temizleme (MP3, FLAC)
- [ ] Toplu yeniden adlandırma işlevi
- [ ] Bulut depolama entegrasyonu (isteğe bağlı)
- [ ] Zamanlanmış otomatik temizleme
- [ ] Widget desteği
- [ ] Karanlık/Aydınlık tema geçişi

---

## 📊 İstatistikler

![GitHub repo size](https://img.shields.io/github/repo-size/yourusername/metadata-cleaner)
![GitHub code size](https://img.shields.io/github/languages/code-size/yourusername/metadata-cleaner)
![Lines of code](https://img.shields.io/tokei/lines/github/yourusername/metadata-cleaner)

---

## ⭐ Yıldız Geçmişi

Bu projeyi faydalı buluyorsanız, lütfen yıldız vermeyi düşünün!

---

**Türkiye'de ❤️ ile yapıldı**

**Basit • Hızlı • Güvenli**
