# Vize Kampı – 2. Sınıf

Statik bir web sitesi. Derleme ya da sunucu gerekmez.

## Vercel'e yükleme
1. vercel.com → **Add New… → Project**.
2. Bu klasörü bir GitHub deposuna yükleyip içe aktar **ya da** `npx vercel` komutunu bu klasörde çalıştır.
3. Framework Preset: **Other**, Build Command: boş, Output Directory: `./` (kök).
4. Deploy. Bitti.

## Klasör yapısı
- `index.html`, `css/`, `js/app.js`: uygulama
- `data/courses.js`: ders listesi (ad, renk, Drive linki)
- `data/<ders>.js`: her dersin konu anlatımı, soruları, eşleştirme kartları
- `img/`: görseller

## Notlar
- Kullanıcı kayıtları (ad / misafir, ders ders eksikler) tarayıcının yerel depolamasında tutulur. Başka cihaza geçmek için “Eksiklerim → Dışa aktar / İçe aktar”.
- Sesli okuma tarayıcının yerleşik Türkçe sesini kullanır (Chrome, Edge, Safari).
- PDF: “Eksiklerim → PDF olarak al → Yazdır / PDF olarak kaydet”.
