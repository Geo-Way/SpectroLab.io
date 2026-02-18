# 🌍 GeoWay Spectral Lab / PyroLab

**Explorando ideas, construyendo soluciones geoespaciales**  
*Exploring ideas, building geospatial solutions*

Este repositorio contiene dos aplicaciones web interactivas diseñadas para la enseñanza de conceptos de teledetección y su aplicación en la gestión de incendios forestales. Ambas herramientas forman parte del **Laboratorio Geoespacial de GeoWay**, un espacio de innovación educativa con tecnologías geoespaciales.

This repository contains two interactive web applications designed for teaching remote sensing concepts and their application in wildfire management. Both tools are part of the **GeoWay Geospatial Lab**, an educational innovation space with geospatial technologies.

---

## 🛰️ Aplicaciones / Applications

### 1. EspectroLab – Laboratorio de Firmas Espectrales
Permite comprender el concepto de **firma espectral** a partir de imágenes de laboratorio (con filtro infrarrojo) o capturas con cámara. El estudiante puede asignar valores de reflectividad a cada banda (Azul, Verde, Rojo, NIR) de forma manual o automática, y visualizar la curva espectral resultante.

**Características:**
- Visualización de 4 bandas (RGB + NIR real o simulado).
- Sliders para ajuste manual (escala 0–10).
- Selección automática de valores haciendo clic en cualquier banda.
- Cursor sincronizado que muestra valores en tiempo real.
- Gráfica de firma espectral (con opción de superponer firma ideal de vegetación).
- Captura con cámara o carga de imagen propia.
- Popup informativo sobre la banda NIR (real o simulada).
- Interfaz responsive y multilingüe (ES, EN, DE).

### 2. PyroLab – NDVI y gestión de incendios
Enfocada en el **Índice de Vegetación de Diferencia Normalizada (NDVI)** y su aplicación como indicador de estrés hídrico y combustible vegetal.

**Características:**
- Visualización de bandas Rojo y NIR (reales o simuladas).
- Imagen NDVI en falso color (rojo–verde).
- Barra de leyenda con marcador dinámico del NDVI bajo el cursor.
- Sincronización de cursor entre las tres ventanas.
- Tablas interpretativas del NDVI en contexto de incendios.
- Video explicativo (opcional, desde carpeta `img/`).
- Captura con cámara o carga de imagen.
- Interfaz responsive y multilingüe (ES, EN, DE).

---

## 📸 Capturas de pantalla (opcional)

Puedes incluir aquí imágenes de la interfaz para mostrar el aspecto de las aplicaciones.

---

## 🛠️ Tecnologías utilizadas / Technologies used

- HTML5, CSS3 (Tailwind CSS)
- JavaScript (vanilla)
- Chart.js (para gráficas)
- Font Awesome (iconos)
- API de cámara (getUserMedia)
- Canvas API (procesamiento de píxeles)
- Favicons personalizados

---

## 📁 Estructura de carpetas / Folder structure
