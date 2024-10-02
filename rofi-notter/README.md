# Rofi-Notter

Rofi-Notter es un componente personalizado del repositorio Kinder.Rofi, que forma parte del macro repositorio Kinder.Dots. Esta herramienta mejora la funcionalidad de Rofi dentro del ecosistema Kinder.Dots, proporcionando una interfaz fluida para gestionar notas en múltiples bóvedas de Obsidian.

## Características

- Acceso y gestión de notas en tres bóvedas de Obsidian: “work”, “learn”y “personal”.
- Creación de nuevas notas utilizando plantillas predefinidas
- Visualización y edición de notas existentes
- Interfaz amigable impulsada por Rofi

## Instalación

Para instalar Rofi-Notter, clona el repositorio Kinder.Rofi:

```bash
git clone https://github.com/AndreaKinder/Kinder.Rofi.git
cd Kinder.Rofi/rofi-notter
```

## Uso

Ejecuta el script para lanzar la interfaz de Rofi-Notter:

```bash
./rofi-notter.sh
```

Se te presentarán dos opciones principales:

- 📑 Crear Nota: Crea una nueva nota en una de las tres bóvedas
- 🔖 Ver Notas: Navega y edita notas existentes

## Configuración

Puedes personalizar las siguientes variables en el script:

- TERMINAL: Tu emulador de terminal preferido
- VIEW: Tu visor de documentos preferido
- EDITOR: Tu editor de texto preferido
- Directorios de bóvedas: Rutas a tus bóvedas de Obsidian

## Dependencias

- Rofi
- Un emulador de terminal (por defecto: Alacritty)
- Un editor de texto (por defecto: Neovim)

## Contribuciones

Las contribuciones a Rofi-Notter son bienvenidas. Por favor, siéntete libre de enviar pull requests o abrir issues en el repositorio Kinder.Rofi.

## Licencia

Este proyecto es parte de Kinder.Dots y está sujeto a sus términos de licencia.

Para información más detallada sobre el código y su funcionalidad, por favor consulta los comentarios en línea en el script.