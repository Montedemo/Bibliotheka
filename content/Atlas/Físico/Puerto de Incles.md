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
 <section class="wa-section main-content"><p><span class="dropcap">P</span>ASO montañoso de los <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="cb40d9c8-1edb-439a-943c-523f8af04972" data-template-type="location" data-article="cb40d9c8-1edb-439a-943c-523f8af04972">Pirineos Centrales</span> entre los <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="18ce02b0-3c11-413e-ad34-b81b376c753d" data-template-type="location" data-article="18ce02b0-3c11-413e-ad34-b81b376c753d">Valles de Andorra</span> y el <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="10eee935-c213-4308-8af4-73b1d428b1ec" data-template-type="location" data-article="10eee935-c213-4308-8af4-73b1d428b1ec">Savarthès</span> enclavado en el punto más bajo de la frontera entre ambos, entre los picos de <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="b20c35a5-302a-4aed-a638-7cb556ba9ee3" data-template-type="location" data-article="b20c35a5-302a-4aed-a638-7cb556ba9ee3">L'Anrondat</span> y la <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="e1547cf1-4539-45e0-87e2-216670a43a05" data-template-type="location" data-article="e1547cf1-4539-45e0-87e2-216670a43a05">Font Argenta</span> en la <span data-article-privacy="private" data-article-id="a22a76f2-5b76-483c-bde4-4fa9be611bd1" data-template-type="location" class="private-article article-unlinked entity-link wa-link">Sierra de Astan</span>.
</p><div id="17f4644409bc3ccee593e591d31def99" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/15e0d0822d350905df97267203e7a161.png" alt title="Port d'Incles.png" /></div>
<hr /><p></p></section>  <section data-section-id="alternativename" class="wa-section public"><dl><dt>Alternativename</dt><dd>Port de la Font Argenta</dd></dl></section>   

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

