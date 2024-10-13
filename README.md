# Cómo instalar Git en Windows

## Introducción
Git es un sistema de control de versiones distribuido que permite rastrear cambios en archivos y colaborar con otros desarrolladores. Este documento te guiará a través del proceso de instalación de Git en Windows.

## Requisitos previos
- Un sistema operativo Windows (10 o superior recomendado).
- Acceso a Internet para descargar el instalador.

## Pasos para la instalación

### Paso 1: Descargar el instalador de Git
1. Visita la página oficial de Git: [git-scm.com](https://git-scm.com).
2. Haz clic en el botón de descarga para Windows. Esto descargará automáticamente el instalador adecuado para tu sistema.

### Paso 2: Ejecutar el instalador
1. Navega a la carpeta donde descargaste el instalador (generalmente la carpeta de "Descargas").
2. Haz doble clic en el archivo `Git-x.x.x.exe` (donde x.x.x representa la versión) para abrir el instalador.

### Paso 3: Configurar la instalación
1. **Selecciona el idioma**: Elige tu idioma preferido y haz clic en "OK".
2. **Licencia**: Acepta los términos de la licencia y haz clic en "Next".
3. **Seleccionar componentes**: 
   - Deja las opciones predeterminadas seleccionadas. 
   - Puedes optar por añadir íconos de acceso directo para facilitar el acceso.
4. **Seleccionar el editor de texto predeterminado**: Escoge tu editor de texto favorito o deja el predeterminado (Vim) y haz clic en "Next".
5. **Ajustes de PATH**: 
   - Selecciona "Use Git from the Windows Command Prompt" para que Git se pueda ejecutar desde cualquier terminal en Windows.
6. **Configuraciones adicionales**: Revisa las opciones y deja las predeterminadas si no tienes preferencias específicas. Haz clic en "Next" hasta llegar a "Install".

### Paso 4: Completar la instalación
1. Haz clic en "Finish" una vez que la instalación haya finalizado. Puedes optar por abrir Git Bash inmediatamente.

## Verificar la instalación
1. Abre el "Símbolo del sistema" o "Git Bash".
2. Escribe el siguiente comando y presiona Enter para confirmar que Git se instaló correctamente:

   ```bash
   git --version