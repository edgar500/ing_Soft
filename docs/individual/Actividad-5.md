<div style="display: table;">
    <div style="width: 75%;float: left;margin: auto;padding: 50px 0px 50px 10px; float: left;">
        <span style="color: black;font-size: 25px;font-weight: bold;">UNIVERSIDAD NACIONAL AUTÓNOMA DE MÉXICO</span></br></br>
        <span style="color: black;font-size: 26px;">FACULTAD DE ESTUDIOS SUPERIORES ACATLÁN</span>
    </div>
    <img src="/archivos/index/fesa.png" alt="drawing" width="200" style="width: 25%;"/>
</div>

&nbsp;

# Actividad 5

## Siles Ochoa Edgar Jair


### ¿Qué es JSON y XML?

![Mi Imágen](/archivos/individual/actividad-05/XvsJ.jpg)

###

### JSON (JavaScript Object Notation):

![Mi Imágen](/archivos/individual/actividad-05/JSON.jpg)

Cuando hablamos de Jason, hablamos de un formato de intercambio de datos, este formato tiene la característica de ser muy fácil de entender para el programador, tanto en su lectura y su escritura y para la máquina (computadora), resulta fácil de interpretar y generar. Este formato se caracteriza por contener solo texto derivado de JavaScript y utilizan la extensión .json, por centrarse más en el contenido que en el formato lo cual es muy útil cuando se trata de mantener los datos de intercambio lo más compactos posibles. 

### AJAX (Asynchronous JavaScript and XML):

Jason es la opción ideal para trabajar con AJAX. JavaScript asíncrono y XML permite que las aplicaciones web funcionen de forma asíncrona, esto permite que las solicitudes que se realicen al servidor se ejecuten en segundo plano, es decir que los cambios ocurren en tiempo real sin necesidad de que la página o la aplicación se refresque o cargue con cada solicitud hecha a la base de datos.
La mayoría de sitios web hoy en día están adaptados a AJAX, y también podemos solicitar datos de un dominio diferente con el método JSONP.
JSONP es una extensión de JSON que permite la integración de etiquetas Script.

### Elementos  de JSON:

Está conformado por dos elementos claves:

Keys, son cadenas de caracteres.

Values, son tipos de datos válidos (arreglo, objeto, cadena (string), booleano, número o nulo.).


### Características de JSON:

-Es un formato de datos.
-Requiere comillas dobles para las cadenas.
-Puede tomar cualquier forma de datos válida que requiera.
-Solo las cadenas que están entre comillas pueden ser consideradas como propiedades.


### XML(Extensible Markup Language):

![Mi Imágen](/archivos/individual/actividad-05/XML.jpg)

El lenguaje de marcado extensible define un conjunto de reglas para la codificación de documentos, tiene la característica de ser muy similar al lenguaje HTML, proporciona una plataforma para definir un formato y generar un lenguaje personalizado. Los archivos XML se componen de etiquetas las cuales nos aportan datos que queremos procesar, estas etiquetas pueden ser individuales o anidadas. 
Este lenguaje es muy simple y fácil de emplear, sigue un estándar para la comunicación de datos entre dispositivos mediante redes, la desventaja es que XML es muy pesado ya que contiene muchos caracteres relacionados con su formato, se puede compactar a conveniencia pero JSON suele ser mejor opción en ese caso.

### Características de XML: 

-XML puede ser usado para volver más dinámico HTML ya que los datos se pueden almacenar en un archivo XML y utilizar HTML para la visualización y el diseño. 

-XML simplifica el intercambio de datos , ya que se almacena como formato de texto y nos permite almacenar los datos de forma independiente.

-XML se utiliza como base para crear nuevos lenguajes de internet.


### Cuadro comparativo:

![Mi Imágen](/archivos/individual/actividad-05/cuadro.jpg)


### Ejemplos: 

### JSON:

####

"menu": {
        "id": "file",
        "value": "File",
        "popup": {
            "menuitem": [
                {
                    "value": "New", "onclick": "CreateNewDoc()"
                },{
                    "value": "Open", "onclick": "OpenDoc()"
                },{
                    "value": "Close", "onclick": "CloseDoc()"
                }
            ]
        }
    }
}


### XML:

 < menu id="file" value="File" >
    < popup >
      < menuitem value="New" onclick="CreateNewDoc()" />
      < menuitem value="Open" onclick="OpenDoc()" />
      < menuitem value="Close" onclick="CloseDoc()" />
    < /popup>
  < /menu> 


### Fuentes:

https://www.hostinger.mx/tutoriales/que-es-ajax 

https://www.arnoldgutierrez.com/xml-vs-json-servicio-web-cual-ellos-mejor-opcion/

https://www.nextu.com/blog/que-es-json/

https://www.hostinger.mx/tutoriales/que-es-json

https://rockcontent.com/es/blog/que-es-xml/

https://openwebinars.net/blog/que-es-xml-y-para-que-se-usa/

