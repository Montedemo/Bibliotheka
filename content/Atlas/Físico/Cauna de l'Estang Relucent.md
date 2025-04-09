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
 <section class="wa-section main-content"><p><span class="dropcap">R</span>ED laberíntica de cuevas situada en la cara oriental del macizo del <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="90d13d26-1108-4879-86a9-bd1cdea7df8f" data-template-type="location" data-article="90d13d26-1108-4879-86a9-bd1cdea7df8f">Mont Ternat</span>, en las cercanías de la población de <span data-article-privacy="private" data-article-id="2194b5a2-d086-4505-86eb-1dae4e380d0e" data-template-type="settlement" class="private-article article-unlinked entity-link wa-link">Quier</span> y que desembocan en un gran estanque subterráneo de misteriosas aguas.
</p><div id="3aa72940a996edbeb9177cea85402621" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/895fa76a12a6a29daa576bd54aa28479.png" alt title="sakany 01.png" /></div><hr />
<h3>Descipción</h3>
Al este del Mont Ternat, no lejos de Quier, hay un corte vertical en la roca que forma la entrada a una confusa red de oscuras cavernas. En el interior se escucha el eco de voces un tanto familiares que llevan de aquí para allá retazos de conversaciones tiempo atrás olvidadas h algún que otro nombre de persona. Se las conoce a nivel popular como "La Grieta" o "Las Entrañas de Satán", pero los magi se refieren a ellas como "Las Cuevas del Estanque Reluciente", ya que conocen la existencia de una laguna de aguas quietas y negras que se encuentra en el corazón de las cuevas. Dificilmente accesibles y con una estructura laberíntica de pozos y túneles que desalientan la exploración, el lugar a penas ha sido hollado por pies humanos.
<br />
El estanque huele a azufre, el olor del fuego del infierno, pero no tiene aura infernal, sino mágica de 4, que puede atraer a criaturas mágicas a vivir en la cueva durante cortos periodos de tiempo. Mirar el estanque y plantear una pregunta en silencio produce estrañas visiones. Beber de ella produce náuseas, alucionaciones terrorífias y puede causar la muerte, aunque sorprendentemente el agua sepa a manzanas dulces. En realidad el estanque actúa con una inteligencia curiosa. Se niega a contestar preguntas mundanas o de poca importancia y resulta particularmente útil para los magi. Como regla general, tira un dado de estrés y consulta la tabla de resultados para determinar los resultados de una pregunta. 
<br />
Los magi de <span data-article-privacy="private" data-article-id="2d3840d3-89f2-4d91-9dd9-a767dbedfd26" data-template-type="organization" class="private-article article-unlinked entity-link wa-link">Crista Nebulae</span> tratan al estanque con nerviosismo y respeto y no hacen uso de él con demasiada frecuencia. <span data-article-privacy="private" data-article-id="27be54f7-c263-48d7-b121-c1aa17aacbca" data-template-type="person" class="private-article article-unlinked entity-link wa-link">Óculo</span> advierte que el estanque fue creado por diablos y le preocupa que no se pueda descubrir nada acerca de sus poderes. <span data-article-privacy="private" data-article-id="1ce46194-9c89-4bee-a496-6bbb13c397b9" data-template-type="person" class="private-article article-unlinked entity-link wa-link">Consuelia</span> la fundadora de Crista Nebulae, dijo una vez que el estanque le había dado información engañosa, pero en ciertas ocasiones ha resultado sser de una ayuda inestimable para la alianza, así que los magi recurren a él en tiempos de crisis y cuando hay que tomar decisiones de gran importancia. Tal es el aprecio que sienten por ellas que no han revelado su existencia a sus afiliados de <span data-article-privacy="private" data-article-id="0f9705d5-84cc-44b7-b917-a0c11c18a3c3" data-template-type="organization" class="private-article article-unlinked entity-link wa-link">Miniata Sophia</span>, enfrascados en la resolución de los enigmas que les plantean las vecinas <span data-article-privacy="private" data-article-id="6aa9772c-972e-41ab-af5b-8d75f37de2e5" data-template-type="location" class="private-article article-unlinked entity-link wa-link">Grutas de Nhaus</span>.<div id="b30a3557c2f52f34cea1727ec2d5ee04" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/bfdc5f08bbe86d313740ee96356c3b9a.png" alt title="sakany 02.png" /></div><hr />
<h3>El secreto del estanque</h3>
Las cuevas son en realidad un lugar donde el paso del tiempo se trasforma en algo confuso. Para el estanque el tiempo es irrelevante: pasado, presente y futuro forman parte de un todo sin distinción. Cuando los personajes se adentran en las cuevas, los ecos de su pasado y su futuro murmuran a su alrededor. 
<br />
Fue un demonio quien creó el estanque para tentar a la humanidad y tener a ésta a su servicio a cambio de sabiduría y conocimientos secretos. Sin embargo, en la actualidad el estanque se encuentra habitado por el "fantasma" de un mago Criamon llamado <span data-article-privacy="private" data-article-id="b1b1a893-96c0-407f-9b50-4893bb3571a6" data-template-type="person" class="private-article article-unlinked entity-link wa-link">Custofonus</span>. Este mago derrtó al demonio que había creado el estanque, pero debido a la terrible confrontación que tuvo en el lugar, el mago entró en Crepúsculo. Por eso su fantasma no es tal en realidad: no puede comunicarse ni evolucionar y realmente no piensa ni siente nada. Sería más acertado decir que el estanque encarna los poderes e ideales que Custófonus tenía en el momento de su muerte. Sus ideales eran, y siguen siendo, la búsqueda de la respuesta al Enigma y, en cierta medida, el estanque parece haber escapado de la prisión del tiempo. <br />
Dado que los poderes de Custófonus implican un concepto en el que el tiempo es una ilusión, su victoria sobre el demonio no solo cambió la naturaleza del estanque sino que afectó también a todo lo anterior. Su esencia define la naturaleza del estanque en el pasado, presente y futuro, puesto que para él, los tres son lo mismo. Paradójicamente, Custófonus no tiene necesariamente que haber luchado con el demonio cuando comience la saga.<div id="cc2ecafd4e36edc40586a0483cee08dc" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/1447a5cf1a72d7f990ef20cd485cc3c0.png" alt title="sakany 04.png" /></div><hr /><h3>Ideas para relatos</h3>
Un mago Criamon llega al <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="10eee935-c213-4308-8af4-73b1d428b1ec" data-template-type="location" data-article="10eee935-c213-4308-8af4-73b1d428b1ec">Savarthès</span> y se hace llamar Custófonus. La gente tiene problemas a la hora de hablar con él por su tendencia a responder preguntas aún no formuladas y por contra ignora aquellas que se le han planteado. También habla con personas que no están presentes e ignora a los que si lo están. Custófonus vaga por el valle y puede que profetice respecto a los acontecimientos por venir o también que dé explicaciones a secretos olvidados desde hace mucho tiempo, aunque nunca hará ninguna de las dos cosas como respuesta a preguntas planteadas directamente. 
<br />
Las declaraciones o acciones de Custófonus podrían llevar a los personajes a investigar, por ejemplo, el santuario del <span data-article-privacy="private" data-article-id="4ffc9868-e550-4f80-9e5e-2e577891d899" data-template-type="location" class="private-article article-unlinked entity-link wa-link">Cuerno de Bracel</span>, o podrían también conducirles a un relato de un asesinato ya olvidado o incluso hacia algún tipo de tesoro de cualquier naturaleza. 
<br />
Transcurrido algún tiempo, Custófonus daría con la cueva del estanque reluciente. Llegaría a Ventocaelatus pidiendo la ayuda de la alianza contra lso demonios que ha encontrado en la cueva cercana. Cuando los personajes se aceraran a la cueva sin la compañía del mago no encontrarían ninguna presencia diabólica. Por el contrario, al ir con Custófonus se revelaría una poderosa aura infernal (+6) y la manifestación de un demonio mayor de poder infernal alrededor de 45). El demonio fue el creador del estanque y por lo tanto forma parte de su paradoja del tiempo, de este modo sabe de antemano que Custófonus le derrotará, así que procurará corromper a los personajes antes de ser destruido. 
<div id="21c0230b14d229d3ad7936838cbedb8a" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/d4e488c2d197dc7fdc8a85a78771f393.png" alt title="sakany 03.png" /></div><p></p></section>  <section data-section-id="sidebarcontent" class="wa-section public"><dl><dt>General Details</dt><dd><div id="b6bf5b1ee7ca21e1bc40fed5f80350a0" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/3aeabdbcac884e292c11438c2b21f7c8.png" alt title="entrada de Sakany.png" /></div></dd></dl></section><section data-section-id="sidepanelcontent" class="wa-section public"><dl><dt>General Details</dt><dd><div class="visibility-toggler" id="6ed3cf13906dc93a2f205a19e122c640"> 
          </div></dd><dt class="phrase-key">Aura</dt>
          <dd class="phrase-value"> Mágica, 4 </dd>
         
<div class="visibility-toggler" id="a07525385a9a9aee6e54efea1bf37afa"> 
          <dt class="phrase-key">Regio</dt>
          <dd class="phrase-value"> No </dd>
        </div> 
<div class="visibility-toggler" id="e6b7e14d2e7295f0b82359f717f8eb04"> 
          <dt class="phrase-key">Vis</dt>
          <dd class="phrase-value"> 6 peones de Intellego al año </dd>
        </div></dl></section><section data-section-id="sidebarcontentbottom" class="wa-section public"><h2>General Details</h2>
<p></p><h5>Visiones del Estanque</h5>
<small><div class="visibility-toggler" id="e2eb0d630f533f0c4f268deb109c140d"> 
          <dt class="phrase-key"><b>Pifia</b></dt>
          <dd class="phrase-value"> Visión de un paraíso terrenal en el que aparecen todas las personas que en algún momento han sido amadas por el perosnaje además de todas las cosas que alguna vez ha valorado o deseado. El personaje cree que el estanque le proporciona todas estas cosas y siente un tremendo e irracional deseo de quedarse a la vez que de intentar por todos los medios que cualquier personaje se acerque. Todo personaje que permanezca aquí durante más de una Estación comenzará a desgastarse físicamente. Perderá un nivel de vida por cada estación siguiente a la primera a menos que supere una tirada de estrés de VIT DE 10+. Si pifia perderá dos niveles de vida. </dd>
        </div>
<div class="visibility-toggler" id="270dcec7bd381680e5346fcfd0fb5564"> 
          <dt class="phrase-key"><b>0</b></dt>
          <dd class="phrase-value"> El personaje sufre visiones terroríficas e infernales en las que los secuaces de Lucifer intentan arrastrarle hacia el interior del estanque. Esta experiencia debería ser representada puesto que el personaje puede reaccionar de forma bastante violenta. Si sus compañeros tratan de inmobilizarle para calmarle, les confundirá con tales demonios. En cualquier caso el personaje quedará visiblemente afectado y asustadizo duante el resto de la Estación (añadir un Rasgo de Personalidad Miedo a los Demonios +3). </dd>
        </div> 
<div class="visibility-toggler" id="aed76af1b2f1350795e737a58a13fe44"> 
          <dt class="phrase-key"><b>2</b></dt>
          <dd class="phrase-value"> No hay visión, a excepción quizás de una momentánea aparición de la sombra de una cara (<span data-article-privacy="private" data-article-id="b1b1a893-96c0-407f-9b50-4893bb3571a6" data-template-type="person" class="private-article article-unlinked entity-link wa-link">Custofonus</span>). Sin embargo el personaje sufrirá una sensación de temor, como si se enfrentase a un gran poder. </dd>
        </div> 
<div class="visibility-toggler" id="abea668ffca8ebc21d5072952e035fbe"> 
          <dt class="phrase-key"><b>3-6</b></dt>
          <dd class="phrase-value"> Las visiones son poco claras, ambiguas y engañosas según sea la actitud del personaje del estanque en relación a los móviles del personaje. </dd>
        </div> 
<div class="visibility-toggler" id="e2e9440807fd3241da237bfe6ea4d6db"> 
          <dt class="phrase-key"><b>7-9</b></dt>
          <dd class="phrase-value"> Se experimentarán visiones que sin lugar a dudas se refieren a las preguntas planteadas, pero que no proporcionarán las respuestas a estas de una manera obvia. Estas visiones qizá ofrezcan pistas, advertencias o respuestas veladas a la pregunta. El estanque puede confundir deliberadamente a los personajes cuyos móviles desapruebe. </dd>
        </div> 
<div class="visibility-toggler" id="4374e4844a97cbe3bd295c0e194e0eaf"> 
          <dt class="phrase-key"><b>10+</b></dt>
          <dd class="phrase-value"> Una visión con un mensaje claro, normalmente una respuesta directa a la pregunta que se ha formulado, pero no necesariamente una respuesta completa, aunque sí verdadera y reveladora. </dd>
        </div> 
</small><hr /><p></p><hr /></section>   

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

