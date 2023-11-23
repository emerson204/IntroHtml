## ETIQUETAS

<etiqueta> </etiqueta>

1. Las etiquetas son elementos que permiten estructurar el codigo HTML y pueden ser de dos tipos

   1.1 De apertura y Cierre -> La mayoria de etiquetas utilizan esta sintaxis, que indican un inicio y un final de la etiqueta

      <h1>Soy un encabezado</h1>
      <p>Soy un parrafo</p>

   1.2 Self-Closing( no necesitan cierre ) -> Solo en algunas etiquetas se utiliza esta sintaxis osea no tiene otra segundo etiqueta que indique es el cierre
   <img />
   <input />

   1.3 Etiqueta de Bloque -> Son aquellos que ocupan todo el espacio de ancho y eso hace que cada elemento bloque funcione poniendose uno debajo de otro
   <h1></h1>

   1.4 Etiqueta de Linea -> Son aquellos que solo ocupan su espacio necesario y pues funciona poniendose uno a lado de otro
   <span></span>

   -NOTA : Pues tanto como etiqueta de linea y bloque lo puedes modificar con CSS , tanto como un elemento de linea lo puedes convertir en bloque y viceversa

2. Pueden tener atributos -> Los atributos pues añaden informacion adicional a la etiqueta , es muy importante en algunas etiquetas ya que es necesario tener atributo para que funcione correctamente , como tambien pueden ser no necesarios en algunas etiquetas

<h1 atributo="valorAtributo">Soy un encabezado</h1>

2.1 Opcionales -> Es opcional porque asi le pongas o no atributo, pues sigue funcionando igual

  <p class="parrafo">Soy un parrafo</p>

2.2 Obligatorio -> Es obligario porque sin su ruta de la imagen no tendria sentido poner esa etiqueta
<img src="ruta" alt="mensaje de accesibilidad"  />

3. Encabezados -> Los encabezados son importantes para poner titulo o subtitulos , y tienen un orden la cual es importante seguir . Tenemos 6 tipos de encabezados

IMPORTANTE : Tienes que seguir el orden , no puedes poner un h1 y luego saltarte a un h3 , eso es incorrecto , tienes que poner un h1 luego h2 y asi sucesivamente segun sea necesario

<h1></h1> -> Es el titulo principal y solo debe de haber un solo H1
<h2></h2> -> Pueden haber varios h2 y asi varios en los otros encabezados 
<h3></h3> -> Pueden haber varios h3 y asi varios en los otros encabezados 
<h4></h4> -> Pueden haber varios h4 y asi varios en los otros encabezados 
<h5></h5> -> Pueden haber varios h5 y asi varios en los otros encabezados 
<h6></h6> -> Pueden haber varios h6 y asi varios en los otros encabezados
