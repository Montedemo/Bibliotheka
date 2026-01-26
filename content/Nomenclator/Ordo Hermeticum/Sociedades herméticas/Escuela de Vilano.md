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
Founded: 
Founder: Vilano
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

**Virtud Recomendada:** Afinidad con (Puntería) o Cuidadoso con (la habilidad Puntería). 

La Escuela de Vilano se basa en ataques indirectos que evitan la Resistencia Mágica. Un ejemplo de un ataque indirecto es usar la magia para levitar una roca sobre la cabeza de alguien, y luego dejar caer la roca. Varios ejemplos de ataques indirectos se dan en ArM5, página 139. 

[[Vilano]] era un mago Flambeau del siglo IX de Istria en el [[Tribunal Transilvano]]. Sufría del defecto Hermético Magia Débil, pero permaneció decidido a probarse a sí mismo en la batalla. Vilano fue el primer miembro de la [[Casa Flambeau]] en tener éxito usando solo hechizos indirectos, el más famoso cuando mató al Dragón Verde de Labin aplastándolo con dos árboles. Sus tácticas han sido ampliamente emuladas dentro y fuera de su Casa. 

El uso de hechizos indirectos permite a un seguidor de Vilano atacar a cualquier oponente sin importar cuán fuerte sea su resistencia mágica. Los miembros de esta escuela no necesitan preocuparse por usar hechizos de baja magnitud para obtener un mejor Total de Penetración: pueden usar sus hechizos más poderosos para enfrentarse incluso a oponentes aún más poderosos. Esto hace que la Escuela de Vilano sea sorprendentemente efectiva. 

La escuela de Vilano es muy popular como una escuela secundaria, para ser utilizado cuando el ataque principal de un mago no funciona. Es probablemente la escuela de combate mágico más comúnmente usada en toda la Orden, ya que no requiere ni Artes específicas ni Maestría de ningún hechizo. Esto la hace atractiva para los magos que quieren tener alguna capacidad de combate, pero no están dispuestos a dedicar muchas estaciones a mejorar sus Totales de penetración. 

Como todas las escuelas, la Escuela de Vilano tiene sus debilidades. La selección de hechizos indirectos es bastante limitada y muchos de ellos sólo funcionan bajo circunstancias específicas. 

Por ejemplo, [[Avalancha (PeTe40)]] puede hacer mucho daño, pero sólo si uno de los oponentes que se encuentren en una ladera empinada o en la base de un acantilado. 

Por lo general los Magos tratan de compensar estas limitaciones eligiendo algunos hechizos más versátiles que pueden ser usados en cualquier lugar La [[Honda Mágica (ReTe10)]] de Vilano_ es muy popular, vea la sección Nuevos hechizos en las reglas de este capítulo) y asegurándose de que tienen el repertorio de hechizos lo más amplio posible para cubrir varios tipos de situaciones.

Los conjuros indirectos generalmente necesitan ser apuntados, y pueden faltar. Un buen nivel en la habilidad de Puntería reduce pero no elimina ese riesgo. Una consecuencia menos obvia de apuntar es que los hechizos indirectos requieren dos tiradas de estrés (una para lanzar el hechizo y otra para Apuntar) y por lo tanto tienen dos posibilidades de pifiar. 

La mayoría de los hechizos indirectos causan un daño bastante bajo. Son buenos para atrapar o herir a los oponentes, pero pueden llegar a ser poco útiles para terminar una pelea de forma rápida (a menos que el lanzador tenga la suerte de enterrar a su oponente bajo una avalancha). 

El gran riesgo es que el oponente pueda todavía ser capaz de hacer contraataques eficaces. Algunos seguidores de Vilano desarrollan fuertes defensas mágicas, tal vez combinando sus tácticas con ideas de la Escuela de Ramius. Otros usan la invisibilidad cuando luchan, para que sea difícil para el enemigo atacarlos. Una tercera opción es confiar en grogs escudo para proteger al mago por tiempo suficiente que puede neutralizar completamente al enemigo. 

Muchos seguidores de Vilano hacen uso de Artefactos (objetos imbuidos, encantados, etc.) además de hechizos. Una de las principales limitaciones de los Artefactos es que su penetración suele ser generalmente débil, pero las tácticas de esta escuela eluden ese problema.

### Hechizos indirectos 

Los siguientes hechizos de la **Quinta Edición de Ars Magica** pueden ser parcialmente efectivos sin necesidad de penetrar la Resistencia Mágica. En la sección de Magia Flambeau de la [[Casa Flambeau]]se dan algunos hechizos indirectos adicionales: 
- La [[Trampa de la Tejedora (CrAn35)]]: Aunque las telarañas no tocan al mago, lo rodean y lo mantienen quieto en su sitio.
- [[Sendero de Agua Deslizante (CrAq5)]] El mago puede caminar en el aceite mágico, igual que puede caminar a través de un puente creado mágicamente. 
- [[Sepultura de las Aguas (ReAq35)]]: Aunque la ola no puede dañar directamente al magi, puede volcar un barco en el que está montando o golpear un pequeño puente donde este se encuentre. 
- [[Ira de Neptuno (ReAq40)]]: Similar a la _sepultura de las Aguas_, pero la ola es mucho más destructiva 
- [[Levantar a los Muertos (ReCo25)]]: Si el cadáver ataca en combate desarmado, se podrá resistir usando la Resistencia Mágica debido a que todo el cadáver está bajo un efecto mágico activo, pero si el cadáver maneja un arma no mágica, el arma no requiere superar la Resistencia Mágica. 
- [[Títere sin Voluntad (ReCo25)]]: Similar a _Levantar a los Muertos.
- [[Muerto Andante (ReCo35)]]: Similar _Levantar a los Muertos._ 
- [[Lazos de Leña (CrHe15)]]: las ramas no inmovilizan completamente al magi, pero surgen alrededor de él y limita su movimiento|
- [[Red de Sarmientos (ReHe15)]]: este es muy efectivo, la madera no tiene que tocar al magi para inmovilizarlo. El Director de juego puede dar un bonus a la tirada de Fuerza para escapar. 
- [[Tentáculos del Bosque (ReHe20)]] (ReHe 20, ArM5 p.211): Similar a _La Trampa de la Tejedora_ o _Lazos de Leña._
- [[Llama Revoltosa (ReIg5)]]: El movimiento de la llama es mágico, pero la llama en sí no lo es; la llama se detiene como si hubiera tocado suavemente al mago, pero todavía lo quema. 
- [[Salto de la Llamas (ReIg10)]]. Similar a _Llama Revoltosa_.
- [[Horadar la Tierra (PeTe15)]]: no se aplica resistencia mágica porque abre un agujero bajo los pies del magi. 
- [[Mazazo de Gigante (PeTe20)]]  Los fragmentos de metal son disparados como proyectiles y evitan la [[Resistencia Mágica]]
- [[Desplome de la Fortaleza (PeTe25)]]:La Resistencia Mágica no protege contra la caída de piedra a causa de la gravedad. 
- [[Avalancha (PeTe40)]]: Similar a _El Desplome de la Fortaleza.
- [[Tierra Hendida (ReTe30)]]: Resistencia mágica no protege al mago de caer en el abismo, pero lo protege de ser aplastado cuando se cierra. Si el abismo se cierra lentamente en lugar de violentamente (ver la descripción del hechizo), esto no sería resistido, pero el mago probablemente sería capaz de salir durante el proceso. 
- [[Rasgar la Tierra (ReTe35)]]: Similar a _La Tierra Hendida.

