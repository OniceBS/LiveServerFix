# Pasos para resolver problemas de live server al cambiar el browser predefinido:

```sh
1.) En el archivo settings.json -> Advance Custom Browser Cmd Line (es la primer opción que aparece en los ajustes de la extensión), no se debe referenciar ningún explorador, se debe dejar vacio asi: ("liveServer.settings.AdvanceCustomBrowserCmdLine": "",), si no funciona dejandolo vacio de esa manera, borrar esa linea de codigo y seguir con los pasos 2 y 3.
```
```sh
2.) En la 3ra opción de los ajustes de la extensión de live server (Custom browser), se debe dejar en "null".
```
```sh
3.)En la busqueda de windows escribir -> "elegir un explorador web predeterminado" -> Navegador web -> (Elegir el explorador deseado, en mi caso Opera GX). 