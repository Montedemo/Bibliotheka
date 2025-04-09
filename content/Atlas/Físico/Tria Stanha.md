---
NoteIcon: geoagua
tags:
  - Geography 
categoria: Formación Terrestre/Acuática
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
 <section class="wa-section main-content"><p><span class="dropcap">C</span>ONJUNTO de lagos glaciares en el alto valle circular del mismo nombre, en el límite noroeste de Andorra, donde nace el río <span data-article-privacy="private" data-article-id="b934b8c1-35aa-4032-8625-8528c2594361" data-template-type="location" class="private-article article-unlinked entity-link wa-link">Valira del Nort</span>. Es un paraje de excepcional belleza, origen de un buen número de leyendas. El lugar es atravesado por rebaños estivales y viajeros que lo cruzan tras o después de atravesar los puertos de L'Albelha y Tristaina.
</p><div id="c71fbc553d14829d1fbdc1839da2e6d0" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/eb08876208c6846cc6a0d3b94a08e054.jpeg" alt title="tristaina.jpeg" /></div>
<hr /><h3>Descripción</h3>
<div id="8dcd18af9c9c006df389f5352103d0c9" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/9baa34ae64bf013bf67940108dd45dc9.jpg" alt title="1280px-Tristaina_43.jpg" /></div>
<hr /><h3>Habitantes</h3>
<p></p>
<p>
</p><div id="e07be07309b298cb8541c3d6dc714082" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/81cf3b50a97c4659692ce40d42354a6f.jpeg" alt title="Estanys-de-Tristaina-2.jpeg" /></div>
<hr /><h3>Ideas para relatos</h3>
<div id="a0a23d49a7d894d0205a6e5401eed5d4" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/eb16cd0a183998f146c1a199300b4f57.jpeg" alt title="Du-Port-de-l'Albeille.jpeg" /></div><p></p></section>  <section data-section-id="sidebarcontent" class="wa-section public"><dl><dt>General Details</dt><dd><div id="5de36363f7e03eb4c2cc6a946b3405b5" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/22dc5353613c5190e731dd2e93bf67dc.jpeg" alt title="Estanys-de-Tristaina.jpeg" /></div></dd></dl></section><section data-section-id="sidepanelcontent" class="wa-section public"><dl><dt>General Details</dt><dd><div class="visibility-toggler" id="6ed3cf13906dc93a2f205a19e122c640"> 
          </div></dd><dt class="phrase-key">Aura</dt>
          <dd class="phrase-value"> Feérica </dd>
        </dl></section><section data-section-id="alternativename" class="wa-section public"><dl><dt>Alternativename</dt><dd>Tristaina, Tristanha</dd></dl></section>   

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

