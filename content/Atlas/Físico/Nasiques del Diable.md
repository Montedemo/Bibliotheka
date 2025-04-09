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
 <section class="wa-section main-content"><p><span class="dropcap">S</span>ERIE de minas ubicadas entre <span data-article-privacy="private" data-article-id="b46f76d2-773b-45dd-a040-842a4fec9d1c" data-template-type="settlement" class="private-article article-unlinked entity-link wa-link">Belha</span> y el <span data-article-privacy="private" data-article-id="bed5c40d-71fe-4e5b-a5b5-7b7f705c5432" data-template-type="location" class="private-article article-unlinked entity-link wa-link">Caireforc dels Vents</span> que se precipitan tierra adentro por la ladera de la montaña de <span class="article-link article-explorer-link entity-link wa-link" data-article-privacy="public" data-article-id="11da3276-3de9-42f2-aa1e-d5a6141e02df" data-template-type="location" data-article="11da3276-3de9-42f2-aa1e-d5a6141e02df">La Rulha</span> en els Clots de Garsaing bajo un pronunciado promontorio. Convencidos de que se encuentran ocupadas por demonios, los lugareños las han apodado "les Nasiques del Diable" (los Ollares del Diablo) y nadie en su sano juicio en la comarca querrá trabajar allí.
</p><div id="66f8f990adf3b849b3825962bd6fa8cf" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/289d3c10f33b40c1d4df72d7f47da4a4.png" alt title="montedemo_a_series_of_entrances_to_abandoned_medieval_mines_mad_c81c2c98-28c9-4fb7-a299-a4b4832aac24.png" /></div>
<hr /><h3>Historia</h3>
Las minas estuvieron abandonadas durante muchos años antes de la llegada de los magi de <span data-article-privacy="private" data-article-id="da7c2d29-19a8-4212-845a-377cca659708" data-template-type="organization" class="private-article article-unlinked entity-link wa-link">Ventocaelatus</span>, ya que las criaturas que los habitaban ahuyentaron a sus propietarios. Los magi las despejaron y las pusieron en marcha, convirtiéndose en la fuente de ingresos principal de la alianza, que permitió financiar sus grandes construcciones interiores. 
<br />
En aquel tiempo, mucha gente se prestaba gustosa para trabajar en las minas una vez que los "brujos" afirmaron haber derrotado a las bestias que las moraban. Además, el salario era bueno. A parte de los mineros de la zona se reclutaron más trabajadores de Tarascon, de Andorra, e incluso de Fois. Pero pronto sus mentes fueron esclavizadas por Belraphazor siendo obligados a trabajar como autómatas sin recibir nada más que el sustento y el cobijo, hacinados en cabañas malolientes. El trabajo en las minas era peligrosísimo pero la dominación mental les hacía ignorar todo riesgo. Muchos murieron antes de la Tormenta de Almas, e incluso entonces, siguieron trabajando hasta que el fin de Belraphazor les liberó de su esclavizamiento y enloquecidos por la libertad recobrada, destruyeron el lugar y se asesinaron entre ellos o escaparon, relatando el horror del cautiverio sufrido.
<br />Desde entonces han estado abandonadas, no siendo capaces los sucesores de Belraphazor de volverlas a poner en marcha. Nadie en su sano juicio volvería a trabajar allí ni a dejarse engañar. Las minas han permanecido abandonadas desde entonces y, habitadas por las fantasmas y por los demonios de la montaña, se han vuelto inaccesibles incluso para la expediciones enviadas por <span data-article-privacy="private" data-article-id="2d3840d3-89f2-4d91-9dd9-a767dbedfd26" data-template-type="organization" class="private-article article-unlinked entity-link wa-link">Crista Nebulae</span> para intentar volverlas a poner en marcha.
<div id="9a87a467d7927046c979f543683da300" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/0ddd5732bbfd5f6e1cf384c46ca31e56.png" alt title="montedemo_some_spooky_entrances_to_abandoned_mines_carved_on_on_210612a7-23e0-4e86-92fa-b6cd7ead6ec6.png" /></div>
<p></p>
<p>
</p>
<p>
</p><hr /><h3>Descripción</h3>
Las minas se extienden por profundas y empinadas cuevas que afloran en la roca como orificios nasales (ollares) por las que "respiran los demonios de la Rulha" y que se sumergen en la roca. Aquí y allá se pueden ver los pasadizos que, partiendo de los corredores principales, se adentran aún más en las montañas a medida que los mineros seguían cavando incesantemente, desprovistos de más voluntad que la de cavar sin parar.
<br />
En su momento un equipo de más de treinta hombrtes, sin ayuda de los magi (a excepción del suministro de material y herramientas), picaban y machacaban la roca -a menudo, a ciegas-, picaban y machacaban la roca y cargaban los cascotes a sus espaldas. Incluso niños estaban ocupados introduciéndose en los pasadizos más pequeños y en el exterior de las cuevas, las mujeres rebuscaban entre los escombros hasta encontrar alguna piedra que mereciera la pena para ser triturada y fundida. La ladera de la montaña se ha convertido en un vertedero de rocas sin valor.
<div id="4c400f16dbd27d386b646e0404f557ed" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/48782d2a18911892d6cb9027e60db205.png" alt title="montedemo_some_spooky_entrances_to_abandoned_mines_carved_on_on_fa76c1bd-84ef-4ce0-a55c-693b50328850.png" /></div>
<hr /><h4>Los Demonios de la Montaña</h4>
Las minas existían desde tiempos de los godos pero sus antiguos mineros huyeron a causa de los "demonios" que, según se creía, las habitaban. En realidad las perforaciones se habían encontrado con las galerías del hogar de los trasgos de la Rulha, una raza de elementales que habita oculta en las profundidades de la tierra. Los druidas del <span data-article-privacy="private" data-article-id="bed5c40d-71fe-4e5b-a5b5-7b7f705c5432" data-template-type="location" class="private-article article-unlinked entity-link wa-link">Caireforc dels Vents</span> conocían su existencia pero nunca interfirieron con ellos. Lo mismo hicieron después los miembros de la <strong class="article-unlinked">La Alianza Sin Nombre</strong> que siguieron manteniendo las minas inactivas. Pero los magi de Ventocaelatus para asegurarse las minas para su propio disfrute, dirigieron un ataque por los pasadizoa, matando a un gran número de trasgos y encerrando a muchos más en una grupa que sellaron mágicamente. En las décadas que transcurrieron desde entonces solo se les ha vuelto a ver en una ocasión en el que los mineros irrumpieron ciegamente en una gran caverna que estaba atestada de tales criaturas. Ventocaelatus les derrotó de nueo y sellaron una vez más la profunda y recóndita prisión de los trasgos. Pero las progresivas crisis de Ventocaelatus llevaron al abandono de las minas, pobladas en sus galerías por los enajenados fantasmas de los mineros que han seguido cavando y han "liberado" a los trasgos. La misión enviada por Crista Nebulae para apoderarse del lugar al poco de la destrucción de Ventocaelatus relata la presencia de los fantasmas pero también de ojos que brillaban y figuras que se movían en la oscuridad. Los derrumbamientos provocados en la exploración llevaron a los intrusos a echarse atrás. La revitalización de Ventocaelatus impidió a los magi de Crista Nebulae enviar una nueva misión de limpieza, ya que el lugar se encuentra demasiado cerca del Caireforc dels Vents como para no entrar en conflicto abierto. 
<br />
En realidad, mientras los magi de Ventocaelatus llenaban sus cofres con plata manchada con la sangre de los mineros muertos, los trasgos no permanecían inactivos. Su rey, <span data-article-privacy="private" data-article-id="2f755356-8d7b-40e9-b8c1-f3e0614e0116" data-template-type="person" class="private-article article-unlinked entity-link wa-link">Garsaing</span> y los suyos tienen su propia sangre a tener en cuenta. Las dos últimas veces que lucharon contra el mundo exterior sintieron en sus carnes el frío hierro y fueron fustigados por una magia desconcida. Batalla tras batalla fueron cayendo buenos amigos, sus corazones volvieron a la tierra y sus huesos de piedra recubren ahora estancias que nunca volvieron a ser visitadas. Para colmo de injurias, los visitantes se dedicaban a robar las rocas de la montaña. Por lo que a los trasgos respecta, los invasores estaban violando y profanando la montaña. Garsaing planéo venganza. No se trataba de menudencias como provocar derrumbamientos en los túneles (en realidad estos se caían de forma natural debido a la incompentencia de los mineros que, además de no entender de minería, cavaban a ciegas, esclavizados por la alienante magia de Belraphazor y Cellemon. No, Garsaing planeaba una venganza de proporciones épicas, que se vio pospuesta en cuanto los magi dejaron de ejercer su poder sobre los mineros. 
<br />
En una sala de cuarzo en algún lugar muy profundo de La Rulha, guardado por cavernas que se cierran como enormes bocas sobre los que osan adentrarse en ellas, se sienta Garsaing en un trono hecho de un solo bloque de plata pura. Junto a él se encuentra su armadura de cristal puro y su negra espada de obsidiana, testigos constantes de las batallas en las que ha participado. Se pasa la mano sobre la cabeza calva, de pelo gris con la textura del granito. Sus ojos inexpresivos se detienen en cada detalle de todo lo bello que le rodea. Al igual que la propia roca, Garsaing no tiene prisa pero si alguna vez vuelven a molestarle, lo lamentarán.
<br />
Los trasgos emplean su eternidad en crear impresionanes esculturas en mineral de plata pura. En lugar de usar toscas herramientas para sus creaciones artísticas utilizan hilillos de agua mientras acarician la roca en un acto de amor. No hay una soa de sus esculturas que se haya podido realizar en menos de un milenio. Los trasgos también crean música con polvo y roca seca, una música tan suave y lenta que los mortales catalogarían de silencio. Pero es música. Música que trata de la voluptuosa y cruel venganza. Desde su trono, Garsaing permanece sentado y escucha. 
<br />
Si algún nuevo intruso trata de penetrar en sus dominios, será llevado ante Garsaing para que pueda interrogarle acerca de los hábitos y los poderes de los magi. Su venganza llegará muy pronto. Pero "ahora" para Garsaing quizá represente un año. Y pronto puede muy bien tratarse de un siglo.
<div id="f754b6692312c33146794c01d6a0ea5c" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/9469a6ae59dc1385ae7cd02095142ee5.png" alt title="montedemo_a_gigantic_magical_grotto_hall_made_of_quartz_with_wo_f2454b60-7d42-4c94-9f16-cb41294ab665.png" /></div>
<h4>Ideas para relatos</h4>
<h5>El intruso fugitivo</h5>
Uno de los grogs de Crista Nebulae podría haber escapado tras haber sido capturado por los trasgos e interrogado por Garsaing. Quizá solo cree haber escapado cuando ha sido liberado para que actúe como cebo que atraiga a los intrusos sobre los que los trasgos ansían venganza. El grog, capturado a su vez por los hombres de Ventocaelatus, escenificará con todo detalle la personalidad justa de Garsaing y la espectacular belleza de su Corte Dorada y el fastuoso tesoro de estatuas de plata que alberga su palacio. El grog sería encontrado dehidratado y hambriento en una cueva. Para Garsaing tres días no representan nada en su escala de tiempo, luego daría por supuesto que el humano no estaría hambriento ni creería que los humanos diesen ningún crédito al relato del grog, dado que ha estado ausente "tan poco tiempo". Es ahí donde reside el error que podría significar su perdición.
<br />
Si los personajes pudiesen introducirse rápidamente y con precisión por los túneles de los ollares podrían ser capaces de rescatar a alguien desaparecido -partiendo de la base de que supiesen determinar hacia dónde se dirigió. Una posibilidad sería que lanzasen un ataque después de escuchar el relato del Grog o, por otra parte, podrían tender una emboscada a un trasgo para poder interrogarle ellos. Sin embargo, hay que tener en cuenta que estas criaturas son prácticamente insensibles al dolor y, además, un año de cautiverio no representaría prácticamente nada para ellos.
<br /> A menos que los personajes le detrotasen previamente, Garsaing podría incluso obtener su venganza al fin. Su venganza final podría consistir en atraer a los magos hacia la mina y derrumbarla sobre ellos, o encerrarles y ahogarles con las aguas subterráneas, o ambas cosas a la vez. Recordemos que Garsan no tiene prisa y dispone de décadas para planearlo...<p></p></section>   

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

