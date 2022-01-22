# Calcular_tiempo

ESPAÑOL

Escriba una función llamada add_time que tome dos parámetros requeridos y un parámetro opcional:

una hora de inicio en el formato de reloj de 12 horas (terminando en AM o PM)
un tiempo de duración que indica el número de horas y minutos
(opcional) un día de inicio de la semana, sin distinción entre mayúsculas y minúsculas
La función debe agregar el tiempo de duración a la hora de inicio y devolver el resultado.

Si el resultado será al día siguiente, debería aparecer (día siguiente) después de la hora. Si el resultado será más de un día después, debería aparecer (n días después) después de la hora, donde "n" es el número de días después.

Si a la función se le asigna el parámetro opcional de día de inicio de la semana, la salida debe mostrar el día de la semana del resultado. El día de la semana en la salida debe aparecer después de la hora y antes del número de días posteriores.

A continuación se muestran algunos ejemplos de diferentes casos que la función debe manejar. Preste mucha atención al espaciado y la puntuación de los resultados.

add_time("3:00 PM", "3:10")
# Return: 18:10

add_time("11:30 AM", "2:32", "Lunes")
# Return: 14:02, lunes

add_time("11:43 AM", "00:20")
# Return: 12:03 PM

add_time("22:10", "3:30")
# Return: 1:40 AM (día siguiente)

add_time("11:43 PM", "24:20", "martes")
# Return: 00:03, jueves (2 días después)

add_time("6:30 PM", "205:12")
# Return: 7:42 AM (9 días después)

No importe ninguna biblioteca de Python. Suponga que las horas de inicio son horas válidas. Los minutos del tiempo de duración serán un número entero menor que 60, pero la hora puede ser cualquier número entero.

Desarrollo

Escribe tu código en time_calculator.py. Para el desarrollo, puede usar main.py para probar su función time_calculator(). Haga clic en el botón "ejecutar" y main.py se ejecutará.

Pruebas

Las pruebas unitarias para este proyecto están en test_module.py. Importamos las pruebas de test_module.py a main.py para su comodidad. Las pruebas se ejecutarán automáticamente cada vez que presione el botón "ejecutar".



INGLES

Write a function named add_time that takes in two required parameters and one optional parameter:

a start time in the 12-hour clock format (ending in AM or PM)
a duration time that indicates the number of hours and minutes
(optional) a starting day of the week, case insensitive
The function should add the duration time to the start time and return the result.

If the result will be the next day, it should show (next day) after the time. If the result will be more than one day later, it should show (n days later) after the time, where "n" is the number of days later.

If the function is given the optional starting day of the week parameter, then the output should display the day of the week of the result. The day of the week in the output should appear after the time and before the number of days later.

Below are some examples of different cases the function should handle. Pay close attention to the spacing and punctuation of the results.

add_time("3:00 PM", "3:10")
# Returns: 6:10 PM

add_time("11:30 AM", "2:32", "Monday")
# Returns: 2:02 PM, Monday

add_time("11:43 AM", "00:20")
# Returns: 12:03 PM

add_time("10:10 PM", "3:30")
# Returns: 1:40 AM (next day)

add_time("11:43 PM", "24:20", "tueSday")
# Returns: 12:03 AM, Thursday (2 days later)

add_time("6:30 PM", "205:12")
# Returns: 7:42 AM (9 days later)
Do not import any Python libraries. Assume that the start times are valid times. The minutes in the duration time will be a whole number less than 60, but the hour can be any whole number.

Development

Write your code in time_calculator.py. For development, you can use main.py to test your time_calculator() function. Click the "run" button and main.py will run.

Testing

The unit tests for this project are in test_module.py. We imported the tests from test_module.py to main.py for your convenience. The tests will run automatically whenever you hit the "run" button.
