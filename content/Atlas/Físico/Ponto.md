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
 <section class="wa-section main-content"><p>El mar Negro es un mar ubicado entre Europa oriental y Asia occidental. Se encuentra encerrado entre los Hemo, Sarmatia, el Cáucaso y la península de Anatolia. El estrecho del Bósforo lo conecta con el pequeño mar de Mármara, y el estrecho de los Dardanelos conecta al anterior mar con el mar Egeo, que es una división del mar Mediterráneo. También está conectado con el mar de Azov, situado al noreste, por el estrecho de Kerch.
</p>
<p>
Existe una salida neta de agua de 300 km3 al año a través del Bósforo y del estrecho de Dardanelos hacia el mar Egeo, mientras que el agua del Mediterráneo discurre hacia el mar Negro como parte de un camino de ida y vuelta de intercambio hidrológico. El flujo que sale del mar Negro es más frío y menos salino, y el flujo que entra desde el Mediterráneo es más cálido y salino, por lo que este flujo es el resultado de los cambios de densidad causados por la diferente salinidad, lo que da lugar a una gran cantidad de agua anóxica a 150 m bajo la superficie, que tienen la particularidad de descomponer los barcos hundidos fabricados en hierro pero no así los barcos de madera. El mar Negro también recibe agua del gran sistema fluvial de Eurasia por el norte del mar. Los ríos que le aportan más agua son el Danubio, el Dniéster, el Dniéper y el Don.</p></section>  <section data-section-id="alternativename" class="wa-section public"><dl><dt>Alternativename</dt><dd>Mar Negro, Mare Nigrum, Ponto Euxino</dd></dl></section><section data-section-id="history" class="wa-section public"><h2>History</h2>
<p>En la obra Geografía (1.2.10) Estrabón dice que en la antigüedad, el mar Negro era llamado a menudo "El Mar" (ὁ πόντος, ho pontos). Durante mucho tiempo, la tradición grecorromana se ha referido al mar Negro como el mar Hospitalario (Εὔξεινος Πόντος, Eúxeinos Póntos), lo que reemplazó a un nombre anterior, el de mar Inhóspito (Πόντος Ἄξεινος, Póntos Áxeinos), citado por primera vez por Píndaro (c. 475 a. C.). Estrabón (7.3.6) cree que el mar Negro fue llamado "Inhóspito" antes de la colonización griega porque era difícil de navegar y porque sus costas estaban pobladas por tribus salvajes. El nombre fue cambiado por el de "Hospitalario" después de que los milesios griegos colonizaran la costa sur, el Ponto, convirtiéndola en parte de la civilización griega. También es posible que el epíteto Áxeinos venga etimológicamente de la palabra escita axšaina, que significa "oscuro"; por lo que la designación de mar Negro podría provenir de la antigüedad.
</p>
<p>
Por el mar Negro pasan muchas rutas habituales del mundo oriental: hacia los Hemo, hacia las estepas del norte de Eurasia, al Cáucaso y a Asia Central, a Asia Menor y a Mesopotamia, y hacia Grecia desde el suroeste.
</p>
<p>
Los procesadores más antiguos del oro se encontraban en Varna. Además, el mar Negro fue, supuestamente, navegado por los argonautas. La tierra al este del mar Negro, la Cólquida (actualmente Georgia) era el fin oriental del mundo conocido por los griegos.</p><hr /></section>   

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

