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
 <section class="wa-section main-content"><p><span class="dropcap">C</span>ONJUNTO de lagos glaciares en el alto valle de Astan de difícil acceso debido a su lejanía; se necesitan 8 horas de caminata desde <span data-article-privacy="private" data-article-id="4481ecdc-20f0-4295-a9e4-38a38a636341" data-template-type="settlement" class="private-article article-unlinked entity-link wa-link">Astan</span>.
La ruta más fácil viene desde Andorra por un camino hasta el pueblo de Soldeu (1850m) desde donde se puede llegar fácilmente a los lagos por el amplio valle de Inclès y el collado de Font Argenta (2252m) que domina los lagos del mismo nombre en 100m.
<br />
Hay 3 estanques en Font Argenta, siendo el grande el único importante, de 40 m de profundidad, el pequeño está situado unos metros por encima del grande en el que desemboca y el otro es aún más pequeño y sin comunicación con los demás, desagua en un pantano y su arroyo desciende directamente al valle.
<br />
Estos lagos están mal abastecidos debido a su altitud, el pico negro de Joclar los domina a 500 m y el Col de Font Argenta a sólo 100 m.
La cuenca glaciar que da origen al valle del Astan queda dividida por el pico de Joclar en dos valles: valle occidental con los 3 lagos de Font Argenta, y el valle oriental con los 2 lagos de Joclar y l'Estanyol.
<br />
Los dos torrentes se juntan y se dirigen a la meseta de Garsaing donde el Astan se hincha con el arroyo Coma de Varilhas con las aguas de los dos pequeños estanques de l'Anrondat y Miraball.
<br />
Hacia abajo de la meseta de Garsaing, un riachuelo se escapa del minúsculo estanque de Cabaillère.
</p><div id="c265b5aa44a80e0897f37caac6965674" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/cff48fe1bd77e366787657285eff0b0b.jpeg" alt title="etang-de-fontargente.jpeg" /></div><p></p></section>  <section data-section-id="sidebarcontent" class="wa-section public"><dl><dt>General Details</dt><dd><div id="dfc03b3c8445fe4cacab680387ab6e8a" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/7f3514b39c0c7fe55945a74078ec9f17.jpeg" alt title="Etangs-de-Fontargente.jpeg" /></div></dd></dl></section><section data-section-id="alternativename" class="wa-section public"><dl><dt>Alternativename</dt><dd>Fontargenta</dd></dl></section>   

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

