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
 <section class="wa-section main-content"><p>Río de la <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="82fae6a7-afac-4fac-9957-6000f6b3eb18" data-template-type="location" data-article="82fae6a7-afac-4fac-9957-6000f6b3eb18">Septimania</span> que nace en la <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="7ede2424-73ac-4a48-98fc-3496351baff9" data-template-type="location" data-article="7ede2424-73ac-4a48-98fc-3496351baff9">Cerdanha</span> y cuyo valle conforma el <span data-article-privacy="private" data-article-id="cbad7a50-0e1a-4779-8acd-c789a7273f93" data-template-type="location" class="private-article article-unlinked entity-link wa-link">Conflent</span>. Desemboca en el Mediterráneo en <span data-article-privacy="private" data-article-id="41c5399e-bc14-4d3d-af5a-8ec4cfa796c2" data-template-type="settlement" class="private-article article-unlinked entity-link wa-link">Perpinhan</span> en el <span data-article-privacy="private" data-article-id="41744e5d-3986-47d0-a8de-c4ec83d54078" data-template-type="location" class="private-article article-unlinked entity-link wa-link">Rosellón</span>.</p></section>   

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

