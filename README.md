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
