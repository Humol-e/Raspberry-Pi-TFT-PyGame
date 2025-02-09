# Raspberry Pi TFT con PyGame

Este proyecto muestra cómo utilizar una pantalla TFT con una Raspberry Pi empleando la biblioteca PyGame. Incluye ejemplos de visualización de un cubo 3D y una interfaz HUD (Head-Up Display).

## Contenidos del repositorio

- **cube.py**: Script que muestra un cubo 3D rotando en la pantalla TFT.
- **hud.py**: Script que presenta una interfaz HUD en la pantalla TFT.
- **.gitignore**: Archivo para excluir archivos innecesarios del repositorio.
- **readme.md**: Este archivo con información sobre el proyecto.

## Requisitos

- **Hardware**:
  - Raspberry Pi (cualquier modelo compatible).
  - Pantalla TFT compatible conectada a la Raspberry Pi.

- **Software**:
  - Sistema operativo Raspbian o similar.
  - Python 3 instalado.
  - Biblioteca PyGame para Python 3.

## Instalación

1. **Actualizar el sistema**:
   ```bash
   sudo apt-get update
   sudo apt-get upgrade
2. **Instalar python3 y pip**:
   ```bash
    sudo apt-get install python3 python3-pip
3. **Instala python3 game_**:
   ```bash
    sudo apt-get install python3-pygame

4. **Clonar repositorio**
   ```bash
    git clone https://github.com/luisllamasbinaburo/Raspberry-Pi-TFT-PyGame.git
    cd Raspberry-Pi-TFT-PyGame


**USO**
Antes de ejecutar los scripts, asegúrate de que la pantalla TFT esté correctamente configurada y funcionando como una salida de framebuffer
(generalmente /dev/fb1).

Si deseas que la salida de PyGame se muestre directamente en la pantalla TFT, es posible que necesites configurar la variable de entorno SDL_FBDEV para apuntar al framebuffer de la pantalla TFT. 
Por ejemplo:
   ```bash
      export SDL_FBDEV=/dev/fb1





