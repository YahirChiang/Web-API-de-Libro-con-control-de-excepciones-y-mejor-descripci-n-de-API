# Web-API-de-Libro-con-control-de-excepciones-y-mejor-descripci-n-de-API
## Clase Libro.java
El archivo Libro.java es una clase en Java que representa un objeto de tipo libro en nuestra aplicación de biblioteca digital. Esta clase contiene diferentes atributos que describen las características de un libro y métodos para interactuar con esos atributos.
Estas son las siguientes variables:

titulo: Esta variable de tipo String almacena el título del libro.

autor: Almacena el nombre del autor del libro como un String.

isbn: Representa el número de ISBN del libro, que es un identificador único para cada libro.

anioPublicacion: Un entero que indica el año de publicación del libro.

genero: Almacena el género del libro, también como un String.

editorial: El nombre de la editorial que publicó el libro.

![Code de la clase libro](https://raw.githubusercontent.com/mamf1209/libros/main/libro.jpg)



# Pruebas a través de Postman:
## Endpoint GET/libros
### Descripción:
Este endpoint devuelve todos los libros almacenados en la base de datos.

![Obtener todos los libros](https://raw.githubusercontent.com/mamf1209/libros/main/GetAllBook.jpg)

## Endpoint GET/libros/{id_libro}
### Descripción:
Este endpoint devuelve un libro específico según su ID.

![Obtener libro por ID](https://raw.githubusercontent.com/mamf1209/libros/main/GetID.jpg)

## Endpoint POST/libros
### Descripción:
Este endpoint permite añadir un nuevo libro a la base de datos.

![Crear libro](https://raw.githubusercontent.com/mamf1209/libros/main/Create.jpg)

## LocalHost:
Acá se puede visualizar la página actualizada despues de realizar el útlimo Endpoint (donde se creó un nuevo libro):

![Imagen de localhost](https://raw.githubusercontent.com/mamf1209/libros/main/localhost1.jpg)

## Crea la excepción en el paquete com.tuuniversidadexceptions:

![Captura de Pantalla de la Aplicación](https://github.com/YahirChiang/Web-API-de-Libro-con-control-de-excepciones-y-mejor-descripci-n-de-API/blob/main/Capturadepantalla2024-06-03 195428.jpg)



