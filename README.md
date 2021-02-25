# Master en CSS
### Aprendendiendo CSS3, Maquetación Web, Responsive Web Design, SASS, LESS, Flexbox, CSS Grid Layout y Bootstrap 4. 
  - Duración: +20h


## Bitácora del curso

### Dia 1: 22.11.2020,		
### HTML5: Introducción 
- Creación de una página web simple.
* Primeros pasos con CSS
- Selectores, Fuentes, colores
  - Herramientas para trabajar con CSS3 (Disponible para Windows)
    - https://picpick.app/en/

- Fuentes personalizadas en CSS
  - Descargar fonts de Google
    - https://fonts.google.com/
    ```
    $ mkdir proyecto/fonts
    $ unzip Charm.zip
    ```
    * Asociar fuente desde CSS
    * Personalizar uso en CSS
	
* Colores en CSS
    * Uso de rgb css generator
      - https://www.css3maker.com/css-3-rgba.html

    * Google color picker
      - https://htmlcolors.com/google-color-picker

* Fondos 
  - Usar imagenes de fondos y patrones

### Dia 2: 23.11.2020
### Modelo de cajas y posicionamiento de elementos

- Margenes, padding, bordes
  	> Importante: Asignar el tamaño apropiado de la caja padre
- Posicionamiento de caja.
  	- usando; div, class y section
  	  > Importante: float: left | display: block
  	- Ventaja del uso de 'clearfix'
- Acomodar cajas en un bloque
  	- Agrupar un determinada cantidad de cajas por filas
* Ejercicio #1: HTML + CSS
  - Maquetar una página con cabecera, menu y contenedor de cajas
  - Sombreado selectivo y bordes redondeado
  - Posicionamiento; Overflows
  	- absoluto y fijos
  	  - z-index: orden de apilado
  	  - position: fixed
  	    > Ideal: Redes sociales / Enlace rápidos

## Dia 3: 24.11.2020
### Continuación 
* Pseudoclases en CSS
* Transicciones
* Animaciones

### Proyecto Web Completo: HTML5 y CSS3
- Maquetación Web
    - Maquetación de la cabecera
  	- Herramienta recomendada por el profesor:
  	  - Extension firefox: 'Web Developer' 
  	  	> Ayuda a obtener medidas en pixeles de secciones de la página
  	  	> ( Acceso: Miscelaneous/Display Ruler )
  	- Barra de navegación: menú, submenues
  	- Barra lateral;  contenido, Formularios

## 25.11.2020, Dia 4: 

### Proyecto Web Completo HTML5 & CCS3: Continuación de la maquetación 
- Secciones/Artículos:
  - contenido, stickers, iconos 
  - Uso de la fuente 'Web simbols'
  - https://www.fontsquirrel.com/
  - https://www.fontsquirrel.com/fonts/web-symbols?q%5Bterm%5D=symbols&q%5Bsearch_check%5D=Y
		    > Útil: cada letra tiene un logotipo o simbolo (svg) sin perder calidad.
		    > Buscar en Glyphs: letra que asocia el icono.
  - Culminación del proyecto: 
    - Footer



### Sección 16:  Introducción al Responsive Web Design

## 30.11.2020, Dia 5: 

### Responsive Web Design con CSS3
- Maquetación con porcentajes
- Media queries
- Viewports
### Proyecto completo con Maquetación avanzada
- desde el diseño PSD/PNG a HTML y CCS
  - Maquetado por secciones: cabecera, Menú, banner, tarjetas, barra lateral
  - Estilos CSS para la secciones

## 2.12.2020, Dia 6:
### Continuación:  Maquetación con CSS

## 3.01.2021, Dia 7
### Animaciones y transiciones avanzadas
- Animaciones para el Logo, Banner y las tarjetas
- Animacion sección Redes sociales y Footer
### Responsive Web Design
- Diseño adaptable en escritorio/tablet
## 9.01.2021, Dia 8:
- Diseño adaptable (continuación)
- Responsive avanzado para tablet/pantallas medianas
- Responsive para smartphones/pantallas de tamaño reducido
- Responsive para pantallas muy pequeñas

## 25.02.2021, Dia 9:
- Aprendiendo Sass
  - Trabajar con Sass usando npm
    - Instalar Node JS
      - Descargar instalable para Windows
      > https://nodejs.org/en/
      - En Linux
      > sudo apt install nodejs
      > sudo apt install npm
    - Abrir la consola de comando
      - Linux
        > sudo npm install -g sass
      - Windows
        > npm install -g sass
    - Compilar el archivo scss y generar el styles.css
        > sass --watch estilos.scss styles.css