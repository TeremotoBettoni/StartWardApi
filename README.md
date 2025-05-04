# StartWard objetivo
Crear una aplicación para consultar las películas de Star Wars mediante la SW API.
Crear un menú para que el usuario elija la película que quiere buscar.
Generar un archivo .json con los datos de la película.

# API SWAP
- https://swapi.py4e.com/api/films/1/

    Ahora para adaptar nuestro código y seguir accediendo a la información de la película de Star Wars, necesitamos hacer un pequeño cambio en nuestra clase ConsultaPelicula.
    URI.create("https://swapi.py4e.com/api/films/"+numeroDePelicula+"/");

# Dependency
    - Gson 2.9.0 to 2.11.0: Java 7
    resource: https://github.com/google/gson
