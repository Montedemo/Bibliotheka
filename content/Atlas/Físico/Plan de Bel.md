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
 <section class="wa-section main-content"><p>LLANURA elevada en el centro del <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="82254c47-60d6-46b2-a9b2-309bac60aea8" data-template-type="location" data-article="82254c47-60d6-46b2-a9b2-309bac60aea8">altiplano de Bel</span>, una amplia muela horadada por múltiples barrancos, cárcavas y cortados. Bel es un hito geográfico que sirve de divisoria entre el país de Sabarthès y el Lordadais y constituye un paisaje por sus suave relieve de comas cubiertas de prados y salpicadas de bosquecillos abiertos. Abierta a los cuatro vientos, Bel tiene una excepcional panorámica de las montañas alrededor, con la cresta de los Pirineos al sur y los montes de Tava al norte.
</p>
<p>
</p><div id="27aa36f8da3fb5e580a94610f7ebad6a" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/543d279390228b71e78d1bc1766272fc.jpeg" alt title="plan de bel.jpeg" /></div>
<hr /><p></p></section>  <section data-section-id="sidepanelcontent" class="wa-section public"><dl><dt>General Details</dt><dd><div class="visibility-toggler" id="5e3f2d3ac76ce09d46f639b6886255b7"> 
          </div></dd><dt class="phrase-key">Altitud de la cumbre</dt>
          <dd class="phrase-value"> 2610 m. </dd>
         
--Altitud media de la muela:1700 m.--</dl></section><section data-section-id="geography" class="wa-section public"><h2>Geography</h2>
<p>El plan de Bel se alza en el centro de una muela o altiplano macizo cortado por los angostos valles del <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="b311c872-59bd-4a54-a26c-8e85de6fb223" data-template-type="location" data-article="b311c872-59bd-4a54-a26c-8e85de6fb223">Río Astón</span> y<span data-article-privacy="private" data-article-id="4e7a35a7-68aa-44b5-92c5-f74fc74cf613" data-template-type="location" class="private-article article-unlinked entity-link wa-link">Arroyo de la Vall</span>al oeste y al este respectivamente, y por el propio <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="cbdd5b43-1a4e-4b3b-bcad-67ecb60f704d" data-template-type="location" data-article="cbdd5b43-1a4e-4b3b-bcad-67ecb60f704d">Arièja</span> al norte, cuyo valle se estrecha considerablemente a su sombra. Dicha muela está delimitada por cuatro escarpados espolones que terminan en abruptos cortados sobre dichos ríos.
<br />
Estos son, al norte, mirando al Arièja.
<span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="dfac0f3c-bb4e-4511-9e37-67915d1bb6b5" data-template-type="location" data-article="dfac0f3c-bb4e-4511-9e37-67915d1bb6b5">Sarrat del Auzels</span>
Mont Rodon
<span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="7b50285d-9ada-4e7e-8748-031e7d7aeee6" data-template-type="location" data-article="7b50285d-9ada-4e7e-8748-031e7d7aeee6">Mont Agut</span>
</p><div id="89f86ae594ede1b58964c58ad67246d3" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/f46fea4f5e9162b3a5b49821e13870c7.png" alt title="Macizo de Bel.png" /></div><p></p><hr /></section><section data-section-id="tourism" class="wa-section public"><h2>Tourism</h2>
<p>El lugar es frecuentemente visitado por magos del Tribunal Provenzal e Ibérico, atraídos por la curiosidad de experimentar su poderosa aura mágica, y el importante foco de poder que representa.</p><hr /></section><section data-section-id="florafauna" class="wa-section public"><h2>Florafauna</h2>
<p>Existe un tipo de cabra montesa particular que solo se ve en el Laparan, de gran tamaño (algunos ejemplares pueden alcanzar el de un asno pequeño), cuernos finos, pelaje pardo rojizo y cuatros traseros listados. Tiene poco que ver con las cabras pirenaicas locales -ausentes aquí. Excelentes trepadoras, pueden acceder por todos los rincones y recovecos de la escarpada montaña.</p><hr /></section>   

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

