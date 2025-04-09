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
 <section class="wa-section main-content"><p>Macizo e importante cumbre de los Pirineos Centrales, divisoria entre los condados de Sobrarbe y Bigorra. Su cumbre -la Grand Vinhamala o Pica Longa más alta de la vertiente septentrional de los Pirineos. En aragonés se conoce como Comachibosa.</p></section>  <section data-section-id="alternativename" class="wa-section public"><dl><dt>Alternativename</dt><dd>Comachibosa, Camagibosa, Binha Mala</dd></dl></section><section data-section-id="geography" class="wa-section public"><h2>Geography</h2>
<p>Vinhamala es lo nom donat al massís entièr que s'espandís entre Aragon e Bigorra. Es format de divèrses soms, que los màgers son lo Grand Vinhamala o Pica Longa (3298 m), la Punta Chausenca (3204 m) e lo Petit Vinhamala (3032 m). Lo Vinhamala es tanben lo site del pus bèl glacièr pirenenc - lo glacièr d'Osso - qu'es la via normala cap a la cima de Vinhamala.</p><hr /></section><section data-section-id="history" class="wa-section public"><h2>History</h2>
<p>El nombre no parece tener origen en viñedos, sino en la malinterpretación de un topónimo prerromano, "bigna" o cumbre y que vendría a significar. la Cumbre Malvada, algo que también recordaría el nombre aragonés del mismo lugar: Comagibosa, "cumbre jorobada", dado que el vulgo atribuye los defectos físicos como las jorobas a las personas malvadas. 
</p>
<p>
Este término sería dado por los pastores gascones y aragoneses a un macizo de difícil acceso, aludes traicioneros, fuertes vientos y donde es fácil perderse, como forma de aviso y precaución.</p><hr /></section>   

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

