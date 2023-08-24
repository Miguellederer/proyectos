Conocimiento de Seguridad y gestión de Calidad Serie 1
1.	Que es un fallo? 

R// Es la manifestación o aparición de defectos durante la ejecución de una aplicación lo que ocasiona un fallo.  
Ejemplo un mensaje de alerta por algún conflicto durante la aplicación.

2.	Cuales son las diferencias ejecuciones de caja negra y caja blanca:

R//Las ejecuciones de caja negra son pruebas funcionales los cuales se utilizan en un grado de conocimiento de dichos procesos y ahora bien la caja blanca es un modelo para poder monitorear y analizar el diseño, código fuente y la estructura con el objetivo mejorar la eficiencia del sistema.

3.	Describe las etapas del ciclo de vida de las pruebas de software (Proporcione un
ejemplo las cuales describan algunas de las etapas del ciclo de prueba).
*Planificación: se realiza la planificación, costo, beneficios del entorno para desarrollar el programa.
*Diseño: Se realiza la interfaz grafica la cual los usuarios podrán interactuar.
*Programación: es implementar o transferir la fase de diseño a lenguaje de programación y realizar los respectivos algoritmos.
*Explotación: Realizar pruebas o llegar al programa a un estrés donde se puedan encontrar errores y poder depurarlas.
*documentación: Se realiza un Manual de usuario donde se explica todas las funcionalidades del programa.
*Mantenimiento: se realiza pruebas para encontrar fallos y poder parchearlos.

4.	En términos de calidad de software, ¿Qué es el plan de testeo?

R// Es un modelo donde se realiza pruebas a los programas para encontrar fallos y poder depurarlos por medio de parches y con esto los desarrolladores pueden volver mas eficiente el programa.

5.	¿Qué elementos tomarías para crear una estrategia de pruebas?

*Realizar Pruebas: se realiza las debidas pruebas para encontrar fallos en la estructura o código fuente.
*Realizar pruebas previstas: realizar las debidas pruebas en funciones donde podemos anticipar cualquier fallo a futuro.
*Mantenimiento: Siempre realizar pruebas de testeo para ir depurando todos los fallos encontrados y así volver más eficiente a todo el código.



Casos de usos: Serie 2

1.	Encuentras un fallo en un proyecto de producción, ¿Cómo aseguras que el fallo sea
resuelto? 	
R// Se le notifica al Desarrollador para realizar la corrección y luego se le solicitaría la retroalimentación del código para volver a realizar la prueba y descartar el fallo.

2.	El servidor de correo del proveedor está fallando, ¿Qué tipos de pruebas
efectuarías para asegurar que el fallo sea del lado de proveedor?
R// 1. comprobaría con múltiples dispositivos para verificar si todos los dispositivos conectados a la intranet tengan comunicación.  2. Verificar el estado del Servidor de mi proveedor si esta presentando fallos. 3.Descartar alguna mala conexión a internet. 4. Realizar pruebas de ping.

3.	Los clientes finales no tienen la idea de cómo validar el proyecto, ¿Qué harías como
tester para obtener la aceptación del cliente final?

R// Le mostraría o realizaría las pruebas en presencia del cliente para mostrar las funcionalidades del proyecto y que estas mismas cumplan con lo solicitado por el cliente y además mostrarle un manual del usuario para que el cliente tenga una guía de paso a paso.

4.	El proyecto funciona de acuerdo a la lógica del cliente, Sin embargo al tener un gran
número de usuarios se observa una lentitud en la aplicación ¿Que tipos de pruebas
efectuaría para visualizar este problema?

R// enviaría solicitudes de diferentes dispositivos para descartar la saturación de información y buscaría si la Base de Datos es rápida y eficiente para descartar toda saturación y realizaría consultas masivas para tratar de volver mas eficiente al programa.

5.	Como tester observa que una aplicación tiene varias vulneabilidades y riesgos, por
lo tanto, ¿qué tipos de pruebas recomendarías para disminuir las vulnerabilidades y
riesgos de esa aplicación?

R// 1. En un entorno seguro y manipulado realizaría ataques simultáneos o pruebas de penetracion para mitigar de alguna forma las vulnerabilidades 2. Utilizar herramientas de automatizadas para analizar el código fuente en busca de vulnerabilidades. 3.realizaria un análisis de diseño y de su arquitectura para evitar alguna fuga. 4. Brindar capacitación sobre seguridad de la información para que todo desarrollador tenga una buena practica de codificación segura y precisa.



//Plan de Ataque


FECHA	No. Ejecuciones	No. Ejecuciones Previstas	No. Re-ejecuciones	No. Re-ejecuciones previstas	TESTER	Fallos Encontrados	No. De Fallos Previstos
23/08/2023	7	15	5	2	Miguel Lederer	6	3
Detalle Ejecución 1							
En la primera ejecucion del archivo me percate que en la Linea No. 36 donde se encuentra la  librería math.random, faltaba una sintaxis para poder realizar su funcion de manera correcta la cual es generar el numero aleatorio durante el juego ; en especifico puedo indicar que a la librería le hizo falta agregar la sintaxis math.floor al principio por lo que quedaría de la siguiente forma: math.floor(math.random()*100)+1;							
							
							
							
							
							
							
FECHA	No. Ejecuciones	No. Ejecuciones Previstas	No. Re-ejecuciones	No. Re-ejecuciones previstas	TESTER	Fallos Encontrados	No. De Fallos Previstos
23/08/2023	10	11	7	3	Miguel Lederer	5	3
Detalle Ejecución 2							
En la segunda ejecucion, pude percatarme que en la linea 40 donde se encuentra la funcion const lowOrHi = document.querySelector('lowOrHi'); tenía un error de sintaxis donde faltaba un punto antes de 'lowOrHi'.							
							
							
							
							
							
							
FECHA	No. Ejecuciones	No. Ejecuciones Previstas	No. Re-ejecuciones	No. Re-ejecuciones previstas	TESTER	Fallos Encontrados	No. De Fallos Previstos
23/08/2023	14	12	9	4	Miguel Lederer	4	2
Detalle Ejecución 3							
En la tercera Ejecucion,  en la linea 76 precisamente donde la funcion guessSubmit.addeventListener('click', checkGuess); se encontro nuevamente un pequeño error con la sintaxis ya que Event siendo su primera letra "e" corresponde a escribirse en Mayuscula y no minuscula, por lo que la sintaxis correcta quedaría de la siguiente forma : guessSubmit.addEventListener('click', checkGuess);							
							
							
							
							
							
							
FECHA	No. Ejecuciones	No. Ejecuciones Previstas	No. Re-ejecuciones	No. Re-ejecuciones previstas	TESTER	Fallos Encontrados	No. De Fallos Previstos
23/08/2023	10	5	8	4	Miguel Lederer	3	2
Detalle Ejecución 4							
En la Cuarta Ejecucion, en la linea 84 donde se ejecuta la funcion del boton resetButton.addeventListener('click', resetGame); nuevamente se encuentra un error en la sintaxis precisamente la misma que en el anterior detalle con la letra "e" de AddEventListener por lo que la sintaxis correcta quedaría de la siguiente manera resetButton.addEventListener('click', resetGame);							
							
							
							
							
							
							
FECHA	No. Ejecuciones	No. Ejecuciones Previstas	No. Re-ejecuciones	No. Re-ejecuciones previstas	TESTER	Fallos Encontrados	No. De Fallos Previstos
23/08/2023	5	9	9	5	Miguel Lederer	2	2
Detalle Ejecución 5							
En la 5ta. Ejecucion me percate que los colores asignados a mensajes se encontraban intercambiados según la condicion en los incisos 4 y 5 ; siendo los mensajes de victoria y derrota.							
							
							
							
							
							
							
FECHA	No. Ejecuciones	No. Ejecuciones Previstas	No. Re-ejecuciones	No. Re-ejecuciones previstas	TESTER	Fallos Encontrados	No. De Fallos Previstos
23/08/2023	1	5	5	8	Miguel Lederer	2	1
Detalle Ejecución 6							
En la Linea 46 donde la condicion conts ATTEMPS = 5 en lugar de 5 oportunidades serían 10, debido a que una de las condiciones del Proyecto son 10 intentos y al ejecutar el archivo Index.html el usuario tendría unicamente 5 oportunidades, por lo que se realizo la correccion correspondiente.							
							
							
							
							
							
							
![image](https://github.com/Miguellederer/proyectos/assets/143050630/c36dd67c-ffa6-4603-987c-ddca864b1424)
