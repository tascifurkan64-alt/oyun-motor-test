# Oyun Motoru — Test Derlemesi

Bu depo bir oyun DEĞİL. Tek amacı: Fener Adası / Mercan Koyu / Liman Meydanı'nın ortak motorunda kullanacağımız mimarinin (Capacitor + gerçek native AdMob reklamları) gerçekten çalıştığını, GitHub Actions üzerinden derlenip telefona kurularak doğrulanmasıdır.

## Bu depoyu nasıl kullanacaksın

1. Bu dosyaları/klasörleri GitHub'a yükleyip commit ettikten birkaç dakika sonra, deponun üstündeki **"Actions"** sekmesine gir.
2. "Android Test Build" adlı çalışmanın (workflow run) yeşil tikle bittiğini gör (birkaç dakika sürebilir).
3. O çalışmaya tıkla, en altta **"Artifacts"** bölümünde **oyun-motor-test-debug-apk** dosyasını indir (bu bir .zip, içinde app-debug.apk var).
4. app-debug.apk dosyasını telefonuna aktar (kendine e-posta/Drive ile gönderebilirsin) ve kur (Android "bilinmeyen kaynaklardan yükleme"ye bir kereliğine izin vermeni isteyebilir).
5. Uygulamayı aç, iki butondan birine bas — ekranda "Geçiş reklamı gösterildi ✅" ya da benzeri bir test reklamı görürsen, mimari gerçekten çalışıyor demektir.

Burada kullanılan reklam kimlikleri Google'ın herkese açık TEST kimlikleri — gerçek hesapla ilgisi yok, gerçek paraya dönüşmez. Bu adım geçtikten sonra asıl oyunun (Fener Adası) gerçek içeriğine geçeceğiz.
