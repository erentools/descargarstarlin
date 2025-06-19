# Starlink Web

Este es el sitio web oficial de LMTV Films, diseñado para ser completamente adaptable a móviles y visualmente atractivo. Proporciona acceso a tutoriales de instalación, descarga directa de la app y contacto con soporte por WhatsApp.

## 📁 Estructura del Proyecto

```
Starlink_Index_Completo_WhatsApp_FINAL/
│
├── index.html
└── media/
    ├── fondo.mp4           # Video de fondo para toda la página
    ├── intro.mp4           # Video superior reproducido automáticamente
    ├── video1.mp4          # Tutorial de instalación para Xiaomi
    ├── video2.mp4          # Tutorial de instalación para otros dispositivos
    ├── LMTV.apk            # Archivo APK de la aplicación para descarga
    └── whatsapp.png        # Ícono de WhatsApp para soporte
```

## 🛠 Instrucciones

### 1. Subida a un Hosting (como Hostinger)
1. Entra a tu panel de control y abre el **Administrador de Archivos**
2. Navega a la carpeta `public_html`
3. Sube y extrae el contenido del ZIP directamente allí
4. Asegúrate de que `index.html` esté en la raíz y los archivos de medios estén en la carpeta `media/`

### 2. Cambiar Número de WhatsApp
Abre el archivo `index.html` y busca esta línea:

```html
<a href="https://wa.me/573001112233" target="_blank">
```

Reemplaza `573001112233` por tu número en formato internacional (sin + ni espacios).

### 3. Subir tus propios videos
Coloca tus archivos de video (`fondo.mp4`, `intro.mp4`, `video1.mp4`, `video2.mp4`) dentro de la carpeta `media/`.

### 4. Subir tu APK
Reemplaza `Starlink.apk` dentro de `media/` por tu propio archivo `.apk`.

---

### 🌐 Vista previa

Una vez subido todo correctamente, accede desde tu navegador a tu dominio y deberías ver:
- Video de fondo animado
- Video inicial automático
- Dos tutoriales plegables
- Botón para descarga de la app
- Sección de contacto por WhatsApp

---

✅ Todo está optimizado para dispositivos móviles.
