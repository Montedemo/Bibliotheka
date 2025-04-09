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
 <section class="wa-section main-content"><p>Una de las principales cordilleras de <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="298d6b16-2538-44ad-928c-5d5c34faeda9" data-template-type="location" data-article="298d6b16-2538-44ad-928c-5d5c34faeda9">Europa</span>, situada en el sector sudoccidental de esta, dividiendo las partes de Hispania y <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="95e463a3-b292-434e-8950-8d20a84d7f6a" data-template-type="location" data-article="95e463a3-b292-434e-8950-8d20a84d7f6a">Galia</span>.</p></section>  <section data-section-id="alternativename" class="wa-section public"><dl><dt>Alternativename</dt><dd>Pyraenei Montes, Pyrineii, Pirineus, Pirinées</dd></dl></section><section data-section-id="geography" class="wa-section public"><h2>Geography</h2>
<p>A primera vista, se puede dividir los Pirineos en sus dos laderas o vertientes, la meridional y más extensa -o Pirineos Hispánicos- cuyas aguas van a parar en su mayoría al río Ebro por lo que pueden ser llamados también ibéricos - y la septentrional o Pirineos Gálicos, u océanicos ya que la mayoría de sus aguas van a parar al Océano. También podríamos dividir los Pirineos según la cultura dominante de su zona, así: Pirineos vascones, Pirineos aquitanos, Pirineos aragoneses, Pirineos provenzales y Pirineos catalanes. Sin embargo, dado que las comunidades pirenaicas están íntimamente conectadas a ambas vertientes, vamos a obviar dicha división y marcar dos lineas verticales: Sumus Portus y Airenosia, dividiendo los Pirineos tres segmentos, de Oeste a Este:
</p><ol>
<li><b>Pirineos Centrales:</b> entre Sumus Portus y Airenosia (Valle de Arán), incluyendo ambos. Donde su ubican las grandes cumbres pirenaicas: Aneto, la Punta de Llardana y el Monte Perdido.</li>
<li><b>Pirineos Occidentales</b>: a partir del Sumus Portus (Somport) hacia el Oeste, hasta el Sumus Pyreneo (collado de Ibañeta o Roncesvalles) en Navarra. Su última gran cumbre es el monte Ori, u Orrhy.</li>
<li><b>Pirineos Orientales</b>: después del Valle de Arán hasta Caput Diaboli (Cabo de Creus) donde los Pirineos se sumergen en el Mediterráneo. Su última gran cumbre es el pico de Bastiments y su mayor altura, la Pica d'Estats en el macizo de Mont Calm entre los condados de Urgel y Fois.</li>
</ol>
<h4>El piedemonte</h4>
El piedemonte pirenaico, también llamado Pyrenaica, se extiende más allá de la cordillera propiamente dicha, y especialmente hacia el sur, en el lado hispánico, se extiende un amplio y complejo sistema de sierras desde Navarra hasta Cataluña, casi alcanzando el Mediterráneo, y con cumbres que alcanzan los 2.600 m. Hacia el norte, las laderas de los Pirineos descienden abruptamente y no hay verdaderas estribaciones, a excepción del macizo de las Corbèras, en Rosellón, y el macizo de Plantaurel, en el condado de Fois. 
<p></p>
<p>
</p><h4>Paisaje</h4>
Las características más llamativas del paisaje pirenaico son:
la ausencia de grandes lagos, como los que llenan los valles laterales de los Alpes.
la rareza y la elevación relativamente alta de los pasos utilizables.
la gran cantidad de torrentes de montaña llamados localmente gives, que a menudo forman cascadas elevadas, de mayor altura que las alpinas.
la frecuencia con la que el extremo superior de un valle asume la forma de un semicírculo de acantilados escarpados, llamado circo.
<p></p>
<p>
Faltan pasos bajos, y los romanos solo pudieron abrir calzadas en las tierras bajas de los extremos occidental y oriental de los Pirineos, cerca del nivel del mar.  Los demás pasos son collados de alta montaña, en el que el trasporte de mercancías solo puede ser llevado por mulas, y muchas veces, a hombros de porteadores locales, con la salvedad del Sumus Portus, en el que los romanos consiguieron construir una calzada y que es el paso más importante en el centro de los Pirineos. 
</p>
<p>
Otros pasos menores son:
</p><ul>
<li>el Col de la Perche (1.581 m (5.187 pies)), hacia el este, entre el valle del Têt y el valle del Segre,</li>
<li>el Pas de la Casa o Port d'Envalira, que proporciona la ruta de Fois a Andorra,</li>
<li>el <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="952fff6a-d594-4eb5-abd0-a8c97abe7000" data-template-type="location" data-article="952fff6a-d594-4eb5-abd0-a8c97abe7000">Puerto de Incles</span> que atraviesa el punto más bajo del Pirineo andorrano</li>
<li>el cercano Col de Puymorens (1.920 m (6.300 pies)).</li>
<li>el Port de la Bonaigua (2.070 m (6.790 ft)), en plena sierra en la cabecera del Valle de Arán,</li>
<li>el casi collado del Plan de Beret (1.870 m (6.140 ft))</li>
<li>el Col du Pourtalet (1.794 m (5.886 pies)), más de 100 km (62 millas) al oeste.</li>
<li>El puerto de Roncesvalles, que atraviesa el collado de Ibañeta (1.057 m (3.468 pies)), íntegramente en Navarra y que es un punto importante en la ruta de peregrinación del Camino de Santiago.</li>
</ul>
Una característica visual notable de esta cadena montañosa es La Brecha de Roland, una brecha en la línea de la cresta que, según la leyenda, fue creada por Roland.
<p></p>
<p>
</p><h4>Clima</h4>
Aunque generalmente húmedos, la cantidad de precipitaciones que recibe la cordillera, entre lluvia y nieve, es mucho mayor en los Pirineos occidentales que en los orientales debido al aire húmedo que sopla desde el océano Atlántico sobre el mar cantábrico. Después de dejar caer su humedad sobre los Pirineos occidental y central, el aire queda seco sobre los Pirineos orientales. La temperatura media de invierno es de -2 ° C.
<p></p>
<p>
Las secciones de la cordillera varían en más de un aspecto. Hay algunos glaciares en los Pirineos occidentales y nevados centrales, pero no hay glaciares en los Pirineos orientales porque las nevadas son insuficientes para provocar su desarrollo. Los glaciares están confinados a las laderas septentrionales de los Pirineos centrales, y no descienden, como los de los Alpes, hacia los valles, sino que tienen sus mayores longitudes en la dirección de la cadena montañosa. Se forman, de hecho, en una zona estrecha cerca de la cresta de las montañas más altas. 
</p>
<p>
La línea de nieve anual varía en diferentes partes de los Pirineos desde aproximadamente 2700 a 2800 metros (8900 a 9200 pies) sobre el nivel del mar. En promedio, la nieve estacional se observa al menos el 50% del tiempo por encima de los 1.600 metros entre diciembre y abril.</p><p></p><hr /></section><section data-section-id="naturalresources" class="wa-section public"><h2>Naturalresources</h2>
<p>Los minerales metálicos de los Pirineos no tienen en general mucha importancia, aunque hay notables minas de hierro en varios lugares de Andorra, así como en Vicdessos y Sabarthès, y el pie de Canigó, en el Rosellón, hace mucho tiempo. El tajo abierto de Trimoun cerca del municipio de Luzenac es una de las mayores fuentes de talco en Europa.
</p>
<p>
Los manantiales minerales son abundantes y notables, y destacan especialmente las aguas termales. Las termas, entre las que se pueden citar las de Les Escaldes en Andorra, Panticosa y Lles en España, Aqs, Banheres de Luchon y Aigues Caldes, son sulfurosas y en su mayoría situadas en altura. Los manantiales inferiores, como los de Banheres de Bigorre , Rennes-les-Bains (Aude) y Capmanha de Aude no son termales.</p><hr /></section><section data-section-id="history" class="wa-section public"><h2>History</h2>
<p>De acuerdo con la leyenda, los Pirineos recibieron su nombre de Pirene, hija de Bebryx, rey legendario de la Ceritania. Hercules abusó de la hospitalidad de Bebryx, quien le había dado cobijo mientras viajaba para cumplir su décimo trabajo, y sedujo a la joven. De dicha unión surgió una serpiente que sería madre de los dragones pirenaicos.
El semidiós abandonó a la joven, quien, a pesar de todo, quiso seguir a su enamorado. Pero fue atacada y devorada por unos animales salvajes. Hércules, alertado por los gritos de Pirene, volvió sobre sus pasos, pero no encontró más que un cuerpo sin vida. Como homenaje a esta prueba de amor, Hércules la devolvió a su casa y construyó un inmenso mausoleo amontonando hasta el infinito rocas que formaron una serie de montañas, a las que denominó Pirineos. La gente del <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="10eee935-c213-4308-8af4-73b1d428b1ec" data-template-type="location" data-article="10eee935-c213-4308-8af4-73b1d428b1ec">Sabarthès</span> sitúa la tumba de Pirene en la cueva de L'Ombrivas, en la que unas concreciones de estalagmitas forman una especie de sepultura colosal.
</p>
<p>
Según otra leyenda, Pirene dio a luz una serpiente antes de morir, y su cuerpo fue colocado sobre una hoguera. El fuego de la incineración se propagó a la montaña, hasta el punto que las poblaciones del Ampurdán en las que residían comerciantes griegos denominaron Pirineos (del griego pyr, pyros, ‘fuego’) a aquellos macizos cubiertos de llamas.
</p>
<p>
Otra de las teorías más aceptadas es la de que el nombre procede de un incendio (fuego en griego es pyros) del que dieron cuenta Estrabón y Diodoro Sículo, causado por unos pastores al roturar sus tierras de cultivos. Se dijo que incluso las vetas de oro y plata se fundieron a nivel del subsuelo.</p><hr /></section><section data-section-id="florafauna" class="wa-section public"><h2>Florafauna</h2>
<p></p><h4>Flora</h4>
Un efecto aún más marcado de la preponderancia de las precipitaciones en la mitad occidental de la cadena se observa en la vegetación. Las montañas más bajas en el extremo oeste están cubiertas de bosques, pero la extensión de los bosques disminuye a medida que uno avanza hacia el este. Los Pirineos orientales son peculiarmente salvajes y áridos, tanto más cuanto que es en esta parte de la cadena donde predominan las masas graníticas. También moviéndose de oeste a este, hay un cambio en la composición de la flora, y el cambio se hace más evidente a medida que se pasa por el centro de la cadena montañosa, desde cuyo punto el macizo de Corberas se extiende hacia el noreste hacia el centro de la Galia. En el oeste la flora se parece a la de Europa central, mientras que en el este tiene un carácter netamente mediterráneo. Los Pirineos son casi tan ricos en especies endémicas como los Alpes y son muchas las plantas únicas que solo pueden encontrarse aquí.
<p></p>
<p>
</p><h4>Fauna</h4>
En su fauna, los Pirineos presentan algunos casos llamativos de endemismo. El desmán pirenaico sólo se encuentra en algunos de los arroyos de la vertiente norte de estas montañas; La salamandra de los Pirineos , un anfibio endémico, también vive en arroyos y lagos situados a gran altura. Entre otras peculiaridades de la fauna pirenaica se encuentran los insectos ciegos de las cavernas de Sabarthés.
<p></p>
<p>
La cabra montés pirenaica, una subespecie endémica de la cabra montés ibérica, es una de sus especies más características, y muy apreciada como trofeo de caza; Entre los grandes depredadores, destacan el lobo y el oso pardo, peligrosos para quienes se adentran en las zonas agretes.</p><p></p><hr /></section>   

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

