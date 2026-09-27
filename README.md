# Civciv İngilizce

6-8 yaş çocuklar için görsel ve sesli İngilizce öğrenme uygulaması.

## Bu repo nasıl çalışır?

Bu proje [Capacitor](https://capacitorjs.com) kullanarak `www/index.html` içindeki
web uygulamasını bir Android uygulamasına çevirir. Native Android projesi bu
repoda **tutulmaz** — her build'de GitHub Actions tarafından sıfırdan üretilir.

## APK nasıl indirilir?

1. Bu repoya her `main` dalına push yaptığında (veya elle "Run workflow" ile
   tetiklediğinde), **Actions** sekmesindeki **"Build Debug APK"** iş akışı
   otomatik çalışır.
2. İş akışı bitince, o çalıştırmanın sayfasında **Artifacts** bölümünden
   `civciv-ingilizce-debug-apk` dosyasını indirebilirsin.
3. İndirilen `.zip` içinden çıkan `app-debug.apk` dosyasını Android telefona
   aktarıp kurabilirsin (telefonda "bilinmeyen kaynaklardan yükleme" izni
   gerekebilir).

## Play Store için imzalı AAB

Google Play'e yüklenecek imzalı `.aab` dosyası için bir imzalama anahtarı
(keystore) ve GitHub Secrets kurulumu gerekiyor — bu, bir sonraki adım.
