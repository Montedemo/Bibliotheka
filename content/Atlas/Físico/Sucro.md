---
NoteIcon: geoagua
tags:
  - Geography 
  - water
categoria: Formación Acuática
clase: clase 1
tipo: clase 2
location: 
  - Mar o accidente marino mayor
  - Curso de agua principal
  - Continente/subcontinente para aguas interiores
  - Otras para aguas interiores menores
aura:
  - reinodpoder1
  - reinodpoder2
propietario: dueño
disputado: conflicto
region:
  - Estado 
  - Demarcación
  - Comarca
  - Subcomarca
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
 <section class="wa-section main-content"><p>Río mediterráneo que nace en los <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="2ea4c137-062c-4eff-806d-a2f3d6479d8f" data-template-type="location" data-article="2ea4c137-062c-4eff-806d-a2f3d6479d8f">Montes Celtibéricos</span> y desemboca en la villa de <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="27b55d14-4005-420f-933f-6c85b845af73" data-template-type="settlement" data-article="27b55d14-4005-420f-933f-6c85b845af73">Cullera</span>. Riega las ciudades de  <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="5ddc81cd-d4cc-4a5c-aac2-c5ef3fdbe6d8" data-template-type="settlement" data-article="5ddc81cd-d4cc-4a5c-aac2-c5ef3fdbe6d8">Cuenca</span> y <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="521bfbf8-27b0-46cc-baa8-0ebe2b4a8640" data-template-type="settlement" data-article="521bfbf8-27b0-46cc-baa8-0ebe2b4a8640">Xàtiva</span>.</p></section>   

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

