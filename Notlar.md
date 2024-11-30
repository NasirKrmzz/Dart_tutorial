pubspec.yaml, Flutter ve Dart projelerinin yapılandırma dosyasıdır.
1. Temel Bilgiler
name: my_app
description: A new Flutter project
version: 1.0.0+1
2. Bağımlılıklar
Kodu kopyala
dependencies:
  flutter:
    sdk: flutter
  http: ^1.1.0  # Paket adı ve sürüm numarası
  provider: ^6.0.0
3. Flutter Spesifik Ayarlar
flutter:
  assets:
    - assets/images/logo.png
    - assets/data/sample.json
  fonts:
    - family: Roboto
      fonts:
        - asset: fonts/Roboto-Regular.ttf
flutter pub get :
* Pubspec.yaml dosyasında tanımlanan paketlerin ve sürüm bilgilerine göre ilgili kütüphanelerin Pub (Dart''ın paket yöneticisi) depolarından indirilmesini sağlar.
* Projeye eklenen yeni kütüphanelerin kullanılabilir hale gelmesini sağlar
