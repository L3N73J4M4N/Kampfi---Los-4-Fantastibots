# Kampfi - 2022
Inspirado por los errores tecnicos y la mala suerte, Kampfi fue creado para maximizar la cantidad de cosas que podrian salir mal al hacer girar un pedazo de acero a la velocidad del ventilador en el radiador de un sedan. El equivalente battlebotiano de lo que sucede cuando le das un ak-47 a un mono.

![Kampfi](/multimedia/KampfiFinal.jpeg)

## Integrantes
- Antonia Gutierrez - FCFM
- Benjamín Gonzalez - FCFM
- Joaquin Camhi - FCFM
- Matías Carvajal - FCFM

## Descripción del proyecto
Battlebot blindado con polialuminio y acero. Como arma tiene instalada una hélice de acero en la parte delantera, la cual gira mediante un motor de 12 volts a una velocidad suficiente para romper el robot contrincante. Tiene un tren de traccion compuesto por 2 ruedas delanteras energetizadas por motores de 9 volts, y una rueda trasera no actuada. 

### Forma del robot
La forma triangular de Kampfi asegura que sea difícil de ser destruído por algun ataque superior (como ejemplo, un bot que ataca mediante un martillo), además le da la capacidad de ser facil de armar y desarmar en caso de que sean necesaria reparaciones, dado a que se compone unicamente de panales cuadrados y triangulares.

### Estrategia utilizada
#### Ofensiva
Kampfi esta equipado de una hélice delantera angulada en 45° con respecto al horizonte. Para atacar se acerca a su victima y al activar el giro de la hélice es capas de destruír cualquier pieza impresa en filamento plastico, separar uniones entre paneles que componen la armadura, doblar corazas metalicas y penetrar pedazos de polialuminio debido al perfil con puntas en las esquinas del arma. Para atacar se debe activar el arma para que empieze a girar y se debe conducir hacia el contrincante en un angulo, idealmente golpeando por el lado izquierdo para aprovechar que la helice gira en sentido antihorario e intentar levantar y desestabilizar al contrintante. 

#### Defensiva
Debido al lento movimiento del robot no es práctico intentar evitar ataques enemigos, la principal defensa es la ofensa: Resistir a los golpes enemigos mediante la coraza de polialuminio y acero, e intentar aterrizar un golpe certero al mecanismo de transmision del arma del contrincante, idealmente desarmandolo. De forma experimental se ha determinado que la armadura es capaz de resistir ataques de armas tipo "spinner", cilindros o discos con perfiles girando a altas velocidades.

#### Uso del arma
La arma se puede activar o desactivar remotamente, se recomienda activar el arma previo al ataque para que gire a una velocidad suficiente como para hacer daño, y desactivar el arma una vez alcanzada una rotación suficiente para evitar gastar la batería principal del robot, dejando que la inercia rotacional del rectangulo de acero le proporcione el daño al enemigo. Si se activa el arma y debido a alguna resistencia (la helice esta atrapada en el cuerpo del contrincante, o en la malla del ring) no gira la helice se debe desactivar inmediatamente el arma, para evitar sobrecalentar los electronicos del robot, junto con el gasto de bateria asociado, el motor usado tiene una gran velocidad de rotacion pero bajo torque: Si no empieza a girar la hélice una vez activada el arma, lo mas probable es que nunca empieze a girar debido a que la resistencia es mayor al torque del motor.

#### Distribución de armadura
Las defensas del robot estan distribuidas de forma relativamente equitativa: El frente esta protegido por el motor de la helice y la helice en sí, los lados tienen polialuminio, y debido a que hay una distancia de un par de centimetros de las laminas de este material y los componentes internos es difícil que se vean dañados por ataques laterales, la parte superior del robot es especialmente resistente a ataques de martillos como se explicó en la seccion "Forma del robot", y la parte trasera es protegida por dos barras paralelas de acero. Debido al peso del robot y a la forma de este, los ataques con objetivo de voltear al enemigo son ineficaces en Kampfi

### Movimiento
El movimiento y la operación del robot se logran mediante una simple aplicación movil. 6 botones, 4 organizados en una cruz y 2 paralelos, abajo de esta, permiten el movimiento y uso del arma, respectivamente.

## Diagrama funcional

![inicio](/multimedia/inicio.png)
![movimiento](/multimedia/movimiento.png)
![ataque](/multimedia/ataque.png)

## Paso a Paso
### Materiales

-Plancha de aluminio compuesto
-Plancha de acero inoxidable cortada en rectangulos
-Puente H de 12V
-Relay de 5 V
-Cables
-Arduino Uno
-Regulador de voltaje 7 V a 5 V
-Motor de radiador
-Pintura en Aerosol plateada y roja
-Filamento plastico
-Bateria 11.1 V 1500 mA
-Bateria 7.4 V 1200 mA
-Tornillos
-Tuercas
-Madera
-Estaño
-2 motores de rueda 5 V
-2 ruedas de goma
-un (1) Kampfi de regulación (ISO b4tT73b0T-K)


### Herramientas

-Taladro
-CNC
-Impresora 3D
-llave inglesa
-Destornillador
-Sierra Circular
-Martillo
-Cautin soldador


### Procedimiento

1) Descargar todos los archivos necesarios: archivos .f3z con el ensamblado y los distintos componentes, el codigo de arduino y el .apk de la aplicación para controlarlo.
2) Reunir los diferentes componentes electronicos y de movimiento.
3) Realizar el circuito de Arduino del robot.
4) Probar que funcione la parte electrica (las conexiones) a través de la aplicacion.
5) Abrir los archivos "piezas_corazas.f3z" y "base.f3z" y cortar las piezas necesarias en una CNC.
6) Recortar de la forma requerida las piezas de madera presentes en "ensamblado.f3z" cuyo fin es unir a través de tornillos las partes de la coraza.
7) Ensamblar cada una de las piezas y componentes electronicos. Para esto, verifique el archivo "ensamblado.f3z" para guiarse.
8) Asegurar que todo este en su lugar, se recomienda una cantidad de 3 tornillos por lado.
9) Comprobar el funcionamiento con el diagrama funcional.

Su Kampfi esta listo para funcionar.

**no nos hacemos responsables de fallas con las ruedas o daños ocasionados por el poco cuidado con el arma**

REQUISITOS:
-LLORAR
-Echarse CAA
-Echarse Proba 
-Echarse/Botar Electro


## Licencia
<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Licencia Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />Esta obra está bajo una <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Licencia Creative Commons Atribución-NoComercial 4.0 Internacional</a>.
