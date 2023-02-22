# Para la obtención de la nota final del bootcamp se siguió la siguiente metodología

- En cada semanal hubo como mínimo 1 curso que se evaluaba.
- Los profesores dejaron trabajos en clase de donde se obtuvieron las notas de trabajos o en su defecto se calcula la nota de trabajos con la nota del semanal.
- Cada curso obtiene una nota ponderada en base a su syllabus teniendo un porcentaje `x%` para la nota de semanal y `y%` para la nota de trabajos de modo que esos porcentajes sumen el 100%.
- Esa nota ponderada por cada curso es lo observado en el dashboard de notas en Looker Studio.
- Esa nota se pondera en base a la cantidad de creditos del curso, cada curso vale como mínimo 1 crédito y aumenta en creditos cada 12 horas dictadas.
- Cada curso corresponde a un área de aprendizaje.
- De cada área se obtiene un promedio y esos promedios son los que se ponderan con los creditos del área (los creditos del área son la suma de los creditos de todos los cursos que corresponden a dicha área) y se divide entre la cantidad de creditos totales.
Acá una muestra:
</br></br>
Bootcamp X
</br>

- Area 1</br>

|Curso | Horas dictadas | Creditos |
|------|----------------|----------|
|Curso 1|12 |1|
|Curso 2|24 |2|
|Curso 3|24 |2|
|Curso 4|36 |3|

Promedio_area1 = 19 (EJEMPLO)</br>
Creditos_area1 = 8
</br>

- Area 2</br>

|Curso | Horas dictadas | Creditos |
|------|----------------|----------|
Curso 1 | 60 |5</br>
Curso 2 | 24 |2</br>
Curso 3 | 36 |3</br>
Curso 4 | 24 |2</br>

Promedio_area2= 18 (EJEMPLO)</br>
Creditos_area2 = 12
</br>

- Area 3</br>

|Curso | Horas dictadas | Creditos |
|------|----------------|----------|
Curso 1 | 12 |1</br>
Curso 2 | 36 | 3</br>

Promedio_area3= 12 (EJEMPLO)</br>
Creditos_area3 = 4
</br>

- Area 4</br>

|Curso | Horas dictadas | Creditos |
|------|----------------|----------|
Curso 1 | 12 | 1</br>
Curso 2 | 24 |2</br>
Curso 3 | 24 |2</br>

Promedio_area4= 15 (EJEMPLO)</br>
Creditos_area4 = 5
</br></br>
Prome final= Suma1_n(Pro_an*Cant_cred_an)/creditos totales</br>
Prome final= (19\*8 + 18\*12 + 12\*4 + 5\*15) / 29 = 16.9

- Luego con ese promedio obtenido por áreas pasamos a la nota de proyecto final.
- Los jurados los calificaron en base a sus exposiciones y sus trabajos así como tambien ustedes se calificaron a si mismos, en el caso de que la calificación entre los miembros del mismo grupo hacia tí fuera buena (de 3.5 a 5 estrellas⭐en promedio) obtendrías la nota completa que te colocó el jurado, de ser regular (1.5 a 3.5 estrellas ⭐ en promedio) obtendrias el 90% de la nota del jurado y si tus compañeros te calificaron con menos de eso obtuviste el 80% de la nota del jurado.
- Por ultimo para obtener ahora sí la nota que les llegó al correo como calificación final se tuvo en cuenta ambas notas (nota por áreas y nota de la exposición) con un peso del 40% y 60% respectivamente.
