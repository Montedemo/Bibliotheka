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
 <section class="wa-section main-content"><p><span class="dropcap">Í</span>ZARO es una en aguas del mar Cantábrico, situada en la costa de <strong class="article-unlinked">Vizcaya</strong>, frente a las localidades de Bermeo y Mundaca a una distancia de 3 km de la primera y 2,2 km de la segunda. La isla ocupa el centro de la desembocadura de la <span data-article-privacy="private" data-article-id="4ab3ce90-c6a2-47c3-bf3f-2f0a54161ad0" data-template-type="location" class="private-article article-unlinked entity-link wa-link">Ría de Mundaca</span>, y se encuentra flanqueada por los cabos de Ogoño y Machichaco. 
<br /></p></section>  <section data-section-id="sidebarcontent" class="wa-section public"><dl><dt>General Details</dt><dd><div id="08d9195beda4176868cf02315991a585" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/2f951b6ae25777880203d410689c64b9.jpeg" alt title="640px-Izaro_island_2.jpeg" /></div></dd></dl></section><section data-section-id="geography" class="wa-section public"><h2>Geography</h2>
<p>La isla es alargada, de forma triangular, y está orientada en dirección NO-SE. La parte más alta y ancha de la isla es la parte SE. En su parte más ancha, mide unos 150 m, y su longitud es de 675 m, siendo su altura máxima de 44,5 m. La punta noroeste es denominada Archicote. Hacia el noreste de la isla, y separado de esta unos 200 m, existe una roca llamada Potorro-harri o Harri-ederra. Al sudeste se encuentra un embarcadero natural o "puerto" de Ízaro.
<br />Las gentes del lugar han solido especular sobre el origen de la isla; vista desde la playa de Laga, en el extremo nororiental de la reserva, presenta una forma similar al cabo de Ogoño, lo que ha motivado la creencia de que en tiempos remotos se desgajó de aquella roca hundiéndose en el mar. En cualquier caso la isla forma parte de una misma unidad geológica con la punta de Anzoras, situada en la margen derecha de la ría.</p><hr /></section><section data-section-id="history" class="wa-section public"><h2>History</h2>
<p>El lugar ha sido un emplazamiento aislado ocupado tan solo por balleneros y piratas.
<br />Las aguas bravías -que las gentes atribuyen a la acción de las sirenas, dificultan el acceso solo a marineros expertos y este solo es posible en días soleados, por lo que el lugar siempre ha peranecido distante e incomunicado de las poblaciones costeras de Bermeo y Mundaca.
<br />Existen ruinas de una antigua construcción en la explanada superior que los lugareños atribuyen a un viejo monasterio abandonado o destruido por los saqueadores <strong class="article-unlinked">Vikingos</strong>. Apenas quedan vestigios de él.</p><hr /></section><section data-section-id="florafauna" class="wa-section public"><h2>Florafauna</h2>
<p>Izaro es una importante colonia de aves marinas; allí la especie más abundante es la gaviota patiamarilla, aunque también anidan el paíño común y la garceta común.</p><hr /></section>   

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

