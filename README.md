# **PROYECTO DA-DE Florida 2026**

- - -

# <h1 align="center">**`DATA ANALYTICS Y APLICACION PARA LA VIABILIDAD DE RESTAURANT EN FLORIDA, USA`**</h1>

## **Descripcion del proyecto**

"Nuestro proyecto consiste en encontrar ciudades en el estado de Florida, en los Estados Unidos de América, fuera del área de la capital Miami, con condiciones para la localización y apertura de un proyecto gastronómico de calidad internacional que eleve el nivel de la oferta gastronómica general de la ciudad, y que tenga las condiciones para convertir este a proyecto gastronómico en un punto turístico importante de la ciudad, para esto nuestro proyecto va a considerar las reseñas de usuarios de toda la oferta gastronómica del estado de Florida, fuera del área de la capital Miami y conurbaciones, como Fort Lauderdale, Hollywood, Boca Raton y West Palm Beach, estas reseñas nos van a dar una perspectiva de la oferta turística de las diferentes ciudades del estado Florida, excluyendo Miami, para poder decidir la ciudad que tenga el mejor potencial para la realización del proyecto.""

## **Analisis preliminar de los datos**

"Los datos colectados consistian en los datos de google maps, divididos en metadata_sitios conteniendo los datos de diversos comercios de estados unidos en 11 archivos json y review-estados conteniendo los datos de los reviews de los usuarios en 51 carpetas, 1 por cada estado de USA, con varios archivos .json cada uno, el segundo dataset es el de yelp, el primer archivos es business.pkl archivo formato pickle de python que contiene información del comercio, incluyendo localización, atributos y categorías, el segundo es review.json que contiene las reseñas completas, incluyendo el user_id que escribió el review y el business_id por el cual se escribe la reseña, estos son los archivos que se van a usar para el proyecto archivos adicionales se pueden incluir en el futuro 

Se inicia el proceso de EDA al concatenar los 11 archivos JSON en 'metadata-sitios', se procedió a filtrar los 5031 restaurantes en Florida, excluyendo Fort Lauderdale, Miami, Miami Gardens y Boca Raton. De este conjunto, un 88.6% ofrece servicio de entrega a domicilio. La categoría más valorada que acepta tarjeta de crédito es la de Desayuno/Gasolinera/Golosinas. Entre las categorías con mejores puntajes se destacan los restaurantes de pizza, comida mexicana, locales de comida rápida y cocinas estadounidenses. Considerando estos datos, explorar la inversión en un restaurante con estas tendencias puede tener resultados.
.""
