# Estación Meteorológica IoT

Este proyecto ha sido desarrollado como parte de la asignatura *Tecnologías Emergentes* y tiene como objetivo simular un sistema de monitorización ambiental conectado con la plataforma [ThingSpeak](https://thingspeak.com), utilizando Python y un entorno interactivo con interfaz gráfica.

## Autor

**Mara Olmo Segovia**  
---

## Funcionalidades

La aplicación permite:

- Introducir manualmente datos ambientales:
  - CO₂ (ppm)
  - Ruido (dB)
  - Luminosidad (lux)
  - Presión atmosférica (hPa)
  - Velocidad del viento (km/h)
- Enviar los datos al canal de ThingSpeak mediante su API REST.
- Leer el último dato almacenado en el canal.
- Consultar el historial de los últimos cinco registros.
- Visualizar gráficas actualizadas en tiempo real directamente desde ThingSpeak.

---

## Tecnologías utilizadas

- **Python** – Lenguaje de desarrollo.
- **Jupyter Notebook** – Entorno de programación interactiva.
- **ThingSpeak API** – Almacenamiento y visualización de datos IoT.
- **ipywidgets** – Creación de interfaces gráficas en Jupyter.
- **requests** – Comunicación HTTP con la API de ThingSpeak.
- **pandas** – Visualización tabular del historial de datos.
- **HTML `<iframe>`** – Integración de gráficas en tiempo real desde ThingSpeak.

---

## Estructura del repositorio

- `OLMO_SEGOVIA_MARA_Actividad2.ipynb` – Código fuente de la aplicación.
- `README.md` – Este archivo, con toda la información del proyecto.
- `OLMO_SEGOVIA_MARA_ANEXO1.docx` – Creación y configuración del canal ThingSpeak.
- `OLMO_SEGOVIA_MARA_ANEXO2.docx` – Programar la aplicación en Python.
- `OLMO_SEGOVIA_MARA_ANEXO3.docx` – Publicación del proyecto en Github.

---

## Canal ThingSpeak

Canal público utilizado: **Estación Ambiental**  
ID del canal: `2960836`

---



