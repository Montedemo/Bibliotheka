---
tags: Category/subcontinent
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
NoteIcon: geo
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

 <section class="wa-section main-content"><p>Se define como Germania o Magna Germania, las inhóspitas tierras que quedaron fuera del Imperio Romano, habitadas por los belicosos barbaros <span data-article-privacy="private" data-article-id="a89cb899-d8e0-492d-9d82-ebfc02f5b787" data-template-type="ethnicity" class="private-article article-unlinked entity-link wa-link">Germanos</span> y delimitadas por el curso del Rín, al Oeste, y por el río Oder al este. Al Sur, las fronteras del Imperio delimitaban Germania a partir del Danubio pero en la actualidad esta frontera geográfico cultural comienza en la cara norte de los <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="ee75ea35-701d-4d7f-a872-85bbfdd811d9" data-template-type="location" data-article="ee75ea35-701d-4d7f-a872-85bbfdd811d9">Alpes</span>.
<br />
</p>
<p>
Paradójicamente estas tierras fuera del Imperio Romano son el hogar del actual Imperio Romano de Occidente, también llamado Imperio Romano Germánico o Sacro Imperio. El Imperio de los Romanos, a veces conocido como el Imperio Romano Germánico, es el estado más grande de toda Europa. Extendiéndose a lo largo de Europa Central, el Imperio alcanza desde los bordes orientales de Francia hasta los reinos de Polonia, y desde el Báltico hasta el sur de los Alpes.
<br /> El Sacro Imperio está gobernado actualmente por la dinastía Habsburg. Los emperadores Habsburgo están en conflicto con las fuerzas papistas para determinar si es el Emperador o el Papa la cabeza temporal de la Cristiandad. El resultado de la contienda está todavía por decidirse, pero ha desviado mucho la atención del emperador lejos de los asuntos germánicos, y Germania está sufriendo por todo esto. Aunque solo unos pocos se quejan abiertamente de negligencia, los resultados de esta (caminos en mal estado, pobreza y miseria) son visibles por todos lados.
<br />
</p>
<p>
El Imperio también envuelve al reino de Bohemia, una nación vasalla pero que retiene bastante independencia política. El emperador Federico I Barbarroja ha intentado varias veces socavar a la dinasíta Piemsyl, que gobierna Bohemia mediante manipulación política. Los intentos subversivos de Federico han includi un esfuerzo para deponer al obispo de Praga (miembro de la familia Piemysl) en 1187, pero la familia sobrevive. La tensión se suavizará tras la muerte del emperador Federico.
<br />
</p>
<p>
La frontera oriental del Imperio está dividida en una serie de marcas para protegerse de los nómadas orientales. La gente de estas marcas presiona lentamente las fronteras del Imperio por el sur y el este. Como resultado, están creciendo las tensiones en las fronteras de Polonia y Hungría. 
<br />
</p>
<p>
Aunque el Imperio Romano Germánico es el estado más grande y poderoso militarmente de Europa, no es el más rico, ya que carece de un puerto en el Mediterráneo, por lo que queda fuera del floreciente comercio marítimo, que es la espina dorsal de la riqueza italiana y francesa.
<br /></p></section>  <section data-section-id="sidebarcontent" class="wa-section public"><dl><dt>General Details</dt><dd><div id="07dc4bd1c5aafad044b706bbad33e6a2" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/411695d785dca1310ae3360b0048b129.png" alt title="Germania" /></div></dd></dl></section><section data-section-id="alternativename" class="wa-section public"><dl><dt>Alternativename</dt><dd>Teutonia, Alemania, Sacro Imperio</dd></dl></section><section data-section-id="geography" class="wa-section public"><h2>Geography</h2>
<p></p><h4>Las tierras alpinas</h4>
Desde el sur, lo primero que encuentra un viajero en el Germania son los traicioneros <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="ee75ea35-701d-4d7f-a872-85bbfdd811d9" data-template-type="location" data-article="ee75ea35-701d-4d7f-a872-85bbfdd811d9">Alpes</span> . Estas montañas son las más altas de la Europa mítica, con algunos picos que superan los 4500 metros. 
<br />Los Alpes occidentales, que lindan con las Galias son los más empinados y constan de precipicios acantilados y picos altos, con pocos pasos que atraviesan
valles estrechos y agudos que serpentean casi paralelos al recorrido de la cordillera. 
<br />Los Alpes orientales son más bajos,
aunque todavía a menudo a más de 10,000 pies de altitud, con terrazas pendientes y valles más anchos que brindan más oportunidades para pasar a través de la cordillera.
<br />
<p></p>
<p>
Las laderas superiores de los Alpes están cubiertas de bosques de pinos, particularmente en el lado norte. Las pendientes medias y sus alrededores las tierras están cubiertas por llanuras de grava con suelo pobre, apto únicamente para la producción de cebada, avena y otros cereales forrajeros.
<br />
</p>
<p>
Las laderas medias de los Alpes albergan a muchos bovinos, que prosperan sobre las hierbas silvestres que crecen en las llanuras de grava. Estas llanuras descienden hacia el río Danubio y la ciudad de Ulm.
<br />
</p><h4>Las tierras altas centrales</h4>
Más allá de las llanuras de grava del promontorio alpino se encuentra el tierras altas centrales de Germania. Esta tierra montañosa está cubierta de colinas onduladas y boscosas, macizos de granito y corrientes volcánicas. Es una región muy fértil, hogar de la gran Selva Negra y el famoso <strong class="article-unlinked">Valle Alto del Rín</strong> . Las tierras altas centrales obtienen considerables precipitaciones de lluvia y nieve durante todo el año.
<br />
<h4>Las tierras bajas septentrionales</h4>
Las tierras altas persisten en gran parte del Imperio central. Solo en el norte cesan, para ser reemplazadas por las Tierras Bajas. Estas tierras bajas son principalmente humedales, marismas, y pantanos. Las áreas habitadas (particularmente en el oeste) deben protegerse del mar mediante diques. Al este, las tierras se elevan lentamente, convirtiéndose en prados montañosos en el extremo oriental de las tierras bajas. Sin embargo, incluso en el este, estas tierras son mucho más bajas y
más llanas que en cualquier parte de las tierras altas.<p></p><hr /></section>   

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
