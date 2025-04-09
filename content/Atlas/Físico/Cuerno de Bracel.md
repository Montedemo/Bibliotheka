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
 <section class="wa-section main-content"><p><span class="dropcap">E</span>L Cuerno de Bracel, también llamado pico de Bracel, es una cumbre de los <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="cb40d9c8-1edb-439a-943c-523f8af04972" data-template-type="location" data-article="cb40d9c8-1edb-439a-943c-523f8af04972">Pirineos Centrales</span> limitando con los Orientales y situado entre los países del <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="10eee935-c213-4308-8af4-73b1d428b1ec" data-template-type="location" data-article="10eee935-c213-4308-8af4-73b1d428b1ec">Savarthès</span> y el <span data-article-privacy="private" data-article-id="fe604f77-4f49-44e0-a765-69a199863169" data-template-type="location" class="private-article article-unlinked entity-link wa-link">País de Sault</span>. Tiene una altitud de 2.222 y forma parte de los picos de altitud mediana de la <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="53792d76-7259-443a-a6ce-9b9cf0698386" data-template-type="location" data-article="53792d76-7259-443a-a6ce-9b9cf0698386">cadena pirenaica</span>. Su forma escarpada y abrupta con una gran caída en sus laderas sur y sudeste (500-1100), la hace destacar en el paisaje de la región y haber sido objeto de leyendas y culto desde muy antiguo. Está ricamente poblado por una abundante y variada fauna pirenaica.
</p><div id="dbfa10669e2442cd326b66f6d5002fa5" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/b51ce525edf79985b21f54b39991cedc.jpg" alt title="640px-Cassoula_Dent_d'Orlu.jpg" /></div><small>Cara norte del Cuerno de Bracel vista desde Mont Alhon</small>
<hr /><p></p></section>  <section data-section-id="sidebarcontent" class="wa-section public"><dl><dt>General Details</dt><dd><div id="0182236ae2edb10777c65dee1ea8d7fa" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/e927cd72c711ccd57aeff4c0f969e6ef.jpeg" alt title="Dent_Orlu_Pyrenees_France.jpeg" /></div></dd></dl></section><section data-section-id="sidepanelcontent" class="wa-section public"><dl><dt>General Details</dt><dd><div class="visibility-toggler" id="c2754528457fecd8334c0ab98008914f"> 
          </div></dd><dt class="phrase-key">Altitud</dt>
          <dd class="phrase-value"> 2222m </dd>
         
<div class="visibility-toggler" id="e6b7e14d2e7295f0b82359f717f8eb04"> 
          <dt class="phrase-key">Vis</dt>
          <dd class="phrase-value"> 12 peones Creo al año </dd>
        </div></dl></section><section data-section-id="sidebarcontentbottom" class="wa-section public"><h2>General Details</h2>
<p></p><div class="articletoc" data-component="article_toc"></div>
<hr /><div id="ca075fe15073b2d43f60944612de8deb" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/020b9fd9e1bf63a4003b3aa846d50640.png" alt title="Bracel02.png" /></div><span data-article-privacy="private" data-article-id="f2dcb2d9-51d1-4503-b86a-5afdb8b7863c" data-template-type="person" class="private-article article-unlinked entity-link wa-link">Bracel</span> 
<hr /><div id="26d488d0942ffcad52f1846bc396ffff" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/2bd5c9968f1db302b798b778d0b4b8a5.png" alt title="montedemo_a_huge_strong_majestic_and_impressive_stag_but_it_has_e0758a97-5c57-420c-8781-30e0b0b258d6.png" /></div><span data-article-privacy="private" data-article-id="3ea5d410-a3bd-4213-9066-dd8af5174b60" data-template-type="person" class="private-article article-unlinked entity-link wa-link">Mawredd</span> 
<hr /><div id="d56897af3d2382ca169d1eb678e6c7d0" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/653e93926cdd2ab0f53613b4934ef0a8.jpg" alt title="Cernunnos - Gundestrupkedlen-_00054_(cropped).jpg" /></div><span data-article-privacy="private" data-article-id="6a85b561-7eef-41ec-b5c0-449534fd8056" data-template-type="person" class="private-article article-unlinked entity-link wa-link">Cernunnos</span> 
<hr /><p></p><hr /></section><section data-section-id="alternativename" class="wa-section public"><dl><dt>Alternativename</dt><dd>Pic de Bracel</dd></dl></section><section data-section-id="geography" class="wa-section public"><h2>Geography</h2>
<p>El monte del Cuerno está situado en el borde oriental de los <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="cb40d9c8-1edb-439a-943c-523f8af04972" data-template-type="location" data-article="cb40d9c8-1edb-439a-943c-523f8af04972">Pirineos Centrales</span> al norte del eje central de la cordillera. Delimita por el norte el valle del río <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="667995e7-5273-4b4b-924a-7f1e37bffcf6" data-template-type="location" data-article="667995e7-5273-4b4b-924a-7f1e37bffcf6">Orièja</span> y por el sur el del río Lauza, así como los países del Savarthès y Sault.
<br />
Con su altitud de 2.222 metros, ofrece una bella vista sobre el valle y tiene una forma particularmente escarpada y abrupta hacia su cara sur. 
<br />
El monte del Cuerno está desprovisto de corrientes de agua perennes. Ninguno de sus arroyos y ríos de la <span data-article-privacy="private" data-article-id="e2c46db9-4b49-46a6-87ea-c6b5624a95f3" data-template-type="location" class="private-article article-unlinked entity-link wa-link">Val de Orlu</span> tienen su fuente en el pico del macizo. Sus principales barrancos o ramblas son el rec de Bracel y el rec de la Tremtja, ambos afluentes del Orieja. 
</p><div id="01bd2d23d1ee63e25136ae0669de0092" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/58a01376aaa797147501c5cd38de7bf4.jpg" alt title="640px-Dent_d'Orlu_08-20.jpg" /></div>
<hr /><p></p><hr /></section><section data-section-id="naturalresources" class="wa-section public"><h2>Naturalresources</h2>
<p></p><h4>Fuente de Vis</h4>
Las bellotas del roble solitario que se alza en su cumbre recolectadas a principios del otoño, ofrecen 12 peones de vis Creo al año.
<div id="3467e1890ed5493058c391c46614880d" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/a65aabce800ddf546e974f528530d4cb.png" alt title="el roble de Bracel.png" /></div><p></p><hr /></section><section data-section-id="history" class="wa-section public"><h2>History</h2>
<p>Hace muchos siglos, antes de que los romanos conquistasen la Galia, se erigía un santuario en lo alto del Monte del Cuerno. Estaba dedicado a un antiguo dios al que los invasores romanos llamaron Cernunnos e identificaron con Pan. Era una deidad astada de la fertilidad que reinaba sobre los animales del bosque. Durante la dominación romana los nativos continuaron adorando al dios en secreto, e incluso se llegó a reconstruir el santuario en la cima del monte alla por el siglo IV d.C. Sin embargo, la llegada del Cristianismo supuso un terrible golpe para la deidad, que tuvo que retirarse a Arcadia.
<br />Aún hoy en día algunos habitantes del Savarthès hablan de un antiguo dios que vivía en las montañas y algunos afirman que han visto a su compañero, un enorme ciervo. Existe todavía un pequeño santuario dedicado a ese dios en el Monte del Cuerno y algún que otro ingenuo, de vez en cuando cava agujeros en busca de un tesoro que se dice fue enterrado en el lugar. En la <span data-article-privacy="private" data-article-id="e2c46db9-4b49-46a6-87ea-c6b5624a95f3" data-template-type="location" class="private-article article-unlinked entity-link wa-link">Val de Orlu</span> particularmente en el pueblo de <span data-article-privacy="private" data-article-id="4b38a6c0-31cc-421e-a8e2-1818b7e2d105" data-template-type="settlement" class="private-article article-unlinked entity-link wa-link">Orlun</span>, la gente del pueblo todavía celebra un festival en honor del antiguo dios el día primero de mayo. Se organiza un gran banquete en el que la efigie de paja de un hombre astado preside la mesa. aunque los curas del valle rezan oraciones cristianas antes de la comida, está claro incluso para ellos que el banquete es una celebración pagana. 
<br />
La leyenda atribuye al Diablo la extraña forma de la montaña:
<br />
</p><blockquote class="visibility-toggler" id="9958b598932cdcd65467898edc2e3733">
 "Satanás mientras viajaba alrededor del mundo, cruzando las montañas con sus alas poderosas, calculó mal su vuelo y cayó con tanta desgracia que se rompió un cuerno, dejándolo allí clavado para siempre".</blockquote>
<div id="3251aff9abf84788e0bbc95a90afebac" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/cbbc251127b4b4c69fff17b2eb990dcf.jpg" alt title="640px-Rando_Bonascre_2019_(19)_Dent_d'Orlu_Tarbesou.jpg" /></div>
<hr /><p></p><hr /></section><section data-section-id="tourism" class="wa-section public"><h2>Tourism</h2>
<p>Para un observador mundano, el Monte del Cuerno no deja de ser como otro cualquier accidente geográfico peculiar al que la gente sencilla venera. En realidad, el monte tiene distintos niveles de regio que al franquearse adentran al viajero dentro del mundo Feérico, junto con los habitantes sobrenaturales que residen en él. El mapa indica la localización y los límites de los distintos niveles de Regio.
<br />
</p><h4>El Nivel Mundano</h4>
Si un visitante no puede o no quiere pasar a los niveles de Regio feérica y solo visita el nivel terrenal, el monte le parecerá de lo más común, aunque hermoso, pintoresco y particularmente abundante en fauna salvaje. En lo alto de la cima hay un gran roble que desafía las inclemencias y cuyas ramas han sido adornadas por los aldeanos con guirnaldas de flores secas y harapos hechos jirones. Situado debajo de las ramas se pueden verlos restos de un improvisado refugio y parece que no hace mucho el lugar sirvió de morada para algún vagabundo.
<div id="59b8dd365945de3d4adb7884ea9ddb5e" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/72f30e730ff1c4df0f8a94714ce4132b.png" alt title="montedemo_a_lone_huge_majestic_oak_tree_on_top_of_Dent_dOrlu_pe_a80f94ce-7c3d-47cf-b5bc-fb3182874004.png" /></div>
<h4>El Primer Nivel (Aura 1)</h4>
El primer nivel de regio feérica existe justo por "encima" del nivel terrenal y tiene un aura feérica de 1, extendiéndose por toda la montaña y sus laderas. Aquí el monte presenta una apariencia distinta a la del nivel terrenal y podemos encontrarnos con un santuario del que se ocupan gillet y su familia, que veneran al antiguo dios del monte.
<br />
De las ramas del árbol cuelgan cintas de colores y flores que se mantienen frescas durante meses después de ser cortadas. También hacen ofrendas de comida que colocan en el recio refugio de madera que han construido para albergar el improvisado santuario. en algunas ocasiones, Gillet incluso duerme allí con la esperanza de tener algún sueño profético. El santuario consiste tan sólo en una mesa donde reposan una vieja cornamenta y las frecuentes ofrendas de Gilet.
<br />
Gillet es un hombre libre, sencillo, que susbsiste de lo que puede sacar de los campos limítrofes de Orlun. Se ocupa del santuario al giual que su padre antes que él, con la convicción de que sus ofrendas vayan a parar a manos de duendes y poderes ancestrales que salvaguardan la fertilidad del pueblo. Gillet vive ignorante del verdadero poder que reside en el Monte. Tanto él como su familia pueden moverse libremente dentro y fuera del primer nivel de regio y reciben un trato de respeto considerable por parte de los aldeanos locales, que les rinden honores como servidores de los poderes antiguos. Sin embargo, los miembros de la familia no acaban de entender el Reino Feérico en el que penetran. Simplemente creen que los Poderes tienen un lugar en el que hay que dejarles ofrendas.
<br />
<div id="a7b8b40df3dd4b7d87997fee1e1c2743" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/36486229dfbc38355b01aa42377faed0.png" alt title="montedemo_a_lone_huge_majestic_oak_tree_on_top_of_Dent_dOrlu_pe_d540e2fc-05d0-4c5f-846a-64102c725a8c.png" /></div>
<h4>El Segundo Nivel (Aura 3)</h4>
Por encima del nivel feérico que alberga el rústico santuario de Gillet hay un reino de mayor poder. Allí el roble es más nudoso que en los niveles inferiores. Hay una sala de madera, no una choza o santuario, protegida entre las ramas del árbol. Es el hogar de <span data-article-privacy="private" data-article-id="f2dcb2d9-51d1-4503-b86a-5afdb8b7863c" data-template-type="person" class="private-article article-unlinked entity-link wa-link">Bracel</span>, la personificación de la "memoria" colectiva sobre el antiguo dios Cernunnos. Bracel parece un hombre anciano de aspecto enfermizo que viste con harapos y lleva un pesado torques de oro alreadedor de su cuello. Su apariencia y poder reflejan el grado de reverencia de la gente hacia la deidad. Si la gente del valle se olvida deldios, Bracel se desvanecerá pero si renuevan su adoración hacia la antigua divinidad, Bracel crecerá en poder, fuerza y tamaño.
<br />
La sala contiene mobiliario celta sencillo, incluida una mesa con comida que corresponde al altar del nivel de Regio inferior. Cuando Bracel retira comida de la mesa desaparece alguna de las ofrendas del santuario de Gillet. Dado que Bracel muestra interés por comer en muy contadas ocasiones, con frecuencia arroja alimentos a los animales que viven en los alrededores de su sala en este nivel de regio. Un detalle a destacar en la sala es una capa de piel de ciervo y un tocado con astas que cuelgan de un clavo en la puerta.
<br />
El aspecto más notable de este nivel de Regio son sus animales. El área que rodea la sala está habitada por gran numero de criaturas del bosque: desde ardillas y urogallos hasta rebecos y lobos, todos ellos dotados de gran astucia e inteligencia, aunque están privados de la facultad del habla. Son criaturas musculosas y ágiles, pero también tienen pellejos caídos y ojos fatigados. En realidad la mayoría parecen bastante viejos. 
<br />
El jefe de todos estos animales es <span data-article-privacy="private" data-article-id="3ea5d410-a3bd-4213-9066-dd8af5174b60" data-template-type="person" class="private-article article-unlinked entity-link wa-link">Mawredd</span> (que significa "majestad" o "nobleza"). Es un enorme ciervo que tiempo atrás acompañó por el mundo a Cernunnos antes de que éste se retirase a Arcadia. Tiene el tamaño de un caballo y la fuerza de un toro, pero tiene un aspecto cansado y envejecido. En ciertas partes de su cuerpo se puede ver cómo tiene la piel arrugada, lo que muestra que un día fue todavía más poderoso y fuerte de lo que es hoy. Su pelaje ha perdido el brillo, se muestra apagado y ha desaparecido en algunos sitios. El rostro de Mawredd refleja un gran cansancio, tristeza y desdén. Es el único animal que posée la facultad del habla, pero ya no cree que exista nada en el mundo que merezca la pena ser comentado.
<h5>Relaciones con Bracel</h5>
Si los personajes consiguen introducirse en el Regio feérico del <span data-article-privacy="private" data-article-id="4ffc9868-e550-4f80-9e5e-2e577891d899" data-template-type="location" class="private-article article-unlinked entity-link wa-link">Cuerno de Bracel</span> serán bienvenidos en la sala de Bracel, quien no se caracteriza precisamente por ser un anfitrión cálido y acogedor, pero proporcionará comida y descanso a los que estén cansados y hambrientos.
<br />A Bracel le interesan bien poco los objetivos y necesidades de sus huéspedes. Únicamente muestra interés por las noticias sobre la convicción religiosa de la gente en el mundo exterior. Aislado en su sala, Bracel recibe muy poca información sobre la dedicación que la gente tiene hacia Cernunnos y solo puede conocerla a través de las fluctuaciones de su poder. La única forma de conseguir la ayuda de Bracel en algún asunto terrenal es prometiéndole que se difundirá la palabra de Cernunnos. Soi los personajes pueden proporcionar los medios para restablecer la adoración al antiguo dios astado, entonces Coffa les ofrecerá sus servicios. 
<br />
Las amenazas físicas o mágicas no le afectan demasiado. Siente que su presencia y existencia en el mundo son limitadas y a medida que se desvanecen sus poderes se da cuenta de cómo se propagan otras creencias. Solo así se podría destruir a Bracel, que se defenderá con poca convicción.
<div id="74d2eebc4805f43560fd011ad59f3ce9" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/44668222c2f24f56bd2e7b79275adf93.png" alt title="montedemo_a_lone_huge_majestic_oak_tree_on_top_of_Dent_dOrlu_pe_2f033776-14be-4af1-9799-6ea69ec721fa.png" /></div>
<hr /><h3>Ataques al Monte del Cuerno</h3>
Las agresiones al Monte del Cuervo y a sus ocupantes podrán tener un efecto devastador para la religión del Monte e incluso para la Europa Mítica. La furia de Cernunnos tomará una u otra forma dependiendo de qué o quién sea destruido en el ataque.
<br />
Destruir el santuario de Gillet o la sala de Bracel provocaría la esterilidad a mujeres y animales del valle al menos durane un año y no habría manera de sacar las cosechas adelante. A menos que se reconstruyese el santuario o la sala, las cosechas seguirían sufriendo y nacerían muy pocos niños y animales.
<br />
Del mismo modo, si no se realizase el festival anual en honor a Cernunnos, quizás porque lo impidiera la iglesia, se sufriría una esterlidad semejante.
<br />
Si alguien matase a Mawredd todos y cada uno de los bosques feéricos de la Europa Mítica se verían afectados. Estos bosques retrocederían y aquellos más fuertes (los que tengan auras feéricas o mágicas de ocho a diez) se volverían un poco más débiles perdiendo un punto de Aura. Aunque tales cambios pasarían desapercibidos para ojos mundanos, la gente con mayor percepción notaría que los duendes se han visto forzados a retirarse al inerior de los bosques. Además, algunas entradas a Arcadia podrían cerrarse para siempre.
<br />
Si los personajes estuviesen directamente implicados en la muerte de Mawredd se convertirían en los odiados enemigos de muchos duentes y ganarían una mala reputación de nivel 10 entre todos los duendes de Europa Mítica. 
<br />
Bracel es la personificación de la memoria humana sobre Cernunnos. Si es asesinado, la gente de Orlun y de todo el Savarthès le olvidarían inmediatamente. No se repetiría la fiesta anual. Si se diesen estas condiciones, la misma esterilidad y hambruna que anteriormente se ha descrito afectaría a la totalidad del valle.
<br />
Una vez que Cernunnos sea olvidado en el Savarthès, su memoria y la de los festivales solo podría ser evocada por las preguntas y relatos de un forastero, quizá alguien que tenga lazos con los duendes y que gracias a esto no olvidara a la divinidad. Si alguna fuerza exterior consiguiese que la gente del valle recordase al antiguo dios y además volviesen a adorarle, Bracel resucitaría y se salvarían de una total y segura destrucción.
<h4>La Maldición</h4>
Los criminales que asaltasen el Monte del Cuerno no se librarían del sufrimiento que provocarían. Estos individuos se verían afectados por la maldición de Cernunnos. Dicha maldición afectaría a la fuerza y virilidad de sus víctimas y sería equivalente al Defecto Mayor Sobrenatural. En los momentos cruciales, tales como situaciones deseperadas en combate, las víctimas se verán debilitadas o exhaustas. A menos que se supere una tirada de VIT de 7+, la víctima gana automáticamente un -3 a la fuera y un nivel de Fatiga a Largo plazo. El penalizador a la fuerza se elimina cuando se recupere el nivel de fatiga. Si se pifia la tirada de Vitalidad, el sujeeto padecerá una esterilidad permanente. Toda criatura del sexo masculino tocada por la víctima perderá la fertilidad durante un año. Aunque se supere la tirada de Vitalidad, se pederá un nivel de Fatiga a Corto Plazo.
<div id="da8f75ae51b3b7e094e6247f22cae148" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/239c42e402b21a6dc10a4f9043434ab1.png" alt title="montedemo_a_huge_strong_majestic_and_impressive_stag_but_it_has_b822cd66-a9ab-40ff-b86e-2e132e43ade7.png" /></div><small><b>Mawredd</b></small>
<hr /><h3>Ideas para relatos</h3>
Los personajes podrían investigar el Monte del Cuerno si estuviesen interesados por los rumores sobre deidades antiguas o si tuviesen la esperanza de encontrar una nueva fuente de vis en el lugar. Si el santuario fuese destruido o se prohibiese la fiesta, los aldeanos podrían ir en busca de los magos cuando viesen que tanto ellos como sus animales se han vuelto estériles. El santuario podría ser destruido y la fiesta prohibida gracias a los esfuerzos de los cruzados o a los monjes de San Martín por eliminar el paganismo y la herejía. 
<br />
Podría ocurrir que unos mercenarios encontrasen el camino hasta la sala de Bracel y que robasen alguna de sus pertenencias (quizá el tocado o su torques). Bracel podría ponerse en contacto con los personajes para pedir ayuda ofreciendo virilidad y fuerza a cambio. ¿Qué razón impulsó a los mercenarios a robar las posesiones de Bracel? Podrían estar en realidad trabajando para otra alianza. ¿Cómo se las arreglaron para encontrar el camino hasta el regio de Bracel?
<div id="55c91260606f05f1443ac9a134d5c26b" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/5e990c1cfc6721baa9ecfb7eb24574a1.png" alt title="montedemo_a_lone_huge_majestic_oak_tree_on_top_of_Dent_dOrlu_pe_7e5f4a86-6feb-447d-95e5-c7f0ecb652ab.png" /></div><p></p><hr /></section><section data-section-id="florafauna" class="wa-section public"><h2>Florafauna</h2>
<p>La diversidad de condicioens climáticas es el origen de una importante diversidad florística y faunística en la zona. De hecho, la diversidad de hábitats: prados, páramos, bosques, humedales, acantilados) forman un componente esencian en la riqueza natural del entorno.
</p><h4>Fauna</h4>
<ul>
<li>Los rebecos son particularmente abundantes en el Cuerno de Bracel, siendo el animal más característico, además de ciervos, corzos y jabalíes.</li>
<li>El urogallo o faisán de los Pirineos, también apreciado como manjar de las mesas de los nobles;</li>
<li>Comadrejas, martas, armiños y nutrias;</li>
<li>Zorro rojo, lobo gris, oso pardo;</li>
<li>Desmán de los Pirineos</li>
</ul>
<h4>Flora</h4>
El Cuerno de Bracel posée en su base una flora extremadamente rica. En cambio, su cumbre está totalmente desprovista de árboles, donde se pueden encontrar flores de extrema rareza como la genciana amarilla, la drosera de hoja redonda, la lirio de los Pirineos, la genciana burser y la fritillaria de los Pirineos.
<br />Paradojicamente, la cumbre presenta la extraña y solitaria presencia de un roble testigo que desafía solitariamente altitud e inclemencias.
<div id="53995fb4772df6d1d4830b2dd6d9c851" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/3fb7fb41726b71ceaf4b3b4d1ec84c6d.jpeg" alt title="sarrio2.jpeg" /></div>
<hr /><p></p><hr /></section>   

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

