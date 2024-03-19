# DEFINICIONES DE GIT Y METODOLOGIAS 
## Git push 
Sirve para enviar los datos de la rama a otro repositorio o a la main

Segun  ATLASSIAN (2024),enviar (push) es lo opuesto a recuperar (fetch), con algunas salvedades. Permite mover una o varias ramas a otro repositorio, lo que es una buena forma de publicar contribuciones. Es como svn commit, pero envía una serie de confirmaciones en lugar de un solo conjunto de cambios.
## Git pull
Sirve para traer los cambios de otro repositorio a tu repositorio

Segun ATLASSIAN (2024),el comando git pull se emplea para extraer y descargar contenido desde un repositorio remoto y actualizar al instante el repositorio local para reflejar ese contenido. La fusión de cambios remotos de nivel superior en tu repositorio local es una tarea habitual de los flujos de trabajo de colaboración basados en Git. El comando git pull es, en realidad, una combinación de dos comandos, git fetch seguido de git merge. En la primera etapa de la operación git pull ejecutará un git fetch en la rama local a la que apunta HEAD. Una vez descargado el contenido, git pull entrará en un flujo de trabajo de fusión. Se creará una nueva confirmación de fusión y se actualizará HEAD para que apunte a la nueva confirmación.
## Git Branch
Sirve para gestionar tus ramas (ver las ramas activas,crear ramas, eliminarlas ,ect)

Segun Pro Git 2da edicion (2014),el comando git branch es en realidad una especie de herramienta de gestión de ramas. Puede listar las ramas que tienes, crear una nueva rama, eliminar ramas y cambiar el nombre de las ramas.
La mayor parte de [ch03-git-branching] está dedicada al comando branch y es utilizado a lo largo de todo el capítulo. En primer lugar, lo introducimos en Crear una Rama Nueva y examinamos la mayor parte de sus otras características (listar y borrar) en Gestión de Ramas.
En Hacer Seguimiento a las Ramas usamos la opción git branch -u para establecer una rama de seguimiento.
Finalmente, examinamos algo de lo que hace en segundo plano en Referencias Git.
## Git checkout
Sirve para cambiar de rama y ver el contenido de tu carpeta.

Segun Pro Git 2da edicion (2014),el comando git checkout se usa para cambiar de rama y revisar el contenido de tu directorio de trabajo.
## Git Fork
Sirve como para clonar un repositoria a un repositorio tuyo

Segun Platzi (s.f),Los forks o bifurcaciones son una característica única de GitHub en la que se crea una copia exacta del estado actual de un repositorio directamente en GitHub. Este repositorio podrá servir como otro origen y se podrá clonar (como cualquier otro repositorio). 
## Git merge
Sirve para mezclar ramas y sus cambios

Segun Git 2da edicion (2014),la herramienta git merge se utiliza para fusionar uno o más ramas dentro de la rama que tienes activa. A continuación avanzará la rama actual al resultado de la fusión.
## Quality Assurance
Es dejar al codigo con la mayor calidad posible para que sea utilizable y tenga un buen funcionamiento

Segun linkedin "SQA-Software Quality Assurance S. A." (2023),“Quality Assurance” traducido al español es “Aseguramiento de la calidad”, que en el contexto del desarrollo de software es el proceso de evaluación de la calidad y el aseguramiento de que el software cumple con los requisitos del usuario y especificaciones del negocio, esto se logra mediante la realización de pruebas para identificar y corregir defectos, errores y problemas antes de que sea entregado a los usuarios finales.
## Testing o pruebas
La accion de probar lo que tienes de diferentes maneras para encontrar posibles errores y arreglarlos

Segun IBM (s.f), la prueba de software es el proceso de evaluar y verificar que un producto o aplicación de software hace lo que se supone que debe hacer. Los beneficios de las pruebas incluyen la prevención de errores, la reducción de los costos de desarrollo y la mejora del rendimiento.
## Debugging o Depuración
Es examinar el programa  quitar los errores del codigo para evitar problemas 

Segun learn.Micreosoft (2023),El término depuración puede significar una gran cantidad de cosas diferentes, pero literalmente significa quitar errores del código. Sin embargo, hay muchas formas de hacerlo. Por ejemplo, puede examinar el código en busca de errores tipográficos o usar un analizador de código. También podría depurar el código mediante un generador de perfiles de rendimiento. O bien, puede usar un depurador.
## Metodologías de proyectos
Conjunto de teorias y tecnicas para organizarse a travez de estandares para hacer las cosas mas rapido y sin esfuerzo

Segun la UNIR (2020),La metodología de gestión de proyectos es la disciplina de conocimiento encargada de elaborar, definir y sistematizar el conjunto de técnicas, métodos y procedimientos que se deben seguir durante el desarrollo de un proyecto para la producción de los productos o servicios que supone.
No es posible concebir la dirección de proyectos sin pensar de manera casi automática en la serie de pasos que debemos cumplir para asegurar la consecución de los objetivos del proyecto.
## Metodología en cascada
Metodogia estilo cascada que va una despues de otra 

Segun el Instituto Europeo de Posgrado (2022),La metodología Waterfall es un método de gestión de proyectos, al igual que el diagrama de PERT, basado en el desarrollo secuencial de fases que fluyen como una cascada. Es decir, divide el proyecto en distintas fases secuenciales, en las que cada nueva fase sólo comienza cuando se ha completado la anterior.
## Metodologías ágiles
Metodologia en la que se hace un tema por cortos periodos de tiempo

Segun la Universidad Europea(2022),Las metodologías ágiles son una manera de trabajar rápida, eficaz y flexible. Su objetivo es desarrollar productos y servicios de calidad adaptados a las necesidades de unos clientes y a las preferencias de un mercado que cambian a un ritmo vertiginoso. 
## Iteración
Es corregir los errores repetidamente hasta que el producto quede bien 

Segun la Universitat Carlemany (2023),La iteración es el proceso coordinado de repetir una serie de pasos o tareas con el objetivo de mejorar un producto, servicio o proyecto a lo largo del tiempo. En este caso, la repetición de un programa informático para corregir errores y perfeccionar cada uno de sus elementos.