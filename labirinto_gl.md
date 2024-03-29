---
layout: regulamento_gl
title: Regulamento de Labirinto
---
[<img src="https://upload.wikimedia.org/wikipedia/commons/3/32/Flag_of_Spain_%28Civil%29.svg" width="50">](labirinto_es)

### Regulamento de Labirinto

  - Revisión 4 (2019): vixente dende OSHWDem 2019

##### Obxectivo

Un robot autónomo debe resolver un labirinto e completar o seu percorrido dende a cela de
partida “saída” até a cela de chegada “meta” no menor tempo posible.

Disporá de 7 minutos para completalo no menor tempo que poida. Gañará a competición o robot que complete o percorrido no menor tempo.

##### O labirinto

![Imaxe do labirinto](img/maze_finish_line.jpg)

1. O labirinto está formado por unha área de 16 por 16 celas, que veñen sendo estancias
de forma cadrada e adxacentes por cada un dos catro lados do perímetro da propia
cela.

2. Cada cela ten un tamaño de 180 por 180 milímetros, e sobre cada un dos lados da cela
pode existir, ou non, unha parede que non deixará pasar o robot por ese lateral.

3. As paredes do labirinto teñen unha altura de 50mm, un grosor de 12mm e van
situadas sobre o medio e medio das celas que separa.

4. Hai que ter en conta que unha parede invade o espazo das dúas celas e reducen a área
de cada cela achicándoa 6mm polo lado da parede e, polo tanto, deixando os
corredores polos que ten que pasar o robot en 168mm de ancho.

5. Asúmese un 5% de tolerancia en tódalas dimensións dadas.

6. Os lados das celas que delimitan o exterior do labirinto estarán todas pechadas por
paredes, evitando que o robot saia do labirinto.

7. Os lados das paredes son de color branca, a parte superior das paredes é de cor
laranxa e o chan é de cor negra. As partes do labirinto son de madeira, rematada con
pintura mate.

8. Debe asumirse que as tonalidades e remates da pintura poden variar ó longo do
percorrido, existir zonas de sombras pola iluminación ambiental e variacións na
cantidade de fricción que ofrece o chan. As columnas que soportan las paredes son de
madeira, e quedan á vista do robot.

9. No chan pode existir a unión de taboleiros de madeira que poderían provocar un
pequeno desnivel ou focha que se tratará de minimizar para evitar que os robots
poidan ser afectados.

10. O punto de partida ou “saída” está situado en unha das catro esquinas do labirinto.
**A saída está orientada de maneira que cando a parede libre se atopa ó "norte", as
paredes da contorna do laberinto se atopan ó "oeste" e "sur". É dicir, o robot sae no
sentido horario.**

11. O punto de chegada ou “meta” está situado no centro do labirinto.

12. A meta está composta dunha área de 2 por 2 celas con paredes só no seu perímetro,
agás na entrada que será tan só dunha parede nunha cela e que se denomina "porta de
meta".

13. A zona de meta terá unha marca no chan que indica ao robot a zona de chegada. Dita
marca será unha liña branca de 2cm de grosor.

14. Para a xeración do labirinto vaise utilizar o seguinte repositorio:
[https://github.com/brico-labs/OshwdemMazes](https://github.com/brico-labs/OshwdemMazes). O programa executarase xusto antes
do comenzo da proba e servirá para configurar as paredes do labirinto.

##### Os robots

1. A placa controladora do robot, en caso de habela, debe estar baseada en tecnoloxías
abertas. Tamén son válidas as plataformas ou kits de robótica baseados en
tecnoloxías abertas.

2. O funcionamento do robot debe ser completamente autónomo. Pódese utilizar
calquera método de control, sempre e cando estea integrado enteiramente no robot e
non reciba sinais oi indicacións externas (de calquera tipo).

3. Recoméndase que o robot non supere os 16cm de ancho por 16cm de largo. Se cambian de xeometría no deberían superar estas dimensións. Non existe limitación na altura do robot. O robot debe ser unha única unidade indivisíbel.

4. O robot non poderá saltar por riba, sobrevoar, escalar, cortar, rascar, queimar, danar ou
destruír as paredes do labirinto.

5. O robot deben ter un nome ou número con fins de rexistro e seguimento. O robot debe
amosar este nome ou número para permitir a sua identificación á organización e
xuíces e os espectadores.

6. Os robots deben funcionar unicamente coa enerxía proporcionada por pilas ou baterías
eléctricas integradas no propio robot.

##### Desenvolvemento da competición

1. A orden de participación será decidido pola organización. Se avisará con antelación o desenvolvemento do mesmo a orden de participación de cada robot.

2. Momentos antes do comenzo da competición se amosará o percorrido do labirinto. Dende ese mesmo instante os robots deben estar na mesa dos xuíces e non se permite ningún cambio de peza, carga de programa ou comunicación remota co robot.

3. Os robots poderán acceder ou ser retirados do labirinto unicamente por orde dos xuíces.

4. Cada robot disporá únicamente de 7 minutos para recoñecer, cartografar e resolver o labirinto. O tempo comeza a contar no momento que o xuíz dá a orde e remata ao finalizar o tempo disposto ou en calquera momento por decisión do participante.

5. Durante os 7 minutos de tempo que dispón cada robot, se poderá iniciar o percorrido tantas veces como queira o constructor. O xuiz disporá dun segundo cronómetro co que tomará os tempos parciais de cada un dos intentos de resolución do labirinto.

6. O cronómetro de tempos parciais se porá en marcha cando o robot toca a liña divisoria da cela de saída.

7. O cronómetro de tempos parciais parará cando o robot supera completamente a porta de meta.

8. O operador do robot poderá realizar os axustes, dentro do seu tempo de 7 minutos, de acordo as seguintes operacións: 

    1. Axuste electrónico, mediante controis integrados no robot, da configuración que non aporte información relativa ao percorrido do labirinto.
    2. Axuste manual dos sensores ou dos elementos motrices do robot.
    3. Substitución das baterías.
    4. Facer reparacións de pezas danadas ou substituílas por outras que teñen similares características que a peza danada.

9. En caso de colisión coas paredes do labirinto ou detención do robot por máis de 10 segundos sen que este teña intención de movemento ou de progresión no percorrido, se perderá o intento en curso.

10. O tempo a ter en conta para a competición cos outros robots será o menor dos tempos en completar axeitadamente o percorrido do labirinto.

##### Gañadores da competición

O robot que haxa completado o labirinto no menor tempo será o gañador da competición. O segundo e terceiro clasificado será o que teña o segundo e terceiro menor tempo respectivamente.

En caso de empate ou falta de puntuación para algún dos clasificados, os xuíces
determinarán os gañadores en función das características técnicas do robot, comportamento no labirinto ou outros factores.

Cada participante poderá levar só un premio dos tres establecidos.

##### Xuíces

Na sala haberá en todo momento unha persoa identificada como “xuíz principal” e será a encargada de comunicar calquera decisión final con respecto ao desenvolvemento da competición e interpretación das normas.

Outras persoas poden estar identificadas como “xuíz asistente” e axudarán ao xuíz principal nas tarefas que teña delegadas.

O participante sempre se debe dirixir ao xuíz principal para calquera reclamación ou aclaración das normas. Entón, se o xuíz principal o estima oportuno, pode redirixir ao participante a un xuíz asistente.

As decisións finais sempre as tomará o xuíz principal.

##### Recursos de interese

  * [Repositorio para a xeración de labirintos](https://github.com/brico-labs/OshwdemMazes)
  * [Think Labyrinth!](http://www.astrolog.org/labyrnth.htm)


----

Esta obra está baixo unha [licenza de Creative Commons Recoñecemento 4.0 Internacional (CC-BY)](http://creativecommons.org/licenses/by/4.0/).
