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
 <section class="wa-section main-content"><p>Lagunas de origen glaciar entre los picos de Joclar y de Rulha, la dos mayores en el lado meridional, por Andorra y una tercera en el lado de Fois.</p></section>  <section data-section-id="sidebarcontent" class="wa-section public"><dl><dt>General Details</dt><dd><div id="b390418185452bfb369700a4f9f65211" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/7413fd1d83b5b19b9c3ee5ef08bf2274.jpeg" alt title="estany gran de joclar.jpeg" /></div></dd></dl></section><section data-section-id="geography" class="wa-section public"><h2>Geography</h2>
<p>El conjunto de estanques glaciares de Joclar está formado por:
</p><ul>
<li><b>Gran Joclar</b>, el de mayor tamaño separado del <b>Estany Segón</b> por un brazo de tierra, ambos inundando la hondonada que separa el Alt del Joclar del Pic de Escobes, la silueta del cual preside el paraje.</li>
<li><b>Estany Negre</b>: al norte de los anteriores, entre el Pic Negre y <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="11da3276-3de9-42f2-aa1e-d5a6141e02df" data-template-type="location" data-article="11da3276-3de9-42f2-aa1e-d5a6141e02df">La Rulha</span> , en tierras de Fois.</li>
<li><b>l'Estanyol</b>: el más pequeño y septentrional del conjunto, a la sombra de <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="11da3276-3de9-42f2-aa1e-d5a6141e02df" data-template-type="location" data-article="11da3276-3de9-42f2-aa1e-d5a6141e02df">La Rulha</span> y también en tierras sabartenses.</li>
</ul><p></p><hr /></section>   

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

