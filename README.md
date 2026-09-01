# 📥 Generador Amigable yt-dlp

Una interfaz web ligera, intuitiva y 100% *front-end* para construir comandos complejos de `yt-dlp` en Windows sin complicaciones.

Permite configurar descargas de video, audio y fraccionamiento por tramos en cuestión de segundos, sin necesidad de recordar parámetros de consola ni enviar datos a servidores externos.

---

## 🚀 Características

* **Interfaz Limpia y Oscura:** Diseño moderno, responsivo y adaptado para un trabajo rápido.
* **Pegado Directo:** Botón para pegar la URL del portapapeles con un solo clic.
* **Descarga Completa o por Tramos:** Opción para fraccionar videos largos en partes personalizadas (ideal para conferencias, cursos o podcasts).
* **Formatos y Calidades Ajustables:** Selección simple entre MP4, MKV, WEBM, MP3 y M4A, con ajuste de resolución (4K, 1080p, 720p, etc.).
* **Ruta Predeterminada Práctica:** Salida configurada directamente hacia la carpeta `%USERPROFILE%\Downloads` usando el título original del video.
* **Privacidad Total:** Funciona de forma totalmente local en el navegador (sin backend ni rastreo).

---

## 📌 Requisitos Previos (Windows 11)

Para ejecutar los comandos generados en tu consola (CMD o PowerShell), necesitas tener instalados **yt-dlp** y **FFmpeg**.

### Instalación Rápida con `winget` (Recomendado)

Abre PowerShell o CMD y ejecuta:

```powershell
winget install yt-dlp.yt-dlp
winget install Gyan.FFmpeg# descargaVideo
