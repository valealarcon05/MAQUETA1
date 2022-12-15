# Estado de los archivos:
U: untracked files(git sabe que está pero no tiene registro)
M: modifed(git sabe que está ahí pero sabe que está modificado)
A: added (agregado)[cuando se pone git add . (se agregan todos los archivos), sino git add <archivo>]
para subir: git push -u origin (se sube a la rama main)
probe nuevamente con git push solo y se subió correctamente
# cambio en index, agrego html5
luego de colocar html5, se coloca el bootstrap(cosas interesantes) en head y el javascript(abr ventanas modales) en body y el fontoawesome en html(agrga iconos)
## para html:
los <h1-6> sirven para encabezados
los <p> sirven para cuerpo o párrafo
<span> sirve para separar parte de un párrafo de otro
<b> sirve para texto en negrita<b>
<u> se subraya el texto<u>
<strike> se tacha el texto<strike>
<strong> destaca texto más que negrita(<b>)<strong>
el <i> marca con cursiva o itálica<i>
el <br> marca salto de línea de texto<br>
con <tt> se escribe en fuente donde todas las letras tienen igual tamaño
las fuentes<tt>: <font> agrega estilo, tamaño y color al texto específico<font> y <basefont> configura todo el texto del mismo estilo(casi no se usan)<basefont>
<em> marca con énfasis el texto<em>
<li> para cada elementode la lista<li>
<ol> listas ordenadas, con <ol type="a,A,I,1"> es el tipo de letra d inicio y con <ol reverse> da la lista ordenada al reves y con <ol start="..."> indicas donde empieza la lista
con <ul> se da una lista desarmada y con <ul type> algunos modos
<div> se usa para contener otros elementos HTML y con CSS se usa para agregar formato a un bloque de contenido
con <img src = "imagen.png" alt="descripción imagen"> es elemento vacío para poder desplegar una imagen web, por src da el nombre de la imagen y por alt la descripción de la imagen
el <a href="URL(con o sin dominio)"></a> crea un enlace a otra paginas web o URL
los enlaces pueden ser de 3 tipos: internos(mismo dominio), externo(otra pag web) o de posición(mismo lugar pagina, lugar concreto de otra pagna)
el elemento <meta> se usa pra dar info adicional importante del doc: incluir pares de nombre - valor que describen las propiedades del documento HTML, como el autor, la fecha de caducidad, una lista de palabras clave, el autor del documento, etc.
el <iframe> aparece en cualquier parte del doc y define una región rectangular dentro del doc para mostrar un doc separado
HTML5:
elementos semánticos(con significado):
<header>: especificar contenido de tipo introductorio o un conjunto de enlaces de navegación(encabezados, logo, autoría)
<nav>: sección de una pagina para proporcionar enlaces de navegación
<section>: Una sección es una agrupación temática de 
contenido, normalmente con un encabezado
    <article>.... <aside>(contenido indirectamente relacionao con el principal)
</section>
<footer>..</footer>: pie de página
<form>
<table>
<article>: específica contenido autónomo e independiente
<body> bgcolor: : establece un color para el fondo de la página.
● text: establece un color para el cuerpo del texto.
● alink: establece un color para los enlaces activos o los enlaces seleccionados.
● link: establece un color para el texto vinculado.
● vlink: establece un color para los enlaces visitados, es decir, para el texto vinculado en el que ya ha hecho clic
====
CSS: define conjunto de reglas que permiten describir cada parte que componen estilos CSS, para cambiar los valores predeterminados en html
h1 {propiedad(https://carontestudio.com/blog/listado-de-propiedades-css/) : valor de la propiedad}
selector: se le asigna estilo personalizado
    universal: selecciona todos los elementos de la página
    de tipo o etiqueta: selecciona los elementos de la página que etiqueta HTML coincide con el valor del selector
    descendente: seleciona los elementos que se encuentran dentro de otros
declaración: : especifica los estilos que se aplican a los elementos:
        p span(elemento descendiente) { propiedad: valor;}(selecciona todos los textos)
        h1 span {propiedad: valor;}
para destacar solo un párrafo específico se indica el párrafo desde html por <p class="destacado">...</p> y luego en css .destacado{color:blue;}
para vincular html de css se usa en index.html en <head> con <link rel="stylesheet" href="styles.css">