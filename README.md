# 🗺️ JavaMaps - Konum Kaydetme ve Listeleme Uygulaması

Bu proje, kullanıcıların **Google Maps** üzerinden kendi konumlarını seçip kaydedebildiği, kaydedilen konumları listeleyip silebildiği bir **Android mobil uygulamasıdır**.  
Proje Android Studio kullanılarak **Java diliyle** geliştirilmiştir.

---

## 🚀 Özellikler

- 📍 Harita üzerinden uzun basarak konum ekleme  
- 💾 Eklenen konumları **Room Database** ile kalıcı olarak saklama  
- 🗒️ Kayıtlı konumları listeleme (RecyclerView)  
- 🗑️ Kayıtlı konumları silme  
- 🗺️ Google Maps API ile dinamik harita gösterimi  
- 🧭 Cihazın mevcut konumunu algılama  
- 🔄 Intent yapısı ile “yeni” veya “eski” konum seçimi yönetimi  

---

## 🛠️ Kullanılan Teknolojiler

| Kategori | Teknoloji |
|-----------|------------|
| **Dil** | Java |
| **IDE** | Android Studio |
| **UI** | XML, ViewBinding |
| **Veri Tabanı** | Room (SQLite) |
| **API** | Google Maps SDK |
| **Mimari** | Activity + Adapter Yapısı |
| **Bağımlılıklar** | RecyclerView, Material Components |

---

## 🧩 Uygulama Yapısı

app/
├── java/com/bahabakan/javamaps/
│ ├── adapter/
│ │ └── PlaceAdapter.java
│ ├── model/
│ │ └── Place.java
│ ├── view/
│ │ ├── MainActivity.java
│ │ └── MapsActivity.java
│ └── room/
│ ├── PlaceDao.java
│ └── PlaceDatabase.java
├── res/
│ ├── layout/
│ ├── values/
│ └── drawable/
└── AndroidManifest.xml
---
## ⚙️ Kurulum

1. Repoyu klonla:
   ```bash
   git clone https://github.com/BahaBakan/javaMaps.git
