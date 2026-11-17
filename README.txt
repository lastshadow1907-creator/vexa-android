VEXA ANDROID APK - KURULUM

Bu Android Studio/Gradle projesi Vexa'nin canli sitesini WebView icinde acar.

GITHUB UZERINDEN APK URETME:
1. Bu klasordeki dosyalari (app, .github, build.gradle.kts, settings.gradle.kts, gradle.properties) AYNI Android GitHub deposunun kokune yukleyin.
2. GitHub > Actions > Vexa Android APK > Run workflow.
3. Islem basarili olunca calismanin altindaki Artifacts > Vexa-Android-APK dosyasini indirin.
4. ZIP icindeki app-debug.apk dosyasini Android telefona kurun.

DIKKAT:
- Bu bir DEBUG APK'dir. Ilk test ve dogrudan dagitim icin; Play Store yayini icin release signing gerekir.
- Web arayuzu Vercel'de yeni surum yayina alindiginda uygulamada da degisir.
- Web push bildirimleri, arka plan cagrilari ve bazi OAuth akislarinin Android WebView'da calisacagi garanti edilmez.
- Gercek cihazda kamera, mikrofon, mesaj, dosya secme, oturum ve bildirim testleri yapin.
- GitHub Actions derlemesi burada calistirilmadi; APK dosyasi degil, APK uretecek proje sunuluyor.
