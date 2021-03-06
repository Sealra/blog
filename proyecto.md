---
layout: post
---

16:00 - 31/10/2020

Esto es un blog para el proyecto de Introducción a la Ingeniería, curso de la Universidad Técnica Federico Santa María.

Nuestro proyecto será realizado por un equipo de 3 personas, las cuales son:

- Sebastián Alvarado, estudiante de primer año de Ingeniería Civil Informática.
- Franco Araya, estudiante de primer año de Ingeniería Civil Informática.
- Lucas Saavedra, estudiante de primer año de Ingeniería Civil Informática.


La idea principal del proyecto consistirá de una aplicación, la cual recibirá la canción que estemos escuchando en el momento en Spotify,
con el fin de ser traducida al Español (si es que la letra original de la canción está en otro idioma) presionando un botón,
posteriormente la letra ya traducida será mostrada en pantalla.

13:17 - 07/11/2020

Decidimos que será una aplicación "móvil", la cual sea capaz de traducir la canción que estés escuchando en ese momento en Spotify.
De esta manera, ayudar a personas que no hablen inglés, a entender las letras de sus canciones favoritas.

En su interface el usuario verá el nombre del artista y la canción que esta escuchando en el momento, también incluirá un botón para 
llevar a cabo la traducción.

Para este proyecto, utilizaremos React Native y nos apoyaremos en 3 API’s, la API de Spotify, la API de Google Translator y la API de musixmatch.

Existen aplicaciones similares, como musixmatch y Google Translator, pero nuestro proyecto busca juntar estas aplicaciones con el fin 
de facilitar aún más la traducción de las canciones.

Esta aplicación traducirá las canciones de manera eficiente, y con pocos pasos, haciéndola cómoda para el usuario.

15:26 - 10/11/2020

Se realizo la primera retroalimentacion dirigida por la profesora, como grupo extraimos de la conversacion las siguientes ideas para el programa:

- Opciones de valoracion para las traducciones. 

- Juegos interactivos opcionales (estos todavia no se encuntran bien definidos pero estaran relacionados directamente con las palabras de contenga la cancion).

- Recomendaciones de canciones del mismo artista que el usuario estaba escuchando.

17:00 - 21/11/2020

Este proyecto será realizado en React Native, haciendo uso de 3 API’s (Spotify, Google Translator y Musixmatch) y, además, una base de datos (la cual será Amazon Web Services). 

 

Esta aplicación cumplirá con las siguientes características: 

- Mostrar qué canción se está escuchando en el momento. 

- Poder traducir las canciones de manera directa con Spotify. 

- Recomendar canciones del mismo artista. 

- Poseerá un “juego” que consistirá en que se seleccione una palabra, y el usuario tendrá que escoger entre 4 opciones el significado de la palabra en cuestión. 

- Poseerá un “juego” que consistirá en que se seleccione una palabra, y el usuario tendrá que escoger entre 4 imágenes cuál es la correcta. 

Planificación:  

Primera meta: Se espera que para el sábado 28 de noviembre ya hayan sido conectadas las API’s de Spotify, Musixmatch y Google Translator con la app. 

Segunda meta: El viernes 4 de diciembre la meta que esperamos lograr es la creación de la interfaz para la app (dentro de la interfaz consideramos el botón de traducir, las recomendaciones de canciones y la visualización del nombre de la canción escuchada), además, esperamos como meta adicional haber empezado con los primeros avances de uno de los juegos. 

Tercera meta: Para el sábado 12 de diciembre, esperamos ya tener terminado el primer juego (este es el de elección del significado de la palabra) y el segundo (este consiste en elegir la imagen asociada a la palabra seleccionada) ya terminado. 

Cuarta meta: Será para el sábado 19 de diciembre y tendrá como finalidad poder revisar y arreglar los detalles estéticos que necesite la app, es decir, esperamos tener una interfaz más “bonita” para los usuarios. 

 

También ha sido agregado al Github evidencia de que ya ha sido instalado React Native y podemos correr aplicaciones en nuestros dispositivos móviles. 

Link en donde se encuntra la evidencia 1 y 2 : https://github.com/Sealra/blog

18:53 - 28/11/2020 

Como grupo consideramos la idea de realizar un cambio de formato en el proyecto debido a que luego de investigar más a fondo he intentar repetidas veces la conexión con la API de Spotify no se lograba hacer la conexión de manera correcta, además casi toda la información que pudimos encontrar con respecto a las implementaciones de las APIs (Spotify, Musixmatch y Google Translator) se encontraban dirigidas a React y el desarrollo web, es por esto que se le planteo la idea al ayudante de dirigir el proyecto hacia el desarrollo web, descartando la idea de hacer una aplicación como se pensó en primera instancia.

20:52 - 28/11/2020

Se redactó un correo digirió a la profesora del paralelo 1, en donde se le informó del cambio que se quería realizar con respecto al proyecto (pasar de una aplicación a página web) y también se aclaraba en el correo que las funcionalidades planteadas en la primera entrega se mantendrían en su totalidad.

21:04 - 29/11/2020

Se logró realizar con éxito la conexión entre la API de Spotify y la página web, como evidencia del progreso del proyecto se subió el avance de la primera conexión al repositorio en la carpeta lyricsfy.

Además se empezó a trabajar la conexión con la API de Musixmatch.

Link en donde se encuntra la carpeta Lyricsfy con el código con el progreso: https://github.com/Sealra/blog

02:54 - 07/12/2020

La conexión con la API de Musixmatch y la pagina se establece con éxito, logrando que la letra de la canción que este escuchando el usuario aparezca en la página cabe destacar que la traducción de la letra no está integrada todavía, pero se empezara a trabajar en esa función.

También se destaca que se planteó la posibilidad de utilizar el i18next (framework de internalización y localización) como herramienta para traducir las canciones.

22:31 - 07/12/2020

Para la traducción de las letras se decide utilizar la API Translator Texts de Microsoft Azure, este cambio se debió a que se presentaron problemas a la hora de registrarnos para obtener el acceso a la API (se dejará la evidencia n°3 para mostrar el problema en el repositorio), ante esto como una solución alternativa se optó por usar la API mencionada anteriormente, ya que cumple con las misma características de la API de Google Translator como por ejemplo su detección de idiomas, permisos de usos gratuitos de la API, es decir, se puede llamar varias veces a la API de forma gratuita y amplia variedad de idiomas que se pueden traducir 

(Cabe destacar que la API de Google nos entregaba mayor acceso a diferentes idiomas (alrededor de 100 idiomas) en comparación de la API de Microsoft Azure (alrededor de 70 idiomas) pero como el proyecto se enfoca en el inglés esta diferencia fue ignorada).

Se dejará la evidencia n°4 para demostrar el funcionamiento y desarrollo del proyecto hasta la fecha.

Link del repositorio en donde se encuentra la evidencia n° 3 y 4: https://github.com/Sealra/blog

23:00 - 12/12/2020

Fue realizada la entrega N°2 del proyecto, se grabó el video (que puede ser encontrado en el siguiente link: https://www.youtube.com/watch?v=sScvKTpBUUw), y además, se subió el código a el siguiente repositorio: https://github.com/Sealra/lyricsfy, recomendamos encarecidamente leer el README.

17:50 - 19/12/2020

Para la entrega N°3 del proyecto, ha sido agregada la funcionalidad de que se recomienden las 10 canciones más populares del artista que estes escuchando, además, el código ha sido ordenado, con la finalidad de facilitar la compresión, por lo cual, el repositorio con el código también ha sido actualizado (https://github.com/Sealra/lyricsfy). La evidencia se encontrará en el repositorio de este mismo blog (https://github.com/Sealra/blog), en la carpeta "evidencia 19-12-2020".

Por otra parte, para mejorar la visibilidad de el repositorio del blog, se creó la carpeta "evidencia entregas pasadas" que contiene las evidencias anteriores del repositorio.

23:46 - 23/12/2020

Se realizó la 3ra entrega del proyecto, subiendo el vídeo a Youtube en el siguiente link: https://www.youtube.com/watch?v=LQma6Ap1yfY

