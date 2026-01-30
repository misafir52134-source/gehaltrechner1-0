# 📱 Lohnrechner 1.0 - PWA Kurulum Talimatları

## 🎯 Ne Yaptık?

HTML maaş hesaplayıcınızı **Progressive Web App (PWA)** haline getirdik. Artık telefonunuza gerçek bir uygulama gibi yükleyebilirsiniz!

## 📦 Dosyalar

- **lohnrechner.html** - Ana uygulama dosyası
- **manifest.json** - Uygulama ayarları
- **sw.js** - Service Worker (offline çalışma)
- **icon-192.png** - Küçük ikon
- **icon-512.png** - Büyük ikon

## 🚀 Telefona Nasıl Yüklenir?

### Yöntem 1: Web Sunucusu ile (Tavsiye Edilen)

1. **Dosyaları bir web sunucusuna yükleyin:**
   - GitHub Pages (ücretsiz)
   - Netlify (ücretsiz)
   - Vercel (ücretsiz)
   - Kendi web siteniz

2. **Telefonda açın:**
   - Chrome veya Safari ile siteyi açın
   - "Ana ekrana ekle" / "Install App" butonuna tıklayın
   - ✅ Uygulama yüklendi!

### Yöntem 2: GitHub Pages (En Kolay - Ücretsiz)

1. GitHub hesabı oluşturun (github.com)
2. Yeni repository oluşturun (isim: lohnrechner)
3. Tüm 5 dosyayı yükleyin
4. Settings → Pages → Branch: main → Save
5. 2 dakika bekleyin
6. https://KULLANICI_ADI.github.io/lohnrechner/lohnrechner.html
7. Telefonda bu linki açın ve "Ana ekrana ekle"

### Yöntem 3: Netlify (Çok Kolay - Ücretsiz)

1. netlify.com'a gidin
2. "Add new site" → "Deploy manually"
3. Tüm 5 dosyayı sürükle bırak
4. Link gelecek (örn: random-name.netlify.app)
5. Telefonda aç ve "Ana ekrana ekle"

## ✨ Yeni Özellikler

✅ **Offline Çalışma** - İnternet olmadan da kullanabilirsiniz
✅ **Veri Kaydetme** - Girdiğiniz veriler telefonda saklanır
✅ **Ana Ekranda İkon** - Gerçek uygulama gibi
✅ **Tam Ekran Mod** - Tarayıcı çubukları olmadan
✅ **Hızlı Açılış** - İkinci açılışta çok hızlı

## 📱 Android & iOS Uyumlu

- ✅ Chrome (Android)
- ✅ Safari (iPhone)
- ✅ Edge
- ✅ Samsung Internet

## 🔧 Test Etmek İçin (Bilgisayarda)

1. Chrome'da `lohnrechner.html` dosyasını açın
2. F12 → Application → Manifest kontrol edin
3. Lighthouse → PWA testi yapın

## 📞 Sorular?

Ayhan Karataş tarafından geliştirildi
Version 1.0 - Ocak 2026

---

## 🎓 Teknik Detaylar

- **Teknoloji:** Progressive Web App
- **Framework:** Vanilla JavaScript (framework yok)
- **Storage:** LocalStorage (veriler tarayıcıda)
- **Offline:** Service Worker ile cache
- **Responsive:** Mobil uyumlu tasarım

**Not:** HTTPS gerekli! GitHub Pages, Netlify, Vercel otomatik HTTPS sağlar.
