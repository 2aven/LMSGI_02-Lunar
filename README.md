# LMSGI_02-Lunar
## Lunar Landing (HTML i CSS)

### [Aterratge Lunar](https://rawgit.com/2aven/LMSGI_02-Lunar/master/index.html)

Planificació:
1. [x] Disseny principal del HTML segons el StoryBoard, primer en format d'escriptori (*desktop*).
    Ha de contenir:
    - [x] *index-d.html* vinculat a *d.css*
    ```ruby
    <link rel="stylesheet" type="text/css" href="css/d.css"> 
    ```
    - [x] Control Panel (Altura / Velocitat / Combustible ...)
    - [x] (Menú-enllaços) Game Options (Pausa / Reinici / Ajuda)
    - [x] Nau
    - [x] Àrea d'aterratge
    - [x] Dotar la pàgina de colors de guía (no definitius)
    - [x] *ajuda.html* vinculat a *a.css*
1. [x] Aconseguir imatges.
    - [x] [Lluna](https://upload.wikimedia.org/wikipedia/commons/4/42/The-surface_of_the_moon.png)
    - [x] [Nau](https://openclipart.org/detail/28806/a-cartoon-moon-rocket)
    - [x] [Espai](https://opengameart.org/content/space-backdrop) (fons)
    - [x] Les imatges són obtingudes de galeries OpenSource
1. [x] Reducció d'imatges per [Tinypng](https://tinypng.com/)
1. [x] Dissenyar una paleta de colors adaptada a les imatges: [Roda cromàtica](https://color.adobe.com/es/create/color-wheel/?base=2&rule=Custom&selected=2&name=cohet&mode=rgb&rgbvalues=0.4823529411764706,0.8666666666666667,0.9647058823529412,1,0.611764705882353,0,0.6509803921568628,0,1,0.9529411764705882,0.9529411764705882,0.9529411764705882,0.8,0.8,0.8&swatchOrder=0,1,2,3,4) en base a la imatge del coet, seleccionant colors del camp anàleg i complementari (per evitar el vermell estrident)
    * Gis: F3F3F3
    * Gris clar: CCCCCC
    * Morat: A600FF
    * Taronja: FF9C00
    * Cel: 7BDDF6
1. [x] Copiar-ho per adaptar a format *mobile* per smartphone ( -> *index-m.html* vinculat a *m.css*)
1. [x] [Validar][Validator] les pàgines (aplicar correccions)
    - [x] Incloure ```lang="ca"``` a l'etiqueta *meta*.
    - [x] Guardar-ho a una branca github: [*inicial*](https://github.com/2aven/LMSGI_02-Lunar/tree/inicial)
1. [x] Unificar els formats *Desktop* i *Mobile* a index.html mitjançant **media query**
    ```ruby  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel='stylesheet' media='screen and (min-width: 720px)' href='css/d.css'>
    <link rel='stylesheet' media='screen and (max-width: 720px)' href='css/m.css'>
    ```
1. [x] [Validació][Validator]
1. [x] Crear una branca github amb versió mimificada
    - [x] [Validació][Validator]

* Nota: No s'ha fet ús de Sprites, ja que per seguir amb les indicacions de fer el menú com a llista d'enllaços, s'han escrit de forma textual en lloc d'usar un grup d'imatges.

[Validator]: https://validator.w3.org/
