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
    - [x] [Lluna](https://openclipart.org/detail/20299/moon-in-comic-style)
    - [x] [Nau](https://openclipart.org/detail/28806/a-cartoon-moon-rocket)
    - [x] [Espai](https://opengameart.org/content/space-backdrop) (fons)
    - [x] Les imatges són obtingudes de galeries OpenSource
1. [x] Reducció d'imatges per [Tinypng](https://tinypng.com/)
1. [ ] Disenyar una paleta de colors adaptada a les imatges
1. [ ] Aplicar Sprites
1. [ ] Validació
1. [ ] Crear una branca github amb versió mimificada
    - [ ] Validació

