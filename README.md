# DogExpress Games

Modern ve teknolojik tasarımlı, çevrimdışı Android deneme sürümü.
Üç örnek oyun, kategori filtresi, oyun adımları ve cihazda saklanan ilerleme.
Android 8.0 veya üzeri gerekir.

## GitHub'da derleme

1. Bu paketin içindeki dosyaları GitHub deponun köküne ekle. Gizli `.github` klasörünü de ekle.
2. **Actions → Android APK** bölümünden son çalıştırmayı aç. İstersen **Run workflow** ile yeniden çalıştır.
3. Başarılı koşunun **Artifacts** bölümünden **dogexpress-games-test** paketini indir.
4. Paketi aç ve `app-debug.apk` dosyasını Android cihazında dene.

Bu iş akışı Android Studio gerektirmez ve Google Play'e yükleme yapmaz.
Her koşudaki deneme anahtarı değişebileceğinden, bir test APK'sı önceki test
kurulumunun üzerine yüklenemeyebilir. Eski kurulumu kaldırmak yerel ilerlemeyi siler.
