# Tutorial_Arcade_MAME_2023
Tutorial para descargar y configurar MAME para emular juegos Arcade.

**Paso 1:** Nos descargamos ARCADE64 y lo descomprimimos donde lo queramos. Es importante tomar nota de la versión (por ejemplo, 0.254 a fecha de este tutorial). Es el programa que usaremos para lanzar los juegos con MAME. Este programa es de uso libre y legal:  
"ARCADE64 0.254.0 (64-bit, GUI)"  
https://arcade.mameworld.info/  

**Paso 2:** Descargar las ROMs de los juegos por Torrent (usar cliente qBitorrent), el llamado romset, que son todos los juegos actualmente emulados por MAME. Esta es la parte ilegal, hablando claro. Este romset es único para cada versión, en este caso necesitamos el romset de la versión 0.254. Hay varios tipos de empaquetado (merged, non-merged y split), si no sabemos cual usar, el más indicado es el "Split":  
"Set: MAME 0.254 ROMs (split)"  
11.966 ROMs / 75.75Gb  
https://pleasuredome.github.io/pleasuredome/mame/index.html  

**Paso 3 (Opcional):** Las ROMs anteriores contienen la mayoría de juegos, pero hay una pequeña parte de los juegos (un 4%) que para jugarlos se necesitan los ficheros CHD, que ocupan cerca de 1Tb. Estos son principalmente juegos modernos a partir del año 2000, en 3D, con cineméticas en Laserdisc.... una minoría, pero ocupan mucho espacio:  
"Set: MAME 0.254 CHDs (merged)"  
555 CHDs / 933Gb  
https://pleasuredome.github.io/pleasuredome/mame/index.html  

**Paso 4 (Opcional):** Los EXTRAs contienen multitud de elementos de los juegos, como capturas de pantalla, carátulas, iconos, posters... Hay que colocar cada uno en la carpeta que corresponda:  
"Set: MAME 0.254 EXTRAs"  
"Set: MAME 0.254 Multimedia"  

**Paso 5:** Arrancamos arcade64.exe, menú Options / Directory, y en el desplegable de "ROMs" seleccionamos la carpeta donde hemos descargado las ROMs y la añadimos. En el mismo sitio de ROMs, añadimos tambien la ruta de los CHD, si opcionlamente decidimos bajarlos tambien.
Esperamos a que la barra verde de abajo termine de buscar los juegos, y hacemos click en el menú "Tools" y en "Audit all sets".  El resultado debería ser casi perfecto, aunque no es raro falle alguna que otra rom, y haya que leer el error para solucionarlo.
Hacemos click en el 5º botón de arriba etiquetado "Toggle grouped view".  

**Paso 6:**  Ya podemos hacer click en cualquier juego de la lista y jugarlo.
