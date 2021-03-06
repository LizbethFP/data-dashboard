# Data Dashboard

* **Track:** _Common Core_
* **Curso:** _Creando tu primer sitio web interactivo_
* **Unidad:** _Producto final_

***
## Objetivo
---
En Laboratoria, las Training Managers (TMs) hacen un gran trabajo al analizar la mayor cantidad de datos posibles respecto al desempeño de las estudiantes para apoyarlas en su aprendizaje. Para revisar esta data, las TMs, normalmente, tienen que revisar muchos documentos de excel (Google Spreadsheets) que están localizados en distintas carpetas y ubicaciones. Muchas veces pierden tiempo localizando estos documentos y ejecutando fórmulas para obtener los datos que necesitan.

Para poder optimizar su tiempo, las TMs han solicitado que construyamos una herramienta web donde puedan ver estos datos fácil y rápidamente. Y nos comentaron que estos son los datos que revisan normalmente:

* El total de estudiantes presentes por sede y generación.
* El porcentaje de deserción de estudiantes.
* La cantidad de estudiantes que superan la meta de puntos en promedio de todos los sprints cursados. La meta de puntos es 70% del total de puntos en HSE y en tech.
* El porcentaje que representa el dato anterior en relación al total de estudiantes.
* El Net Promoter Score (NPS) promedio de los sprints cursados. El NPS se calcula en base a la encuesta que las estudiantes responden al respecto de la recomendación que darían de Laboratoria, bajo la siguiente fórmula:

[Promoters] = [Respuestas 9 o 10] / [Total respuestas] * 100
[Passive] = [Respuestas 7 u 8] / [Total respuestas] * 100
[Detractors] = [Respuestas entre 1 y 6] / [Total respuestas] * 100

[NPS] = [Promoters] - [Detractors]
* La cantidad y el porcentaje que representa el total de estudiantes que superan la meta de puntos técnicos en promedio y por sprint.
* La cantidad y el porcentaje que representa el total de estudiantes que superan la meta de puntos de HSE en promedio y por sprint.
* El porcentaje de estudiantes satisfechas con la experiencia de Laboratoria.
* La puntuación promedio de l@s profesores.
* La puntuación promedio de l@s jedi masters.
Con esa información y con la base de datos que nos facilitaron pudimos crear este diseño. Sin embargo, creemos que tú podrías proponer algún cambio a este diseño que pueda mejorar la experiencia de las TMs.

### Dashboard propuesto
#### Dashboard N° 1
![Sin titulo](assets/docs/dashboard-sketch.jpg)
En este dashboard, se encuentra lo siguiente:
1.  Una barra de navegación  a la izquierda, donde se ubica en la parte superior el logo de Laboratoria, la imagen del usuario con su nombre como pie de página, una barra de búsqueda con un ícono de búsqueda, un menú desplegable de las sedes por países y ciudades.
2. Una sección principal con una parte designada para íconos de mensajería, chat y cerra sesión.
3. Luego, se cuenta con una sección de pestañas que habilitan la información de general, estudiantes y profesores, según la sede y generación seleccionadas.
4. En la sección de general, se indica en la primera fila las inscripciones, nivel de logro, promedio de los sprints cruzados; en la segunda fila, las habilidades técnicas; en la tercera fila, las habilidades emocionales; en la cuarta fila, la satisfacción de las estudiantes, la calificación de los profesores y la calificación de los jedi.  


## Contenido

Este proyecto contiene:

1. Un archivo  **`README.md`** que explica el contenido del repositorio.

2. Una carpeta `docs` donde se encuentran las imágenes que representan el dashboard de Laboratoria en formato **jpg**.

## Autoras
* Melyna
* Lizbeth

## Fecha
30/11/2017

## Flujo de trabajo

1. Debes realizar un [**fork**](https://gist.github.com/ivandevp/1de47ae69a5e139a6622d78c882e1f74)
   de este repositorio.

2. Luego deberás **clonar** tu fork en tu máquina. Recuerda que el comando a usar
   es `git clone` y su estructura normalmente se ve así:

   ```bash
   git clone https://github.com/<nombre-de-usuario>/freelancer.git
   ```

3. Cuando hayas terminado tu producto, envía un Pull Request a este repositorio
   (puedes solicitar apoyo de tus profes para este paso).

> Nota: No olvides que es una buena práctica describir tu proyecto en este
> archivo `README.md` y también desplegar tu web a Github Pages :smiley:.
