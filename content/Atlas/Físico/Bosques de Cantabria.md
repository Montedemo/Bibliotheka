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
 <section class="wa-section main-content"><p>Esta feraz tierra septentrional queda compuesta por un manchón de terrenos antiguos extendidos al Este del <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="1a3c5c3a-8006-4097-aeee-78e85ad17b03" data-template-type="location" data-article="1a3c5c3a-8006-4097-aeee-78e85ad17b03">Monte Vindio</span> hasta enlazar con los <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="53792d76-7259-443a-a6ce-9b9cf0698386" data-template-type="location" data-article="53792d76-7259-443a-a6ce-9b9cf0698386">Pirineos</span>, formando un arco amesetado de tierras agrestes, afiligranado tan hondamente por la erosión que ha contribuido al aislamiento secular de sus habitantes. No obstante, la extensión del arbolado no es uniforme y se abre en numerosos claros y pastizales, donde se ubican pequeñas aldeas y caseríos familiares, con lo que en suma se trata de un territorio muy poblado aunque de habitat disperso y de muy original carácter.</p></section>  <section data-section-id="geography" class="wa-section public"><dl><dt>Geography</dt><dd>País de clima marítimo, brumoso, suave, explicación de la hondura espiritual de su paisaje.</dd></dl></section><section data-section-id="history" class="wa-section public"><h2>History</h2>
<p>Se corresponde exactamente con la provincia visigótica de Cantabria, si bien no fue habitada íntegramente por los cántabros, sino también por los autrigones, caristios y várdulos, siendo desplazados estos últimos por los vascones en su expansión a finales de época romana.</p><hr /></section><section data-section-id="florafauna" class="wa-section public"><dl><dt>Florafauna</dt><dd>Vegetación de los bosques boreales, con prados, robles, brezos.</dd></dl></section>   

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

