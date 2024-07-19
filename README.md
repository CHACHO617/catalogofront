# React App Catálogo
Problematica: Este proyecto de react busca mostrar el consumir el backend creado en Node js mediante un front end con React, mostrando que el proyecto como tal puede se puede consumir el backend (API) creado usando Node Js mediante un front con otro framework JavaScript como React. 

### Catalogo.js
Este componente Catalogo es una parte de una aplicación React que muestra una lista de productos con sus detalles. Incluye una barra de búsqueda para filtrar los productos por nombre.

#### Funcionalidades
Carga de datos: Al montarse el componente, se realiza una solicitud HTTP a un endpoint para obtener una lista de productos y sus respectivos ingredientes.
Filtrado: Permite filtrar los productos mostrados en función del término de búsqueda ingresado por el usuario.
Visualización: Muestra detalles de cada producto, incluyendo imagen, nombre, descripción, precio, stock e ingredientes.

#### Componentes
SearchBar: Un componente para la barra de búsqueda que permite al usuario ingresar texto para filtrar los productos.

#### Axios
Se utiliza para realizar solicitudes HTTP.

### Searchbar.js
El componente SearchBar es una parte de una aplicación React que proporciona una barra de búsqueda para filtrar productos u otros elementos en una lista.

#### Funcionalidades
Entrada de búsqueda: Permite al usuario ingresar texto para buscar productos.
Actualización del término de búsqueda: A través de una función de devolución de llamada, actualiza el estado del término de búsqueda en el componente padre.

#### Terminos
searchTerm: El término de búsqueda actual que se muestra en el campo de entrada.
onChange: Función de devolución de llamada que se ejecuta cuando el usuario cambia el valor del campo de entrada.
