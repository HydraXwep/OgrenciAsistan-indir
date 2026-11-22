# Öğrenci Asistanı — İndir

Okul hayatını tek uygulamada toplayan, yapay zekâ destekli öğrenci asistanı.
**Bağımsız bir öğrenci projesidir, resmî üniversite uygulaması değildir.** Bu sayfa test sürümünü denemek isteyenler içindir.

Güncel sürüm: Windows ve Mac **1.0.10**, Android **1.0.9** (1.0.10 yakında; uygulama içinden kendiliğinden gelecek).

| Platform | İndir | SHA-256 |
| --- | --- | --- |
| Windows 10/11 | [OgrenciAsistan-Kurulum-1.0.10.exe](https://wwpyhlwxasjsnrjjvbdf.supabase.co/storage/v1/object/public/releases/OgrenciAsistan-Kurulum-1.0.10.exe) | `732e0392c3b74c746c8b5db54e6e8d01704dccfce66b3452474f90a189b4a2c3` |
| Android | [OgrenciAsistan-android-1.0.9.apk](https://wwpyhlwxasjsnrjjvbdf.supabase.co/storage/v1/object/public/releases/OgrenciAsistan-android-1.0.9.apk) | `2929d05ffffb341839e12bfb40ca1b790fd7b75f626fce0d98b3fca947753c69` |
| macOS 12+ (deneme) | [OgrenciAsistan-mac-1.0.10.zip](https://github.com/HydraXwep/OgrenciAsistan-indir/releases/download/v1.0.10/OgrenciAsistan-mac-1.0.10.zip) | `5dfaee0d78441b3770f54f3de11f752393d9d67f9b179acd2e7e48db68c42041` |

**1.0.10'da yeni:** uygulamanın adı Mac menüsünde ve pencerede "Öğrenci Asistanı", pencere ilk açılışta geniş;
ana sayfada okunmamış mesaj sayısı; derslerde kredi yazıyla. 1.0.9 kurulu Mac'lerde yeni zip'i indirip uygulamayı
eskisinin üstüne koy.

## Kurulum

**Windows**
1. `.exe` dosyasını indirip çift tıkla.
2. "Windows bilgisayarınızı korudu" uyarısı çıkarsa **Ek bilgi → Yine de çalıştır** de (kurulum dosyası henüz imzalı değil).
3. Kurulum yönetici izni istemez; bitince uygulama açılır. Yeni sürümler uygulamanın içinden gelir.

**Android**
1. `.apk` dosyasını telefondan indirip aç.
2. "Bilinmeyen uygulamaları yükle" izni sorarsa tarayıcına izin ver, sonra **Yükle** de.
3. Yeni sürümler uygulamanın içinden gelir.

**macOS** (ilk Mac sürümü, deneme aşamasında)
1. `.zip` dosyasını indir, çift tıkla; çıkan **ogrenci_asistan** uygulamasını **Uygulamalar** klasörüne sürükle.
2. İlk açılışta "açılamıyor / doğrulanamadı" uyarısı çıkar (uygulama Apple tarafından imzalı değil). **Bitti** de, sonra
   **Sistem Ayarları → Gizlilik ve Güvenlik**'e git, en altta **Yine de Aç**'a tıkla ve Mac şifrenle onayla.
3. "Öğrenci Asistanı, Anahtar Zinciri'ndeki bilgilerinizi kullanmak istiyor" diye sorarsa Mac şifreni yaz ve
   **Her Zaman İzin Ver** de ("Beni hatırla" bunun için gerekli).
4. Mac'te güncellemeler uygulamanın içinden gelmez; yeni sürümü bu sayfadan indirip eskisinin üstüne koy.

## Hesap

- Uygulamayı açınca **Kayıt ol** sekmesinden hesap aç. GNO hesaplayıcı ve temalar hesapsız da çalışır.
- Mesajlaşma gibi üyelik isteyen bölümler için **üyelik anahtarını geliştiriciden iste**, sonra uygulamada gir.
- Bir sorun görürsen uygulamada **Ayarlar → Hata bildir**'den yaz.

İndirdiğin dosyanın değiştirilmediğini kontrol etmek için SHA-256 değerini tablodakiyle karşılaştırabilirsin
(Mac/Linux: `shasum -a 256 dosya`, Windows: `certutil -hashfile dosya SHA256`).
