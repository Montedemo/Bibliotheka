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
 <section class="wa-section main-content"><p>El Lago de Carucedo se sitúa en la parte más occidental del Berizo, en el <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="983c8eac-8499-4733-9286-134d8464e491" data-template-type="organization" data-article="983c8eac-8499-4733-9286-134d8464e491">Reino de León</span> Destaca entre los lagos de barrera o aluvionamiento por su singular formación, debida a la explotación de las minas de oro romanas de Las Médulas.
</p><hr /><p></p></section>  <section data-section-id="sidebarcontent" class="wa-section public"><dl><dt>General Details</dt><dd><div id="34f6d6503aede53853bd52dd2e60184f" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/831448cb18e2f2c9ca20110729e6cefe.jpeg" alt title="Lago_de_Carucedo_.jpeg" /></div></dd></dl></section><section data-section-id="geography" class="wa-section public"><dl><dt>Geography</dt><dd>El Lago tiene un perímetro de aproximadamente 5 kilómetros y 9 metros de profundidad máxima.</dd></dl></section><section data-section-id="history" class="wa-section public"><h2>History</h2>
<p>El lago tiene una forma peculiar debido a su aprovechamiento, desde época romana, para enviar el agua con la que se anegaban las minas de oro de Las Médulas, explotadas mediante el método de ruina montium.</p><hr /></section><section data-section-id="localizedPhenomena" class="wa-section public"><h2>Localizedphenomena</h2>
<p>En El Bierzo existe la leyenda de que la espada de Roldán, Durandarte, se encuentra en el Lago de Carucedo, cerca de las minas romanas de Las Médulas.
<br />
Otra leyenda es la de <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="d6d63b68-f868-4c81-ad14-a5aeb258065d" data-template-type="myth" data-article="d6d63b68-f868-4c81-ad14-a5aeb258065d">Carissia y la ciudad anegada de lágrimas</span>, una ondina que se enamoró del general romano Tito Carissio. Al burlarse de ella lloró tanto que con sus lágrimas inundó la ciudad de Lucerna y se formó el lago.
<br />
Esta leyenda conecta el lugar con el <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="5b2591f0-9825-4c83-a6e9-b5b46d51af15" data-template-type="location" data-article="5b2591f0-9825-4c83-a6e9-b5b46d51af15">Mar Yago</span> que también se atribuye el haberse formado al inundar una ciudad llamada Lucerna.</p><hr /></section>  <section data-section-id="seeded" class="wa-section secret"><h2>Secrets</h2>
<p>Las aguas de Carucedo albergan una regio por la que se puede llegar a la Ciudad Anegada, la misma ciudad feérica dentro de una regio a la que se puede llegar desde el Mare Iacum. Solo @Vieya de Merinita conoce dicho secreto.</p><hr /></section>   

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

