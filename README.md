<p align="center">
  <img src="icons/icon-128.png" width="96" alt="CoverLabel logo">
</p>

<h1 align="center">CoverLabel</h1>

<p align="center">
  Imprime etiquetas y portadas de colecciones al tamaño exacto — videojuegos, CDs, DVDs, libros y más.
</p>

<p align="center">
  <a href="https://github.com/JFSAINTS/coverlabel/releases/latest"><img src="https://img.shields.io/github/v/release/JFSAINTS/coverlabel?label=Descargar&color=7c6af7" alt="Última versión"></a>
  <a href="https://coverlabel.netlify.app"><img src="https://img.shields.io/badge/Web%20App-coverlabel.netlify.app-00C7B7?logo=netlify" alt="Netlify"></a>
  <img src="https://img.shields.io/badge/Plataforma-Windows%20%7C%20Android%20%7C%20Web-blue" alt="Plataformas">
  <img src="https://img.shields.io/badge/Sin%20instalaci%C3%B3n-Portátil-22c55e" alt="Portátil">
</p>

---

## ¿Qué es CoverLabel?

**CoverLabel** es una herramienta gratuita para imprimir portadas y etiquetas de colecciones al tamaño exacto, directamente desde el navegador o como app de escritorio. Diseñada para coleccionistas que quieren reproducir cajas, inlays, spines o carátulas con precisión milimétrica.

Funciona **sin servidor**, **sin cuenta** y **sin conexión** una vez cargada.

---

## Casos de uso

| Colección | Ejemplo |
|-----------|---------|
| 🎮 Videojuegos retro | Carátulas NES, SNES, Mega Drive, Neo Geo AES/MVS, Game Boy |
| 💿 Música | Portadas de CD, inlays interiores, carátulas de vinilo |
| 📀 Cine y series | Cubiertas de DVD, Blu-ray, VHS |
| 📚 Libros y cómics | Sobrecubiertas, lomos, marcapáginas |
| 🎲 Juegos de mesa | Cartas, tokens, reglamentos a medida |
| 🏷️ Etiquetas | Spine labels, price tags, cualquier etiqueta personalizada |

---

## Características

### Modos de impresión

- **Cuadrícula automática** — ajusta múltiples copias de la imagen por página, aprovechando al máximo el papel
- **Modo División** — divide portadas grandes (p. ej. Neo Geo AES 184×267 mm) en varios trozos para imprimir en A4 y ensamblarlas
- **Modo Póster** — imprime a tamaño A3 completo, o distribuye la imagen en 4 hojas A4 para montar un póster

### Tamaños de papel
A4 · A5 · A3 · Carta (US Letter) · con detección automática según las dimensiones introducidas

### Exportación
- **PDF** listo para imprimir (máxima calidad, vectorial)
- **PNG** para retoque o compartir

### Configuración de imagen
- Márgenes ajustables (0–30 mm)
- Escala libre o encaje automático
- Rotación 0–360°
- Opción para invertir imagen en espejo

### PWA / Sin conexión
Funciona completamente offline después de la primera carga. Instálala desde el navegador como app.

---

## Descargas

| Plataforma | Archivo | Notas |
|------------|---------|-------|
| **Windows** (instalador) | [CoverLabel Setup.exe](https://github.com/JFSAINTS/coverlabel/releases/latest) | Con acceso directo en escritorio |
| **Windows** (portátil) | [CoverLabel.exe](https://github.com/JFSAINTS/coverlabel/releases/latest) | Sin instalación, ejecutar directo |
| **Android** | [CoverLabel.apk](https://github.com/JFSAINTS/coverlabel/releases/latest) | Requiere permitir fuentes desconocidas |
| **Web / PWA** | [Abrir en el navegador](https://coverlabel.netlify.app) | Funciona en cualquier dispositivo |

---

## Cómo usar

1. **Abre** la app (web, .exe o APK)
2. **Arrastra** una imagen o usa el botón para cargarla
3. **Introduce** el ancho y alto en milímetros de tu portada/etiqueta
4. **Ajusta** márgenes, escala y rotación si es necesario
5. **Exporta** como PDF o PNG, o imprime directamente

### Modo División (portadas grandes)
Si la portada no cabe en una hoja A4, activa **División** → el sistema calcula automáticamente en cuántas partes dividir la imagen y genera una página por trozo con guías de ensamblaje.

### Modo Póster
Activa **Póster** → elige entre imprimir a **A3** (una hoja grande) o distribuir la imagen en **4 hojas A4** para montar un póster de 420×594 mm.

---

## Tecnología

- HTML + CSS + JavaScript puro (sin frameworks)
- [jsPDF](https://github.com/parallax/jsPDF) para exportación PDF
- [Electron](https://www.electronjs.org/) para la app de escritorio Windows
- [Capacitor](https://capacitorjs.com/) para la app Android
- PWA con Service Worker para uso offline

---

## Privacidad

Toda la app corre **100% en local**. Las imágenes que cargas no se envían a ningún servidor. No hay analíticas ni rastreo.

---

## Licencia

MIT — libre para uso personal y comercial.
