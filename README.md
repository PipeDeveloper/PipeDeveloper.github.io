[![GitHub license](https://img.shields.io/github/license/PipeDeveloper/Openkore-Configs.svg)](https://github.com/PipeDeveloper/Openkore-Configs/blob/master/LICENSE)
[![Docker Build status](https://img.shields.io/docker/build/PipeDeveloper/Openkore-Configs.svg)](https://hub.docker.com/r/PipeDeveloper/Openkore-Configs/)
[![GitHub issues](https://img.shields.io/github/issues/PipeDeveloper/Openkore-Configs.svg)](https://github.com/PipeDeveloper/Openkore-Configs/issues)
[![GitHub forks](https://img.shields.io/github/forks/PipeDeveloper/Openkore-Configs.svg)](https://github.com/PipeDeveloper/Openkore-Configs/network)
[![GitHub stars](https://img.shields.io/github/stars/PipeDeveloper/Openkore-Configs.svg)](https://github.com/PipeDeveloper/Openkore-Configs/stargazers)
[![Github All Releases](https://img.shields.io/github/downloads/PipeDeveloper/Openkore-Configs/total.svg)](https://github.com/PipeDeveloper/Openkore-Configs/releases)

**Para más información, visita nuestro [Wiki ![](https://github.com/PipeDeveloper/PipeDeveloper.github.io/blob/master/assets/css/question.png?raw=true)](https://github.com/PipeDeveloper/Openkore-Configs/wiki)**

---
## Índice

- [Link de Descarga](#link-de-descarga)
- [Instrucciones de Instalación](#instrucciones-de-instalación)
- [Modificar y Mantener Builds/Updates](#modificar-y-mantener-buildsupdates)
- [Estado de Macros](#estado-de-macros)
- [Agradecimientos](#agradecimientos)
- [Referencias](#referencias)

---
## Link de Descarga

El repositorio puedes descargarlo del siguiente link: [Descargar ![](https://github.com/PipeDeveloper/PipeDeveloper.github.io/blob/master/assets/css/icon-download.png?raw=true)](https://github.com/PipeDeveloper/Openkore-Configs/archive/master.zip)

Para otras descargas visita nuestra sección de releases: [Releases ![](https://github.com/PipeDeveloper/PipeDeveloper.github.io/blob/master/assets/css/icon-download.png?raw=true)](https://github.com/PipeDeveloper/Openkore-Configs/releases)

**Recuerda utilizar los archivos que vas a utilizar**



## Instrucciones de Instalación

1. Haga click en el enlace de [descarga](https://github.com/PipeDeveloper/Openkore-Configs/releases).

2. Descomprima la carpeta `Openkore-Configs.zip` y seleccione la carpeta de acuerdo a la clase que se quiera trabajar.

3. Mueva y reemplace los archivos en la carpeta principal de Openkore.
    - Es recomendable hacerlo con todos, tanto control como plugins.
  
  
4. En el caso que el macro requiera un **plugin** descarguelo [aqui](https://github.com/PipeDeveloper/Openkore-Configs/releases) o desde nuestro [repositorio](https://github.com/PipeDeveloper/Openkore-Configs/) y agreguelo a la carpeta principal de Openkore.
    - Por defecto nuestros plugins están agregados en **sys.txt** en la carpta control, si desea utilizar otros plugins no olvide agregarlos! (más informacion consulte nuestra [Wiki](https://github.com/PipeDeveloper/Openkore-Configs/wiki)).


## Modificar y Mantener Builds/Updates

**Esto es opcional, para más informacion consulte la sección avanzada de nuestra [Wiki](https://github.com/PipeDeveloper/Openkore-Configs/wiki)**

1. Clone el proyecto desde nuestro [repositorio](https://github.com/PipeDeveloper/Openkore-Configs/).
2. Modifique el archivo `config.pm` de acuerdo a la clase trabajada.
3. Utilize los archivos `generador-eventmacros-windows.bat` (Windows 7/8/8.1/10) o` generador-eventmacros-linux-osx.sh` (Linux / OsX) para generar su macro.
4. Para actualizar los macros mediante el repositorio:
    - **Windows**: Al ejecutar el generador, este le preguntará si decea actualizar y conservará sus macros modificados/personalizados.
    - **Linux / OsX**: Si el repositorio es actualizado, ejecutar los siguientes comandos.
        - `git stash save` Este comando guarda las modificaciones.
        - `git pull --rebase` Este comando actualiza los archivos de la macro.
        - `git stash pop` Este comando restaura las modificaciones.

5. Utilize el generador nuevamente para generar la nueva macro actualizada con sus configuraciones ya aplicadas.


## Estado de Macros

Puedes corroborar el estado de los macros actuales, quest y configs en el siguiente [**Link** ![](https://github.com/PipeDeveloper/PipeDeveloper.github.io/blob/master/assets/css/Warning.png?raw=true)](https://github.com/PipeDeveloper/Openkore-Configs/wiki).

## Agradecimientos
Derechos de autor reservados a [Nipodemos](https://github.com/Nipodemos) y [Contribuidores](https://github.com/eventMacrosBR/up_1_ao_99_todas_classes-bro/graphs/contributors) en el proyecto bRO.

Derechos de autor a [Zelecktor](https://github.com/Zelecktor) y colaboradores en este proyecto.

## Referencias
Documentación y enlaces útiles para trabajar con el proyecto y eventMacros en nuestra [Wiki ![](https://github.com/PipeDeveloper/PipeDeveloper.github.io/blob/master/assets/css/question.png?raw=true)](https://github.com/PipeDeveloper/Openkore-Configs/wiki)


---
Copyright ® 2018 PipeDeveloper. Todos los derechos reservados. Políticas de Privacidad y Seguridad.
