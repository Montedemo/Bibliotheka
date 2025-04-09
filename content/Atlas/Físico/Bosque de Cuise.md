---
NoteIcon: geo
tags:
  - Geography 
categoria: Formación Terrestre
clase: Paraje  
tipo: Bosque 
location: 
  -  
  - 
aura:
  - 
  - 
propietario: dueño
disputado: conflicto
region: 
  - 
  - 
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
Al sur de [[Compiègne]] se encuentra una enorme extensión de bosque, un largo dedo de arbolado que se extiende desde el borde de la [[2. Geografía 🌍/Politico/3. Demarcaciones/Isla de Francia]] hasta las [[Ardenas]], con una longitud casi ininterrumpida de unos setenta millas. Gran parte del bosque es una reserva real, destinada a la caza de los reyes franceses. En general, es un lugar agradable, soleado y espacioso, con ríos sinuosos y estanques, suaves colinas cubiertas de hayas y robles, y rico en ciervos, lobos y jabalíes; en resumen, un lugar ideal para la caza. El bosque está salpicado de pequeñas aldeas y monasterios, cruzado por unos pocos caminos y numerosos senderos de caza. Los magos del Tribunal desconocen la existencia de una presencia feérica significativa en estos bosques; si existe algún gobernante feérico de este dominio forestal, seguramente es tanto recluido como generoso con los mortales.
### Imagen

### Mapa
![[MapPlaceholder.png|Placeholder]]
![[ImagePlaceholder.png|Placeholder Picture]]


