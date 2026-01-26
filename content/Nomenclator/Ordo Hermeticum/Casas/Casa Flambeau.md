---
Tags: Category/Group/Hermetic
categoria: Organización
clase: Hermética
tipo: Casa Hermética
subtipo: Sociedad
Region:
  - Europa
TribFav:
PrimaryHome: Castra Solis
Gobierno: democracia
superior: Orden de Hermes
Vinculo: 
Reputaciones: 
Poblacion:
Founded: 
Founder: 
Disbanded:
Leader: Garus
NoteIcon: hermetic
---

> [!infobox]
> # `=this.file.name`
> ![[image-616.png]]
> ###### `=this.categoria` `=this.clase` 
>  |   |
> ---|---|
> Tipo |  `=this.tipo`|
> Estructura  | `=this.subtipo`|
> Domus Magna | `=this.PrimaryHome`|
> Ámbito | `=this.region`|
> Población  | `=this.Poblacion`| 
> Tribunales favoritos   | `=this.TribFav`| 
> ###### Política  
>  |   |
> ---|---|
> Primus | `=this.leader`|
> Parte de | `=this.superior`|
> Vínculos con | `=this.vinculo`|
> Sistema de gobierno | `=this.Gobierno`|
> ###### Historia 
>  |   |
> ---|---|
> Fundador/es | `=this.Founder`|
> Fundado en | `=this.Founded`|
> Disuelto en | `=this.Disbanded`|
>###### Instituciones y organizaciones 
>```dataview
TABLE WITHOUT ID link(file.name) AS "Grupo", tipo
from "3. Personajes y Organizaciones 🧑‍🤝‍🧑/Grupos/1. Hermeticum/Grupos hermeticos"
where contains( Casa, this.file.name)
SORT file.name DESC
>```
> ###### Miembros Clave
>```dataview
TABLE WITHOUT ID link(file.name) AS "Figuras", Titulo, ☠
from "3. Personajes y Organizaciones 🧑‍🤝‍🧑/Personajes"
where contains( Casa, this.file.name)
SORT file.name DESC
>```
>###### Alianzas Dedicadas
>```dataview
TABLE WITHOUT ID link(file.name) AS "Alianzas", Tribunal
from "3. Personajes y Organizaciones 🧑‍🤝‍🧑/Grupos/1. Hermeticum/Alianzas"
where contains( Casa, this.file.name)
SORT file.name DESC
>```

# `=this.file.name`

> [!cite]
> _¿De qué vale esta magia si nosotros no la usamos? ¿Que tan bueno es un hechicero que solo se sirve a sí mismo? El poder, en sí, es nada. La verdadera medida de un mago no es cuanto poder maneja, sino la dignidad de la causa en la que se ejerce._ 
— Flambeau 

La casa Flambeau es una fraternidad frágil de magi de la [[Orden de Hermes]], atraídos por sus tendencias guerreras y su amor por la aventura. Mientras que otros magos a veces los consideran una chusma rebelde y violenta que debe mantenerse bajo control, el valor de la Casa Flambeau y su capacidad de lucha han ayudado a la Orden de Hermes a sobrevivir a las peores crisis de su historia. 

Los magi Flambeau se ven a ellos mismos como guerreros mágicos. El combate no es necesariamente su _raison d’être_ , pero están preparados para luchar cuando sea necesario. Algunos piensan en sí mismos como el análogo hermético de caballeros mundanos: guerreros de élite encargados de defender a los débiles y defender la justicia. Al igual que los caballeros mundanos, los magos Flambeau tienden hacia la bravuconería. 

Cuando los magos piensan en la casa Flambeau, la gran mayoría, piensa en la magia de fuego. Flambeau el fundador fue el primer y más famoso maestro del arte de Ignem. Mientras que la magia del fuego sigue siendo popular dentro de la Casa, no es la única especialidad practicada por sus miembros. 

En sus corazones, los seguidores de Flambeau creen que la magia está destinada a ser usada. Admiran el logro sobre todo, aunque cada magi dentro de la casa sigue su propio camino a la gloria personal. Esto podría ser cualquier cosa desde luchar con enemigos perdidos de la orden, a dirigir un movimiento político hermético, a escribir grandes libros para aclarar e inspirar futuras generaciones de magos. Esta es una Casa vigorosa y activa, profundamente implicada en todos los aspectos de la sociedad hermética. 

> [!summary]  **Puntos Clave** 
**Población:** 114 (19 en el Tribunal de Provenza) 
**Primus:** [[Garus]], un Ex-soladado de fortuna y campeón de torneos, ahora entrado en años. Miembro destacado de los [[Milites]], una facción que promueve la caballería y el servicio a la Orden. 
**Domus magna:** [[Castra Solis]], un modesto castillo en el [[Tribunal Provenzal]]. 
**Tribunales Preferidos:** Tradicionalmente Iberia, Provenza, y Normandia, pero los magi Flambeau viajan largas distancias en busca de aventuras. En las décadas recientes, se han instalado cada vez más en Novgorod, Thebas y el Tribunal de Levante. 
**Lema:** Ad mortem incurramus (“Hasta la Muerte, Carguemos”). Fue adoptado durante la Guerra del Cisma y ha permanecido desde entonces. 
**Simbolo:** Un Reloj de Arena. Para la Casa Flambeau, simboliza tanto el lapso fugaz de una vida mortal como la intemporalidad de los hechos legendarios.

> [!important] Figuras famosas
> [[Apromor]]: El aprendiz más antiguo de Flambeau y el primer Primus de la casa. Apromor lideró los esfuerzos de la Casa Flambeau para reclutar activamente magos paganos. Finalmente se apartó de la magia del fuego para concentrarse en hechizos de destrucción.
[[Elaine]]: El segundo aprendiz de Flambeau. A Hoplita, Archimago, notable estudiosa y Autora, entrenó a cuatro aprendices y estableció firmemente el linaje directo del Fundador. 
[[Kaeso]]: Fundador de la tradición Mitraica dentro de la casa Flambeau. 
[[Entisimon]]: Primus que reunió su Casa durante la Guerra del Cisma y más tarde fue deshonrado en la Crisis de Normandía.
**Cindrallon**: Una aprendiz Flambeau que fue juzgada por los ancianos de la Casa de haber pasado la Prueba (Gauntlet) matando a un magus renegado. Ella había completado su aprendizaje en solo siete años.

---

## Historia 

[[Flambeau, el Fundador]]es más bien una figura bastante oscura. Dejó pocos escritos, en parte porque aprendió las letras tarde en su vida y nunca se sintió cómodo con una pluma en la mano. Lo que la Orden sabe de él proviene de las memorias de su filii, y de las pocas cartas que sobreviven dictadas del fundador a este. 

Detalles como la edad exacta de Flambeau, el lugar de nacimiento, e incluso su nombre cristiano se pierden a la historia. Nació en una familia de pequeños nobles en [[Gascuña]], probablemente hacia el año 715 DC. Su patria familiar fue atrapada en el camino del ejército invasor árabe de Emir Abd al-Raman, que atravesó los [[Pirineos]] y avanzó por Francia en 732. El rey franco **Carlos Martel** repelió a los moros en la batalla de Tours (10 de octubre de 732) Pero antes de esa batalla los invasores dejaron una franja de destrucción a lo largo de su marcha hacia el norte. Los moradores árabes atacaron y quemaron la finca familiar del joven Flambeau, matando a sus parientes. Flambeau fue disparado con una flecha y dejado para morir. Los siervos supervivientes lo encontraron y lo cuidaron lo mejor que pudieron, pero su herida se ulceró y el languideció de fiebre. Los campesinos llevaron al joven enfermo a un ermitaño local que era conocido por sus habilidades curativas. Este era [[Laberius]], un mago cuya magia descendía del antiguo[[Culto de Mitra]]

Laberius inmediatamente reconoció el potencial mágico de Flambeau. Se dedicó a cuidar al joven Flambeau hasta que estuvo sano y entonces comenzó a entrenarlo como su aprendiz. Flambeau demostró ser un alumno apto, pero testarudo. Se enfadó con el misticismo pagano que subyacía en los hechizos rituales de su Maestro y se dedicó a intentar modificar los encantamientos para que funcionaran sin mencionar a los dioses paganos. 

Laberius percibió una oportunidad de ganar una posición como un brujo de la corte ofreciendo ayudar a los cristianos contra los moros. Los francos rechazaron sus insinuaciones, por lo que él y su aprendiz viajaron al Reino de [[Asturias]] en el norte de España. Allí, fue recibido como mago de la corte para un primo menor de la casa real. Laberius y su aprendiz servían siempre al lado de su señor, incluso luchando junto a él en las primeras batallas de la Reconquista.  Con la ayuda mágica de Laberius, su señor mundano disfrutó de un gran éxito asaltando y realizando escaramuzas contra los moros. Al tercer año de la campaña, los moros llegaron a sospechar que sus enemigos tenían ayuda mágica. Reunieron un grupo de cinco o seis sahires (Convocadores de Jinii) para cazar y destruir sus enemigo magicos. Los [[Sahires]] atrajeron a Laberius y a su patrón hacia una emboscada. El joven hombre en que se había convertido Flambeau logró escapar con su vida, pero su maestro, su señor mundano y la mayoría de los caballeros y hombres de armas fueron masacrados por los [[Jinn]] (genios) de los Sahirs. 

El aprendiz de Laberius juró vengar a su Maestro. Intentó encontrar a un miembro de la tradición mágica de Laberius con quien pudiese terminar sus estudios, pero los pocos magos que se encontró le recibieron con desconfianza o con hostilidad absoluta. 
Finalmente se escondió en una cueva en la vertiente septentrional de los Pirineos y continuó sus estudios mágicos solo. A través del ensayo de la prueba y el error adaptó un hechizo sencillo que Laberius le había enseñado, usado solo para encender braseros ceremoniales, y lo uso para producir chispas y llamas cada vez más grandes. 

Después de cinco años de reclusión, había perfeccionado un ataque único y poderoso similar a [[Lanza de Fuego (CrIg20)]]. Fue entonces cuando adoptó el nombre de guerra **Flambèl** y regresó a Iberia para vengar la muerte de su maestro. Flambèl  logró cazar a tres de los sahires que habían matado a Laberius, pero los demás se le escaparon. Después de pelear con varios Jinn infernales, Flambeau se convenció de que todos los Sahires eran Invocadores de demonios, y los atacaba cada vez que los encontraba. 

Había matado a una docena de hechiceros moros y se había convertido en uno de los magos más temidos de la Europa mítica cuando [[Trianoma, la Fundadora]] se le acercó con la oferta para unirse a la Orden. 

### Flambèl y la Joven Orden

Al principio, Flambeau era escéptico acerca de la idea de un orden de los magos. Tenía una profunda desconfianza hacia los magos de todo tipo, incluso miembros de su propia tradición, y no creía que la alianza de magos de Trianoma pudiera durar. Después de Trianoma le demostró la eficacia del Parma Magica contra los hechizos hostiles, Flambeau se dio cuenta de que estaría en una severa desventaja si no aprendiera su secreto. Accedió a viajar a [[Durenmar]] y escuchar lo que [[Bonisagus, el Fundador]] y los otros Fundadores tenían que decir. 

Trianoma le pidió permiso a Flambeau para extender su propia Parma Magica sobre él antes de conocer a cualquier brujo de Durenmar. Ella le dijo que lo protegería contra la traición, pero también lo protegía de la desconfianza y la hostilidad engendrada por el Don de otros magos. Para sorpresa de Flambeau, encontró a los otros Fundadores como dignos de confianza y simpáticos. Llegó a creer en la Orden como una liga de magos honorables que podrían poner fin a la traición y las rivalidades mezquinas tan comunes entre los magos europeos antes de la Fundación. Esperaba construir la Orden en una alianza militar que pudiera destruir la putativa [[Orden de Suleiman]].  

Como todos los fundadores, Flambèl hizo algunas contribuciones a la teoría hermética. Su logro de haber inventado un hechizo único y original demostraba que tenía más talento en el laboratorio de lo que su violenta reputación podría sugerir. Sin embargo, sus contribuciones fueron modestas en comparación con las de algunos otros Fundadores. Flambèl estaba más interesado en aplicar la teoría de Bonisagus que en extenderla. Él pronto inventó muchos nuevos hechizos, ampliando enormemente su repertorio personal. 

Más tarde en su carrera, pasó años buscando maneras de superar la Parma Mágica, en el caso de que el secreto de la misma cayese alguna vez en manos enemigas. En este trabajo fue pionero en el estudio de la penetración como una habilidad arcana. Lo cierto es que las contribuciones más duraderas de Flambèl fueron en la política, no en la investigación. Para expandir la nueva alianza de magos, viajó por lo que ahora son los Tribunales de Normandía y Provenza, reclutando tantos magos como pudo. Resultó ser un negociador capaz. 

El peso de su reputación era suficiente para hacer que los brujos no herméticos estuvieran dispuestos a hablar con él en lugar de pelear, y una vez que tenía su atención, era carismático y persuasivo. Su entusiasmo por la Orden era contagioso. Aunque entrenó sólo a dos aprendices, la Casa creció rápidamente a través del reclutamiento. Cuando la Orden era joven y sólo contaba con unas pocas docenas de magos, parecía existir el riesgo de que los magos no herméticos se organizaran para resistir su expansión. A través de una combinación de diplomacia, intimidación y algunas batallas bien elegidas, Flambèl trabajó para anular amenazas de los hechiceros ajenos a la orden. Juntos, Flambèl y sus seguidores fundaron la Alianza de [[Val-Negra]] en los [[Pirineos]], lugar oculto e inaccesible elegido por su valor estratégico frente a los Sahires de la Iberia morisca. Con el tiempo, la ventaja estratégica de su ubicación se volvió menos importante para el Fundador, ya que centro sus esfuerzos de luchar contra los sahires y ayudar a construir y fortalecer la Orden.

### La controversia sobre la Guerra de Magi

> [!cite]
> _Este Juramento defiende nuestra seguridad, pero ¿quién defenderá nuestro Honor?_ 
— Flambeau 

Flambèl vino a apoyar la idea de Bonisagus para una Orden de brujos, pero rechazó la primera versión del Juramento Hermético. Le preocupaba que si juraba el juramento, sus enemigos pudieran escapar de su venganza uniéndose a la Orden. 

En el Primer [[Gran Tribunal]], no estaba claro exactamente cómo la Orden cumpliría su propio Código. [[Guernicus, el Fundador]] aún no había aceptado convertirse en el primer Quaesitor, y ni [[CERTAMEN]] ni el [[Código Periférico]] existían. Flambeau había pasado su vida adulta luchando contra magos moriscos en Iberia. Creía firmemente que existían enemistades profundamente arraigadas entre los magos, dijo que era ingenuo pensar que estas enemistades podían ser simplemente dejadas de lado. 

Flambeau argumentó de forma convincente que los magos necesitaban tener el derecho a usar la violencia cuando fuera necesario. Dio una serie de situaciones hipotéticas en las que un mago podía intimidar, chantajear o atormentar a otro sin estar en claro incumplimiento del Código. Argumentó que si la ley prohibía estrictamente a un mago vengarse contra otro, los magos malvados florecerían y los honorables podrían convertirse en proscritos. 

Varios de los fundadores se opusieron a la propuesta de Flambeau: su oponente más directo fue Guernicus, que temía que legalizar el “declarar la Guerra a un Magi” socavaría la paz de la Orden. El asunto se resolvió finalmente en un famoso debate. Flambeau señaló que Guernicus se había visto obligado a vengar a su Maestro. Sin la guerra de los Magi, a Flambeau se le negaría ese mismo derecho. 

Muchos de los Fundadores tuvieron experiencia de primera mano de las atrocidades que los magos cometieron unos contra otros antes de la Fundación, así que finalmente aprobaron añadir la Guerra de los Magis al Código. 

Flambeau imaginó la guerra de Magi como una especie de juicio por combate. Esperaba que los magos simplemente se reunieran en el campo de honor para resolver sus diferencias en la batalla abierta. Sin embargo, el concepto jurídico de la Guerra del Mago se convirtió en algo más bien diferente de lo que él esperaba, como se explicará más adelante en este capítulo. 

Paradójicamente, Flambèl nunca recurrió a la guerra de los Magi. Sus enemigos jurados, los [[Sahires]], no se unieron a la Orden hasta más de un siglo después de su muerte.

#### Únete o muere 
Flambeau propugnaba que todos los magos de la cristiandad fueran traídos a la Orden (por la fuerza, si era necesario). No todos los Fundadores estaban de acuerdo: Guernicus insistió en que la membresía en la Orden debía ser algo estrictamente voluntario. Flambeau señaló que un mago que se negaba a realizar el Juramento se negaba a hacer las paces con la Orden y debía ser tratado como un enemigo. Guernicus persuadió al Primer Tribunal de que los magos debían tener la oportunidad de unirse a la Orden antes de ser atacados. En su mayor parte, Flambeau parecía haberse tomado en serio esa directiva (excepto con respecta a los Sahires, sus enemigos jurados). Flambeau creía firmemente que todos los Sahires eran diabolistas y repetidamente dijo que preferiría marcharse que ver a uno de ellos aceptado en la Orden.  Flambeau personalmente reclutó a varios magi para la Joven Orden. Contrario a lo que se dice de su leyenda, era generalmente diplomático, no beligerante, hacia los magos no herméticos (aunque era sincero sobre las consecuencias potenciales de negarse a unirse a la orden). En al menos una ocasión perdió la paciencia y gritó las famosas palabras: "¡Únete a nosotros o muere!", pero generaciones posteriores de magos tienden a exagerar la frecuencia con la que utilizó ese ultimátum. 

El único caso documentado en el que Flambeau utilizó su famosa amenaza fue en 771. Él y tres seguidores se enfrentaban a un mago llamado Varstus que vivía en los Alpes italianos. Varstus era experto en magia Afín (Conexiones Afines) (sympathetic), que tenía potencial para ser usado como una forma de ataque. Además, se rumoreaba que estaba organizando a otros magi para resistir la expansión hermética en el área. Trianoma se había acercado previamente a Varstus con una oferta de pertenencia a la Orden, pero este había respondido con desprecio y amenazas. Bonisagus le pidió personalmente a Flambeau que resolviera la situación, con la esperanza de que su reputación como Asesino de Brujos (wizard-slayer) le hiciese a Varstus vacilar.  Varstus se mostró tan ignorante como obstinado: el nombre de Flambeau no significaba nada para él, y recibió al Fundador con la misma beligerancia y arrogancia que había mostrado con Trianoma. Flambeau finalmente perdió la paciencia y gritó: "Únete a nosotros o muere!", Lanzando un rayo de fuego en un árbol cercano para enfatizar sus palabras. Le dio Varstus hasta la puesta del sol para decidir. El mago italiano se retiró, diciendo que consideraría la oferta, y luego inmediatamente huyó a las montañas. Flambeau esperó hasta la puesta del sol como prometió, luego él y sus seguidores comenzaron la persecución. Varstus estaba muerto antes del siguiente amanecer; Sus aliados brujos capitularon y se unieron a la Orden.Aun así, Flambeau creía que traer nuevos magos a la Orden debía ser un proceso gradual y diplomático. Los magos en 1220, especialmente los jóvenes magi, deben ser conscientes demandar a otros Magi el decidir entre "unirse o morir" no es una técnica de reclutamiento común ni recomendada. Incluso en la Europa mítica, uno puede atrapar más moscas con miel que con vinagre.

### La Segunda Generación*

El aprendiz más antiguo de Flambeau era un muchacho vasco que llamó Michel, en honor a [[Miguel Arcángel]]. Flambeau se aseguró de conseguir a los mejores tutores que pudo encontrar para que le enseñaran latín y las artes liberales. También hizo un esfuerzo para dar a su aprendiz una base firme y equilibrada en las artes herméticas. Miquel acompañó Flambeau a lo largo de Europa Mítica y aprendió el arte de la diplomacia a su Maestro. Flambeau tenía grandes esperanzas para su aprendiz y preparó a Miquel para que le sucediera como líder de la Casa. Pero después de que Miquel pasara  su Reto , se cambió su nombre hermético a [[Apromor]]. Él y Flambeau se separaron y tuvieron muchos desacuerdos. Aunque Mikel finalmente se convirtió en el primer Primus de la casa Flambeau, hizo muchos cambios, pocos de los cuales se habrían sido aprobados por su *parens*.

Flambeau comenzó a entrenar entonces a un segundo aprendiz, una muchacha franca a la que llamo [[Elaine]], la forma en que la entrenó parece haber sido una reacción a la decepción que sentía por Apromor. Flambeau mantuvo un control más estricto sobre su educación y entrenamiento que con Apromor (aunque sí se basó en tutores para enseñarle latín y escribir). Se aseguró de que estuviera expuesta a las enseñanzas morales de la Iglesia. Flambeau entrenó a Elaine principalmente en magia de fuego, aunque también le dio tiempo suficiente para leer sobre otro tipo temas.  Como resultado, Elaine siguió el ejemplo de Flambeau más de cerca que Apromor. Como su *parens*, toda su carrera la dedicó al servicio de la Orden. Elaine era tanto guerrera como erudita, sirvió con distinción como [[Hoplita]], y escribió varios libros que todavía son populares en 1220. 

Elaine entrenó a cuatro aprendices y finalmente se convirtió en Archimaga. Nunca fue muy activa políticamente, sin embargo su influencia en la Casa fue muy importante: formó a sus aprendices para compartir el sentido de honor de Flambeau y su profundo compromiso de servir a la Orden. Elaine también se acredita como el primer líder intelectual dentro de la casa Flambeau. Sus escritos perspicaces sobre la teoría de la magia y la filosofía demuestran que los magos de Flambeau pueden estar interesados en algo más que simplemente explotar cosas con conjuros de fuego. De sus crónicas de la casa pedura la forma francesa del nombre del fundador, recordado como Flambeau y de la Casa misma. 

> [!NOTE] Los escritos de Elaine 
>Elaine escribió varios libros que son extensamente leídos y copiados a través de su casa. Los originales fueron guardados en la biblioteca de Val-Negra, pero se han perdido desde que la Alianza se hundió profundamente en invierno. Todavía podía haber manuscritos desconocidos de ella, que se deshagan en algún cofre olvidado de Val-Negra. La Gran Biblioteca de [[Durenmar]] tiene excelentes ejemplares de sus obras que todavía sobreviven:
>- **Ars Flambonis** (“El Arte de Flambeau”): Summa de Ignem, Nivel 14, Calidad 12. Elaine escribió este libro como un tribut a su Pater (Maestro), Y el texto está lleno de anécdotas sobre sus enseñanzas. 
>- **Ultor** (“El Vengador”): Summa sobre la penetración, nivel 5, calidad 11. Mientras que los principios en este libro se aplican a la derrotar de cualquier tipo de resistencia mágica, Elaine pone énfasis específicamente en la penetración del Parma Mágica. Está basado en los primeros trabajos de Flambeau y en la experiencia práctica de Elaine como Hoplita. 
>- **Liber de Lumine** (“Libro de la Luz”): Tractatus de Ignem, Calidad 11. Como el título sugiere, este libro se concentra en la luz como un aspecto de la Forma de Ignem. 
>- **De Magia Sympathetica** (“La Mágia Afin”): Tractatus de Teoría Mágica, Calidad 11. Este libro cubre las Conexiones Arcanas y el tema relacionado de conexiones Afines (que otorgan un bono de penetración, véase ArM5, página 84). Si bien está inspirada en la investigación de Elaine en Penetración, su contenido es puramente teórico y es aplicable a todo tipo de hechizos. Es a la vez perspicaz y rigurosa. 
>- **De Potestate et Obligatione** (“El Poder y la Responsabilidad”): Tractatus de Philosophiae, Calidad 11. Un discurso sobre la práctica responsable y ética de la magia. Elaine avanza la idea de que El Don es dado por Dios para crear a los magos, dándoles poderes especiales y una responsabilidad especial para servir a su voluntad. Su filosofía está evidentemente influenciada por el libro de _San Agustín, Ciudad de Dios._|

### El Final del Fundador 

Las Artes de [[Flambeau, el Fundador]] nunca fueron fuertes fuera de su área de especialidad. Debido a un débil Ritual de Longevidad, el Fundador se había vuelto viejo y frágil hacia el año 820. Una mañana en la primavera de ese año dejó a [[Val-Negra]] solo. Dónde fue después se desconoce. Algunos magos, entre ellos [[Apromor]], creían que Flambeau buscaba un encuentro con los [[Sahires]]. Las opiniones están divididas en cuanto a si él quería morir en la batalla contra sus enemigos jurados, o si (como Apromor sospechaba) estaba cansado de luchar y trataba de ofrecer la paz. Cualesquiera que fueran sus intenciones, Flambeau nunca regresó, llevando a Apromor ya otros a concluir que los sahires lo habían emboscado y lo habían matado. 

Otros magos creen que Flambeau se retiró de la magia y se unió a un monasterio para vivir sus últimos años en una devoción silenciosa al Señor. Flambeau fue un cristiano a lo largo de su vida: entusiasta en su juventud, más piadoso y contemplativo en sus últimos años. Muchos de los que lo conocían, incluyendo a su filia Elaine, creían esta versión de la historia. 

> [!embed-item]  El Talismán Perdido del Fundador
> El talismán de Flambeau se llamaba Corazón-Ardiente: un ópalo de fuego de corte ovalado, impecable, del tamaño de una nuez. Cuando lo encantó por primera vez, lo colocó en el extremo de un bastón, pero en años posteriores decidió reasignarlo y lo usó como un colgante. Cualquiera que sea el destino del Fundador, su talismán nunca ha sido encontrado. Las memorias de los aprendices de Flambeau enumeran varios efectos que le ayudaron a imbuir en su talismán: una versión más poderosa de Guarda contra el Calor (ReIg 30 o superior), Palabras de la Llama Titilante (InIg 35), Hoja de la llama Hostil (CrIg 15), Lámpara sin llama (CrIg 10) e Ira Creciente (CrMe 15). Flambeau probablemente invirtió otros efectos en la joya, pero nadie sabe lo que podrían haber sido. 
>
>Aparte de sus poderes mágicos, Corazón-Ardiente tiene un valor histórico significativo. Como una Conexión Arcana (de duración indefinida) a su creador, podría usarse para descubrir el lugar de descanso final de Flambeau. Desde que Flambeau desapareció poco después de salir de Val-Negra, se cree que su talismán está en algún lugar de los Pirineos o cerca de ellos (aunque puede haber sido encontrado y trasladado a otro lugar por algún desconocido). 

### La Casa con la dirección de Apromor

Apromor condujo la casa Flambeau a lo largo de un camino decididamente diferente de lo que su Pater había puesto. Apromor era un astuto diplomático y estratega. Creía que la [[Orden de Hermes]] ya estaba firmemente establecida y que la necesidad de defenderla de amenazas externas estaba disminuyendo con el tiempo. Por otro lado, consideraba la consolidación del poder dentro de las [[Casa Tremere]] y [[Casa Tytalus]] como un signo de las rivalidades internas emergentes. Hizo fuertes movimientos para fortalecer su propia Casa contra la competencia política dentro de la Orden. 

Una de las principales iniciativas de Apromor fue continuar los esfuerzos de su Pater para reclutar a los magos no herméticos. Flambeau fue un gran devoto y creyente de la religión cristiana a lo largo de toda su vida, aunque siempre estuvo dispuesto a aliarse con magos que adoraban a los "viejos dioses",  nunca aprobó realmente el paganismo y se esforzó por convertir a sus aliados en su propia fe. Esto llevó a algunos nuevos miembros de la Orden a abandonar la Casa Flambeau para ir otras Casas en las que sus creencias eran más aceptadas. 

En un esfuerzo por aumentar el número de magos dentro de su Casa, Apromor emprendió una campaña prolongada y consistente para asegurar que los magos paganos reclutados por la Casa Flambeau permanecieran allí. Varios magi de Flambeau remontaron su linaje mágico al antiguo [[Culto de Mercurio]]. Trabajaron con [[Priamitus]] de la [[Casa Mercere]] para reconstruir el culto romano. Apromor alentó estos esfuerzos y proporcionó algunos recursos, aunque no participó personalmente. Como resultado de la participación de la Casa Flambeau en la reconstrucción del Culto de Mercurio, varios de sus miembros continúan practicando la magia mercuriana en 1220. 

La otra gran desviación de Apromor de las prácticas de su Pater fue en el uso de las Artes mágicas. Flambeau originalmente había entrenado a Apromor para luchar usando magia de fuego, pero en el medio de su carrera, Apromor se alejó de ese enfoque. A diferencia de su Pater, Apromor había sido entrenado en la teoría hermética desde el principio y por tanto tenía un conocimiento mucho más amplio de las artes mágicas. Nunca fue tan poderoso con la magia del fuego como el propio Fundador, así que con el tiempo comenzó a experimentar con otras formas de ataque mágico. Se estableció en Perdo como su Técnica favorita. Apromor describió su nuevo estilo de lucha como más "sutil" que el de Flambeau, con lo que quería decir que era más preciso y menos intrusivo.

### La Guerra del Cismo 

Los miembros de la casa Flambeau creen generalmente que la guerra del cisma era justificada y necesaria. Los descendientes de los magos que lucharon en la guerra suelen considerar las acciones de sus antepasados como heroicas. Tienden a pasar por alto el papel de su propia casa en la ilegalidad que condujo a la guerra. 

Nunca había habido mucho amor entre las casas Diedne y Flambeau. El mismo Flambeau no gustaba de los paganos ya menudo hablaba en contra de la Casa Diedne, que promovía activamente una religión no cristiana. Cuando Apromor cambió su política hacia el reclutamiento activo de magos paganos, la mayoría de los paganos que se unieron a la casa Flambeau pertenecían a las tradiciones romanas; Su rivalidad con los druidas volvió a los días del Imperio Romano. 

Después de la La Corrupción de la [[Casa Tytalus]], las sospechas corrieron alto dentro de la Orden. Algunos magos sospechaban de la [[Casa Diedne]] de atrocidades como el diabolismo o el sacrificio humano. Cuando la Casa Diedne usó su poder político para impedir que los Tribunales investigaran sus Alianzas, varios magos de la [[Casa Flambeau]] decidieron tomar la ley en sus propias manos. Declararon las Guerras de Magi y así poder atacar las alianzas de los Diedne y buscar pistas de los ritos Infernales de los druidas. Los magos de Diedne se defendieron de estas incursiones, llevando a muertes en ambos lados. Los conflictos se intensificaron cuando los miembros de cada Casa declararon Guerras de Magi para vengar a sus compañeros asesinados. En muchos casos, los magos abandonaron todo pretexto de legalidad y simplemente atacaron a sus enemigos sin previo aviso. 

Por supuesto, los magos de otras Casas también estuvieron involucrados en el conflicto. Cuando el Primus [[Cercistum]] de la Casa Tremere declaró la guerra a la Casa Diedne y pidió ayuda al resto de la Orden, Primus [[Entisimon]] de la Casa Flambeau fue el primero en responder. Reunió su Casa en un famoso discurso en Val-Negra. Hubo voces dentro de la Casa Flambeau pidiendo moderación y paz, aunque esto se acabó cuando Entisimon decidió tomar partido. 

Algunos magos de Flambeau hablaron apasionadamente en los Tribunales, instando a sus sodales a preservar la visión de los Fundadores de la coexistencia pacífica entre las Casas. Otros tomaron una acción más directa, escoltando [[Quaesitores]] a las áreas sin ley en un esfuerzo para restaurar el orden. Pero incluso los magos de Flambeau más comprometidos con la paz se detuvieron sin usar la fuerza para frenar a los alborotadores dentro de su propia casa. Después de que Entisimon tomara partido en el conflicto, las voces de la razón dentro de la casa Flambeau fueron silenciadas. Al menos un magi que persistió demasiado tiempo en tratar de calmar el conflicto fue asesinado en una Guerra de magi por un compañero Flambeau, pues lo consideraron un colaborador del enemigo.

### El nacimiento de los Milites 

Aunque la casa Flambeau inicialmente disfrutó de sus éxitos en la guerra del cisma, pronto el enemigo se organizó y comenzó a infligir importantes heridas a la Casa. La casa Flambeau simplemente carecía de la disciplina, estructura de mando y capacidad logística para emprender una guerra a gran escala. Al darse cuenta de esto, algunos de sus magos realizaron acuerdos con las Alianzas de la Casa Tremere, para estar bajo el mando organizado militar de los líderes Tremere. 

Otros miembros, dentro de la Casa Flambeau, se dieron cuenta de que podían tener éxito en la guerra si pudiesen mejorar sus tácticas y estrategia. Algunos viejos magos Flambeau eran veteranos de la campaña contra los [[Sahires]] de Iberia y sabían apoyarse mutuamente en batalla. Reunieron jóvenes magos en sus banderas y les enseñaron a luchar como unidades coordinadas. Los miembros de estas bandas de guerra realizaron juramentos de hermandad y defensa mutua. Estos magos llegaron a verse como análogos directos de los caballeros mundanos: guerreros de élite jurados a una vida de honor y servicio. Llegaron a ser llamados los [[Milites]] ("caballeros") por sus juramentos y código de conducta. 

Los milites por lo general luchaban en equipos de al menos tres o cuatro magos, acompañados de fuertes grupos de grogs. Tenían suficiente disciplina para enviar avanzada de exploradores y vigilar sus flancos y retaguardia. Rara vez se caían en las emboscadas de la Casa Diedne. Los milites sufrieron menos pérdidas que otras facciones de su Casa y lucharon con más éxito. Éxito, que a su vez, atrajo a más magos a sus estandartes. 

Cuando Primus Entisimon trató de implementar una gran estrategia para la [[997-1013 Guerra del Cisma]], los milites descartaron sus planes, dirigiendo la guerra desde el frente como mejor les pareció. Al terminar la Guerra del Cisma el número de miembros era casi una cuarta parte de los miembros de la Casa y poco a poco han ido ganando número e influencia desde entonces. 

### La Crisis de Normandía

Después de que la [[Casa Diedne]] fuera finalmente derrotada, los magi fijaron su atención a los lugares mágicos y las fuentes del vis que antes poseían las Alianzas de los Diedne. Había existido Alianzas Diedne en toda Europa mítica, pero eran particularmente abundantes (y ricas) en [[Bretaña]]. Los veteranos Flambeau de la guerra del cisma, junto con la [[Casa Tremere]], se vieron con el derecho a la parte del botín, debido a haber llevado el peso de la lucha contra la casa Diedne. No obstante La [[Casa Tytalus]] veía las cosas de otra manera: el antiguo territorio de la Casa Diedne era un gran premio, y solo seria de aquel que fuese lo suficientemente fuerte e inteligente como para ganarlo. 

Este sería punto de partida que daría lugar al enfrentamiento de las dos Casas. La casa Flambeau vio a los magos de Tytalus como unos despiadados oportunistas, reclamando falsamente tierras y fuentes que deberían pertenecer a la Casa Flambeau por su derecho de conquista.  Se resistieron a las reclamaciones del territorio de Diedne por parte de la Casa Tytalus con todos los medios a su disposición: quejas Herméticas legales, certamenes y, en última instancia, las Guerras de Magi. 

La [[Casa Tytalus]] no se achantó del conflicto, sino que lo intensificó. En poco tiempo, la disputa por territorio y recursos adquirió una dimensión ideológica. Por su parte, la casa Flambeau retrató a sus oponentes Tytalus como parásitos despreciables y sinvergüenzas, que habían sido tímidos durante la lucha real, pero ahora eran lo suficientemente audaces como para reclamar los restos. La casa Tytalus vio a los veteranos de Flambeau como invasores en una región que había sido tradicionalmente su patria, y estaban decididos de luchar hasta el final. 

El [[Tribunal Normando]] no pudo contener el conflicto. La situación en Bretaña se deterioró hasta el punto que pareció reflejar la misma anarquía que había precedido a la misma Guerra del Cisma. Al final, fue la casa Flambeau quien puso fin al conflicto. Dirigidos por los milites, los miembros de la Alianza insistieron en la restauración de la ley y el orden. Trajeron a los violentos miembros de su propia Casa a la cabeza y, en el Gran Tribunal de 1063, negociaron una tregua. Se celebraron Tribunales Especiales para dividir el territorio en disputa.  El Primus Flambeau [[Entisimon]], que había estado alentando el conflicto, se vio obligado a dimitir en desgracia.

---

## Estructura y organización 

Casa Flambeau tiene una laxa organización interna. Aunque no hay una jerarquía formal y no hay distintos cargos en la Csa además del Primus, sí hay una orden de jerarquía libre basada en el prestigio individual. Los magos de Flambeau tienen gran estima a la capacidad práctica: aquellos que logran logros importantes ganan respeto y estatus en la Alianza. Por otro lado, los magos que logran poco o muestran una reticencia a actuar pueden perder el estatus. Los miembros más respetados de la Alianza suelen ser magos de mediana edad que tienen muchas victorias y logros a su favor, y además siguen siendo activos e involucrados en los asuntos herméticos. 

Para reflejar el sistema del prestigio dentro de la casa Flambeau, la sección de las reglas de este capítulo proporciona mecánicos para la [[Aclamación de la Casa]], un sistema de la reputación. Es similar, pero no idéntico, al sistema de reputación de la casa de la [[Casa Bonisagus]].

Casa Flambeau trata de celebrar reuniones frecuentes. Se mantiene unida principalmente por _esprit de corps_ (El sentimiento de honor y orgullo compartido por los ideales y logros de un grupo de personas), por lo que las reuniones se consideran importantes para la cohesión de la Alianza. La mayoría de las reuniones de la casa son sociales. 

Los magos Flambeau son aficionados a contar historias con una jarra de cerveza en la mano, debaten sobre sus artes favoritas o tácticas de combate, y enfrentándose ocasionalmente en un certamen amistoso. Con mucha frecuencia, las reuniones de Flambeau incluyen alguna actividad organizada, relacionada con el combate, como una caza o un torneo, que fomenta el compañerismo y ayuda a los magos a perfeccionar sus habilidades de combate. 

### El Primus 

Cada vez que la posición de Primus queda vacante, los miembros de la Casa Flambeau de toda Europa mítica se reúnen en la Domus Magna para elegir uno nuevo. Los magos que no pueden asistir pueden votar mediante un poder. El proceso electoral es tumultuoso y desorganizado, y es a veces descrito por los asistentes como un "Torneo de fanfarronería". Los más destacados magos de Flambeau proclaman su candidatura y hacen discursos fanfarroneando acerca de sus magníficos logros (que los califican para el liderazgo), y sus gloriosos planes para el futuro Casa. El Quaesitor de Casa preside la reunión y acepta las mociones de la sala. Para mantener un mínimo de orden, el Quaesitor prohíbe certamen entre candidatos. Los miembros de la Casa pueden solicitar una votación para eliminar a cualquier candidato después de que todos los candidatos hayan tenido la oportunidad de hablar, pero tales mociones rara vez pasan en el primer intento. Los discursos, debates, mociones y votaciones ocasionales continúan, a veces durante varios días, hasta que surge un ganador. 

Los poderes directos del Primus son relativamente pocos; Gobierna más por influencia y persuasión que por autoridad formal. Tiene la autoridad para presidir cualquier Reto (Gauntlet) para admisión en la Casa Flambeau. Él es el gobernante de la Alianza de [[Castra Solis]], aunque en la práctica hay otros magos, residentes de antiguo en la Domus Magna, que realmente controlan sus recursos. Por tradición, el Primus organiza y preside el gran torneo en Castra Solis. 

El actual Primus, [[Garus]], es un viejo magus que fue un aventurero y soldado de fortuna en su juventud. Él lucha según la Escuela del Fundador (ver "[[Escuelas de Combate Mágico]].  Su liderazgo comienza a debilitarse porque ha permanecido demasiado tiempo dentro de las paredes de la Domus Magna. Se da cuenta de que sus días como líder de la Casa Flambeau están contados. 

El año 1220 representa un momento difícil en la historia de la casa Flambeau, como sucede tras período de paz prolongada. La Guerra del Cisma termino hace más dos siglos; La mayoría de los magos creen que la Casa Diedne nunca volverá resurgir de nuevo. Con pocas amenazas directas que amenacen a la Orden, la Casa Flambeau no tiene una causa con la que congregarse. Sus miembros están divididos, persiguiendo sus propias prioridades y creando facciones rivales dentro de la Casa. El reclutamiento se hace cada vez más difícil, ya que la Casa parece carecer de un propósito. 

Garus es uno de los [[Milites]]. Él cree que el futuro de la Casa depende de encontrar una manera de fortalecer la identidad común de sus miembros y los valores compartidos. Su visión es organizar la Casa en algo parecido a un orden de caballería, con una misión unificada y una estructura formal de mando. En esto, se enfrenta a formidable oposición desde dentro de su propia casa. 

El Primus sabe que reformar la casa Flambeau debe hacerse gradualmente o los miembros de la Cámara nunca lo aceptarán. No espera que el trabajo se complete durante su mandato. Dedica considerable energía política a ayudar a ciertos magos prometedores y con ideas afines a que ganen prestigio dentro de la Casa. Evidentemente, espera que uno de ellos sea elegido como su sucesor.  Garus ha implementado una serie de reformas encaminadas a fortalecer la unidad de la Casa. Antes de su mandato, el torneo de la Casa se celebraba sólo durante los años del Tribunal. Garus aumentó la frecuencia a cada cuatro años (habrá un torneo en 1220). El torneo ayuda a construir compañerismo; Además, las ceremonias de inauguración le brindan un púlpito cómodo para dar conferencias sobre su visión del futuro de la Casa. 

Otra de las reformas de Garus ha sido poner por escrito las reglas de caballería de los Milites. Jurar el código de conducta de los milites es estrictamente voluntario, pero Garus anima a los jóvenes magos a hacerlo. También ha introducido reglamentos más formales para las reuniones de la Cámara, que al principio se enfrentaron con una fuerte oposición. Los magos pronto se dieron cuenta de que hicieron las reuniones más ágiles y por lo tanto más cortas; Después de esto, las nuevas reglas disfrutaron de un amplio apoyo

### Domus Magna

La Domus Magna original de la casa Flambeau fue [[Val-Negra]], una Alianza en el lado meridional de los Pirineos. Durante la Guerra del Cisma, el Primus [[Entisimon]] observo que la remota ubicación de Val-Negra la hacía inadecuada como un cuartel general, por lo que trasladó el cuartel de mando a la Alianza de [[Castra Solis]]. Fue su sucesor quien trasladó oficialmente la sede de la Casa; Hay rumores de que los elementos neo-romanos dentro de la Casa (el [[Culto de Mercurio]]) influyeron en la decisión de trasladar la Domus Magna. 

Castra Solis había sido fundada por [[Kaeso]], miembro del [[Culto de Mitra]], que [[Apromor]] había reclutado en 809. Kaeso construyó la alianza sobre una cueva subterránea que fue sagrada para el culto: el nombre de la alianza es una referencia al aspecto de Mithras como un Dios sol. Castra Solís se encuentra en el [[Tribunal Provenzal]], varias leguas al sur de [[Burdeos]]. 

Se podría esperar que la Domus Magna de la casa Flambeau sea una imponente fortaleza, pero de hecho Castra Solís se asemeja más a una gran casa solariega. Kaeso se dio cuenta de que incluso los muros de piedra más poderosos podían ser fácilmente destruidos por la magia, por lo que se concentró en la construcción de defensas mágicas en lugar de las físicas. El pacto tiene una serie de objetos encantados disponibles para su defensa. 

Castra Solís evita la construcción de una gran fortaleza por otra razón: se encuentra dentro del territorio del duque de [[Aquitania]] y no desea tenerlo de enemigo a causa de la construcción de un fuerte castillo en sus tierras. El Tamaño de la Alianza es pequeño por esta razón. La alianza tiene muchas habitaciones y hay un par de casas de huéspedes en el pueblo cercano. Aun así, no hay espacio suficiente para acomodar a todos los magos de la casa Flambeau, y mucho menos para a sus aprendices, guardias y sirvientes. 

Un campo grande, vacío cerca de la alianza se utiliza para los torneos y otros acontecimientos de la casa. Durante los grandes eventos, los visitantes ponen sus carpas en el campo, que es lo suficientemente grande para los campamentos de los magos y el evento. 

La biblioteca de Castra Solis tiene una impresionante colección de libros sobre magia de combate, incluyendo textos de laboratorio para hechizos de combate y tomos de Habilidades para Hechizos Dominados como Penetración y Parma Mágica. La biblioteca también incluye muchos libros sobre dragones y otras bestias fantásticas. El pacto no permite a los visitantes copiar ninguno de los libros, pero los miembros de la casa Flambeau son bienvenidos a estudiar de ellos - por una cuota. Castra Solis tiene un aura mágica relativamente débil - solo nivel 3. El aura es más fuerte en lo Divino Cueva de Mithras, que está conectado a la casa principal de la alianza por una escalera secreta. Las propiedades exactas de esa cueva, y las formas en que los residentes de Castra Solís lo usan, son un secreto de la alianza. 

#### Los Grog de Castra Solis**
Castra Solis mantiene un pequeño grupo de grogs con el fin de pasar desapercibidos, pero este grupo esta entre los guerreros más diestros, mejor entrenados y mejor comandados en la Orden. Como hogar de varios Maestros magi Flambeau, la casa se enorgullece de ofrecer a sus mejores guerreros para ayudar a sus miembros en peligrosas misiones. La domus magna rara vez contrata reclutas novatos, en lugar prefiere seleccionar sus grogs de lo mejor que pueden encontrar en otros alianzas Flambeau. Muchos magos Flambeau consideran un deber y un honor trasladar a sus criados a Castra Solis. Incluso aquellos que están menos unidos en la comunidad están dispuestos a separarse con unos pocos buenos sirvientes a cambio de las recompensas que la domus magna ofrece: vis, oro, artículos menos encantados, o la oportunidad de pasar temporadas estudiando en su biblioteca.
Los grogs de Castra Solis son altamente experimentados. Incluso los cocineros y los agropecuarios son elegidos por su lealtad y su excelencia en sus oficios. Todos los grogs reciben entrenamiento de combate: se entrena a cualquier sirviente varón para que defienda la Alianza en caso de una emergencia.Los grogs protectores están entre los guerreros mejor entrenados de la Orden entera. Este grupo es pequeño, quizás sólo veinte grogs con escudo y algunos sirvientes, pero su capitán los entrena diariamente buscando la máxima eficacia en el combate. La mayoría de los grogs luchadores llevan objetos encantados. A cambio de su riguroso entrenamiento y de la lealtad a la Alianza, los grogs de Castra Solis reciben valiosas recompensas. Su paga es muy alta. Sus familias y ellos viven en cómodos y espaciosos aposentos.. Cuando un grog muere o se ve obligado a retirarse, la alianza se encarga de que su familia sea cuidada. Los oficiales y grogs de élite pueden incluso recibir un Ritual de Longevidad. Muchos grogs aspiran al honor de ser escogidos un día para guardar la domus magna. La mayoría -si no todos- los grogs escudo sirven a la [[Legión de Mitra]]como Auxiliares.

> [!embed-item]  El Cuerno de los Campeones
> Castra Solis tiene un cuerno mágico que puede convocar magi seniores Flambeau de cualquier parte de Europa mítica. El cuerno es guardado por un mago conocido como el Castellan. Los magos que se ofrecen voluntariamente como defensores proporcionan al castellano una Conexión Arcana fija a sí mismos. Como gesto de confianza y respeto, el castellano da a cada voluntario una Conexión Arcana a sí mismo a cambio. El Cuerno de Campeones es un dispositivo imbuido con los siguientes efectos, cada uno de los cuales se activa al sonar una nota diferente en el cuerno. 
> **Sonido de Alarma**
> CrIm 50 
> Penetración +70, 1/día
> El Cuerno es audible para todo el mundo de un grupo objetivo, independientemente de la distancia, siempre y cuando el usuario tenga una conexión arcana con cada persona. Este efecto tiene una penetración alta para asegurar que será escuchado por los magos concretos. Al sonido del cuerno, los magos que se han ofrecido para defender Castra Solis bajan su Parma Mágica y esperan el efecto de convocatoria. 
> (Efecto: Base 1, +4 Conexión Arcana, +2 Grupo +35 para Penetración) 
> **Invocación de los Campeones**
> ReCo 65 
Penetración 0, 1/día 
Cada miembro del grupo objetivo es instantáneamente transportado a la presencia del Cuerno, siempre que el objetivo tenga una Conexión Arcana. Este efecto no tiene penetración, por lo que los magos pueden optar por resistir la convocatoria.
(Efecto: Base 35, +4 Conexión Arcana, +2 Grupo)|

### Uniéndose a la Casa Flambeau

El procedimiento para unirse a la casa Flambeau es el mismo tanto para los aprendices como para los magos procedentes de otras casas. Si el candidato ya es un mago de otra Casa, debe renunciar a su pertenencia a esa Casa antes de entrar en la Casa Flambeau (aunque por lo general estos candidatos sólo abandonan su Casa original después de pasar la prueba (Guantelete) de la Casa Flambeau). 

Primero, el candidato debe **encontrar un Padrino** dentro de la casa Flambeau. Cualquier miembro de la Casa puede actuar como patrocinador, pero el candidato obtendrá aceptación y reconocimiento en proporción a la reputación del Padrino. Se considera un honor, si un magos de la casa le pide a otro que sea el Padrino de u aprendiz. 

El desafío para un mago "adulto" suele ser más difícil que para un aprendiz. Los desafíos típicos pueden ser un certamen usando las artes favoritas del candidato, participar en un torneo de la Casa, una caza organizada, o una búsqueda que lleve al candidato a través de un área peligrosa. La prueba puede ser arriesgada: pedirle al candidato que cace y mate solo a una bestia sobrenatural sería un ejemplo de un desafío especialmente peligroso. El Padrino es el árbitro final de si el candidato pasa o no. 

Casa Flambeau le gusta que el Reto tenga el mayor público posible. Cuanto más prestigioso sea el patrocinador, más magos asistirán a la prueba. Un gran número de público en el la prueba ayuda a establecer y difundir la reputación del nuevo hechicero Flambeau. Si el candidato falla la prueba, hay una gran probabilidad de que él gane una Reputación desfavorable debido a que los espectadores estén decepcionados (o divertidos) difundan la historia. 

Por el Código Periférico, cuando un aprendiz falla su prueba tres veces, la cuarta prueba es decidida por un Quaesitor. Cuando esto ocurre, cuando el candidato tenga éxito se le permite unirse a la Orden, pero no a la Casa Flambeau, a menudo la [[Casa Ex-Miscellanea]]. 

En circunstancias especiales, un magus o incluso un aprendiz puede ser aceptado directamente en la casa Flambeau sin la necesidad de una prueba. Esto se hace para los candidatos que ya se han demostrado su habilidad de alguna manera dramática. 
Por ejemplo, una aprendiz de Flambeau llamada Cindrallon se convirtió en Magi de la Casa Flambeau con sólo siete años de aprendizaje, debido a que ella sola mató a un magus renegado. Aunque ella había usado una lanza en lugar de un hechizo para matar al renegado, su Maestro y el Primus acordaron que ella había mostrado un valor excepcional y capacidad de lucha. Otros casos similares fueron promociones que ocurrieron en los campo de batalla durante la guerra del cisma.

Desde los días del Fundador, los magos Flambeau han llevado a cabo una ceremonia de iniciación pública después del Reto. El nuevo mago de Flambeau está de pie una vigilia de toda la noche (quizás en una iglesia, si su Pater es cristiano, o tal vez en un antiguo templo o sitio mágico) y luego aparece con una bata blanca antes de una asamblea de la casa. El nuevo mago jura o reafirma el Juramento Hermético ante un oficial (el Primus, un Quaesitor o un mago muy respetado), que luego le da un golpecito en el hombro con una varita o bastón y otorga su sello de voto (sigil). A veces los Parens del nuevo magus le dan un regalo al final de la ceremonia.

---

## Cultura 

La Casa Flambeau es un grupo variopinto de magos. Vienen de una diversidad de tradiciones mágicas, incluyendo magi que han sido transferidos desde otras casas. Si bien cada miembro de la Casa tiene una perspectiva única, es posible generalizar sobre la cultura común que ha surgido. 

Casa Flambeau tiene un **fuerte espíritu marcial**. Sus miembros creen que la fuerza a menudo es necesaria, tal vez inevitable. Muchos ven el combate como la prueba más pura de la fuerza y la mayor fuente de gloria. No obstante no todos los miembros de la casa Flambeau son máquinas centradas solo en la lucha, muchos de ellos tienen otros intereses, pero comparten la opinión de que la habilidad en combate les convierte en una élite dentro de la orden. 

Muchos se ven a sí mismos como los defensores de la paz de la Orden y protectores de sus colegas menos bélicos. Incluso los miembros más cultos e intelectuales de la Alianza entrenan para mantener sus habilidades de combate. El certamen se considera una parte esencial de la autodefensa de un mago: un mago que se especializa en matar pero descuida certamen es incapaz de defenderse en disputas legales contra otros magos. 

[[Flambeau, el Fundador]]  el fundador tenía un **fuerte sentido de honor personal**, que es emulado por la mayoría de sus seguidores. Los miembros individuales de la Alianza tienen diferentes ideas sobre exactamente lo que significa el honor, pero tienden a tener creencias firmes sobre el tema. 

Cuando los valores de dos magos Flambeau entran en conflicto pueden surgir luchas, certamen, e incluso guerras de los magi. Los miembros de la Casa Flambeau son muy **independientes**. Con un sentido del honor, valentía y sed de gloria, tienden a parecerse a una versión mágica de los caballeros medievales. Un forastero describió una vez a la casa Flambeau como "cincuenta príncipes y ningún subdito". 

En parte debido a su forma de ser tan independiente, los magos Flambeau pueden ser **muy competitivos entre sí**. Esta competición puede ser de muchas formas, desde ser el primero en matar a un magus renegado, tratar de vincular el familiar más impresionante, o inventar el hechizo más espectacular Ignem. Siempre que los magos de Flambeau se reúnen, tienden a presumir y pavonearse. 

Otro legado del Fundador es un **compromiso de servir**. Flambeau habló a menudo de la responsabilidad que tienen los magos para usar el Don en alguna causa digna. En su entusiasmo por llevar a cabo esta directiva, los miembros de la Casa Flambeau tienen reputación de superar a veces los límites del Código. Por ejemplo, algunos de ellos están activos en las Cruzadas y Reconquista, no obstante existe una cláusula del Código contra la interferencia mundana. El espíritu independiente de la Alianza lleva a muchos a admirar secretamente a los magos rebeldes que están dispuestos a transgredir el Código para hacer lo que creen que es correcto. Al mismo tiempo, la Casa Flambeau es conocida por su disposición a ayudar a los [[Quaesitores]] a tratar y (especialmente) castigar a los que violan la ley. A menudo los miembros de la Casa se ponen en conflicto entre sí.

### Los Torneos Flambeau 

La Casa Flambeau lleva organizando torneos desde los años posteriores a la Guerra del Cisma. El torneo principal es una competición regular celebrada en Castra Solís, que dura cinco días en torno al solsticio de verano de cada año bisiesto (los torneos más recientes fueron en 1216 y 1220). Otros torneos a veces se celebran en otras Alianzas Flambeau, en intervalos regulares (por ejemplo, cada siete años), o para celebrar ocasiones especiales. 

Los torneos de la Casa Flambeau no son exclusivos: cualquier miembro de la Orden es bienvenido a competir. Los torneos suelen atraer a una serie de competidores de las [[Casa Tytalus]] y [[Casa Tremere]]. Los torneos fomentan la fraternidad permitiendo a los magos de Flambeau la oportunidad de animar a los miembros de su propia casa. 

#### Certamen 
El evento principal del torneo de magos es certamen. La competición normalmente se organiza como un torneo de eliminación. En cada ronda del torneo, un par de magos se emparejan y se enfrentan. El ganador de dos de tres duelos dentro de la ronda pasa a la siguiente ronda. A los participantes se les permite 15 minutos de descanso entre los duelos, y al menos una hora de una ronda a otra. 

El marcador lo llevan unos oficiales (por lo general, magos que no tienen la intención de competir) que utilizan un proceso de preselección para pre-organizar los duelo, por lo que los competidores más fuertes (en la opinión de los oficiales) no se enfrentan hasta la ronda final de la torneo. 

Las reglas normales del certamen se alteran a propósito del torneo. El mago más joven elige la Forma, y el más antiguo de la Técnica (es inusual para los concursantes ser exactamente la misma edad hermética, tales situaciones se deciden por un lanzamiento de moneda). Los competidores pueden vetar la elección de sus oponentes de Arte como de costumbre, pero no pueden usar un veto en ambos, solo en el primer o el segundo duelo. De esta manera, cada concursante tiene garantizado poder usar su primera opción de Arte al menos una vez. Aunque el código periférico permite al ganador de un certamen lanzar un hechizo sobre el perdedor, las reglas del torneo lo prohíben estrictamente. 

#### Dimicatio 
Otro evento popular del torneo es el dimicatio, que significa "concurso" o "batalla". No está relacionado con el certamen estándar. Los competidores tratan de lanzar hechizos reales entre sí utilizando la opción de "Lanzamiento SinFuerza". Cada mago usa una defensa de “Lanzamiento Rápido” para tratar de bloquear el conjuro contrario. El primer magus cuyo hechizo alcance Parma de su oponente es el ganador. 

Huelga decir que este concurso conlleva peligros sustanciales. Los hechizos dirigidos que evitan la resistencia mágica están estrictamente prohibidos. 

El concurso siempre se lleva a cabo en condiciones estrictamente controladas frente a un árbitro y muchos espectadores. El árbitro usa un hechizo Intellego Vim como la Vista de las Mágicas Activas para determinar el ganador. Si el hechizo de un mago realmente penetra el Parma de su oponente, esto se toma como juego sucio y habrá una investigación hermética inmediata. Las reglas del concurso permiten cualquier hechizo que se dirija directamente al oponente - y cuanto mayor sea el nivel del hechizo, más difícil será defenderlo. La multitud disfruta mucho con la _Bola de Fuego infernal._ 

Debido a que dimicatio tiene un gran potencial para accidentes o juego sucio, algunos Quaesitores quieren prohibirlo del concurso. Y esto sólo aumenta su atractivo para la mayoría de los magos Flambeau. El gran torneo de Castra Solis siempre incluye un evento Dimicatio; cualquier magus que gane por lo menos dos rondas en el evento certamen está calificado para entrar en el evento dimicatio, que tiene su propio premio aparte.

##### Dimicatio en Detalle 
Si desea jugar al dimicatio, usa las reglas normales de combate. Los concursantes comienzan uno frente al otro dentro al Alcance Voz. El concurso comenzara con el sonido de una campana u otra señal. Ambos competidores tiran Iniciativa y el ganador será el primero en lanzar el primer hechizo ofensivo. El defensor debe entonces lanzar un Hechizo Rápido )Contrahechizo), para defenderse. Ver reglas de Lanzamiento Rápido. 

El director de juego deberá de considerar según su propio juicio o criterio si una combinación particular de Forma y Técnica es eficaz como defensa contra un hechizo en particular, hay que tener en cuenta la **regla general de que un Lanzamiento Rápido defensivo de mitad del nivel del hechizo atacante suele ser suficiente para detenerlo**. Esto se vuelve más difícil si el defensor no es capaz identifica el Formula del hechizo.

> [!example] Ejemplo
> Si un magus lanza [[Bola de Fuego Infernal (CrIg35)]], su oponente podría defender usando Creo Aquam (para apagar el fuego), Rego Ignem (para desviar la bola de fuego), o incluso Creo Herbam (para crear un escudo de madera). Las defensas de Perdo Vim pueden funcionar, pero necesitarías cumplir las reglas normales para disipar la magia. 

  Si la defensa tiene éxito, el defensor puede lanzar un hechizo ofensivo en su turno en la Orden de Iniciativa. El ciclo se repite de acuerdo con la secuencia de combate normal. Las reglas del concurso permiten a los magos utilizar vis si lo desean.

#### Batalla de Hechiceros 
Aún más polémico es “la Batalla de Hechiceros”, es un evento poco común y peligroso donde magos y equipos de grogs en realidad luchan entre sí. El objeto de la Batalla de Hechiceros es que un mago lance con éxito un hechizo de **Alcance Toque** en el mago opuesto (usando **_Lanzamiento_** SinFuerza_**). Pero para esto requiere derrotar a los grogs que protegen a ese mago. 

Cada equipo consta de un mago y cinco grogs. Y se permite, y se espera, que un mago extienda su Parma Magica para cubrir algunos o todos sus grogs. 

La Batalla de los magos es un torneo _au plaisance_, un concurso para el placer de los participantes y espectadores. Las reglas exactas para el concurso varían de un torneo a otro (todavía no están regladas) pero generalmente incluyen: 
- Solamente se permiten los hechizos de alcance personal y Toque; esto evita que los magos neutralicen los grogs opuestos con demasiada facilidad. Algunos torneos permiten los hechizos de rango de voz, siempre y cuando se usen sólo en los propios grogs del lanzador. 
- Los grogs suelen estar armados con armas embotadas (-3 a Daño), y la selección de armas puede estar restringida (martillos de guerra no son armas seguras del torneo). 
- Los hechizos que causan daño suelen estar limitados a tercera magnitud y por debajo, o prohibidos por completo. (El torneo en Castra Solis prohíbe hechizos que causen daño.) 
- Los Artefactos encantados están permitidos siempre y cuando obedezcan todas las restricciones para los hechizos. 
- A los magos se les permite usar vis durante la Batalla de los magos. 

Incluso con estas reglas, el potencial de muerte o lesiones accidentales es tan grande que muchos Quaesitores están horrorizados de que este evento incluso exista.

#### Desafíos Especiales
Los torneos también pueden tener algún tipo de Desafío Especial ideado por el anfitrión del torneo. Antes del Torneo se anuncia el desafío con una descripción detallada con objeto de los participantes sepan de que va. El desafío puede ser cualquier cosa que el anfitrión elija organizar, pero por lo general es algo dramático, posiblemente peligroso. Como ejemplos sería un concurso para robar una joya mágica custodiada por trolls, o una carrera a través de un laberinto lleno de trampas mágicas. 

Nuevamente, ciertos Quaesitores (y otros magos en general) no ven con buenos ojos los Desafíos especiales porque a menudo son peligrosos, y a veces cruzan el límite de molestar a los hadas. 

#### Entretenimiento y eventos paralelos
Los torneos grandes también pueden incluir eventos menores. Las pruebas de precisión usando hechizos dirigidos, similares a los torneos mundanos de tiro con arco, son comunes. Puede haber competiciones separadas para aprendices y grogs. Junto a la competencia hay música, entretenimiento, fiesta y mucho alcohol.

#### Premios del Torneo 
Los magos no compiten en torneos meramente por la fama y el prestigio. El anfitrión del torneo también ofrece premios. Estos pueden ser tan simples como un monedero de vis: una torre (diez peones) es un premio moderado. 

Los Torneos más grandiosos ofrecen premios más lujosos: libros, artículos encantados menores, incluso dispositivos imbuidos. Cualquier cosa que la mayoría de los magos valoraría podría ser ofrecida como un premio. Cuanto mayor sea el premio, más competidores serán atraídos al torneo. 

Los Archimagos suelen estar contentos de dejar que los magos jóvenes compitan, pero un premio realmente atractivo puede incluso atraer a algunos magos que se encuentren retirados.

> [!skill] Lanzamiento Sin Fuerza
> Un mago puede reducir de forma deliberada el Total de penetración de un hechizo a 0. En esencia, cuando el Magus lanza un hechizo puede optar o no usar su habilidad de penetración, en caso de no usar su habilidad de penetración el total de penetración del hechizo es 0, y como la mayoría de los magos tienen al menos una Resistencia Mágica de 0, el hechizo no afectará a un magi objetivo a menos que se saque una Pifia. 
>El lanzamiento sinFuerza no requiere habilidad ni esfuerzo particular. Es útil en torneos mágicos, o cuando un mago lanza un hechizo que cubre un área grande y quiere evitar afectar inadvertidamente a cualquier magi que pueda estar dentro del área objetivo.

### Escuelas de Combate Mágico 
Cuando se piensa en la casa Flambeau, se suele pensar en magia de fuego. Flambeau el Fundador fue un maestro del Arte de Ignem y un gran número de magos Flambeau siguen sus pasos. Como una casa de guerreros y campeones, Flambeau incluye una amplia variedad de magos de combate, aunque no todos dependen de la magia del fuego. Por ejemplo Apromor, el primer aprendiz de Flambeau, se concentró en los hechizos de Perdo. 

Con el tiempo, los magos sucesores han inventado otros estilos de lucha. Magos de la Casa Flambeau se refieren a cada estilo de lucha como una **schola**  de combate mágico. Estas escuelas no son linajes formales. Son simplemente grupos de magos que han elegido un enfoque común para el combate mágico. Así como los eruditos mundanos podrían describir a un filósofo como perteneciente a la escuela de Aristóteles, los magos Flambeau hablan de magos pertenecientes a la Escuela del Fundador o la Escuela de Apromor. 

Clasificar a los magos en las escuelas es más preciso que simplemente hablar acerca de las artes que prefieren. Combatir con hechizos de fuego es bastante sencillo, pero otras artes, como Rego, pueden utilizarse de diferentes maneras. Hablar en términos de escuelas da a los magos de Flambeau la terminología necesaria para discutir acerca tácticas y contramedidas, y tener largos debates sobre por qué su escuela favorita es mejor que la de todos los demás. 

Los magos de Flambeau nombran cada escuela de combate mágico como el magus que la inventó. A veces, los magos hablan de los estilos de magia de otras Casas como escuelas: un mago que lucha usando dispositivos encantados puede decirse que sigue la Escuela de Verditius, o una maga que lucha cambiando de forma y convirtiéndose en una bestia puede decirse que sigue la Escuela de Bjornaer .

#### Eligiendo una Escuela 
Todo magus que aprende hechizos de batalla se está preparando para usar alguna escuela de combate mágico, de forma consciente o no. Magos Flambeau tienden a elegir cuidadosamente sus escuelas de combate, dedicando una gran cantidad de tiempo de estudio y laboratorio para dominarlos. Hay una gran diferencia entre un mago que conoce unos cuantos hechizos de combate que son incompatibles entre sí y uno que ha dedicado muchas estaciones de estudio cuidadosamente planteado sobre las Artes, Habilidades y hechizos interconectados que hacen que una escuela sea efectiva. Los magos Flambeau tienden a desarrollar cualquier escuela de lucha que se adapte mejor a las fortalezas individuales de su Don, es decir, sus Virtudes Herméticas (y los defectos). De esta manera es exactamente cómo la mayoría de las escuelas fueron inventadas en el primer lugar: algún mago antiguo desarrolló una estrategia basada en su fuerza individual. Hay otras razones para elegir una escuela en particular; por ejemplo, los magos a menudo eligen una segunda escuela para compensar cualquier debilidad que pueda tener su escuela primaria, o pueden seleccionar una escuela adecuada para combatir a un tipo particular de oponente. 

Los magos que son entrenados dentro de la casa Flambeau su escuela es escogida por sus *parentes*. Por lo general, el parens suele entrenar a su aprendiz en la escuela que él sigue o en cualquiera que el parens prefiera. También hay excepciones. Si el Don de un aprendiz es obviamente adecuado para una escuela en particular, sus parens pueden enseñarle esa escuela para su beneficio. A veces un parens elige una escuela diferente para su aprendiz porque él quiere explorar esa escuela. En cualquier caso, la escuela asignada a un aprendiz de Flambeau puede o no ser una que el aprendiz hubiera elegido para sí mismo. Los magos que se unen a la casa Flambeau de otras casas son libres de seguir cualquier escuela que más les guste, al igual que los magos Flambeau que han pasado su Prueba (The Gauntlet).

#### Ejemplos de Escuelas de Combate Mágico

| Escuela |                                            Descripción           |       Virtud Recomendada                                                 |
| ------------------------------- | ----------------------------------------------------- | ----------------------------------------------------------- |
| [[Escuela del Fundador]]               | Ataque usando Fuego                                   | Afinidad con Ignen                                          |
| [[Escuela de Apromor]]                | Daña al oponente directamente con Perdo               | Afinidad con Perdo                                          |
|[[Escuela de Boreas]]                   | Ataque directo usando frío                            | Afinidad con Ignen o Perdo                                  |
| [[Escuela de Ramius]]                     | Ataques mundanos y defensas mágicas                   | Guerrero                                                    |
| [[Escuelas de Sebastian]]                | Ataque directo usando una forma distinta a Ignen      | Focus Mágico                                                |
| [[Escuela de Vilano]]                 | hechizos dirigidos a sobrepasar la Resistencia mágica | Afinidad con Puntería o Cuidadoso con la habilidad puntería |


---

## Personajes Flambeau 

### Virtudes y Defectos 

#### Virtudes y Defectos de la Casa 
Los Magos de la Casa Flambeau ganan una Virtud Menor gratuita en la creación del personaje como beneficio de su Casa. Esta Virtud libre debe ser **Afinidad con Arte (Ignem)** o **Afinidad con un Arte (Perdo)**. Estas Virtudes son muy apropiadas para tres de las seis escuelas de combate mágico. 

Si el director de juego lo desea, puede permitir que los magos jugadores que quieran especializarse en las Escuelas de Ramio, Sebastián o Vilano sustituyan la virtud de su casa por una de las Virtudes Menores recomendadas de su escuela, es decir:
- Guerrero
- Focus Magico 
- Afinidad con Puntería o Cuidadoso con Puntería 

#### Personajes mercurianos 
Las siguientes virtudes y defectos son sugeridos como los más apropiados para los personajes Mercurianos, y los jugadores son libres de elegir aquellas que sientan que son adecuadas al personaje. 

- **Virtudes sugeridas:** Maestría de la Magia, Magia Mercuriana; Magia Cíclica, Hechizos Dominados, Magia Metódica, Premoniciones, Erudito de (Magia). 

- **Defectos Sugeridos:** Magia Cíclica, Magia Espontanea Difícil, Magia Rígida, Hechizos lentos, Vulnerable al poder Divino, Visiones, Magia Espontanea débil, Pagano (ver _casas de Hermes: Castas_). 

Quienes pertenecen al culto también tienen acceso a cualquiera de las habilidades especiales de Hechizos Dominados Flambeau. 

#### Personajes mitraicos 
Para crear un personaje que pertenezca a la tradición mitraica dentro de la Casa Flambeau, elige algunas Virtudes y defectos de la lista a continuación. Dado que el antiguo Culto de Mitra no sobrevivió de manera intacta al paso del tiempo, no todos los personajes con herencia mitraica poseen todas, o incluso la mayoría, de estas habilidades. Además este Culto Mistérico está abierto a personajes de cualquier linaje mágico. Descender del linaje mitraico en la Casa Flambeau no implica que el personaje tenga más posibilidades de ser aceptado en la Legión. Como es un Culto Misterico, la Legión de Mitra puede enseñar poderes adicionales a los personajes que se someten a la Iniciación. 

- **Virtudes Sugeridas:** Cabal Legacy , Maña con Ignem (Virtud de la Casa), Don Silencioso, Afinidad con Creo, Magia Ciclica (Virtud), Estimulo Vital, Foco Mágico Menor (Soldados), Voluntad de Hierro, Determinación 

- **Defectos Sugeridos:** Deficiencia en (normalmente en Perdo), Magia Ciclica (negativa), Artes Incompatibles (usualmente dos combinaciones con Perdo), Vulnerable al poder Infernal, Propósito Elevado

### Conceptos Flambeau

Las siguientes son algunas ideas para los conceptos de personaje tanto de jugadores como de no jugadores.

#### Hoplitas
> [!cite]
> _La ley es tan fuerte como la fuerza que la respalda. Si consientes en ser la balanza de la Justicia, entonces seré su espada._ 
- Flambeau a Guernicus, cuando Guernicus se convirtió en el primer Quaesitor. 

Los Hoplitas son un grupo informal de magos de combate que trabajan estrechamente con los Quaesitores. Cazan y matan a los magos que han sido expulsados de la Orden por crímenes herméticos. Mientras que todos los miembros de la Orden tienen el deber de matar a los renegados herméticos, los Hoplitas buscan agresivamente a los renegados. La tradición sostiene que quien mata a un mago que se encuentra fuera de la ley tiene derecho a cualquier botín que pueda poseer. 

Además de su papel de ejecutores de la Orden, los Hoplitas pueden ser llamados para acompañar a los Quasitores en investigaciones peligrosas, o para apresar a los fugitivos. Muchos Hoplitas empiezan trabajando con Quaesitores que conocen personalmente, como los miembros de su Alianza hogar. Con el tiempo, un mago que gana una buena reputación también puede ser llamado a ayudar a otros Quaesitores. 

Un Hoplita exitoso necesita poder de combate fuerte para abrumar a sus enemigos, y suficiente habilidad con magia Intellego para poder localizar a magos que huyen de la justicia hermética.

#### Cruzados 
Algunos magos de la Casa Flambeau creen que la Orden todavía enfrenta amenazas significativas de magos no herméticos. En Iberia y Tierra Santa, los magos sarracenos todavía practican sus artes, a veces con el patrocinio de los nobles musulmanes. El paganismo todavía prevalece en partes del Tribunal de Novgorod. En Escandinavia, hay rumores de una sociedad secreta de magos que obtienen su poder de los viejos dioses nórdicos. Incluso dentro del corazón de la Orden, el Rin y los Tribunales Romanos, todavía hay asistentes de sectas que han escapado al conocimiento de la Orden. 

Algunos son inofensivos, pero otros pueden convertirse en enemigos de la Orden, incluso diabolistas. La casa Flambeau tiene una larga trayectoria de lucha contra los enemigos de la Orden, reales e imaginarios. Los miembros de la Alianza son activos tanto en la Reconquista como en las Cruzadas en Tierra Santa. Mientras que el Código prohíbe a los magos de interferir en asuntos mundanos, los magos no herméticos generalmente carecen de restricciones similares. 

Luchar contra magos hostiles que están acompañados por mundanos cae en un área gris de la Ley Hermética. Los magos Flambeau que luchan en tales batallas a menudo afirman que realmente estaban luchando contra magos enemigos, y cualquier bajas mundanas eran simplemente los secuaces de los magos. 

Si los Quaesitores son persuadidos por tales explicaciones, y cuán agresivamente persiguen a los magos que luchan en las Cruzadas o Reconquista, es asunto de su grupo o de la **saga** decidirlo. Incluso si tu saga ocurre en algún lugar donde la Orden de Hermes hace cumplir el Código estrictamente, es probable que existan algunos magos Flambeau inconformista que piensan que pueden salir a luchar en las Cruzadas. 

En Tierra Santa, Iberia y otras áreas donde pueden encontrarse magos no herméticos, algunos miembros de la Casa Flambeau intentan llevar a cabo la obra de su Fundador reclutando a estos magos en la Orden. Otros afirman que los demás magos no herméticos han tenido tiempo suficiente para unirse a la Orden y deben haber decidido no hacerlo; se sienten justificados en purgarlos de la Europa mítica. Dado que los magos que mantienen estas dos visiones opuestas, por lo general, operan en las mismas áreas, a menudo chocan entre sí. Muchos certámenes e incluso algunas Guerras de Mago han sido realizados a causa del tema de los hechiceros no herméticos.

### Cazadores de demonios y exorcistas 
> [!cite]
> _Nunca permitas que el mal florezca._ 
— Flambeau 

Los [[Quaesitores]] son responsables de investigar signos de diabolismo dentro de la Orden, pero eso no significa que trabajen solos. Algunos miembros de la Casa Flambeau son expertos en la lucha contra los demonios, armados con hechizos como [[Destierro al Olvido Eterno (PeViGen)]]. Los demonios y el diabolismo no restringen sus actividades a la Orden de Hermes: se pueden encontrar entre mundanos y magos no-Herméticos también. En estas áreas, que están fuera de la autoridad directa de los Quaesitores, algunos magos Flambeau se han encargado de investigar y combatir la influencia demoníaca. El propio Fundador advirtió que los demonios eran una de las grandes amenazas a la Orden. Varios de sus seguidores dedican sus carreras mágicas a enfrentar esa amenaza. 

Los demonios son notoriamente difíciles de identificar porque sus “engaños” no pueden ser descubiertos con la magia hermética. Normalmente se requiere una combinación de magia Intellego y habilidades mundanas de investigación. Dado que El Don hace que sea difícil para los magos obtener información útil de los mundanos, los cazadores de demonios Flambeau a menudo dependen de la ayuda de grogs o compañeros. Un Compañero con las Virtudes de Fe Verdadera o Abjuración puede ser especialmente útil. 

loa magi Flambeau que se especializan en la lucha contra los demonios por lo general prefieren la Escuela de [[Apromor]], que es muy adecuado para la magia Perdo Vim.

#### Duelistas y Campeones 
A veces la mejor defensa de un magus para evitar convertirse en el objetivo de una Guerra del Magos es hacer que un alto magistrado de la Casa Flambeau jure vengarle. El Código Periférico no impide que los magos emprendan la Guerra de Mago para vengar a amigos y aliados muertos. Los magos Flambeau, especialmente aquellos con un sentido de caballería, a menudo están dispuestos a hacer una promesa pública de venganza para disuadir a otros magos de declarar la guerra. Ellos juran declarar la Guerra del Mago a cualquier mago que primero declare la Guerra del Mago a su aliado. 

El fundamento jurídico de esta práctica deriva del [[Tribunal Normando]] de 898 dC, que exoneró a Dominicus de Casa Jerbiton de mal comportamiento cuando utilizó la Guerra de Mago para vengar a un amicus (Amigo) que había sido asesinado en una guerra de Mago . El  Quaesitor Presidente dictaminó en la redacción del Código de que "ninguna retribución recaerá sobre el mago que me mata" significa sólo que la Orden no castigará al vencedor en la Guerra de Mago. Otros magos que desean vengar al perdedor de la Guerra del Mago siguen siendo libres de hacerlo, siempre y cuando declaren y pelen en la Guerra de Mago de acuerdo a lo establecido en el Código Periférico. 

Los magos tienen varias razones por las que podrían ofrecer convertirse en el vengador de otro mago. Pueden ser amigo íntimo (amici) de otro mago y desear protegerlo. Algunos magos Flambeau simplemente están sedientos de sangre y se comprometen a vengar a otros magos con la esperanza de tener la oportunidad de luchar una Guerra de Mago. Otros magos tienen un desarrollado sentido de caballerosidad lo que les motiva a defender a magos más débiles contra el acoso y la agresión. A veces un mago que busca protección ofrece pago o favores a cambio de una promesa de venganza. 

Otra forma en que magos de Flambeau sirven como campeones es en certamen. Muchos magos Flambeau disfrutan del certamen porque porque es lo más cercano que un mago puede legalmente llegar a la lucha contra otro mago, sin ser una Guerra de mago de la guerra o un torneo Flambeau. El Certamen se considera una forma práctica digna porque ejercita la habilidad en las artes, la penetración, y el Parma Magica. Aunque los miembros de la casa Flambeau carecen de ese talento especial para el certamen que tienen los magos Tremere, los años de la práctica del torneo han convertido a algunos de ellos en duelistas formidables. Los magos Flambeau sirven como campeones de certamen por varias razones: como caballerosidad, para proteger a sus amigos y sodales, o porque están siendo pagados. 

Además del duelo en los torneos de la casa, algunos magos de Flambeau viajan por la Europa Mitica desafiando a otros magos a un certamen por deporte y desafío.

#### Mercenarios y Aventureros
Magos de la Casa Flambeau prestan ocasionalmente sus habilidades de combate para ser usados como soldados de la fortuna. Las Alianzas a veces necesitan de músculo extra para ayudar a protegerse de la intimidación de una Alianza más grande, o de criaturas hostiles como   hadas oscuras o dragones. A veces dos o más magos Flambeau formarán una pequeña banda mercenaria y vagarán por la Europa Mítica buscando empleo. Como mercenarios mundanos, los soldados de la fortuna de Flambeau no son famosos por su lealtad. Pueden retirarse de las misiones que consideran demasiado peligrosas, o incluso cambiar de bando si la oposición les hace una mejor oferta. 

Otra variante del concepto de mercenario es el caballero andante mágico, que ayuda a otros magos (o mundanos) por generosidad de espíritu. Tanto los mercenarios como los caballeros andantes se sienten atraídos por conflictos importantes, como cuando dos alianzas importantes se convierten en rivales acérrimos o cuando la aplicación del Código se rompe en un área. 

#### Políticos y Oradores
Los magos Flambeau tienden a ser pragmáticos y proactivos. Pueden involucrarse en la política hermética con esperanzas de dar forma a las políticas de la Orden y promover sus causas favoritas. Flambeau mismo era un guerrero y un estadista; los magos Flambeau políticamente activos les gusta pensar que están emulando a su Fundador. 

La postura política de la casa Flambeau tiende a variar con el Primus. Cuando un primus relativamente nuevo e influyente está en el cargo, a veces intenta (con diversos grados de éxito) dirigir la Casa hacia una agenda política unificada. Si el primus es débil, los miembros de su casa le prestan poca atención y persiguen sus objetivos políticos individuales (a menudo conflictivos). La influencia actual del Primus está empezando a menguar, pero incluso cuando comenzó como primus busco realizar una reforma de su propia casa. 

Independientemente de los objetivos políticos del Primus, la Casa Flambeau generalmente favorece una interpretación más permisiva del Código. Por ejemplo, algunos de sus miembros creen que la restricción del Código contra la interferencia mundana no debería prohibirles que se unan con aliados mundanos contra un enemigo sobrenatural (como los diabolistas o un dragón). La Casa tiende a oponerse a cualquier tratado o restricción que restrinja su libertad de usar la fuerza contra oponentes sobrenaturales. 

Aparte de un interés compartido en dejar espacio legal para sus diversas actividades, los miembros de la Cámara tienen objetivos políticos variables, a veces conflictivos. Los magos Flambeau individualistas pueden ser influyentes dentro de sus tribunales de origen, pero la Casa en su conjunto tiende a carecer de influencia política debido a su falta de consenso. Los objetivos políticos de un magus de Flambeau pueden ser casi cualquier cosa; aquí hay algunos ejemplos posibles: 

- Persuadir a la Orden de tomar en serio una amenaza potencial como el rumor de la Orden de Odín, o putativa Orden de Suleiman. 

- Intentar construir alianzas militares o pactos defensivos entre los Alianzas, especialmente en los Tribunales fronterizos donde las amenazas parecen más comunes. 

- Establecer relaciones más amistosas con los mundanos y con la Iglesia. 

- Preparar la Orden para contrarrestar la agresión de los mundanos y la Iglesia. 

- Apoyar u oponerse a la reforma legal en la Orden (véase Tradicionalistas/ en Casas de Hermes: castas) 

- Garantizar el cumplimiento del Código en los Tribunales remotos 

- Defender el derecho de los magos a luchar contra magos no herméticos, por ejemplo, en las Cruzadas 

#### Cazadores y Mata-Dragones
La caza organizada es una actividad muy popular para los magos Flambeau. Por supuesto, los magos no suelen contentarse con perseguir solo a las bestias mundanas: prefieren la caza sobrenatural. Una cacería adecuada requiere un cazador experto para rastrear a la bestia. 

Además de la caza como deporte, algunos magos Flambeau buscan bestias sobrenaturales para obtener vis y los ingredientes mágicos raros que proporcionan. Los cazadores pueden trabajar solos, o con un pequeño equipo de grogs y compañeros. Los magos pueden buscar los servicios de un cazador para obtener los materiales que necesitan para sus proyectos e investigación. Algunos cazadores de Flambeau practican técnicas para capturar bestias mágicas vivas, para uso como familiares, mascotas o guardianes. De vez en cuando, una bestia sobrenatural se convierte en una amenaza para los mundanos o incluso magos: un cazador Flambeau está bien equipado para hacer frente a una amenaza de este tipo. 

Los magos Flambeau que se consideran cazadores suelen ser expertos en magia Animal. Intellego Animal e Intellego Vim pues son importantes para ayudarles a distinguir a las bestias sobrenaturales de las mundanas. Ellos confían en habilidades mundanas de caza y / o en la magia de Intellego para encontrar su Conexión Arcana a su presa (lo cual mejora su Penetración). Los cazadores pueden usar cualquier escuela de combate mágico, pero la mayoría de ellos evitan la Escuela del Fundador. Incinerar a una bestia con fuego no es una buena manera de preservar la vis y otras partes valiosas del cuerpo.

#### Proscritos y Pícaros 
No todos los magos Flambeau son honorables. Al igual que los caballeros ladrones de la Europa mítica, algunos miembros de la casa Flambeau, y otras casas, piden rescates o roban a los mundanos o incluso a otros magos. La magia puede ser muy útil para escapar de la captura: un magus inteligente puede ser capaz de vivir como un bandido durante mucho tiempo sin que se enteren los Quaesitores. 

Algunos magos forajidos son villanos que roban y matan a otros más débiles. Otros se ven a sí mismos como luchadores por la libertad, dispuestos a violar el Código para ayudar a resistir de un mal Rey o un invasor extranjero. Algunos se ven obligados a convertirse en bandoleros a causa del colapso de sus fuentes normales de ingresos de sus Alianzas. 

Al igual que los proscritos mundanos, los magos ladrones no siempre son profesionales: pueden estar recurriendo al pillaje como una actividad secundaria. La probabilidad de que los magos decidan volverse proscritos está relacionado con la estricta aplicación del Código en su Tribunal y en la saga en su conjunto. 

Incluso cuando los Quaesitores aplican el Código rigurosamente, puede haber algunos magos que sienten que las recompensas de ser bandolero merece la pena. 

Los ladrones-magos por lo general prefieren la magia que no es fácilmente evidente, por lo que sus víctimas no pueden identificarlos como magos. A menudo luchan según la Escuela de Ramius porque sus tácticas son menos intrusivas. En lugar de usar hechizos de ataque, los forajidos astutos prefieren usar la magia para el reconocimiento, la defensa y la evasión.

---

## Magia Flambeau

### Modificación de los Efectos para los Objetos Encantados 

Los magi de la Casa Flambeau han desarrollado una nueva forma de hacer más útiles los objetos mágicos en combate. Esto ha sido difundido en toda la Orden y está disponible para todos los magos. 

#### Gatillo rápido
El efecto gana un bono de +3 a la Iniciativa. Esto añade +5 al nivel del efecto 

### Habilidades de Hechizos Dominados

Las habilidades especiales conferidas por el Dominio de Hechizo son a menudo útiles en combate. Los Magos de la Casa Flambeau son aficionados a todas las habilidades especiales de de los Hechizos Dominados enumeradas en la Quinta Edición de Ars Magica (página 140) y han desarrollado algunas habilidades especiales adicionales propias. Estas están disponibles para los magos de cualquier casa, a pesar de que se originó dentro de la casa Flambeau. 

#### Lanzamiento Imperturbable 
Añade el nivel de hechizo Dominado del lanzador a todas las tiradas de Concentración relacionadas con el hechizo. Esto le ayuda a mantener la duración de los hechizos de Concentración en medio del caos de la batalla, o cuando lances otro hechizo. 

#### Lanzamiento Oculto
Los Magi no pueden identificar de manera automática la Forma del hechizo, cuando lo lanzas. Esto hace que sea difícil para ellos usar hechizos de Lanzamiento Rápido como defensa. Se considera que lanzas siempre el hechizo de forma sutil (Ver lanzamiento Rápido). Los magi deberán de realizar una tirada para determinar la Forma del hechizo que has lanzado: 

> [!skill] Determinar la Forma usada en un hechizo lanzado
> **(Percepción + Atención) vs. (15 – Magnitud del efecto) + Nivel del Hechizo Dominado.** 

#### Lanzamiento Preciso
Añade +1 a todas las tiradas de Apuntar que el lanzador realice con el hechizo, incluyendo Puntería a la tirada. Restar un dado de pifia de cualquier tirada de Apuntar que haga usando el hechizo, siendo el mínimo de uno. Un magi puede seleccionar esta habilidad varias veces para el mismo hechizo. 

#### Recitador Rápido
Añades +1 a la Iniciativa total del Lanzamiento cuando lances el hechizo Dominado. Si también tiene la habilidad especial de Lanzamiento Rápido, también se añade +1 a su velocidad de Lanzamiento Rápido. Esta habilidad no puede ser usada para hechizos Rituales. Un mago puede seleccionar esta habilidad varias veces para el mismo hechizo.

### Proyectiles y Magia de Rego 

Las leyes de la física en la Europa mítica se ajustan a las ideas medievales, no a las modernas. Las diferencias son a menudo sin importancia, pero se vuelven significativas cuando un mago utiliza hechizos de Rego para lanzar proyectiles o para dejar caer objetos pesados desde una altura. La física (o "filosofía natural" tiene numerosas contradicciones con nuestro paradigma pero este epígrafe aborda un tema concreto, en el que magos de la Casa Flambeau tienen más interés: cómo usar hechizos Rego como una forma de ataque. 

Hay tres formas diferentes de magia Rego puede ser utilizado de manera ofensiva. 

1. **Usar la magia para impulsar el proyectil hasta el objetivo**: En este caso, la fuerza motriz del proyectil se debe enteramente a la magia. 
	- La Resistencia Mágica protege contra esta forma de ataque con proyectiles, haciendo que se detengan de forma inofensiva en el borde de la Resistencia Mágica del objetivo, como se describe en [[Resistencia Mágica]]. 
	- Este tipo de hechizo no necesita ser dirigido (no precisa Apuntar)
	- Casi todos los hechizos de Rego en el libro de reglas ArM5 funcionan de esta manera
2. **Explotar el "movimiento natural":** la tendencia natural de los objetos pesados a caer hacia abajo. 
	> Un mago podría usar la magia de Rego para levitar una roca sobre la cabeza de alguien y luego cancelar el hechizo. La roca caería naturalmente y evitaría la resistencia mágica. 
	- Estos hechizos deben estar dirigidos a alcanzar sus objetivos.
3. **Usar un impulso mágico para lanzar un proyectil**, como una flecha se lanza desde un arco. 
	- Los Magos pueden inventar hechizos que lanzan proyectiles de esta manera: 
	- Solamente los hechizos de Rego diseñados especialmente pueden lanzar proyectiles de esta manera - la descripción del hechizo debe declarar explícitamente que puede lanzar proyectiles (estos hechizos son de mayor magnitud que los hechizos genéricos de Rego). 
	- Hechizos que lanzan liberan del control del proyectil inmediatamente después de lanzarlo. El proyectil continúa entonces sobre una trayectoria natural. 
	- La filosofía natural medieval explica cómo una flecha puede seguir moviéndose después de que esta salga propulsada por el arco: resumiendo, implica el movimiento del aire alrededor de la flecha. 
	- el hechizo debe ser apuntado, pero el proyectil evita la Resistencia Mágica.
	- El **Alcance** del hechizo sólo tiene que ser **Toque** (la magia sólo necesita actuar en el momento en que se proyecta el proyectil), pero una vez lanzado, el proyectil está sujeto a las leyes naturales del movimiento. 
	- La tirada de Apuntar sufre una penalización de alcance tal como lo hace un arma de proyectil  y la distancia del proyectil no puede superar la distancia que podría alcanzar un arco mundano muy poderoso (o eslinga, catapulta u otro dispositivo). 
	- La mayoría de los proyectiles lanzados por hechizos tienen un incremento de rango de 20 pasos. 

### Hechizos de combate flamboyanos
Los siguientes hechizos fueron creados para el combate por magi de la [[Casa Flambeau]] pero están disponibles para cualquier magus. 

#### Creo Animal 

> [!charm] Invocar a la Muerte Reptante
> *(Summoing the Creeping Death)*
> Cr(Re)An25
>A: Toque, D: Diam, O: Ind 
>Conjura una áspid, que obedece mágicamente las ordenes mentales del lanzador. Usa las estadísticas de una víbora del apartado de Bestias Mundanas (ArM, P.295), excepto que el veneno de un áspid es mucho más mortífero que el de una víbora. Los efectos del veneno de áspid se dan en la página 265 de ArM5, Dificultad 9. La serpiente no tiene Fuerza y por lo tanto no tiene Resistencia Mágica propia, pero como es una criatura creada mágicamente, Resistencia Mágica protege contra su ataque (usa la Penetración Total del lanzador). Este hechizo es usado a veces por los magos que siguen la escuela de Sebastián, pero otros magos de Flambeau tienden para despreciarlo como una forma innoble del ataque. 
>
>(Base 10, +1 Toque, +1 Diámetro, +1 Rego requisito)

#### Rego Animal 

> [!charm] Carga de Furia
> *(Fury of the Charging Bull)*
ReAn 20 
A: Voz, D: Mom, O: Ind 
El animal objetivo (que puede ser tan grande como tamaño +3) se enfada y debe hacer una tirada de Personalidad usando un Rasgo como Enfadado o Fiera (o quizás otros, a discreción del Director de juego). Si la tirada supera un Factor de Dificultad de 9, el animal entra en una rabia. Una vez que el animal es excitado, se calma con normalidad. Los animales dóciles como las ovejas o los bueyes se calman casi inmediatamente, mientras que los animales especialmente agresivos como los jabalíes o los lobos pueden causar un alboroto que dura varios minutos. Mientras está enojado, el animal trata de expulsar a la gente u otros animales que están cerca, y puede atacar a los que no huyen de él. 
Algunos magos que siguen la Escuela de Vilano utilizan este hechizo para hacer que los animales ataquen a sus enemigos. En la práctica, sus efectos son impredecibles, es igual de probable que el animal ataque a cualquier espectador como el objetivo previsto, ¡y no hay nada que le impida de atacar al magi! 
(Base 5, +2 Voz, +1 tamaño)

#### Creo Aquam 

> [!charm] **Daga de Hielo** 
(Dagger of Ice)*
Cr(Re)Aq 10 
A: Voz, D: Mom, O: Ind 
Crea un carámbano de un pie de largo y ancho y lo lanza a un objetivo. El carámbano impacta automáticamente. Siempre y cuando que penetre la Resistencia Mágica de objetivo. Inflige +5 de daño (en parte debido a su parte en forma de punzón). Después del impacto, el carámbano se rompe a pequeños fragmentos, que desaparecen rápidamente. 
(Base 3, +2 Voz, +1 Rego requisito)

> [!charm] **Venganza del Alquimista** 
*(Alchemist’s Revenge)*
CrAq 25 
A: Voz, D: Mom, O: Ind 
Rocía a un Objetivo con ácido, infligiendo +15 de daño si penetra la Resistencia Mágica. A elección del director de Juego, el ácido puede dañar el equipo del objetivo. 
(Base 15, +2 Voz)

#### Rego Aquam

> [!charm] **Grilletes de Hielo** 
(Shackles of the Frozen Ice)*
ReAq 1220. 
A: Voz, D: solar, O: Parte 
Congela una porción circular de una masa de agua en hielo sólido. Cualquier persona que este vadeando o nadando en el agua queda atrapado en el hielo. 
La Resistencia Mágica no impide que el hielo rodee a un personaje y lo atrape. El área afectada por el hechizo es de **Base Individual**: un volumen aproximado de 1,5 mts de ancho (diámetro) y 0,60 mts de profundo. 
Puesto que el hielo es mágico, sólo inflige daño frío si penetra la Resistencia Mágica. Las reglas para el daño por frío se dan en ArM5, página 266; el hielo creado por este hechizo inflige un daño base de +1. Los personajes que están completamente envueltos en hielo comienzan a ahogarse (véase ArM5, página 265). 
Un personaje atrapado puede romperse del hielo haciendo una tirada de Fuerza. Los personajes también pueden cavar su salida del hielo usando herramientas o armas, pero esto toma tiempo. La Magia, incluyendo los hechizos Perdo Aquam o Creo Ignem, puede liberar un personaje al instante. 
(Base 3, +2 solar, +1 Parte)
>
| **Nivel de cobertura del hielo** | **Tirada de Fuerza** | **Tiempo para liberarse** |
| -------------------------------- | -------------------- | ------------------------- |
| Un pie                           | 6                    | 30 segundos               |
| ambos pies                       | 9                    | 1 minuto                  |
| Hasta las rodillas               | 12                   | 3 minutos                 |
| Hasta la cintura                 | 15                   | 10 minutos                |
| Hasta el pecho                   | 18                   | 15 minutos                |
| Hasta el cuello                  | 21                   | 20 minutos                |
| Completamente Cubierto           | 21                   | Depende de la profundidad |

#### Creo Auram 

> [!charm] **Catapulta de los poderosos Vientos** 
(Catapult of the Mighty Winds)*
Cr(Re)Au 30 
A: Voz, D: Mom, O: Ind 
Vientos terriblemente fuertes barren un objeto (como un barril, un mueble o un desafortunado ser humano) y lo lanzan sobre, haciendo una trayectoria arqueada, hacia cualquier punto dentro del alcance. Si el proyectil tiene resistencia mágica, este hechizo debe penetrarla para poder afectarlo. Sin embargo, una vez que el proyectil está en el aire, su movimiento es natural y por lo tanto, elimina la resistencia mágica de cualquier cosa que golpea. Debe tener éxito en una tirada de apuntar para golpear el objetivo previsto. Debido a que este hechizo le da al lanzador sólo un control indirecto del proyectil, la tirada de Apuntar sufre un penalizador de -3 y un dado de pifia adicional. Los vientos son lo suficientemente fuertes como para lanzar a un hombre adulto de 6 metros en el aire. Tanto el proyectil, como cualquier cosa debajo de este, sufren daños cuando se estrella contra la tierra: el daño es normalmente de +10 pero podría ser menor si el proyectil es considerablemente más ligero que un humano adulto. 
(Base 5, +2 Voz, +2 Artificial, +1 Rego requisito)

#### Muto Auram 

> [!charm] **Maldición de los Malos Humos** 
(Curse of the Evil Humors)*
MuAu 25 
A: Voz, D: Diam, O: Parte 
Convierte el aire limpio en humo sucio que pueden causar enfermedades. Los humos forman una nube de 1,5 mts de ancho y 0,6 mts de altura. Son invisibles pero malolientes y nocivos. Los personajes que respiran el aire ensuciado deben hacer una tirada de resistencia contra un Factor de dificultad de 6 o contraer la malaria (tirar solo la primera vez que un personaje se exponga). 
Esta enfermedad, cuyo nombre es italiano por "mal aire", provoca una herida media. Una vez que un personaje ha contraído la enfermedad, una mayor exposición a este hechizo no tiene efecto. Los malos humos se disipan cuando termina la duración del hechizo. Una brisa rápida puede dispersar los humos en dos o tres asaltos, y los vientos fuertes hacen de este hechizo inútil. 
(Base 5, +2 Voz, +1 Diámetro, +1 Parte)

#### Rego Corpus

> [!charm] **Zancada del mago** 
*(Wizard’s Leap)* 
ReCo 15 
A: Per, D: Mom, O: Ind 
El lanzador se transporta instantáneamente hasta 15 metros en cualquier dirección, siempre que pueda ver su destino o tenga una Conexión Arcana. Su talismán viaja con él automáticamente, los requisitos de lanzamiento se requieren para traer cualquier otra ropa o equipo. Este hechizo es muy efectivo como defensa de _lanzamiento rápido_ para escapar de ataques u otros contratiempos, y también puede ser utilizado para evitar obstáculos o lanzar ataques sorpresa. 
(Base 15)

#### Muto Herbam 

> [!charm] **Aegis de la Madera irrompible** 
*(Aegis of Unbreakable Wood)*
MuHe 15 
A: toque, D: Solar, O: Ind. 
Haces un escudo de madera (u objeto de dimensiones similares) tan fuerte como el hierro, aumentando su bono de Defensa en +1. Este es el mejor bono que la magia puede proporcionar sin aumentar el tamaño del escudo. El peso (y la carga) del protector no se modifican. Sigue siendo susceptible al fuego, pero es casi indestructible. 
(Base 4, +1 Toque, +2 Solar)

#### Perdo Herbam 

> [!charm] **El Árbol que cae en el bosque** 
*(Tree Falling in the Forest)*
Pe(Re)He 35 
A: Visual, D: Mom, O: Ind 
Corta un árbol al instante, haciéndolo caer en la dirección que el lanzador quiera. Con una tirada exitosa en apuntar, puedes hacerlo caer sobre una criatura. El daño es de hasta +18 para un árbol maduro, y la víctima o las víctimas también pueden ser atapadas por el peso del árbol. Cuando se usa como forma de ataque, este hechizo evita la resistencia mágica. 
(Base 5, +3 Visual, +2 tamaño, +1 Rego requisito)

####  Creo Ignem 

> [!charm] **Prueba de las llamas** 
*(Test of the Flames)*
CrIg 15 
A: Toque, D: Anillo, O: Circulo 
Las llamas de una altura hasta la cintura llenan el círculo objetivo. Todo dentro del círculo tiene +5 de daño cada ronda. Este hechizo es de origen antiguo y se cree que se originó como una prueba ritual dentro del Culto de Mitras. Fue utilizado una vez por los magos de Flambeau como prueba de la resistencia, una especie de alternativa al certamen. 
Las personas sometidas a prueba (incluyendo, por lo general, el lanzador) permanecerían dentro del círculo, sin usar su Parma Mágica, tratando de resistir las llamas durante el mayor tiempo posible. La última persona que dejó el círculo se considerada la ganadora. El protocolo sugiere que si alguien cae indefenso debido a quemaduras se rompe el Anillo, terminando con el hechizo, para rescatar al desafortunado. 
Esta prueba es poco utilizada en 1220 porque la mayoría de los magos Flambeau prefieren el certamen estándar; también, algunos miembros de la Casa Flambeau poseen una inmunidad sobrenatural al fuego, dándoles una ventaja injusta en la prueba. 
(Base 4, +1 Toque, +2 Anillo)

> [!charm] **El Último vuelo del Fénix** 
*(Last Flight of the Phoenix)*
CrIg 50 
A: Per, D: Mom, O: Ind 
El lanzador arde en llamas, inmolándose en una bola de fuego blanco-caliente que causa:
>
> **Tomando como centro al personaje inmolado...**
> 
> |  Un radio de... |  Daño |
|---|---|
|1,20 mts|+45|
|Entre 1,20 y 1,80 mts|+20|
|Entre 1,80 y 3,00 mts|+5|
>
>Dentro del radio de 1,20 metros el fuego está lo suficientemente caliente como para fundir el acero. Suele ser usado por los magos que tienen alguna virtud mayor de inmunidad contra el fuego. Dado que su rango es personal, elimina la propia resistencia mágica del lanzador. 
Una versión temprana de este hechizo se encontró en las notas de laboratorio del propio Flambeau. Algunos miembros de su Casa especulan que puede haber usado para salir en un resplandor de gloria en una batalla final contra sus enemigos moros. 
(Base 40, +2 tamaño)

#### Perdo Ignem 

> [!charm] **Apagar el Incendio furioso** 
*(Quench the Raging Conflagration)*
PeIg 20 
A: Voz, D: Mom, O: Ind 
Extingue cualquier fuego hasta el tamaño de un incendio en la casa. Muchos Magos Flambeau aprenden este hechizo, o llevan objetos encantados con un efecto similar, para controlar cualquier incendio accidental causado por la magia de Creo Ignem. 
(Base 4, +2 Voz, +2 Tamaño)

#### Rego Ignem 

> [!charm]  **El fuego obediente** 
*(The Obedient Fire)*
ReIg 20 
A: voz, D: Conc, O: Ind 
Controlas la velocidad y la dirección en la que se extiende un incendio. El lanzador puede hacer que el fuego se extienda a través de las superficies combustibles tan rápido como el caminar un hombre. Puede saltar la mayoría de las brechas, como un paso a través, pero no puede cruzar incluso el riachuelo más minúsculo del agua. El lanzador puede evitar que el fuego se extienda en ciertas direcciones, pero en realidad no puede evitar que se queme las cosas que toca. 
Podría, por ejemplo, hacer que un fuego se extendiera en forma de círculo y luego expandirse hacia afuera, o mantener el fuego alejado de sí mismo mientras sigue a sus enemigos alrededor de la habitación. 
Si el fuego rodea a un personaje, su calor no es mágico y por lo tanto ignora la resistencia mágica. Se requiere una tirada de puntería para que el fuego se cierre lo suficiente como para dañar. Si el fuego crece más que un **Objetivo Sala**, el lanzador pierde el control. 
(Base 4, +2 Voz, +1 Concentración, +1 Tamaño)

#### Creo Mentem 

> [!charm] **Corazon de El León** 
*(Heart of the Lion)*
CrMe 15 
A: Ocular, D: Solar, O: Ind 
Mejora a una persona con coraje indomable, aumentándole su Rasgo de Personalidad Valiente a +3. Esto puede, pero no siempre, llevar a actos de imprudencia. Si lanzas este hechizo en tus grogs, se aconseja que perderán su miedo hacia ti así como su miedo al enemigo. 
(Base 4, +1 Ocular, +2 Solar)

####  Creo Terram 

> [!charm] **Espada de la vaina invisible** 
*(Sword from the Unseen Scabbard)*
CrTe 15 
A: Toque, D: Diam, O: Ind 
Conjure una espada larga de acero. La espada sólo dura dos minutos - alrededor de 20 asaltos de combate -, pero que suele ser suficientemente tiempo para defenderse de una escaramuza. La espada creada mágicamente debe penetrar la resistencia mágica para dañar a los oponentes que tienen Resistencia Mágica. Tenga en cuenta que la creación de cosas artificiales con magia requiere una tirada de inteligencia + Precisión, como se indica en la página 125 de ArM5. Un Factor de Dificultad de 6 es suficiente para hacer una espada de mano de obra mediocre, pero útil. 
(Base 5, +1 Toque, +1 Diametro)

> [!charm] **Caballero de la Armadura plateadas** 
*(Silvery Scales of the Knight)*
CrTe(An) 30 
A: Toque, D: Solar, O: Ind 
Conjure una Armadura completa **_Cota de malla_**. El requisito Animal es necesario para crear las correas de cuero de la armadura, relleno de lana, y gambeson - sin estos elementos, la armadura no sería eficaz. El estilo de la armadura, incluyendo cualquier cresta que aparece en el casco, depende del Sigil de su Mago. La armadura es mágica, por lo que su portador no podrá golpear o agarrar, mientras use guanteletes creados, a una criatura mágica o resistente a la magia sin superar la resistencia de este. La armadura tiene la misma carga que la armadura no mágica, y se tarda el mismo tiempo en ponérsela (varios minutos como mínimo). 
Se requiere una tirada Inteligencia + Precisión contra un factor de dificultad de 9 para crear una armadura de calidad promedio; una tirada fallida puede causar o una reducción de la Protección y / o un incremento de carga, a discreción del director de juego. 
(Base 5, +1 Toque, +2 Solar, +2 Forma muy elaborada (Artificial))

#### Muto Terram 

> [!charm] **Dureza de la Adamantina** 
*(Hardness of Adamantine)*
MuTe 25 
A: Toque, D: Solar, O: Ind 
Este hechizo infunde un objeto de metal con una fuerza y dureza sobrenatural. Incluso los metales más débiles como el oro o el plomo pueden verse afectados. El objeto se vuelve casi inquebrantable por medios mundanos. Si se usa en armadura de Cota de malla o Escamas de metal, el valor de protección de la armadura se incrementa en +2. 
Si se usa en un arma afilada o puntiaguda, el arma gana +1 a daño. Este bono se puede combinar con el hechizo _El Filo del Escalpelo_ (ArM5, P.231) u otros hechizos. 
(Base 4, +1 Toque, +2 Solar, +2 afectar al metal)

#### Perdo Terram 

> [!charm] **Deshacer la obra de un albañil** 
*(Undoing the Stonemason’s Handiwork)*
PeTe 15 
A: Voz, D: Mom, O: Parte 
Este hechizo rompe un pedazo de mampostería o pavimento en sus componentes ladrillos o piedras. No tiene efecto sobre la piedra sólida. El volumen afectado es un 0,30 mts de ancho, alto, y profundo (dependiendo del grosor de la mampostería), y puede ser una parte de un una pieza (obra mampostería o pavimento) más grande. 
Los seguidores de la Escuela de Vilano a veces utilizan este hechizo para producir un gran número de piedras sueltas, que luego pueden utilizar como munición. Los magos con un conocimiento de la cantería pueden utilizarlo para debilitar o colapsar las estructuras de piedra dañando los puntales de las paredes y los arcos, aunque los pilares sólidos y similares son inmunes a sus efectos. 
(Base 3, +2 Voz, +1 Parte, +1 Destruir piedra)

> [!charm] **Armadura Liviana** 
*(Hauberk of Sublime Lightness)*
PeTe 30 
A: Toque, D: Solar, O: Ind 
Vuelve a una armadura de metal liviana, eliminando casi por completo su peso. Armadura hecha de cuero reforzado con metal, Cota de malla o Escamas de metal reduce su carga a 1 para la armadura parcial, y a 2 para la armadura completa. El hechizo elimina el peso de la armadura, pero no su volumen. 
(Base 5, +1 Toque, +2 Solar, +2 afectar al metal)

#### Rego Terram 

> [!charm]  **Honda Invisible de Vilano** 
*(Invisible Sling of Vilano)*
ReTe 10 
A: Toque, D: Mom, O: Ind 
Lanza una piedra, de un tamaño similar al que podría ser lanzado con una honda mundana, a un objetivo dentro del alcance. A diferencia de la versión estándar de _Honda Magica_ (ArM5, página 232), este hechizo arroja la piedra como si fuese un proyectil. 
Requiere una tirada de puntería para alcanzar el objetivo deseado, si tiene éxito, La Resistencia Mágica no ofrece protección. La piedra inflige +5 de daño al impacto y tiene un incremento de rango de 20 Pies. 
(Base 5, +1 Toque)

> [!charm] **Levantamiento Ominoso de la Piedra Pesada** 
*(Ominous Levitation of the Weighty Stone) 
ReTe 15 
R: Voz, D: Conc, T: Ind 
Mover una piedra a través del aire tan rápido como un pájaro vuela. Cuando el lanzador deja de concentrarse, la piedra cae inmediatamente al suelo. 
El nombre del hechizo sugiere una de sus aplicaciones comunes: dejar caer una roca pesada sobre alguien. Debido a que la piedra cae naturalmente, tal ataque no está sujeto a la Resistencia Mágica. En su lugar, se requiere una tirada de Apuntar para alcanzar el objetivo deseado (véase ArM5, página 138). 
Atacar con este hechizo toma dos rondas: una para mover la piedra sobre el objetivo y otra para apuntar y soltar. 
El daño infligido depende principalmente del tamaño de la piedra: +5 para una piedra del tamaño de un puño de hombre, +10 para una piedra de construcción típica, hasta +21 para una piedra grande (véase también la Tabla de Impacto en la página 266 de ArM5). Las piedras particularmente grandes pueden dañar estructuras así como criaturas. 
La limitación principal en la eficacia de combate de este hechizo es la disponibilidad de piedras grandes. El mismo Vilano se lamentó más de una vez pues nunca había una buena roca cuando uno la necesitaba 
(Base 3, +2 Voice, +1 Concentration, +1 affect stone)



