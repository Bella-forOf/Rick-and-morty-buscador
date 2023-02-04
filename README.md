# EVALUACION FINAL MODULO 3

## Realizada por : Bella Irene Garcia Villegas.

![image text](https://www.latercera.com/resizer/oStaaBjKjrTK8rrWE2MFitEba_g=/900x600/smart/arc-anglerfish-arc2-prod-copesa.s3.amazonaws.com/public/FIN7ZFLY2VF7ZIO3F4VAH7DJ5I.jpg)

Este proyecto obtiene los personajes de Rick y Morty de una API y te permite ver su información. Además, puedes filtrar estos personajes por dos criterios: por nombre y por especie. Si hace clic en cualquier personaje, puede acceder a una página individual para cada uno de ellos que muestra más detalles.

🧩Componentes🧩
La estructura de este proyecto está dividida por componentes:

App.js: componente principal que controla todos los demás y la lógica principal de la aplicación.
CharacterDetail.js: componente que representa la página individual de cada personaje con todos sus detalles.
CharacterItem.js: componente que representa la información básica de un carácter.
CharactersList.js: componente que representa los personajes en la página principal.
FilterByName.js: componente que representa la entrada donde el usuario puede escribir un filtro para el nombre del personaje.
FilterBySpecies.js: componente que muestra las casillas de verificación en las que el usuario puede hacer clic para filtrar por especie.
Filters.js: componente que representa todos los filtros de la página.
Header.js: componente que representa la imagen del encabezado y el título.
PickleImages.js: componente que importa las imágenes utilizadas cuando mostramos una página de error al usuario.
Reset.js: componente que genera un botón que restablece las entradas de los filtros.
🌐Servicios🌐
Para que nuestra aplicación funcione, necesitamos dos servicios:

api.js: contiene la función que llama a la API y devuelve los datos del servidor.
localStorage.js: contiene funciones necesarias para gestionar el almacenamiento local de una forma más sencilla.

Este proyecto se inició con Create React App .

Guiones disponibles
En el directorio del proyecto, puede ejecutar:

npm start
Ejecuta la aplicación en el modo de desarrollo.
Abra http://localhost:3000 para verlo en su navegador.

La página se volverá a cargar cuando realice cambios.
También puede ver errores de pelusa en la consola.

npm run githubpages
Crea la aplicación para la producción en la docscarpeta.
Empaqueta correctamente React en modo de producción y optimiza la compilación para obtener el mejor rendimiento.

La compilación se minimiza y los nombres de archivo incluyen los hashes.
¡Tu aplicación está lista para ser implementada!
