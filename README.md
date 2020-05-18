# twitter-selectivo

Analisis de Control de Twitter

-Diego Alejandro Malagon Ruiz 20162020098
-Edwin Felipe Quintero Camacho 20162020066

Se establecen los criterios para la determinacion de control de difuccion, se puede hacer esta restrinccion mediante las siguientes opciones que establecemos:

1) Para Seguidores (Amigos)

si se escoge la opcion de seguidores, los unicos que tengran permiso ú acceso al compartimiento o difuccion de dicha informacion seran las personas que se encuntren vinculadas como seguidores al usuario principal (Quien comparte originalmente la informacion)

2) En general (Todo publico)

Si escoge la opcion de general o para todo publico no se restringe el manejo de los demas usuarios sobre dicha informacion

3) Especificado (Cierto grupo de personas en particular)

En la seccion de "Especificados" se concidera generar un estilo de seccion donde el usuario principal a compartir la informaccion escriba una lista detallada de los contactos que desee que puedan compartir sus Twitts, ya sea buscando en su lista de seguidores y seleccionando los que dessee o ingresando algun(os) usuarios en particulares por el correo ó username 

---------------------------------------------------------------------------------------------------------------------------

Para el manejo de Datos y la presentación del tablero de análisis tenemos los siguiente criterios y directivas:

1.Obtención del lapso de tiempo a analizar:

como primera medida el usuario debe ingresar al software el tiempo en el cual desea hacer el estudio, es decir, el usuario ha de escoger un lapso de tiempo para en él examinar los datos del tuit en cuestión y obtener así el pico de visualización además de  la cantidad de RT´s de likes y de comments.

2. Contadores de datos:

 Para la implementación empezaremos con un contador tanto de likes, como de comentarios y RT´s que proveerán la información al usuario al final además de servir como variables de decisión para obtener el pico más alto de visualización. 

3. Función para obtener el pico más alto: 

Esta función va a  tener en cuenta el número de RT´s y el hilo del tuit, ¿Esto por qué? básicamente la cantidad de RT´s refleja una mayor difusión del tuit y el hilo del tuit en general nos ayuda a mantener en tendencia al mismo. Por lo tanto la funcionalidad a implementar es evaluar minuto a minuto durante el tiempo establecido por el usuario las cantidad de RTs y comments para ir descartando picos durante el transcurso del tiempo hasta llegar al mayor. Si el usuario no establece tiempo de análisis, se mostrarán las estadísticas a lo largo de la vida del tuit. 

4.Visualización de datos:

Esta función se encargará de realizar la interfaz y mostrarle al usuario los datos obtenidos, tanto los básicos(RT´s, Likes, Comments) como el momento de mayor visualización, esto gracias a un dashboard o tablero de datos.



