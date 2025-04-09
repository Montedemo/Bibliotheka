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
 <section class="wa-section main-content"><p>El monte Larrunarri o Ñañarri, de 1346 m de altitud, y situado en la sierra de Aralar (entre Guipúzcoa y Navarra), es uno de los montes más emblemáticos del territorio histórico guipuzcoano. A sus pies se sitúa la ermita de Nuestra Señora de los Remedios, en Larráiz, Guipúzcoa, muy venerada por los habitantes de los alrededores. La leyenda dice que en su cumbre "Mari", la diosa por excelencia del Olimpo Vasco, tiene una de sus residencias.</p></section>  <section data-section-id="alternativename" class="wa-section public"><dl><dt>Alternativename</dt><dd>Ñañarri, Txindoki</dd></dl></section><section data-section-id="geography" class="wa-section public"><h2>Geography</h2>
<p>Visible desde muchos puntos del País Vasco, es el referente de la sierra de Aralar. Marca uno de sus límites, y bajo su cumbre se extienden las campas donde pastan multitud de rebaños de ovejas. Su afilado pico de caliza y su emblemática arista se alzan sobre el entorno verde de los extensos pastizales y bosques de hoja caduca.
<br />
Su nombre es Larrunarri o Larrunari, y su contracción Ñañarri, pero también se le conoce como Txindoki, nombre de una borda de pastores que se sitúa a los pies de la cumbre, al este, en terrenos de Amézqueta.
<br />
La mole caliza se alza a 1000 m sobre el santuario de Larraitz, que está a 401 m de altitud. Quedan visibles la arista y el barranco, poblado de bosque autóctono, que caen desde la cumbre.
<br />
El terreno calizo hace su aparición con multitud de acumulaciones de rocas. El paisaje toma el aspecto típico de las zonas kársticas y se llena de pequeñas construcciones, escondidas en las depresiones del terreno y entre los escasos árboles, que suelen habitar los pastores de ovejas en las temporadas que mantienen sus rebaños en las campas de Aralar.</p><hr /></section><section data-section-id="history" class="wa-section public"><h2>History</h2>
<p>Los alrededores del Larrunarri están llenos de monumentos megalíticos que son testimonio de la ocupación de estas tierras desde la prehistoria. Los dólmenes, menhires y túmulos jalonan las campas de Aralar recordando que, en el pasado, había habitantes que se mantenían de la caza y el pastoreo por estas mismas campas donde hoy siguen pastando las ovejas.</p><hr /></section><section data-section-id="florafauna" class="wa-section public"><h2>Florafauna</h2>
<p>La vegetación está formada por robles, hayas, espinos albares y un sinfín de árboles de las latitudes cantábricas, que van dejando paso a los pastos según se gana altura.
</p>
<p>
Abundan el jabalí y el venado, aunque son difíciles de ver, siendo el lobo el depredador rey, junto al cada vez más raro de ver oso. Los buitres y los cuervos son las aves más abundantes, además de otras rapaces.</p><hr /></section><section data-section-id="localizedPhenomena" class="wa-section public"><h2>Localizedphenomena</h2>
<p>Una de las moradas de <span data-article-privacy="private" data-article-id="4dfa4398-fb35-4370-b7ba-797f7632a826" data-template-type="person" class="private-article article-unlinked entity-link wa-link">La Mari</span> está en esta montaña, que alterna con otras como el Amboto, el Oiz o el Aketegi. Y no es de extrañar que haya elegido este monte para su ubicación. No en vano su afilado pico es visible desde cualquier parte del país, y desde él se divisan todas las otras cumbres que sirven de morada a esta mítica diosa.
</p>
<p>
A sus pies, los hombres y mujeres que residen a la sombra de la cumbre le prestan devoción y ofrendas, ya que a la mediación de la Mari se le atribuyen toda clase de logros y milagros. No obstante los clérigos locales insisten en que tales obras han de ser atribuidas a la mediación de la misericordiosa Señora de los Remedios.</p><hr /></section>   

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

