# 🕌 Cevşen Listesi — Harmonie31

Association Harmonie31 bünyesinde okunan Cevşen-i Şerif için bâb dağılım ve takip uygulaması.

🔗 **Canlı site:** [kullaniciadin.github.io/cevsen-listesi](https://kullaniciadin.github.io/cevsen-listesi/)

---

## ✨ Özellikler

| | |
|---|---|
| 📖 | Cevşen-i Şerif'in 100 bâbı — herkes boş bir bâbı okuyup işaretleyebilir |
| 🕋 | Her bâbın Arapça metni, okunuşu ve meali tam ekranda, sekmeler halinde |
| ➡️ | "Okudum, sonraki bâba geç" — tek dokunuşla okunur ve otomatik ilerler |
| ✍️ | İsim sadece bir kere sorulur, tarayıcında hatırlanır |
| 🔠 | Yazı boyutu büyütme/küçültme (A− / A+) |
| 🎉 | 100 bâb tamamlanınca kutlama animasyonu |
| 🗂️ | Birden fazla Cevşen turu aynı anda tutulabilir, aralarında geçiş yapılabilir |
| 🏆 | "En Çok Katkı Sağlayanlar" — tüm turlar boyunca kim kaç bâb okumuş |
| 📱 | Tek tıkla WhatsApp'ta paylaşılabilir, QR kod üretilebilir |
| 🔓 | Yönetici modu ile tur adı/tarih/açıklama değiştirilebilir, tur silinebilir |

## 📚 İçerik Kaynağı

Bâbların Arapça metni, okunuşu ve meali; birçok bağımsız kaynakta ortak olarak yer alan
geleneksel bir Cevşen mealinden alınmıştır. Daha geniş/detaylı meal ve sesli tilâvet
isteyenler [herkul.org/cevsen](https://herkul.org/cevsen) üzerinden dinleyebilir.

## 🚀 Kullanım

Bu proje sadece **Harmonie31 üyeleri arasında** dahili kullanım içindir.

## 🛠️ Teknik

Statik HTML/JS + [Firebase Firestore](https://firebase.google.com/) (canlı senkronizasyon) ile çalışır, [GitHub Pages](https://pages.github.com/) üzerinde barındırılır. Arapça metinde **Şeyh Hamdullah Mushaf** hattı kullanılır.

Bu uygulama, [Hatim Listesi](https://github.com/sadikerd/hatim-listesi) uygulamasıyla aynı tasarım
sistemini paylaşır ama tamamen ayrı bir Firebase projesi ve veritabanı kullanır.

## 📋 Sürüm Geçmişi

| Sürüm | Değişiklik |
|---|---|
| 1.0 | İlk sürüm — 100 bâb, isim + PIN ile alma, yönetici modu |
| 2.0 | Akış sadeleştirildi: PIN/yardım/boşalt kaldırıldı, tam ekran okuma + tek dokunuşla ilerleme |
| 2.1 | Arapça/meal/okunuş her cümle ayrı satırda; yazı boyutu kontrolü; herkul.org fontu |
| 2.2 | "En Çok Katkı Sağlayanlar" tablosu eklendi |
| 2.3 | Telefon ana ekranına uygulama gibi eklenebiliyor (PWA); menüden Hatim Listesi'ne geçiş linki eklendi |

---
<p align="center"><i>Harmonie31 için sevgiyle hazırlandı 🌙</i></p>
