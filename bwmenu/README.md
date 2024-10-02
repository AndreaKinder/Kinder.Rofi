# bwmenu - Integración de Bitwarden para Rofi

Bienvenido a bwmenu, un potente componente de Kinder.Rofi, que es un sub-repositorio de Kinder.Dots (configuraciones personalizadas para Arch Linux). Esta herramienta permite una interacción fluida con Bitwarden a través de la interfaz de Rofi.

## Descripción general

bwmenu es un script que integra el gestor de contraseñas Bitwarden con Rofi, proporcionando una forma conveniente y eficiente de acceder a tu bóveda de Bitwarden directamente desde tu menú Rofi. Este componente ha sido adaptado del trabajo original encontrado en el repositorio [mattydebie/bitwarden-rofi](https://github.com/mattydebie/bitwarden-rofi/blob/master/bwmenu).

## Características

- Acceso rápido a las entradas de la bóveda de Bitwarden
- Búsqueda y filtrado de elementos de Bitwarden
- Copia de nombres de usuario y contraseñas al portapapeles
- Funcionalidad de auto-escritura para facilitar el llenado de formularios
- Manejo seguro de información sensible

## Requisitos previos

Antes de usar bwmenu, asegúrate de tener instalado lo siguiente:

- Rofi
- Bitwarden CLI (bw)
- xclip o wl-clipboard (dependiendo de tu sistema)

## Instalación

Como parte de Kinder.Rofi, bwmenu viene preconfigurado en el repositorio Kinder.Dots. Para usarlo:

1. Clona el repositorio Kinder.Dots
2. Navega al directorio Kinder.Rofi
3. Asegúrate de que bwmenu tenga permisos de ejecución

## Uso

Para usar bwmenu, simplemente ejecuta:

```bash
rofi -show bw -modi "bw:./bwmenu"
```

También puedes vincular este comando a un atajo de teclado para un acceso rápido.

## Configuración

bwmenu puede ser personalizado para adaptarse a tu flujo de trabajo. Revisa el script para ver las opciones disponibles y modifícalo según sea necesario.

## Contribuciones

Las contribuciones para mejorar bwmenu son bienvenidas. Por favor, envía pull requests o issues al repositorio Kinder.Dots.

## Licencia

Esta adaptación de bwmenu se distribuye bajo la misma licencia que el proyecto original. Por favor, consulta el repositorio original para obtener detalles sobre la licencia.

¡Gracias por usar bwmenu! Esperamos que esta herramienta mejore tu experiencia de gestión de contraseñas en tu entorno Arch Linux.