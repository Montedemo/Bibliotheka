---
NoteIcon: geo
tags:
  - Geography 
categoria: Formación Terrestre/Acuática
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
 <section class="wa-section main-content"><p><span class="dropcap">E</span>L paraje de las Hoces del Río Duratón las gargantas que este río tiene en su tramo medio. Estas son el cañón que el Duratón, afluente del río Duero, ha excavado en una zona de roca caliza entre las localidades de Sepúlveda y Burgomillodo en el centro de las tierras de la <span data-article-privacy="private" data-article-id="26dec0d1-cdba-49c9-ab2a-9523cf437cdc" data-template-type="location" class="private-article article-unlinked entity-link wa-link">Extremadura castellana</span>, dentro de la diócesis de Segovia.
<br />Se trata de un lugar de excepcional belleza natural, donde el río discurre formando sinuosos meandros encajonados entre ásperas paredes de roca, a su vez perforadas por multitud de abrigos y cuevas.
<br />Es un entorno del cual las aves de todo tipo, desde los majestuosos buitres a los más humildes estorninos han hecho su refugio y santuario, paz natural que desde tiempo inmemorial han buscado ermitaños y anacoretas.
</p><hr /><p></p></section>  <section data-section-id="sidebarcontent" class="wa-section public"><dl><dt>General Details</dt><dd><div id="b00eb681d08c9746240fe40c30743457" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/abb5b5d746d6ba63c191c2922cba38a6.jpg" alt title="640px-Hoces_del_Duratón.jpg" /></div></dd></dl></section><section data-section-id="sidebarcontentbottom" class="wa-section public"><h2>General Details</h2>
<p></p><div id="2de8e607372c5cae862981237a9d502f" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/d39f6b3aa6c9a7774aea589e48adc03b.jpg" alt title="640px-Hoces_duraton_meandro.jpg" /></div><small>Meandros del Duratón</small><div id="45e81b9b31176b1ef649a35c42d54e5e" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/3e4acaa39791a24edfcf3d073b536696.jpeg" alt title="640px-Hoces_Duratón_fondo_del_cañón_3.jpeg" /></div><small>El fondo del cañon</small><div id="00a4d9a60da3c21d8ec9c578182bb17a" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/1f577c17c9b49799f5d3466fc092c496.jpeg" alt title="640px-Hoces_Duratón_cortado.jpeg" /></div><small>Los cortados</small><div id="64101aeb8bebf22bea8a74e50c722a13" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/c2232ea34ac2ba3ac15452b5972bc7c1.jpeg" alt title="640px-Hoces_Duratón_paramera.jpeg" /></div><small>La paramera</small><div id="70c7269386d91b0623ceef79aa1a3f71" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/05fe78569c198809669537d45ce89fb6.jpg" alt title="Buitre_leonado.jpg" /></div><small>Buitre leonado</small><hr /><div id="5dbf966e7849e4759ec4bc951d4cf953" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/379b78ae61ddffbe5ee5b3cb815e8cd6.jpg" alt title="640px-Pintura_rupestre.jpg" /></div><small>Pinturas rupestres</small><div id="230f683eb0d350d433ded6a9ecce5d5d" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/f78d7663d7b5af8774bcc0867a94fb8e.jpeg" alt title="640px-Hoces_Duratón_siete_altares_2.jpeg" /></div><small>Cueva de los Siete Altares</small><div id="340e35c1d00869afe0b3451e392a6100" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/c43ef9e8575d84593cc4afec6151a936.jpg" alt title="640px-Sepulveda_Iglesia_y_Monasterio_de_San_Frutos-2012.jpg" /></div><small>Monasterio de San Frutos</small><p></p><hr /></section><section data-section-id="geography" class="wa-section public"><h2>Geography</h2>
<p>El paraje ocupa unas 5000 hectáreas, siendo el eje del mismo el cauce del propio río. El río Duratón discurre durante 27 km encajonado en el cañón que ha excavado en el sustrato calizo. En el último tercio de este recorrido traza cerrados meandros que reafirman la excavación propiamente dicha. Las paredes, que alcanzan los 100 m de altura en algunos puntos sirven de lugar de nidificación a muchas especies de aves, pero la relevancia fundamental se la llevan los buitres leonados que se han convertido en uno de los principales atractivos del parque.
<br />
Las características orográficas que se dan en este espacio protegido hacen que se distingan tres ambientes diferentes:
</p><ol>
<li>La parte alta está ocupada por el páramo en donde abundan los bosques de sabinas y enebros. Existen también poblaciones de pinos resineros asentadas sobre sustrato arenoso.</li>
<li>El fondo del cañón está ocupado por un bosque de ribera compuesto por sauces, chopos y alisos entre otras especies. </li>
<li>Las paredes de los cortados rocosos dan sustento a una vegetación rupícola, propia de la roca, adaptada a la escasez de suelo y agua. Estos tres ambientes diferentes dan cobijo a una rica fauna en la que tienen especial relevancia las aves.</li>
</ol><p></p><hr /></section><section data-section-id="history" class="wa-section public"><h2>History</h2>
<p>El espacio de las Hoces del río Duratón ha sido ocupado por el hombre desde tiempos ancestrales, que han dejado su huella incluso en forma de pinturas en los abrigos y oquedos las paredes de roca.
<br />
La tribu celtíbera de los arévacos ocupó el lugar que luego fue conquistado por los romanos, de los cuales aún se pueden ver algunos restos de sus obras viales como la calzada en Sepúlveda, o los puentes de Picazos y Talcano. Los romanos dieron de la vecina localidad de Sepúlveda el estatus jurídico de municipio que tuvo una vida amplia y relacionada con el exterior.
<br />
Los visigodos ocuparon el lugar dejado por los romanos. A ellos se deben algunos santuarios que se encuentran esparcidos por toda el área del parque, relacionados con la tradición eremita que se mantuvo viva durante mucho tiempo en estas tierras. Muchas de las cuevas existentes en el cañón fueron convertidas en pequeñas ermitas. La más relevante es la cueva de los Siete Altares, considerada la primera iglesia de la diócesis de Segovia. En esa tradición eremita tiene origen la devoción a San Frutos (patrón de Segovia cuya ermita y tumba se encuentran en el parque).
<br />
Los árabes no dejaron muchos vestigios de su larga presencia en el cañón, ya que ocuparon el lugar desde el siglo VIII al X. Se puede apreciar algún resto en las murallas de Sepúlveda. En el año 940 se le encargó a Fernán González, conde de Castilla, la repoblación de la villa de Sepúlveda que había quedado despoblada debido a las correrías de Alfonso I, aunque se sabe que existía una población campesina alrededor de la misma, es decir en tierras de los que hoy es el paraje. Es esta repoblación la que estabilizó una zona cristiana más allá del río Duero, germen del país de la <span data-article-privacy="private" data-article-id="26dec0d1-cdba-49c9-ab2a-9523cf437cdc" data-template-type="location" class="private-article article-unlinked entity-link wa-link">Extremadura castellana</span>. En el año 979, Almanzor intentó recuperar la villa sin éxito, objetivo que consiguió años más tarde, en 984 o en 986. En el año 1010 la villa pasó definitivamente a manos cristianas al ser tomada por Sancho García, nieto de Fernán González.
<br />
Ya en la repoblación efectuada por Fernán González se estableció el Fuero de Sepúlveda y que en el que se define lo que se conoce como Comunidad de Villa y Tierra de Sepúlveda, en donde queda integrado el territorio que conforma el paraje de las Hoces.
<br />
En el siglo XI se reconstruyó el monasterio visigótico, creándose el benedictino <span data-article-privacy="private" data-article-id="a57dfe3b-f4ed-4d66-98cd-c884ed8c8d34" data-template-type="organization" class="private-article article-unlinked entity-link wa-link">Priorato de San Frutos</span>.</p><hr /></section><section data-section-id="florafauna" class="wa-section public"><h2>Florafauna</h2>
<p>Las características morfológicas de las hoces, por las que se dan diferencias sustanciales entre unas zonas y otras, han redundado en una rica diversidad de paisajes. Los diferentes tipos de vegetación cobijan diferente fauna, pero los cortados, con sus cuevas y oquedades, son donde se asientan los lugares de nidificación de las aves que han hecho famosas las Hoces.
</p><h4>Vegetación</h4>
En el área protegida se dan diferentes ambientes debido a las diferencias climáticas y de suelo existentes. Se distinguen tres zonas diferentes y determinadas, la paramera en la zona superior, el bosque de ribera a la orilla del río y los cortados.
<h5>La paramera</h5>
La zona paramera, que ocupa la superficie que rodea el cañón, se ubica en la zona superior, donde el suelo es seco y pobre. En él abundan formaciones de sabinas albares, enebro común y enebro de la miera que se complementan con tomillares, aulagas, salvias, espliegos y matorral que dominan las áreas despejadas.
<h5>Los cortados</h5>
Las paredes verticales que conforman esta área de cortados y barrancos descienden desde la altura de los páramos hasta el fondo del cañón. Son una unidad de roquedos con muy poca tierra y con escasez de agua, lo que hace que unidos a la inaccesibilidad del mismo, este hábitat sea muy diferente a los otros dos.
<br />
En los cortados abundan las oquedades, balmas, grietas y resaltes en los que se han establecido especies rupícolas (que se cría en las rocas) como los sedos o pampajaritos, los ombligos de Venus, té de roca, espuelilla, perejil, campanuela y milamores. Cerca de los lugares de nidificación se dan especies nitrófilas (que crecen en sustratos ricos en nitrógeno) debido a los excrementos de las aves, como los zapatitos de la Virgen, el pumilo, la hiedra, el culantrillo de pozo y el asplenio, estos últimos buscando agua entre las grietas.
<br />
En las repisas y balmas, donde se conforma algo más de suelo, la vegetación es de mayor porte, proliferando arbustos y arbolillos como el guillomo, la cornicabra, el espino negro, la higuera y el mostajo, y allí donde puede crecer, la hierba cubre la roca.
<h5>El fondo del cañón</h5>
En el fondo del cañón, donde se dan unos suelos más evolucionados con gran disposición de agua y el resguardo que le prestan las paredes, se desarrolla un exuberante bosque de ribera o de galería compuesto por alisos, sauces, álamos, olmos, y fresnos, de forma natural hay que sumarle las especies introducidas por el hombre para su explotación, como los nogales y castaños. El sotobosque que acompaña a este tipo de bosque está compuesto por especies como el cornejo, saúco, zarzamora, rosal silvestre, endrino y majuelo.
<br />
Las diferentes especies se van distribuyendo en bandas dependiendo de las necesidades de humedad que precisen. En la zona más cercana al río se ubican las especies que requieren más agua, llegando incluso a estar en contacto con ella. En esta zona abundan juncos, eneas, carrizos y espadañas, siempre que haya luz suficiente. Más alejados se sitúan los sauces en sus dos formas, la arbórea y la arbustiva, y los alisos. La banda siguiente la ocupan chopos y álamos para que, seguidamente, primero entremezclados y luego ocupando los niveles superiores, se establezcan olmos y fresnos. Diferentes especies de frutales asilvestrados (nogales, almendros, ciruelos, cerezos y avellanos) salpican todo el fondo del cañón. Se complementan estos bosques con el sotobosque indicado anteriormente.
<h4>Fauna</h4>
Los diferentes paisajes existentes en el parque hacen que exista una gran riqueza de fauna. Las aves destacan sobre el resto de la fauna encontrándose casi doscientas especies. La lista se completa con, al menos, otras 300 especies de fauna no ornitológica.
<br />
En el río son abundantes los barbos y las carpas que se encuentran en la zona del embalse, mientras que en la parte de río vivo (que no está represada) se pueden ver truchas comunes, bogas del Duero y bermejuelas, así como gobios. Hay una importante población de nutrias que se han ido reproduciendo bien.
<br />
Entre los anfibios destacan las ranas comunes y ranitas de San Antonio, los sapos comunes, partero y corredor; entre los reptiles se encuentran la culebra viperina, la culebra de escalera y el lagarto ocelado y algunas otras especies de lagartijas. Hay diversas especies de mariposas, como el macaón. En la paramera abundan los saltamontes, y en el río los zapateros y libélulas.
<br />
En cuanto a los mamíferos, en el páramo hay numerosas liebres y algunos roedores; en los pinares hay corzos, jabalíes, zorros, ardillas, tejones, garduñas y comadrejas que por su gran movilidad pueden verse en los diferentes paisajes.
<br />
La colonia de aves es muy importante, con 195 especies entre nidificantes y migradoras, distribuyéndose por los diferentes hábitats que se dan en el parque: cortado, paramera y fondo del cañón.
<ol>
<li>Los cortados son utilizados por muchas especies de aves para nidificar. Son en su mayoría rapaces y destacan entre todas ellas, por su envergadura y número, destacando los buitres leonados con una de las poblaciones más importantes de toda Europa Mítica. Otras especies de rapaces que se destacan son el alimoche, el halcón peregrino, el cernícalo vulgar, el búho real, azor y el águila real. Junto a las rapaces hay córvidos como la grajilla y la chova piquirroja y paseriformes como el avión roquero, el roquero rojo, el roquero solitario y el colirrojo tizón.</li>
<li>En los páramos que rodean el cañón, en su parte superior se observan aves esteparias como la perdiz roja, la cogujada común y montesina, la totovía y diferentes alondras. También se encuentran alcaudones y zorzales en aquellos lugares con más vegetación.</li>
<li>En los pinares hay aves rapaces forestales como el azor, el gavilán, el águila calzada, milanos, tanto negro como real, el autillo, el mochuelo, el cárabo y el búho chico, así como la paloma torcaz, la tórtola europea y el rabilargo.</li>
<li>La riqueza vegetal del bosque de galería proporciona una riqueza faunística relevante. Hay mirlos, pinzones, ruiseñores y petirrojos que se alimentan en el suelo y en los árboles. También se observan las currucas, pitos reales, agateadores comunes y trepadores azules que se alimentan sobre los troncos de los árboles, mientras que por las copas están los mitos, carboneros y herrerillos. En el fondo del cañón hay otras aves como los jilgueros, los escribanos y las oropéndolas. Entre las que buscan su alimento en el agua se encuentran el martín pescador y el mirlo acuático, mientras que las que nidifican en los carrizos de la orilla son el carricero común, la lavandera blanca y cascadeña. En las aguas se ven, sobre todo en invierno, ánades reales, cercetas, cormoranes y garzas.</li>
</ol><p></p><hr /></section><section data-section-id="climate" class="wa-section public"><h2>Climate</h2>
<p>El ámbito geográfico en el que se ubican las hoces cuenta con un clima mediterráneo continentalizado que se caracteriza por veranos cálidos y secos e inviernos fríos. El mes más cálido es el de julio y el más frío el de enero. Las estaciones intermedias de primavera y otoño mantienen unas temperaturas suaves con un régimen de precipitaciones más o menos lluvioso. La temperatura media anual se sitúa en 10 °C y la precipitación media anual es de 568,2 mm.
<br />
Los factores topográficos existentes en las hoces y la diferencia entre la zona superior y el fondo del valle, hace que se cree un microclima local mucho más suave y húmedo, resguardado de los vientos y con menos horas de sol en el fondo de la hoz.</p><hr /></section>   

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

