---
NoteIcon: geotierra
tags:
  - Geography 
  - land 
categoria: Formación Terrestre
clase: Cordillera 
tipo: Sierra 
location: 
aura:
  - reinodpoder1
  - reinodpoder2
propietario: dueño
disputado: conflicto
region:  
  - Picardía 
  - Reims 
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

En marcado contraste con la civilización cultivada de Reims, se encuentra un bosque salvaje y montañoso que comienza inmediatamente al sur de la ciudad, extendiéndose hacia el valle del río Marne y con una extensión de 25 millas. Las tierras de [Champaña](app://obsidian.md/2.%20Geograf%C3%ADa%20%F0%9F%8C%8D/Politico/2.%20Vasallos/Champa%C3%B1a) se inician al otro lado. Los árboles cubren densamente un altiplano de piedra caliza con una geografía irregular, llena de pequeños lagos, ríos subterráneos y abismos. Esto hace que estos bosques, a diferencia del [Bosque de Cuise](app://obsidian.md/Bosque%20de%20Cuise), sean poco adecuados para la caza, una actividad que tampoco interesa a los arzobispos de Reims. Como resultado, todo tipo de bestias salvajes deambulan con relativa impunidad. La Montaña de Reims alberga varios sitios peculiares y fuentes de vis.

**El Bosque de San Lie**  
En lo alto de una cresta en el borde norte del bosque, con una vista imponente de Reims y la llanura circundante, hay un antiguo túmulo funerario rodeado por un bosque de robles. Este lugar tranquilo tiene una pequeña capilla dedicada a San Lie, un ermitaño del siglo V. Las flores pálidas que crecen en el túmulo pueden cosecharse para obtener algunas peones de vis Creo, lo que constituye un _tropaeum_.

**El Bosque Retorcido de Verzy**  
En las zonas orientales del bosque se encuentra un bosquecillo siniestro de hayas negras deformes, torcidas y atrofiadas. Este lugar, que tiene un aura feérica de 4, es evitado por los campesinos de los alrededores. Según algunas historias, los aldeanos que se adentran en él son capturados por un oscuro pueblo de aspecto enano. Al regresar, están marcados con alguna deformidad y se niegan a hablar sobre su experiencia.

**Nanteuil**  
Cerca del centro del bosque hay un valle remoto donde los Caballeros Templarios han fundado un priorato. Este es un lugar decididamente extraño para establecer tal institución, ya que es muy difícil de alcanzar y no parece conducir a ningún lado. En los escritos del mago Norlanus se menciona que una vez visitó el sitio y encontró que era un _regio_, posiblemente de origen Divino. Al salir del priorato como huésped, escribió que se encontró en una versión completamente diferente y más luminosa del bosque. Otros, sin embargo, afirman que Norlanus simplemente experimentó un episodio potente de Crepúsculo.

**La Abadía de Hautvillers**  
No muy lejos de la orilla norte del río Marne se encuentra Hautvillers, fundada en 660 por San Nivardo. Hay una gran iglesia abacial en un lugar apartado e idílico, rodeada de viñedos. Este monasterio es ahora una rama de la escuela de Reims, y se producen allí algunos de los manuscritos más magníficamente decorados de la región. A unas pocas millas río arriba está la antigua ciudad gala de Ay, una pequeña comunidad de viticultores con una residencia real que es visitada ocasionalmente por los Reyes de Francia.
