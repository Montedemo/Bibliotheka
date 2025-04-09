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
 <section class="wa-section main-content"><p><span class="dropcap">P</span>EQUEÑA serranía situada en el límite occidental de los <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="dce691b0-4783-4b83-86ca-801f4453bb41" data-template-type="location" data-article="dce691b0-4783-4b83-86ca-801f4453bb41">Monegros</span> en el <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="15b4db11-0e8f-474b-9d4e-cc8d28ffeb20" data-template-type="organization" data-article="15b4db11-0e8f-474b-9d4e-cc8d28ffeb20">Reino de Aragón</span>. Se extiende a lo largo de 40 kms en el límite entre las tierras de <span data-article-privacy="private" data-article-id="c007a6e5-30f6-4291-80b3-f2310a823075" data-template-type="settlement" class="private-article article-unlinked entity-link wa-link">Zaragoza</span> y <span data-article-privacy="private" data-article-id="3b5ae0d5-ba1b-43a0-ae15-f05b3f5aa10f" data-template-type="settlement" class="private-article article-unlinked entity-link wa-link">Huesca</span>, desde los Llanos de la Violada hasta las cercanías de La Almolda.
</p><div id="333ccf0e1b243829399c4d1989d0be5d" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/10e9cdc83be23ad0c4a03aa05bbf3204.png" alt title="alcubierre01.png" /></div>
 
<hr /><p></p></section>  <section data-section-id="geography" class="wa-section public"><h2>Geography</h2>
<p>Constituye una zona subdesértica, siendo el relieve más destacado del <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="84ca6161-c564-4375-b8b7-396a6b833b99" data-template-type="location" data-article="84ca6161-c564-4375-b8b7-396a6b833b99">Valle de Hiberia</span>. Forma la divisoria de aguas entre la cuenca inferior del río Gállego y la del río Flumen. Los agentes naturales externos —agua y viento fundamentalmente— han configurado un paisaje de lomas, pequeños relieves tabulares, áreas llanas a veces endorreicas, barrancos y cárcavas y típicos valles de fondo plano, sin cauces definidos.
<br />
Sus mayores alturas son la <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="54a40522-6c82-4bcb-a867-ebbe82429d2a" data-template-type="location" data-article="54a40522-6c82-4bcb-a867-ebbe82429d2a">Ermita de San Caprasio</span>, de 834 metros, y el <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="3ed70298-5fd6-4a35-86e4-f9a5dd834a54" data-template-type="location" data-article="3ed70298-5fd6-4a35-86e4-f9a5dd834a54">Monte Oscuro</span>, con 824 metros. Otras alturas importantes son Torre Ventosa (786 m), la Manadilla (703 m), Puig Ladrón (699 m), la Corona de la Reina (629 m) y el Vedado (552 m), ambas estas últimas al norte de la sierra.
<br />
Esta serranía comprende a su vez la Sierra Alta de Leciñena, los Montes de Perdiguera, la Sierra de Lanaja, la Sierra de Pallaruelo, la Sierra de Farlé, y la Sierra de Santa Quiteria, en orden de Noroeste a Sureste.
</p><div id="4dd26d3b5f455ce23206f75dcef596ac" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/620f5cd26fc9dd2dd44dd99ea28b1931.png" alt title="ermita de san caprasio.png" /></div>
 
<hr /><p></p><hr /></section><section data-section-id="naturalresources" class="wa-section public"><h2>Naturalresources</h2>
<p>La madera de dichos árboles es muy apreciada para la construcción naval y periódicamente partidas de leñadores vienen para talar árboles y llevarlos, via Ebro, hacia Zaragoza o hacia Tortosa.</p><hr /></section><section data-section-id="history" class="wa-section public"><h2>History</h2>
<p>La sierra toma su nombre de un termino de origen ibérico arabizado que significa "lomas o colinas separadas". Aunque habitado desde antiguo nunca ha sido un lugar atractivo para el florecimiento de comunidades humanas, siendo destino buscado por ermitaños y anacoretas para retirarse del mundo al ser un lugar desierto cercano a los grandes núcleos urbanos de <span data-article-privacy="private" data-article-id="c007a6e5-30f6-4291-80b3-f2310a823075" data-template-type="settlement" class="private-article article-unlinked entity-link wa-link">Zaragoza</span> y <span data-article-privacy="private" data-article-id="3b5ae0d5-ba1b-43a0-ae15-f05b3f5aa10f" data-template-type="settlement" class="private-article article-unlinked entity-link wa-link">Huesca</span>, ya que apenas es transitado por otras gentes que pastores y leñadores. 
</p><div id="54f41e9ba344ca3004bd5779eee75cac" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/9e6679319cf8de8beae8df37a0eb0f56.png" alt title="alcubierre02.png" /></div><p></p><hr /></section><section data-section-id="florafauna" class="wa-section public"><h2>Florafauna</h2>
<p>Esta serranía está poblada de frondosos bosques sobre todo de milenarias sabinas -formaciones que eran acompañadas de carrascas (como se conoce en Aragón a la encina), quejigos, madroños o enebros. Asimismo, de este hecho en relación con la gran calidad y espesura de sus bosques, deriva el nombre de Monegros ("Mons negros" [sic] Montes negros). Muchos árboles están siendo talados para la construcción naval, pero susbsisten muchos ejemplares monumentales.</p><hr /></section>   

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

