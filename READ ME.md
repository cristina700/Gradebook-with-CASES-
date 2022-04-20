# Gradebook-with-CASES-
Queries using CASE, GROUP BY, COUNT and ROUND

I want to track student grades, with their name, number grade, and what percent of activities they've completed. So we select all of the rows, and display the name, number_grade, and percent_completed, multiplying by 100 and rounding the fraction_completed column.
Later, in other table, I want to know how many students have earned which letter_grade. For that, I output the letter_grade by using CASE with the number_grade column, outputting 'A' for grades > 90, 'B' for grades > 80, 'C' for grades > 70, and 'F' otherwise. Then use COUNT with GROUP BY to show the number of students with each of those grades.


Quiero hacer un seguimiento de las calificaciones de mis alumnos, sus nombres, calificaciones en letras A, B, C, y F y el porcentaje de actividades realizadas. Para eso seleccionamos todas las filas, mostramos el nombre, nota que sacó y porcentaje de actividades realizado, multiplicando por 100 y redondeando el número de porcentaje.
Después, en otra tabla, quiero saber cuantos estudiantes han logrado las diferentes calificaciones en letras. Para eso, produzco las letras usando CASE la columna de notas (en número) generando "A" para las notas >90, "B" para las notas >80, "C" para las notas >70 y "F" para los demás casos. Luegouso COUNT con BROUP BY para mostrar la cantidad de alumnos con cada una de esas letras.
