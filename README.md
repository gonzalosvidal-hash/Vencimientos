# Mis Vencimientos

Proyecto inicial para empaquetar la interfaz aprobada como aplicación Android mediante Capacitor.

## Estructura

- `www/index.html`: interfaz aprobada, conservada como base visual.
- `package.json`: dependencias de Capacitor y notificaciones locales.
- `capacitor.config.json`: configuración Android.
- `.github/workflows/build-apk.yml`: construcción automática de APK de depuración.

## Estado

Esta es la base inicial. La lógica nativa de notificaciones diarias a las 09:00 se implementará y probará en el siguiente paso. No considerar esta primera APK como versión terminada.
