---
NoteIcon: geotierra
tags:
  - Geography 
  - land 
categoria: Formación Terrestre
clase: clase 1
tipo: clase 2
location: 
  - Continente/subcontinente para unidades mayores
  - Cordillera/curso principal/mar al que pertenece 
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
 <section class="wa-section main-content"><p>Larga e irregular serie de montañas y sierras que flanquean el río Ebro por el sur. A su alrededor forman las ásperas tierras de los páramos de Celtiberia.</p></section>  <section data-section-id="geography" class="wa-section public"><h2>Geography</h2>
<p>En fuentes romanas, es este el nombre de la alineación montañosa que flanquea al río Ebro por el sur, siendo sus alturas principales el monte Caunus cerca de Bilbilis, el Saltus Manlianus (la Sierra de Molina) y los "montes Doca" en Castilla.
</p>
<p>
La Idubeda marca la divisoria entre el valle del río <span data-article-privacy="private" data-article-id="8a5fec47-2b7e-4d6d-903b-63189fcfdef2" data-template-type="location" class="private-article article-unlinked entity-link wa-link">Ebro</span> y los ríos que van a morir al Océano, (Duero y Tajo). Discurre en dirección NO-SE desde el nacimiento del Ebro hasta el mismo <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="d5fcc32b-3357-47d2-a54c-a93f41ebdefe" data-template-type="location" data-article="d5fcc32b-3357-47d2-a54c-a93f41ebdefe">Mediterráneo</span> en las tierras de Edetania.</p><hr /></section><section data-section-id="history" class="wa-section public"><h2>History</h2>
<p>Idubeda es el nombre de uno de los veintisiete míticos reyes de España que se listan entre los descendientes de Túbal. Sería hijo de Ibero y padre de Brigo. Habría dado nombre a los montes Idubedas.</p><hr /></section>   

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

