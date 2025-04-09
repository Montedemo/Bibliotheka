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
 <section class="wa-section main-content"><p>Los montes Carpetanos son una larga cadena montañosa situada en el centro de la <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="5ff3ea64-57a9-4e12-8823-322e90f3be82" data-template-type="location" data-article="5ff3ea64-57a9-4e12-8823-322e90f3be82">Spania</span> formando prácticamente un eje suroeste-noreste que la divide en dos mitades, norte y sur. Tienen una longitud aproximada de 400 km y se extiende desde el valle del río Alagón, afluente del Tajo y que los separa de su continuación, los <span data-article-privacy="private" data-article-id="87d18655-2535-4755-a914-2a62d932c16c" data-template-type="location" class="private-article article-unlinked entity-link wa-link">Vettones, M.</span>, hasta los montes de <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="2ea4c137-062c-4eff-806d-a2f3d6479d8f" data-template-type="location" data-article="2ea4c137-062c-4eff-806d-a2f3d6479d8f">Idubeda</span> en el centro-noreste de <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="5ff3ea64-57a9-4e12-8823-322e90f3be82" data-template-type="location" data-article="5ff3ea64-57a9-4e12-8823-322e90f3be82">Spania</span>. Constituye la separación natural entre los reinos de Castilla y de Toledo, y también forman divisoria entre las cuencas de los ríos Duero y Tajo.
La mayor elevación del sistema es el pico Almanzor (2592 m sobre el nivel del mar), situado en los <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="8778a0c6-e307-403d-81be-4d7f8e46e3fa" data-template-type="location" data-article="8778a0c6-e307-403d-81be-4d7f8e46e3fa">Montes Cretos</span>. La cordillera es un encadenamiento de sierras sucesivas, separadas  entre sí por grandes valles o puertos de montaña. De todas ellas, las más importantes por extensión son las siguientes, ordenadas de oeste a este: Cretos, Guadarrama y Ayllón. La base de estas montañas oscila de los 500 a 1200 metros.</p></section>  <section data-section-id="alternativename" class="wa-section public"><dl><dt>Alternativename</dt><dd>Transierra</dd></dl></section><section data-section-id="geography" class="wa-section public"><h2>Geography</h2>
<p>El término "montes Carpetanos" es un término académico pues no es compartido por los habitantes de la zona, los cuales se refieren a las diferentes sierras de las que se compone la cordillera y no tienen conciencia de un todo. Enumeradas de oeste a este, las sierras son las siguientes:
</p><ul>
<li>Sierra de Gredos, en Ávila y Cáceres (Pico Almanzor, 2592 m).</li>
<li>Sierra de la Horcajada, en Ávila (Risco de la Umbrela, 1562 m).</li>
<li>Sierra de Villafranca, en Ávila (Cerro Moros, 2059 m).</li>
<li>Sierra de Piedra Aguda, en Ávila (Piedra Aguda, 1817 m).</li>
<li>La Serrota, en Ávila (Serrota, 2294 m).</li>
<li>Sierra de Hoyocasero, en Ávila (Navasolana, 1708 m).</li>
<li>Sierra de la Paramera, en Ávila (Pico Zapatero, 2160 m).</li>
<li>Sierra de Ávila, en Ávila (Cerro de Gorría, 1727 m).</li>
<li>Sierra de Ojos Albos, en Ávila y Segovia (Cruz de Hierro, 1657 m).</li>
<li>Sierra de San Vicente, en Toledo (Cruces, 1373 m).</li>
<li>Sierra de Guadarrama, en Ávila, Madrid y Segovia (Peñalara, 2428 m).</li>
<li>La Mujer Muerta, en Segovia (La Pinareja, 2197 m)).</li>
<li>Siete Picos, en Segovia y Madrid (Siete Picos, 2138 m).</li>
<li>La Maliciosa, en Madrid (Maliciosa, 2227 m).</li>
<li>Cuerda Larga, en Madrid (Cabeza de Hierro Mayor, 2383 m).</li>
<li>Sierra de Malagón, en Ávila, Madrid y Segovia (Cueva Valiente, 1903 m).</li>
<li>Sierra de la Morcuera, en Madrid (La Najarra, 2122 m).</li>
<li>Sierra de Canencia, en Madrid (Mondalindo, 1831 m).</li>
<li>Sierra de la Cabrera, en Madrid (Cancho Gordo, 1564 m).</li>
<li>Sierra de Somosierra, en Segovia y Madrid (Colgadizos, 1834 m).</li>
<li>Sierra de Ayllón, en Segovia, Madrid y Guadalajara (Pico del Lobo, 2274 m).</li>
<li>Sierra de la Puebla, en Madrid y Guadalajara (La Tornera, 1866 m).</li>
<li>Sierra de Ocejón, en Guadalajara (Ocejón, 2049 m).</li>
<li>Sierra de Alto Rey, en Guadalajara (Alto Rey, 1858 m).</li>
<li>Sierra de Pela, en Guadalajara y Soria (Sima de Somolinos, 1548 m).</li>
</ul>
Las sierras más extensas e importantes del sistema Central son las de la Estrella, la de Gata y la de Gredos en la mitad occidental, y la de Guadarrama y la de Ayllón en la mitad oriental. La cordillera enlaza en su extremo este con el sistema Ibérico a través de la sierra de Pela, los Altos de Baraona y sierra Ministra.<p></p><hr /></section>   

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

