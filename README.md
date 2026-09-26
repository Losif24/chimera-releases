<p align="center"><img src="escaparate/banner.png" alt="Chimera" width="100%"></p>

<p align="center">
  <a href="https://github.com/Losif24/chimera-releases/releases/latest"><img src="https://img.shields.io/github/v/release/Losif24/chimera-releases?style=for-the-badge&label=versi%C3%B3n&color=C9A45C" alt="última versión"></a>
  <a href="https://github.com/Losif24/chimera-releases/releases"><img src="https://img.shields.io/github/downloads/Losif24/chimera-releases/total?style=for-the-badge&label=descargas&color=D4703F" alt="descargas"></a>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Windows 10 y 11">
  <img src="https://img.shields.io/badge/Python-3.13-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/QML-Qt%206-41CD52?style=for-the-badge&logo=qt&logoColor=white" alt="QML y Qt 6">
</p>

<h3 align="center">
  <a href="https://github.com/Losif24/chimera-releases/releases/latest">⬇️ Descargar para Windows</a>
</h3>

Chimera es un entorno de escritorio para entender y mantener proyectos de software. Indexa el código, muestra cómo se relacionan sus archivos y te permite editarlo con esa información siempre a mano, para saber qué afecta a qué antes de tocar nada.

## Aplicaciones

| Aplicación | Descripción |
|---|---|
| **Launcher** | El punto de partida. Desde aquí abres las demás aplicaciones, gestionas tus proyectos y sus archivos, y recibes las actualizaciones. |
| **CODE** | Editor de código con los colores de un IDE: git en el margen, plegado de bloques, varios cursores, búsqueda y reemplazo en todo el proyecto, terminal integrada y un depurador de Python que explica cada error. |
| **ANÁLISIS** | Grafo interactivo de dependencias. Muestra las capas del proyecto, los ciclos, el impacto de cada cambio y el riesgo de cada archivo. |

## Visualización

<table>
  <tr>
    <td width="50%"><img src="escaparate/code.png" alt="CODE · editor con git, plegado y esquema"><p align="center"><sub><b>CODE · editor con git, plegado y esquema</b></sub></p></td>
    <td width="50%"><img src="escaparate/dividido.png" alt="CODE · dos archivos a la vez y selección en columna"><p align="center"><sub><b>CODE · dos archivos a la vez y selección en columna</b></sub></p></td>
  </tr>
  <tr>
    <td width="50%"><img src="escaparate/avisos.png" alt="CODE · avisa al escribir si rompes una regla del proyecto"><p align="center"><sub><b>CODE · avisa al escribir si rompes una regla del proyecto</b></sub></p></td>
    <td width="50%"><img src="escaparate/historia.png" alt="CODE · la historia de cada archivo y qué cambió en cada commit"><p align="center"><sub><b>CODE · la historia de cada archivo y qué cambió en cada commit</b></sub></p></td>
  </tr>
  <tr>
    <td width="50%"><img src="escaparate/compilar.png" alt="CODE · compilar cualquier proyecto y saltar a cada error"><p align="center"><sub><b>CODE · compilar cualquier proyecto y saltar a cada error</b></sub></p></td>
    <td width="50%"><img src="escaparate/depurar.png" alt="CODE · ejecutar y depurar Python"><p align="center"><sub><b>CODE · ejecutar y depurar Python</b></sub></p></td>
  </tr>
  <tr>
    <td width="50%"><img src="escaparate/reemplazar.png" alt="CODE · buscar y reemplazar en todo el proyecto"><p align="center"><sub><b>CODE · buscar y reemplazar en todo el proyecto</b></sub></p></td>
    <td width="50%"><img src="escaparate/analisis.png" alt="ANÁLISIS · grafo de dependencias"><p align="center"><sub><b>ANÁLISIS · grafo de dependencias</b></sub></p></td>
  </tr>
  <tr>
    <td width="50%"><img src="escaparate/capas.png" alt="ANÁLISIS · capas del proyecto: en rojo, lo que va contra la arquitectura"><p align="center"><sub><b>ANÁLISIS · capas del proyecto: en rojo, lo que va contra la arquitectura</b></sub></p></td>
    <td width="50%"><img src="escaparate/impacto.png" alt="ANÁLISIS · qué se rompe si tocas un archivo"><p align="center"><sub><b>ANÁLISIS · qué se rompe si tocas un archivo</b></sub></p></td>
  </tr>
  <tr>
    <td width="50%"><img src="escaparate/launcher.png" alt="Launcher"><p align="center"><sub><b>Launcher</b></sub></p></td>
    <td width="50%"><img src="escaparate/novedades.png" alt="Launcher · actualizaciones verificadas y vuelta a una versión anterior"><p align="center"><sub><b>Launcher · actualizaciones verificadas y vuelta a una versión anterior</b></sub></p></td>
  </tr>
  <tr>
    <td width="50%"><img src="escaparate/biblioteca.png" alt="Launcher · biblioteca de proyectos"><p align="center"><sub><b>Launcher · biblioteca de proyectos</b></sub></p></td>
    <td width="50%"><img src="escaparate/proyecto.png" alt="Launcher · explorador de proyectos"><p align="center"><sub><b>Launcher · explorador de proyectos</b></sub></p></td>
  </tr>
</table>

## Características

- **Apertura inmediata.** Con el launcher abierto, CODE se mantiene listo en segundo plano y los archivos se abren en menos de un segundo.
- **Integración con Windows.** Comandos `ch`, `ch-code` y `ch-an` disponibles en <kbd>Win</kbd> + <kbd>R</kbd> y en la terminal, además de accesos directos en el menú contextual del Explorador.
- **Gestión de proyectos.** Navega por los archivos de cada proyecto y renómbralos, cópialos o elimínalos sin salir del launcher.
- **Ejecutar y depurar Python.** <kbd>F5</kbd> ejecuta el archivo con el Python que ya tienes instalado e instala las librerías que falten. Si hay un error, se pausa en la línea y explica en español qué pasó; puntos de parada, paso a paso y variables a la vista.
- **Git y cambios grandes sin miedo.** Las líneas nuevas y cambiadas se marcan en el margen y se revierten con un clic; reemplazar en todo el proyecto enseña cada coincidencia antes de tocar nada y se puede deshacer.
- **Editor pensado para el día a día.** Plegado de bloques, varios cursores, visor de imágenes, sangría automática, cierre de paréntesis y comillas, guías de sangría, atajos configurables y guardado automático. La terminal se abre con <kbd>Ctrl</kbd> + <kbd>Mayús</kbd> + <kbd>Ñ</kbd>.
- **Informes exportables.** Resumen del proyecto, análisis de impacto, flujo de dependencias y un `MAPA.md` listo para incluir en el repositorio.
- **Actualizaciones verificadas.** Cada instalador se comprueba con su huella SHA-256 y siempre es posible volver a una versión anterior.

## Lenguajes compatibles

<p align="center"><img src="https://skillicons.dev/icons?i=cpp,py,cs,js,ts,java,kotlin,go,rust,swift,dart,php,ruby,qt&perline=14" alt="lenguajes"></p>
<p align="center"><sub>C/C++ · Python · C# · JavaScript · TypeScript · Java · Kotlin · Go · Rust · Swift · Dart · PHP · Ruby · QML</sub></p>

## Tecnologías

<p align="center"><img src="https://skillicons.dev/icons?i=py,qt,windows" alt="Python, Qt y Windows"></p>
<p align="center"><sub>Python 3.13 · QML / Qt Quick (PySide6) · Inno Setup</sub></p>

## Instalación

1. Descarga la última versión de `ChimeraSetup-x.y.z.exe` desde [Releases](https://github.com/Losif24/chimera-releases/releases/latest).
2. Ejecuta el instalador. Chimera se instala para tu usuario en `%LOCALAPPDATA%\Programs\Chimera` y no requiere permisos de administrador.
3. A partir de ese momento, el launcher te avisará de cada nueva versión y se encargará de instalarla.

**Requisitos:** Windows 10 u 11 de 64 bits.

## Comandos

| Comando | Acción |
|---|---|
| `ch` | Abre el launcher |
| `ch-code .` · `ch-code archivo.py` | Abre CODE con la carpeta actual o solo con ese archivo |
| `ch-an .` · `ch-an MiProyecto` | Abre ANÁLISIS con ese proyecto |

---

<p align="center"><sub>Las ilustraciones proceden de grabados de dominio público: «Belerofonte mata a la Quimera», de Theodoor van Thulden según Rubens (1641, Rijksmuseum), y «Belerofonte en Pegaso» (1878).<br>Desarrollado por Losif24.</sub></p>
