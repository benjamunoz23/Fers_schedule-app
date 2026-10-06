# Fer's Magic Schedule — APK de Android

## Obtener el APK (sin instalar nada en tu PC)
1. Crea una cuenta en github.com y un repositorio nuevo (privado está bien).
2. Sube TODO el contenido de esta carpeta (incluida `.github`, `www`, `assets`, `debug.keystore`).
3. Ve a la pestaña **Actions** → "Construir APK" → espera ~5 min a que se ponga verde
   (si no parte solo: *Run workflow*).
4. Entra a la ejecución → abajo, en **Artifacts**, descarga `fers-magic-apk` (zip con `app-debug.apk`).
5. Pasa el APK al celular de Fer (WhatsApp/Drive/cable) y ábrelo.
   Android pedirá permitir "instalar apps de orígenes desconocidos".

## Primera vez en el celular
- Pestaña Recordatorios → **Activar notificaciones** → Permitir.
- Toca **Probar notificación (10 s)**, cierra la app y confirma que llega.
- Ajustes del celular → Apps → Fer's Magic → Batería → "Sin restricciones"
  (importante en Xiaomi, Samsung, Huawei, Oppo para que no mate los avisos).

## Actualizar la app
Cambia `www/index.html`, súbelo a GitHub y descarga el nuevo APK. Se instala encima sin perder
datos porque la firma (`debug.keystore`) es siempre la misma. No la borres.

## Ojo con el progreso
La app instalada guarda sus datos aparte de la versión web. Para pasar el progreso de la versión
web al APK: Generar código de backup en la web → pegarlo y Restaurar en el APK.
