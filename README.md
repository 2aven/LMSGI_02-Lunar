# LMSGI_02-Lunar
## Lunar Landing (HTML i CSS)

Planificació:
1. [ ] Diseny principal del HTML segons el StoryBoard, primer en format d'escriptori
    Ha de contenir:
    - [x] index-d.html vinculat a d.css
    ```ruby
    <link rel="stylesheet" type="text/css" href="css/d.css"> 
    ```
    - [x] Control Panel (Altura / Velocitat / Combustible ...)
    - [x] (Menú-enllaços) Game Options (Pause / About / How to play)
    - [x] Nau
    - [x] Àrea d'aterratge
    - [x] Dotar la pàgina de colors de guía (no definitius)
    - [ ] ajuda.html vinculat a ajuda.css
1. [ ] Copiar-ho per adaptar a format smartphone ( -> index-m.html vinculat a m.css)
1. [ ] Unificar els formats *Desktop* i *Mobile* a index.html mitjançant **media query**
    ```ruby  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel='stylesheet' media='screen and (min-width: 720px)' href='css/d.css'>
    <link rel='stylesheet' media='screen and (max-width: 720px)' href='css/m.css'>
    ```
1. [ ] Crear els html corresponents per les pàgines dels menús *About*, *How to play* ...
1. [ ] Crear arxius CSS de les pàgines de menú
1. [x] Aconseguir imàtges.
    - [x] [Lluna](https://upload.wikimedia.org/wikipedia/commons/4/42/The-surface_of_the_moon.png)
    - [x] [Nau](https://openclipart.org/detail/28806/a-cartoon-moon-rocket)
    - [x] [Espai](https://opengameart.org/content/space-backdrop) (fons)
    - [x] Les imatges són obtingudes de galeries OpenSource
1. [x] Reducció d'imatges per [Tinypng](https://tinypng.com/)
1. [x] Disenyar una paleta de colors adaptada a les imatges: [Roda cromàtica](https://color.adobe.com/es/create/color-wheel/?base=2&rule=Custom&selected=2&name=cohet&mode=rgb&rgbvalues=0.4823529411764706,0.8666666666666667,0.9647058823529412,1,0.611764705882353,0,0.6509803921568628,0,1,0.9529411764705882,0.9529411764705882,0.9529411764705882,0.8,0.8,0.8&swatchOrder=0,1,2,3,4) en base a la imatge del coet, seleccionant colors del camp anàleg i complementàri (per evitar el vermell estrident)
    * Gis: F3F3F3
    * Gris clar: CCCCCC
    * Morat: A600FF
    * Taronja: FF9C00
    * Cel: 7BDDF6
1. [ ] Aplicar Sprites
1. [ ] Validació
1. [ ] Crear una branca github amb versió mimificada
    - [ ] Validació

