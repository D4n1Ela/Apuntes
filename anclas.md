### *Anclas* ###


***Consigna***

*En una única página indexamos los items de la lista con el título de la sección del texto que se quiere mostrar: Al hacer click en el item la página se posiciona de forma automática, con esto se evota la utilización del scroll y el buscador.*

***Condiciones***

- *La página tiene un listado: Realizar al menos 4 items.*
- *El texto que le corresponde estará en un contenedor **div**.*
- *El texto tiene que ser extenso de forma que genere un scroll en la página.*
- *En cada **div** de texto habrá un ancla que posicione el layout en el menú de la página.*


&nbsp;

    <!DOCTYPE html>
    <html>
    <head>
        <title></title>
    </head>
    <body>
        <div>
            <a name="contenido" ></a>
            <h1>Contenido</h1>
                <ul>
                    <li><a href="#noticias">Noticias</a></li>
                    <li><a href="#productos">Productos</a></li>
                    <li><a href="#referencias">Referencias</a></li>
                    <li><a href="#nextPage">Next Page</a></li>
                </ul>
        </div>

        <div>
            <a name="noticias"></a>
            <h2>Noticias</h2>
                <p>Texto Extenso...</p>
            <a href="#contenido">Volver Arriba</a>
        </div>

        <div>
            <a name="productos"></a>
            <h2>Productos</h2>
                <p>Texto Extenso...</p>
            <a href="#contenido">Volver Arriba</a>
        </div>

        <div>
            <a name="referencias"></a>
            <h2>Referencias</h2>
                <p>Texto Extenso...</p>
            <a href="#contenido">Volver Arriba</a>
        </div>

        <div>
            <a name="nextPage"></a>
            <h2>Next Page</h2>
                <p>Texto Extenso...</p>
            <a href="#contenido">Volver Arriba</a>
        </div>

    </body>
    </html>



### *Observaciones* ###

1. ***Para vincular el item con la sección***

> *En la lista del menú la etiqueta <a> tendrá en el atributo **href** como valor el **#** seguido del nombre del ancla.*

        <li><a href="#noticias">Noticias</a></li>
    
    
&nbsp;

2. ***Arriba de cada elemento h se codea:***

        <a name="nombreSeccion"></a>
    
> *Es importante recordar que el valor que contiene el **atributo name** y el **valor que tiene el atributo href** de la lista **coincidarán** exceptuando el **#**.*


&nbsp;

3. ***Se codea lo siguiente para volver al menú.***

        <a href="#contenido">Volver Arriba</a>
   
> *Se coloca al final de cada sección.*