---
NoteIcon: geotierra
tags:
  - Geography 
  - land 
categoria: Formación Terrestre
clase: Montaña 
tipo: Macizo Montañoso 
location: 
  - Galia 
  - Montes Arvernos 
aura:
  - Feérica 
propietario: 
disputado: conflicto
region:
  - Borgoña  
  - Borgoña Ducal 
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
El [[Morvan]] es la única verdadera región salvaje de tamaño significativo en [[Borgoña Ducal]]. Su nombre, de origen celta, significa "Montaña Negra". Este macizo basáltico, más elevado que las tierras circundantes, es una meseta frecuentemente envuelta en lluvia, nieve o niebla, y sus ríos son propensos a volverse turbulentos y desbordarse repentinamente. Gran parte del Morvan está cubierto de bosques de robles, carpes y hayas, con algunos coníferos en las laderas más altas, rodeados de escarpes rocosos.  

Este terreno ondulado y empobrecido está escasamente poblado, sin campos fértiles ni viñedos. Los pocos campesinos errantes que sobreviven aquí suelen ser evitados por quienes habitan en regiones más civilizadas. Los magos de la región conocen varias fuentes de **vis** en el Morvan, muchas de las cuales son disputadas debido a la presencia de **hadas oscuras** que acechan en los lagos, arroyos y bosques.  

### Mapa
![[MapPlaceholder.png|Placeholder Map]]

### Imagen
![[ImagePlaceholder.png|Placeholder Picture]]