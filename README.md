# Prueba-RA-2-LM

# 1A. Pregunta 
## ¿Por qué NO se centra el texto del h1 en este caso? Explícalo con tus palabras.
Por que le falta un "display: flex;" en el CSS para que funcione el "text-align".

# 1B. Ejercicio - Soluciona de dos formas diferentes
## Debes indicar dos formas diferentes de conseguir que el h1 si quede centrado visualmente en la cabecera.
Utilizar "display: flex;" en el CSS de h1 o utilizar un "display: grid;". Para ambas opciones solo haría falta añadir el display en el CSS que ya tenemos. 

# 1C. Ejercicio – Convertir la cabecera en dos filas
## Sin modificar el HTML, debes conseguir mediante CSS que la cabecera se reorganice.
Se utiliza el "display: flex;" en el CSS para que se vea el texto centrado. Al menú de navegación le aplicamos también en el CSS un "display: flex; align-items: center;". Para separar las filas 30px le ponemos a h1 y a main-nav en CSS "margin: 15px;".
Quedaría así:
".site-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

h1 {
  display: flex;
  text-align: center;
  margin: 15px;
}

.main-nav {
  display: flex;
  align-items: center;
  margin: 15px;
}"

# 1D. Ejercicio – Dar relieve y separación visual al header
##  Se pretende que la cabecera del sitio (.site-header) tenga un aspecto más definido y se diferencie claramente del resto de la página.
Para que la cebcera tenga un color de fondo distinto al resto de la página utilizamos en el CSS de header "background-color: #(el color);", para divir la cabezera del contenido principal podemos añadirle a la cabezera en el CSS "box-shadow: 0 15px 15px #(color);", para que tenga un espaciado interior utilizamos padding y margin en el CSS. 
Quedaría así:
".site-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #(color);
  box-shadow: 0 15px 15px #(color);
  padding: 10px;
  margin: 10px;
}"

# Ejercicio 2 — Reorganización del header con tres elementos
## Ahora debes incluir también el botón del menú lateral dentro del header.
### 2A.
Añamidmos en el HTML un nav con el id SiteMenú y la clase navham, le ponemos "input type = "checkbox" id = "toggle"", "label for = "toggle"", el símbolo ☰, cerramos label, creamos un "div class = "texto"", añadimos el índice y cerramos tanto el div como el nav.
### 2B.
En el CSS añadimos "#toggle { display: none; }" "label { display: inline-block; padding: 10px 15px; cursor: pointer; user-select: none; }" ".texto { display: none; margin-top: 10px; padding: 10px; }" "#toggle chacked ~.texto { display: block; }" ".navham { display: flex; align-items: left; }

# Ejercicio 3 — Miniaturas, zoom y enlace a la imagen original
## En tu galería de imágenes, debes realizar lo siguiente:
### 3A. Crear miniaturas
### 3B. Efecto hover
### 3C. Enlace a la imagen original
<img width="613" height="724" alt="galería" src="https://github.com/user-attachments/assets/75831d79-9ebc-466a-8414-6ccfa35d1ee9" />

# Ejercicio 4 — Informe de evidencias del proyecto (defensa técnica simple)
## 4.1. Introducción

El tema de la página web eran los videojuegos de Five Nights at Freddy 's. He incluido un apartado hablando de la web y explicando un poco de qué tratan los videojuegos de Five Nights at Freddy 's, también he explicado un poco la historia y he añadido una tabla con datos sobre los juegos. He añadido también un apartado de comentarios y un apartado con algunos de mis animatrónicos favoritos (de los principales). Además he incluido un apartado sobre fangames, easter eggs, los libros y sus historias resumidas, las películas y un resumen de lo que tratan y por último algunas colaboraciones de FNAF con tortas marcas. 
Mi idea a la hora de diseñar la página era que tuviese los colores de la pizzería que vemos en el primer juego que son algunos tonos de gris, blanco, negro y rojo. Intente agregar bastantes imágenes y recalcar las palabras importantes en negrita.

## 4.2. Evidencias de HTML5
- header:
<img width="598" height="242" alt="image" src="https://github.com/user-attachments/assets/7ce317e5-e623-494c-b91f-8b2bd0bf899a" />
<img width="603" height="198" alt="image" src="https://github.com/user-attachments/assets/b962ac76-54e2-421b-bc50-172965f670b5" />
Lo he utilizado para poner la información del índice, el título y para poner el Logo de la página web. Luego lo he utilizado para poner los títulos y los subtítulos.

- main: 
<img width="78" height="22" alt="image" src="https://github.com/user-attachments/assets/6393531f-32b8-4554-a5c9-dce39466d44c" />
<img width="602" height="370" alt="image" src="https://github.com/user-attachments/assets/4e539237-499b-44f5-834a-90d620bbc2f7" />
Lo he utilizado para guardar la información de toda la página menos la parte del header, la del índice, la del botón hamburguesa y la del head.

- section:
<img width="222" height="32" alt="image" src="https://github.com/user-attachments/assets/da751329-31fc-460c-9f94-fe818894ab88" />
<img width="601" height="127" alt="image" src="https://github.com/user-attachments/assets/f06c64a6-5740-4061-9987-548344517d2d" />
Lo he utilizado para dividir las distintas secciones donde se encuentra la información.

No he utilizado el footer.

- Menú superior:
<img width="539" height="153" alt="image" src="https://github.com/user-attachments/assets/f22df5d7-b9fe-4ec5-bee0-eb92def483b1" />
<img width="840" height="65" alt="image" src="https://github.com/user-attachments/assets/0c232805-55bf-41d8-ad77-8c6457b6434c" />
Es el índice que se ve en la parte superior de la página justo debajo del título y el logo de la web.

- Menú lateral:
<img width="600" height="211" alt="image" src="https://github.com/user-attachments/assets/350f5329-d0c1-4aeb-8773-016c2c954bb4" />
<img width="844" height="221" alt="image" src="https://github.com/user-attachments/assets/fb7a986b-5003-4b5a-8fd1-630da3f85f2f" />
Es el índice con el botón de hamburguesa. El botón permite mostrar y ocultar el menú del índice.

- Sección Hero:
<img width="600" height="612" alt="image" src="https://github.com/user-attachments/assets/c9e8834a-6e26-4263-8fd7-d2d29e91c2a5" />
<img width="1823" height="920" alt="image" src="https://github.com/user-attachments/assets/c9889ab1-45f2-4c79-949a-865e57f92c88" />
La sección Hero es la sección principal de la página web. Contiene una breve descripción sobre la página web y el tema del que trata y una imágen relacionada con ello.

- Tabla:
<img width="465" height="488" alt="image" src="https://github.com/user-attachments/assets/7d37b841-fd6c-43f6-8adb-e5e3f7394beb" />
<img width="1822" height="230" alt="image" src="https://github.com/user-attachments/assets/5dd05904-682b-4061-9bbe-4879a9e5299c" />
Es la tabla con los datos de los videojuegos y la segunda sección de la página web. Incluye cuantos animatrónicos tiene cada juego, su fecha de lanzamiento y el creador.

- Formulario:
<img width="590" height="289" alt="image" src="https://github.com/user-attachments/assets/b3da468e-cad8-413e-91e7-fd2d0dbc2775" />
<img width="600" height="190" alt="image" src="https://github.com/user-attachments/assets/f8b32d2f-8749-468c-b564-e92b52e06c70" />
Es la tercera sección de la página web. Es un formulario en el que puedes escribir dentro de las casillas blancas.

- Galería de imágenes:
<img width="602" height="590" alt="image" src="https://github.com/user-attachments/assets/ccab342a-af92-4530-9f8f-015320237268" />
<img width="471" height="281" alt="image" src="https://github.com/user-attachments/assets/76616dfc-b490-4f04-b8f2-319bb008cd4f" />
En la galería de imágenes he puesto algunos de los personajes principales y he utilizado CSS para tratar de organizarla.

-Enlaces: 
<img width="426" height="21" alt="image" src="https://github.com/user-attachments/assets/e2517344-f69a-4d05-811c-65b4a6a28cd0" />
He añadido enlaces a las imágenes para que al hacer click en ellas te muestre la imagen en grande.

## 4.3. Evidencias de CSS

- Class:
<img width="358" height="460" alt="image" src="https://github.com/user-attachments/assets/5e55f148-e8bf-457c-9e1f-9e39db337734" />
Trataba de hacer que la galería de imágenes se viera mejor.
<img width="262" height="159" alt="image" src="https://github.com/user-attachments/assets/8ef55b29-41e9-4c68-b7c9-dfde292e3665" />
También lo he utilizado para mejorar el Formulario y para centrar el Logo.

- Pseudoclases:
No he utilizado ninguna.

- Flexbox o Grid:
<img width="186" height="225" alt="image" src="https://github.com/user-attachments/assets/ca0be73c-bd99-4e40-a6f1-0bc112027047" />
Lo he utilizado para modificar la posición de las cosas en la página web.

- Box-shadow:
<img width="306" height="23" alt="image" src="https://github.com/user-attachments/assets/3bc27ff5-bb66-4161-a4f8-34ec2e89f4f8" />
Lo he utilizado para crear una sombra roja alrededor de la página principal y alrededor de las imágenes.

- Estilos del menú:
<img width="258" height="62" alt="image" src="https://github.com/user-attachments/assets/ca70ce24-98d7-4133-88a5-fe3415172468" />

- Resumen:
He intentado que la página se viese mejor visualmente con CSS, añadiendo sombras y colores, además de organizar las cosas de una forma específica.

## 4.4. Fuentes utilizadas

He utilizado la fuente predeterminada por que me gustaba como quedaba en la página web.

## 4.5. Menú lateral: breve explicación

1. ¿Qué ocurre al pulsar el botón?
   Al pulsar el botón se abre la pestaña del menú lateral donde puedes seleccionar a qué parte del proyecto ir.
   
2. ¿Qué clase cambia?
   Cambia la clase texto por que se tiene que ocultar y mostrar cuando se pulse el botón.
   
3. ¿Cómo se mueve el menú con CSS?
   Hemos creado con CSS un botón que al ser presionado activa el texto y al volverlo a presionar lo oculta.

   <img width="314" height="458" alt="image" src="https://github.com/user-attachments/assets/437832db-1f19-45b3-9e40-25617e292d82" />

## 4.6. Conclusión personal

1. ¿Qué has aprendido?
  He aprendido a manejar mejor CSS, a crear un menú lateral que se muestre y se oculte y he averiguado donde suelo fallar.
   
2. ¿Qué te gustaría mejorar?
  Me gustaría mejorar la galería de imágenes ya que ha quedado un poco mal el diseño y me gustaría haber hecho algo más con el Formulario. Además creo que debería haber cambiado la forma de las imágenes de la página web para que estuviesen más redondeadas.
   
3. ¿Qué ha sido lo que más te ha costado?
  Al principio me costó un poco realizar el menú lateral pero al final averigüé cómo hacerlo. Lo que más me ha costado es la galería de imágenes y cuadrarlo todo.
   
4. ¿Qué parte de tu web te gusta más?
  Me gusta como me ha quedado la parte de los libros y las películas con los posters, además me gusta como han quedado los colores que he puesto en la página y como resalta el rojo difuminado con el fondo negro. También me gusta la especie de efecto metálico que he conseguido que tenga al dividir las secciones con hr.
   
