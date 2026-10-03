# Kana Lux · App para Android (APK)

Esta carpeta tiene todo lo necesario para que **GitHub** arme la app (archivo `KanaLux.apk`) sin instalar nada en su computadora.

## 1. Crear la cuenta y el repositorio (una sola vez)

1. Entre a **github.com** y cree una cuenta gratis (**Sign up**).
2. Arriba a la derecha toque **+** → **New repository**.
3. En *Repository name* escriba `kana-lux`. Déjelo en **Public**: aquí no van sus datos, solo el programa.
4. Toque **Create repository**.

## 2. Subir esta carpeta

1. En la página del repositorio toque el enlace **uploading an existing file**.
2. Abra esta carpeta en su computadora, seleccione **todo lo que hay adentro** (incluida la carpeta `.github`) y arrástrelo a la página. No arrastre la carpeta de afuera, sino su contenido.
3. Abajo toque **Commit changes**.

> Si en la pestaña **Actions** no aparece nada: toque **Add file → Create new file**, escriba como nombre `.github/workflows/build.yml`, pegue el contenido del archivo `build.yml.txt` y toque **Commit changes**.

## 3. Esperar a que se arme la app

1. Toque la pestaña **Actions**. Verá "Construir APK" trabajando (círculo amarillo).
2. Tarda unos **8 a 12 minutos**. Cuando termine verá un **check verde** ✓.

## 4. Instalar en el celular

1. En el celular, abra el navegador y entre a `github.com/SU-USUARIO/kana-lux/releases`.
2. Toque **KanaLux.apk** para descargarlo.
3. Ábralo. El celular le pedirá permiso para **instalar apps de fuentes desconocidas**: permítalo para el navegador.
4. Toque **Instalar**. Le aparece el ícono dorado de **Kana Lux**.
5. Al abrirla, acepte el permiso de **notificaciones** (para los avisos de las 6:00 a. m.).

## 5. Pasar sus datos actuales

1. Mándese al celular el archivo **Respaldo Kana Lux (datos actuales).json** (por WhatsApp o Google Drive). **No lo suba a GitHub.**
2. En la app: menú → **Respaldo** → **Elegir archivo de copia…** → elija ese archivo → **Sí, recuperar**.

## Importante

- Los datos quedan **guardados solo en el celular**. Haga una copia cada semana en **Respaldo → Hacer copia ahora** y guárdela en Google Drive o WhatsApp.
- Si desinstala la app o borra sus datos en Ajustes, se pierde todo lo que no tenga en una copia.
- **Actualizaciones:** cuando haya una versión nueva, reemplace el archivo `www/index.html` en GitHub (Add file → Upload files). GitHub arma la APK nueva sola; instálela encima de la anterior y **sus datos se conservan**.
- No borre la carpeta `keystore`: es la "firma" que permite actualizar la app sin perder los datos.
