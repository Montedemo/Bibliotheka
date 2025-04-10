---
tags: Category/state
categoria: institución política/administrativa/eclesiástica
clase: estado soberano, estado vasallo, demarcaciòn, comarca
tipo: reino, ducado, condado, marca, provincia, región, comarca, valle, alfoz
Denomyn: gentilicio
location: unidad geográfica que lo engloba totalmente
capital: ciudad principal o sede de la corte
leader: personaje histórico
titulo: rey, duque, conde, etc.
superior: jerárquico
organizacion: estado o confederación al que pertenece
disputado: por otro estado
gobierno: monarquía feudal, república
estructura: sistema feudal, tributario, burocrático
economia: feudal, mercantil
moneda: dinero, dinares, besantes
religion: catolicismo, sunna, ortodoxo
lengua: 
- idioma oficial,
- idioma oficial, 
- otro
etnias: 
- etnia predominante
- otra
founded: "año"
disbanded: "año"
founder: personaje histórico
predecesor: estado desaparecido
sucesor: estado por aparecer
NoteIcon: state
---

> [!infobox]
> # `=this.file.name`
> ![[armas.png]]
> ###### `=this.clase` 
>  |   |
> ---|---|
> Rango |  `=this.tipo`|
> Localización | `=this.location`|
> Capital | `=this.capital`|
> Gentilicio | `=this.Denomyn`|
> ###### Política  
>  |   |
> ---|---|
> Gobernante | `=this.leader`|
> Título | `=this.titulo`|
> Vasallo de | `=this.superior`|
> Parte de | `=this.organizacion`|
> Disputado por | `=this.disputado`|
> Sistema de gobierno | `=this.gobierno`|
> Sistema de poder | `=this.estructura`|
> Sistema económico | `=this.economia`|
> Moneda: | `=this.moneda`|
> Religión oficial | `=this.religion`|
> Lengua oficial | `=this.lengua`|
> Etnias | `=this.etnias`|
> ###### Historia 
>  |   |
> ---|---|
> Fundador/es | `=this.founder`|
> Fundado en | `=this.founded`|
> Disuelto en | `=this.disbanded`|
> Heredero de | `=this.predecesor`|
>Predecesor de |  `=this.sucesor`|
> ###### Geografía 
> ![[MapPlaceholder.png|cover hsmall]]
> ###### Territorios
>```dataview
TABLE WITHOUT ID link(file.name) AS "Territorios", tipo, leader  
from "2. Geografía 🌍/Politico"
where contains( organizacion, this.file.name)
SORT file.name DESC
>```
>```dataview
TABLE WITHOUT ID link(file.name) AS "Vasallos", tipo, leader  
from "2. Geografía 🌍/Politico"
where contains( superior, this.file.name)
SORT file.name DESC
>```
>###### Poblaciones
> ```dataview
table WITHOUT ID link(file.name) AS "Población", clase
from "2. Geografía 🌍/Demografico"
where contains( region, this.file.name)
>```
>###### Organizaciones y grupos
> ```dataview
TABLE WITHOUT ID link(file.name) AS "Grupos", PrimaryHome
from "3. Personajes y Organizaciones 🧑‍🤝‍🧑/Grupos"
where contains( region, this.file.name)
SORT file.name DESC
>```
>###### Personalidades 
>```dataview
TABLE WITHOUT ID link(file.name) AS "Figuras", Titulo, ☠
from "3. Personajes y Organizaciones 🧑‍🤝‍🧑/Personajes/Historicos"
where contains( region, this.file.name)
SORT file.name DESC
>```
> ```dataview
TABLE WITHOUT ID link(file.name) AS "Otras", tipo, ☠
from "3. Personajes y Organizaciones 🧑‍🤝‍🧑/Personajes/PNJs"
where contains( region, this.file.name)
SORT file.name DESC
>```

> [!infobox ]+ Collapsible Infobox
>  # `=this.file.name` Mítica 
>```dataview
TABLE WITHOUT ID link(file.name) AS "Magi", Casa, Alianza
from "3. Personajes y Organizaciones 🧑‍🤝‍🧑/Personajes/Hermeticos"
where contains( region, this.file.name)
SORT file.name DESC
>```
>```dataview
table WITHOUT ID link(file.name) AS "Alianzas", PrimaryHome, Estacion
from "3. Personajes y Organizaciones 🧑‍🤝‍🧑/Grupos/1. Hermeticum/Alianzas"
where contains( region, this.file.name)
SORT file.name DESC
>```
> ```dataview
TABLE WITHOUT ID link(file.name) AS "Númenes", PrimaryHome, tipo, RdP
from "3. Personajes y Organizaciones 🧑‍🤝‍🧑/Personajes/Numina"
where contains( region, this.file.name)
SORT file.name DESC
>```
> ```dataview
TABLE WITHOUT ID link(file.name) AS "Bestiario", tipo, RdP
from "6. Bestiario 🐉"
where contains( region, this.file.name)
SORT file.name DESC
>```

# `=this.file.name`

 <section class="wa-section main-content"><p>Sector mediterráneo de la Galia, formado por los valles y ríos gálicos que desembocan en este mar, particularmente el <span data-article-privacy="private" data-article-id="ef5bd1ee-4062-4e1c-a97e-c43b8c959d6e" data-template-type="location" class="private-article article-unlinked entity-link wa-link">Ródano</span>. Recibe su nombre de la ciudad de <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="afe460c2-77df-4a8f-91e3-564c0d5509bb" data-template-type="settlement" data-article="afe460c2-77df-4a8f-91e3-564c0d5509bb">Narbona</span>, capital de la primera provincia romana fuera de Italia, o Provincia, asentada precisamente en la Galia Mediterránea, entre los <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="ee75ea35-701d-4d7f-a872-85bbfdd811d9" data-template-type="location" data-article="ee75ea35-701d-4d7f-a872-85bbfdd811d9">Alpes</span> y los <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="53792d76-7259-443a-a6ce-9b9cf0698386" data-template-type="location" data-article="53792d76-7259-443a-a6ce-9b9cf0698386">Pyrenaei</span> .</p></section>  <section data-section-id="geography" class="wa-section public"><h2>Geography</h2>
<p>El clima en las tierras altas centrales varía ampliamente. En las vertientes meridionales, el clima se templa con los vientos del Mediterráneo, que ascienden por el valle del <span data-article-privacy="private" data-article-id="ef5bd1ee-4062-4e1c-a97e-c43b8c959d6e" data-template-type="location" class="private-article article-unlinked entity-link wa-link">Ródano, río</span> proporcionando lluvia y vientos cálidos. De igual manera, las vertientes occidentales y septentrionales reciben lluvias considerables, aunque están sujetas a importantes variaciones de temperatura al estar más lejos del mar. Las tierras altas centrales, sin embargo, apenas reciben lluvia; los vientos son cortantes, los inviernos duros e incluso el verano en esta región es fresco. 
<br />
</p>
<p>
</p><h4>Septimania</h4>
Entre las tierras altas del centro-sur y el extremo sur del <span data-article-privacy="private" data-article-id="ef5bd1ee-4062-4e1c-a97e-c43b8c959d6e" data-template-type="location" class="private-article article-unlinked entity-link wa-link">Ródano, río</span> se extienden las pequeñas llanuras de de Provenza y Languedoc. Atrapadas entre los Pirineos y las tierras altas centrales de los Montes Arvernos, estas provincias estrechas están irrigadas por la escorrentía de sus sistemas montañosos contiguos. Sin embargo, estas provincias son muy fértiles -aunque no tanto como Aquitania- y están bendecidas con un clima cálido y benigno. No obstante, esta región está algo aislada el resto de Francia, y la gente es más independiente que en el resto, mostrando reluctancia al gobierno del rey de <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="d9f4bc26-8375-4019-a470-9b0b1e3a7fda" data-template-type="organization" data-article="d9f4bc26-8375-4019-a470-9b0b1e3a7fda">Francia</span> 
<br /><p></p><hr /></section>   

## Etymology
Origen del término.
***
## Política
...
### Estructura y organización
Definición de la jerarquía de títulos que la componen. Descripción de los principales roles y sus responsabilidades en la organización. 
### Agenda pública
Objetivos y motivación detrás de las acciones. 
### Relaciones exteriores
Relaciones diplomáticas establecidas.
### Leyes 
Normas escritas o no que rigen a la población. Los aspectos que incluyen son: crimen, propiedad, empleao, comercio, finanzas, impuestos, litigios y castigos. Quién crea las leyes y donde se guardan y documentan. Quién aplica la ley. Qué tipo de castigos se aplican a los infractores. Cómo de laxo o evitable es el largo brazo de la ley. 
### Ejército
Cuáles son las fuerzas militares o de seguridad de la organización, si las hay. Qué divisiones son signficativas. Se pueden enlazar a otras organizaciones geopolíticas o no. 
***
## Geografía
Describe los rasgos geográficos más remarcables.
### Relieve
El terreno es una llanura, una montaña o una serie de colinas. 
### Hidrografía
Principales cursos de agua que atraviesan el territorio. 
### Clima
### Naturaleza
Entorno natural y dinámicas que gobiernan el ecosistema de este lugar.  Cómo cambia el ecosismtema con el paso de las estaciones. Como reaccionan los organismos a este cambio (migraciones, hibernaciones, caza o apareamiento.) hay algún fenómeno natural, climatológico o sobrenatural que sea particular o distintivo (tormentas, inundaciones, terremotos, actividad volcánica, etc.)
#### Clima
Temperatura y tiempo atmosférico de la zona. Comportamientos habituales y extremos del clima. Nivel de predecibilidad del clima, de estacionalidad o de estabilidad. 
#### Fauna y Flora
Animales y plantas característicos de los espacios naturales. Información de su ecología e interacciones locales. 
***
## Society
### Población 
Cómo se divide la población en el territorio. Etnicidades, natalidad, mortandad, esperanza de vida. 
### Implantación
Territorios que ocupa y cual es el estado de ocupación. Cuáles son sus sus tierras ancestrales o las tomadas por la fuerza. Cómo han sido asimiladas o colonizadas. 
### Estratificación
Denominaciones, naturaleza  y características de las diferentes clases sociales: élites, clases medias, clases populares y marginados. 
### Creencias
Mitos, folklore y tradiciones locales. 
### Cultura
Forma que sus habitantes perciben o reaccionan ante el mundo que les rodea. Cuales son sus creencias y costumbres principales. 
### Religión
Cómo de implantada está la religión oficial y qué otras religiones están presentes en la organización. Existencia de alguna religión prohibida o tabú. 
Principales centros religiosos y jerarquía.
### Minorías
Identidad y naturaleza de las minorías étnicas y religiosas. Grado de libertad, integración o marginación.
### Viajeros y visitantes
Clase de gente foránea  visita el lugar, qué buscan aquí y qué suelen hacer. Dónde es más fácil encontrarles. 
### Educación
Cómo de formados están los habitantes. Cuál es el nivel medio. Centros de educación, formación y saber. 
### Ciencia y tecnología
Qué inovaciones tecnológicas están disponibles para toda la población y que logros trascedentales les da una ventaja militar o económica sobre sus vecinos. Han desarrollado alguna tecnología o manufactura específica .
***
## Economía
Nivel de desarrollo económico y prosperidad.
### Recursos  Naturales
Madera de los bosques, grano. de los campos, ovejas de las colinas y metales o piedras de las entrañas de la tierra. Los recursos naturales definen los bienes que pueden encontrarse o que pueden ser explotados por la población.
### Agricultura e Industria
Es una potencia agrícola o manufacturera. Cuales son las actividades que sustentan esas facetas (metalurgia, telares, colmenas, rebaños, ballenas, etc.)
### Comercio y Transporte
Como se mueven estos productos fuera y dentro de las fronteras. Infraestructuras y vías de comunicaciones. Centros de comercio, mercados principales y ferias. Compañías comerciales y rutas. Acuerdos de comercio. 
#### Importaciones
Cuáles son los productos que necesita traer del exterior o que aprecia cómo bienes de lujo. Qué productos son más baratos de importar aunque se puedan producir dentro.
#### Exportaciones
Que mercaderías están demandadas fuera y cuán abundante es ese recurso. 
### Infraestructuras 
Bienes y recursos que aseguran la salud, riqueza o bienestar de la población: canalizaciones de agua, fortificaciones, puentes, murallas, puertos, casas consistoriales, etc.
***
## Historia
Esbozo sucinto. Los listado de eventos se adjuntan en líneas cronológicas. 
### Antecedentes
Situación anterior. Organizaciones predecesoras. 
### Fundación
Proceso de formación y creación de esta unidad geopolítica
### Crisis y evoluciones
Momentos relevantes en su devenir histórico y cambios que experimenta. 
### Disolución
Causas y proceso de disolución.
***
## Rumores, leyendas y secretos
Noticias que circulan oficial y oficiosamente por el lugar. Misterios y secretos. Rumores. Historias locales.  Secretos y actividades crípticas.
***
## Perspectiva Hermética
Implantación de la Orden
Alianzas
Tradiciones no-herméticas.
Aspectos de interés hermético: vis en bruto, auras y poderes sobrenaturales.
