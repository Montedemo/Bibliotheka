---
Tags: Category/Group/Hermetic
categoria: organización/institución
clase: Hermética 
tipo:  Escuela de combate
Region: 
PrimaryHome: 
Casa: Casa Flambeau
Tribunal: 
Gobierno: 
superior: 
Vinculo: 
Reputaciones: 
Founded: 
Founder: Boreas
Disbanded: 
Leader: 
Titulo: 
NoteIcon: hermetic
---

> [!infobox]
> # `=this.file.name`
> ![[ImagePlaceholder.png]]
> ###### `=this.categoria`  `=this.clase` 
>  |   |
> ---|---|
> Tipo |  `=this.tipo`|
> Sede | `=this.PrimaryHome`|
> Ámbito | `=this.region`|
> Tribunal | `=this.Tribunal`|
> Casa | `=this.Casa`|
> ###### Política  
>  |   |
> ---|---|
> Dirigente | `=this.leader`|
> Título | `=this.titulo`|
> Parte de | `=this.superior`|
> Sistema de gobierno | `=this.Gobierno`|
> ###### Historia 
>  |   |
> ---|---|
> Fundador/es | `=this.Founder`|
> Fundado en | `=this.Founded`|
> Disuelto en | `=this.Disbanded`|
> ###### Integrantes 
>```dataview
TABLE WITHOUT ID link(file.name) AS "Miembro", Titulo, ☠
from "3. Personajes y Organizaciones 🧑‍🤝‍🧑/Personajes"
where contains( AssociatedGroup, this.file.name)
SORT file.name DESC
>```
>###### Vínculos
>```dataview
TABLE WITHOUT ID link(file.name) AS "Grupo", tipo, leader
from "3. Personajes y Organizaciones 🧑‍🤝‍🧑/Grupos"
where contains( Vinculo, this.file.name)
SORT file.name DESC
>```
# `=this.file.name`

La Escuela de Boreas se basa en la única combinación Forma-Técnica de Perdo Ignem. Boreas era un mago del siglo IX que descendía de [[Flammans, el Fundador]] a través de la línea de [[Apromor]]. Él intentó tender un puente sobre el cisma existente en su linaje desarrollando una escuela del combate que era accesible a los seguidores de Flambeau ya los seguidores de Apromor. 

La mayoría de los magos encuentran la Escuela de Boreas demasiado especializada para ser muy interesante. Incluso la Escuela del Fundador es más amplia y versátil. 

La Escuela de Boreas tiene sus ventajas, por lo que los seguidores de otras escuelas a veces se basan en ella como una forma de ataque secundario. 

El frío y la oscuridad son áreas suficientemente especializadas para que cada una se califique como una de Virtud **_Foco mágico menor_**. Los magos que tengan las virtudes de **_Afinidad en Perdo, Afinidad en Ignen o Foco_** pueden ser muy efectivos cuando usan esta escuela. 

La Especializacion de Boreas y sus hechizos basados en el frío evitan algunas de las debilidades tanto de la Escuela del Fundador como de la Escuela de Apromor. Los hechizos fríos que se desvían no pueden incendiar los edificios. Además el frío puede dañar la mayoría de los seres vivos con una sola Forma, reduciendo la necesidad de que un seguidor de Apromor aprenda múltiples Formas para afectar a personas, animales y hadas. 

En este sentido, Boreas tuvo éxito en su intento de crear una escuela de combate que combinase los dos principales linajes dentro de su Casa. De igual forma que las escuelas del Fundador y de Apromor, los ataques en la Escuela de Boreas necesitan penetrar la Resistencia Mágica. 

Debido a que la Escuela de Boreas enfatiza sólo una combinación de Forma-Técnica, requiere menos estudio para dominar que la Escuela de Apromor. Algunos jóvenes magos Flambeau eligen especializarse en la Escuela de Boreas al inicio de sus carreras y luego diversificar en el uso de la Escuela de Apromor a medida que se vuelven más expertos en múltiples formas. 

La principal limitación de la Escuela de Boreas es la limitada variedad de hechizos disponibles en las Artes de Perdo Ignem. Dispone de hechizos de oscuridad, que pueden ser útiles para el sigilo. Por otro lado Los hechizos de Perdo Ignem causan menos daño que los hechizos de Creo Ignem de similar magnitud, pero son tan efectivos como los hechizos de Perdo Corpus.
