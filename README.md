# 📸 Guardar Imágenes JPG en ESP32 CAM con MicroSD

Este repositorio contiene un proyecto que te enseñará a capturar y guardar imágenes en formato JPG utilizando la **ESP32 CAM** y una **tarjeta microSD**. Es ideal para aquellos interesados en proyectos de IoT, vigilancia y fotografía remota. 🚀

## Contenido del Repositorio

- **Código fuente**: Archivos de código necesarios para la configuración de la ESP32 CAM.
- **Esquema de conexión**: Diagramas y explicaciones sobre cómo conectar la microSD a la ESP32 CAM.
- **Instrucciones**: Guía paso a paso para la configuración y ejecución del proyecto.

## Requisitos

- **Hardware**:
  - ESP32 CAM 🛠️
  - Tarjeta microSD (con adaptador, si es necesario) 💾
  - Cable USB para programación (FTDI)🔌
  - Fuente de alimentación (opcional) ⚡

- **Software**:
  - Arduino IDE (o compatible) 💻
  - Bibliotecas necesarias:
    - `SD_MMC.h`
    - `FS.h`
    - `WiFi.h`
    - `esp_camera.h`
    - `time.h`
    - `WiFi.h`

## Instrucciones de Uso

1. **Conectar el hardware**:
   - Sigue el esquema de conexión proporcionado en el repositorio. 🔗

2. **Configurar el código**:
   - Abre el archivo `SDCAM.ino` en Arduino IDE y ajusta las configuraciones de red (SSID y contraseña). 🔑

3. **Cargar el código**:
   - Conecta tu ESP32 CAM al ordenador y selecciona el puerto correcto en Arduino IDE. ⚙️
   - Carga el código. ⬆️

4. **Probar el proyecto**:
   - Una vez cargado el código, abre el monitor serie para ver las capturas de imágenes en tiempo real. 🖥️

## Licencia

Este proyecto está bajo la de libre uso


¡Disfruta creando con tu ESP32 CAM! 🎉
