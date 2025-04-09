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
 <section class="wa-section main-content"><p><span class="dropcap">C</span>UMBRE pirenaica de 2730 m, parte de la <span data-article-privacy="private" data-article-id="a22a76f2-5b76-483c-bde4-4fa9be611bd1" data-template-type="location" class="private-article article-unlinked entity-link wa-link">Sierra de Astan</span> en la divisoria entre los <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="18ce02b0-3c11-413e-ad34-b81b376c753d" data-template-type="location" data-article="18ce02b0-3c11-413e-ad34-b81b376c753d">Valles de Andorra</span> y el <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="10eee935-c213-4308-8af4-73b1d428b1ec" data-template-type="location" data-article="10eee935-c213-4308-8af4-73b1d428b1ec">Savarthès</span>.
</p><div id="e4ca2c3f59bbc1e4f130f4cd5467b35b" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/f2ff13f675abeca2607271e0e52f8658.jpeg" alt title="l'anrondat 2.jpeg" /></div><p></p></section>  <section data-section-id="sidebarcontent" class="wa-section public"><dl><dt>General Details</dt><dd><div id="aff39cbea2ce66e56f9ebb4295f9ed69" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/2ec213769f6848da5851463e8d93d88e.jpeg" alt title="pic de l'anrondat.jpeg" /></div></dd></dl></section><section data-section-id="sidepanelcontenttop" class="wa-section public"><dl><dt>General Details</dt><dd><b>Altitud</b>
<br />2730 m.</dd></dl></section><section data-section-id="sidepanelcontent" class="wa-section public"><dl><dt>General Details</dt><dd><div id="0d5560948394b3519992ab40edb5f1c0" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/25a11d1a432b1a2ffcdfc7b4b1fc37a5.jpeg" alt title="anrondat y l'isle.jpeg" /></div>
<div id="23ce8aca15cd3e3be27ceb660664a66f" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/561d65638e512a612cb185bc9249039f.jpeg" alt title="collado de anrondat.jpeg" /></div></dd></dl></section><section data-section-id="alternativename" class="wa-section public"><dl><dt>Alternativename</dt><dd>l'Ancorat</dd></dl></section><section data-section-id="geography" class="wa-section public"><h2>Geography</h2>
<p>Esta cumbre pirenaica conforma junto con su hermana menor, Fontargenta, una clara divisoria entre las tierras de los condados de Fois y de Urgel a ambas pendientes. El collado de l'Anrondat separa visualmente su cumbre de la de Font Argenta, cuyo perfil esta última parece replicar a menor altura. El collado permite también el paso de la frontera pero es mucho más escarpado que el <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="952fff6a-d594-4eb5-abd0-a8c97abe7000" data-template-type="location" data-article="952fff6a-d594-4eb5-abd0-a8c97abe7000">Puerto de Incles</span>.
<br />
En la vertiente sur, se encuentra el curioso paisaje del Estany de l'Ilha, estanque glaciar pirenaico con una gran isla concéntrica. Bordea este estanque por el oeste una cumbre menor del macizo, la Tossa de les Mussoles.
<br />
En su ombría se encuentra el extraño espolón de roca que apunta en dirección norte conocido como el <span data-article-privacy="private" data-article-id="bed5c40d-71fe-4e5b-a5b5-7b7f705c5432" data-template-type="location" class="private-article article-unlinked entity-link wa-link">Caireforc dels Vents</span> o la Coma de l'Infern, nombre por el que es también conocida la montaña en las tierras del Savarthés.</p><hr /></section><section data-section-id="history" class="wa-section public"><h2>History</h2>
<p>Debe su nombre (enredado, anclado) a la leyenda que atribuye su pico como aquel donde Noé encayó con el arca, aunque la iglesia local matiza que solo "rozó" con su casco la cumbre, para evitar la confusión con el monte Ararat de Armenia, donde la biblia sitúa el encayamiento. No obstante, solo en los <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="18ce02b0-3c11-413e-ad34-b81b376c753d" data-template-type="location" data-article="18ce02b0-3c11-413e-ad34-b81b376c753d">Valles de Andorra</span> se cuenta esta leyenda. En el Savarthès muchos llaman a esta montaña el Pic de Coma de l'Infer o del <span data-article-privacy="private" data-article-id="bed5c40d-71fe-4e5b-a5b5-7b7f705c5432" data-template-type="location" class="private-article article-unlinked entity-link wa-link">Caireforc dels Vents</span>, al encotrarse esta singular formación en su ladera norte.</p><hr /></section>   

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

