<p align="center">
  <img src="./images/climax_sh_logo.png" alt="SHSM_Logo">
  </p>

<h4 align="center"> 
WORK IN PROGRESS - NOT AVAILABLE YET.
</h4>

<h4 align="center">
<a href="README_eng.md">Read in English</a>
</h4>

<h4 align="center"> 
Un add-on para Blender que permite importar archivos BSP de Silent Hill: Shattered Memories y Silent Hill: Origins (PS2) con toda la geometría, materiales, texturas, coordenadas UV, colores de vértices y normales.
  </h4>

## Características

-  Importación completa de mapas BSP
-  Geometría con vértices, caras y topología correcta
-  Materiales y texturas automáticas
-  Coordenadas UV
-  Vertex colors
-  Normales de vértices
-  Soporte para triangle strips

## Instalación

### Opción 1: Instalación desde Release (Recomendado)

1. Andá [Releases](../../releases) y descargá `climax_sh_bsp_importer-v1.0.zip`
2. En Blender: **Edit > Preferences > Add-ons**
3. Haz clic en **Install** y selecciona el archivo ZIP descargado
4. Buscá `Climax Silent Hill BSP Importer` y habilita el add-on

### Opción 2: Instalación Manual

1. **Descargá o cloná este repositorio**
2. **Copiá la carpeta `climax_sh_bsp_importer`** a tu directorio de scripts de Blender:
   - **Windows**: `%APPDATA%\Blender Foundation\Blender\<version>\scripts\addons\`
   - **Linux**: `~/.config/blender/<version>/scripts/addons/`
   - **macOS**: `~/Library/Application Support/Blender/<version>/scripts/addons/`
3. Abrí Blender y andá a **Edit > Preferences > Add-ons**
4. Buscá `Climax Silent Hill BSP Importer` y habilita el add-on

## Uso

### Preparar archivos

Los archivos BSP deben estar organizados así:

```
your_map_folder/
├── your_map.bsp              (Silent Hill: Origins o Silent Hill: Shattered Memories)
├── texture_name1.png
├── texture_name2.png
└── ...
```

**Nota:** El complemento soporta tanto extensión `.bsp` como `.shsm_bsp`. Si tienes conflictos con otros plugins, puedes renombrar a `.shsm_bsp`.

### Importar

1. **File > Import > Silent Hill BSP (.bsp / .shsm_bsp)**
2. **Selecciona** el archivo `.bsp` o `.shsm_bsp`
3. Las texturas se cargarán automáticamente del directorio `Textures/`
4. ¡Listo! El mapa se importará con toda su geometría y materiales

### Juegos Soportados (Por ahora)

- **Silent Hill: Shattered Memories** (PS2)
- **Silent Hill: Origins** (PS2)

## Licencia

Este proyecto es comunitario y está disponible para uso personal y educativo.

---

¿Problemas? Reporta en la sección de issues.
