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
 <section class="wa-section main-content"><p>También llamado Mons Albinus -forma latina original que alude al color blanco de sus paredes de roca-, es un pequeño macizo montañoso del norte de Spania que se encuentra situado en el centro de los montes Vindios, a caballo entre los reinos de Asturias y León.</p></section>  <section data-section-id="sidebarcontent" class="wa-section public"><dl><dt>General Details</dt><dd><div id="0a112ce8f95df9a6ad2233daef7adc24" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/27b3c7e91867b647c4c632a93ba6fc6b.png" alt title="1024px-Peña_Ubiña_1.png" /></div></dd></dl></section><section data-section-id="alternativename" class="wa-section public"><dl><dt>Alternativename</dt><dd>Monte Albino, Mons Albinus, Agueria, Ubina, Obina</dd></dl></section><section data-section-id="geography" class="wa-section public"><h2>Geography</h2>
<p>En el macizo se sitúan 58 cumbres de más de 2000 m de altitud como Peña Ubiña (2417 m), que da nombre al macizo, Peña Rueda (2155 m), imponente mole caliza de forma piramida, sin olvidar el techo del macizo, los Picos del Fontán, con sus 2417 m, el Prau Fontán (2367 m), El Siete (2356 m) o El Crestón del Pasu Malu (2377 m), constituyendo la segunda mayor altura de la cornisa cantábrica después de los Montes <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="1a3c5c3a-8006-4097-aeee-78e85ad17b03" data-template-type="location" data-article="1a3c5c3a-8006-4097-aeee-78e85ad17b03">Vindio, M.</span></p><hr /></section><section data-section-id="history" class="wa-section public"><h2>History</h2>
<p>A pesar de su altitud, es una zona habitada desde tiempos inmemoriales, como atestiguan los Abrigos Rupestres de Fresnedo, cercanos al pueblo de Fresnedo (Teverga), los castros de Focella y Barrio (Teverga) o Ricabo y El Collao (Quirós). Los yacimientos vinculados a la Vía de La Carisa y las fortificaciones visigodas del Homón de Faro (Lena).
<br />
En este parque también está presente el Camino Real del Puerto de la Mesa, calzada romana asentada sobre una senda ya utilizada por los primero pobladores de la zona.</p><hr /></section><section data-section-id="florafauna" class="wa-section public"><h2>Florafauna</h2>
<p>Los bosques, abundantes, tienen predominio de haya, roble y abedules, y vegetación de alta montaña. En la zona de los Puertos de Aguería se encuentra el mayor bosque de acebo de Asturias.
<br />
En el macizo de las Ubiñas está presente la fauna propia de la cornisa cantábrica: ciervo, jabalí, lobo, venado, rebeco y corzo, nutria, urogallo y el oso pardo.</p><hr /></section>   

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

