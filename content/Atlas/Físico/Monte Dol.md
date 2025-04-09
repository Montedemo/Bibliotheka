---
NoteIcon: geotierra
tags:
  - Geography
  - land
categoria: Formación Terrestre
clase: Colina
tipo: Promontorio
location:
  - Continente/subcontinente para unidades mayores
  - Cordillera/curso principal/mar al que pertenece
aura:
  - mágica
propietario: dueño
disputado: conflicto
region:
  - Bretaña
  - Rennes
  - Costa Esmeralda
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

El Monte Dol, un saliente de granito, domina la zona aunque sólo tiene 210 pies de altura. Fue un lugar sagrado para los druidas galos. [[Branugurix]] , domus magna de la [[Casa Diedne]], estaba aquí, oculta en una regio . La mayoría de los cristianos evitan el monte. Cuentan una historia de que San Miguel peleó aquí contra el Diablo, arrojándolo con tal fuerza que la hendidura hecha por el impacto y las cicatrices dejadas por sus garras son claramente visibles en el lado norte del monte. Cerca está la hendidura hecha por la espada del santo y en la que arrojó a su oponente. Pero el Diablo reapareció un momento después en la isla de Mont St. Michel, burlándose del santo, y la huella hecha por el pie del santo cuando saltó desde la cima del Monte Dol en persecución aún está allí. De hecho, lo que la historia recuerda es un asalto a Branugurix.


La pequeña ciudad de Dol se encuentra en un acantilado en el borde sur del pantano. La construcción de una catedral fortificada dedicada a San Samson está en progreso aquí. Al sur de Dol está el menhir de Champ-Dolent (Campo del Dolor), de 30 pies de altura con una base aproximadamente cuadrada que se va estrechando hacia un punto; marca el lugar donde tuvo lugar la batalla final de la Guerra del Cisma.

### Mapa
![[MapPlaceholder.png|Placeholder Map]]

### Imagen
![[ImagePlaceholder.png|Placeholder Picture]]

Placeholder

## PNJ Notables
Placeholder

## Geografía
Placeholder

## Fauna y Flora
Placeholder

## Puntos de Interés
Placeholder

## Objetos de Valor
Placeholder

## Habitantes
Placeholder

## Visitantes
Placeholder

## Historia
Placeholder

## Otros detalles de interés
Placeholder

