---
NoteIcon: geo
tags:
  - Geography 
categoria: Formación Terrestre
clase: Paraje  
tipo: Bosque 
location: 
  - Galia 
  - Llanura del Sena 
aura:
  - feérica 6
  - reinodpoder2
propietario: dueño
disputado: conflicto
region: 
  - Isla de Francia 
  - Región de París 
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
A unos 50 kilómetros al sur de [[París]], en la orilla izquierda del [[Sena]], se encuentra el bosque de Fontainebleau, una región rocosa y diversa de unos 32 kilómetros en cada dirección. Es un paisaje seco con colinas de arenisca, claros bosques llenos de caza y antiguos montículos druídicos. La zona más húmeda parece un páramo salpicado de estanques, mientras que otra parte es desértica, con rocas que tienen formas antropomórficas o animalescas.


### Imagen

### Mapa
![[MapPlaceholder.png|Placeholde
![[ImagePlaceholder.png|Placeholder Picture]]



## Perspectiva hermética 

#### La Fuente de las Aguas Hermosas  
En el centro del bosque está la "Fontaine-Belle-Eau", una regio feérica con un aura mágica de 6. Una hermosa ninfa, asociada con la diosa Diana, habita junto a la fuente, acompañada por un tranquilo ciervo blanco y otros animales del bosque. Aunque raras veces los humanos llegan hasta esta regio, los perros de caza pueden encontrarla accidentalmente. Aquellos que actúan con humildad pueden recibir recompensas, pero quienes persisten en la caza podrían ser maldecidos. Las formas antropomórficas de las rocas cercanas podrían ser el resultado de estas maldiciones y son fuente de valiosos materiales mágicos.