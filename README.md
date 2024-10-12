# Cómo instalar Git en Windows

## Introducción
Git es un sistema de control de versiones distribuido que te permite rastrear cambios en archivos y colaborar con otros desarrolladores. Este documento te guiará a través del proceso de instalación de Git en un sistema operativo Windows.

## Requisitos previos
- Un sistema operativo Windows (10 o superior recomendado).
- Acceso a Internet para descargar el instalador.

## Pasos para la instalación

### Paso 1: Descargar el instalador de Git
1. Visita la página oficial de Git: [git-scm.com](https://git-scm.com).
2. Haz clic en el botón de descarga para Windows. Esto descargará automáticamente el instalador.

### Paso 2: Ejecutar el instalador
1. Navega a la carpeta donde descargaste el instalador (usualmente en "Descargas").
2. Haz doble clic en el archivo `Git-x.x.x.exe` (donde x.x.x es la versión).

### Paso 3: Configurar la instalación
1. **Selecciona el idioma**: Elige tu idioma preferido y haz clic en "OK".
2. **Licencia**: Acepta los términos de la licencia y haz clic en "Next".
3. **Seleccionar componente**: Deja seleccionadas las opciones predeterminadas y haz clic en "Next".
4. **Seleccionar el editor de texto predeterminado**: Selecciona tu editor favorito o deja el predeterminado (Vim) y haz clic en "Next".
5. **Ajustes de PATH**: Selecciona "Use Git from the Windows Command Prompt" para poder usar Git en la terminal de Windows y haz clic en "Next".
6. **Configuraciones adicionales**: Puedes dejar las opciones predeterminadas y hacer clic en "Next" hasta llegar a "Install".

### Paso 4: Completar la instalación
1. Haz clic en "Finish" una vez que la instalación haya finalizado.

## Verificar la instalación
Para asegurarte de que Git se ha instalado correctamente:
1. Abre el "Símbolo del sistema" o "Git Bash".
2. Escribe el siguiente comando y presiona Enter:

   ```bash
   git --version
