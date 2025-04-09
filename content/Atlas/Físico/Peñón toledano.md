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
 <section class="wa-section main-content"><p>Se conoce así al cerro escarpado, rodeado por el <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="00fea915-3b49-49b2-9f9c-de8345d24b05" data-template-type="location" data-article="00fea915-3b49-49b2-9f9c-de8345d24b05">Tajo</span> en tres de sus cuatro partes que sirve de basamento natura o pedestal a la <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="03e41c57-ad44-4b2a-9572-14789189ef45" data-template-type="settlement" data-article="03e41c57-ad44-4b2a-9572-14789189ef45">Ciudad de Toledo</span> , y donde reside en primer término su sugestiva belleza. Toledo sobre su basamento, contemplado a gran distancia y atendiendo a sus rasgos geométricos, ofrece la proporción en sus dimensiones, la esbeltez de líneas y la armonía necesaria de sus elementos, para que ante nuestros sentidos lo califiquemos como una obra de arte, ya sea divina, mágica o humana.
</p>
<p>
La situación y forma de este peñón, separado al azar de la meseta le ha conferido su importancia estratégica como fortaleza natural, asiento de tribus, sede de reyes y codiciada posesión en todas épocas. Si la ciudad se extendiera sobre la monótona Mancha, esta perdería sus encantos y resultarían imposibles los trazados de sus murallas, calles y edificios. El Toledo humano debe su origen y su desenvolvimiento, precisamente al hecho de haber sido asentado en el hermoso pedestal, pintoresca y estratégicamente emplazado.
</p>
<p>
La naturaleza ofrece en Toledo una sensación distinta a la habitual; no se trata de accidentes de dimensiones descomunales, de formas de erosión raras, sino de un accidente de trazado y proporciones tales que diríase ha sido concebido por el más inspirado artista. La hoz del Tajo, siendo profunda, tiene vertientes simétricas, uniformes y de perfil sencillo; la planta del foso es casi poligonal, y dentro de ese aspecto rígido, tiene enlaces por curvas suaves y regulares. Las rápidas laderas muestran las entrañas rocosas en forma tan caprichosa que figuran una estructura de gruesos sillares paralelopipédicos. No obstante, literatos, historiadores y cronistas de todas las épocas han bautizado al pedestal de esta ciudad con los más variados calificativos: "enhiesto peñasco", "eminencia abrupta", "lugar riscoso y encumbrado", "alta roca", "escarpa-do risco", "montaña inaccesible", "gallarda roca", "ciudad rocosa", "abrupta y dura sierra arcaica", "grisáceo y brutal peñas-co", "ciudad de las águilas", "fantasma pétreo". 
</p>
<p>
Sin embargo, geográficamente hablando, el promontorio toledano puede calificarse de cerro achatado, o más bien de una altiplanicie con una planta de forma de un trapecio isósceles, cuyas bases tienen longitudes de 1600 y 700 m.
La altitud máxima respecto al nivel del río es de unos 70 m. La máxima cota es de 548 m. en la explanada del Alcázar y la mínima en el nivel del río en el Puente de San Martín, 440 m. La curva de cota 500 coincide en buena parte con la línea que marca el cambio de pendiente entre la superficie de la cumbre, suavemente ondulada, con una inclinación entre el 1--30%) y las vertientes rápidas, especialmente en los frentes del río, con algunos traoms hasta el 70%. 
</p>
<p>
Las irregularidades más notables que deforman el cuerpo geométrico son: la profunda depresión cuya línea sigue la calle del Barco, y su paralela, surcada por la calle del Cristo de la Parra.
La base superior del tronco de pirámide queda alterada por una serie de pequeñas colinas, las Doce Colinas, de las cuales las más prominentes forman una divisoria en sentido O-E que separa dos vertientes, la N. con una superficie menor a un tercio del to-tal, y la S. algo mayor que las dos terceras partes.</p></section>  <section data-section-id="sidebarcontent" class="wa-section public"><dl><dt>General Details</dt><dd><h3>El Peñón Toledano</h3>
<p></p>
<p>
</p><div id="f79815f1be6072a334f0fcc7b0a2c9a5" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/9eb83906302c26c11d85338279e1e130.jpeg" alt title="toledo-spain-toledo-ispaniya-4092.jpeg" /></div>
Toledo vista desde el Castillo de San Servando</dd></dl></section><section data-section-id="sidepanelcontenttop" class="wa-section public"><h2>General Details</h2>
<p></p><h4>Dimensiones</h4>
<ul>
<li>Altitud máx. sobre el nivel del mar: 548 m.</li>
<li>Altitud mín. sobre el nivel del mar: 440 m.</li>
<li>Altitud máxima sobre el río: 70 m.</li>
<li>Curva defensiva: 500 m.</li>
<li>Extensión (sobre plano): triángulo de 1600 x 700 m.</li>
</ul><p></p><hr /></section><section data-section-id="alternativename" class="wa-section public"><dl><dt>Alternativename</dt><dd>El cerro de Toledo, El cerro toledano, Las Doce Colinas</dd></dl></section><section data-section-id="geography" class="wa-section public"><h2>Geography</h2>
<p>Vamos a estudiar a Toledo sin Toledo, es decir, separando mentalmente cuanto constituye la obra del hombre, hasta dejar desnudo el peñón, en el cual vamos a contemplar la obra natural y por último, veremos en los rasgos de su fisonomía topográfica se encuentran los condicionantes de su entramado urbano.
El que por primera vez contemple Toledo, desde un punto lejano o a vista de pájaro, se quedará intensamente emocionado ante el sorprendente espectáculo que presenta el cerro erizado de pintorescas construcciones, presididas por el Alcázar y agrupadas alrededor de la soberana Catedral; pero en esto conjunto de casas, monasterios, conventos, iglesias y minaretes, etc., no están sus construcciones colocadas como en una población cualquiera, sino entremezcladas aparentemente en confusa red, tendida sobre la ondulada cumbre del montículo y recortada bruscamente ante un escarpe circular, sobre cuya arista se alzan los lienzos del recinto amurallado.
</p>
<p>
El pacífico Tajo, en su curso por la llanura de la Sagra, marcha con un serpenteo indeciso, propio de su régimen de vejez; deja unas orillas para invadir otras, pero al llegar ante el notorio promontorio toledano, abandona la tranquila marcha por terrenos aluviales, y penetra decidido por la estrecha hoz entre los materiales cristalinos, con recorrido tumultuoso, hasta que vuelve de nuevo a discurrir por la planicie, después de haber dado guardia de honor a la colosal fortaleza. El Tajo, riega las felices vegas de Toledo donde se ubican las villas y los palacios de recreo de reyes moros y castellanos; bate las máquinas y molinos y los batanes.
</p>
<p>
La belleza sugestiva de la Ciudad de los Reyes reside en primer término en el majestuoso pedestal o basamento natural sobre el que se alza, y en segundo lugar nos recrea el detalle de la filigrana de la superstructura, integrada por ese manto de piedra y barro, labrado por las manos de los artífices de todas las generaciones humanas. Toledo sobre su basamento, contemplado a gran distancia y atendiendo a sus rasgos geométricos, ofrece la proporción en sus dimensiones, la esbeltez de líneas y la armonía necesaria de sus elementos, para que ante nuestros sentidos lo califiquemos como una obra de arte, ya sea divina, mágica o humana.
</p>
<p>
La Naturaleza ofrece en Toledo una sensación distinta a la habitual; no se trata de accidentes de dimensiones descomunales, de formas de erosión raras, sino de un accidente de trazado y proporciones tales que diríase ha sido concebido por el más inspirado artista. La hoz del Tajo, siendo profunda, tiene vertientes simétricas, uniformes y de perfil sencillo; la planta del foso es casi poligonal, y dentro de ese aspecto rígido, tiene enaces por curvas suaves y regulares. Las rápidas laderas muestran las entrañas rocosas en forma tan caprichosa que figuran una estructura de gruesos sillares paralelopipédicos. Dos profundos barrancos dan acceso al foso por su orilla derecha y entre ambos se eleva la Peña del Rey Moro a modo de colosal remate decorativo.
</p>
<p>
</p><h5>Una fortaleza natural</h5>
El emplazamiento de Toledo ha venido ofreciendo excelentes condiciones como fortaleza natural, con tres frentes protegidos por el magnífico foso del río Tajo y el cuarto formado por un rápido talud.
<p></p>
<p>
Tanto en una fortificación de campaña como en una permanente, el elemento fundamental de trazado es la<b> cresta militar</b>, situada delante de la topográfica, allí donde la pendiente suave de la cumbre cesa, comenzando el fuerte declive; desde la cresta militar deben quedar batidos todos los puntos del talud, lo cual no ocurre generalmente desde la cresta topográfica. Pero en la posición de Toledo, la cresta militar está admirablemente marcada, y coincide de modo aproximado, con la línea de nivel, cuya altitud sobre el mar es de 500 metros.
</p>
<p>
Dada la extensión de esta fortaleza, se entiende que las tribus primigenias, poco numerosas, no pudieran cubrir su línea natural defensiva y morasen en cerros más pequeños y fácilmente fortificables con los del Bú.
</p>
<p>
Pero el Toledo romano y visigodo sí responde al perfil de ciudad cuyo amplio perímetro hay que defender. La muralla de Wamba, alzada en buena parte sobre la romana, se basa en la cresta militar de 500 m.
</p>
<p>
</p><h5>Las Doce Colinas</h5>
Pese a que se ha intentado reducir el número de prominencias del Peñón Toledano a siete, para conectarla espiritualmente con Roma o Jerusalén, son en realidad doce las colinas o cumbres que presenta:
<ol>
<li>Explanada del Alcázar: 548 m.</li>
<li>Pórtico de San Román: 543 m.</li>
<li>San Vicente, con la cumbre en la parte N de la calle lateral: 538 M.</li>
<li>Callejón de los Husillos, al sur de la Calle de la Plata: 538 m.</li>
<li>Callejón de las Esquivias, al final del mismo, en la Alacava: 536 m.</li>
<li>cerro de la Virgen de Gracia, en el O de la Alacava: 531 m.</li>
<li>Cuesta o Espina del Can, en su punto medio (cerca de San Justo) 531 m.</li>
<li>Calle de la Sillería (cerca de San Nicolás, detrás del Corral del Carbón): 530 m.</li>
<li>Travesía de San Cristóbal; 515 m.</li>
<li>Palacio de San Andrés, puerta principal: 510 m.</li>
<li>Callejón de la Divisa, a mitad: 509 m.</li>
</ol>
<p></p>
<p>
</p><h5>Ciudad y río</h5>
Aunque el río <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="00fea915-3b49-49b2-9f9c-de8345d24b05" data-template-type="location" data-article="00fea915-3b49-49b2-9f9c-de8345d24b05">Tajo</span> no atraviesa la ciudad de Toledo, en este caso, la relación entre ciudad y río es indiscutible, ya que el Tajo forma un amplio semicírculo ofreciendo defensa natural en dos tercios del perímetro urbano: el llamado <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="7d99c81f-a753-482d-8763-5e32f39e9807" data-template-type="location" data-article="7d99c81f-a753-482d-8763-5e32f39e9807">Valle del Tajo</span>, aunque se trata más bien de un profundo corte que de un "valle". Esto hace que una gran parte de la ciudad se halle ajena a las vías de comunicación interurbanas, al contrario de otras muchas ciudades, y a pesar de encontrarse desde sus orígenes en una zona estratégica de paso, su especial configuración hace que la red exterior de caminos no le afecte determinantemente, sino que la toque tangencialmente, como la calzada de Zaragoza a Mérida, o con las vías que surcan el vado situado aguas arriba al noroeste, o la que van al puente de barcas al NO.
Antes de la construcción del puente, el cruce del río se realizaba por un vado natural existente entre la huerta del rey y la de Safont. Sin embargo este vado debía de limitarse a ciertas épocas del año en las que el descenso del nivel dividía el río en dos brazos. De hecho, aún a la puerta Nueva, en el arrabal de la Antequeruela, se la conoce como Bab al-Mojahda (Puerta del Vado).
<p></p>
<p>
Los romanos fueron los encargados de construir el único puente fijo de la ciudad. Este puente, llamado por los árabes al-Qantara (el puente) queda totalmente lateral al recinto. Hasta tal punto que en la ciudad de Toledo la existencia de un puente no ha generado un núcleo poblacional al otro lado del mismo, y es que realmente la relación entre Toledo y el Tajo se basa más en el elemento topográfico que hidrográfico.
</p>
<p>
</p><h4>Relieve y red urbana</h4>
El relieve es el principal determinante del urbanismo toledano a través de estos tres parámetros:
<ol>
<li>En primer lugar, el recinto se asienta sobre un cerro rodeado -<span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="7f591c32-bd34-4cb4-91c6-35dba4cee285" data-template-type="location" data-article="7f591c32-bd34-4cb4-91c6-35dba4cee285">El Peñón Toledano</span>- en tres de sus lados por el río Tajo.</li>
<li>El notable cambio de pendiente alrededor de los 500 metros de altura, de tal manera de que es a partir de dicha altitud cuando aparece el asentamiento propiamente dicho.</li>
<li>La comunicación entre la ciudad y el río se hace a través de las vaguadas, que constituyen los caminos de acceso naturales, y las vías de evacuación residuales.</li>
</ol>
<h5>Elevaciones</h5>
De las elevaciones surgen divisorias y vaguadas. Ya hemos visto la configuración del <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="7f591c32-bd34-4cb4-91c6-35dba4cee285" data-template-type="location" data-article="7f591c32-bd34-4cb4-91c6-35dba4cee285">El Peñón Toledano</span> en Las Doce Colinas entre las que destacan las del Alcázar (550 m.) y la de San Román (554 m.)
<p></p>
<p>
En una sección E-O, el cerro va subiendo desde el río hasta el Alcázar por el Oeste y hasta San Román por el Este. Esto significa que los puntos de paso están en las depresiones entre las cimas. Además, existen dos vertientes claramente diferenciadas por la línea de cumbres:
</p><ol>
<li>la vertiente Norte cuenta con las divisorias de las frontales de Sillería, San Vicente y Esquivias;</li>
<li>Para la vertiente Sur interviene una segunda línea de cumbres formadas por el callejón de la Divisa y cuesta del Can, San Andrés y San Cristóbal.</li>
</ol>
<h5>Barrancos y vaguadas</h5>
Muchas de las calles han tenido una situación obligada e invariable en el transcurso de los siglos, como son las determinadas por las vaguadas o depresiones creadas por las líneas de cumbres, en las cuales no es posible colocar obstáculos al veloz deslizamiento de las aguas de lluvias que por sus cursos naturales se precipitan hacia el Tajo.
<h5>Vaguadas principales</h5>
No todas tienen igual importancia. La división tradicional de la ciudad en cuatro cuarteles: el Barco, San Sebastián, Puerta Nueva y Cambrón se corresponden con las cuatro vaguadas más importantes por las que discurren las calles generadoras de la organización de la ciudad:
<p></p>
<p>
</p><ol>
<li><b>Puerta Nueva (A)</b> en dirección Norte, parte de San Vicente, baja por Alfileritos, tuerce a mano izquierda por Carmelitas Descalzos, y luego por la Calle de la Luz hasta la puerta de Valmardón. Pasada por la puerta discurre por la calle de los Azacanes ahsta llegar a la puerta Nueva, donde confluye con otra vaguada que surca el barrio de la Antequeruela. Por ella discurren las bajadas de la Antequeruela uniendo la puerta Nueva on la antigua de la Bisagra a través de la Plaza de la Estrella.</li>
<li><b>El Barco (B)</b>: en dirección Sur, la vaguada formada por las calles del Barco y del Pozo Amargo que discurre en dos ramales independientes. El primero comienza en la cuesta de los Portugueses, baja por la calle de las Tornerías, bordea la catedral y se mete por la calle del Barco hasta unirse con la del Pozo Amargo en la Plazuela de Don Fernando. El segundo comienza en las Tendillas, sigue por Nuncio Viejo y bordea la catedral hasta coger la calle del Pozo Amargo. A partir de la plazuela de Don Fernando llega hasta la puerta del Hierro.</li>
<li><b>San Sebastián (C)</b>: en paralelo a la anterior; por la que discurren las calles de Santa Úrsula y del Cristo de la Parra hasta llegar a la puerta de San Sebastián o de Curtidores.</li>
<li><b>El Cambrón (D)</b>: en dirección Oeste, por las calles de las Tendillas, la Merced o de Capuchinas, Nuncio Nuevo, real y Carmelitas hasta la puerta del Cambrón.</li>
</ol>
<p></p>
<p>
En estas cuatro vaguadas principales del cerro se ubican los cuatro colectores de saneamiento terminando todas en una puerta de la muralla. El relieve ha actuado como elemento estructurador de la ciudad desde sus comienzos y estas alcantarillas pueden remontarse hasta la época romana.
</p>
<p>
</p><h5>Vaguadas secundarias</h5>
Además de estos ejes nucleares existen otros por vaguadas secundarias y líneas de deslizamiento topográficas (de parecida cota o pasos entre elevaciones de relieve):
<ol>
<li>vaguada secundaria por Alamillos y la Calle Campana.</li>
<li>vaguada secundaria por Santa Leocadia, colegio de Doncellas, san Pedro Mártir y Rojas.</li>
<li>línea de deslizamiento por Sillería, Alfileritos y Cárcel Vieja.</li>
<li>línea de deslizamiento por Cuesta de Belén y calle de la Plata.</li>
</ol>
<h5>El eje colector</h5>
La articulación de toda esta red viaria se consigue mediante un gran eje colector, que constituye la espina dorsal de la ciudad. Este gran eje está formado por las calles del Ángel, Santo Tomé, Trinidad, Hombre de Palo y del Comercio, uniendo entre sí las antiguas puertas interiores de Assuica y de la Sangre y atravesando todo el distrito comercial de la ciudad, encargándose de tres funciones básicas en el urbanismo:
<ul>
<li>Interconectar las cuatro grandes áreas de la ciudad: zonas Norte, Sur, Judería y Alficén.</li>
<li>Unir entre sí todas las vías generadoras, de vaguadas secundarias y de deslizamiento.</li>
<li>Servir de soporte y focalizador al área comercial clásica de la ciudad (Alcaná, Catedral, Zocodover)</li>
</ul>
<h5>Estructura radial</h5>
Aún así, se mantiene en su conjunto la estructura radiada, herencia de época musulmana, de la disposición del solar y por su naturaleza de plaza fortificada.
<p></p>
<p>
Las arterias radiales principales son:
</p><ol>
<li>Calles del Ángel, Santo Tomé, Trinidad;</li>
<li>calle Ancha y Hombre de Palo;</li>
<li>Calle del Pozo amargo</li>
<li>Calle del Barco.</li>
</ol>
Las cuatro convergen hacia el solar de la mezquita-catedral.
<p></p>
<p>
</p><h5>Explanaciones convergentes</h5>
La principal es la zona ocupada por la Mezquita-Catedral, es una explanada a la que afluyen más o menos directamente, 19 calles. Esta explanación, además de ser la más extensa, ocupa el sitio central y es de suponer que fuera el foro en época romana, donde más tarde se emplazaría la primera catedral cristiana, trasformada luego en Mezquita Aljama, que dejaría aún vasto espacio para lo que se podría denominar Plaza Mayor.
<p></p>
<p>
La Plaza del Zocodover, por su situación inmediata al Alficén, al frente N. amurallado, ha desempeñado importante servicio en las organizaciones defensivas de la ciudad, y aquí confluyen siete calles.
</p>
<p>
Las otras dos explanaciones son San Cristóbal y el Tránsito. Ambas se edificaron en época árabe y por su situación éxcéntrica no representan papel importante en el trazado.
</p>
<p>
</p><h5>Calles precipicio</h5>
Independientemente de las calles propiamente dichas, existen otras que se pueden llamar calles precipicio, las cualas no pueden figurar como de tránsito normal, ya que muchas de ellas están provistas de escalones o rampas y otras que no los tienen, deberían tenerlos, ya que pueden tener vaolres muy superiores de inclinación a los de caminos de alta monaña: la cuesta del Can tiene el 25% de pendiente; la cuesta de la Reina el 24%, la cuesta de los Escalones, el 30% y la Travesía del Reptil, calle trazada en la zona de escarpe, un 50%.<p></p><hr /></section>   

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

