Миникрафт Alpha — Android-проект

Это Android-оболочка WebView для вашего файла HTML. Исходная игра находится в:
app/src/main/assets/index.html

Как собрать APK:
1. Установите Android Studio на компьютер.
2. Распакуйте архив MinicraftAndroid.zip.
3. В Android Studio выберите Open и откройте папку MinicraftAndroid.
4. Дождитесь синхронизации Gradle и установки Android SDK Platform 35.
5. Выберите Build > Build Bundle(s) / APK(s) > Build APK(s).
6. APK будет создан в app/build/outputs/apk/debug/app-debug.apk.

Для сборки нужен интернет, чтобы Gradle скачал Android Gradle Plugin и Kotlin plugin.
При запуске игры нужен интернет для загрузки Three.js и шрифта из CDN, которые исходный HTML подключает по HTTPS.
Минимальная версия Android: 6.0 (API 23).
