# control-de-procesos-R
### practicas de curso julio-agosto 2019
# Tecnologico de estudios superiores de Huixquilucan

### Ingenieria Mecatronica 

### Asignatura. Control de procesos 

### Asesor. Dr Enrique Garcia Trinidad 

### Alumno. Tovar Farfan Raul
### Control de procesos 
# practica 1
# Introduccion al LabVIEW 

LabVIEW (Laboratory Virtual Instrument Engineering Workbench) de National Instruments es
un ambiente de programación basado en programación gráfica y no en texto como lo son
lenguajes de programación tradicionales como C, C++ o java. Labview es un desarrollo de
programación interactivo y un sistema de ejecución diseñado para personas como científicos o
ingenieros que sin ser informáticos necesitan programar como parte de su trabajo. El ambiente
de desarrollo de Labview trabaja sobre computadoras Windows, Mac OS X, o Linux, además se
pueden crear programas que corren en una variedad de plataformas embebidas como FPGAs
(Field Programmable Gate Arrays), DSPs (Digital Signal Processors) y microprocesadores.
Usando el poderoso lenguaje de programación gráfico, Labview puede incrementar la
productividad, programas que toman semanas o meses en ser escritos en lenguajes de
programación convencionales pueden ser completados en horas usando Labview, ya que este
ha sido diseñado específicamente para realizar mediciones, analizar datos, y presentar
resultados al usuario en interfaces gráficas fáciles de programar, es ideal para simulaciones,
presentación de ideas, programación general e incluso para la enseñanza de conceptos básicos
de programación.
La computadora, hardware plug-in y Labview es lo que se necesita para realizar un instrumento
virtual completo, ofreciendo así una alternativa de mayor flexibilidad a los instrumentos
estándares de laboratorio, pues al estar basado en software será cada usuario y no el fabricante
del instrumento el que define la funcionalidad de este y si se necesita cambiar algo simplemente
se modifica el programa.


# Contenido
### Primer programa en labVIEW
Para poder iniciar con la programacion en LabVIEW y comenzar con nuesro primer programa es necesario ir explicando paso a paso los procedimientos a seguir como se muestra a continuacion.


1.- Ejecutando por primera vez LabView aparecerá un recuadro "Welcome to LabView el cual cancelaremos presionando (x) en la parte superior derecha, Para posteriormente abrir un nuevo VI como se muestra a continuación .
<img src="praktik-1-2.png"//>

2.-una vez abierto el nuevo VI presionamos Ctrl+T para poder visualizar la parte virtual y la de diagrama de bloques, las cuales utilizaremos para construir mostró programa virtual de esta primer práctica
<img src="praktik-1-3.png"/>

una vez aqui podemos Visualizar las herramientas que nos ofrece el programa en cada plano de las ventanas y de esta manera empezar a trabajar en el primer programa visualde esta curso.
<img src="praktik-1-4.png"/>

3.-Entrandoen materia, Lo que prosigue es arrastrar 2 ventanas de control u un indicador, para de esta forma poder variar los números que se van a restar y el indicador en sonde se mostrara el resultado de la operación.
De esta manera tenemos como resultado un restador el cual al cambiarle la operación puede ser una suma, multiplicación, división o cualquier otro operador.
<img src="praktik-1-5.png"/>.



# practica 2
### insteumentoa virtuales

# Introduccion
Los ficheros generados con Labview se llaman Instrumentos Virtuales (VIs). Cada VI se compone de dos partes principales: el panel frontal (front panel) o interfaz con el usuario donde se colocan controles como botones, perillas, leds, indicadores, etc.; para que el usuario observe cierta información y ejecute diversas acciones y el diagrama de bloques (block diagram) que es el código fuente del VI donde se programa el funcionamiento de la aplicación. En la Figura 1 se muestra el panel frontal y el diagrama de bloques de un programa en Labview.
<img src="praktik-2-1.png"/>.

# Desarrollo
para  Empezar abrimos un nuevo archivo VI. Como en la práctica anterior, pero en esta ocasión   construiremos un programa el cual demostrará el funcionamiento de algunos instrumentos virtuales que podemos implementar en una simulación.

1.-dando click derecho sobre nuesros espacios de trabajp nos vamos a numeric, ai podemos observar algunas hwrraminetas qie se utilisaran y conectaremos entre si para poder ver si buen funcionamiento basico.
<img src="praktik-2-2.jpg"/>.
                         
2-arrastramos los elementos que vamos a utilosar, las cuales son dos perillas que en esta ocaccipn sumaremos y les ponemps un display a cada una para mostrar el valor que tienen en numero y la suma la realizamos como en la practica amterior, tomemos en cuenta hacer unas modificaciones como agrandar la perilla y modificar la escala como en la imagen.
<img src="https://github.com/R-Tovar/control-de-procesos-R/blob/master/praktik-2-4.jpg"/>

3.-despues agragamos un siclo wile Para que la operacion se ejecute constante mente mientras se mantenga, tamboen un temporisador par que se este ejecutando cada cierto tiempo y una modificacion mas, dando click derecho sobre cialquoer perilla la remplasaremos con otro dispocitivo que tenga la misma funcion.
<img src="https://github.com/R-Tovar/control-de-procesos-R/blob/master/praktik-2-3.jpg"/>

#conclucion
en esta practica Pudimos observar algunos instrumentos virtuales que se pueden implementar parara el mejor uso de un programa virtual, de esta manera y conociendo estos detalles se podrán utilizar de mejor manera en programas más complejos. 



# practica 3
#### programa calculo del IMC

# intepduccion
En esta practica se pretende realizar un programa en el cual se pueda calcular el IMC,pero a qie se refiere el IMC. Una medida de la obesidad se determina mediante el índice de masa corporal (IMC), que se calcula dividiendo los kilogramos de peso por el cuadrado de la estatura en metros (IMC = peso [kg]/ estatura [m2]). Según el Instituto Nacional del Corazón, los Pulmones y la Sangre de los Estados Unidos (NHLBI), el sobrepeso se define como un IMC de más de 25. Se considera que una persona es obesa si su IMC es superior a 30. Usted puede determinar su IMC con la calculadora que se encuentra a continuación. Con la cifra del IMC puede averiguar su composición corporal en la tabla que aparece en el indocadoe de mas en el programa.

# Desarrollo
1.- para empesar, pensamos en los insteumentoa virtuales que vamos a utilizar ya que vamos a agregar 2 pantallotas de control para ingresar la alturo en (m) y las decimales en (cm),otra mas para el peso en Kg , recordando que la mayoria de los programas que crearemos tienen que estar dentro de un siclo wile y claro nesecitamos un indicador para observar el resultado del (imc).
<img src="https://github.com/R-Tovar/control-de-procesos-R/blob/master/praktik-3-2.jpg"/>

2.-el calculo de la masa probiene de una simple formula la cual ocuparemos para unir nuestros datos y sacar el resultado, tambien recordemos poner un boton de stop para parar el programa en el ciclo wuile,de esta forma paramos el programa de una mejor manera y casi esta listo nuestro programa.
<img src="praktik-3-1.jpg"/>

3.-ahora remplasamos el indicador por algo mas grafico de esta forma podremos ver una pequeña grafica la cual sera mas didactico el poder observar el imc, y en la parte de decoraciones podremos poner unos rangos para observar los limites de imc.
<img src="praktik-3-3.jpg"/>.

# conclucion
en esta practica nos podemos dar cuenta que la implementacion de un programa virtual ya puede servor pra un usuario con una nesecidad y de esta manera crear programas que sean de utilidad para los demas. sin contar que es el princip para desarrollar sistemas que controlen erramoentas fisicas y se puedad monitoriar desde una computadora y de la misma manera controlarlos

