---
NoteIcon: geo
tags:
  - Geography 
categoria: Formación Terrestre
clase: Paraje  
tipo: Prado  
location: Chalons
aura: Infernal, 3
propietario: 
disputado: 
region: 
  - Champaña 
---

> [!infobox]
> # `=this.file.name`
> ![[MapPlaceholder.png|cover hsmall]]
> ###### `=this.categoria` 
> ###### Información general
>  |   |
> ---|---|
> Clase | `=this.clase` |
> Tipo | `=this.tipo` |
> Region | `=this.region` |
> Parte de | `=this.location` |
> Aura | `=this.aura`  |
> ###### Viaje (`=[[Travel Calculator]].HoursPerDay` hrs per day)
> ###### [[Travel Calculator]]  / [[Exhaustion]]:  `=[[Travel Calculator]].ExhaustionLevel`
> Destino |  Jornadas  |
> ---|---|
> [[Voonlar]] | 🕓: `VIEW[round((88* {Travel Calculator#TravelCalc}) / 60 / {Travel Calculator#HoursPerDay}, 1)]`      |
> ###### Politica
>  |   |
> ---|---|
> Propiedad de: | `=this.propietario` |
> Disputado por | `=this.disputado` |
>###### Lugares de interés
> ```dataview
table WITHOUT ID link(file.name) AS "Engloba",  tipo
from "2. Geografía 🌍/Fisico"
where contains( location, this.file.name)
>```
>###### Poblaciones de interés
> ```dataview
table WITHOUT ID link(file.name) AS "Engloba",  tipo
from "2. Geografía 🌍/Demografico"
where contains( location, this.file.name)
>```
>###### Organizaciones
> ```dataview
table WITHOUT ID link(file.name) AS "Entidad", link(Leader) AS "Jefe", categoría, clase, tipo
from "3. Personajes y Organizaciones 🧑‍🤝‍🧑/Grupos"
where contains( PrimaryHome, this.file.name)
>```
>###### Personalidades 
>```dataview
TABLE WITHOUT ID link(file.name) AS "Nombre", clase, tipo, ☠
from "3. Personajes y Organizaciones 🧑‍🤝‍🧑/Personajes"
where contains( PrimaryHome, this.file.name)
SORT file.name DESC
>```
>###### Criaturas
> ```dataview
TABLE WITHOUT ID link(file.name) AS "Criatura", tipo, RdP
from "6. Bestiario 🐉"
where contains( PrimaryHome, this.file.name)
SORT file.name DESC
>```


# `=this.file.name`

### Imagen

### Mapa
![[MapPlaceholder.png|Placeholder]]
![[ImagePlaceholder.png|Placeholder Picture]]

La Batalla de los Campos Cataláunicos, una de las más grandes y sangrientas de la Alta Edad Media, tuvo lugar en 451 en las cercanías de la ciudad romana de Catalaunum (Châlons-en-Champagne). Ese mismo año, Atila el Huno, acompañado por sus aliados ostrogodos, aprovechó la debilidad del poder romano en la Galia e invadió hacia el oeste. Para mediados de año, ya había saqueado Reims y sitiado Orleáns, mientras que París fue salvada por las oraciones de Santa Genoveva.

El general romano Aecio lideró un ejército de auxiliares provenientes de Italia, que se unió a los visigodos bajo el mando de Teodorico y a los francos, liderados por el legendario rey Meroveo. Ambos ejércitos, de unos cincuenta mil hombres cada uno, se encontraron en los Campos Cataláunicos a mediados de verano.

Los adivinos de Atila predijeron correctamente la derrota de los hunos, aunque también la muerte de uno de los líderes enemigos. Durante la batalla, los hunos intentaron apoderarse de una estratégica cresta del terreno, pero fueron repelidos por la alianza romana, provocando una retirada desordenada. Durante el caos, Teodorico murió por una lanza ostrogoda, aunque el avance visigodo obligó a las tropas de élite de Atila a refugiarse en su campamento fortificado. A pesar de la derrota, Atila logró escapar y continuó siendo una amenaza para Europa durante dos años más.

La brutalidad de la batalla fue devastadora, con más de cuarenta mil muertos. Según el cronista del siglo VI Jordanes, “un arroyo que fluía entre bancos bajos se llenó con la sangre de los caídos, transformándose en un torrente de sangre mezclada con agua.”

Hoy en día, el campo de batalla, a unas pocas millas de Châlons, está compuesto por tierras desoladas, pastoreadas por ovejas dispersas y campesinos empobrecidos. Se dice que una aura infernal de nivel 3 impregna el lugar, y en la noche del solsticio de verano, el arroyo corre rojo de sangre, acompañado de gritos aterradores. El sitio es un portal hacia una regio infernal donde los espectros de los combatientes luchan eternamente, guiados por demonios guerreros. Un mago valiente podría cosechar vis de Perdo y Corpus, aunque algunas pueden estar corruptas por lo Infernal.