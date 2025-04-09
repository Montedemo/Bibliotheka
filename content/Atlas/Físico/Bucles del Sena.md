---
NoteIcon: geoagua
tags:
  - Geography 
  - water
categoria: Formación Acuática
clase: Humedal
tipo: Meandros 
location: 
  - Sena 
  - Galia 
  - Llanura del Sena 
aura:
  - Mágica 5
propietario: Requies Draconis 
disputado: Ruan 
region:
  - Francia  
  - Normandia 
  - Llanura del Sena 
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
Entre Ruán y su desembocadura en el [[Mar Británico]], el río [[Sena]] se ralentiza discurriendo en una serie de meandros (llamados *boucles*, que a su vez generan un variado paisaje de marismas, campos y bosques. ) Este fue el hogar del dragón [[Gargouille]] y la sede de las alianzas herméticas [[Confluensis]], hasta que se trasladó a Cotentin en el siglo XI y de sus sucesora, la Casa Mercer  de [[Requies Draconis]]. 
### Mapa
![[MapPlaceholder.png|Placeholder Map]]

### Imagen
![[boucles de seine.webp|Placeholder Picture]]



