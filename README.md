-----------

# ![unnamed](https://user-images.githubusercontent.com/117502426/233875095-91593f48-7279-44b4-88eb-9982ec818820.png)

## Descripción del proyecto

- M-BROS LIBRARY
- Versión del proyecto
- Versión 1.0

Libreria pensada para el estudio de los componentes de CSS y HTML, la cual fue hecha con tematica de MARIO-BROS, teniendo así una librería creativa dónde podremos aprender mas de la documentación principal de CSS y HTML.

 La libreria MBbros es una libreria creada a nuestra creatividad, inspirandonos en los colores del mundo de Mario Bros.
 En ella se esncuentran clases para crear elementos, ala vez clases utilarias la cual modifica, crea, para colores etc.
 
 Para poder implementar su libreria en su entorno de desarrollador debe seguir los siguientes pasos:
 GIT
 
  - Inicie sesion en GitHub
 - Dirigase a su consola GIT - BASH y coloque el codigo que se muestra a continuacion 
 
 
 ``git clone https://github.com/usuario/MBROS_LIBRARY``
 
 - En breve se clonara el repositorio para que lo pueda usar en su entorno de desarrollo
 
 Para poder visualizarlo desde su dispositivo debe ingresar al enlace del repositorio que se presenta a continuacion: 
 
 `` https://edraslazov.github.io/MBROS_LIBRARY/``


A continuacion se presentaran una seria de ejemplos con su respectivo codigo:


# INICIO
![5ad63907-b5e5-4f0e-bc9f-2b3e348bc3cf](https://user-images.githubusercontent.com/117502426/234311220-c8ac2c0d-7187-4a40-b97c-d3ed50ec3cf4.jpg)





# FLEXBOX-END
![1db162d3-8502-45b0-8e72-1ee70421457f](https://user-images.githubusercontent.com/117502426/234310450-e3216e11-1524-48ef-b5e5-3cc0dd57efec.jpg)




# BARRAS DE NAVEGACION
![214c3be6-9ac4-438e-af31-a57119996a71](https://user-images.githubusercontent.com/117502426/234310519-6f7c701d-e065-4b38-8019-c287a93718a1.jpg)




# ALERTAS
![4cdc4760-0f87-4013-8ea9-b16f117f6001](https://user-images.githubusercontent.com/117502426/234310671-718f8fa3-16ac-4344-a9e0-39737939fad5.jpg)



# BADGES
![a5ea559a-7fb1-41a9-b71a-4bcd2005286a](https://user-images.githubusercontent.com/117502426/234310728-0cec5917-fce0-451a-88c9-3f9efeed7046.jpg)



# TARJETAS
![fe1510f1-e548-4be9-ace8-584a938f6763](https://user-images.githubusercontent.com/117502426/234310791-6028bf5c-40ff-48b6-8fe8-739a44e38062.jpg)


 
 
## DESCRIPCION DE USO DE LIBRERIA
                    
Libreria botones  | Definicion
------------- | ----------------
mb-btn1  | Boton de tipo peqeño
mb-btn2  | Boton de tipo mediano
mb-btn3  | Boton de tipo normal
mb-btn4  | Boton de tipo grande



|                                      Tarjetas y alertas  
| ------------- 
| Se crearon mediante las clases definidas en nuestra libreria|

|                                    Barras de navegacion 
| ------------- 
| Se crearon mediante las clases definidas en nuestra libreria|


Libreria badges    | Definicion
-------------      | ----------------------------------------------------------------
badges-secondary  | es utilizada en el badges de tipo titulo
badges-button1  | es utilizada en el badges de tipo boton con notificacion
badges-espacio-badges-primary -pill  | se manda a llamar el badge pill o tipo pastilla 

Libreria Modificacion de tamañy grosor de texto | Definicion
------------- | ---------------------------------------------------------------------------------------------------------------------------
mb-fun-10  | Hace referencia al tamaño 10, la cual se puede utilizar llamando otros tipos de numeros segun el requerimiento que se desee

Libreria asignar sombras    | Definicion
-------------      | --------------------------------------------------------------------------------------------------------------------------------------------------
mb-heavy-shadow  | se utilza para sombrear los elementos con el elementos shadow
mb-shadow-10px | Ambas se utilizan para crear sombras, el px que observamos es para hacer referencia al tamaño del sombreado que necesite. Nota: no necesariamente se  tiene que colocar el px.

Libreria margin   | Definicion
-------------      | --------------------------------------------------------------------------------------------------------------------------------------------------
mb-m-, mb-mt-, mb-mr-, mb-mb-, mb-ml-  | Clases que se utilizaran para colocar los margin, podra usarse mediante las clases, y asignando un numero despues del guion de la clase para definir su tamaño

Libreria padding   | Definicion
-------------      | ------------------------------------------------------------------------------------------------------------------------------------------------
mb-p-, mb-pt-, mb-pr-, mb-pb-, mb-pl| Clases que se utilizaran para colocar los padding, podra usarse mediante las clases, y asignando un numero despues del guion de la clase para definir su tamaño

Libreria border   | Definicion
-------------      | ------------------------------------------------------------------------------------------------------------------------------------------------
mb-border-: solid, dashed, dotted, double, groove | Para utilizar cada border se tiene que inicializar con mb-border, un ejemplo seria este: mb-border-double; 

Libreria Flexbox  | Definicion
-------------      |------------------------------------------------------------------------------------------------------------------------------------------------
mb-Flexbox  | Inicializa la clase Flexbox, donde utilizamos align items y justify content, usandose como mb-Flexbox la clase principal para poder llamar las subclases que se encuentran dentro


Libreria RedondearElementos | Definicion
-------------      | ------------------------------------------------------------------------------------------------------------------------------------------------
mb-br-, mb-brpx-  | Donde tenemos mb-br-, se utiliza mediante porcentajes, y mb-brpx se utiliza mediante pixeles que se pueden colocar segun medida que se requiera

Libreria OcultarElementos | Definicion
-------------      | ------------------------------------------------------------------------------------------------------------------------------------------------
mb-high, mb-invisble, mb-inline | Se utiliza para ocultar elementos, para omitir enlaces, y quitar bordes, y quitar elementos y que se mantenga el espacio asignado
   mb-none-cir  mb-sub-none |  Se utiliza para ocultar elementos, para omitir enlaces, y quitar bordes, y quitar elementos y que se mantenga el espacio asignado
   
  Libreria colores  | Definicion
-------------     |------------------------------------------------------------------------------------------------------------------------------------------------
mb-letraf-rojo     | Ejemplo de clase utilizando el color rojo, se le ira dando el color segun la clase que se decida, y se define si es neutro, fuerte o suave, segun las iniciales, en este apartado es especificicamente para letra 
mb-bg-rojo-s    | Ejemplo de clase utilizando el color rojo, se le ira dando el color segun la clase que se decida, y se define si es neutro, fuerte o suave, segun las iniciales, en este apartado es especificicamente para background.






 
 A continuacion se presenta un codigo para crear un elemento lo que es un bton

```html 
<button class="mb-bgamarillo-s mb-brpx-25 mb-letraf-blanco mb-font-Verdana-15px" style="height: 40px; width: 180px; cursor:pointer">NORMAL</button> 
```


Este código HTML define un botón con las siguientes características:

La clase del botón se establece como ```"mb-bgamarillo-s mb-brpx-25 mb-letraf-blanco mb-font-Verdana-15px"```

El estilo del botón se define con una altura de 40 píxeles y una anchura de 180 píxeles.
El cursor del botón se establece en "pointer", lo que indica que el cursor cambiará a una mano cuando se mueva sobre el botón, lo que indica que es un elemento interactivo.
El texto dentro del botón se establece como "NORMAL". Este texto se mostrará en el botón y se utilizará para identificar el propósito del botón.

Formulario
```html
<form action="">
          <label for="Usuario">Usuario:</label>
          <input type="text" id="Usuario" name="Usuario" required>
            <!--formulario de ingreso de contraseña-->
          <label for="password">Contraseña:</label>
          <input type="password" id="password" name="password" required>
            <!--formulario de ingreso de correo-->
            <label for="email">Email:</label>
          <input type="email" id="email" name="email" required>
            <!--formulario de ingreso de fecha-->
            <label for="fecha">Fecha:</label>
          <input type="date" id="fecha" name="fecha" required>
            <!--formulario de ingreso de hora-->
            <label for="hora">Hora:</label>
          <input type="time" id="hora" name="hora" required>
            <!--formulario de ingreso de color-->
            <label for="color">Color:</label>
          <input type="color" id="color" name="color" required>
            <!--formulario de ingreso de rango-->
            <label for="rango">Rango:</label>
          <input type="range" id="rango" name="rango" required>
            <!--formulario de ingreso de telefono-->
            <label for="telefono">Telefono:</label>
          <input type="tel" id="telefono" name="telefono" required>
          <input type="submit" value="Enviar">

        </form>
        ```
        
        
Una de las caracteristicas importantes de esta pagina web, es que podemos visualizar y ejemplificar codigo en la pagina, a continuacion se presentan los disntintos temas aplicados .

Clases utilitarias: 
Las clases utilitarias usadas estan llamadas directamente en la carpeta "Estilos", dentro de la librería, donde se uso una gran variedad de clases para poder llegar a tener la pagina web que observaran.











#  INTEGRANTES: 
##### Waldir Vasquez Rosa  VR19030
##### Edras Ariel Viera Lazo Vl20011
##### Andres Isai Vasquez Vasquez VV18009
