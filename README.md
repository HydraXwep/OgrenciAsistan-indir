# Öğrenci Asistanı — İndir

Okul hayatını tek uygulamada toplayan, yapay zekâ destekli öğrenci asistanı.
**Bağımsız bir öğrenci projesidir, resmî üniversite uygulaması değildir.** Bu sayfa test sürümünü denemek isteyenler içindir.

Güncel sürüm: **1.0.9**

| Platform | İndir | SHA-256 |
| --- | --- | --- |
| Windows 10/11 | [OgrenciAsistan-Kurulum-1.0.9.exe](https://wwpyhlwxasjsnrjjvbdf.supabase.co/storage/v1/object/public/releases/OgrenciAsistan-Kurulum-1.0.9.exe) | `9e128e36692188ca7a7685ebd24d41e9d49912f381fbb73c26a3ad3e34573cf1` |
| Android | [OgrenciAsistan-android-1.0.9.apk](https://wwpyhlwxasjsnrjjvbdf.supabase.co/storage/v1/object/public/releases/OgrenciAsistan-android-1.0.9.apk) | `2929d05ffffb341839e12bfb40ca1b790fd7b75f626fce0d98b3fca947753c69` |
| macOS 12+ (deneme) | [OgrenciAsistan-mac-1.0.9.zip](https://github.com/HydraXwep/OgrenciAsistan-indir/releases/latest/download/OgrenciAsistan-mac-1.0.9.zip) | `cdc5fd2349e9314840bdc68ae2b3202b6739bf9870d6afaee4172f9834bf4b2a` |

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
