# rofi-web

rofi-web es un componente personalizado para Rofi, diseñado para mejorar las capacidades de navegación y búsqueda web directamente desde tu lanzador Rofi. Este componente es parte del repositorio Kinder.Rofi, que es un sub-repositorio de Kinder.Dots - una colección completa de configuraciones personalizadas de Arch Linux.

## Características

- Acceso rápido a URLs predefinidas
- Funcionalidad de búsqueda web sin problemas
- Integración con el navegador Firefox

## Instalación

Para instalar rofi-web, sigue estos pasos:

1. Clona el repositorio Kinder.Dots:
    
    ```bash
    git clone https://github.com/AndreaKinder/Kinder.Dots.git
    ```
    
2. Navega al sub-repositorio Kinder.Rofi:
    
    ```bash
    cd Kinder.Dots/Kinder.Rofi/rofi-web/
    ```
    
3. Copia el script rofi-web a tu ubicación preferida, por ejemplo:
    
    ```bash
    sudo cp rofi-web ~/.local/bin/
    ```
    
4. Haz que el script sea ejecutable:
    
    ```bash
    chmod +x ~/.local/bin/rofi-web
    ```
    

## Uso

Para usar rofi-web, puedes vincularlo a un atajo de teclado o ejecutarlo desde tu terminal:

```bash
rofi-web
```

Al iniciarse, rofi-web te presentará un menú con URLs predefinidas. Puedes:

- Seleccionar una de las URLs predefinidas para abrirla directamente en Firefox
- Ingresar una URL personalizada para visitar ese sitio web
- Ingresar un término de búsqueda para realizar una búsqueda en Google

## Personalización

Puedes personalizar fácilmente las URLs predefinidas editando el array `urls` en el script. Abre el script en tu editor de texto preferido y modifica la siguiente línea:

```bash
urls=("https://www.google.com" "https://www.github.com" "https://www.stackoverflow.com")
```

Agrega o elimina URLs según sea necesario, manteniendo el formato consistente.

## Dependencias

rofi-web requiere las siguientes dependencias:

- Rofi
- Firefox
- Bash

Asegúrate de que estén instaladas en tu sistema Arch Linux antes de usar rofi-web.

## Contribuciones

¡Las contribuciones a rofi-web son bienvenidas! Si tienes sugerencias para mejoras o correcciones de errores, por favor abre un issue o envía un pull request al repositorio Kinder.Rofi.

## Licencia

Este proyecto es parte de Kinder.Dots y está sujeto a sus términos de licencia. Por favor, consulta el repositorio principal de Kinder.Dots para obtener información sobre la licencia.