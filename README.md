# Control de Información Estudiantil

## Enunciado
La universidad ABC solicita un sistema que permita llevar control de todos sus estudiantes, profesores y cursos. Se necesita conocer que cursos se encuentran disponibles, que profesores los dictan y que estudiantes están inscritos en dichos cursos. También se requiere mantener un registro de las notas de cada estudiante a lo largo de todos sus cursos inscritos.

* Por cada estudiante y profesor, la universidad necesita saber su nombre, RUT, edad, dirección de residencia, celular y correo electrónico.
* En un semestre se dictan una gran variedad de cursos. Cada curso posee 1 o más paralelos, esto dependiendo de la cantidad de estudiantes que requieran tomarlo.
* Cada paralelo posee un mínimo y un máximo de estudiantes (determinado por el curso). Si solo existe un paralelo y este no alcanza el mínimo de estudiantes, el curso es cancelado. En ese caso, los estudiantes afectados pueden inscribirse en un curso similar.
* Los estudiantes pueden tomar distintos cursos en un semestre, siempre y cuando no excedan el limite de 30 créditos. Los cursos de tipo "taller", "normal", y "capstone" cuestan 4, 5 y 30 créditos respectivamente.
* Un profesor imparte de 1 a 5 paralelos por semestre. Si un profesor imparte mas de 3 paralelos en un semestre, recibe un bono de responsabilidad.
* Si un estudiante consume menos de 15 créditos en un semestre se le considera como estudiante de tiempo parcial; de otra forma, se le considera como estudiante de tiempo completo.
* Las notas de un estudiante se miden en el rango de 10 a 70. Si el promedio de notas del estudiante en un semestre es menor a 50, el estudiante pasa a estado de prueba académica.
