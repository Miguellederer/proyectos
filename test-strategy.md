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
