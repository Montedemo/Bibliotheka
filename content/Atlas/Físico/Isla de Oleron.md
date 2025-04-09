---
NoteIcon: geotierra
tags:
  - Geography 
  - land 
categoria: Formación Terrestre
clase: Isla 
tipo: Isla habitada 
location: 
  - Galia 
  - Mar Cantábrico 
  - Estuario de Gironda 
aura:
  - feérica
propietario:
disputado: conflicto
region:
  - Aquitania  
  - Guyena 
  - Charentes 
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
Isla aquitana al norte del estuario de Gironda. Se trata de la mayor isla de la galia con 34 km de largo y 15 de ancho y con un relieve relativamente plano cuya cota más alta es de 34 metros. Oleron se encuentra en el corazón de la zona más soleada de la costa atlántica gala lo que la beneficia con un clima templado y agradable. 

## Historia 
Oleron se conoce desde el siglo I bajo el nombre de Uliaros (in aquitanico sinu Vilaros) -según Plinio el Viejo. Se cultiva la vid desde finales del siglo III cuando el emperador Probo extendió a toda las Galias el privilegio de tener viñedos y producir vino. 

En los siglos VII y VIII, la isla, junto con Ré, formó las Vacetae Insulae o islas Vacetian. Vaceti est otro nombre para los vascones, la referencia es evidencia del control vasco (gascón) de las islas en esa fecha.

Fue en Oléron entre 1152 y 1160 cuando Leonor de Aquitania introdujo las primeras leyes 'marítimas' o de 'almirantazgo' en esa parte del mundo: los Rollos de Oléron.

## Perspectiva Hermética
Sede de una antigua corte feérica de la era artúrica y desde 1028 de la poderosa alanza de la [[Casa Merinita]] de [[Oleron]] cuyo cabecilla es el consorte de la reina feérica de la isla. 
