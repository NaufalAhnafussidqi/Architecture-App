# Architecture App

Architecture App adalah aplikasi Android yang menunjukkan praktik terbaik dalam pengembangan aplikasi Android menggunakan Clean Architecture. Aplikasi ini dirancang untuk menjadi referensi bagi developer yang ingin mempelajari pola arsitektur yang terstruktur, testable, dan maintainable.

## Instalasi

1. Clone repository ini
   ```bash
   git clone https://github.com/NaufalAhnafussidqi/Architecture-App.git
   ```
2. Buka project di Android Studio
3. Sinkronkan Gradle dan build project
4. Jalankan aplikasi pada emulator atau perangkat fisik

## Struktur Project (Clean Architecture)

```
Architecture-App/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/naufal/architecture/
│   │   │   │   ├── presentation/    # UI Layer (Jetpack Compose)
│   │   │   │   │   ├── components/
│   │   │   │   │   ├── screens/
│   │   │   │   │   └── viewmodels/
│   │   │   │   ├── domain/        # Business Logic Layer
│   │   │   │   │   ├── model/
│   │   │   │   │   ├── repository/
│   │   │   │   │   └── usecase/
│   │   │   │   └── data/          # Data Layer
│   │   │   │       ├── local/
│   │   │   │       │   ├── dao/
│   │   │   │       │   └── database/
│   │   │   │       ├── remote/
│   │   │   │       │   ├── api/
│   │   │   │       │   └── model/
│   │   │   │       └── repository/
│   │   │   ├── res/
│   │   │   └── AndroidManifest.xml
│   │   └── test/                  # Unit Tests
│   └── build.gradle.kts
├── gradle/
├── build.gradle.kts
├── settings.gradle.kts
└── gradle.properties
```

## Kontak

- **Author:** Naufal Ahnafus Sidqi
- **GitHub:** [@NaufalAhnafussidqi](https://github.com/NaufalAhnafussidqi)
