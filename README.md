# DS2AudioToolkit

Audio propio y sonidos nuevos para **Darksiders II Deathinitive Edition** (PC), escrito en Python
con solo la biblioteca estándar.

El juego usa Wwise 2014.1: los bancos (`.bnk`, versión 112) viven dentro de `media\media.upak` y
el audio largo en `media\sounds_streamed\PC\*.pck`. DS2AudioToolkit quiere permitir dos cosas:

1. **Sustituir sonidos existentes** por audio propio: el mismo evento suena con otro audio.
2. **Añadir sonidos nuevos** con sus propios disparadores en `scripts.obsp` (con
   [D2ScriptViewer](../D2ScriptViewer)).

`media.upak` no se toca nunca: los bancos modificados o nuevos los carga en tiempo de ejecución
un módulo de audio de Darksiders2DLL.

## Requisitos

Python 3.10 o posterior en Windows. No hace falta instalar ningún paquete.

## Licencia y créditos

Licencia MIT, a nombre de BOTProT800 ([LICENSE](LICENSE)). La procedencia de todo lo externo
está en [CREDITS.md](CREDITS.md) y los cambios en [CHANGELOG.md](CHANGELOG.md).