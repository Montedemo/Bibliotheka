---
Tags: Category/Group/Hermetic
categoria: organización/institución
clase: Hermética 
tipo: Escuela de Combate 
Region: 
PrimaryHome: 
Casa: Casa Flambeau 
Tribunal: 
Gobierno: 
superior: 
Vinculo: 
Reputaciones: 
Founded: 800
Founder: Sebastian 
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

**Virtud Recomendada**: Focus Mágico (Menor o Mayor) 

Las Escuelas de Sebastián son una familia de escuelas que se basan en conjurar objetos o sustancias dañinas usando Formas distintas a Ignem. Sebastian era un antiguo mago del siglo VIII que se unió a la Orden como miembro de la [[Casa Flambeau]]. Logró la inusual proeza de aprender la magia hermética después de haber sido entrenado en una tradición no hermética, que le obstaculizo el desarrollo eficiente en varias artes. 

Sebastián desarrolló un método de lucha basado en su única fortaleza, la Forma de Aquam. "Las Escuelas de Sebastián" es realmente un apodo para un gran número de escuelas secundarias basadas en formas inusuales: 
- la Escuela de Ebroin, basada en animales de conjuración; 
- la Escuela de Marosa, basada en los ataques de Herbam; y así. 

Incluso los miembros de la Casa Flambeau tienen problemas para seguir el rastro de tantas pequeñas escuelas (algunas de las cuales sólo tienen un único miembro vivo), por lo que las "Escuelas de Sebastián" han surgido como un término genérico. La actual Escuela de Sebastián fue sólo la primera y más famosa de estas escuelas menores. La mayoría de los miembros de la familia de las Escuelas de Sebastian tienen un foco mágico (mayor o menor) y diseñan sus ataques para aprovecharse de ese foco. Las escuelas son también atractivas para los magos que quieren especializarse en Artes, además de Perdo o Ignem. Tales Artes pueden tener usos distintos al combate. 

Como las escuelas del Fundador y de Apromor, las Escuelas de Sebastián dependen de la capacidad de penetrar la Resistencia Mágica. Tienden a ofrecer hechizos que hacen menos daño en comparación con hechizos de Ignem de magnitud similar. Las escuelas siguen siendo una buena opción para los magos que quieren especializarse en ciertas formas (Animal, Aquam, Herbam o Terram). Se utilizan comúnmente fuera de la casa Flambeau por los magos que piensan de sí mismos como especialistas más bien que combatientes, pero que desean estar listos para defenderse.


#### Focos Mágicos para la Escuela de Sebastián
Algunos ejemplos de focos mágicos que pueden ser útiles para los magos que siguen la Escuela de Sebastián. Todos funcionan como Focos Mágicos Menores, a no ser que se indique lo contrario. Las Formas de Mentem, Imaginem y Vim son inadecuadas para conjurar sustancias nocivas, y los magos que se especializan en la Forma de Ignem se clasifican dentro de las Escuelas del Fundador o de Boreas. 

- **Animal:** Aves (mayor), Insectos Venenosos, serpientes, canidos, dientes. 

- **Aquam:** Acido, veneno, Aceite hirviendo 

- **Auram: C**lima (mayor), relámpagos, gas venenoso 

- **Corpus:** Necromancia (mayor), animar cadáveres, huesos humanos 

- **Herbam:** Espinas, Parra, Plantas Toxicas 

- **Terram:** Filos, Metal Fundido, Estalagmitas/estalactitas 

Para ver algunos ejemplos de Foco Mágico menor y Mayor en ArM5, páginas 77 y 78.