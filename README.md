# Acertijo de las ocho reinas
> Este proyecto fue diseñado como proyecto final de la materia de Estructuras de Datos del Instituto Tecnológico Autónomo de México. Tiene como objetivo solucionar el problema de las ocho reinas por medio de la aplicación de conjuntos en Java 15.0.1. La solución se muestra en una interfaz gráfica en la que el usuario inserta las fila y columna de la primera reina y el algoritmo encuentra las posiciones de las siete reinas restantes. 
---
Versión 1.0
---
Marzo 2022

## Tabla de contenidos
* [Problema de las ocho reinas](#info)
* [Especificaciones de la implementación](#especif)
* [Funcionalidades](#func)
* [Capturas de pantalla](#capturas)
* [Documentación para replicar](#docum)
* [Contacto](#contacto)
---


## Problema de las ocho reinas <a name="info"></a> 
El problema de las ocho reinas tiene como objetivo acomodar ocho reinas en un tablero de ajedrez de manera que no se amenacen entre ellas. El algoritmo utilizado para solucionar el problema de las ocho reinas permite que el usuario elija las fila y columna en la que se coloca la primera reina . De ahí, con el uso conjuntos y otros conocimientos de la materia Estructura de Datos, la solución se representa en una interfaz gráfica donde el usuario visualiza la posición de las demás reinas. En el caso en que no haya solución, el programa informa al usuario.


## Especificaciones de la implementación <a name="especif"></a> 
La dependecia de clases utilizadas en el programa se muestra en el siguiente diagrama UML
![UML](https://github.com/KarenArteaga/Acertijo-8-Reinas/files/8306208/Diagrama.UML.pdf)



## Funcionalidades <a name="func"></a> 
- Insertar la fila y columna de la primera reina
- Calcular la posición de las siete reinas restantes
- Mostrar la posición de las reinas en un tablero de ajedrez virtual
 
 ### Interfaz gráfica de usuario
 - El tablero de ajedrez virtual se ve de la siguiente manera: 
  ![Interfaz gráfica](https://user-images.githubusercontent.com/69361149/159027992-f6fef4bf-f1aa-4bb5-8d1c-c42240d661b6.png)
  
  ### Ejemplo de uso
 - Este es un ejemplo en que el usuario decide colocar la primera reina en la fila uno y columna uno. 
  ![Ejemplo11](https://user-images.githubusercontent.com/69361149/159029310-737f13ee-d5ad-4f32-b3ac-81b718e38db1.png)


## Documentación para replicar <a name="docum"></a> 

  ### Pasos para replicar
  1. Clona el [repositorio](https://github.com/KarenArteaga/Acertijo-8-Reinas.git)
  2. Accede a la carpeta del repositorio clonado desde la terminal y, después, a la carpeta Reinas con el comando `cd <directorio de la carpeta>`.
  ![terminal](https://user-images.githubusercontent.com/69361149/159034049-677c6056-b65f-4cc5-af90-9e221ced7051.png)
  3. Usa el comando `javac *.java` para compilar el programa.
  4. Usa el comando `java Reinas` para ejecutar el proyecto.
     - Se abrirá la siguiente interfaz gráfica de usuario
    ![Interfaz gráfica](https://user-images.githubusercontent.com/69361149/159027992-f6fef4bf-f1aa-4bb5-8d1c-c42240d661b6.png)
  5. Escribe fila y columna en donde se quiere colocar a la primera reina.
  6. Da clic en *Calcular* para encontrar el lugar de las siete reinas restantes.
     - En este ejemplo se coloca la primera reina en la fila seis y columna siete.
    ![ejemplo2](https://user-images.githubusercontent.com/69361149/159036509-9775a6cb-a35e-49d5-b1d1-5935516ca825.png)
  7. Cierra la ventana para terminar la ejecución.


## Reconocimientos <a name="recon"></a> 
- Este proyecto es un caso especial del problema de las N reinas planteado por Franz Nauck en 1850. 
- Este proyecto fue desarrollado por Uxia Vázquez y Karen Arteaga en noviembre 2020.
- La documentación de este proyecto fue escrita por Alan Vivanco.


## Contacto
* Creado por [Karen Arteaga](https://github.com/KarenArteaga) - sígueme en mis redes sociales como @artekaren
* Documentado por [Alan Vivanco]() - sígueme en mis redes sociales como @alan_vibess

