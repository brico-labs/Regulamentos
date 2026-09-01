---
layout: regulamento_es
title: Reglamento de Sumo
---
[<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/64/Flag_of_Galicia.svg/300px-Flag_of_Galicia.svg.png" width="50">](loita_sumo_gl)

### Reglamento de Mini Sumo

  - Revisión 7 (2026): vigente desde OSHWDem 2026

##### Objetivo

Dos robots compiten entre sí simulando los enfrentamientos humanos de sumo. No se permite a los robots la utilización de armas ni girar sobre sí mismos (como forma de ataque), y el único objetivo es empujar al robot oponente para sacarlo del Dohyo.

El reglamento se detalla a continuación.

#### Sección 1: Definición de los enfrentamientos de Sumo Robot

##### Artículo 1.- Definición
Un enfrentamiento se libra entre dos participantes. De acuerdo con las reglas del juego (en adelante "el presente Reglamento") cada participante compite en un Dohyo (ring de sumo) con un robot construido por el/la participante según lo especificado en la Sección 3. Los asaltos comienzan a las órdenes del juez y continúa hasta que un participante gana dos puntos en modalidad clasificatoria o hasta tres puntos en modalidad liga. El juez determina el ganador del enfrentamiento.

#### Sección 2: Requisitos del Dohyo

##### Artículo 2.- Interior del Dohyo
El interior del Dohyo se define como la superficie de juego rodeada de una línea en el borde, que también forma parte de la superficie de juego. Cualquier lugar fuera de esta área se considera el exterior del Dohyo.

##### Artículo 3.- Especificaciones del Dohyo

1. El Dohyo será de forma circular y de unas dimensiones adecuadas para la clase mini-sumo.
2. Las líneas de inicio (shikiri-sen) constan de dos líneas paralelas pintadas en color marrón (o equivalente para la absorción de la luz IR) centradas en el Dohyo, con unas dimensiones y espacio de separación adaptadas a la clase mini-sumo. La distancia de separación entre las líneas se mide a sus bordes exteriores.
3. La línea del borde se marca como un anillo circular blanco en el borde exterior de la superficie de juego. El área del Dohyo se extiende hasta el borde exterior de esta línea circular.

<img src="https://raw.githubusercontent.com/brico-labs/Regulamentos/gh-pages/img/minisumo_dohyo.png" width="400" height="400" />

**Especificaciones del Dohyo**

| Clase | Altura | Diámetro | Material | Grosor* | Longitud* | Separación* | Ancho borde |
| :---- | :----: | :------: | :------: | :-----: | :--------: | :---------: | :---------: |
| Mini  |  19mm  |   77 cm  |    MDF   |   2 cm  |  10 cm     | 10 cm       | 2,5 cm      |

<sup>* Líneas de inicio (shikiri-sen)
Estas medidas pueden variar un 5%</sup>

##### Artículo 4.- Exterior del Dohyo
Debe existir un espacio de **un metro** libre de obstáculos fuera del borde exterior del Dohyo para no confundir a los robots.
Este espacio puede ser de cualquier color, material o forma. Este área, con el Dohyo en el medio, se va a llamar el "área del Dohyo". Cualquier marca o parte de la plataforma del Dohyo fuera de las dimensiones mínimas también serán considerados en el área del Dohyo.

#### Sección 3: Reglamentación para los Robots

##### Artículo 5.- Especificaciones

1. La placa controladora del robot, en caso de haberla, debe estar basada en tecnologías abiertas. También son válidas las plataformas o kits de robótica basados en tecnologías abiertas.

2. El robot debe caber en un cubo de las dimensiones establecidas para cada clase. Un robot puede expandirse en tamaño una vez se da comienzo al enfrentamiento, pero no puede separarse físicamente en pedazos y debe seguir siendo un solo robot centralizado. Los robots que no cumplan esta restricción perderán el combate. Los tornillos, tuercas y otras partes del robot con una masa total de menos de 5 gramos que caigan del cuerpo de un robot no causarán la pérdida del combate.

3. La masa total de un robot al comienzo de un combate debe estar por debajo de la especificada para cada clase.

Clase | Altura | Anchura | Longitud | Masa
:--- | :---: | :---: | :---: | :---: |
**Mini** | ilimitada | 10 cm | 10 cm | 500 gr

4. Clases autónomas: Los robots de la clase Mini (500gr) deben ser autónomos. La activación y desactivación de ambos robots en la competición será mediante IR usando el protocolo RC05. El juez tendrá un mando y será el encargado de activar y desactivar los robots para iniciar y acabar los asaltos.
5. El funcionamiento autónomo de los robots debe comenzar sin retraso tras el inicio con el mando por parte del juez.
6. El robot debe tener un nombre o número con fines de registro y seguimiento.
7. Se permite el uso de elementos afilados en el cuerpo del robot siempre y cuando no tengan la capacidad de dañar al robot contrario, el dohyo ni sus inmediaciones. Es decir, si un robot es muy rápido y además posee una cuchilla afilada para usarse como cuña, debe poder detenerse de forma rápida, fiable y segura.


##### Artículo 6.- Restricciones

1. Dispositivos para crear interferencias (jamming), como LED’s IR con la intención de saturar los sensores IR del oponente.

2. Partes que puedan dañar o romper el Dohyo. Usar partes que puedan dañar intencionadamente al robot oponente o a su operador. Los empujones y golpes derivados de estos no están considerados con intención de causar daño.

3. Dispositivos que puedan almacenar fluidos, polvo, gas u otras sustancias para lanzar al oponente.

4. Dispositivos de pirotecnia.

5. Dispositivos que lancen objetos al oponente.

6. La utilización de sustancias pegajosas para incrementar la tracción.

7. El uso de dispositivos para incrementar el “efecto suelo”, como bombas de vacío o imanes.

8. El uso de cualquier tipo de fuente de energía para el funcionamiento del robot que no sea la proporcionada por pilas o baterías eléctricas.

#### Sección 4: Desarrollo de los combates

##### Artículo 7.- Desarrollo de los combates
1. Cada combate consta de **tres asaltos**, con un tiempo total de tres minutos, a menos que sea extendido por los jueces.

2. El primer participante que gane dos asaltos en modalidad clasificatoria o tres en modalidad liga, dentro del tiempo límite, será el ganador del combate. Un participante recibe un punto cuando gana un asalto. Si se alcanza el límite de tiempo antes de que un participante pueda obtener los puntos necesarios y uno de los participantes ha recibido un punto, el participante con ese punto se considera el ganador del combate.

3. En cada uno de los asaltos de un mismo combate se irán alternando las orientaciones de los robots en la salida, en el siguiente orden: de frente, de lado, de espaldas.

4. Cuando haya un empate entre dos participantes y en función de la modalidad de competición, podría establecerse un nuevo asalto (asalto extendido), en cuyo caso se reiniciará el orden de salida, durante el cual el participante que consiga el punto se convertirá en el ganador del combate.

#### Sección 5: Comienzo, parada, reanudación y finalización de un asalto

##### Artículo 8.- Comienzo
Tras las instrucciones de los jueces, los dos participantes se acercarán al Dohyo y pondrán cada robot en su mitad del Dohyo, detrás de sus respectivas líneas de inicio, sin desplazarlo lateralmente. El robot o cualquier parte de este no puede ser colocado más allá de la línea de inicio hacia su oponente. No se requiere poner el robot pegado a la línea de inicio. Cuando el juez anuncie el comienzo del asalto, activará los robots de forma remota que **empezarán a operar de manera inmediata**. 

##### Artículo 9.- Parada y reanudación
Los asaltos se paran y reanudan por indicación de los jueces.

##### Artículo 10.- Finalización
Los asaltos finalizan por indicación de los jueces. Los participantes podrán recuperar sus robots en el área del Dohyo.

#### Sección 6: Tiempo combate

##### Artículo 11.- Tiempo de combate
Un combate debe llevarse a cabo en un total de 3 minutos, que comenzarán y finalizarán por orden de los jueces.

##### Artículo 12.- Asalto extra
Si, por decisión de los jueces, se requiera un asalto extra, ésta tendrá una duración máxima de 3 minutos.

##### Artículo 13.- Exclusiones de tiempo
Lo siguiente no está incluido dentro del tiempo de partida:

1. El tiempo transcurrido desde que los jueces anuncian el punto del asalto hasta el comienzo del siguiente asalto. El tiempo establecido entre asaltos es de 30 segundos.

2. El tiempo transcurrido desde que los jueces anuncian la parada del asalto hasta su reanudación.

#### Sección 7: Puntuación

##### Artículo 14.- Puntuación
Se considera que un robot ha ganado un asalto cuando:

1. Un participante fuerza al robot contrincante a tocar el área fuera del Dohyo, incluyendo el borde lateral del mismo.
2. El robot contrincante, por sí mismo, toca el área fuera del Dohyo, incluyendo el borde lateral del mismo.
3. El robot contrincante no se mueva en los 5 segundos posteriores al inicio del combate.

El asalto se considerará empate en las siguientes circunstancias:

1. Los robots están enredados u orbitando entre sí sin ningún progreso aparente durante 5 segundos. Si no está clara la intención de los robots, el juez puede prorrogar dicho plazo hasta un máximo de 30 segundos. 

2. Ambos robots se mueven sin intención de luchar, o se paran al mismo tiempo y permanecen detenidos durante 5 segundos sin tocarse. Sin embargo, si un robot detiene su movimiento en primer lugar, transcurridos cinco segundos será declarado como que no tiene intención de luchar. En este caso, el oponente recibirá un punto, incluso si éste último también se detiene. Si los dos robots se mueven y no está claro si se están progresando, el juez puede prorrogar el plazo hasta un máximo de 30 segundos.

3. Los dos robots tocan el exterior del Dohyo más o menos al mismo tiempo, y no se puede determinar quién tocó en primer lugar.

4. Se ha vencido el tiempo máximo del asalto y ninguno de los dos robots ha salido del Dohyo.

Un asalto se considera nulo cuando en los 5 segundos posteriores al inicio:

	1. ninguno de los dos robots comienza a moverse.
	2. los robots se salen del dohyo sin tocarse.
	3. uno de los robots se sale del dohyo sin tocar al oponente y el otro no comience a moverse.
	
Si el asalto resulta nulo, se dará un aviso a los competidores y se repetirá una sola vez. Si vuelve a ser nulo, se considerará empate por inactividad.

Cuando se requiera la decisión de los jueces para determinar el ganador de un asalto se tendrán en cuenta las siguientes consideraciones:
    
    1. méritos técnicos en el movimiento y funcionamiento de un robot.
    2. las penalizaciones durante el asalto.
    3. actitud del participante durante el combate.


#### Sección 8: Faltas
##### Artículo 15.- Faltas
Los participantes que realicen cualquiera de los hechos descritos en los Artículos 6, 16 o 17, serán amonestados por saltarse este reglamento.

##### Artículo 16.- Insultos
Un participante que profiere insultos al oponente o a los jueces, o pone voces en el robot que pronuncie palabras insultantes, o que aparezcan escritas en el cuerpo del robot, o que realice gestos insultantes, se considera una falta por incumplimiento de este reglamento.

##### Artículo 17.- Faltas leves
Se considera una falta leve cuando un participante:

1. Entra en el Dohyo durante el asalto, excepto cuando el participante lo hace para recoger el robot fuera del Dohyo una vez el juez anunció la asignación del punto o para el asalto. Entrar en el Dohyo significa:

    1. una parte del cuerpo del participante está en el Dohyo.
    2. un participante utiliza algún mecanismo para tocar el Dohyo.
    
2. Realiza las siguientes acciones:

    1. Exige parar el asalto sin razones aparentes.
    2. Tarda más de 30 segundos para comenzar el asalto, a menos que el juez incremente el tiempo.
    3. Hacer alusiones a la imparcialidad del asalto, el combate o el torneo.

#### Sección 9: Penalizaciones

##### Artículo 18.- Penalizaciones
Los jugadores que incumplan los artículos 6 y 16 del presente reglamento perderán el combate y serán descalificados del torneo. El juez otorga dos puntos al oponente.

##### Artículo 19.- Acumulación de faltas
Las faltas leves descritas en el artículo 17 son acumulativas a lo largo de todo el asalto. Dos
faltas leves conllevan otorgar un punto al oponente.

#### Sección 10: Jueces

##### Artículo 20.- Los jueces
En la sala habrá una persona identificada como "juez principal" y será la encargada de comunicar cualquier decisión final con respecto al desarrollo de la competición y la interpretación de las normas.

Otras personas pueden estar identificadas como "juez asistente" y ayudarán al juez principal en las tareas que tengan delegadas.

El participante siempre se debe dirigir al juez principal para cualquier reclamación o aclaración de las normas. Entonces, si el juez principal lo estima oportuno, puede redirigir al participante al juez asistente.

Las decisiones finales siempre las tomará el juez principal.

##### Artículo 21.- Declaración de objeciones
Un participante puede presentar objeciones a la organización antes de que termine el asalto, si hay alguna duda en el ejercicio de este reglamento. Si no hay miembros de la organización presentes, la objeción se puede presentar al juez antes de la finalización del asalto.

#### Sección 11: Miscelánea

##### Artículo 22.- Flexibilidad del reglamento
Siempre y cuando se respeten el concepto y fundamentos de las reglas, estas deberán ser lo suficientemente flexibles para abarcar cambios en el número de jugadores y en el contenido de las partidas.

##### Recursos de interés
[Listado de robots minisumo *Open Source*](https://open-robosports.github.io/kits/minisumo)

---

Esta obra está bajo una <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">licencia de Creative Commons Reconocimiento 4.0 Internacional.</a>
<p align="center">
<img src="https://i.creativecommons.org/l/by/4.0/88x31.png">
</p>

Reglamento derivado de [Unified Sumo Robot Rules](http://robogames.net/rules/all-sumo.php).
