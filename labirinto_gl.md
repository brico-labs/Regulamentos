---
layout: regulamento_gl
title: Regulamento de Labirinto
---
[<img src="https://upload.wikimedia.org/wikipedia/commons/3/32/Flag_of_Spain_%28Civil%29.svg" width="50">](labirinto_es)

# Regulamento de Labirinto

  - Revisión 1 (2015): vixente dende OSHWDem 2015

### Obxectivo

Un robot autónomo debe resolver un labirinto e completar o seu percorrido dende a cela de
partida “saída” até a cela de chegada “meta” no menor tempo posible.

Disporá de 5 minutos para recoñecer o labirinto e de 3 intentos para completalo no menor
tempo que poida. Gañará a competición o robot que complete o percorrido no menor tempo.

### O labirinto

![Imaxe do labirinto](img/maze_finish_line.jpg)

1. O labirinto está formado por unha área de 13 por 13 celas, que veñen sendo estancias
de forma cadrada e adxacentes por cada un dos catro lados do perímetro da propia
cela.

2. Cada cela ten un tamaño de 150 por 150 milímetros, e sobre cada un dos lados da cela
pode existir, ou non, unha parede que non deixará pasar o robot por ese lateral.

3. As paredes do labirinto teñen unha altura de 100mm, un grosor de 20mm e van
situadas sobre o medio e medio das celas que separa.

4. Hai que ter en conta que unha parede invade o espazo das dúas celas e reducen a área
de cada cela achicándoa 10mm polo lado da parede e, polo tanto, deixando os
corredores polos que ten que pasar o robot en 130mm de ancho.

5. Asúmese un 5% de tolerancia en tódalas dimensións dadas.

6. Os lados das celas que delimitan o exterior do labirinto estarán todas pechadas por
paredes, evitando que o robot saia do labirinto.

7. Os lados das paredes son de color branca, a parte superior das paredes é de cor
laranxa e o chan é de cor negra. As partes do labirinto son de madeira, rematada con
pintura mate.

8. Debe asumirse que as tonalidades e remates da pintura poden variar ó longo do
percorrido, existir zonas de sombras pola iluminación ambiental e variacións na
cantidade de fricción que ofrece o chan. As columnas que soportan las paredes son de
aluminio, en cor natural e quedan á vista do robot.

9. No chan pode existir a unión de taboleiros de madeira que poderían provocar un
pequeno desnivel ou focha que se tratará de minimizar para evitar que os robots
poidan ser afectados.

10. O punto de partida ou “saída” está situado en unha das catro esquinas do labirinto.

11. O punto de chegada ou “meta” está situado no centro do labirinto.
 
12. A meta está composta dunha área de 3 por 3 celas con paredes só no seu perímetro,
agás na entrada que será tan só dunha parede nunha cela e que se denomina "porta de
meta".

13. A zona de meta terá unha marca no chan que indica ao robot a zona de chegada. Dita
marca será unha liña branca de 2cm de grosor.

14. Para a xeración do labirinto vaise utilizar o seguinte repositorio:
[https://github.com/brico-labs/OshwdemMazes](https://github.com/brico-labs/OshwdemMazes). O programa executarase xusto antes
do comenzo da proba e servirá para configurar as paredes do labirinto.

### Os robots

1. A placa controladora do robot, en caso de habela, debe estar baseada en tecnoloxías
abertas. Tamén son válidas as plataformas ou kits de robótica baseados en
tecnoloxías abertas.

2. O funcionamento do robot debe ser completamente autónomo. Pódese utilizar
calquera método de control, sempre e cando estea integrado enteiramente no robot e
non reciba sinais oi indicacións externas (de calquera tipo).

3. Non existe limitación en canto a masa, dimensións ou xeometría do robot, coa única
excepción da altura, que non debe superar, en ningún caso, os 95mm. O robot debe ser
unha única unidade indivisíbel.

4. O robot non poderá saltar por riba, sobrevoar, escalar, cortar, rascar, queimar, danar ou
destruír as paredes do labirinto.

5. O robot deben ter un nome ou número con fins de rexistro e seguimento. O robot debe
amosar este nome ou número para permitir a sua identificación á organización e
xuíces e os espectadores.

6. Os robots deben funcionar unicamente coa enerxía proporcionada por pilas ou baterías
eléctricas integradas no propio robot.

### Desenvolvemento da competición

1. A orden de participación virá dado pola orden de chegada ou anotación na lista de
inscritos á competición. Se avisará con antelación o desenvolvemento do mesmo a
orden de participación de cada robot.

2. Momentos antes do comenzo da competición se amosará o percorrido do labirinto.
Dende ese mesmo instante os robots deben estar na mesa dos xuíces e non se permite
ningún cambio de peza, carga de programa ou comunicación remota co robot.

3. Cada participante poderá inscribir e participar con até tres robots, pero soamente
poderá ter opción a un dos premios se un ou varios dos seus robots resultan
gañadores.

4. Os robots poderán acceder ou ser retirados do labirinto unicamente por orde dos
xuíces.

5. Cada robot disporá de 5 minutos para recoñecer o labirinto. O tempo comeza a contar
no momento que o xuíz dá a orde e remata ao finalizar o tempo disposto ou en
calquera momento por decisión do participante.

6. Soamente durante o tempo de recoñecemento, o operador do robot poderá reiniciar o
percorrido ou recoñecemento tantas veces como queira, ademais de levar a cabo as
seguintes operacións:

    1. Axuste electrónico, mediante controis integrados no robot, da configuración que non aporte información relativa ao percorrido do labirinto.
    2. Axuste manual dos sensores ou dos elementos motrices do robot.
    3. Substitución das baterías.
    4. Facer reparacións de pezas danadas ou substituílas por outras que teñen similares características que a peza danada.
    
7. Dentro do tempo de recoñecemento do labirinto, o robot que consiga entrar á zona de
meta poderá seguir operativo ou continuar explorando o labirinto até que finalice o
tempo establecido.

8. Unha vez transcorrido o tempo de recoñecemento, o robot terá 3 intentos para
completar o percorrido do labirinto dende a zona de saída até a zona de meta no
menor tempo posible. O xuíz indicará cando comeza e finaliza cada intento.

9. O cronómetro se porá en marcha cando o robot toca a liña divisoria da cela de saída.

10. O cronómetro parará cando o robot supera completamente a porta de meta.

11. O operador do robot poderá realizar os axustes, entre cada intento, de acordo as
operacións detalladas no punto 6.i e 6.ii desta mesma sección.

12. En caso de colisión coas paredes do labirinto ou detención do robot por máis de 10
segundos sen que este teña intención de movemento ou de progresión no percorrido,
se perderá o intento en curso.

13. O tempo a ter en conta para a competición cos outros robots será o menor dos tempos
en completar axeitadamente o percorrido do labirinto.    

### Gañadores da competición

O robot que haxa completado o labirinto no menor tempo será o gañador da competición. O
segundo e terceiro clasificado será o que teña o segundo e terceiro menor tempo
respectivamente.

En caso de empate ou falta de puntuación para algún dos clasificados, os xuíces
determinarán os gañadores en función das características técnicas do robot, comportamento
no labirinto ou outros factores.

Cada participante poderá levar só un premio dos tres establecidos.

### Xuíces

Na sala haberá en todo momento unha persoa identificada como “xuíz principal” e será a
encargada de comunicar calquera decisión final con respecto ao desenvolvemento da
competición e interpretación das normas.

Outras persoas poden estar identificadas como “xuíz asistente” e axudarán ao xuíz principal
nas tarefas que teña delegadas.

O participante sempre se debe dirixir ao xuíz principal para calquera reclamación ou
aclaración das normas. Entón, se o xuíz principal o estima oportuno, pode redirixir ao
participante a un xuíz asistente.

As decisións finais sempre as tomará o xuíz principal.

### Recursos de interese 

  * [Repositorio para a xeración de labirintos](https://github.com/bricolabs/OshwdemMazes)
  * [Solving a Maze](https://www.cs.bu.edu/teaching/alg/maze/)
  * [Think Labyrinth!](http://www.astrolog.org/labyrnth.htm)


----

Esta obra está baixo unha [licenza de Creative Commons Recoñecemento 4.0 Internacional (CC-BY)](http://creativecommons.org/licenses/by/4.0/).
