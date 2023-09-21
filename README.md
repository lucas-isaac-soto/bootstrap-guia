# Bootstrap Guia

### Motivo de esta guia.
Hago esto ya que me interesa aprender una tecnologia nueva que me ayude a poder estilizar sitios web de manera responsive con poco esfuero.  
Pienso que podre utilizar bootstrap para agilizar el estilo de mis etiquetas HTML evitando poner un esfuerzo significativo en el desarrollo de archivos de estilos extensos y ademas, me da la posibilidad de incluir estilos especificos donde crea que son necesarios.

---

### Introduccion a Bootstrap.

#### Que es bootstrap:
Boostrap es una biblioteca tambien llamado framework, de estilos css y funcionalidades js, incluso teniendo un apartado para iconos.  
Este fue creado por Twitteren 2005 para poder definir un estandar de estilos en la web.

#### No es la unica herramienta:
Asi como Boostrap existen otras bibliotecas como   
- Bulma
- Tailwind
- etc.

---

### Como iniciar en Bootstrap.
Gracias a la buena documentacion de Bootstrap contamos con una seccion para poder iniciarnos en el proceso de uso de esta herramienta.  
Link a bootsrap introduccion: [Bootsrap Introduccion](https://getbootstrap.com/docs/5.3/getting-started/introduction/ "Bootsrap Introduccion")  

---

### Como utilizar Bootstrap en nuestros proyectos.
Podemos utilizar Bootstrap atravez de la CDN (Content Delivery Network), esta es una tecnica la cual distribuimos recursos de internet con el solo hecho de estar conectado a internet.  
A fin de cuenta Bootstrap son solo archivos css y js nosotros podemos descargar estos e importarlos de forma local o con la CDN la cual los descarga de internet.  

Al usar la CDN la ventaja es que estos archivos ya no los mantendremos en nuestro disco y siempre descargaremos la version mas reciente si esta cambiase, como aspecto negativo si no llegamos a tener internet estos archivos nunca se cargaran ademas de agregar demoras en tiempo de cargas al tener que realizar la peticion para traer estos estilos.  

---

### Que esperar de Bootstrap
Algo importante a tener en cuenta es que no es necesario conocer al 100% todas las clases que maneja Bootstrap, por ello vamos a aprender las mas utilizadas y aquellas que son particulares siempre tenemos la documentacion de Bootstrap para consultarla.  

---

### Aspectos importante a tener en cuenta de Bootsrap al utilizarlo.
Bootstrap divide la pantalla siempre en 12 secciones (columnas) a lo largo de nuestra pantalla, y permite especificar cuantas columnas nosotros le asignaremos a cada elemento incluso cuando la pantalla cambie, algunas palabras claves que nos interesara son:

| keyword | significado       |
| ------- | ----------------- |
| sm      | small             |
| md      | medium            |
| lg      | large             |
| xl      | extra large       |
| xxl     | extra extra large |

<br></br>
Bootstrap trabaja con clases llamadas **container**, son clases para contener elementos de forma muy general.  
Esta nos permite dividir la pantalla teniendo espacio a la isquierda y derecha para poder centrar el contenido en el medio de forma sencilla. Sin tener importado Bootstrap todo lo que hagamos no funcionara, normalmente trabajaremos con tag **div**.  

Dentro de estos **contenedores** trabajaremos con un espacio horizontal los cuales seran tag div que usan la clase **row** (Fila).  
Podemos tener multiples Filas dentro de un container.  

Si nosotros agregamos elementos dentro de esta clase fila, los elementos se mostraran con su display original sea block o inline.  

Para ello podemos hacer uso de columnas, cada fila puede tener a lo sumo 12 columnas, las cuales mencionamos antes que es la predefinida por bootstrap. Ademas podemos especificar con la tabla anterior cuando la pantalla cambie cuantas le asignaremos simplemente agregandole mas clases.  

A lo largo de los ejercicio que vamo a hacer haremos uso de basta variedad de estas clases de bootsrap para aprender todo lo que podemos llegar a hacer. 

# **EMPECEMOS**
