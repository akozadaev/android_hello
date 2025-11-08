## android_hello

Учебный Android-проект, созданный на стандартном шаблоне Android Studio. Цель — продемонстрировать базовую структуру приложения на Java с одной activity и макетом `ConstraintLayout`.

### Стек
- Java 8, XML
- Android SDK: `compileSdk 34`, `minSdk 26`, `targetSdk 34`
- Android Gradle Plugin 7.3.1, Gradle 8.5
- Зависимости: `androidx.appcompat`, `com.google.android.material`, `androidx.constraintlayout`

### Структура
- `app/src/main/java/com/akozadaev/android_hello/MainActivity.java` — единственная activity
- `app/src/main/res/layout/activity_main.xml` — разметка экрана
- `app/src/main/res/values` — ресурсы приложения

### Сборка и запуск
```bash
./gradlew assembleDebug
```

Для запуска используйте Android Studio или команду:
```bash
./gradlew installDebug
```
на подключённом устройстве или эмуляторе с Android 8.0+.

### Тесты
```bash
./gradlew test
./gradlew connectedAndroidTest
```

### Лицензия
Проект распространяется по лицензии MIT. См. `LICENSE`.

