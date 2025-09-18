# 🎧 AudiobookGenerator

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)  
[![Status](https://img.shields.io/badge/Status-In%20Development-orange.svg)](#)  
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)  

Proyecto en Python para generar audiolibros a partir de archivos PDF.

---

## 📝 Descripción General

**AudiobookGenerator** es una herramienta CLI (línea de comando) desarrollada en Python que convierte archivos PDF en audios, utilizando síntesis de voz. Ideal para quienes desean escuchar textos en lugar de leerlos, ya sea por comodidad, accesibilidad o multitarea.

---

## ⚙️ Características Principales

- Conversión de PDF a formato de audio (por ejemplo MP3 o WAV).  
- Manejo de PDFs con texto claro (OCR no incluido por defecto).  
- Posibilidad de seleccionar voz/TTS si está soportado por la librería.  
- Uso sencillo desde la terminal / consola.  
- Sin dependencias de servidor; funciona localmente.

---

## 🛠 Tecnologías Utilizadas

- Python 3.8 o superior  
- Librerías de texto a voz (TTS) como `pyttsx3` u otra similar (dependiendo de implementación)  
- Librerías para manejo de PDF, por ejemplo `PyPDF2`, `pdfplumber` u otras  

---

## 🚀 Instalación

  ```bash
  git clone https://github.com/nik01101/AudiobookGenerator.git
  cd AudiobookGenerator
  pip install -r requirements.txt
  ```
  ## ▶️ Uso
  ```bash
  Copiar código
  python main.py ruta/al/archivo.pdf --output ruta/salida.mp3
  Reemplaza ruta/al/archivo.pdf por el PDF que quieres convertir.
  ```

--output es opcional si quieres definir dónde guardar el audio resultante.

## 📂 Estructura del Proyecto
  ```bash
  AudiobookGenerator/
  ├── main.py               # Script principal que ejecuta la conversión
  ├── requirements.txt      # Lista de dependencias necesarias
  ├── README.md             # Esta documentación
  └── .idea/                # Configuración del IDE (opcional, ignorar)
  ```
## 📦 Dependencias (requirements.txt)
```bash
pyttsx3
PyPDF2
(puedes ajustar esta lista según las librerías que efectivamente estás usando, por ejemplo añadir pdfplumber, gTTS, etc.)
```

## 🤝 Contribuciones
Contribuciones bienvenidas. Algunas ideas:

Agregar soporte para OCR para PDFs escaneados.

Permitir elección de voz o idioma si la librería lo soporta.

Añadir logging o progreso de conversión.

Soporte para múltiples formatos de salida de audio.

Cómo contribuir:

Haz un fork del repositorio.

Crea una rama nueva: git checkout -b feature/tu-mejora.

Haz tus cambios, prueba localmente.

Haz commit: git commit -m "Agrega nueva funcionalidad".

Push y envía un Pull Request.

## 📜 Licencia
Este proyecto está bajo la Licencia MIT.
Consulta el archivo LICENSE para más detalles.

## 👨‍💻 Autor
Desarrollado por Nikcolas Canessa 💻
