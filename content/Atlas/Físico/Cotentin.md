---
NoteIcon: geotierra
tags:
  - Geography 
  - land 
categoria: Formación Terrestre
clase: Península 
tipo: 
location: 
  - Galia 
  - Mar Británico 
aura:
propietario: dueño
disputado: conflicto
region:
  - Normandía 
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
Península pantanosa en la costa oeste del ducado de [[Normandía]].  Una región muy poco poblada y pobre. Esto se debe a que gran parte de la tierra es un horrible pantano y marismas, pero algunos castillos y pueblos se amontonan en las áreas secas. Los viajeros que pasan por el bosque de Brix (que se encuentra al sur de Cherburgo) corren el riesgo de emboscada por jaurías de lobos feéricos que acechan el bosque, pero los aldeanos que viven en el bosque pueden negociar con seguridad los caminos del bosque.

Hubo una alianza construida cerca de la ciudad de Cherburgo llamado **Pagus**. La alianza fue destruida durante la Guerra del Cisma, y hoy algunos de sus fuentes de vis son controvertidamente reclamados por una casa filial de [Fengheld](app://obsidian.md/Fengheld) (un gran alianza del [Tribunal del Rín](app://obsidian.md/Tribunal%20del%20R%C3%ADn) que está construida en Cherburgo. También se encuentra en la península la gran alianza quaesitorial de [Confluensis](app://obsidian.md/Confluensis).

### La Hague-Dicke
Los invasores nórdicos del siglo IX construyeron un terraplén fortificado — la Hague-Dicke — que separó la porción noroccidental de la península de Cotentin del continente. Las fortificaciones se utilizaron como cuarteles para guerreros que se quedaron varados y no pudieron cruzar los peligrosos mares de invierno hacia Escandinavia. También se organizaban aquí las tripulaciones durante la temporada de saqueo. Hoy en día, la fortaleza está desmantelada, enmarañada y ruinosa; su curso exacto ni siquiera se conoce definitivamente. Sin embargo, hay rumores de tesoros que fueron saqueados de monasterios y enterrados a lo largo del terraplén por saqueadores ya sobrecargados con botín.

### Barfleur
La ciudad portuaria de [[Barfleur]] fue donde se construyó gran parte de la flota de invasión de Guillermo el Conquistador. Desde entonces, se han encargado muchos barcos militares y mercantiles en los astilleros de Barfleur. El puerto no está exento de peligros — Guillermo hijo de Enrique I (rey de Inglaterra) se ahogó después de que su barco, al salir de Barfleur, chocara con una roca en 1120. También hay una serie de fantasmas marítimos que atormentan Barfleur, incluidos una flota espectral que navega frente a la ciudad durante tormentas invernales torrenciales, buscando inútilmente un puerto seguro.

### Mapa
![[MapPlaceholder.png|Placeholder Map]]

### Imagen
![[cotentin.webp|Placeholder Picture]]

