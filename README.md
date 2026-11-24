# PhoneUp (Android)

Игра лежит в app/src/main/assets/index.html и открывается в WebView.

## Как получить APK без Android Studio
1. Создай репозиторий на github.com и загрузи в него все файлы этой папки (включая .github).
2. Открой вкладку Actions, дождись зелёной галочки у "Build APK".
3. Внутри запуска скачай PhoneUp-apk, распакуй, установи app-debug.apk на телефон
   (разреши установку из неизвестных источников).

## Как собрать на компьютере
Нужны JDK 17 и Android SDK (или Android Studio): открой папку в Android Studio -> Build -> Build APK(s).
Либо: gradle assembleDebug  ->  app/build/outputs/apk/debug/app-debug.apk
