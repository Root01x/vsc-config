"# vsc-config

Configuración personalizada de Visual Studio Code con un enfoque minimalista y productivo.

## Descripción

Este repositorio contiene mi configuración personal de VS Code, optimizada para una experiencia de desarrollo limpia y sin distracciones. El setup utiliza el tema **Kanagawa Dragon** con efectos de transparencia y una interfaz simplificada.

## Características Principales

- **Interfaz Minimalista**: Sin breadcrumbs, minimap, ni barra de actividad visible
- **Tema Oscuro**: Kanagawa Dragon con colores personalizados
- **Fuente Profesional**: JetBrains Mono con ligaduras habilitadas
- **Efectos Visuales**: Transparencia sutil con GlassIt
- **Formateo Automático**: Guardado con formato automático activado
- **Layout Optimizado**: Sidebar a la derecha, editor centrado con padding

## Instalación

### 1. Clonar el repositorio

```bash
git clone <repository-url> vsc-config
cd vsc-config
```

### 2. Copiar archivos de configuración

**Windows:**
```bash
copy settings.json "%APPDATA%\Code\User\settings.json"
copy keybindings.json "%APPDATA%\Code\User\keybindings.json"
```

**macOS/Linux:**
```bash
cp settings.json ~/Library/Application\ Support/Code/User/settings.json
cp keybindings.json ~/Library/Application\ Support/Code/User/keybindings.json
```

### 3. Instalar extensiones

Las extensiones se pueden instalar manualmente desde el marketplace o usando el comando:

```bash
code --install-extension enkia.tokyo-night
code --install-extension github.copilot
code --install-extension github.copilot-chat
code --install-extension gruntfuggly.activitusbar
code --install-extension metaphore.kanagawa-vscode-color-theme
code --install-extension qufiwefefwoyn.kanagawa
code --install-extension s-nlf-fh.glassit
```

## Extensiones Incluidas

| Extensión | Propósito |
|-----------|-----------|
| **Kanagawa Theme** | Tema de color principal (Dragon variant) |
| **Tokyo Night** | Tema alternativo oscuro |
| **GitHub Copilot** | Asistente de código con IA |
| **Copilot Chat** | Interfaz de chat para Copilot |
| **ActivitusBar** | Gestión personalizada de la barra de actividades |
| **GlassIt** | Efectos de transparencia en la ventana |

## Configuración Destacada

### Apariencia
- Tema: Kanagawa Dragon
- Fuente: JetBrains Mono (16px)
- Transparencia: Alpha 250
- Padding del editor: 16px superior e inferior

### Interfaz
- Barra de actividad: Oculta
- Sidebar: Posición derecha
- Breadcrumbs: Desactivados
- Minimap: Desactivado
- Menu bar: Compacto

### Editor
- Formato automático al guardar
- Ligaduras de fuente habilitadas
- Números de línea con color de acento personalizado

## Personalización de Colores

El esquema de colores utiliza una paleta cohesiva:
- Background principal: `#181616`
- Acentos: `#9c6a0db7` (tono dorado/marrón)
- Elementos activos: `#272626` con variaciones de transparencia

## Atajos de Teclado

Actualmente no hay atajos personalizados configurados. Puedes agregar los tuyos en [keybindings.json](keybindings.json).

## Respaldo y Sincronización

Este repositorio sirve como respaldo de la configuración. Para mantenerlo actualizado:

```bash
# Copiar configuración actual a este directorio
# Windows
copy "%APPDATA%\Code\User\settings.json" settings.json
copy "%APPDATA%\Code\User\keybindings.json" keybindings.json

# Commit y push
git add .
git commit -m "Update configuration"
git push
```

## Requisitos

- Visual Studio Code v1.80 o superior
- Fuente JetBrains Mono instalada en el sistema ([Descargar aquí](https://www.jetbrains.com/lp/mono/))
- Extensiones listadas en [extensions.txt](extensions.txt)

## Licencia

Configuración personal de uso libre. Siéntete libre de usar y modificar según tus necesidades." 
