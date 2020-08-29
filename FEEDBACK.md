
# Revisión de Proyecto 


# HTML

Para la parte de HTML los puntos que hay que recalcar son sobre todo las buenas practicas y los requerimientos.

###  Bueno

- Estructura con sentido
- Buena identación

### Malo

- Aunque utilizamos más etiquetas para tener mejor semántica, aún pudimos ocupar otras, como `article`
- No le agregamos `alt` a las imagenes, esto es importante por varias razones, entre ellas tener un mejor SEO y mejor experiencia de usuario

Te recomiendo checar este repo:
[https://github.com/hail2u/html-best-practices#escape-----and--with-named-character-references](https://github.com/hail2u/html-best-practices#escape-----and--with-named-character-references)

Y esta página:
[https://www.w3schools.com/TAGS/default.ASP](https://www.w3schools.com/TAGS/default.ASP)

# CSS

Para esta parte lo que hay que tener en cuenta es el escalamiento de un proyecto y buenas practicas.

### Bueno

- Tenemos una baja especificidad en las reglas
- Usamos buen uso de la compilación de cascada

### Malo

- Tenemos unos cuantos comentarios, pero bien no pudieron estar, deben de ser más explicativos
- Lo tenemos todo en un solo archivo
- Como buena practica los numeros en hexadecimal deben ir en minuscula
- Usamos estilos en etiquetas que no nos permiten tener un buen escalamiento del proyecto. 

Esta página es muy buena para practicar este tipo de cosas.
[https://css-tricks.com/guides/](https://css-tricks.com/guides/)

# JS

### Bueno

- Buena identación
- Buen nombre de variables y funciones

### Malo

- Esta en el archivo HTML, eso por estandar, no debe de ser, debe estar en otro archivo y nadamás se importa ese archivo
- Usamos `var`, debemos de dejar utilizar `var` y sustituirla por ya sea `const` o `let`, dependiendo el caso
- Es más recomendable que utilices `getElementById`, ya que es muy común que las clases cambien


# CONCLUSIÓN

Se ve un avance, aún nos falta, pero si vamos avanzando bien.
Hay que tener mucho en cuenta la modularización de las cosas.
