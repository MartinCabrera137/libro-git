##Martin Cabrera Hernandez 18100154
###Lista de ejercicicios
#### 1.-Ejercicios de creación y actualización de repositorios (ejercicios básicos)

Ejercicio 1

Configurar Git definiendo el nombre del usuario, el correo electrónico y activar el coloreado de la salida. Mostrar la configuración final.

[![1.jpg](https://i.postimg.cc/V6qrhZNw/1.jpg)](https://postimg.cc/473x75t2)



Ejercicio 2
Crear un repositorio nuevo con el nombre libro y mostrar su contenido.

[![2.jpg](https://i.postimg.cc/brqDf0Gt/2.jpg)](https://postimg.cc/dkSt8yjs)

Ejercicio 3

1. Comprobar el estado del repositorio.
2. Crear un fichero indice.txt con el siguiente contenido
Capítulo 1 Introducción a Git
Capítulo 2 Flujo de trabajo básico
Capítulo 3 Repositorios remotos
1. Comprobar de nuevo el estado del repositorio.
2. Añadir el fichero a la zona de intercambio temporal.
3. Volver a comprobar una vez más el estado del repositorio.

[![3.jpg](https://i.postimg.cc/J46ySkRs/3.jpg)](https://postimg.cc/KRTvM4kb)

Ejercicio 4

Realizar un commit de los últimos cambios con el mensaje “Añadido índice del libro.” y ver el estado del repositorio.

[![4.jpg](https://i.postimg.cc/mkVcLcM6/4.jpg)](https://postimg.cc/V0rs4kKj)


Ejercicio 5

1. Cambiar el fichero indice.txt para que contenga lo siguiente
Capítulo 1 Introducción a Git
Capítulo 2 Flujo de trabajo básico
Capítulo 3 Gestión de ramas
Capítulo 4 Repositorios remotos
2. Mostrar los cambios con respecto a la última versión guardada en el repositorio.
3. Hacer un commit de los cambios con el mensaje “Añadido capítulo 3 sobre gestión de ramas”.

[![5.jpg](https://i.postimg.cc/7YYGBVrv/5.jpg)](https://postimg.cc/Jtvz0jhK)

Ejercicio 6

1. Mostrar los cambios de la última versión del repositorio con respecto a la anterior.
2. Cambiar el mensaje del último commit por “Añadido capítulo 3 sobre gestión de ramas al índice.”
3. Volver a mostrar los últimos cambios del repositorio.

[![6.jpg](https://i.postimg.cc/BZCPczyc/6.jpg)](https://postimg.cc/RqN0vgvN)

#### 2.- Ejercicios de manejo del historial de cambios

Ejercicio 1
1.- Mostrar el historial de cambios del repositorio.
Crear la carpeta capitulos y crear dentro de ella el fichero capitulo1.txt con el siguiente texto.
Git es un sistema de control de versiones ideado por Linus Torvalds.

2.- Añadir los cambios a la zona de intercambio temporal.
3.- Hacer un commit de los cambios con el mensaje“Añadido capítulo 1.”
Volver a mostrar el historial de cambios del repositorio.

[![imagen-2022-09-18-173920501.png](https://i.postimg.cc/1zj1Qyfc/imagen-2022-09-18-173920501.png)](https://postimg.cc/KKBH7S7R)

Ejercicio 2
1. Crear el fichero capitulo2.txt en la carpeta capitulos con el siguiente texto.
2. El flujo de trabajo básico con Git consiste en: 1- Hacer cambios en el repositorio. 2- Añadir los cambios a la zona de intercambio temporal. 3- Hacer un commit de los cambios.
4. Añadir los cambios a la zona de intercambio temporal.
5. Hacer un commit de los cambios con el mensaje “Añadido capítulo 2.”
6. Mostrar las diferencias entre la última versión y dos versiones anteriores.

[![imagen-2022-09-18-175232136.png](https://i.postimg.cc/SK3QG67h/imagen-2022-09-18-175232136.png)](https://postimg.cc/DWQKvbMj)

Ejercicio 3
1. Crear el fichero capitulo3.txt en la carpeta capitulos con el siguiente texto.
2. Git permite la creación de ramas lo que permite tener distintas versiones del mismo proyecto y trabajar de manera simultanea en ellas.
4. Añadir los cambios a la zona de intercambio temporal.
5. Hacer un commit de los cambios con el mensaje “Añadido capítulo 3.”
6. Mostrar las diferencias entre la primera y la última versión del repositorio.

[![imagen-2022-09-18-180328579.png](https://i.postimg.cc/fRHYDPZf/imagen-2022-09-18-180328579.png)](https://postimg.cc/XrCrgQrr)

Ejercicio 4
1. Añadir al final del fichero indice.txt la siguiente línea: Capítulo 5: Conceptos avanzados
2. Añadir los cambios a la zona de intercambio temporal.
3. Hacer un commit de los cambios con el mensaje “Añadido capítulo 5 al índice.”.
4. Mostrar quién ha hecho cambios sobre el fichero indice.txt.

[![imagen-2022-09-18-180507267.png](https://i.postimg.cc/FHnk2JgP/imagen-2022-09-18-180507267.png)](https://postimg.cc/tsWg6JcP)




#### 3. Ejercicios de deshacer cambios
Ejercicio 1
1. Eliminar la última línea del fichero indice.txt y guardarlo.
2. Comprobar el estado del repositorio.
3. Deshacer los cambios realizados en el fichero indice.txt para volver a la versión anterior del fichero.
4. Volver a comprobar el estado del repositorio.

[![imagen-2022-09-18-181239907.png](https://i.postimg.cc/3wTQrtBW/imagen-2022-09-18-181239907.png)](https://postimg.cc/YvbsbfTw)

Ejercicio 2
1. Eliminar la última línea del fichero indice.txt y guardarlo.
2. Añadir los cambios a la zona de intercambio temporal.
3. Comprobar de nuevo el estado del repositorio.
4. Quitar los cambios de la zona de intercambio temporal, pero mantenerlos en el directorio de trabajo.
5. Comprobar de nuevo el estado del repositorio.
6. Deshacer los cambios realizados en el fichero indice.txt para volver a la versión anterior del fichero.
7. Volver a comprobar el estado del repositorio.

[![imagen-2022-09-18-181731825.png](https://i.postimg.cc/3NpPHpv2/imagen-2022-09-18-181731825.png)](https://postimg.cc/zHzdCypf)

Ejercicio 3
1. Eliminar la última línea del fichero indice.txt y guardarlo.
2. Eliminar el fichero capitulos/capitulo3.txt.
3. Añadir un fichero nuevo captitulos/capitulo4.txt vacío.
4. Añadir los cambios a la zona de intercambio temporal.
5. Comprobar de nuevo el estado del repositorio.
6. Quitar los cambios de la zona de intercambio temporal, pero mantenerlos en el directorio de trabajo.
7. Comprobar de nuevo el estado del repositorio.
8. Deshacer los cambios realizados para volver a la versión del repositorio.
9. Volver a comprobar el estado del repositorio.

[![imagen-2022-09-18-182018267.png](https://i.postimg.cc/QM2mZzkn/imagen-2022-09-18-182018267.png)](https://postimg.cc/1gKwpJdp)

Ejercicio 4
1. Eliminar la última línea del fichero indice.txt y guardarlo.
2. Eliminar el fichero capitulos/capitulo3.txt.
3. Añadir los cambios a la zona de intercambio temporal y hacer un commit con el mensaje “Borrado accidental.”
4. Comprobar el historial del repositorio.
5. Deshacer el último commit pero mantener los cambios anteriores en el directorio de trabajo y la zona de intercambio temporal.
6. Comprobar el historial y el estado del repositorio.
7. Volver a hacer el commit con el mismo mensaje de antes.
8. Deshacer el último commit y los cambios anteriores del directorio de trabajo volviendo a la versión anterior del repositorio.
9. Comprobar de nuevo el historial y el estado del repositorio.

[![imagen-2022-09-18-182315208.png](https://i.postimg.cc/52wNmYKY/imagen-2022-09-18-182315208.png)](https://postimg.cc/QFd38t3h)

#### 4. Ejercicios de gestion de ramas
Ejercicio 1
1. Crear una nueva rama bibliografia y mostrar las ramas del repositorio.

[![imagen-2022-09-18-182705679.png](https://i.postimg.cc/c1RS2yM2/imagen-2022-09-18-182705679.png)](https://postimg.cc/0ryFK440)


Ejercicio 2
1. Crear el fichero capitulos/capitulo4.txt y añadir el texto siguiente
2. En este capítulo veremos cómo usar GitHub para alojar repositorios en remoto.
4. Añadir los cambios a la zona de intercambio temporal.
5. Hacer un commit con el mensaje “Añadido capítulo 4.”
6. Mostrar la historia del repositorio incluyendo todas las ramas.

[![imagen-2022-09-18-183648965.png](https://i.postimg.cc/Bb6BTGqb/imagen-2022-09-18-183648965.png)](https://postimg.cc/HcqMmR81)


Ejercicio 3
1. Cambiar a la rama bibliografia.
2. Crear el fichero bibliografia.txt y añadir la siguiente referencia 
Chacon, S. and Straub, B. Pro Git. Apress.
4. Añadir los cambios a la zona de intercambio temporal.
5. Hacer un commit con el mensaje “Añadida primera referencia bibliográfica.”
6. Mostrar la historia del repositorio incluyendo todas las ramas.

[![imagen-2022-09-18-183920725.png](https://i.postimg.cc/Qt6pxnp3/imagen-2022-09-18-183920725.png)](https://postimg.cc/BLK8mpYY)
