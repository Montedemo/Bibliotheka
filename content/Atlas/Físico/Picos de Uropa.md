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
 <section class="wa-section main-content"><p><span class="dropcap">L</span>OS Picos de Uroba son el macizo montañoso que corona la cornisa montañosa del norte de Spania hacia el Mar Cantábrico, entre las dos Asturias y León. Aunque no muy extenso, su cercanía al mar hace que sea pródigo en accidentes geográficos de gran interés.
<br /></p></section>  <section data-section-id="sidebarcontent" class="wa-section public"><dl><dt>General Details</dt><dd><div id="3ad6480e61edd5bc1a0e0db9a9faef3f" class="visibility-toggler image-thumb-container user-css-image-thumbnail position-relative padding-10 "><img src="https://worldanvil.com/uploads/images/4cf3d7cf2393404c722b8c50dc4577e5.jpg" alt title="640px-Vega_de_Urriello_y_el_Picu._Destacan,_a_su_derecha,_los_Tiros_de_la_Torca_y_la_bicéfala_cumbre_de_la_Morra.jpg" /></div></dd></dl></section><section data-section-id="alternativename" class="wa-section public"><dl><dt>Alternativename</dt><dd>Uropa. Monte Vindio, Mons Vindius</dd></dl></section><section data-section-id="geography" class="wa-section public"><h2>Geography</h2>
<p>Esta formación caliza se extiende por las dos Asturias y León, y en ella destacan sus alturas, en muchos casos por encima de los 2500 m s. n. m., por lo cerca que se encuentran del mar Cantábrico, pues en su punto más septentrional apenas distan 15 kilómetros del mar.
<br />
Los Picos de Uroba están divididos en tres macizos: el macizo occidental o Cornión, el macizo central o de los Urrieles, y el macizo oriental o de Ándara.
<br />
Las mayores alturas se encuentran en el macizo de los Urrieles, que pasa por ser el más agreste de los tres, pues catorce de sus cimas superan los 2600 m de altitud, con la Torre Cerredo, de 2650 m, como techo de estas montañas y tercer máximo de toda la Spania, después de Sierra Nevada y los Pirineos. Otra montaña que forma parte de este macizo es el Picu Urriellu, de gran importancia histórica.
<br />
En el macizo de Cornión, llamado así por la forma de cuerno que ofrece su silueta al ser visto desde el oeste, destaca la Peña Santa, que con sus 2596 m de altitud supera en 110 m a la siguiente cima de este macizo, la Torre de Santa María o Torre Santa de Enol. Por estas dos montañas, la Peña Santa y la Torre Santa, este macizo se conoce asimismo como el de las Peñas Santas.
<br />El macizo de Ándara, donde se ubica el circo del mismo nombre, es el más modesto de los tres, tanto en altura (su techo, la Morra de Lechugales, alcanza los 2444 m de altitud) como en verticalidades.</p><hr /></section><section data-section-id="history" class="wa-section public"><h2>History</h2>
<p>El monte Vindio es una denominación histórica de un monte perteneciente a la cordillera Cantábrica, si bien hoy en día su situación geográfica es totalmente incierta, pero se atribuye tradicionalmente al sector oriental de los Picos de Uroba.
<br />
Durante las guerras cántabras, en el año 26 a. C., tras la derrota de las tribus cántabras en la batalla de Bérgida, que algunos autores localizan en Valberga (Burón), muy próximo al macizo del Mampodre y Riaño; otros en Bergidum, que sitúan en El Bierzo; y la mayoría de los tratadistas de Cantabria lo relacionan con la ciudad fortificada de Vellica que cita Ptolomeo en Cantabria, donde los cántabros supervivientes se retiran en busca de refugio entre los riscos de este monte.
<br />
En cualquier caso, la batalla del monte Vindio forma parte del relato histórico que Floro titula Bellum Cantabricum. Es decir, la campaña militar romana contra los cántabros. Por otra parte, el Bellum Asturicum de Floro hace referencia a la campaña militar contra los ástures.
<br />
Según Floro, el Vindio era tan inaccesible que hasta los propios cántabros se sentían seguros al pensar que antes subirían allí las olas del mar que las legiones romanas. De nada serviría, pues según Orosio, los nativos son asediados por las tropas romanas que entran a través del valle del Cares, Duje y Dobra. Las tropas romanas son reforzadas por tropas desembarcadas en Nueva de Llanes, en Asturias que atraviesan la sierra de Cuera hacía el concejo asturiano de Onís.
<br />
La resistencia fue inútil. En el otoño del año 25 a. C. la mayoría de los cántabros perecerían de inanición y por frío.</p><hr /></section><section data-section-id="florafauna" class="wa-section public"><h2>Florafauna</h2>
<p></p><h5>Flora</h5>
La escasa distancia de los Picos de Europa a la costa, de aproximadamente 30 kilómetros, permite que en ellos se desarrollen especies vegetales tanto atlánticas como mediterráneas. La vegetación presente en los Picos se puede diferenciar según la altura a la que se encuentra. Así se pueden señalar las áreas dominadas por la encina, el roble y el haya.
<br />
Por encima de los 1500 m, debido a la altura y a lo escarpado del terreno, la presencia vegetal se limita, allí donde el suelo lo permite, a la pradera alpina. Destacan especies del género Sedum y Saxifraga entre las grietas de las rocas. A menor altura se puede apreciar la presencia de especies vegetales como el fresno, el enebro, el abedul, el nogal o el tilo, así como algunas especies de flores, como la aguileña cantábrica, el alhelí de campo o la siempreviva. También podemos encontrar plantas carnívoras, como la Pinguicula vulgaris.
<br />
Son sus ancestrales hayedos uno de los elementos característicos de su paisaje vegetal.
<h5>Fauna</h5>
De la fauna presente en los Picos de Europa destaca el rebeco cantábrico (Rupricapra pyrenaica parva). Su presencia en las zonas más elevadas de los macizos resulta tan espectacular como sorprendente es su agilidad en un terreno tan difícil, pues es el único que osa aventurarse en los Picos hasta sus zonas más altas.
<br />
En lugares más accesibles hay una mayor variedad de especies, como el corzo, el ciervo, el jabalí, el zorro, el oso o el lobo. En los ríos, la nutria, el mirlo acuático, el Martín pescador, el salmón atlántico y la trucha. Y sobre todo al peculiar urogallo, que aunque su presencia es mayor en la Cordillera Cantábrica, aquí también se puede ver y escuchar su canto. El urogallo habita en los bosques, donde convive con el pito negro (Dryocopus martius), la perdiz, el gato montés, el lirón, la ardilla y la gineta.
<br />
Entre las más de 100 variedades de aves que se pueden encontrar en el parque natural, destacan las grandes rapaces, como el águila real, el águila culebrera, el alimoche, el buitre leonado y el quebrantahuesos. También habitan la chova piquirroja, la chova piquigualda y el cuervo. Y se puede observar el vuelo del acentor, la bisbita y el gorrión alpino.<p></p><hr /></section>   

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

