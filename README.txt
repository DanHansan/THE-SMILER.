THE SMILER - Proyecto Android

Este proyecto envuelve el prototipo 3D en una aplicación Android de pantalla completa.

Para generar el APK:
1. Instala Android Studio en una computadora.
2. Abre Android Studio y selecciona "Open".
3. Elige la carpeta THE_SMILER_Android (la carpeta que contiene settings.gradle).
4. Espera a que Gradle sincronice y acepta instalar el Android SDK 35 si lo solicita.
5. Ve a Build > Build Bundle(s) / APK(s) > Build APK(s).
6. El APK de prueba se generará en:
   app/build/outputs/apk/debug/app-debug.apk

Importante:
- El juego se carga desde app/src/main/assets/index.html.
- El prototipo actual usa Three.js desde un CDN, por lo que necesita internet al iniciar.
- Este paquete es el proyecto Android listo para compilar, NO un APK ya compilado.
- Para distribuirlo públicamente harían falta pruebas en dispositivos, optimización y firma de publicación.
